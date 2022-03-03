# java-word-count-beam

## Quick Start

- <https://beam.apache.org/get-started/quickstart-java/>

## Project focused

Use Maven archetype to fetch a project. 
In 44-517, create java-word-count-beam project folder.

In 44-517/java-word-count-beam

- Create README.md
- Open project folder in VS Code.
- Create a sample.txt with content from Shakespeare's sonnets (as we did Monday).

## Run WordCount Using Maven
mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount`
-D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
 