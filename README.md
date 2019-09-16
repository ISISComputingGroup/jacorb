# Jacorb P2 builder

### To build:

- Ensure your `JAVA_HOME` points to a Java 11 JDK
- Ensure you have a maven version >=3.6 (but not 3.6.1 as that version has a bug preventing tycho builds from succeeding).
- `cd` into `jacorb`
- run `mvn clean verify`

### To deploy:

- Copy the `jacorb` directory onto `shadow`, replacing the old one.
- Update version numbers (if changed) in ibex_gui target platform and manifests
