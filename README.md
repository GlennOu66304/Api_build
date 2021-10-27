# Api_build

## NodeJS qr code
```
var QRCode = require('qrcode')
 
QRCode.toDataURL('I am a pony!', function (err, url) {
  console.log(url)
})
```
[qr code](https://www.npmjs.com/package/qrcode)   
## Receive the string as the first paramater in console
Make sure you choose the json format in post man and choose the body content as below:, do not choose the text sections
```
{"text":"GY"}
```
