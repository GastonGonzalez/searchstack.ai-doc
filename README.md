# SearchStack.ai

This document provides a step-by-step guide to install a full local development stack of
SearchStack.ai. These instructions are for Linux, but in general, work well for Mac OS X.

## Recommended Development Workspace

1. Create a parent directory for all the SearchStack.ai projects. This directory can be located 
   anywhere on your system as long as you have read/write access. 
   
        $ mkdir -p ~/workspace/searchstack.ai
        
2. Define an environment variable called `SEARCHSTACK_AI_HOME`. It should be set to the absolute
   directory created in the previous step. The lines below assume that you are using the Bash
   shell. Add these to ~/.bash_profile.

        SEARCHSTACK_AI_HOME=$HOME/workspace/searchstack.ai
        export SEARCHSTACK_AI_HOME

3. Change into `SEARCHSTACK_AI_HOME` directory. 

        $ cd $SEARCHSTACK_AI_HOME

## Development Tool Chain

Install the following development tools.

1. Java JDK 8 (OpenJDK or Oracle JDK)
2. [Maven 3.5+](http://maven.apache.org/)
3. [Apache Ant](https://ant.apache.org/)

## Setup Guides

1. [Automation Project](setup/01-automation.md)
2. [Document Processing](setup/02-document-processor.md)