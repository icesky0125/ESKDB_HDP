# ESKDB_HDP

Installing: 

git clone https://github.com/icesky0125/ESKDB_HDP

cd ESKDB_HDP

mvn package

To execute the demos, simply run:

java -jar target/ESKDBHDP-0.0.1-SNAPSHOT-jar-with-dependencies.jar -t data/abalone.arff -S ESKDB -K 5 -I 1000 -L 2 -E 10 -V

Note: please get the latest HDP smoothing package from https://github.com/fpetitjean/HDP.
