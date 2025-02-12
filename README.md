# Nearby
Next Level Week Pocket: Mobile by Rocketseat

### :rocket: Technologies
- Android: [Kotlin](https://kotlinlang.org/) and [Compose](https://developer.android.com/compose).

### :camera: Screenshots

#### :iphone: Android
<img width="200" alt="mobile-detail" src="https://github.com/fredericoamsb/nearby/blob/main/screenshots/welcome.png?raw=true"> <img width="200" alt="mobile-detail" src="https://github.com/fredericoamsb/nearby/blob/main/screenshots/home.png?raw=true"> <img width="200" alt="mobile-detail" src="https://github.com/fredericoamsb/nearby/blob/main/screenshots/market_details.png?raw=true">

### :hammer: How to test
- Open the project in Android Studio and run it on an emulator;
- To run on physical device:
  - Open the terminal in the backend directory and run the command ```npm start```;
  - In the NearbyRemoteDataSource.kt file, change from ```LOCAL_HOST_EMULATOR_BASE_URL``` to ```LOCAL_HOST_PHYSICAL_BASE_URL```;
  - Change the IP address in the network_security_config.xml file and in the NearbyRemoteDataSource.kt file to your current IP address.