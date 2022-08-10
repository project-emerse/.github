# EMERSE

Though the EMERSE project is open-source, the projects here are private since we want to track the usage of it since it is grant-funded.  If you want accesss, send the EMERSE team a message at EMERSE-team@umich.edu.

Here's a short outline of the projects available:

* [EMERSE](https://github.com/project-emerse/emerse) is our full text search engine.
* [Indexing](https://github.com/project-emerse/indexing) is our tool for indexing documents into Solr for use in EMERSE.
* [HL7 Processor](https://github.com/project-emerse/hl7-processor) is our hl7 message processor and rtf-to-html/pdf document converter.
* [Schedule](https://github.com/project-emerse/schedule) is our simple cron-like application for doing ETL tasks.

And here are some of the libraries we developed, used in some or all of the projects:

* [Gradle Plugin](https://github.com/project-emerse/gradle-plugin) is a gradle plugin used in many projects and structures projects similarly.
* [SQL](https://github.com/project-emerse/sql) is a slim layer of JDBC which abstracts SQL just enough to be database vendor agnostic.

These libraries are stored on our own [maven repository](https://project-emerse.org/repo/), referenced in some of our projects.
