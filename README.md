# gradle-kindergarten
A play project for learning gradle build tool.

## Pre-requisites
- Gradle 4.10.2

## Gradle Features Covered
* Gradle tasks
* Gradle extra properties.

### Gradle extra properties
1. Run ```./gradlew showExtraProps``` to see hardcoded value of ```extraProp```.
2. Run ```./gradlew -PextraProp='Tattva' showExtraProps``` to see same value (Extra properties can not be overriden).
3. Run ```./gradlew showGradleProps``` to see hardcoded/default value of ```gradleProp```.
4. Run ```./gradlew -PgradleProp='Bodha' showGradleProps``` to see overriden value of ```gradleProp```.

