# https-spring-boot

Command to create self signed SSL Certificate

    keytool -genkey -alias https-example -storetype JKS -keyalg RSA -keysize 2048 -validity 365 -keystore https-example.jks
    
 Secured access
 
    https://localhost:8080/test - Hello HTTPS test