# QQ钱包 PHP SDK
**【请求型接口】--QPay_client_**

 - 统一支付接口类--UnifiedOrder
 - 订单查询接口--OrderQuery
 - 退款申请接口--Refund
 - 退款查询接口--RefundQuery
 - 对账单接口--DownloadBill
 - 短链接转换接口--ShortUrl

**【响应型接口】--QPay_server_**

 - 通用通知接口--Notify

**【CommonUtil】常用工具：**

 - trimString()，设置参数时需要用到的字符处理函数
 - createNoncestr()，产生随机字符串，不长于32位
 - formatBizQueryParaMap(),格式化参数，签名过程需要用到
 - getSign(),生成签名
 - arrayToXml(),ARRAY 转 XML xml
 - ToArray(),XML 转 ARRAY 
 - postXmlCurl(),以POST 方式提交 XML 到对应的接口 URL
 - postXmlSSLCurl(),使用证书，以 POST 方式提交 XML 到对应的接口 URL
 
 
### 感谢 https://github.com/djlinks/wxpay 提供 微信支付接口 SDK