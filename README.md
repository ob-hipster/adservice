# Ad Service

The Ad service provides advertisement based on context keys. If no context keys are provided then it returns random ads.

## Releases

| branch               | level        |
| -------------------- | ------------ |
| release-0.8.0-12.0.0 | 0.8.0-12.0.0 |

## Building locally

The Ad service uses gradlew to compile/install/distribute. Gradle wrapper is already part of the source code. To build Ad Service, run:

```
./gradlew installDist
```
It will create executable script src/adservice/build/install/hipstershop/bin/AdService

### Upgrading gradle version
If you need to upgrade the version of gradle then run

```
./gradlew wrapper --gradle-version <new-version>
```

## Building docker image

From `src/adservice/`, run:

```
docker build ./
```

