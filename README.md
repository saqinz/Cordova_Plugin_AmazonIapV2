# Cordova_Plugin_AmazonIapV2
This is original Amazon Cordova SDK.
A git repository for Amazon IAP making it easy to import. I have added Package.json to make it work.

Install:
cordova plugin add https://github.com/saqinz/Cordova_Plugin_AmazonIapV2
It will add plug in named: com.amazon.device.iap.cpt.AmazonIapV2Plugin

Check Install Status:

add follwoing in onDeviceReady();
        var iapPlugin = window.AmazonIapV2;
        console.log("iapPlugin" + iapPlugin);
        
Usage Instructions
https://developer.amazon.com/docs/cross-platform-plugins/cpp-use-the-iap-plugin-for-cordova.html
