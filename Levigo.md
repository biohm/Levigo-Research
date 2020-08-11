# Levigo-Research
## Barcodes
https://theappsolutions.com/blog/development/barcode-scanning-app/

A lack of transparency in inventory management may result in loss of customer trust due to the long shipping period, unexpected costs caused by overstocking, and inability to forecast how many products you should order next time.
To make inventory management even more effective and convenient for your workers, consider barcode scanner app development. 
### Benefits
The barcode scanning app for inventory uses the native mobile device camera to read the barcode, and then transfers the data to your local database or ERP system.
A barcode scanning app allows users to perform all the operations without connecting to the internet to upload information to a server.
By using a barcode scanning app, you will receive instant control over critical information in your inventory. Thus, your inventory management system becomes more transparent and effective. 
Since a barcode inventory app sends data to the primary system, you have real-time information on product shipping and inventory.
An inventory barcode scanner app ensures greater inventory counting accuracy while eliminating the human factor.
### Firebase ML kit Barcode Scanning API for Android apps
Can empower your app with the ability to read data encoded using most standard barcode formats. 
Firebase ML kit API has integrated automatic barcode format detection, so the user does not need to specify the format of the barcode. 
The API supports the most common barcode formats: Codabar, Code 39, Code 93, Code 128, EAN-8, EAN-13, ITF, UPC-A, UPC-E, 2D formats: Aztec, Data Matrix, PDF417, QR Code.
### Scandit Barcode Scanner SDK for iOS and Android
This barcode scanner SDK for Android and iOS allows scanning barcodes in  bad light, with damaged labels, unusual barcodes, and with all mobile device types in less than a second.
You can use this Barcode Scanner SDK for capturing labels, documents, machine-readable zones, and more around the barcode. 
Scandit barcode scanning system supports the most common 1D and 2D barcode formats, including QR Codes, PDF417, Aztec, Code-128, Data Matrix, as well as many others.
### Cognex Mobile Barcode SDK for both OS platforms
You can use this SDK to develop a mobile app with barcode integration for different industries, including logistics, manufacturing, healthcare, and commercial services.
This SDK for barcode inventory management allows scanning damaged codes, using the app in challenging lighting conditions or harsh environments, and also supports bunch scanning.
The SDK reads the following barcode formats: EAN, GS1 DataBar, MaxiCode, MSI Plessey, PDF417, UPC, and others.

### Android SDK: Create a Barcode Reader
https://code.tutsplus.com/tutorials/android-sdk-create-a-barcode-reader--mobile-17162

Use the ZXing (Zebra Crossing) library to carry out barcode scanning within an Android app.
Open your main layout file. With the default settings, Eclipse starts your layout with a Relative Layout object, which you can leave as is. Inside of it, replace the existing content (typically a Text View) with a button.
After the button, add two Text Views in which we will output scanning information
Add the button text string to your "res/values/strings" XML file
#### Add ZXing to Your Project
ZXing is an open source library that provides access to tested and functional barcode scanning on Android. Many users will already have the app installed on their devices, so you can simply launch the scanning Intents and retrieve the results.In Eclipse, add a new package to your project by right-clicking the "src" folder and choosing "New", then "Package", and entering "com.google.zxing.integration.android" as the package name.
Right-click your new package, choose "New" then "Class" and enter "IntentIntegrator" as the class name. You can leave the other default settings the way they are. Once you've created this class, do the same for the other class we'll be importing, giving it "IntentResult" as its class name.
Copy the code from both classes in the ZXing library and paste it into the class files you created. These are IntentIntegrator and IntentResult. 
You can now import the ZXing classes into your main Activity class.
#### Scanning
Implement scanning when the user clicks the button we added.
In onCreate, after the existing code, instantiate these variables using the ID values we specified in the XML.
Add an onClick method to your activity class.
Create an instance of the Intent Integrator class we imported.
Call on the Intent Integrator method to start scanning
#### Retrieving Scanning Results
When the user clicks the scan button, the barcode scanner will launch. When they scan a barcode, it will return the scanned data to the onActivityResult method of the calling activity. Add the method to your main activity class.
As with any data being retrieved from another app, it's vital to check for null values. Only proceed if we have a valid result
The Intent Result object provides methods to retrieve the content of the scan and the format of the data returned from it. Retrieve the content as a string value.
For the purpose of this tutorial, we'll just write the values to the Text Views in our layout

## CI/CD
https://semaphoreci.com/blog/cicd-pipeline

A CI/CD pipeline helps you automate steps in your software delivery process, such as initiating code builds, running automated tests, and deploying to a staging or production environment
CI, short for Continuous Integration, is a software development practice in which all developers merge code changes in a central repository multiple times a day
CD stands for Continuous Delivery, which on top of Continuous Integration adds the practice of automating the entire software release process.
It’s essentially a runnable specification of the steps that need to be performed in order to deliver a new version of a software product.
### Source stage
A pipeline run is triggered by a source code repository.
Change in code triggers a notification to the CI/CD tool, which runs the corresponding pipeline.
### Build stage
We combine the source code and its dependencies to build a runnable instance of our product that we can potentially ship to our end users
Failure to pass the build stage is an indicator of a fundamental problem in the configuration of our project and it’s best to address it immediately.\
### Test stage
In this phase we run automated tests to validate the correctness of our code and the behavior of our product
Depending on the size and complexity of the project, this phase can last from seconds to hours.
Failure during the test stage exposes problems in code that developers didn’t foresee when writing the code

Once we have a built a runnable instance of our code that has passed all predefined tests, we’re ready to deploy it

## Tools for testing app development
https://www.testbytes.net/blog/performance-testing-tools-for-mobile-applications/

### Source Labs
This automated mobile app testing covers over 800 different browsers to ensure bug-free user environment.
The testing cloud runs tests in parallel and isn’t time-consuming at all.
### Test Complete
Possible to run repeated UI tests across native and hybrid mobile apps. 
Compatible with both Android and iOS devices
Possible to create automated test scripts or choose from programming languages including Python, VBScript, and JavaScript.
### Calabash
Used to perform automated functional testing for native mobile apps
Two open-source libraries for both Android and iOS devices
It can also provide APIs for touch screening experiences and works well with Ruby, NET, Java, and many other programming languages.
### Webload
Enables you to do a stress test to let you know of the device’s performance. 
Comes with an application that helps in recording scripts directly from a mobile device
### Kobitan
Kobiton provides access to devices for running manual and automated test. 
This mobile device cloud platform is built on top of the Appium open-source framework and could be used to test across devices without script modifications.
The main feature of the tool includes commands, screenshots, faster identification, and automatically generated activity logs
