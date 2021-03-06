# url_shortener
A Python Flask URL Shortener with a global API. The goal of this project is to create a URL shortener that allows you to monetize content behind it. It will be integrated with a payment gateway that will provide you with a voucher. The voucher can then be used to bypass the paywall. 

A global API exists to create short urls as well as vouchers.

## Short URL Features:
- Visit tracking
- Webhooks (see below)
- Expiring Short URLs
- Require Voucher to redirect
- Expiring Vouchers
- Limited Use Vouchers
- Custom Vouchers, such as FREE or LIMIT30


## Webhooks
Webhooks can be called during the following events
- On Redirect

They contain the following:
- IP Address
- User Agent
- Voucher Used
- Short URL
