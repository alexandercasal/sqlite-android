# Steps to update to the latest SQLite build
1. Go to https://sqlite.org/android/doc/trunk/www/install.wiki
2. Locate the zip file download link for the SQLite Android Bindings (see 2. Building a Custom aar file on the wiki page)
3. Replace the following files in this repo with the files from the zip: gradle, sqlite3, sqlite3test, www, Customsqlite.iml, gradle.properties, gradlew, settings.gradle
4. Careful replacing build.gradle to ensure the neccessary values for JitPack to build aren't removed
