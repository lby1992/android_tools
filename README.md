Useful tools for setting up Android development process

Quality Tools
=============
Lint, kLint for Kotlin, Checkstyle, Findbugs, PMD. 

### Usage: 
1. add `apply from: "$project.rootDir/tools/quality/quality.gradle"` to the top of your app or module's `build.gradle` file.
2. `./gradlew check` will run through all static analysis tools on all build variants, or simply `./gradlew check[Variant]` to run the checks on the desired build variant. See `./gradlew tasks` for more detailed commands.`
