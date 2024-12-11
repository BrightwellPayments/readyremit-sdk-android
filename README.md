
# Adding ReadyRemitSDK via Gradle

## Information
- **URL**: [https://github.com/BrightwellPayments/readyremit-sdk-ios](https://github.com/BrightwellPayments/readyremit-sdk-ios)
- **Minimum Android SDK**: 26

## Step-by-Step Guide:

### Gradle
1. Assure you have Maven Central repository in your *project* `build.gradle`:
    ```groovy
    allProject {
        repositories {
            // ...
            mavenCentral()
        }
    }
    ```

2. Add the dependencies in your *module* `build.gradle` file:
   ```groovy
   dependencies {
        // ...
        implementation("io.github.brightwellpayments:ReadyRemitSDK:9.0")
   }
   ```

### Next steps 

You can see how to configure ReadyRemitSDK on our [documentation](https://developer.readyremit.com/docs/android)
