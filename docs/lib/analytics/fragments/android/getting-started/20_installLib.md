Expand Gradle Scripts, open build.gradle (Module: app). You will already have configured Amplify by following the steps in the Project Setup walkthrough.

Add Analytics by adding these libraries into the dependencies block:

```groovy
dependencies {
    implementation 'com.amplifyframework:core:1.0.0'

    // Add these lines in `dependencies`
    implementation 'com.amplifyframework:aws-analytics-pinpoint:1.0.0'
    implementation 'com.amplifyframework:aws-auth-cognito:1.0.0'
}
```