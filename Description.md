Basic web-crawler exercise
A maven app, so can be run using:

mvn clean compile exec:java -Dexec.args="<seedUrl> <max depth to crawl>"
example: mvn clean compile exec:java -Dexec.args="https://goshawkdb.io/ 2"