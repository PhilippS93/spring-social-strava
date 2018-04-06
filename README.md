# Spring Social Strava
=====
It includes all the changes made to the API up to May 13, 2016.

To check out the project and build from source, do the following:

    git clone git://github.com/PhilippS93/spring-social-strava.git
    cd spring-social-strava
    ./gradlew build
    
Maven
=====
javastrava is available on Maven. Just add this to your POM:

```xml
<dependency>
    <groupId>com.github.PhilippS93</groupId>
    <artifactId>spring-social-strava</artifactId>
</dependency>
```

Use the `Strava Connection Factory` to obtain an OAuth2 connection to strava.
    
    StravaConnectionFactory(CLIENT_ID, CLIENT_SECRET)
    