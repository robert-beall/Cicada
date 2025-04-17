# Basic Jenkins Install
These [instructions](https://www.jenkins.io/doc/pipeline/tour/getting-started/#download-and-run-jenkins) come directly from the Jenkins docs.

1. Download [Jenkins Generic Java package (.war)](https://www.jenkins.io/download)
2. Open up a terminal in the download directory
3. Run `java -jar jenkins.war --httpPort=8080`
4. Browse to http://localhost:8080

Follow the instructions to complete the installation.

## Mac Install

1. Install the latest Weekly version: `brew install jenkins`
2. Start the Jenkins service: `brew services start jenkins`
3. Restart the Jenkins service: `brew services restart jenkins`
4. Update the Jenkins version: `brew upgrade jenkins`