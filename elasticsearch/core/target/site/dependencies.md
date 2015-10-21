---
Date-Revision-yyyymmdd: 20151021
title: 'Elasticsearch: Core – Project Dependencies'
...

<div id="banner">

<div id="bannerLeft">

Elasticsearch: Core

</div>

<div class="clear">

------------------------------------------------------------------------

</div>

</div>

<div id="breadcrumbs">

<div class="xleft">

<span id="publishDate">Last Published: 2015-10-21</span>  | <span
id="projectVersion">Version: 2.1.0-SNAPSHOT</span>

</div>

<div class="xright">

</div>

<div class="clear">

------------------------------------------------------------------------

</div>

</div>

<div id="leftColumn">

<div id="navcolumn">

[![Built by
Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

</div>

</div>

<div id="bodyColumn">

<div id="contentBox">

<div class="section">

Project Dependencies
--------------------

<div class="section">

### compile

The following is a list of compile dependencies for this project. These
dependencies are required to compile and run the application:

  GroupId                             ArtifactId                                                                                  Version        Classifier   Type   License                                                                                                            Optional
  ----------------------------------- ------------------------------------------------------------------------------------------- -------------- ------------ ------ ------------------------------------------------------------------------------------------------------------------ ----------
  com.carrotsearch                    [hppc](http://labs.carrotsearch.com/hppc.html/hppc)                                         0.7.1          -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.fasterxml.jackson.core          [jackson-core](https://github.com/FasterXML/jackson-core)                                   2.6.2          -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.fasterxml.jackson.dataformat    [jackson-dataformat-cbor](http://wiki.fasterxml.com/JacksonForCbor)                         2.6.2          -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.fasterxml.jackson.dataformat    [jackson-dataformat-smile](http://wiki.fasterxml.com/JacksonForSmile)                       2.6.2          -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.fasterxml.jackson.dataformat    [jackson-dataformat-yaml](https://github.com/FasterXML/jackson)                             2.6.2          -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.google.guava                    [guava](http://code.google.com/p/guava-libraries/guava)                                     18.0           -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.ning                            [compress-lzf](http://github.com/ning/compress)                                             1.0.2          -            jar    [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)                                              No
  com.tdunning                        [t-digest](https://github.com/tdunning/t-digest)                                            3.0            -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         No
  com.twitter                         [jsr166e](http://github.com/twitter/jsr166e)                                                1.1.0          -            jar    [CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/)                                             No
  commons-cli                         [commons-cli](http://commons.apache.org/proper/commons-cli/)                                1.3.1          -            jar    [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                      No
  io.netty                            [netty](http://netty.io/)                                                                   3.10.5.Final   -            jar    [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)                                          No
  joda-time                           [joda-time](http://www.joda.org/joda-time/)                                                 2.8.2          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-analyzers-common](http://lucene.apache.org/lucene-parent/lucene-analyzers-common)   5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-backward-codecs](http://lucene.apache.org/lucene-parent/lucene-backward-codecs)     5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-core](http://lucene.apache.org/lucene-parent/lucene-core)                           5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-highlighter](http://lucene.apache.org/lucene-parent/lucene-highlighter)             5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-join](http://lucene.apache.org/lucene-parent/lucene-join)                           5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-memory](http://lucene.apache.org/lucene-parent/lucene-memory)                       5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-queries](http://lucene.apache.org/lucene-parent/lucene-queries)                     5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-queryparser](http://lucene.apache.org/lucene-parent/lucene-queryparser)             5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-spatial](http://lucene.apache.org/lucene-parent/lucene-spatial)                     5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.apache.lucene                   [lucene-suggest](http://lucene.apache.org/lucene-parent/lucene-suggest)                     5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  org.hdrhistogram                    [HdrHistogram](http://hdrhistogram.github.io/HdrHistogram/)                                 2.1.6          -            jar    [Public Domain, per Creative Commons CC0](http://creativecommons.org/publicdomain/zero/1.0/)                       No
  org.joda                            [joda-convert](http://joda-convert.sourceforge.net)                                         1.2            -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         No
  com.github.spullara.mustache.java   [compiler](http://github.com/spullara/mustache.java)                                        0.8.13         -            jar    [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)                                                   Yes
  com.spatial4j                       [spatial4j](https://github.com/spatial4j/spatial4j)                                         0.4.1          -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         Yes
  com.vividsolutions                  [jts](http://sourceforge.net/projects/jts-topo-suite)                                       1.13           -            jar    [Lesser General Public License (LGPL)](http://www.gnu.org/copyleft/lesser.txt)                                     Yes
  log4j                               [apache-log4j-extras](http://logging.apache.org/log4j/extras)                               1.2.17         -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         Yes
  log4j                               [log4j](http://logging.apache.org/log4j/1.2/)                                               1.2.17         -            jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         Yes
  net.java.dev.jna                    [jna](https://github.com/twall/jna)                                                         4.1.0          -            jar    [LGPL, version 2.1](http://www.gnu.org/licenses/licenses.html)-[ASL, version 2](http://www.apache.org/licenses/)   Yes
  org.apache.lucene                   [lucene-expressions](http://lucene.apache.org/lucene-parent/lucene-expressions)             5.3.0          -            jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                         Yes
  org.codehaus.groovy                 [groovy-all](http://groovy-lang.org)                                                        2.4.4          indy         jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                         Yes
  org.slf4j                           [slf4j-api](http://www.slf4j.org)                                                           1.6.2          -            jar    [MIT License](http://www.opensource.org/licenses/mit-license.php)                                                  Yes

</div>

<div class="section">

### test

The following is a list of test dependencies for this project. These
dependencies are only required to compile and run unit tests for the
application:

  GroupId                              ArtifactId                                                                              Version   Type   License
  ------------------------------------ --------------------------------------------------------------------------------------- --------- ------ --------------------------------------------------------------------------------------------
  com.carrotsearch.randomizedtesting   [randomizedtesting-runner](http://labs.carrotsearch.com/randomizedtesting-runner)       2.1.16    jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  com.google.jimfs                     [jimfs](https://github.com/google/jimfs/jimfs)                                          1.0       jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  org.apache.httpcomponents            [httpclient](http://hc.apache.org/httpcomponents-client)                                4.3.6     jar    [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  org.apache.lucene                    [lucene-test-framework](http://lucene.apache.org/lucene-parent/lucene-test-framework)   5.3.0     jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)
  org.hamcrest                         [hamcrest-all](https://github.com/hamcrest/JavaHamcrest/hamcrest-all)                   1.3       jar    [New BSD License](http://www.opensource.org/licenses/bsd-license.php)

</div>

</div>

<div class="section">

Project Transitive Dependencies
-------------------------------

The following is a list of transitive dependencies for this project.
Transitive dependencies are the dependencies of the project
dependencies.

<div class="section">

### compile

The following is a list of compile dependencies for this project. These
dependencies are required to compile and run the application:

  GroupId             ArtifactId                                                                    Version   Type   License                                                      Optional
  ------------------- ----------------------------------------------------------------------------- --------- ------ ------------------------------------------------------------ ----------
  org.apache.lucene   [lucene-grouping](http://lucene.apache.org/lucene-parent/lucene-grouping)     5.3.0     jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)   No
  org.apache.lucene   [lucene-misc](http://lucene.apache.org/lucene-parent/lucene-misc)             5.3.0     jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)   No
  org.apache.lucene   [lucene-sandbox](http://lucene.apache.org/lucene-parent/lucene-sandbox)       5.3.0     jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)   No
  org.apache.lucene   [lucene-spatial3d](http://lucene.apache.org/lucene-parent/lucene-spatial3d)   5.3.0     jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)   No
  org.yaml            [snakeyaml](http://www.snakeyaml.org)                                         1.15      jar    LICENSE.txt                                                  No
  org.antlr           [antlr-runtime](http://www.antlr.org)                                         3.5       jar    [BSD licence](http://antlr.org/license.html)                 Yes
  org.ow2.asm         [asm](http://asm.objectweb.org/asm/)                                          4.1       jar    [BSD](http://asm.objectweb.org/license.html)                 Yes
  org.ow2.asm         [asm-commons](http://asm.objectweb.org/asm-commons/)                          4.1       jar    [BSD](http://asm.objectweb.org/license.html)                 Yes

</div>

<div class="section">

### test

The following is a list of test dependencies for this project. These
dependencies are only required to compile and run unit tests for the
application:

  GroupId                     ArtifactId                                                              Version   Type   License
  --------------------------- ----------------------------------------------------------------------- --------- ------ --------------------------------------------------------------------------------------------
  commons-codec               [commons-codec](http://commons.apache.org/codec/)                       1.6       jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  commons-logging             [commons-logging](http://commons.apache.org/proper/commons-logging/)    1.1.3     jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  junit                       [junit](http://junit.org)                                               4.11      jar    [Common Public License Version 1.0](http://www.opensource.org/licenses/cpl1.0.txt)
  org.apache.ant              [ant](http://ant.apache.org/ant/)                                       1.8.2     jar    [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  org.apache.httpcomponents   [httpcore](http://hc.apache.org/httpcomponents-core-ga)                 4.3.3     jar    [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)
  org.apache.lucene           [lucene-codecs](http://lucene.apache.org/lucene-parent/lucene-codecs)   5.3.0     jar    [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)

</div>

</div>

<div class="section">

Project Dependency Graph
------------------------

<div class="section">

### Dependency Tree

-   org.elasticsearch:elasticsearch:jar:2.1.0-SNAPSHOT
    ![Information](./images/icon_info_sml.gif)
    <div id="_dep0" style="display:none">

    +--------------------------------------------------------------------------+
    | Elasticsearch: Core                                                      |
    +==========================================================================+
    | **Description:** Elasticsearch - Open Source, Distributed, RESTful       |
    | Search Engine                                                            |
    |                                                                          |
    | **URL:**                                                                 |
    | <http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsea |
    | rch>                                                                     |
    |                                                                          |
    | **Project License:** [The Apache Software License, Version               |
    | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
    +--------------------------------------------------------------------------+

    </div>

    -   org.hamcrest:hamcrest-all:jar:1.3 (test)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep2" style="display:none">

        +--------------------------------------------------------------------------+
        | Hamcrest All                                                             |
        +==========================================================================+
        | **Description:** A self-contained hamcrest jar containing all of the     |
        | sub-modules in a single artifact.                                        |
        |                                                                          |
        | **URL:** <https://github.com/hamcrest/JavaHamcrest/hamcrest-all>         |
        |                                                                          |
        | **Project License:** [New BSD                                            |
        | License](http://www.opensource.org/licenses/bsd-license.php)             |
        +--------------------------------------------------------------------------+

        </div>

    -   com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 (test)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep4" style="display:none">

        +--------------------------------------------------------------------------+
        | RandomizedTesting Randomized Runner                                      |
        +==========================================================================+
        | **Description:** Foundation classes and rules for applying the           |
        | principles of Randomized Testing.                                        |
        |                                                                          |
        | **URL:** <http://labs.carrotsearch.com/randomizedtesting-runner>         |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

        -   junit:junit:jar:4.11 (test)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep6" style="display:none">

            +--------------------------------------------------------------------------+
            | JUnit                                                                    |
            +==========================================================================+
            | **Description:** JUnit is a regression testing framework written by      |
            | Erich Gamma and Kent Beck. It is used by the developer who implements    |
            | unit tests in Java.                                                      |
            |                                                                          |
            | **URL:** <http://junit.org>                                              |
            |                                                                          |
            | **Project License:** [Common Public License Version                      |
            | 1.0](http://www.opensource.org/licenses/cpl1.0.txt)                      |
            +--------------------------------------------------------------------------+

            </div>
    -   org.apache.lucene:lucene-test-framework:jar:5.3.0 (test)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep8" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Test Framework                                                    |
        +==========================================================================+
        | **Description:** Apache Lucene Java Test Framework                       |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-test-framework>  |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

        -   org.apache.lucene:lucene-codecs:jar:5.3.0 (test)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep10" style="display:none">

            +--------------------------------------------------------------------------+
            | Lucene codecs                                                            |
            +==========================================================================+
            | **Description:** Codecs and postings formats for Apache Lucene.          |
            |                                                                          |
            | **URL:** <http://lucene.apache.org/lucene-parent/lucene-codecs>          |
            |                                                                          |
            | **Project License:** [Apache                                             |
            | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
            +--------------------------------------------------------------------------+

            </div>

        -   org.apache.ant:ant:jar:1.8.2 (test)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep12" style="display:none">

            +--------------------------------------------------------------------------+
            | Apache Ant Core                                                          |
            +==========================================================================+
            | **Description:** master POM                                              |
            |                                                                          |
            | **URL:** <http://ant.apache.org/ant/>                                    |
            |                                                                          |
            | **Project License:** [The Apache Software License, Version               |
            | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
            +--------------------------------------------------------------------------+

            </div>
    -   org.apache.httpcomponents:httpclient:jar:4.3.6 (test)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep14" style="display:none">

        +--------------------------------------------------------------------------+
        | Apache HttpClient                                                        |
        +==========================================================================+
        | **Description:** HttpComponents Client                                   |
        |                                                                          |
        | **URL:** <http://hc.apache.org/httpcomponents-client>                    |
        |                                                                          |
        | **Project License:** [Apache License, Version                            |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

        -   org.apache.httpcomponents:httpcore:jar:4.3.3 (test)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep16" style="display:none">

            +--------------------------------------------------------------------------+
            | Apache HttpCore                                                          |
            +==========================================================================+
            | **Description:** HttpComponents Core (blocking I/O)                      |
            |                                                                          |
            | **URL:** <http://hc.apache.org/httpcomponents-core-ga>                   |
            |                                                                          |
            | **Project License:** [Apache License, Version                            |
            | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
            +--------------------------------------------------------------------------+

            </div>

        -   commons-logging:commons-logging:jar:1.1.3 (test)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep18" style="display:none">

            +--------------------------------------------------------------------------+
            | Commons Logging                                                          |
            +==========================================================================+
            | **Description:** Commons Logging is a thin adapter allowing configurable |
            | bridging to other, well known logging systems.                           |
            |                                                                          |
            | **URL:** <http://commons.apache.org/proper/commons-logging/>             |
            |                                                                          |
            | **Project License:** [The Apache Software License, Version               |
            | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
            +--------------------------------------------------------------------------+

            </div>

        -   commons-codec:commons-codec:jar:1.6 (test)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep20" style="display:none">

            +--------------------------------------------------------------------------+
            | Commons Codec                                                            |
            +==========================================================================+
            | **Description:** The codec package contains simple encoder and decoders  |
            | for various formats such as Base64 and Hexadecimal. In addition to these |
            | widely used encoders and decoders, the codec package also maintains a    |
            | collection of phonetic encoding utilities.                               |
            |                                                                          |
            | **URL:** <http://commons.apache.org/codec/>                              |
            |                                                                          |
            | **Project License:** [The Apache Software License, Version               |
            | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
            +--------------------------------------------------------------------------+

            </div>
    -   com.google.jimfs:jimfs:jar:1.0 (test)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep22" style="display:none">

        +--------------------------------------------------------------------------+
        | Jimfs                                                                    |
        +==========================================================================+
        | **Description:** Jimfs is an in-memory implementation of Java 7's        |
        | java.nio.file abstract file system API.                                  |
        |                                                                          |
        | **URL:** <https://github.com/google/jimfs/jimfs>                         |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-core:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep24" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Core                                                              |
        +==========================================================================+
        | **Description:** Apache Lucene Java Core                                 |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-core>            |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-backward-codecs:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep26" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Memory                                                            |
        +==========================================================================+
        | **Description:** Codecs for older versions of Lucene.                    |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-backward-codecs> |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-analyzers-common:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep28" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Common Analyzers                                                  |
        +==========================================================================+
        | **Description:** Additional Analyzers                                    |
        |                                                                          |
        | **URL:**                                                                 |
        | <http://lucene.apache.org/lucene-parent/lucene-analyzers-common>         |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-queries:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep30" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Queries                                                           |
        +==========================================================================+
        | **Description:** Lucene Queries Module                                   |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-queries>         |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-memory:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep32" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Memory                                                            |
        +==========================================================================+
        | **Description:** High-performance single-document index to compare       |
        | against Query                                                            |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-memory>          |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-highlighter:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep34" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Highlighter                                                       |
        +==========================================================================+
        | **Description:** This is the highlighter for apache lucene java          |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-highlighter>     |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.apache.lucene:lucene-queryparser:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep36" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene QueryParsers                                                      |
        +==========================================================================+
        | **Description:** Lucene QueryParsers module                              |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-queryparser>     |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

        -   org.apache.lucene:lucene-sandbox:jar:5.3.0 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep38" style="display:none">

            +--------------------------------------------------------------------------+
            | Lucene Sandbox                                                           |
            +==========================================================================+
            | **Description:** Lucene Sandbox                                          |
            |                                                                          |
            | **URL:** <http://lucene.apache.org/lucene-parent/lucene-sandbox>         |
            |                                                                          |
            | **Project License:** [Apache                                             |
            | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
            +--------------------------------------------------------------------------+

            </div>
    -   org.apache.lucene:lucene-suggest:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep40" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Suggest                                                           |
        +==========================================================================+
        | **Description:** Lucene Suggest Module                                   |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-suggest>         |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

        -   org.apache.lucene:lucene-misc:jar:5.3.0 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep42" style="display:none">

            +--------------------------------------------------------------------------+
            | Lucene Miscellaneous                                                     |
            +==========================================================================+
            | **Description:** Miscellaneous Lucene extensions                         |
            |                                                                          |
            | **URL:** <http://lucene.apache.org/lucene-parent/lucene-misc>            |
            |                                                                          |
            | **Project License:** [Apache                                             |
            | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
            +--------------------------------------------------------------------------+

            </div>
    -   org.apache.lucene:lucene-join:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep44" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Join                                                              |
        +==========================================================================+
        | **Description:** Lucene Join Module                                      |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-join>            |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

        -   org.apache.lucene:lucene-grouping:jar:5.3.0 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep46" style="display:none">

            +--------------------------------------------------------------------------+
            | Lucene Grouping                                                          |
            +==========================================================================+
            | **Description:** Lucene Grouping Module                                  |
            |                                                                          |
            | **URL:** <http://lucene.apache.org/lucene-parent/lucene-grouping>        |
            |                                                                          |
            | **Project License:** [Apache                                             |
            | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
            +--------------------------------------------------------------------------+

            </div>
    -   org.apache.lucene:lucene-spatial:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep48" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Spatial                                                           |
        +==========================================================================+
        | **Description:** Spatial Strategies for Apache Lucene                    |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-spatial>         |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

        -   org.apache.lucene:lucene-spatial3d:jar:5.3.0 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep50" style="display:none">

            +--------------------------------------------------------------------------+
            | Lucene Spatial 3D                                                        |
            +==========================================================================+
            | **Description:** Lucene Spatial shapes implemented using 3D planar       |
            | geometry                                                                 |
            |                                                                          |
            | **URL:** <http://lucene.apache.org/lucene-parent/lucene-spatial3d>       |
            |                                                                          |
            | **Project License:** [Apache                                             |
            | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
            +--------------------------------------------------------------------------+

            </div>
    -   org.apache.lucene:lucene-expressions:jar:5.3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep52" style="display:none">

        +--------------------------------------------------------------------------+
        | Lucene Expressions                                                       |
        +==========================================================================+
        | **Description:** Dynamically computed values to sort/facet/search on     |
        | based on a pluggable grammar.                                            |
        |                                                                          |
        | **URL:** <http://lucene.apache.org/lucene-parent/lucene-expressions>     |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

        -   org.antlr:antlr-runtime:jar:3.5 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep54" style="display:none">

            +--------------------------------------------------------------------------+
            | ANTLR 3 Runtime                                                          |
            +==========================================================================+
            | **Description:** A framework for constructing recognizers, compilers,    |
            | and translators from grammatical descriptions containing Java, C\#, C++, |
            | or Python actions.                                                       |
            |                                                                          |
            | **URL:** <http://www.antlr.org>                                          |
            |                                                                          |
            | **Project License:** [BSD licence](http://antlr.org/license.html)        |
            +--------------------------------------------------------------------------+

            </div>

        -   org.ow2.asm:asm:jar:4.1 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep56" style="display:none">

            +--------------------------------------------------------------------------+
            | ASM Core                                                                 |
            +==========================================================================+
            | **Description:** A very small and fast Java bytecode manipulation        |
            | framework                                                                |
            |                                                                          |
            | **URL:** <http://asm.objectweb.org/asm/>                                 |
            |                                                                          |
            | **Project License:** [BSD](http://asm.objectweb.org/license.html)        |
            +--------------------------------------------------------------------------+

            </div>

        -   org.ow2.asm:asm-commons:jar:4.1 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep58" style="display:none">

            +--------------------------------------------------------------------------+
            | ASM Commons                                                              |
            +==========================================================================+
            | **Description:** A very small and fast Java bytecode manipulation        |
            | framework                                                                |
            |                                                                          |
            | **URL:** <http://asm.objectweb.org/asm-commons/>                         |
            |                                                                          |
            | **Project License:** [BSD](http://asm.objectweb.org/license.html)        |
            +--------------------------------------------------------------------------+

            </div>
    -   com.spatial4j:spatial4j:jar:0.4.1 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep60" style="display:none">

        +--------------------------------------------------------------------------+
        | Spatial4J                                                                |
        +==========================================================================+
        | **Description:** Spatial4j is a general purpose spatial / geospatial ASL |
        | licensed open-source Java library. It's core capabilities are 3-fold: to |
        | provide common geospatially-aware shapes, to provide distance            |
        | calculations and other math, and to read shapes in WKT format.           |
        |                                                                          |
        | **URL:** <https://github.com/spatial4j/spatial4j>                        |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   com.vividsolutions:jts:jar:1.13 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep62" style="display:none">

        +--------------------------------------------------------------------------+
        | JTS Topology Suite                                                       |
        +==========================================================================+
        | **Description:** The JTS Topology Suite is an API for modelling and      |
        | manipulating 2-dimensional linear geometry. It provides numerous         |
        | geometric predicates and functions. JTS conforms to the Simple Features  |
        | Specification for SQL published by the Open GIS Consortium.              |
        |                                                                          |
        | **URL:** <http://sourceforge.net/projects/jts-topo-suite>                |
        |                                                                          |
        | **Project License:** [Lesser General Public                              |
        | License (LGPL)](http://www.gnu.org/copyleft/lesser.txt)                  |
        +--------------------------------------------------------------------------+

        </div>

    -   com.github.spullara.mustache.java:compiler:jar:0.8.13 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep64" style="display:none">

        +--------------------------------------------------------------------------+
        | compiler                                                                 |
        +==========================================================================+
        | **Description:** Implementation of mustache.js for Java                  |
        |                                                                          |
        | **URL:** <http://github.com/spullara/mustache.java>                      |
        |                                                                          |
        | **Project License:** [Apache License                                     |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0)                         |
        +--------------------------------------------------------------------------+

        </div>

    -   com.google.guava:guava:jar:18.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep66" style="display:none">

        +--------------------------------------------------------------------------+
        | Guava: Google Core Libraries for Java                                    |
        +==========================================================================+
        | **Description:** Guava is a suite of core and expanded libraries that    |
        | include utility classes, google's collections, io classes, and much      |
        | much more. Guava has only one code dependency - javax.annotation, per    |
        | the JSR-305 spec.                                                        |
        |                                                                          |
        | **URL:** <http://code.google.com/p/guava-libraries/guava>                |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   com.carrotsearch:hppc:jar:0.7.1 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep68" style="display:none">

        +--------------------------------------------------------------------------+
        | HPPC Collections                                                         |
        +==========================================================================+
        | **Description:** High Performance Primitive Collections. Fundamental     |
        | data structures (maps, sets, lists, stacks, queues) generated for        |
        | combinations of object and primitive types to conserve JVM memory and    |
        | speed up execution.                                                      |
        |                                                                          |
        | **URL:** <http://labs.carrotsearch.com/hppc.html/hppc>                   |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   joda-time:joda-time:jar:2.8.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep70" style="display:none">

        +--------------------------------------------------------------------------+
        | Joda-Time                                                                |
        +==========================================================================+
        | **Description:** Date and time library to replace JDK date handling      |
        |                                                                          |
        | **URL:** <http://www.joda.org/joda-time/>                                |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   org.joda:joda-convert:jar:1.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep72" style="display:none">

        +--------------------------------------------------------------------------+
        | Joda convert                                                             |
        +==========================================================================+
        | **Description:** Library to convert Objects to and from String           |
        |                                                                          |
        | **URL:** <http://joda-convert.sourceforge.net>                           |
        |                                                                          |
        | **Project License:** [Apache                                             |
        | 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
        +--------------------------------------------------------------------------+

        </div>

    -   com.fasterxml.jackson.core:jackson-core:jar:2.6.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep74" style="display:none">

        +--------------------------------------------------------------------------+
        | Jackson-core                                                             |
        +==========================================================================+
        | **Description:** Core Jackson abstractions, basic JSON streaming API     |
        | implementation                                                           |
        |                                                                          |
        | **URL:** <https://github.com/FasterXML/jackson-core>                     |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   com.fasterxml.jackson.dataformat:jackson-dataformat-smile:jar:2.6.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep76" style="display:none">

        +--------------------------------------------------------------------------+
        | Jackson-dataformat-Smile                                                 |
        +==========================================================================+
        | **Description:** Support for reading and writing Smile ("binary JSON")   |
        | encoded data using Jackson abstractions (streaming API, data binding,    |
        | tree model)                                                              |
        |                                                                          |
        | **URL:** <http://wiki.fasterxml.com/JacksonForSmile>                     |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.6.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep78" style="display:none">

        +--------------------------------------------------------------------------+
        | Jackson-dataformat-YAML                                                  |
        +==========================================================================+
        | **Description:** Support for reading and writing YAML-encoded data via   |
        | Jackson abstractions.                                                    |
        |                                                                          |
        | **URL:** <https://github.com/FasterXML/jackson>                          |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

        -   org.yaml:snakeyaml:jar:1.15 (compile)
            ![Information](./images/icon_info_sml.gif)
            <div id="_dep80" style="display:none">

            +--------------------------------------------------------------------------+
            | SnakeYAML                                                                |
            +==========================================================================+
            | **Description:** YAML 1.1 parser and emitter for Java                    |
            |                                                                          |
            | **URL:** <http://www.snakeyaml.org>                                      |
            |                                                                          |
            | **Project License:** [Apache License Version 2.0](LICENSE.txt)           |
            +--------------------------------------------------------------------------+

            </div>
    -   com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep82" style="display:none">

        +--------------------------------------------------------------------------+
        | Jackson-dataformat-CBOR                                                  |
        +==========================================================================+
        | **Description:** Support for reading and writing Concise Binary Object   |
        | Representation (\[CBOR\](https://www.rfc-editor.org/info/rfc7049)        |
        | encoded data using Jackson abstractions (streaming API, data binding,    |
        | tree model)                                                              |
        |                                                                          |
        | **URL:** <http://wiki.fasterxml.com/JacksonForCbor>                      |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   io.netty:netty:jar:3.10.5.Final (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep84" style="display:none">

        +--------------------------------------------------------------------------+
        | Netty                                                                    |
        +==========================================================================+
        | **Description:** The Netty project is an effort to provide an            |
        | asynchronous event-driven network application framework and tools for    |
        | rapid development of maintainable high performance and high scalability  |
        | protocol servers and clients. In other words, Netty is a NIO client      |
        | server framework which enables quick and easy development of network     |
        | applications such as protocol servers and clients. It greatly simplifies |
        | and streamlines network programming such as TCP and UDP socket server.   |
        |                                                                          |
        | **URL:** <http://netty.io/>                                              |
        |                                                                          |
        | **Project License:** [Apache License, Version                            |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0)                         |
        +--------------------------------------------------------------------------+

        </div>

    -   com.ning:compress-lzf:jar:1.0.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep86" style="display:none">

        +--------------------------------------------------------------------------+
        | Compress-LZF                                                             |
        +==========================================================================+
        | **Description:** Compression codec for LZF encoding for particularly     |
        | encoding/decoding, with reasonable compression. Compressor is basic      |
        | Lempel-Ziv codec, without Huffman (deflate/gzip) or                      |
        | statistical post-encoding. See                                           |
        | "http://oldhome.schmorp.de/marc/liblzf.html" for more on original        |
        | LZF package.                                                             |
        |                                                                          |
        | **URL:** <http://github.com/ning/compress>                               |
        |                                                                          |
        | **Project License:** [Apache License                                     |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)                    |
        +--------------------------------------------------------------------------+

        </div>

    -   com.tdunning:t-digest:jar:3.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep88" style="display:none">

        +--------------------------------------------------------------------------+
        | T-Digest                                                                 |
        +==========================================================================+
        | **Description:** Data structure which allows accurate estimation of      |
        | quantiles and related rank statistics                                    |
        |                                                                          |
        | **URL:** <https://github.com/tdunning/t-digest>                          |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   org.hdrhistogram:HdrHistogram:jar:2.1.6 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep90" style="display:none">

        +--------------------------------------------------------------------------+
        | HdrHistogram                                                             |
        +==========================================================================+
        | **Description:** HdrHistogram supports the recording and analyzing       |
        | sampled data value counts across a configurable integer value range with |
        | configurable value precision within the range. Value precision is        |
        | expressed as the number of significant digits in the value recording,    |
        | and provides control over value quantization behavior across the value   |
        | range and the subsequent value resolution at any given level.            |
        |                                                                          |
        | **URL:** <http://hdrhistogram.github.io/HdrHistogram/>                   |
        |                                                                          |
        | **Project License:** [Public Domain, per Creative Commons                |
        | CC0](http://creativecommons.org/publicdomain/zero/1.0/)                  |
        +--------------------------------------------------------------------------+

        </div>

    -   commons-cli:commons-cli:jar:1.3.1 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep92" style="display:none">

        +--------------------------------------------------------------------------+
        | Apache Commons CLI                                                       |
        +==========================================================================+
        | **Description:** Apache Commons CLI provides a simple API for            |
        | presenting, processing and validating a command line interface.          |
        |                                                                          |
        | **URL:** <http://commons.apache.org/proper/commons-cli/>                 |
        |                                                                          |
        | **Project License:** [Apache License, Version                            |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   org.codehaus.groovy:groovy-all:jar:indy:2.4.4 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep94" style="display:none">

        +--------------------------------------------------------------------------+
        | Apache Groovy                                                            |
        +==========================================================================+
        | **Description:** Groovy: A powerful, dynamic language for the JVM        |
        |                                                                          |
        | **URL:** <http://groovy-lang.org>                                        |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   log4j:log4j:jar:1.2.17 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep96" style="display:none">

        +--------------------------------------------------------------------------+
        | Apache Log4j                                                             |
        +==========================================================================+
        | **Description:** Apache Log4j 1.2                                        |
        |                                                                          |
        | **URL:** <http://logging.apache.org/log4j/1.2/>                          |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   log4j:apache-log4j-extras:jar:1.2.17 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep98" style="display:none">

        +--------------------------------------------------------------------------+
        | Apache Extras™ for Apache log4j™.                                        |
        +==========================================================================+
        | **Description:** This package provides additional appenders, filters and |
        | other capabilities for version 1.2 of Apache log4j™. Several of these    |
        | were backported from the abandoned Apache log4j 1.3 development effort.  |
        |                                                                          |
        | **URL:** <http://logging.apache.org/log4j/extras>                        |
        |                                                                          |
        | **Project License:** [The Apache Software License, Version               |
        | 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                     |
        +--------------------------------------------------------------------------+

        </div>

    -   org.slf4j:slf4j-api:jar:1.6.2 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep100" style="display:none">

        +--------------------------------------------------------------------------+
        | SLF4J API Module                                                         |
        +==========================================================================+
        | **Description:** The slf4j API                                           |
        |                                                                          |
        | **URL:** <http://www.slf4j.org>                                          |
        |                                                                          |
        | **Project License:** [MIT                                                |
        | License](http://www.opensource.org/licenses/mit-license.php)             |
        +--------------------------------------------------------------------------+

        </div>

    -   net.java.dev.jna:jna:jar:4.1.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep102" style="display:none">

        +--------------------------------------------------------------------------+
        | Java Native Access                                                       |
        +==========================================================================+
        | **Description:** Java Native Access                                      |
        |                                                                          |
        | **URL:** <https://github.com/twall/jna>                                  |
        |                                                                          |
        | **Project License:** [LGPL, version                                      |
        | 2.1](http://www.gnu.org/licenses/licenses.html)[ASL, version             |
        | 2](http://www.apache.org/licenses/)                                      |
        +--------------------------------------------------------------------------+

        </div>

    -   com.twitter:jsr166e:jar:1.1.0 (compile)
        ![Information](./images/icon_info_sml.gif)
        <div id="_dep104" style="display:none">

        +--------------------------------------------------------------------------+
        | JSR166e                                                                  |
        +==========================================================================+
        | **Description:** JSR166e                                                 |
        |                                                                          |
        | **URL:** <http://github.com/twitter/jsr166e>                             |
        |                                                                          |
        | **Project License:** [CC0 1.0                                            |
        | Universal](http://creativecommons.org/publicdomain/zero/1.0/)            |
        +--------------------------------------------------------------------------+

        </div>

</div>

</div>

<div class="section">

Licenses
--------

**ASL, version 2:** Java Native Access

**LGPL, version 2.1:** Java Native Access

**Apache 2:** Joda convert, Joda-Time, Lucene Common Analyzers, Lucene
Core, Lucene Expressions, Lucene Grouping, Lucene Highlighter, Lucene
Join, Lucene Memory, Lucene Miscellaneous, Lucene Queries, Lucene
QueryParsers, Lucene Sandbox, Lucene Spatial, Lucene Spatial 3D, Lucene
Suggest, Lucene Test Framework, Lucene codecs

**New BSD License:** Hamcrest All

**BSD:** ASM Commons, ASM Core

**BSD licence:** ANTLR 3 Runtime

**Public Domain, per Creative Commons CC0:** HdrHistogram

**Apache License, Version 2.0:** Apache Commons CLI, Apache HttpClient,
Apache HttpCore, Netty

**Apache License 2.0:** Compress-LZF, compiler

**Common Public License Version 1.0:** JUnit

**MIT License:** SLF4J API Module

**The Apache Software License, Version 2.0:** Apache Ant Core, Apache
Extras™ for Apache log4j™., Apache Groovy, Apache Log4j, Commons Codec,
Commons Logging, Elasticsearch: Core, Guava: Google Core Libraries for
Java, HPPC Collections, Jackson-core, Jackson-dataformat-CBOR,
Jackson-dataformat-Smile, Jackson-dataformat-YAML, Jimfs,
RandomizedTesting Randomized Runner, Spatial4J, T-Digest

**CC0 1.0 Universal:** JSR166e

**Apache License Version 2.0:** SnakeYAML

**Lesser General Public License (LGPL):** JTS Topology Suite

</div>

<div class="section">

Dependency File Details
-----------------------

  Filename                              Size                Entries           Classes           Packages       JDK Rev   Debug
  ------------------------------------- ------------------- ----------------- ----------------- -------------- --------- -------------
  hppc-0.7.1.jar                        1.09 MB             915               901               5              1.6       debug
  randomizedtesting-runner-2.1.16.jar   207.89 kB           173               159               5              1.6       debug
  jackson-core-2.6.2.jar                252.76 kB           116               93                9              1.6       debug
  jackson-dataformat-cbor-2.6.2.jar     47.02 kB            25                10                1              1.6       debug
  jackson-dataformat-smile-2.6.2.jar    74.16 kB            34                17                2              1.6       debug
  jackson-dataformat-yaml-2.6.2.jar     312.93 kB           253               210               20             1.6       debug
  guava-18.0.jar                        2.15 MB             1,719             1,690             17             1.6       debug
  jimfs-1.0.jar                         190.74 kB           129               116               1              1.6       debug
  compress-lzf-1.0.2.jar                77.86 kB            59                42                6              1.6       debug
  t-digest-3.0.jar                      48.59 kB            31                20                1              1.6       debug
  jsr166e-1.1.0.jar                     60.77 kB            37                27                1              1.6       debug
  commons-cli-1.3.1.jar                 51.75 kB            39                26                1              1.5       debug
  commons-codec-1.6.jar                 227.32 kB           218               76                6              1.5       debug
  commons-logging-1.1.3.jar             60.60 kB            42                28                2              1.1       debug
  netty-3.10.5.Final.jar                1.27 MB             950               880               43             1.5       debug
  joda-time-2.8.2.jar                   607.41 kB           749               246               7              1.5       debug
  junit-4.11.jar                        239.30 kB           266               233               28             1.5       debug
  ant-1.8.2.jar                         1.84 MB             1,168             1,090             59             1.4       debug
  httpclient-4.3.6.jar                  578.13 kB           459               420               24             1.5       debug
  httpcore-4.3.3.jar                    276.17 kB           260               232               15             1.5       debug
  lucene-analyzers-common-5.3.0.jar     1.49 MB             673               563               61             1.6       debug
  lucene-backward-codecs-5.3.0.jar      374.68 kB           223               202               10             1.6       debug
  lucene-codecs-5.3.0.jar               408.73 kB           224               206               6              1.6       debug
  lucene-core-5.3.0.jar                 2.25 MB             1,563             1,532             21             1.6       debug
  lucene-grouping-5.3.0.jar             105.97 kB           76                65                3              1.6       debug
  lucene-highlighter-5.3.0.jar          141.08 kB           97                86                3              1.6       debug
  lucene-join-5.3.0.jar                 116.26 kB           90                81                1              1.6       debug
  lucene-memory-5.3.0.jar               32.51 kB            21                12                1              1.6       debug
  lucene-misc-5.3.0.jar                 168.27 kB           122               107               7              1.6       debug
  lucene-queries-5.3.0.jar              206.93 kB           174               162               5              1.6       debug
  lucene-queryparser-5.3.0.jar          391.91 kB           312               273               26             1.6       debug
  lucene-sandbox-5.3.0.jar              260.50 kB           168               148               8              1.6       debug
  lucene-spatial-5.3.0.jar              194.02 kB           139               122               10             1.6       debug
  lucene-spatial3d-5.3.0.jar            121.56 kB           67                59                1              1.6       debug
  lucene-suggest-5.3.0.jar              240.22 kB           150               132               7              1.6       debug
  lucene-test-framework-5.3.0.jar       6.23 MB             482               451               19             1.6       debug
  hamcrest-all-1.3.jar                  299.39 kB           249               204               23             1.5       debug
  HdrHistogram-2.1.6.jar                107.15 kB           67                58                1              1.6       debug
  joda-convert-1.2.jar                  37.56 kB            52                40                1              1.5       debug
  snakeyaml-1.15.jar                    262.98 kB           237               201               19             1.5       debug
  compiler-0.8.13.jar                   108.10 kB           112               94                8              1.6       debug
  spatial4j-0.4.1.jar                   99.78 kB            67                48                9              1.6       debug
  jts-1.13.jar                          776.36 kB           611               539               60             1.5       debug
  apache-log4j-extras-1.2.17.jar        438.28 kB           323               284               23             1.4       debug
  log4j-1.2.17.jar                      478.40 kB           353               314               21             1.4       debug
  jna-4.1.0.jar                         893.16 kB           141               104               3              1.6       debug
  antlr-runtime-3.5.jar                 163.80 kB           130               117               4              1.5       debug
  lucene-expressions-5.3.0.jar          74.07 kB            49                39                2              1.6       debug
  groovy-all-2.4.4-indy.jar             6.49 MB             4,643             3,523             113            1.6       debug
  asm-4.1.jar                           46.25 kB            24                23                2              1.2       release
  asm-commons-4.1.jar                   37.20 kB            23                22                1              1.2       release
  slf4j-api-1.6.2.jar                   25.09 kB            34                23                3              1.3       debug
  Total                                 Size                Entries           Classes           Packages       JDK Rev   Debug
  52                                    32.51 MB            19,338            16,350            735            1.6       50
  compile: 41                           compile: 22.00 MB   compile: 15,668   compile: 13,135   compile: 547   -         compile: 39
  test: 11                              test: 10.51 MB      test: 3,670       test: 3,215       test: 188      -         test: 11

</div>

<div class="section">

Dependency Repository Locations
-------------------------------

  Repo ID                          URL                                                          Release   Snapshot   Blacklisted
  -------------------------------- ------------------------------------------------------------ --------- ---------- -------------
  sonatype.releases                <https://oss.sonatype.org/content/repositories/releases>     Yes       Yes        -
  oss-snapshots                    <https://oss.sonatype.org/content/repositories/snapshots/>   Yes       Yes        -
  apache.snapshots                 <http://repository.apache.org/snapshots>                     -         -          -
  sonatype-nexus-snapshots         <https://oss.sonatype.org/content/repositories/snapshots>    -         Yes        -
  spy                              <http://files.couchbase.com/maven2/>                         Yes       -          -
  maven2-repository.dev.java.net   <http://download.java.net/maven/2/>                          Yes       Yes        Yes
  central                          <http://repo.maven.apache.org/maven2>                        Yes       -          -
  elasticsearch-releases           <http://maven.elasticsearch.org/releases>                    Yes       -          -
  Twitter                          <http://maven.twttr.com/>                                    Yes       Yes        -

Repository locations for each of the Dependencies.

  Artifact                                                                 sonatype.releases                                                                                                                                                                                                                                                  oss-snapshots   apache.snapshots   sonatype-nexus-snapshots   spy   central                                                                                                                                                                                                                      elasticsearch-releases   Twitter
  ------------------------------------------------------------------------ ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ --------------- ------------------ -------------------------- ----- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------ ---------
  com.carrotsearch:hppc:jar:0.7.1                                          [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar)                                                               -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar)                                                               -                        -
  com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16   [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar)   -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar)   -                        -
  com.fasterxml.jackson.core:jackson-core:jar:2.6.2                        [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/core/jackson-core/2.6.2/jackson-core-2.6.2.jar)                                     -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.6.2/jackson-core-2.6.2.jar)                                     -                        -
  com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.2       [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-cbor/2.6.2/jackson-dataformat-cbor-2.6.2.jar)         -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-cbor/2.6.2/jackson-dataformat-cbor-2.6.2.jar)         -                        -
  com.fasterxml.jackson.dataformat:jackson-dataformat-smile:jar:2.6.2      [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-smile/2.6.2/jackson-dataformat-smile-2.6.2.jar)       -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-smile/2.6.2/jackson-dataformat-smile-2.6.2.jar)       -                        -
  com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.6.2       [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.6.2/jackson-dataformat-yaml-2.6.2.jar)         -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.6.2/jackson-dataformat-yaml-2.6.2.jar)         -                        -
  com.google.guava:guava:jar:18.0                                          [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/google/guava/guava/18.0/guava-18.0.jar)                                                               -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/google/guava/guava/18.0/guava-18.0.jar)                                                               -                        -
  com.google.jimfs:jimfs:jar:1.0                                           [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/google/jimfs/jimfs/1.0/jimfs-1.0.jar)                                                                 -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/google/jimfs/jimfs/1.0/jimfs-1.0.jar)                                                                 -                        -
  com.ning:compress-lzf:jar:1.0.2                                          [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/ning/compress-lzf/1.0.2/compress-lzf-1.0.2.jar)                                                       -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/ning/compress-lzf/1.0.2/compress-lzf-1.0.2.jar)                                                       -                        -
  com.tdunning:t-digest:jar:3.0                                            [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/tdunning/t-digest/3.0/t-digest-3.0.jar)                                                               -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/tdunning/t-digest/3.0/t-digest-3.0.jar)                                                               -                        -
  com.twitter:jsr166e:jar:1.1.0                                            [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/twitter/jsr166e/1.1.0/jsr166e-1.1.0.jar)                                                              -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/twitter/jsr166e/1.1.0/jsr166e-1.1.0.jar)                                                              -                        -
  commons-cli:commons-cli:jar:1.3.1                                        -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-cli/commons-cli/1.3.1/commons-cli-1.3.1.jar)                                                      -                        -
  commons-codec:commons-codec:jar:1.6                                      -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.jar)                                                    -                        -
  commons-logging:commons-logging:jar:1.1.3                                -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.1.3/commons-logging-1.1.3.jar)                                          -                        -
  io.netty:netty:jar:3.10.5.Final                                          [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/io/netty/netty/3.10.5.Final/netty-3.10.5.Final.jar)                                                       -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/io/netty/netty/3.10.5.Final/netty-3.10.5.Final.jar)                                                       -                        -
  joda-time:joda-time:jar:2.8.2                                            [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/joda-time/joda-time/2.8.2/joda-time-2.8.2.jar)                                                            -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/joda-time/joda-time/2.8.2/joda-time-2.8.2.jar)                                                            -                        -
  junit:junit:jar:4.11                                                     [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/junit/junit/4.11/junit-4.11.jar)                                                                          -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/junit/junit/4.11/junit-4.11.jar)                                                                          -                        -
  org.apache.ant:ant:jar:1.8.2                                             -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/ant/ant/1.8.2/ant-1.8.2.jar)                                                                   -                        -
  org.apache.httpcomponents:httpclient:jar:4.3.6                           -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.3.6/httpclient-4.3.6.jar)                                          -                        -
  org.apache.httpcomponents:httpcore:jar:4.3.3                             -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.3.3/httpcore-4.3.3.jar)                                              -                        -
  org.apache.lucene:lucene-analyzers-common:jar:5.3.0                      -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-analyzers-common/5.3.0/lucene-analyzers-common-5.3.0.jar)                        -                        -
  org.apache.lucene:lucene-backward-codecs:jar:5.3.0                       -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-backward-codecs/5.3.0/lucene-backward-codecs-5.3.0.jar)                          -                        -
  org.apache.lucene:lucene-codecs:jar:5.3.0                                -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-codecs/5.3.0/lucene-codecs-5.3.0.jar)                                            -                        -
  org.apache.lucene:lucene-core:jar:5.3.0                                  -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-core/5.3.0/lucene-core-5.3.0.jar)                                                -                        -
  org.apache.lucene:lucene-grouping:jar:5.3.0                              -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-grouping/5.3.0/lucene-grouping-5.3.0.jar)                                        -                        -
  org.apache.lucene:lucene-highlighter:jar:5.3.0                           -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-highlighter/5.3.0/lucene-highlighter-5.3.0.jar)                                  -                        -
  org.apache.lucene:lucene-join:jar:5.3.0                                  -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-join/5.3.0/lucene-join-5.3.0.jar)                                                -                        -
  org.apache.lucene:lucene-memory:jar:5.3.0                                -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-memory/5.3.0/lucene-memory-5.3.0.jar)                                            -                        -
  org.apache.lucene:lucene-misc:jar:5.3.0                                  -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-misc/5.3.0/lucene-misc-5.3.0.jar)                                                -                        -
  org.apache.lucene:lucene-queries:jar:5.3.0                               -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-queries/5.3.0/lucene-queries-5.3.0.jar)                                          -                        -
  org.apache.lucene:lucene-queryparser:jar:5.3.0                           -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-queryparser/5.3.0/lucene-queryparser-5.3.0.jar)                                  -                        -
  org.apache.lucene:lucene-sandbox:jar:5.3.0                               -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-sandbox/5.3.0/lucene-sandbox-5.3.0.jar)                                          -                        -
  org.apache.lucene:lucene-spatial:jar:5.3.0                               -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-spatial/5.3.0/lucene-spatial-5.3.0.jar)                                          -                        -
  org.apache.lucene:lucene-spatial3d:jar:5.3.0                             -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-spatial3d/5.3.0/lucene-spatial3d-5.3.0.jar)                                      -                        -
  org.apache.lucene:lucene-suggest:jar:5.3.0                               -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-suggest/5.3.0/lucene-suggest-5.3.0.jar)                                          -                        -
  org.apache.lucene:lucene-test-framework:jar:5.3.0                        -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-test-framework/5.3.0/lucene-test-framework-5.3.0.jar)                            -                        -
  org.hamcrest:hamcrest-all:jar:1.3                                        [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                       -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                       -                        -
  org.hdrhistogram:HdrHistogram:jar:2.1.6                                  [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hdrhistogram/HdrHistogram/2.1.6/HdrHistogram-2.1.6.jar)                                               -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hdrhistogram/HdrHistogram/2.1.6/HdrHistogram-2.1.6.jar)                                               -                        -
  org.joda:joda-convert:jar:1.2                                            -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/joda/joda-convert/1.2/joda-convert-1.2.jar)                                                           -                        -
  org.yaml:snakeyaml:jar:1.15                                              [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar)                                                               -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar)                                                               -                        -
  com.github.spullara.mustache.java:compiler:jar:0.8.13                    [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/github/spullara/mustache/java/compiler/0.8.13/compiler-0.8.13.jar)                                    -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/github/spullara/mustache/java/compiler/0.8.13/compiler-0.8.13.jar)                                    -                        -
  com.spatial4j:spatial4j:jar:0.4.1                                        [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/spatial4j/spatial4j/0.4.1/spatial4j-0.4.1.jar)                                                        -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/spatial4j/spatial4j/0.4.1/spatial4j-0.4.1.jar)                                                        -                        -
  com.vividsolutions:jts:jar:1.13                                          [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/vividsolutions/jts/1.13/jts-1.13.jar)                                                                 -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/vividsolutions/jts/1.13/jts-1.13.jar)                                                                 -                        -
  log4j:apache-log4j-extras:jar:1.2.17                                     [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/log4j/apache-log4j-extras/1.2.17/apache-log4j-extras-1.2.17.jar)                                          -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/log4j/apache-log4j-extras/1.2.17/apache-log4j-extras-1.2.17.jar)                                          -                        -
  log4j:log4j:jar:1.2.17                                                   [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/log4j/log4j/1.2.17/log4j-1.2.17.jar)                                                                      -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/log4j/log4j/1.2.17/log4j-1.2.17.jar)                                                                      -                        -
  net.java.dev.jna:jna:jar:4.1.0                                           -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/net/java/dev/jna/jna/4.1.0/jna-4.1.0.jar)                                                                 -                        -
  org.antlr:antlr-runtime:jar:3.5                                          [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/antlr/antlr-runtime/3.5/antlr-runtime-3.5.jar)                                                        -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/antlr/antlr-runtime/3.5/antlr-runtime-3.5.jar)                                                        -                        -
  org.apache.lucene:lucene-expressions:jar:5.3.0                           -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-expressions/5.3.0/lucene-expressions-5.3.0.jar)                                  -                        -
  org.codehaus.groovy:groovy-all:jar:indy:2.4.4                            [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/groovy/groovy-all/2.4.4/groovy-all-2.4.4-indy.jar)                                           -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/groovy/groovy-all/2.4.4/groovy-all-2.4.4-indy.jar)                                           -                        -
  org.ow2.asm:asm:jar:4.1                                                  -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/ow2/asm/asm/4.1/asm-4.1.jar)                                                                          -                        -
  org.ow2.asm:asm-commons:jar:4.1                                          -                                                                                                                                                                                                                                                                  -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/4.1/asm-commons-4.1.jar)                                                          -                        -
  org.slf4j:slf4j-api:jar:1.6.2                                            [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/slf4j/slf4j-api/1.6.2/slf4j-api-1.6.2.jar)                                                            -               -                  -                          -     [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.6.2/slf4j-api-1.6.2.jar)                                                            -                        -
  Total                                                                    sonatype.releases                                                                                                                                                                                                                                                  oss-snapshots   apache.snapshots   sonatype-nexus-snapshots   spy   central                                                                                                                                                                                                                      elasticsearch-releases   Twitter
  52 (compile: 41, test: 11)                                               25                                                                                                                                                                                                                                                                 0               0                  0                          0     52                                                                                                                                                                                                                           0                        0

</div>

</div>

</div>

<div class="clear">

------------------------------------------------------------------------

</div>

<div id="footer">

<div class="xright">

Copyright © 2009–2015. All rights reserved.

</div>

<div class="clear">

------------------------------------------------------------------------

</div>

</div>
