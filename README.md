symphAstman
===========

Symfony assetic manager to aid in multistage development and deployment

The documentation is on top of the script file, please see bin/recompile

This is a script made to ease the constant running of symfony assetic:dump,
assets:install, cache:clear, cache:warmup and the like.  It contains a selector
when you run the script, i.e. press a number 1), 2) 3), which correspond to dev
env, a stage env (if applicable), and a production env. 

This script ensures the correct commands are being ran on an environment,
preset on the script, editable by a senior developer.  This can be a safe way
to delegate this action to junior developers also, and reduce the learning
curve at the same time.

Please see the bin/recompile script for more info.
