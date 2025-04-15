# Enhance-Wrangler-with-Byte-Size-and-Time-Duration-Units-Parsers

This project is part of the Wrangler assignment submission. It includes updates to the Directives.g4 grammar file along with changes in Java source files and unit tests across the wrangler-core and wrangler-api modules.

Work Summary:
The Directives.g4 file was modified to support new directive(s) as per the assignment requirements.

New and updated Java source files were added under the wrangler-core and wrangler-api modules to implement and handle the new directive logic.

Unit tests were created or modified under wrangler-core to ensure correctness and validate the changes made.

The project was built and tested successfully using Maven, and evidence of successful build/test execution has been included (build-results.txt or build-screenshot.png).

AI coding assistance (ChatGPT) was used during development, and all prompts used have been saved in prompts.txt and committed to the repository.

How to Build and Test:
Make sure Maven is installed.

Run the following command from the root directory:

bash
Copy
Edit
mvn clean install
This will compile the code and run all unit tests.

File Structure (Relevant Files):
css
Copy
Edit
project-root/
├── wrangler-core/
│   ├── src/main/antlr4/.../Directives.g4
│   ├── src/main/java/... (Java logic)
│   └── src/test/java/... (Unit tests)
├── wrangler-api/
│   └── src/main/java/... (Additional logic if any)
├── prompts.txt
├── build-results.txt or build-screenshot.png
├── README.md
All required deliverables as mentioned in the assignment have been committed to GitHub. This includes the grammar file, updated Java source code, test cases, build/test evidence, and the AI prompt log.
