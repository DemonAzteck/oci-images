# AdoptOpenJDK11 - OCI Image JRE11 minimal
Custom Images for Java11 Runners

Image build with default charset _en_US.UTF-8_
Workdir */opt/app*

|Environment Vars||
|---|---|
|JAVA_OPTIONS||
|CLASSPATH||
|JAVA_ARGS||

### Dockerfile for use
```
FROM demonioazteka/ubi8-jre11-minimal:latest
COPY /target /opt/app
```