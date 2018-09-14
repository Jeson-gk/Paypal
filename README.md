# Paypal
Paypal快捷支付集成（非预支付）
因为Paypal支付最终都是通过拉起一个web画面完成支付，所以不管是在移动端、PC端都可以适用。

开发之前需先创建沙盒账号，用于开发、测试。
<br/>1.在 https://www.paypal.com/myaccount/home 创建账号，这是一个正式账号，用于管理沙盒账号。
<br/>2.创建之后，登录账号，进入沙盒环境 https://developer.paypal.com/developer/accounts/ 在Sandbox Accounts下创建收款方和付款方。收款方的Username，Password，Signature这几个值将用于开发。创建付款方时，账户的钱是可以随意输入的，用于沙盒环境支付。
<br/>3.https://www.sandbox.paypal.com/c2/webapps/mpp/merchant 可以查看沙盒账号的收支流水。
