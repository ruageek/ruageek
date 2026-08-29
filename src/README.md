# Source

Maven sources for the `ruageek` Java application.

- `main/java/com/ruageek/apps/Main.java` — the application entry point
  (currently just prints "Hello, World!").
- `test/java/com/ruageek/apps/` — JUnit tests.

Build and test with the Maven wrapper (`./mvnw test`); run with
`./mvnw exec:java -Dexec.mainClass=com.ruageek.apps.Main`.
