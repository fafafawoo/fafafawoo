import akshare as ak
import pandas
print("请输入股票代码，例如‘603259’")
dm = input()
print("请输入开始日期，例如‘20181001’")
st = input()
print("请输入结束日期，例如‘20211001’")
ed = input()
a = ak.stock_zh_a_hist(symbol=dm, period="daily", start_date=st, end_date=ed, adjust="qfq")
a.to_excel('股票数据.xlsx', sheet_name='Sheet1')
