

## Email API
- Create an Account in [ElasticEmail](https://elasticemail.com/) ( IS FREE )
- Set creadentials of the [smtp.js](https://smtpjs.com/) library  
```js
var _EMAIL="your_elastic_email@gmail.com"
var _PASS="your_elastic_api_key"
var _TO="your_email@gmail.com"
var _HOST='smtp.elasticemail.com'

Email.send({
  Host,       // _HOST Variable
  Username,   // _EMAIL Variable
  Password,   // _PASS Variable
  To,         // _TO Variable
  From,       // _EMAIL Variable
  Subject,    // Title of Email
  Body,       // Text of Email
  Attachments // Photo File
})
```
