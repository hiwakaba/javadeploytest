# javadeploytest
javadeploytest

# Do

Staging the content by using the `site` phase of the site lifecycle followed by `site:stage`.
```
$ mvn site site:stage
```

Publishing the staged site to the SCM.
```
$ mvn scm-publish:publish-scm
```
# reference

* https://maven.apache.org/plugins/maven-javadoc-plugin/examples/aggregate.html
* https://maven.apache.org/plugins/maven-scm-publish-plugin/publish-scm-mojo.html
* https://maven.apache.org/guides/mini/guide-site.html#github-pages-apache-svnpubsub-gitpubsub-deployment
* https://maven.apache.org/plugins/maven-site-plugin/examples/multimodule.html
* https://books.sonatype.com/mvnex-book/reference/index.html

