## IBM MobileFirst Foundation
IBM Mobile Foundation is an integrated platform that helps you extend your business to mobile devices.

Mobile Foundation includes a comprehensive development environment, mobile-optimized runtime middleware, a private enterprise application store, and an integrated management and analytics console, all supported by various security mechanisms.

With Mobile Foundation, your organization can efficiently develop, connect, run, and manage rich mobile applications (apps) that can access the full capabilities of your target mobile devices. Mobile Foundation can help reduce time-to-market, cost, and complexity of development, and enables an optimized customer and employee user experience across multiple environments.

## IBM Digital App Builder 

IBM Digital App Builder helps you quickly create mobile, web and PWA (Progressive Web App) multi-channel applications. The apps created using the Digital App Builder leverage IBM Mobile Foundation V8 (on-prem or cloud) for security, backend connectivity, and analytics.

Developers can use this tool to quickly build digital apps that can run on multiple channels. The Digital App Builder provides the ability to drag-and-drop components to quickly build an app. This app can be targeted to multiple channels, like apps for iOS (iPhone, iPad), Android (Phone, Tabs), Progressive web apps (PWA), and web pages.

## Pre-requisites 

 * [Install IBM Digital App Builder](https://github.com/MobileFirst-Platform-Developer-Center/Digital-App-Builder/releases) 
 * [Download IBM MFP Developer Kit](https://mobilefirstplatform.ibmcloud.com/downloads/#collapseDevKit)

 >Prerequisite: To use the MobileFirst Server and DAB in your local workstation, Java Developer Kit (JDK) 7 or 8 needs to be installed.

* Download and install Java 7 or 8 JDK Set the JAVA_HOME environment variable to your JDK directory. For example:

	Windows: C:\Program Files\Java\jdk1.7.0__67
	
	OS X: /Library/Java/JavaVirtualMachines/jdk1.7.0 _ 67.jdk/Contents/Home
	
	*In any case, IBM Digital App Builder does a pre-requisite check and installs the dependencies, or lets you know in case any dependency needs to be installed manually.*
 
*	From a Command-line window, navigate to the extracted folder and execute the "run.sh"  or "run.cmd" script to start the MobileFirst Developer Kit Server.

	Load the MobileFirst Operations Console (username/password: admin/admin): http://localhost:9080/mfpconsole.

* [Familiarise the DAB interface](https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/digital-app-builder/dab-interface/)

## Getting started with Application development in DAB

* [Application development using DAB.](getting-started)
* [Mock backend REST services with Mock API](mock-api)
* [Invoke backend REST Microservices](microservice-invocation)
* [Use API Proxy to invoke REST Microservices](api-proxy)
* [Push Notifications](push-notifications)
* [LiveUpdate](liveupdate)
* [Custom Analytics](custom-analytics)
* [AI and Cognitive Services](watson-chatbot)
* [InApp Feedback](inapp-feedback)
* [Publish to AppCenter](application-center)
