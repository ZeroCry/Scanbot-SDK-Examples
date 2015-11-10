# Scanbot-SDK-Examples

#### How it works?

Check out our Wiki: https://github.com/doo/Scanbot-SDK-Examples/wiki

Check out JavaDocs:  http://doo.github.io/Scanbot-SDK-Documentation/Android/

#### How do I get the license?

You can run examples and even develop your app without a license. If you do not specify the license in `AndroidManifest` then SDK will work in trial mode (currently, for 1 minute). If this is not enough for you, contact us at sdk@scanbot.io and we'll give you a free trial license for longer period.

#### What is the latest version of the SDK?

Current version is 1.13.1

#### Why example is not working / stopped working

Either your trial period is expired or you set the license incorrectly. Please, double check that.

#### Note

Please kindly take note of the following points when downloading the SDK:

- This is a trial version and will only work for 1 minute (if you require a trial license which works for a longer period of time please contact us).
- We are constantly updating and evolving the SDK and it is no final product.
- The SDK with a trial license should only be tested in a experimental setting and it is not developed to be integrated into your live products.

#### Changelog

##### 1.13.1
* Fixed bug when final image contained less than preview image from camera stream.

##### 1.13.0
* Added `ImageQualityOptimizer` which allows you to optimize image size

##### 1.12.2
* Fixed bug when `AutosnappingController` stop operating after `onPause`

##### 1.12.1
* Color-document filter was disabled in `ContourDetector`. Now it works again.

##### 1.12.0
* Added `ScanbotSDKInitializer#withLogging()` method which allows you to turn on logging for SDK (disabled by default)
* Improved edge detection
* Added new filter to `ContourDetector`

##### 1.11.0
* Added `ScanbotSDK.isLicenseActive()` method
