# PaymentService

**DEPRECATED!**

Gateway to variety of payment providers. Provides unified interface.
Handles async payment responses.

Owner|Tier|Status|Landscape|Contexts
---|---|---|---|---
CheckoutTeam|Tier1|Prod|Web|Payments, Orders, Customers

##### Deprecated

Payment Service is going to be sunset in min 2021.
Pls consider using AmazingPaymentService instead. 

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

There is no staging environment, please use "sandbox" mode for testing. 

##### Tech

- Golang 13.x: implementation
- AWS Lambda: execution env 
- Serverless: deployment
- AWS ALB: request routing

##### Providers

- Paypal
- Invoice