QA: Smoke Test Client

------------------------------------------------------------------------

<span id="publishDate">Last Published: 2015-10-21</span>  | <span id="projectVersion">Version: 2.1.0-SNAPSHOT</span>

------------------------------------------------------------------------

[![Built by Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

Project Dependencies
--------------------

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId           | ArtifactId                                                                                  | Version        | Type | License                                                                                    |
|-------------------|---------------------------------------------------------------------------------------------|----------------|------|--------------------------------------------------------------------------------------------|
| log4j             | [log4j](http://logging.apache.org/log4j/1.2/)                                               | 1.2.17         | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.apache.lucene | [lucene-test-framework](http://lucene.apache.org/lucene-parent/lucene-test-framework)       | 5.3.0          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                 |
| org.elasticsearch | [elasticsearch](http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch) | 2.1.0-SNAPSHOT | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.hamcrest      | [hamcrest-all](https://github.com/hamcrest/JavaHamcrest/hamcrest-all)                       | 1.3            | jar  | [New BSD License](http://www.opensource.org/licenses/bsd-license.php)                      |

Project Transitive Dependencies
-------------------------------

The following is a list of transitive dependencies for this project. Transitive dependencies are the dependencies of the project dependencies.

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId                            | ArtifactId                                                                                | Version      | Type | License                                                                                      |
|------------------------------------|-------------------------------------------------------------------------------------------|--------------|------|----------------------------------------------------------------------------------------------|
| com.carrotsearch                   | [hppc](http://labs.carrotsearch.com/hppc.html/hppc)                                       | 0.7.1        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.carrotsearch.randomizedtesting | [randomizedtesting-runner](http://labs.carrotsearch.com/randomizedtesting-runner)         | 2.1.16       | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.fasterxml.jackson.core         | [jackson-core](https://github.com/FasterXML/jackson-core)                                 | 2.6.2        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.fasterxml.jackson.dataformat   | [jackson-dataformat-cbor](http://wiki.fasterxml.com/JacksonForCbor)                       | 2.6.2        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.fasterxml.jackson.dataformat   | [jackson-dataformat-smile](http://wiki.fasterxml.com/JacksonForSmile)                     | 2.6.2        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.fasterxml.jackson.dataformat   | [jackson-dataformat-yaml](https://github.com/FasterXML/jackson)                           | 2.6.2        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.google.guava                   | [guava](http://code.google.com/p/guava-libraries/guava)                                   | 18.0         | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.ning                           | [compress-lzf](http://github.com/ning/compress)                                           | 1.0.2        | jar  | [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)                        |
| com.spatial4j                      | [spatial4j](https://github.com/spatial4j/spatial4j)                                       | 0.4.1        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.tdunning                       | [t-digest](https://github.com/tdunning/t-digest)                                          | 3.0          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| com.twitter                        | [jsr166e](http://github.com/twitter/jsr166e)                                              | 1.1.0        | jar  | [CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/)                       |
| commons-cli                        | [commons-cli](http://commons.apache.org/proper/commons-cli/)                              | 1.3.1        | jar  | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                |
| io.netty                           | [netty](http://netty.io/)                                                                 | 3.10.5.Final | jar  | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)                    |
| joda-time                          | [joda-time](http://www.joda.org/joda-time/)                                               | 2.8.2        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| junit                              | [junit](http://junit.org)                                                                 | 4.11         | jar  | [Common Public License Version 1.0](http://www.opensource.org/licenses/cpl1.0.txt)           |
| org.apache.ant                     | [ant](http://ant.apache.org/ant/)                                                         | 1.8.2        | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)   |
| org.apache.lucene                  | [lucene-analyzers-common](http://lucene.apache.org/lucene-parent/lucene-analyzers-common) | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-backward-codecs](http://lucene.apache.org/lucene-parent/lucene-backward-codecs)   | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-codecs](http://lucene.apache.org/lucene-parent/lucene-codecs)                     | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-core](http://lucene.apache.org/lucene-parent/lucene-core)                         | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-grouping](http://lucene.apache.org/lucene-parent/lucene-grouping)                 | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-highlighter](http://lucene.apache.org/lucene-parent/lucene-highlighter)           | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-join](http://lucene.apache.org/lucene-parent/lucene-join)                         | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-memory](http://lucene.apache.org/lucene-parent/lucene-memory)                     | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-misc](http://lucene.apache.org/lucene-parent/lucene-misc)                         | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-queries](http://lucene.apache.org/lucene-parent/lucene-queries)                   | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-queryparser](http://lucene.apache.org/lucene-parent/lucene-queryparser)           | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-sandbox](http://lucene.apache.org/lucene-parent/lucene-sandbox)                   | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-spatial](http://lucene.apache.org/lucene-parent/lucene-spatial)                   | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-spatial3d](http://lucene.apache.org/lucene-parent/lucene-spatial3d)               | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene                  | [lucene-suggest](http://lucene.apache.org/lucene-parent/lucene-suggest)                   | 5.3.0        | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.hdrhistogram                   | [HdrHistogram](http://hdrhistogram.github.io/HdrHistogram/)                               | 2.1.6        | jar  | [Public Domain, per Creative Commons CC0](http://creativecommons.org/publicdomain/zero/1.0/) |
| org.joda                           | [joda-convert](http://joda-convert.sourceforge.net)                                       | 1.2          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.yaml                           | [snakeyaml](http://www.snakeyaml.org)                                                     | 1.15         | jar  | LICENSE.txt                                                                                  |

Project Dependency Graph
------------------------

### Dependency Tree

-   org.elasticsearch.qa:smoke-test-client:jar:2.1.0-SNAPSHOT ![Information](./images/icon_info_sml.gif)
    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">QA: Smoke Test Client</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><p><strong>Description:</strong> Test the Java Client against a running cluster</p>
    <p><strong>URL:</strong> <a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-client" class="uri">http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-client</a></p>
    <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
    </tr>
    </tbody>
    </table>

    -   org.elasticsearch:elasticsearch:jar:2.1.0-SNAPSHOT (test) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Elasticsearch: Core</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Elasticsearch - Open Source, Distributed, RESTful Search Engine</p>
        <p><strong>URL:</strong> <a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch" class="uri">http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

        -   org.apache.lucene:lucene-core:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Core</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Apache Lucene Java Core</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-core" class="uri">http://lucene.apache.org/lucene-parent/lucene-core</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.lucene:lucene-backward-codecs:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Memory</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Codecs for older versions of Lucene.</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-backward-codecs" class="uri">http://lucene.apache.org/lucene-parent/lucene-backward-codecs</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.lucene:lucene-analyzers-common:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Common Analyzers</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Additional Analyzers</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-analyzers-common" class="uri">http://lucene.apache.org/lucene-parent/lucene-analyzers-common</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.lucene:lucene-queries:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Queries</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Lucene Queries Module</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-queries" class="uri">http://lucene.apache.org/lucene-parent/lucene-queries</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.lucene:lucene-memory:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Memory</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> High-performance single-document index to compare against Query</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-memory" class="uri">http://lucene.apache.org/lucene-parent/lucene-memory</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.lucene:lucene-highlighter:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Highlighter</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> This is the highlighter for apache lucene java</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-highlighter" class="uri">http://lucene.apache.org/lucene-parent/lucene-highlighter</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.lucene:lucene-queryparser:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene QueryParsers</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Lucene QueryParsers module</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-queryparser" class="uri">http://lucene.apache.org/lucene-parent/lucene-queryparser</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

            -   org.apache.lucene:lucene-sandbox:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">Lucene Sandbox</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Lucene Sandbox</p>
                <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-sandbox" class="uri">http://lucene.apache.org/lucene-parent/lucene-sandbox</a></p>
                <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
                </tr>
                </tbody>
                </table>
        -   org.apache.lucene:lucene-suggest:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Suggest</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Lucene Suggest Module</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-suggest" class="uri">http://lucene.apache.org/lucene-parent/lucene-suggest</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

            -   org.apache.lucene:lucene-misc:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">Lucene Miscellaneous</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Miscellaneous Lucene extensions</p>
                <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-misc" class="uri">http://lucene.apache.org/lucene-parent/lucene-misc</a></p>
                <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
                </tr>
                </tbody>
                </table>
        -   org.apache.lucene:lucene-join:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Join</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Lucene Join Module</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-join" class="uri">http://lucene.apache.org/lucene-parent/lucene-join</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

            -   org.apache.lucene:lucene-grouping:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">Lucene Grouping</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Lucene Grouping Module</p>
                <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-grouping" class="uri">http://lucene.apache.org/lucene-parent/lucene-grouping</a></p>
                <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
                </tr>
                </tbody>
                </table>
        -   org.apache.lucene:lucene-spatial:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene Spatial</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Spatial Strategies for Apache Lucene</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-spatial" class="uri">http://lucene.apache.org/lucene-parent/lucene-spatial</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

            -   org.apache.lucene:lucene-spatial3d:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">Lucene Spatial 3D</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Lucene Spatial shapes implemented using 3D planar geometry</p>
                <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-spatial3d" class="uri">http://lucene.apache.org/lucene-parent/lucene-spatial3d</a></p>
                <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
                </tr>
                </tbody>
                </table>

            -   com.spatial4j:spatial4j:jar:0.4.1 (test) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">Spatial4J</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Spatial4j is a general purpose spatial / geospatial ASL licensed open-source Java library. It's core capabilities are 3-fold: to provide common geospatially-aware shapes, to provide distance calculations and other math, and to read shapes in WKT format.</p>
                <p><strong>URL:</strong> <a href="https://github.com/spatial4j/spatial4j" class="uri">https://github.com/spatial4j/spatial4j</a></p>
                <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
                </tr>
                </tbody>
                </table>
        -   com.google.guava:guava:jar:18.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Guava: Google Core Libraries for Java</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Guava is a suite of core and expanded libraries that include utility classes, google's collections, io classes, and much much more. Guava has only one code dependency - javax.annotation, per the JSR-305 spec.</p>
            <p><strong>URL:</strong> <a href="http://code.google.com/p/guava-libraries/guava" class="uri">http://code.google.com/p/guava-libraries/guava</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.carrotsearch:hppc:jar:0.7.1 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">HPPC Collections</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> High Performance Primitive Collections. Fundamental data structures (maps, sets, lists, stacks, queues) generated for combinations of object and primitive types to conserve JVM memory and speed up execution.</p>
            <p><strong>URL:</strong> <a href="http://labs.carrotsearch.com/hppc.html/hppc" class="uri">http://labs.carrotsearch.com/hppc.html/hppc</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   joda-time:joda-time:jar:2.8.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Joda-Time</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Date and time library to replace JDK date handling</p>
            <p><strong>URL:</strong> <a href="http://www.joda.org/joda-time/" class="uri">http://www.joda.org/joda-time/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.joda:joda-convert:jar:1.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Joda convert</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Library to convert Objects to and from String</p>
            <p><strong>URL:</strong> <a href="http://joda-convert.sourceforge.net" class="uri">http://joda-convert.sourceforge.net</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.fasterxml.jackson.core:jackson-core:jar:2.6.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Jackson-core</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Core Jackson abstractions, basic JSON streaming API implementation</p>
            <p><strong>URL:</strong> <a href="https://github.com/FasterXML/jackson-core" class="uri">https://github.com/FasterXML/jackson-core</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.fasterxml.jackson.dataformat:jackson-dataformat-smile:jar:2.6.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Jackson-dataformat-Smile</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Support for reading and writing Smile (&quot;binary JSON&quot;) encoded data using Jackson abstractions (streaming API, data binding, tree model)</p>
            <p><strong>URL:</strong> <a href="http://wiki.fasterxml.com/JacksonForSmile" class="uri">http://wiki.fasterxml.com/JacksonForSmile</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.6.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Jackson-dataformat-YAML</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Support for reading and writing YAML-encoded data via Jackson abstractions.</p>
            <p><strong>URL:</strong> <a href="https://github.com/FasterXML/jackson" class="uri">https://github.com/FasterXML/jackson</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

            -   org.yaml:snakeyaml:jar:1.15 (test) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">SnakeYAML</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> YAML 1.1 parser and emitter for Java</p>
                <p><strong>URL:</strong> <a href="http://www.snakeyaml.org" class="uri">http://www.snakeyaml.org</a></p>
                <p><strong>Project License:</strong> <a href="LICENSE.txt">Apache License Version 2.0</a></p></td>
                </tr>
                </tbody>
                </table>
        -   com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Jackson-dataformat-CBOR</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Support for reading and writing Concise Binary Object Representation ([CBOR](https://www.rfc-editor.org/info/rfc7049) encoded data using Jackson abstractions (streaming API, data binding, tree model)</p>
            <p><strong>URL:</strong> <a href="http://wiki.fasterxml.com/JacksonForCbor" class="uri">http://wiki.fasterxml.com/JacksonForCbor</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   io.netty:netty:jar:3.10.5.Final (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Netty</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> The Netty project is an effort to provide an asynchronous event-driven network application framework and tools for rapid development of maintainable high performance and high scalability protocol servers and clients. In other words, Netty is a NIO client server framework which enables quick and easy development of network applications such as protocol servers and clients. It greatly simplifies and streamlines network programming such as TCP and UDP socket server.</p>
            <p><strong>URL:</strong> <a href="http://netty.io/" class="uri">http://netty.io/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0">Apache License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.ning:compress-lzf:jar:1.0.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Compress-LZF</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Compression codec for LZF encoding for particularly encoding/decoding, with reasonable compression. Compressor is basic Lempel-Ziv codec, without Huffman (deflate/gzip) or statistical post-encoding. See &quot;http://oldhome.schmorp.de/marc/liblzf.html&quot; for more on original LZF package.</p>
            <p><strong>URL:</strong> <a href="http://github.com/ning/compress" class="uri">http://github.com/ning/compress</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.html">Apache License 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.tdunning:t-digest:jar:3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">T-Digest</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Data structure which allows accurate estimation of quantiles and related rank statistics</p>
            <p><strong>URL:</strong> <a href="https://github.com/tdunning/t-digest" class="uri">https://github.com/tdunning/t-digest</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.hdrhistogram:HdrHistogram:jar:2.1.6 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">HdrHistogram</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> HdrHistogram supports the recording and analyzing sampled data value counts across a configurable integer value range with configurable value precision within the range. Value precision is expressed as the number of significant digits in the value recording, and provides control over value quantization behavior across the value range and the subsequent value resolution at any given level.</p>
            <p><strong>URL:</strong> <a href="http://hdrhistogram.github.io/HdrHistogram/" class="uri">http://hdrhistogram.github.io/HdrHistogram/</a></p>
            <p><strong>Project License:</strong> <a href="http://creativecommons.org/publicdomain/zero/1.0/">Public Domain, per Creative Commons CC0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   commons-cli:commons-cli:jar:1.3.1 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Apache Commons CLI</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Apache Commons CLI provides a simple API for presenting, processing and validating a command line interface.</p>
            <p><strong>URL:</strong> <a href="http://commons.apache.org/proper/commons-cli/" class="uri">http://commons.apache.org/proper/commons-cli/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.twitter:jsr166e:jar:1.1.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">JSR166e</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> JSR166e</p>
            <p><strong>URL:</strong> <a href="http://github.com/twitter/jsr166e" class="uri">http://github.com/twitter/jsr166e</a></p>
            <p><strong>Project License:</strong> <a href="http://creativecommons.org/publicdomain/zero/1.0/">CC0 1.0 Universal</a></p></td>
            </tr>
            </tbody>
            </table>
    -   log4j:log4j:jar:1.2.17 (test) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Apache Log4j</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Apache Log4j 1.2</p>
        <p><strong>URL:</strong> <a href="http://logging.apache.org/log4j/1.2/" class="uri">http://logging.apache.org/log4j/1.2/</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

    -   org.hamcrest:hamcrest-all:jar:1.3 (test) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Hamcrest All</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> A self-contained hamcrest jar containing all of the sub-modules in a single artifact.</p>
        <p><strong>URL:</strong> <a href="https://github.com/hamcrest/JavaHamcrest/hamcrest-all" class="uri">https://github.com/hamcrest/JavaHamcrest/hamcrest-all</a></p>
        <p><strong>Project License:</strong> <a href="http://www.opensource.org/licenses/bsd-license.php">New BSD License</a></p></td>
        </tr>
        </tbody>
        </table>

    -   org.apache.lucene:lucene-test-framework:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Lucene Test Framework</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Apache Lucene Java Test Framework</p>
        <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-test-framework" class="uri">http://lucene.apache.org/lucene-parent/lucene-test-framework</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
        </tr>
        </tbody>
        </table>

        -   org.apache.lucene:lucene-codecs:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Lucene codecs</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Codecs and postings formats for Apache Lucene.</p>
            <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-codecs" class="uri">http://lucene.apache.org/lucene-parent/lucene-codecs</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
            </tr>
            </tbody>
            </table>

        -   com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">RandomizedTesting Randomized Runner</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Foundation classes and rules for applying the principles of Randomized Testing.</p>
            <p><strong>URL:</strong> <a href="http://labs.carrotsearch.com/randomizedtesting-runner" class="uri">http://labs.carrotsearch.com/randomizedtesting-runner</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   junit:junit:jar:4.11 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">JUnit</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> JUnit is a regression testing framework written by Erich Gamma and Kent Beck. It is used by the developer who implements unit tests in Java.</p>
            <p><strong>URL:</strong> <a href="http://junit.org" class="uri">http://junit.org</a></p>
            <p><strong>Project License:</strong> <a href="http://www.opensource.org/licenses/cpl1.0.txt">Common Public License Version 1.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.apache.ant:ant:jar:1.8.2 (test) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Apache Ant Core</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> master POM</p>
            <p><strong>URL:</strong> <a href="http://ant.apache.org/ant/" class="uri">http://ant.apache.org/ant/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

Licenses
--------

**New BSD License:** Hamcrest All

**Apache 2:** Joda convert, Joda-Time, Lucene Common Analyzers, Lucene Core, Lucene Grouping, Lucene Highlighter, Lucene Join, Lucene Memory, Lucene Miscellaneous, Lucene Queries, Lucene QueryParsers, Lucene Sandbox, Lucene Spatial, Lucene Spatial 3D, Lucene Suggest, Lucene Test Framework, Lucene codecs

**Public Domain, per Creative Commons CC0:** HdrHistogram

**Apache License, Version 2.0:** Apache Commons CLI, Netty

**Apache License 2.0:** Compress-LZF

**Common Public License Version 1.0:** JUnit

**The Apache Software License, Version 2.0:** Apache Ant Core, Apache Log4j, Elasticsearch: Core, Guava: Google Core Libraries for Java, HPPC Collections, Jackson-core, Jackson-dataformat-CBOR, Jackson-dataformat-Smile, Jackson-dataformat-YAML, QA: Smoke Test Client, RandomizedTesting Randomized Runner, Spatial4J, T-Digest

**CC0 1.0 Universal:** JSR166e

**Apache License Version 2.0:** SnakeYAML

Dependency File Details
-----------------------

| Filename                            | Size           | Entries      | Classes      | Packages  | JDK Rev | Debug    |
|-------------------------------------|----------------|--------------|--------------|-----------|---------|----------|
| hppc-0.7.1.jar                      | 1.09 MB        | 915          | 901          | 5         | 1.6     | debug    |
| randomizedtesting-runner-2.1.16.jar | 207.89 kB      | 173          | 159          | 5         | 1.6     | debug    |
| jackson-core-2.6.2.jar              | 252.76 kB      | 116          | 93           | 9         | 1.6     | debug    |
| jackson-dataformat-cbor-2.6.2.jar   | 47.02 kB       | 25           | 10           | 1         | 1.6     | debug    |
| jackson-dataformat-smile-2.6.2.jar  | 74.16 kB       | 34           | 17           | 2         | 1.6     | debug    |
| jackson-dataformat-yaml-2.6.2.jar   | 312.93 kB      | 253          | 210          | 20        | 1.6     | debug    |
| guava-18.0.jar                      | 2.15 MB        | 1,719        | 1,690        | 17        | 1.6     | debug    |
| compress-lzf-1.0.2.jar              | 77.86 kB       | 59           | 42           | 6         | 1.6     | debug    |
| spatial4j-0.4.1.jar                 | 99.78 kB       | 67           | 48           | 9         | 1.6     | debug    |
| t-digest-3.0.jar                    | 48.59 kB       | 31           | 20           | 1         | 1.6     | debug    |
| jsr166e-1.1.0.jar                   | 60.77 kB       | 37           | 27           | 1         | 1.6     | debug    |
| commons-cli-1.3.1.jar               | 51.75 kB       | 39           | 26           | 1         | 1.5     | debug    |
| netty-3.10.5.Final.jar              | 1.27 MB        | 950          | 880          | 43        | 1.5     | debug    |
| joda-time-2.8.2.jar                 | 607.41 kB      | 749          | 246          | 7         | 1.5     | debug    |
| junit-4.11.jar                      | 239.30 kB      | 266          | 233          | 28        | 1.5     | debug    |
| log4j-1.2.17.jar                    | 478.40 kB      | 353          | 314          | 21        | 1.4     | debug    |
| ant-1.8.2.jar                       | 1.84 MB        | 1,168        | 1,090        | 59        | 1.4     | debug    |
| lucene-analyzers-common-5.3.0.jar   | 1.49 MB        | 673          | 563          | 61        | 1.6     | debug    |
| lucene-backward-codecs-5.3.0.jar    | 374.68 kB      | 223          | 202          | 10        | 1.6     | debug    |
| lucene-codecs-5.3.0.jar             | 408.73 kB      | 224          | 206          | 6         | 1.6     | debug    |
| lucene-core-5.3.0.jar               | 2.25 MB        | 1,563        | 1,532        | 21        | 1.6     | debug    |
| lucene-grouping-5.3.0.jar           | 105.97 kB      | 76           | 65           | 3         | 1.6     | debug    |
| lucene-highlighter-5.3.0.jar        | 141.08 kB      | 97           | 86           | 3         | 1.6     | debug    |
| lucene-join-5.3.0.jar               | 116.26 kB      | 90           | 81           | 1         | 1.6     | debug    |
| lucene-memory-5.3.0.jar             | 32.51 kB       | 21           | 12           | 1         | 1.6     | debug    |
| lucene-misc-5.3.0.jar               | 168.27 kB      | 122          | 107          | 7         | 1.6     | debug    |
| lucene-queries-5.3.0.jar            | 206.93 kB      | 174          | 162          | 5         | 1.6     | debug    |
| lucene-queryparser-5.3.0.jar        | 391.91 kB      | 312          | 273          | 26        | 1.6     | debug    |
| lucene-sandbox-5.3.0.jar            | 260.50 kB      | 168          | 148          | 8         | 1.6     | debug    |
| lucene-spatial-5.3.0.jar            | 194.02 kB      | 139          | 122          | 10        | 1.6     | debug    |
| lucene-spatial3d-5.3.0.jar          | 121.56 kB      | 67           | 59           | 1         | 1.6     | debug    |
| lucene-suggest-5.3.0.jar            | 240.22 kB      | 150          | 132          | 7         | 1.6     | debug    |
| lucene-test-framework-5.3.0.jar     | 6.23 MB        | 482          | 451          | 19        | 1.6     | debug    |
| elasticsearch-2.1.0-SNAPSHOT.jar    | 8.80 MB        | 6,306        | 5,785        | 453       | 1.6     | debug    |
| hamcrest-all-1.3.jar                | 299.39 kB      | 249          | 204          | 23        | 1.5     | debug    |
| HdrHistogram-2.1.6.jar              | 107.15 kB      | 67           | 58           | 1         | 1.6     | debug    |
| joda-convert-1.2.jar                | 37.56 kB       | 52           | 40           | 1         | 1.5     | debug    |
| snakeyaml-1.15.jar                  | 262.98 kB      | 237          | 201          | 19        | 1.5     | debug    |
| Total                               | Size           | Entries      | Classes      | Packages  | JDK Rev | Debug    |
| 38                                  | 31.01 MB       | 18,446       | 16,495       | 921       | 1.6     | 38       |
| test: 38                            | test: 31.01 MB | test: 18,446 | test: 16,495 | test: 921 | -       | test: 38 |

Dependency Repository Locations
-------------------------------

| Repo ID                        | URL                                                        | Release | Snapshot | Blacklisted |
|--------------------------------|------------------------------------------------------------|---------|----------|-------------|
| sonatype.releases              | <https://oss.sonatype.org/content/repositories/releases>   | Yes     | Yes      | -           |
| oss-snapshots                  | <https://oss.sonatype.org/content/repositories/snapshots/> | Yes     | Yes      | -           |
| apache.snapshots               | <http://repository.apache.org/snapshots>                   | -       | -        | -           |
| sonatype-nexus-snapshots       | <https://oss.sonatype.org/content/repositories/snapshots>  | -       | Yes      | -           |
| maven2-repository.dev.java.net | <http://download.java.net/maven/2/>                        | Yes     | Yes      | Yes         |
| central                        | <http://repo.maven.apache.org/maven2>                      | Yes     | -        | -           |
| elasticsearch-releases         | <http://maven.elasticsearch.org/releases>                  | Yes     | -        | -           |

Repository locations for each of the Dependencies.

| Artifact                                                               | sonatype.releases                                                                                                                                                                                                                                                | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | central                                                                                                                                                                                                                    | elasticsearch-releases |
|------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|
| com.carrotsearch:hppc:jar:0.7.1                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar)                                                             | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar)                                                             | -                      |
| com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | -                      |
| com.fasterxml.jackson.core:jackson-core:jar:2.6.2                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/core/jackson-core/2.6.2/jackson-core-2.6.2.jar)                                   | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.6.2/jackson-core-2.6.2.jar)                                   | -                      |
| com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.2     | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-cbor/2.6.2/jackson-dataformat-cbor-2.6.2.jar)       | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-cbor/2.6.2/jackson-dataformat-cbor-2.6.2.jar)       | -                      |
| com.fasterxml.jackson.dataformat:jackson-dataformat-smile:jar:2.6.2    | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-smile/2.6.2/jackson-dataformat-smile-2.6.2.jar)     | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-smile/2.6.2/jackson-dataformat-smile-2.6.2.jar)     | -                      |
| com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.6.2     | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.6.2/jackson-dataformat-yaml-2.6.2.jar)       | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.6.2/jackson-dataformat-yaml-2.6.2.jar)       | -                      |
| com.google.guava:guava:jar:18.0                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/google/guava/guava/18.0/guava-18.0.jar)                                                             | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/google/guava/guava/18.0/guava-18.0.jar)                                                             | -                      |
| com.ning:compress-lzf:jar:1.0.2                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/ning/compress-lzf/1.0.2/compress-lzf-1.0.2.jar)                                                     | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/ning/compress-lzf/1.0.2/compress-lzf-1.0.2.jar)                                                     | -                      |
| com.spatial4j:spatial4j:jar:0.4.1                                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/spatial4j/spatial4j/0.4.1/spatial4j-0.4.1.jar)                                                      | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/spatial4j/spatial4j/0.4.1/spatial4j-0.4.1.jar)                                                      | -                      |
| com.tdunning:t-digest:jar:3.0                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/tdunning/t-digest/3.0/t-digest-3.0.jar)                                                             | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/tdunning/t-digest/3.0/t-digest-3.0.jar)                                                             | -                      |
| com.twitter:jsr166e:jar:1.1.0                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/twitter/jsr166e/1.1.0/jsr166e-1.1.0.jar)                                                            | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/twitter/jsr166e/1.1.0/jsr166e-1.1.0.jar)                                                            | -                      |
| commons-cli:commons-cli:jar:1.3.1                                      | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-cli/commons-cli/1.3.1/commons-cli-1.3.1.jar)                                                    | -                      |
| io.netty:netty:jar:3.10.5.Final                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/io/netty/netty/3.10.5.Final/netty-3.10.5.Final.jar)                                                     | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/io/netty/netty/3.10.5.Final/netty-3.10.5.Final.jar)                                                     | -                      |
| joda-time:joda-time:jar:2.8.2                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/joda-time/joda-time/2.8.2/joda-time-2.8.2.jar)                                                          | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/joda-time/joda-time/2.8.2/joda-time-2.8.2.jar)                                                          | -                      |
| junit:junit:jar:4.11                                                   | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/junit/junit/4.11/junit-4.11.jar)                                                                        | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/junit/junit/4.11/junit-4.11.jar)                                                                        | -                      |
| log4j:log4j:jar:1.2.17                                                 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/log4j/log4j/1.2.17/log4j-1.2.17.jar)                                                                    | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/log4j/log4j/1.2.17/log4j-1.2.17.jar)                                                                    | -                      |
| org.apache.ant:ant:jar:1.8.2                                           | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/ant/ant/1.8.2/ant-1.8.2.jar)                                                                 | -                      |
| org.apache.lucene:lucene-analyzers-common:jar:5.3.0                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-analyzers-common/5.3.0/lucene-analyzers-common-5.3.0.jar)                      | -                      |
| org.apache.lucene:lucene-backward-codecs:jar:5.3.0                     | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-backward-codecs/5.3.0/lucene-backward-codecs-5.3.0.jar)                        | -                      |
| org.apache.lucene:lucene-codecs:jar:5.3.0                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-codecs/5.3.0/lucene-codecs-5.3.0.jar)                                          | -                      |
| org.apache.lucene:lucene-core:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-core/5.3.0/lucene-core-5.3.0.jar)                                              | -                      |
| org.apache.lucene:lucene-grouping:jar:5.3.0                            | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-grouping/5.3.0/lucene-grouping-5.3.0.jar)                                      | -                      |
| org.apache.lucene:lucene-highlighter:jar:5.3.0                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-highlighter/5.3.0/lucene-highlighter-5.3.0.jar)                                | -                      |
| org.apache.lucene:lucene-join:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-join/5.3.0/lucene-join-5.3.0.jar)                                              | -                      |
| org.apache.lucene:lucene-memory:jar:5.3.0                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-memory/5.3.0/lucene-memory-5.3.0.jar)                                          | -                      |
| org.apache.lucene:lucene-misc:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-misc/5.3.0/lucene-misc-5.3.0.jar)                                              | -                      |
| org.apache.lucene:lucene-queries:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-queries/5.3.0/lucene-queries-5.3.0.jar)                                        | -                      |
| org.apache.lucene:lucene-queryparser:jar:5.3.0                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-queryparser/5.3.0/lucene-queryparser-5.3.0.jar)                                | -                      |
| org.apache.lucene:lucene-sandbox:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-sandbox/5.3.0/lucene-sandbox-5.3.0.jar)                                        | -                      |
| org.apache.lucene:lucene-spatial:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-spatial/5.3.0/lucene-spatial-5.3.0.jar)                                        | -                      |
| org.apache.lucene:lucene-spatial3d:jar:5.3.0                           | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-spatial3d/5.3.0/lucene-spatial3d-5.3.0.jar)                                    | -                      |
| org.apache.lucene:lucene-suggest:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-suggest/5.3.0/lucene-suggest-5.3.0.jar)                                        | -                      |
| org.apache.lucene:lucene-test-framework:jar:5.3.0                      | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-test-framework/5.3.0/lucene-test-framework-5.3.0.jar)                          | -                      |
| org.elasticsearch:elasticsearch:jar:2.1.0-SNAPSHOT                     | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -                                                                                                                                                                                                                          | -                      |
| org.hamcrest:hamcrest-all:jar:1.3                                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                     | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                     | -                      |
| org.hdrhistogram:HdrHistogram:jar:2.1.6                                | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hdrhistogram/HdrHistogram/2.1.6/HdrHistogram-2.1.6.jar)                                             | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hdrhistogram/HdrHistogram/2.1.6/HdrHistogram-2.1.6.jar)                                             | -                      |
| org.joda:joda-convert:jar:1.2                                          | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/joda/joda-convert/1.2/joda-convert-1.2.jar)                                                         | -                      |
| org.yaml:snakeyaml:jar:1.15                                            | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar)                                                             | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar)                                                             | -                      |
| Total                                                                  | sonatype.releases                                                                                                                                                                                                                                                | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | central                                                                                                                                                                                                                    | elasticsearch-releases |
| 38 (test: 38)                                                          | 18                                                                                                                                                                                                                                                               | 0             | 0                | 0                        | 37                                                                                                                                                                                                                         | 0                      |

------------------------------------------------------------------------

Copyright © 2015. All rights reserved.

------------------------------------------------------------------------


