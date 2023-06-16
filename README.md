# java


### How to import certs into java keystore
- Copy the cert file to JAVA_HOME/jre/lib/security. Example Certificate.cer
- Import the certificate to keystore 'cacerts' using the java keytool.
- Provide a alias to identify the certs.
- Type in password when asked - Default - changeit
```sh
keytool -import -alias maven -keystore cacerts -file Certificate.cer
```

### How to list all the stored certificates in java
```sh
keytool -list -v -keystore cacerts
```


# TODO

### JAXB 
  ```
  @XmlRootElement
  @XmlType
  @XmlElemet
  ```


### How to create a simple java web app - using maven

```mvn archetype:generate -DgroupId=app.web.java -DartifactId=simplejavawebapp -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false
```


