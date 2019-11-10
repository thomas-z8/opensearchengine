# opensearchengine
Open Search Engine Project - the goal of the project is to gather open source code, create open source tools to crawl and index the web, and produce valuable open data

Programming plan (see './Functional Diagrams' for a longer term overview of the project ) : 
1. Create a Cron Task that will run a shell script every 10 minutes.
2. The shell script will read the file .osestatus, check the OSESTATUS variable and log its content.
