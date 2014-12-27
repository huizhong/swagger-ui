# updates

* fix bug "Warning: Deprecated on non deprecated API operations"
see [swagger-springmvc issue 512](https://github.com/martypitt/swagger-springmvc/issues/512)

* add jar output
see [swagger-ui-webjar](https://github.com/wikier/swagger-ui-webjar/blob/master/pom.xml)


# usage

## dependency (pom.xml)
        <dependency>
            <groupId>com.eeeya.daidai.web.server</groupId>
            <artifactId>swagger-ui-webjar</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>

## servlet  (xxx-servlet.xml)

    <!--suppress SpringModelInspection -->
    <resources mapping="/**" location="webjars/swagger-ui/" />

