# Gradle

### org.gradle.jvmargs=-Xmx4096m -XX:MaxPermSize=4096m -XX:+HeapDumpOnOutOfMemoryError


bootRun.systemProperties['spring.profiles.active'] = System.properties['spring.profiles.active']
bootRun.systemProperties['kinesis.output.stream'] = System.properties['kinesis.output.stream']
