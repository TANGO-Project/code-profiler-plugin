# Code Profiler Plugin

&copy; University of Leeds 2016

Code Profiler Plugin (CP) is a component of the European Project TANGO (http://tango-project.eu ).

CP is distributed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Description

The code profiler is a tool for analysing Java code for its energy efficiency.

## Installation Guide

This guide it is divided into two different guides, one specific to compilation of the code profiler and the second on how to run it.

### Compilation

#### Requirements

The code profiler's primary prerequisites are:

* Java
* Eclipse
* Maven

#### Installation and configuration procedure


#### Build status from Travis-CI

[![Build Status](https://travis-ci.org/TANGO-Project/code-profiler-plugin.svg?branch=master)](https://travis-ci.org/TANGO-Project/code-profiler-plugin)

#### Sonar Cloud reports:
The Sonar Cloud reports for this project are available at: https://sonarcloud.io/dashboard?id=eu.tango%3Acode-optimizer-plugin

### Installation Guide for running the Application

In this case, we are going to detail how to run the application as a plugin of the Eclipse IDE.

## Usage Guide

This application works as a standard plugin to eclipse. It creates a new perspective for monitoring that may be used to monitor power consumption of applications running in an eclipse based environment.

It extends [JVM Monitor](http://jvmmonitor.org/) so the JVM Monitor user guide remains applicable. 

## Relation to other TANGO components

The code profiler works with:

* **Energy Modeller** - The Energy modeller provides power modelling services to the code profiler.
