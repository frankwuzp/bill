# bill
账单转换器：将支付宝、微信到处的 .csv 账单转为为记账软件（homebank）可识别的 .qif 文件。

## 使用方式

```
git clone <仓库地址>
cd bill
# 创建两个新文件
mkdir csv qit 
npm install

# 导入支付宝账单后（命名'alipay.csv'）
npm run alipay

# 导入微信账单后（命名'微信支付账单.csv')
npm run weixin
```

- 把原始文件导入到`csv`文件夹内
- 转换后的文件在`qit`文件夹，enjoy~

感谢原作~感恩开源~
