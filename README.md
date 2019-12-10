# Build Health-cache Updater Plugin

This plugin calls the Jenkins job's health report to be generated
when a job is done instead of when the weather column is displayed next.

In theory this should move that work to the executor threads 
instead of the http request threads.

## Changelog

Can be found in [GitHub Releases](https://github.com/jenkinsci/build-health-cache-updater-plugin/releases)
