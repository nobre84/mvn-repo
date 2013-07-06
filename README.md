mvn-repo
========

Currently hosting the HoloGraphLibrary by Daniel Nadeau (https://bitbucket.org/danielnadeau/holographlibrary/wiki/Home)

Utilize by adding the following to your build.gradle:

        repositories {
            maven {
                url 'https://github.com/powerje/mvn-repo/raw/master/'
            }
            mavenCentral()
        }

        dependencies {
            compile 'com.android.support:support-v4:13.0.0'
            compile 'com.echo:holographlibrary:1.0'
        }
