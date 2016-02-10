# CameraBehaviour
Camera behaviour for Polymer using Cordova plugin

```javascript
 getPicture: function () {
                this.takePhoto(this.pictureCallback.bind(this));
 },
 pictureCallback: function(pic){
                this.set("data.bilde", pic);
 },
``` 
