# 支付宝wap支付
- demo 沙盒模式
- app_id merchant_private_key gatewayUrl alipay_public_key 已配置成沙箱环境的
- 运行方式：在项目要目录下 `php -S 127.0.0.1:8000`（自行本地部署时）
- 浏览器打开：www.xieguanping.cn 会出现支付、订单查询等等（注：微信内置浏览器不会呼起支付宝客户端，在微信中选择用safari打开即可呼起）
- 点击后会自动跳转到支付宝的网页支付，如果是在手机上打开，会自动呼起支付宝app
- 支付完成后完成页面跳转