
# Adding ReadyRemitSDK via Gradle

## Information
- **URL**: [https://github.com/BrightwellPayments/readyremit-sdk-android](https://github.com/BrightwellPayments/readyremit-sdk-android)
- **Minimum Android SDK**: 26

## Step-by-Step Guide:

### Gradle
1. Assure you have Maven Central and Jitpack repositories in your *project* `build.gradle`:
    ```groovy
    allProject {
        repositories {
            // ...
            mavenCentral()
            maven { url = URI("https://jitpack.io") }
        }
    }
    ```

2. Add the dependencies in your *module* `build.gradle` file:
   ```groovy
   dependencies {
        // ...
        implementation("io.github.brightwellpayments:ReadyRemitSDK:10.0.0")

       // the minimum Android Bill Of Materials version
       // should be 2025.11.01, or Compose 1.9.5, or AndroidX Core 1.17.0
   }
   ```

Note: Recommended Kotlin Version is 2.1.0

### Next steps 

You can see how to configure ReadyRemitSDK on our [documentation](https://developer.readyremit.com/docs/android)
