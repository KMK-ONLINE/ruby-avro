This is a ruby-only fork of https://github.com/apache/avro, created with command:

    git filter-branch --prune-empty --subdirectory-filter lang/ruby master

It has the snappy compression patch from https://issues.apache.org/jira/browse/AVRO-1804, 
applied on top of https://github.com/apache/avro/commit/f614e15e.
