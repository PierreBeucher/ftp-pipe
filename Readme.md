FTP Pipe
========

Simple FTP to FTP file pipe implemented as a Mule application.

# Usage

- Package the application: `mvn clean package`
- Configure your environment: copy `src/main/resources/ftp-pipe.template.properties` onto your classpath (such as in $MULE_HOME/conf) as `src/main/resources/ftp-pipe.<env>.properties` and adapt it
- Deploy the application (copy the package in $MULE_HOME/apps for Mule Standalone)

# Releases

## 1.0.0

First release. Simple FTP to FTP pipe.