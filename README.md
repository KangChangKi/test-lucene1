test-lucene1
============

1. gradle daemon setup

Add the following in .bash_profile:

export GRADLE_OPTS="-Dorg.gradle.daemon=true"

2. create index

> gradle indexer

3. search

> gradle searcher -Pq=lucene

