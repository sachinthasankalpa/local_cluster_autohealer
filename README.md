# To build the Autohealer
Run `mvn clean install`

## To run the autohealer, which in turn would launch and maintain 1 worker
Run `java -jar target/autohealer-1.0-SNAPSHOT-jar-with-dependencies.jar <number of workers> <path to woker jar>`
Example: `java -jar target/autohealer-1.0-SNAPSHOT-jar-with-dependencies.jar 1 "distributed_password_cracker-1.0-SNAPSHOT-jar-with-dependencies.jar"`
