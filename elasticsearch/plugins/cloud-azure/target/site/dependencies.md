Plugin: Cloud: Azure

------------------------------------------------------------------------

<span id="publishDate">Last Published: 2015-10-21</span>  | <span id="projectVersion">Version: 2.1.0-SNAPSHOT</span>

------------------------------------------------------------------------

[![Built by Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

Project Dependencies
--------------------

### compile

The following is a list of compile dependencies for this project. These dependencies are required to compile and run the application:

| GroupId                   | ArtifactId                                                              | Version | Type | License                                                                                    |
|---------------------------|-------------------------------------------------------------------------|---------|------|--------------------------------------------------------------------------------------------|
| com.microsoft.azure       | [azure-management](https://github.com/Azure/azure-sdk-for-java)         | 0.7.0   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| com.microsoft.azure       | [azure-management-compute](https://github.com/Azure/azure-sdk-for-java) | 0.7.0   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| com.microsoft.azure       | [azure-storage](https://github.com/Azure/azure-storage-java)            | 2.0.0   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.apache.httpcomponents | [httpclient](http://hc.apache.org/httpcomponents-client)                | 4.3.6   | jar  | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)              |

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId           | ArtifactId                                                                                  | Version        | Classifier | Type     | License                                                                                    |
|-------------------|---------------------------------------------------------------------------------------------|----------------|------------|----------|--------------------------------------------------------------------------------------------|
| org.apache.lucene | [lucene-test-framework](http://lucene.apache.org/lucene-parent/lucene-test-framework)       | 5.3.0          | -          | jar      | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                 |
| org.elasticsearch | [elasticsearch](http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch) | 2.1.0-SNAPSHOT | tests      | test-jar | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.hamcrest      | [hamcrest-all](https://github.com/hamcrest/JavaHamcrest/hamcrest-all)                       | 1.3            | -          | jar      | [New BSD License](http://www.opensource.org/licenses/bsd-license.php)                      |

### provided

The following is a list of provided dependencies for this project. These dependencies are required to compile the application, but should be provided by default when using the library:

| GroupId                           | ArtifactId                                                                                  | Version        | Classifier | Type | License                                                                                                          |
|-----------------------------------|---------------------------------------------------------------------------------------------|----------------|------------|------|------------------------------------------------------------------------------------------------------------------|
| com.carrotsearch                  | [hppc](http://labs.carrotsearch.com/hppc.html/hppc)                                         | 0.7.1          | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.fasterxml.jackson.core        | [jackson-core](https://github.com/FasterXML/jackson-core)                                   | 2.6.2          | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.fasterxml.jackson.dataformat  | [jackson-dataformat-cbor](http://wiki.fasterxml.com/JacksonForCbor)                         | 2.6.2          | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.fasterxml.jackson.dataformat  | [jackson-dataformat-smile](http://wiki.fasterxml.com/JacksonForSmile)                       | 2.6.2          | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.fasterxml.jackson.dataformat  | [jackson-dataformat-yaml](https://github.com/FasterXML/jackson)                             | 2.6.2          | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.github.spullara.mustache.java | [compiler](http://github.com/spullara/mustache.java)                                        | 0.8.13         | -          | jar  | [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)                                                 |
| com.google.guava                  | [guava](http://code.google.com/p/guava-libraries/guava)                                     | 18.0           | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.ning                          | [compress-lzf](http://github.com/ning/compress)                                             | 1.0.2          | -          | jar  | [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)                                            |
| com.spatial4j                     | [spatial4j](https://github.com/spatial4j/spatial4j)                                         | 0.4.1          | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.tdunning                      | [t-digest](https://github.com/tdunning/t-digest)                                            | 3.0            | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| com.vividsolutions                | [jts](http://sourceforge.net/projects/jts-topo-suite)                                       | 1.13           | -          | jar  | [Lesser General Public License (LGPL)](http://www.gnu.org/copyleft/lesser.txt)                                   |
| commons-cli                       | [commons-cli](http://commons.apache.org/proper/commons-cli/)                                | 1.3.1          | -          | jar  | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                    |
| io.netty                          | [netty](http://netty.io/)                                                                   | 3.10.5.Final   | -          | jar  | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)                                        |
| joda-time                         | [joda-time](http://www.joda.org/joda-time/)                                                 | 2.8.2          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| log4j                             | [apache-log4j-extras](http://logging.apache.org/log4j/extras)                               | 1.2.17         | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| log4j                             | [log4j](http://logging.apache.org/log4j/1.2/)                                               | 1.2.17         | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| net.java.dev.jna                  | [jna](https://github.com/twall/jna)                                                         | 4.1.0          | -          | jar  | [LGPL, version 2.1](http://www.gnu.org/licenses/licenses.html)-[ASL, version 2](http://www.apache.org/licenses/) |
| org.apache.lucene                 | [lucene-analyzers-common](http://lucene.apache.org/lucene-parent/lucene-analyzers-common)   | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-backward-codecs](http://lucene.apache.org/lucene-parent/lucene-backward-codecs)     | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-core](http://lucene.apache.org/lucene-parent/lucene-core)                           | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-expressions](http://lucene.apache.org/lucene-parent/lucene-expressions)             | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-highlighter](http://lucene.apache.org/lucene-parent/lucene-highlighter)             | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-join](http://lucene.apache.org/lucene-parent/lucene-join)                           | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-memory](http://lucene.apache.org/lucene-parent/lucene-memory)                       | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-queries](http://lucene.apache.org/lucene-parent/lucene-queries)                     | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-queryparser](http://lucene.apache.org/lucene-parent/lucene-queryparser)             | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-spatial](http://lucene.apache.org/lucene-parent/lucene-spatial)                     | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.apache.lucene                 | [lucene-suggest](http://lucene.apache.org/lucene-parent/lucene-suggest)                     | 5.3.0          | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.codehaus.groovy               | [groovy-all](http://groovy-lang.org)                                                        | 2.4.4          | indy       | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| org.elasticsearch                 | [elasticsearch](http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch) | 2.1.0-SNAPSHOT | -          | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                       |
| org.joda                          | [joda-convert](http://joda-convert.sourceforge.net)                                         | 1.2            | -          | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                       |
| org.slf4j                         | [slf4j-api](http://www.slf4j.org)                                                           | 1.6.2          | -          | jar  | [MIT License](http://www.opensource.org/licenses/mit-license.php)                                                |

Project Transitive Dependencies
-------------------------------

The following is a list of transitive dependencies for this project. Transitive dependencies are the dependencies of the project dependencies.

### compile

The following is a list of compile dependencies for this project. These dependencies are required to compile and run the application:

| GroupId                   | ArtifactId                                                           | Version | Type | License                                                                                                                                                                                            |
|---------------------------|----------------------------------------------------------------------|---------|------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| com.microsoft.azure       | [azure-core](https://github.com/Azure/azure-sdk-for-java)            | 0.7.0   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| com.sun.jersey            | [jersey-client](https://jersey.java.net/jersey-client/)              | 1.13    | jar  | [CDDL 1.1](http://glassfish.java.net/public/CDDL+GPL_1_1.html)-[GPL2 w/ CPE](http://glassfish.java.net/public/CDDL+GPL_1_1.html)                                                                   |
| com.sun.jersey            | [jersey-core](https://jersey.java.net/jersey-core/)                  | 1.13    | jar  | [CDDL 1.1](http://glassfish.java.net/public/CDDL+GPL_1_1.html)-[GPL2 w/ CPE](http://glassfish.java.net/public/CDDL+GPL_1_1.html)                                                                   |
| com.sun.jersey            | [jersey-json](https://jersey.java.net/jersey-json/)                  | 1.13    | jar  | [CDDL 1.1](http://glassfish.java.net/public/CDDL+GPL_1_1.html)-[GPL2 w/ CPE](http://glassfish.java.net/public/CDDL+GPL_1_1.html)                                                                   |
| com.sun.xml.bind          | [jaxb-impl](http://jaxb.java.net/)                                   | 2.2.3-1 | jar  | [CDDL 1.1](https://glassfish.java.net/public/CDDL+GPL_1_1.html)-[GPL2 w/ CPE](https://glassfish.java.net/public/CDDL+GPL_1_1.html)                                                                 |
| commons-codec             | [commons-codec](http://commons.apache.org/codec/)                    | 1.6     | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| commons-logging           | [commons-logging](http://commons.apache.org/proper/commons-logging/) | 1.1.3   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| javax.activation          | [activation](http://java.sun.com/products/javabeans/jaf/index.jsp)   | 1.1     | jar  | [Common Development and Distribution License (CDDL) v1.0](https://glassfish.dev.java.net/public/CDDLv1.0.html)                                                                                     |
| javax.inject              | [javax.inject](http://code.google.com/p/atinject/)                   | 1       | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| javax.mail                | [mail](http://kenai.com/projects/javamail/mail)                      | 1.4.5   | jar  | [CDDL](http://www.sun.com/cddl)-[GPLv2+CE](https://glassfish.dev.java.net/public/CDDL+GPL.html)                                                                                                    |
| javax.xml.bind            | [jaxb-api](https://jaxb.dev.java.net/)                               | 2.2.2   | jar  | [CDDL 1.1](https://glassfish.dev.java.net/public/CDDL+GPL_1_1.html)-[GPL2 w/ CPE](https://glassfish.dev.java.net/public/CDDL+GPL_1_1.html)                                                         |
| javax.xml.stream          | stax-api                                                             | 1.0-2   | jar  | -                                                                                                                                                                                                  |
| org.apache.commons        | [commons-lang3](http://commons.apache.org/proper/commons-lang/)      | 3.3.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| org.apache.httpcomponents | [httpcore](http://hc.apache.org/httpcomponents-core-ga)              | 4.3.3   | jar  | [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                                      |
| org.codehaus.jackson      | [jackson-core-asl](http://jackson.codehaus.org)                      | 1.9.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| org.codehaus.jackson      | [jackson-jaxrs](http://jackson.codehaus.org)                         | 1.9.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)-[GNU Lesser General Public License (LGPL), Version 2.1](http://www.fsf.org/licensing/licenses/lgpl.txt) |
| org.codehaus.jackson      | [jackson-mapper-asl](http://jackson.codehaus.org)                    | 1.9.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)                                                                                                         |
| org.codehaus.jackson      | [jackson-xc](http://jackson.codehaus.org)                            | 1.9.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)-[GNU Lesser General Public License (LGPL), Version 2.1](http://www.fsf.org/licensing/licenses/lgpl.txt) |
| org.codehaus.jettison     | jettison                                                             | 1.1     | jar  | -                                                                                                                                                                                                  |

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId                            | ArtifactId                                                                        | Version | Type | License                                                                                    |
|------------------------------------|-----------------------------------------------------------------------------------|---------|------|--------------------------------------------------------------------------------------------|
| com.carrotsearch.randomizedtesting | [randomizedtesting-runner](http://labs.carrotsearch.com/randomizedtesting-runner) | 2.1.16  | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| junit                              | [junit](http://junit.org)                                                         | 4.11    | jar  | [Common Public License Version 1.0](http://www.opensource.org/licenses/cpl1.0.txt)         |
| org.apache.ant                     | [ant](http://ant.apache.org/ant/)                                                 | 1.8.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.apache.lucene                  | [lucene-codecs](http://lucene.apache.org/lucene-parent/lucene-codecs)             | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                 |

### provided

The following is a list of provided dependencies for this project. These dependencies are required to compile the application, but should be provided by default when using the library:

| GroupId           | ArtifactId                                                                  | Version | Type | License                                                                                      |
|-------------------|-----------------------------------------------------------------------------|---------|------|----------------------------------------------------------------------------------------------|
| com.twitter       | [jsr166e](http://github.com/twitter/jsr166e)                                | 1.1.0   | jar  | [CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/)                       |
| org.antlr         | [antlr-runtime](http://www.antlr.org)                                       | 3.5     | jar  | [BSD licence](http://antlr.org/license.html)                                                 |
| org.apache.lucene | [lucene-grouping](http://lucene.apache.org/lucene-parent/lucene-grouping)   | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene | [lucene-misc](http://lucene.apache.org/lucene-parent/lucene-misc)           | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene | [lucene-sandbox](http://lucene.apache.org/lucene-parent/lucene-sandbox)     | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.apache.lucene | [lucene-spatial3d](http://lucene.apache.org/lucene-parent/lucene-spatial3d) | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                   |
| org.hdrhistogram  | [HdrHistogram](http://hdrhistogram.github.io/HdrHistogram/)                 | 2.1.6   | jar  | [Public Domain, per Creative Commons CC0](http://creativecommons.org/publicdomain/zero/1.0/) |
| org.ow2.asm       | [asm](http://asm.objectweb.org/asm/)                                        | 4.1     | jar  | [BSD](http://asm.objectweb.org/license.html)                                                 |
| org.ow2.asm       | [asm-commons](http://asm.objectweb.org/asm-commons/)                        | 4.1     | jar  | [BSD](http://asm.objectweb.org/license.html)                                                 |
| org.yaml          | [snakeyaml](http://www.snakeyaml.org)                                       | 1.15    | jar  | LICENSE.txt                                                                                  |

Project Dependency Graph
------------------------

### Dependency Tree

-   org.elasticsearch.plugin:cloud-azure:jar:2.1.0-SNAPSHOT ![Information](./images/icon_info_sml.gif)
    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">Plugin: Cloud: Azure</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><p><strong>Description:</strong> The Azure Cloud plugin allows to use Azure API for the unicast discovery mechanism and add Azure storage repositories.</p>
    <p><strong>URL:</strong> <a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure" class="uri">http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure</a></p>
    <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
    </tr>
    </tbody>
    </table>

    -   com.microsoft.azure:azure-storage:jar:2.0.0 (compile) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Microsoft Azure Storage Client SDK</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> SDK for Microsoft Azure Storage Clients</p>
        <p><strong>URL:</strong> <a href="https://github.com/Azure/azure-storage-java" class="uri">https://github.com/Azure/azure-storage-java</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

        -   org.apache.commons:commons-lang3:jar:3.3.2 (compile) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Apache Commons Lang</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Apache Commons Lang, a package of Java utility classes for the classes that are in java.lang's hierarchy, or are considered to be so standard as to justify existence in java.lang.</p>
            <p><strong>URL:</strong> <a href="http://commons.apache.org/proper/commons-lang/" class="uri">http://commons.apache.org/proper/commons-lang/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>
    -   com.microsoft.azure:azure-management-compute:jar:0.7.0 (compile) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Microsoft Azure SDK for Compute Management</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> This package contains Microsoft Azure Compute Management SDK.</p>
        <p><strong>URL:</strong> <a href="https://github.com/Azure/azure-sdk-for-java" class="uri">https://github.com/Azure/azure-sdk-for-java</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

        -   com.microsoft.azure:azure-core:jar:0.7.0 (compile) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Microsoft Azure SDK Core</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> This is the core module of Microsoft Azure SDK.</p>
            <p><strong>URL:</strong> <a href="https://github.com/Azure/azure-sdk-for-java" class="uri">https://github.com/Azure/azure-sdk-for-java</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

            -   javax.mail:mail:jar:1.4.5 (compile) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">JavaMail API (compat)</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> JavaMail API (compat)</p>
                <p><strong>URL:</strong> <a href="http://kenai.com/projects/javamail/mail" class="uri">http://kenai.com/projects/javamail/mail</a></p>
                <p><strong>Project License:</strong> <a href="http://www.sun.com/cddl">CDDL</a><a href="https://glassfish.dev.java.net/public/CDDL+GPL.html">GPLv2+CE</a></p></td>
                </tr>
                </tbody>
                </table>

                -   javax.activation:activation:jar:1.1 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">JavaBeans Activation Framework (JAF)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> JavaBeans Activation Framework (JAF) is a standard extension to the Java platform that lets you take advantage of standard services to: determine the type of an arbitrary piece of data; encapsulate access to it; discover the operations available on it; and instantiate the appropriate bean to perform the operation(s).</p>
                    <p><strong>URL:</strong> <a href="http://java.sun.com/products/javabeans/jaf/index.jsp" class="uri">http://java.sun.com/products/javabeans/jaf/index.jsp</a></p>
                    <p><strong>Project License:</strong> <a href="https://glassfish.dev.java.net/public/CDDLv1.0.html">Common Development and Distribution License (CDDL) v1.0</a></p></td>
                    </tr>
                    </tbody>
                    </table>
            -   com.sun.jersey:jersey-client:jar:1.13 (compile) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">jersey-client</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Jersey is the open source (under dual CDDL+GPL license) JAX-RS (JSR 311) production quality Reference Implementation for building RESTful Web services.</p>
                <p><strong>URL:</strong> <a href="https://jersey.java.net/jersey-client/" class="uri">https://jersey.java.net/jersey-client/</a></p>
                <p><strong>Project License:</strong> <a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">CDDL 1.1</a><a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">GPL2 w/ CPE</a></p></td>
                </tr>
                </tbody>
                </table>

                -   com.sun.jersey:jersey-core:jar:1.13 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">jersey-core</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> Jersey is the open source (under dual CDDL+GPL license) JAX-RS (JSR 311) production quality Reference Implementation for building RESTful Web services.</p>
                    <p><strong>URL:</strong> <a href="https://jersey.java.net/jersey-core/" class="uri">https://jersey.java.net/jersey-core/</a></p>
                    <p><strong>Project License:</strong> <a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">CDDL 1.1</a><a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">GPL2 w/ CPE</a></p></td>
                    </tr>
                    </tbody>
                    </table>
            -   com.sun.jersey:jersey-json:jar:1.13 (compile) ![Information](./images/icon_info_sml.gif)
                <table>
                <colgroup>
                <col width="100%" />
                </colgroup>
                <thead>
                <tr class="header">
                <th align="left">jersey-json</th>
                </tr>
                </thead>
                <tbody>
                <tr class="odd">
                <td align="left"><p><strong>Description:</strong> Jersey is the open source (under dual CDDL+GPL license) JAX-RS (JSR 311) production quality Reference Implementation for building RESTful Web services.</p>
                <p><strong>URL:</strong> <a href="https://jersey.java.net/jersey-json/" class="uri">https://jersey.java.net/jersey-json/</a></p>
                <p><strong>Project License:</strong> <a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">CDDL 1.1</a><a href="http://glassfish.java.net/public/CDDL+GPL_1_1.html">GPL2 w/ CPE</a></p></td>
                </tr>
                </tbody>
                </table>

                -   org.codehaus.jettison:jettison:jar:1.1 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">Jettison</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> A StAX implementation for JSON.</p>
                    <p><strong>Project License:</strong> No license is defined for this project.</p></td>
                    </tr>
                    </tbody>
                    </table>

                -   com.sun.xml.bind:jaxb-impl:jar:2.2.3-1 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">JAXB RI</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> JAXB (JSR 222) reference implementation</p>
                    <p><strong>URL:</strong> <a href="http://jaxb.java.net/" class="uri">http://jaxb.java.net/</a></p>
                    <p><strong>Project License:</strong> <a href="https://glassfish.java.net/public/CDDL+GPL_1_1.html">CDDL 1.1</a><a href="https://glassfish.java.net/public/CDDL+GPL_1_1.html">GPL2 w/ CPE</a></p></td>
                    </tr>
                    </tbody>
                    </table>

                    -   javax.xml.bind:jaxb-api:jar:2.2.2 (compile) ![Information](./images/icon_info_sml.gif)
                        <table>
                        <colgroup>
                        <col width="100%" />
                        </colgroup>
                        <thead>
                        <tr class="header">
                        <th align="left">JAXB API bundle for GlassFish V3</th>
                        </tr>
                        </thead>
                        <tbody>
                        <tr class="odd">
                        <td align="left"><p><strong>Description:</strong> JAXB (JSR 222) API</p>
                        <p><strong>URL:</strong> <a href="https://jaxb.dev.java.net/" class="uri">https://jaxb.dev.java.net/</a></p>
                        <p><strong>Project License:</strong> <a href="https://glassfish.dev.java.net/public/CDDL+GPL_1_1.html">CDDL 1.1</a><a href="https://glassfish.dev.java.net/public/CDDL+GPL_1_1.html">GPL2 w/ CPE</a></p></td>
                        </tr>
                        </tbody>
                        </table>

                        -   javax.xml.stream:stax-api:jar:1.0-2 (compile) ![Information](./images/icon_info_sml.gif)
                            <table>
                            <colgroup>
                            <col width="100%" />
                            </colgroup>
                            <thead>
                            <tr class="header">
                            <th align="left">stax-api</th>
                            </tr>
                            </thead>
                            <tbody>
                            <tr class="odd">
                            <td align="left"><p><strong>Description:</strong> There is currently no description associated with this project.</p>
                            <p><strong>Project License:</strong> No license is defined for this project.</p></td>
                            </tr>
                            </tbody>
                            </table>
                -   org.codehaus.jackson:jackson-core-asl:jar:1.9.2 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">Jackson</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> Jackson is a high-performance JSON processor (parser, generator)</p>
                    <p><strong>URL:</strong> <a href="http://jackson.codehaus.org" class="uri">http://jackson.codehaus.org</a></p>
                    <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
                    </tr>
                    </tbody>
                    </table>

                -   org.codehaus.jackson:jackson-mapper-asl:jar:1.9.2 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">Data Mapper for Jackson</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> Data Mapper package is a high-performance data binding package built on Jackson JSON processor</p>
                    <p><strong>URL:</strong> <a href="http://jackson.codehaus.org" class="uri">http://jackson.codehaus.org</a></p>
                    <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
                    </tr>
                    </tbody>
                    </table>

                -   org.codehaus.jackson:jackson-jaxrs:jar:1.9.2 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">JAX-RS provider for JSON content type</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> Jax-RS provider for JSON content type, based on Jackson JSON processor's data binding functionality.</p>
                    <p><strong>URL:</strong> <a href="http://jackson.codehaus.org" class="uri">http://jackson.codehaus.org</a></p>
                    <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a><a href="http://www.fsf.org/licensing/licenses/lgpl.txt">GNU Lesser General Public License (LGPL), Version 2.1</a></p></td>
                    </tr>
                    </tbody>
                    </table>

                -   org.codehaus.jackson:jackson-xc:jar:1.9.2 (compile) ![Information](./images/icon_info_sml.gif)
                    <table>
                    <colgroup>
                    <col width="100%" />
                    </colgroup>
                    <thead>
                    <tr class="header">
                    <th align="left">Xml Compatibility extensions for Jackson</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr class="odd">
                    <td align="left"><p><strong>Description:</strong> Extensions that provide interoperability support for Jackson JSON processor's data binding functionality.</p>
                    <p><strong>URL:</strong> <a href="http://jackson.codehaus.org" class="uri">http://jackson.codehaus.org</a></p>
                    <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a><a href="http://www.fsf.org/licensing/licenses/lgpl.txt">GNU Lesser General Public License (LGPL), Version 2.1</a></p></td>
                    </tr>
                    </tbody>
                    </table>
        -   javax.inject:javax.inject:jar:1 (compile) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">javax.inject</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> The javax.inject API</p>
            <p><strong>URL:</strong> <a href="http://code.google.com/p/atinject/" class="uri">http://code.google.com/p/atinject/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>
    -   com.microsoft.azure:azure-management:jar:0.7.0 (compile) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Microsoft Azure SDK for Management</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> This package contains Microsoft Azure Management SDK.</p>
        <p><strong>URL:</strong> <a href="https://github.com/Azure/azure-sdk-for-java" class="uri">https://github.com/Azure/azure-sdk-for-java</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

    -   org.apache.httpcomponents:httpclient:jar:4.3.6 (compile) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Apache HttpClient</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> HttpComponents Client</p>
        <p><strong>URL:</strong> <a href="http://hc.apache.org/httpcomponents-client" class="uri">http://hc.apache.org/httpcomponents-client</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

        -   org.apache.httpcomponents:httpcore:jar:4.3.3 (compile) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Apache HttpCore</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> HttpComponents Core (blocking I/O)</p>
            <p><strong>URL:</strong> <a href="http://hc.apache.org/httpcomponents-core-ga" class="uri">http://hc.apache.org/httpcomponents-core-ga</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   commons-logging:commons-logging:jar:1.1.3 (compile) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Commons Logging</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> Commons Logging is a thin adapter allowing configurable bridging to other, well known logging systems.</p>
            <p><strong>URL:</strong> <a href="http://commons.apache.org/proper/commons-logging/" class="uri">http://commons.apache.org/proper/commons-logging/</a></p>
            <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
            </tr>
            </tbody>
            </table>

        -   commons-codec:commons-codec:jar:1.6 (compile) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">Commons Codec</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> The codec package contains simple encoder and decoders for various formats such as Base64 and Hexadecimal. In addition to these widely used encoders and decoders, the codec package also maintains a collection of phonetic encoding utilities.</p>
            <p><strong>URL:</strong> <a href="http://commons.apache.org/codec/" class="uri">http://commons.apache.org/codec/</a></p>
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
    -   org.elasticsearch:elasticsearch:test-jar:tests:2.1.0-SNAPSHOT (test) ![Information](./images/icon_info_sml.gif)
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

        -   org.hdrhistogram:HdrHistogram:jar:2.1.6 (provided) ![Information](./images/icon_info_sml.gif)
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

        -   com.twitter:jsr166e:jar:1.1.0 (provided) ![Information](./images/icon_info_sml.gif)
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
    -   org.elasticsearch:elasticsearch:jar:2.1.0-SNAPSHOT (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-core:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-backward-codecs:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-analyzers-common:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-queries:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-memory:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-highlighter:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.apache.lucene:lucene-queryparser:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

        -   org.apache.lucene:lucene-sandbox:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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
    -   org.apache.lucene:lucene-suggest:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

        -   org.apache.lucene:lucene-misc:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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
    -   org.apache.lucene:lucene-join:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

        -   org.apache.lucene:lucene-grouping:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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
    -   org.apache.lucene:lucene-spatial:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

        -   org.apache.lucene:lucene-spatial3d:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
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
    -   org.apache.lucene:lucene-expressions:jar:5.3.0 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Lucene Expressions</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Dynamically computed values to sort/facet/search on based on a pluggable grammar.</p>
        <p><strong>URL:</strong> <a href="http://lucene.apache.org/lucene-parent/lucene-expressions" class="uri">http://lucene.apache.org/lucene-parent/lucene-expressions</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache 2</a></p></td>
        </tr>
        </tbody>
        </table>

        -   org.antlr:antlr-runtime:jar:3.5 (provided) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">ANTLR 3 Runtime</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> A framework for constructing recognizers, compilers, and translators from grammatical descriptions containing Java, C#, C++, or Python actions.</p>
            <p><strong>URL:</strong> <a href="http://www.antlr.org" class="uri">http://www.antlr.org</a></p>
            <p><strong>Project License:</strong> <a href="http://antlr.org/license.html">BSD licence</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.ow2.asm:asm:jar:4.1 (provided) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">ASM Core</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> A very small and fast Java bytecode manipulation framework</p>
            <p><strong>URL:</strong> <a href="http://asm.objectweb.org/asm/" class="uri">http://asm.objectweb.org/asm/</a></p>
            <p><strong>Project License:</strong> <a href="http://asm.objectweb.org/license.html">BSD</a></p></td>
            </tr>
            </tbody>
            </table>

        -   org.ow2.asm:asm-commons:jar:4.1 (provided) ![Information](./images/icon_info_sml.gif)
            <table>
            <colgroup>
            <col width="100%" />
            </colgroup>
            <thead>
            <tr class="header">
            <th align="left">ASM Commons</th>
            </tr>
            </thead>
            <tbody>
            <tr class="odd">
            <td align="left"><p><strong>Description:</strong> A very small and fast Java bytecode manipulation framework</p>
            <p><strong>URL:</strong> <a href="http://asm.objectweb.org/asm-commons/" class="uri">http://asm.objectweb.org/asm-commons/</a></p>
            <p><strong>Project License:</strong> <a href="http://asm.objectweb.org/license.html">BSD</a></p></td>
            </tr>
            </tbody>
            </table>
    -   com.spatial4j:spatial4j:jar:0.4.1 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.vividsolutions:jts:jar:1.13 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">JTS Topology Suite</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> The JTS Topology Suite is an API for modelling and manipulating 2-dimensional linear geometry. It provides numerous geometric predicates and functions. JTS conforms to the Simple Features Specification for SQL published by the Open GIS Consortium.</p>
        <p><strong>URL:</strong> <a href="http://sourceforge.net/projects/jts-topo-suite" class="uri">http://sourceforge.net/projects/jts-topo-suite</a></p>
        <p><strong>Project License:</strong> <a href="http://www.gnu.org/copyleft/lesser.txt">Lesser General Public License (LGPL)</a></p></td>
        </tr>
        </tbody>
        </table>

    -   com.github.spullara.mustache.java:compiler:jar:0.8.13 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">compiler</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Implementation of mustache.js for Java</p>
        <p><strong>URL:</strong> <a href="http://github.com/spullara/mustache.java" class="uri">http://github.com/spullara/mustache.java</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0">Apache License 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

    -   com.google.guava:guava:jar:18.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.carrotsearch:hppc:jar:0.7.1 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   joda-time:joda-time:jar:2.8.2 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.joda:joda-convert:jar:1.2 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.fasterxml.jackson.core:jackson-core:jar:2.6.2 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.fasterxml.jackson.dataformat:jackson-dataformat-smile:jar:2.6.2 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.6.2 (provided) ![Information](./images/icon_info_sml.gif)
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

        -   org.yaml:snakeyaml:jar:1.15 (provided) ![Information](./images/icon_info_sml.gif)
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
    -   com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.2 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   io.netty:netty:jar:3.10.5.Final (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.ning:compress-lzf:jar:1.0.2 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   com.tdunning:t-digest:jar:3.0 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   commons-cli:commons-cli:jar:1.3.1 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   org.codehaus.groovy:groovy-all:jar:indy:2.4.4 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Apache Groovy</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Groovy: A powerful, dynamic language for the JVM</p>
        <p><strong>URL:</strong> <a href="http://groovy-lang.org" class="uri">http://groovy-lang.org</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

    -   log4j:log4j:jar:1.2.17 (provided) ![Information](./images/icon_info_sml.gif)
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

    -   log4j:apache-log4j-extras:jar:1.2.17 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Apache Extras™ for Apache log4j™.</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> This package provides additional appenders, filters and other capabilities for version 1.2 of Apache log4j™. Several of these were backported from the abandoned Apache log4j 1.3 development effort.</p>
        <p><strong>URL:</strong> <a href="http://logging.apache.org/log4j/extras" class="uri">http://logging.apache.org/log4j/extras</a></p>
        <p><strong>Project License:</strong> <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">The Apache Software License, Version 2.0</a></p></td>
        </tr>
        </tbody>
        </table>

    -   org.slf4j:slf4j-api:jar:1.6.2 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">SLF4J API Module</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> The slf4j API</p>
        <p><strong>URL:</strong> <a href="http://www.slf4j.org" class="uri">http://www.slf4j.org</a></p>
        <p><strong>Project License:</strong> <a href="http://www.opensource.org/licenses/mit-license.php">MIT License</a></p></td>
        </tr>
        </tbody>
        </table>

    -   net.java.dev.jna:jna:jar:4.1.0 (provided) ![Information](./images/icon_info_sml.gif)
        <table>
        <colgroup>
        <col width="100%" />
        </colgroup>
        <thead>
        <tr class="header">
        <th align="left">Java Native Access</th>
        </tr>
        </thead>
        <tbody>
        <tr class="odd">
        <td align="left"><p><strong>Description:</strong> Java Native Access</p>
        <p><strong>URL:</strong> <a href="https://github.com/twall/jna" class="uri">https://github.com/twall/jna</a></p>
        <p><strong>Project License:</strong> <a href="http://www.gnu.org/licenses/licenses.html">LGPL, version 2.1</a><a href="http://www.apache.org/licenses/">ASL, version 2</a></p></td>
        </tr>
        </tbody>
        </table>

Licenses
--------

**GPLv2+CE:** JavaMail API (compat)

**LGPL, version 2.1:** Java Native Access

**New BSD License:** Hamcrest All

**Apache 2:** Joda convert, Joda-Time, Lucene Common Analyzers, Lucene Core, Lucene Expressions, Lucene Grouping, Lucene Highlighter, Lucene Join, Lucene Memory, Lucene Miscellaneous, Lucene Queries, Lucene QueryParsers, Lucene Sandbox, Lucene Spatial, Lucene Spatial 3D, Lucene Suggest, Lucene Test Framework, Lucene codecs

**Unknown:** Jettison, stax-api

**BSD:** ASM Commons, ASM Core

**BSD licence:** ANTLR 3 Runtime

**Apache License, Version 2.0:** Apache Commons CLI, Apache HttpClient, Apache HttpCore, Netty

**The Apache Software License, Version 2.0:** Apache Ant Core, Apache Commons Lang, Apache Extras™ for Apache log4j™., Apache Groovy, Apache Log4j, Commons Codec, Commons Logging, Data Mapper for Jackson, Elasticsearch: Core, Guava: Google Core Libraries for Java, HPPC Collections, JAX-RS provider for JSON content type, Jackson, Jackson-core, Jackson-dataformat-CBOR, Jackson-dataformat-Smile, Jackson-dataformat-YAML, Microsoft Azure SDK Core, Microsoft Azure SDK for Compute Management, Microsoft Azure SDK for Management, Microsoft Azure Storage Client SDK, Plugin: Cloud: Azure, RandomizedTesting Randomized Runner, Spatial4J, T-Digest, Xml Compatibility extensions for Jackson, javax.inject

**CC0 1.0 Universal:** JSR166e

**Lesser General Public License (LGPL):** JTS Topology Suite

**ASL, version 2:** Java Native Access

**CDDL:** JavaMail API (compat)

**CDDL 1.1:** JAXB API bundle for GlassFish V3, JAXB RI, jersey-client, jersey-core, jersey-json

**GPL2 w/ CPE:** JAXB API bundle for GlassFish V3, JAXB RI, jersey-client, jersey-core, jersey-json

**Public Domain, per Creative Commons CC0:** HdrHistogram

**Apache License 2.0:** Compress-LZF, compiler

**Common Public License Version 1.0:** JUnit

**MIT License:** SLF4J API Module

**Common Development and Distribution License (CDDL) v1.0:** JavaBeans Activation Framework (JAF)

**GNU Lesser General Public License (LGPL), Version 2.1:** JAX-RS provider for JSON content type, Xml Compatibility extensions for Jackson

**Apache License Version 2.0:** SnakeYAML

Dependency File Details
-----------------------

| Filename                               | Size               | Entries          | Classes          | Packages        | JDK Rev | Debug        |
|----------------------------------------|--------------------|------------------|------------------|-----------------|---------|--------------|
| hppc-0.7.1.jar                         | 1.09 MB            | 915              | 901              | 5               | 1.6     | debug        |
| randomizedtesting-runner-2.1.16.jar    | 207.89 kB          | 173              | 159              | 5               | 1.6     | debug        |
| jackson-core-2.6.2.jar                 | 252.76 kB          | 116              | 93               | 9               | 1.6     | debug        |
| jackson-dataformat-cbor-2.6.2.jar      | 47.02 kB           | 25               | 10               | 1               | 1.6     | debug        |
| jackson-dataformat-smile-2.6.2.jar     | 74.16 kB           | 34               | 17               | 2               | 1.6     | debug        |
| jackson-dataformat-yaml-2.6.2.jar      | 312.93 kB          | 253              | 210              | 20              | 1.6     | debug        |
| compiler-0.8.13.jar                    | 108.10 kB          | 112              | 94               | 8               | 1.6     | debug        |
| guava-18.0.jar                         | 2.15 MB            | 1,719            | 1,690            | 17              | 1.6     | debug        |
| azure-core-0.7.0.jar                   | 145.93 kB          | 137              | 112              | 11              | 1.6     | debug        |
| azure-management-0.7.0.jar             | 94.47 kB           | 73               | 57               | 2               | 1.6     | debug        |
| azure-management-compute-0.7.0.jar     | 619.41 kB          | 374              | 357              | 2               | 1.6     | debug        |
| azure-storage-2.0.0.jar                | 647.41 kB          | 337              | 318              | 7               | 1.6     | debug        |
| compress-lzf-1.0.2.jar                 | 77.86 kB           | 59               | 42               | 6               | 1.6     | debug        |
| spatial4j-0.4.1.jar                    | 99.78 kB           | 67               | 48               | 9               | 1.6     | debug        |
| jersey-client-1.13.jar                 | 128.19 kB          | 116              | 91               | 10              | 1.6     | debug        |
| jersey-core-1.13.jar                   | 454.74 kB          | 405              | 352              | 26              | 1.6     | debug        |
| jersey-json-1.13.jar                   | 159.59 kB          | 126              | 103              | 5               | 1.6     | debug        |
| jaxb-impl-2.2.3-1.jar                  | 869.30 kB          | 709              | 660              | 30              | 1.5     | debug        |
| t-digest-3.0.jar                       | 48.59 kB           | 31               | 20               | 1               | 1.6     | debug        |
| jsr166e-1.1.0.jar                      | 60.77 kB           | 37               | 27               | 1               | 1.6     | debug        |
| jts-1.13.jar                           | 776.36 kB          | 611              | 539              | 60              | 1.5     | debug        |
| commons-cli-1.3.1.jar                  | 51.75 kB           | 39               | 26               | 1               | 1.5     | debug        |
| commons-codec-1.6.jar                  | 227.32 kB          | 218              | 76               | 6               | 1.5     | debug        |
| commons-logging-1.1.3.jar              | 60.60 kB           | 42               | 28               | 2               | 1.1     | debug        |
| netty-3.10.5.Final.jar                 | 1.27 MB            | 950              | 880              | 43              | 1.5     | debug        |
| activation-1.1.jar                     | 61.51 kB           | 50               | 38               | 3               | 1.4     | debug        |
| javax.inject-1.jar                     | 2.44 kB            | 8                | 6                | 1               | 1.5     | release      |
| mail-1.4.5.jar                         | 496.23 kB          | 319              | 288              | 14              | 1.4     | debug        |
| jaxb-api-2.2.2.jar                     | 102.67 kB          | 115              | 101              | 6               | 1.5     | debug        |
| stax-api-1.0-2.jar                     | 22.80 kB           | 44               | 37               | 3               | 1.5     | debug        |
| joda-time-2.8.2.jar                    | 607.41 kB          | 749              | 246              | 7               | 1.5     | debug        |
| junit-4.11.jar                         | 239.30 kB          | 266              | 233              | 28              | 1.5     | debug        |
| apache-log4j-extras-1.2.17.jar         | 438.28 kB          | 323              | 284              | 23              | 1.4     | debug        |
| log4j-1.2.17.jar                       | 478.40 kB          | 353              | 314              | 21              | 1.4     | debug        |
| jna-4.1.0.jar                          | 893.16 kB          | 141              | 104              | 3               | 1.6     | debug        |
| antlr-runtime-3.5.jar                  | 163.80 kB          | 130              | 117              | 4               | 1.5     | debug        |
| ant-1.8.2.jar                          | 1.84 MB            | 1,168            | 1,090            | 59              | 1.4     | debug        |
| commons-lang3-3.3.2.jar                | 403.07 kB          | 241              | 217              | 12              | 1.6     | debug        |
| httpclient-4.3.6.jar                   | 578.13 kB          | 459              | 420              | 24              | 1.5     | debug        |
| httpcore-4.3.3.jar                     | 276.17 kB          | 260              | 232              | 15              | 1.5     | debug        |
| lucene-analyzers-common-5.3.0.jar      | 1.49 MB            | 673              | 563              | 61              | 1.6     | debug        |
| lucene-backward-codecs-5.3.0.jar       | 374.68 kB          | 223              | 202              | 10              | 1.6     | debug        |
| lucene-codecs-5.3.0.jar                | 408.73 kB          | 224              | 206              | 6               | 1.6     | debug        |
| lucene-core-5.3.0.jar                  | 2.25 MB            | 1,563            | 1,532            | 21              | 1.6     | debug        |
| lucene-expressions-5.3.0.jar           | 74.07 kB           | 49               | 39               | 2               | 1.6     | debug        |
| lucene-grouping-5.3.0.jar              | 105.97 kB          | 76               | 65               | 3               | 1.6     | debug        |
| lucene-highlighter-5.3.0.jar           | 141.08 kB          | 97               | 86               | 3               | 1.6     | debug        |
| lucene-join-5.3.0.jar                  | 116.26 kB          | 90               | 81               | 1               | 1.6     | debug        |
| lucene-memory-5.3.0.jar                | 32.51 kB           | 21               | 12               | 1               | 1.6     | debug        |
| lucene-misc-5.3.0.jar                  | 168.27 kB          | 122              | 107              | 7               | 1.6     | debug        |
| lucene-queries-5.3.0.jar               | 206.93 kB          | 174              | 162              | 5               | 1.6     | debug        |
| lucene-queryparser-5.3.0.jar           | 391.91 kB          | 312              | 273              | 26              | 1.6     | debug        |
| lucene-sandbox-5.3.0.jar               | 260.50 kB          | 168              | 148              | 8               | 1.6     | debug        |
| lucene-spatial-5.3.0.jar               | 194.02 kB          | 139              | 122              | 10              | 1.6     | debug        |
| lucene-spatial3d-5.3.0.jar             | 121.56 kB          | 67               | 59               | 1               | 1.6     | debug        |
| lucene-suggest-5.3.0.jar               | 240.22 kB          | 150              | 132              | 7               | 1.6     | debug        |
| lucene-test-framework-5.3.0.jar        | 6.23 MB            | 482              | 451              | 19              | 1.6     | debug        |
| groovy-all-2.4.4-indy.jar              | 6.49 MB            | 4,643            | 3,523            | 113             | 1.6     | debug        |
| jackson-core-asl-1.9.2.jar             | 222.94 kB          | 136              | 120              | 8               | 1.5     | debug        |
| jackson-jaxrs-1.9.2.jar                | 17.89 kB           | 17               | 7                | 1               | 1.5     | debug        |
| jackson-mapper-asl-1.9.2.jar           | 747.70 kB          | 521              | 494              | 18              | 1.5     | debug        |
| jackson-xc-1.9.2.jar                   | 26.44 kB           | 19               | 9                | 1               | 1.5     | debug        |
| jettison-1.1.jar                       | 66.17 kB           | 55               | 40               | 5               | 1.1     | debug        |
| elasticsearch-2.1.0-SNAPSHOT.jar       | 8.80 MB            | 6,306            | 5,785            | 453             | 1.6     | debug        |
| elasticsearch-2.1.0-SNAPSHOT-tests.jar | 630.14 kB          | -                | -                | -               | -       | -            |
| hamcrest-all-1.3.jar                   | 299.39 kB          | 249              | 204              | 23              | 1.5     | debug        |
| HdrHistogram-2.1.6.jar                 | 107.15 kB          | 67               | 58               | 1               | 1.6     | debug        |
| joda-convert-1.2.jar                   | 37.56 kB           | 52               | 40               | 1               | 1.5     | debug        |
| asm-4.1.jar                            | 46.25 kB           | 24               | 23               | 2               | 1.2     | release      |
| asm-commons-4.1.jar                    | 37.20 kB           | 23               | 22               | 1               | 1.2     | release      |
| slf4j-api-1.6.2.jar                    | 25.09 kB           | 34               | 23               | 3               | 1.3     | debug        |
| snakeyaml-1.15.jar                     | 262.98 kB          | 237              | 201              | 19              | 1.5     | debug        |
| Total                                  | Size               | Entries          | Classes          | Packages        | JDK Rev | Debug        |
| 72                                     | 46.89 MB           | 29,317           | 25,426           | 1,352           | 1.6     | 68           |
| compile: 23                            | compile: 6.28 MB   | compile: 4,781   | compile: 4,163   | compile: 212    | -       | compile: 22  |
| test: 7                                | test: 9.82 MB      | test: 2,562      | test: 2,343      | test: 140       | -       | test: 6      |
| provided: 42                           | provided: 30.79 MB | provided: 21,974 | provided: 18,920 | provided: 1,000 | -       | provided: 40 |

Dependency Repository Locations
-------------------------------

| Repo ID                        | URL                                                                                      | Release | Snapshot | Blacklisted |
|--------------------------------|------------------------------------------------------------------------------------------|---------|----------|-------------|
| sonatype.releases              | <https://oss.sonatype.org/content/repositories/releases>                                 | Yes     | Yes      | -           |
| oss-snapshots                  | <https://oss.sonatype.org/content/repositories/snapshots/>                               | Yes     | Yes      | -           |
| apache.snapshots               | <http://repository.apache.org/snapshots>                                                 | -       | -        | -           |
| sonatype-nexus-snapshots       | <https://oss.sonatype.org/content/repositories/snapshots>                                | -       | Yes      | -           |
| spy                            | <http://files.couchbase.com/maven2/>                                                     | Yes     | -        | -           |
| maven2-repository.dev.java.net | <http://download.java.net/maven/2/>                                                      | Yes     | Yes      | Yes         |
| m2.dev.java.net                | <http://download.java.net/maven/2>                                                       | Yes     | Yes      | Yes         |
| central                        | <http://repo.maven.apache.org/maven2>                                                    | Yes     | -        | -           |
| eclipselink.repository         | <http://www.eclipse.org/downloads/download.php?r=1&nf=1&file=/rt/eclipselink/maven.repo> | Yes     | Yes      | -           |
| elasticsearch-releases         | <http://maven.elasticsearch.org/releases>                                                | Yes     | -        | -           |
| repository.jboss.org           | <http://repository.jboss.org/nexus/content/groups/public/>                               | Yes     | Yes      | -           |
| Twitter                        | <http://maven.twttr.com/>                                                                | Yes     | Yes      | -           |

Repository locations for each of the Dependencies.

| Artifact                                                               | sonatype.releases                                                                                                                                                                                                                                                | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | spy | central                                                                                                                                                                                                                    | eclipselink.repository | elasticsearch-releases | repository.jboss.org | Twitter |
|------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------|--------------------------|-----|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|------------------------|----------------------|---------|
| com.carrotsearch:hppc:jar:0.7.1                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar)                                                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar)                                                             | -                      | -                      | -                    | -       |
| com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | -                      | -                      | -                    | -       |
| com.fasterxml.jackson.core:jackson-core:jar:2.6.2                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/core/jackson-core/2.6.2/jackson-core-2.6.2.jar)                                   | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.6.2/jackson-core-2.6.2.jar)                                   | -                      | -                      | -                    | -       |
| com.fasterxml.jackson.dataformat:jackson-dataformat-cbor:jar:2.6.2     | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-cbor/2.6.2/jackson-dataformat-cbor-2.6.2.jar)       | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-cbor/2.6.2/jackson-dataformat-cbor-2.6.2.jar)       | -                      | -                      | -                    | -       |
| com.fasterxml.jackson.dataformat:jackson-dataformat-smile:jar:2.6.2    | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-smile/2.6.2/jackson-dataformat-smile-2.6.2.jar)     | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-smile/2.6.2/jackson-dataformat-smile-2.6.2.jar)     | -                      | -                      | -                    | -       |
| com.fasterxml.jackson.dataformat:jackson-dataformat-yaml:jar:2.6.2     | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.6.2/jackson-dataformat-yaml-2.6.2.jar)       | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.6.2/jackson-dataformat-yaml-2.6.2.jar)       | -                      | -                      | -                    | -       |
| com.github.spullara.mustache.java:compiler:jar:0.8.13                  | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/github/spullara/mustache/java/compiler/0.8.13/compiler-0.8.13.jar)                                  | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/github/spullara/mustache/java/compiler/0.8.13/compiler-0.8.13.jar)                                  | -                      | -                      | -                    | -       |
| com.google.guava:guava:jar:18.0                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/google/guava/guava/18.0/guava-18.0.jar)                                                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/google/guava/guava/18.0/guava-18.0.jar)                                                             | -                      | -                      | -                    | -       |
| com.microsoft.azure:azure-core:jar:0.7.0                               | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/microsoft/azure/azure-core/0.7.0/azure-core-0.7.0.jar)                                              | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/microsoft/azure/azure-core/0.7.0/azure-core-0.7.0.jar)                                              | -                      | -                      | -                    | -       |
| com.microsoft.azure:azure-management:jar:0.7.0                         | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/microsoft/azure/azure-management/0.7.0/azure-management-0.7.0.jar)                                  | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/microsoft/azure/azure-management/0.7.0/azure-management-0.7.0.jar)                                  | -                      | -                      | -                    | -       |
| com.microsoft.azure:azure-management-compute:jar:0.7.0                 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/microsoft/azure/azure-management-compute/0.7.0/azure-management-compute-0.7.0.jar)                  | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/microsoft/azure/azure-management-compute/0.7.0/azure-management-compute-0.7.0.jar)                  | -                      | -                      | -                    | -       |
| com.microsoft.azure:azure-storage:jar:2.0.0                            | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/microsoft/azure/azure-storage/2.0.0/azure-storage-2.0.0.jar)                                        | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/microsoft/azure/azure-storage/2.0.0/azure-storage-2.0.0.jar)                                        | -                      | -                      | -                    | -       |
| com.ning:compress-lzf:jar:1.0.2                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/ning/compress-lzf/1.0.2/compress-lzf-1.0.2.jar)                                                     | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/ning/compress-lzf/1.0.2/compress-lzf-1.0.2.jar)                                                     | -                      | -                      | -                    | -       |
| com.spatial4j:spatial4j:jar:0.4.1                                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/spatial4j/spatial4j/0.4.1/spatial4j-0.4.1.jar)                                                      | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/spatial4j/spatial4j/0.4.1/spatial4j-0.4.1.jar)                                                      | -                      | -                      | -                    | -       |
| com.sun.jersey:jersey-client:jar:1.13                                  | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/sun/jersey/jersey-client/1.13/jersey-client-1.13.jar)                                               | -                      | -                      | -                    | -       |
| com.sun.jersey:jersey-core:jar:1.13                                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/sun/jersey/jersey-core/1.13/jersey-core-1.13.jar)                                                   | -                      | -                      | -                    | -       |
| com.sun.jersey:jersey-json:jar:1.13                                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/sun/jersey/jersey-json/1.13/jersey-json-1.13.jar)                                                   | -                      | -                      | -                    | -       |
| com.sun.xml.bind:jaxb-impl:jar:2.2.3-1                                 | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/sun/xml/bind/jaxb-impl/2.2.3-1/jaxb-impl-2.2.3-1.jar)                                               | -                      | -                      | -                    | -       |
| com.tdunning:t-digest:jar:3.0                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/tdunning/t-digest/3.0/t-digest-3.0.jar)                                                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/tdunning/t-digest/3.0/t-digest-3.0.jar)                                                             | -                      | -                      | -                    | -       |
| com.twitter:jsr166e:jar:1.1.0                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/twitter/jsr166e/1.1.0/jsr166e-1.1.0.jar)                                                            | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/twitter/jsr166e/1.1.0/jsr166e-1.1.0.jar)                                                            | -                      | -                      | -                    | -       |
| com.vividsolutions:jts:jar:1.13                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/vividsolutions/jts/1.13/jts-1.13.jar)                                                               | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/vividsolutions/jts/1.13/jts-1.13.jar)                                                               | -                      | -                      | -                    | -       |
| commons-cli:commons-cli:jar:1.3.1                                      | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-cli/commons-cli/1.3.1/commons-cli-1.3.1.jar)                                                    | -                      | -                      | -                    | -       |
| commons-codec:commons-codec:jar:1.6                                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.jar)                                                  | -                      | -                      | -                    | -       |
| commons-logging:commons-logging:jar:1.1.3                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.1.3/commons-logging-1.1.3.jar)                                        | -                      | -                      | -                    | -       |
| io.netty:netty:jar:3.10.5.Final                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/io/netty/netty/3.10.5.Final/netty-3.10.5.Final.jar)                                                     | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/io/netty/netty/3.10.5.Final/netty-3.10.5.Final.jar)                                                     | -                      | -                      | -                    | -       |
| javax.activation:activation:jar:1.1                                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/javax/activation/activation/1.1/activation-1.1.jar)                                                     | -                      | -                      | -                    | -       |
| javax.inject:javax.inject:jar:1                                        | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/javax/inject/javax.inject/1/javax.inject-1.jar)                                                         | -                      | -                      | -                    | -       |
| javax.mail:mail:jar:1.4.5                                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/javax/mail/mail/1.4.5/mail-1.4.5.jar)                                                                   | -                      | -                      | -                    | -       |
| javax.xml.bind:jaxb-api:jar:2.2.2                                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/javax/xml/bind/jaxb-api/2.2.2/jaxb-api-2.2.2.jar)                                                       | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/javax/xml/bind/jaxb-api/2.2.2/jaxb-api-2.2.2.jar)                                                       | -                      | -                      | -                    | -       |
| javax.xml.stream:stax-api:jar:1.0-2                                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/javax/xml/stream/stax-api/1.0-2/stax-api-1.0-2.jar)                                                     | -                      | -                      | -                    | -       |
| joda-time:joda-time:jar:2.8.2                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/joda-time/joda-time/2.8.2/joda-time-2.8.2.jar)                                                          | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/joda-time/joda-time/2.8.2/joda-time-2.8.2.jar)                                                          | -                      | -                      | -                    | -       |
| junit:junit:jar:4.11                                                   | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/junit/junit/4.11/junit-4.11.jar)                                                                        | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/junit/junit/4.11/junit-4.11.jar)                                                                        | -                      | -                      | -                    | -       |
| log4j:apache-log4j-extras:jar:1.2.17                                   | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/log4j/apache-log4j-extras/1.2.17/apache-log4j-extras-1.2.17.jar)                                        | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/log4j/apache-log4j-extras/1.2.17/apache-log4j-extras-1.2.17.jar)                                        | -                      | -                      | -                    | -       |
| log4j:log4j:jar:1.2.17                                                 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/log4j/log4j/1.2.17/log4j-1.2.17.jar)                                                                    | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/log4j/log4j/1.2.17/log4j-1.2.17.jar)                                                                    | -                      | -                      | -                    | -       |
| net.java.dev.jna:jna:jar:4.1.0                                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/net/java/dev/jna/jna/4.1.0/jna-4.1.0.jar)                                                               | -                      | -                      | -                    | -       |
| org.antlr:antlr-runtime:jar:3.5                                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/antlr/antlr-runtime/3.5/antlr-runtime-3.5.jar)                                                      | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/antlr/antlr-runtime/3.5/antlr-runtime-3.5.jar)                                                      | -                      | -                      | -                    | -       |
| org.apache.ant:ant:jar:1.8.2                                           | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/ant/ant/1.8.2/ant-1.8.2.jar)                                                                 | -                      | -                      | -                    | -       |
| org.apache.commons:commons-lang3:jar:3.3.2                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.3.2/commons-lang3-3.3.2.jar)                                         | -                      | -                      | -                    | -       |
| org.apache.httpcomponents:httpclient:jar:4.3.6                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.3.6/httpclient-4.3.6.jar)                                        | -                      | -                      | -                    | -       |
| org.apache.httpcomponents:httpcore:jar:4.3.3                           | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.3.3/httpcore-4.3.3.jar)                                            | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-analyzers-common:jar:5.3.0                    | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-analyzers-common/5.3.0/lucene-analyzers-common-5.3.0.jar)                      | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-backward-codecs:jar:5.3.0                     | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-backward-codecs/5.3.0/lucene-backward-codecs-5.3.0.jar)                        | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-codecs:jar:5.3.0                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-codecs/5.3.0/lucene-codecs-5.3.0.jar)                                          | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-core:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-core/5.3.0/lucene-core-5.3.0.jar)                                              | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-expressions:jar:5.3.0                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-expressions/5.3.0/lucene-expressions-5.3.0.jar)                                | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-grouping:jar:5.3.0                            | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-grouping/5.3.0/lucene-grouping-5.3.0.jar)                                      | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-highlighter:jar:5.3.0                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-highlighter/5.3.0/lucene-highlighter-5.3.0.jar)                                | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-join:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-join/5.3.0/lucene-join-5.3.0.jar)                                              | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-memory:jar:5.3.0                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-memory/5.3.0/lucene-memory-5.3.0.jar)                                          | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-misc:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-misc/5.3.0/lucene-misc-5.3.0.jar)                                              | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-queries:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-queries/5.3.0/lucene-queries-5.3.0.jar)                                        | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-queryparser:jar:5.3.0                         | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-queryparser/5.3.0/lucene-queryparser-5.3.0.jar)                                | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-sandbox:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-sandbox/5.3.0/lucene-sandbox-5.3.0.jar)                                        | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-spatial:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-spatial/5.3.0/lucene-spatial-5.3.0.jar)                                        | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-spatial3d:jar:5.3.0                           | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-spatial3d/5.3.0/lucene-spatial3d-5.3.0.jar)                                    | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-suggest:jar:5.3.0                             | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-suggest/5.3.0/lucene-suggest-5.3.0.jar)                                        | -                      | -                      | -                    | -       |
| org.apache.lucene:lucene-test-framework:jar:5.3.0                      | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-test-framework/5.3.0/lucene-test-framework-5.3.0.jar)                          | -                      | -                      | -                    | -       |
| org.codehaus.groovy:groovy-all:jar:indy:2.4.4                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/groovy/groovy-all/2.4.4/groovy-all-2.4.4-indy.jar)                                         | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/groovy/groovy-all/2.4.4/groovy-all-2.4.4-indy.jar)                                         | -                      | -                      | -                    | -       |
| org.codehaus.jackson:jackson-core-asl:jar:1.9.2                        | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/jackson/jackson-core-asl/1.9.2/jackson-core-asl-1.9.2.jar)                                 | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/jackson/jackson-core-asl/1.9.2/jackson-core-asl-1.9.2.jar)                                 | -                      | -                      | -                    | -       |
| org.codehaus.jackson:jackson-jaxrs:jar:1.9.2                           | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/jackson/jackson-jaxrs/1.9.2/jackson-jaxrs-1.9.2.jar)                                       | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/jackson/jackson-jaxrs/1.9.2/jackson-jaxrs-1.9.2.jar)                                       | -                      | -                      | -                    | -       |
| org.codehaus.jackson:jackson-mapper-asl:jar:1.9.2                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/jackson/jackson-mapper-asl/1.9.2/jackson-mapper-asl-1.9.2.jar)                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/jackson/jackson-mapper-asl/1.9.2/jackson-mapper-asl-1.9.2.jar)                             | -                      | -                      | -                    | -       |
| org.codehaus.jackson:jackson-xc:jar:1.9.2                              | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/jackson/jackson-xc/1.9.2/jackson-xc-1.9.2.jar)                                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/jackson/jackson-xc/1.9.2/jackson-xc-1.9.2.jar)                                             | -                      | -                      | -                    | -       |
| org.codehaus.jettison:jettison:jar:1.1                                 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/codehaus/jettison/jettison/1.1/jettison-1.1.jar)                                                    | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/codehaus/jettison/jettison/1.1/jettison-1.1.jar)                                                    | -                      | -                      | -                    | -       |
| org.elasticsearch:elasticsearch:jar:2.1.0-SNAPSHOT                     | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | -                                                                                                                                                                                                                          | -                      | -                      | -                    | -       |
| org.elasticsearch:elasticsearch:test-jar:tests:2.1.0-SNAPSHOT          | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | -                                                                                                                                                                                                                          | -                      | -                      | -                    | -       |
| org.hamcrest:hamcrest-all:jar:1.3                                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                     | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                     | -                      | -                      | -                    | -       |
| org.hdrhistogram:HdrHistogram:jar:2.1.6                                | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hdrhistogram/HdrHistogram/2.1.6/HdrHistogram-2.1.6.jar)                                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hdrhistogram/HdrHistogram/2.1.6/HdrHistogram-2.1.6.jar)                                             | -                      | -                      | -                    | -       |
| org.joda:joda-convert:jar:1.2                                          | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/joda/joda-convert/1.2/joda-convert-1.2.jar)                                                         | -                      | -                      | -                    | -       |
| org.ow2.asm:asm:jar:4.1                                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/ow2/asm/asm/4.1/asm-4.1.jar)                                                                        | -                      | -                      | -                    | -       |
| org.ow2.asm:asm-commons:jar:4.1                                        | -                                                                                                                                                                                                                                                                | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/4.1/asm-commons-4.1.jar)                                                        | -                      | -                      | -                    | -       |
| org.slf4j:slf4j-api:jar:1.6.2                                          | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/slf4j/slf4j-api/1.6.2/slf4j-api-1.6.2.jar)                                                          | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.6.2/slf4j-api-1.6.2.jar)                                                          | -                      | -                      | -                    | -       |
| org.yaml:snakeyaml:jar:1.15                                            | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar)                                                             | -             | -                | -                        | -   | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar)                                                             | -                      | -                      | -                    | -       |
| Total                                                                  | sonatype.releases                                                                                                                                                                                                                                                | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | spy | central                                                                                                                                                                                                                    | eclipselink.repository | elasticsearch-releases | repository.jboss.org | Twitter |
| 72 (compile: 23, test: 7, provided: 42)                                | 34                                                                                                                                                                                                                                                               | 0             | 0                | 0                        | 0   | 70                                                                                                                                                                                                                         | 0                      | 0                      | 0                    | 0       |

------------------------------------------------------------------------

Copyright © 2009–2015. All rights reserved.

------------------------------------------------------------------------


