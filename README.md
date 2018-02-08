# GOAL

Bundle the smallest possible groovy application as a `jar`, using Gradle after they changed `sourceSets.output` in 4.0.

# Intro

Examples of gradle not building proper `jar`-archives.

Contains 2 projects with boilerplate groovy code and a an `uberjar` task

# Notes
Run a jar with

`$ java -jar build/libs/tempest.jar`

# Problem
Receiving error 
`Error: Could not find or load main class App`

# Project: standard

A standard project

# Project: w-package

A project where a package is added to the files. Nothing changes.
