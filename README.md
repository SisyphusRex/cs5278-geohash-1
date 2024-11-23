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


I receive Gradle Deprecation warnings at runtime.  They involve the java plugin in the build.gradle file.  Online resources don't explain how to fix it.

Build file 'C:\Users\twpod\Projects\cs5278-geohash-1\build.gradle': line 8
The org.gradle.api.plugins.JavaPluginConvention type has been deprecated. This is scheduled to be removed in Gradle 9.0. Consult the upgrading guide for further information: https://docs.gradle.org/8.9/userguide/upgrading_version_8.html#java_convention_deprecation
        at build_57tfa2xrzvxvhu4kfsttqsr6p.run(C:\Users\twpod\Projects\cs5278-geohash-1\build.gradle:8)
        (Run with --stacktrace to get the full stack trace of this deprecation warning.)
