To run main method:
1. go to build.gradle file
2. add
    * plugins {
        id 'application'
    }

    * application {
        mainClass = 'edu.vanderbilt.cs.live2.GeoHash'
    }
3. terminal from root directory
     * ./gradlew run

To Test:
1. ./gradlew test
