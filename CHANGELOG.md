# Changelog

## Release USSD Android Library 1.1.b (27/09/2018)
New Structure of Messaging, reading and sending each message

latestVersion is 1.1.b

repositories {
    jcenter()
}
dependencies {
    implementation 'com.romellfudi.ussdlibrary:ussd-library:{latestVersion}'
}

---

## Release upload on Maven Central (15/09/2018)
Upload on Maven Central

repositories {
    jcenter()
}
dependencies {
    compile 'com.romellfudi.ussdlibrary:ussd-library:{latestVersion}'
}

---

## Release USSD Android Library 1.0.b (27/08/2018)
Upgrade con.romellfudi for Android Library.

- Import ussdlibrary-1.0.b.aar
- put ussd_service.xml into res/xml folder

or import into project:

maven {
        url 'https://dl.bintray.com/romllz489/maven/'
}
dependencies {
    compile 'com.romellfudi.ussdlibrary:ussd-library:{latestVersion}'
}

---

## Release USSD Android Library 1.0.a (31/07/2018)
Remember import the internal xml into aar or replace with xml similar to ussd_service.xml