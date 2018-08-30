# ESKDB_HDP (Ensemble of SKDB using HDP smoothing)


# Prerequisites

This package requires Java 8 (to run) and Maven (to compile).

# Installing

## Compiling ESKDB using HDP estimation
```
git clone https://github.com/icesky0125/ESKDB_HDP
cd ESKDB_HDP
mvn package
``` 
## Getting a cross-platform jar
A jar file will be created after using "mvn package" command under the target folder. This jar file can be execute in most environments in "target/ESKDBHDP-0.0.1-SNAPSHOT-jar-with-dependencies.jar".

## To execute the demo, simply run:
```java -jar target/ESKDBHDP-0.0.1-SNAPSHOT-jar-with-dependencies.jar -t data/abalone.arff -S ESKDB -K 5 -I 1000 -L 2 -E 10 -V```

The default main class is "src/main/java/ESKDBTest/EvaluationESKDB.java"

# Dataset format
The code is build based on weka, so the dataset format used in this reporitory is "arff". You can try any arff dataets, or convert them to arff.

# Note
please get the latest HDP smoothing package from https://github.com/fpetitjean/HDP.
