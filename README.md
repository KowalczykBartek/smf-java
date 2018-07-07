[![](https://img.shields.io/badge/unicorn-approved-ff69b4.svg)](https://www.youtube.com/watch?v=9auOCbH5Ns4)
![][license img]

### smf-java
port of SMF in Java language.
Examples are stored in example.demo package (those are not generated). If you want to run server and client, first build them
```bash
./gradlew buildClientExample
./gradlew buildServerExample
```
and run
```bash
java -jar ./build/libs/smf-java-server-1.0-SNAPSHOT.jar
java -jar ./build/libs/smf-java-client-1.0-SNAPSHOT.jar
```

### API
If are familiar with internals of SMF, you can use smf.client.core.SmfClient and smf.server.core.SmfServer directly, if not, just look at examples.

## References

* [Main Repository](https://github.com/senior7515/smf) - smf source code
* [Official Documentation](https://senior7515.github.io/smf/) - smf documentation

## Powered by
<img src="http://normanmaurer.me/presentations/2014-netflix-netty/images/netty_logo.png" height="75" width="150">

[license img]:https://img.shields.io/badge/License-Apache%202-blue.svg
