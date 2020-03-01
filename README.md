# s3eGoogleAnalytics

Google Analytics extension for Marmalade SDK (Android)

## How to integrate (Windows)

1. Have your Marmalade SDK installed on your machine

2. Execute both s3eGoogleAnalytics_android.mkb and s3eGoogleAnalytics_android_java.mkb simply by clicking on them or writing their names in the command line

3. Include "s3eGoogleAnalytics" in your project's mkb file

## Usage

In order to initialise s3eGoogleAnalytics extension trigger `s3eGoogleAnalytics_Init(const char* ua_id, const char* screen_name)` where:
- `ua_id` - tracking id from your Google Analytics account
- `screen_name` - on mobile most likely your game's package name, for example: com.companyname.mygame. For more information you can take a look at Google's [documentation](https://developers.google.com/analytics/devguides/collection/android/v3/screens
).

To start a new session use `s3eGoogleAnalytics_Start()` and to end it - `s3eGoogleAnalytics_End()`

## Copyright and License
Copyright 2005-2020 Rixment. Code released under the [MIT](./LICENSE) license.
