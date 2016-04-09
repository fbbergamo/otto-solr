# otto-solr
Uses docker-external to add [solr](https://lucene.apache.org/solr/) support for [otto](https://ottoproject.io/)

## Getting Started
Appfile
``` hcl
application {
    # add to the end of your application block in your Appfile
    dependency { source = "github.com/fbbergamo/otto-solr" }
}
```
