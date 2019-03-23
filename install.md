# Download App from PlayStore

<a href='https://play.google.com/store/apps/details?id=in.canews.protoview'><img width="250" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png'/></a>

# Installation and Usage

Download and Install [ProtoPreview Plugin from Here](https://github.com/canewsin/ProtoView-Issues/releases/tag/0.1.0)

Make Sure node is install on your PC

install npm modules globally
 ## qrcode-terminal
 - [qrcode-terminal](https://www.npmjs.com/package/qrcode-terminal) 
 - `npm i -g qrcode-terminal`
 
 ## http-server
 - [http-server](https://www.npmjs.com/package/http-server) 
 - `npm i -g http-server`
 
 - Open XD Document For Editing and Draw minimum 2 supported elements in Artboard and Select atleast one.
 - Click Ctrl + Shift + P (or) Menu > Plugins > ProtoView (If Shortcut is reserved by another plugin)
 - Open Adobe XD Console
 - A Cmd is Shown There Eg: `http-server C:\Users\Me\AppData\Local\Packages\Adobe.CC.XD_adky2gkssdxte\LocalState\plugin_settings\5f7db82a\public`
 - Open cmd prompt and paste copied cmd from console and press enter
 - it gives a ip address Eg: http://192.168.43.1:8080
 - open another cmd propmt window and type `qcode-terminal IP_ADDRESS_HERE`
 - click enter it will show a qrcode, scan it with mobile(to be connected to same network as PC) app
