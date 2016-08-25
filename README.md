# flx-qrcode

## Install
```javascript
meteor add jayuda:flx-qrcode
```

## Usage
HTML template to display qrcode
```html
{{> QRCode text=helperTEXT size="128px" }}
```
Create Helper on javascript file
```javascript
Template.yourTemplate.helpers({
    helperTEXT: function(){
        return 'Text to Qrcode';
    }
});
```


many thanks to steeve:jquery-qrcode
