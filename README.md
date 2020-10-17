# SearchStack.ai

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

TODO

## Setup Guides

1. [Document Processing](setup/document-processor.md)