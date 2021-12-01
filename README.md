# Flutter Google ML Kit OCR

This a sample Flutter app integrated with the [ML Kit](https://developers.google.com/ml-kit) Vision API for recognition All text from an image.

## Plugins

Using the following dependencies in the pubspec.yaml file:

```yaml
dependencies:
  cupertino_icons: ^1.0.3
  camera: ^0.9.4+5
  google_ml_kit: ^0.7.3
```

> For the latest version of these plugins checkout their respective pages on `pub.dev`.


## Usage

You can try out the app on your system by following these steps:



2. Get packages:
   
   ```bash
   flutter pub get
   ```

3. Go to `android/app/build.gradle` and update the `minSdkVersion` to **26**:
   
   ```gradle
   minSdkVersion 26
   ```

4. Run the app:
   
   ```bash
   flutter run
   ```


Inspire by sbis04/flutter_mlkit_vision
