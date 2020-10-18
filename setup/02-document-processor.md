## Document Processor

## Prerequisites 

* Java JDK  8
* Apache Maven 3.x
* VirtualBox
* [Automation project](02-document-processor.md)

## Installation & Configuration Steps

1. Clone and install `boilerpipe` into your local Maven repository. This project is a dependency
   of the document processor.

        $ cd $SEARCHSTACK_AI_HOME
        $ git clone https://github.com/GastonGonzalez/boilerpipe.git
        $ cd boilerpipe
        $ mvn clean install

2. Clone the _Document Processor_ project.

        $ git clone https://github.com/GastonGonzalez/greenrush-document-processing.git
        $ cd greenrush-document-processing/weedguy-indexer