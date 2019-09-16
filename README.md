# Jacorb P2 builder

### To build:

- Ensure your `JAVA_HOME` points to a java 11 JDK
- `cd` into `jacorb`
- run `mvn clean verify`

### To deploy:

- Copy the `jacorb` directory onto `shadow`, replacing the old one.
- Update version numbers (if changed) in ibex_gui target platform and manifests
