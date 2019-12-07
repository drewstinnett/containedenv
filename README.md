# ContainedENV

## Description

This project is meant to provide utilities for writing out configuration files
based on environment variables.  Lots of projects seem to be implementing this
on their own (Elasticsearch/Grafana), but it would be nice to have one thing
that works for them all...so...here we go!

## Usage

Set your environment variables with a shared prefix.  Section headers should be
followed by a double underscore `__`
