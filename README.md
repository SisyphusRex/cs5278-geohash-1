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


__________________________________________________________

Copyright 2025 Theodore Podewil  
GPL-3.0-or-later  

/* This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see https://www.gnu.org/licenses/. */
