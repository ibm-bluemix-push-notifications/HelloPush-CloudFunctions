# HelloPush-CloudFunctions - Sample app for IBM Cloud functions Push Notification package

This helloPush sample contains an IBM cloud functions project that you can use to learn more about the IBM Cloud Push Notification Service.


## Contents
- [Prerequisites](#prerequisites)
- [Create an instance of IBM Cloud Push Notifications Service](#create-an-instance-of-bluemix-push-notifications-service)
- [setup the app](#setup-the-app)
- [Samples and videos](#samples-and-videos)


### Prerequisites

Before you start, make sure you have the following:

- A [IBM Cloud](http://bluemix.net) account.
- Register devices for the push notifications.

### Create an instance of IBM Cloud Push Notifications Service
- Create an instance of IBM Cloud Push Notifications Service and [configure](https://console.ng.bluemix.net/docs/services/mobilepush/t_push_provider_ios.html) it .


### setup the app

 1. Add the service credentials in the following code,

 ```Javascript
    apikey: "your api Key",
    appId: "your appguid",
    apiHost: "imfpush.ng.bluemix.net",

 ```

### Samples and videos

* Please visit for samples - [Github Sample](https://github.com/ibm-bluemix-mobile-services/bms-samples-swift-hellopush)

* Video Tutorials Available here - [IBM Cloud Push Notifications](https://www.youtube.com/channel/UCRr2Wou-z91fD6QOYtZiHGA)

=======================

Copyright 2019 IBM Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.