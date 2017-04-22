# cordova-sample1

## set up cordova 
npm instal cordova -g 
cordova create sample com.example.hello HelloWorld 

## set up project 
cd sample 
cordova add platform ios 
cordova prepare -d  
cordova emulate --target="iPhone-5s, 9.2" ios 

## plugins 
### dialogs 
cordova plugin add https://github.com/apache/cordova-plugin-dialogs.git 
