### Init

Install buildozer through git or something
buildozer init
(android sdk stuff, javac will be install takes time)
(First builds are really slow +20mins)

### Edit Spec file

-Name, package name
-files to exclude
-files to use if using images, pdf etc
-dependencies
-log level 2
-and a lot

### To Make APK

buildozer android debug

### If phone is connected

buildozer android deploy run
(installs and runs the app)

### To debug install logview

https://bitbucket.org/mlopatkin/android-log-viewer/downloads/

### Filter for your app

with app name =
org.test.appname
or
package.domain.package.name ( from spec file)
