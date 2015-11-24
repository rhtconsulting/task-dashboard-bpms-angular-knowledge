task-dashboard-bpms-angular-knowledge
==============

## Modules:

1. bpms-trader-knowledge: The module containing rules and processes to be deployed in the bpm runtime for this demo

## Deployment

This kjar can be deploy to a BPM Suite runtime, either embedded or remote. It is intended to be used with a the angular task dashboard (see below).

## Related Work

1. [bpms-trader-knowledge](https://github.com/rhtconsulting/task-dashboard-bpms-angular-app): A angularjs 2 app wired together using require.js, package in a Java WAR. It provides a dashboard of human tasks managed in the BPM Suite runtime by integrating with the task query API (link)
2. Red Hat Consulting Business Automation Practice [Standard project structure](http://redhat.slides.com/jholmes/bxms-standard-project-structures)

## Product Version

Currently built against BPM Suite 6.1 update 4 (maven version 6.2.0.Final-redhat-13)
