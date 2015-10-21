QA: Parent POM

------------------------------------------------------------------------

<span id="publishDate">Last Published: 2015-10-21</span>  | <span id="projectVersion">Version: 2.1.0-SNAPSHOT</span>

------------------------------------------------------------------------

[![Built by Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

Project Dependencies
--------------------

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId           | ArtifactId                                                                            | Version | Type | License                                                               |
|-------------------|---------------------------------------------------------------------------------------|---------|------|-----------------------------------------------------------------------|
| org.apache.lucene | [lucene-test-framework](http://lucene.apache.org/lucene-parent/lucene-test-framework) | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)            |
| org.hamcrest      | [hamcrest-all](https://github.com/hamcrest/JavaHamcrest/hamcrest-all)                 | 1.3     | jar  | [New BSD License](http://www.opensource.org/licenses/bsd-license.php) |

Project Transitive Dependencies
-------------------------------

The following is a list of transitive dependencies for this project. Transitive dependencies are the dependencies of the project dependencies.

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId                            | ArtifactId                                                                        | Version | Type | License                                                                                    |
|------------------------------------|-----------------------------------------------------------------------------------|---------|------|--------------------------------------------------------------------------------------------|
| com.carrotsearch.randomizedtesting | [randomizedtesting-runner](http://labs.carrotsearch.com/randomizedtesting-runner) | 2.1.16  | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| junit                              | [junit](http://junit.org)                                                         | 4.11    | jar  | [Common Public License Version 1.0](http://www.opensource.org/licenses/cpl1.0.txt)         |
| org.apache.ant                     | [ant](http://ant.apache.org/ant/)                                                 | 1.8.2   | jar  | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.apache.lucene                  | [lucene-codecs](http://lucene.apache.org/lucene-parent/lucene-codecs)             | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                 |
| org.apache.lucene                  | [lucene-core](http://lucene.apache.org/lucene-parent/lucene-core)                 | 5.3.0   | jar  | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)                                 |

Project Dependency Graph
------------------------

### Dependency Tree

-   org.elasticsearch.qa:elasticsearch-qa:pom:2.1.0-SNAPSHOT ![Information](./images/icon_info_sml.gif)
    <table>
    <colgroup>
    <col width="100%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th align="left">QA: Parent POM</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td align="left"><p><strong>Description:</strong> Parent POM</p>
    <p><strong>URL:</strong> <a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa" class="uri">http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa</a></p>
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

**Apache 2:** Lucene Core, Lucene Test Framework, Lucene codecs

**New BSD License:** Hamcrest All

**Common Public License Version 1.0:** JUnit

**The Apache Software License, Version 2.0:** Apache Ant Core, QA: Parent POM, RandomizedTesting Randomized Runner

Dependency File Details
-----------------------

| Filename                            | Size           | Entries     | Classes     | Packages  | JDK Rev | Debug   |
|-------------------------------------|----------------|-------------|-------------|-----------|---------|---------|
| randomizedtesting-runner-2.1.16.jar | 207.89 kB      | 173         | 159         | 5         | 1.6     | debug   |
| junit-4.11.jar                      | 239.30 kB      | 266         | 233         | 28        | 1.5     | debug   |
| ant-1.8.2.jar                       | 1.84 MB        | 1,168       | 1,090       | 59        | 1.4     | debug   |
| lucene-codecs-5.3.0.jar             | 408.73 kB      | 224         | 206         | 6         | 1.6     | debug   |
| lucene-core-5.3.0.jar               | 2.25 MB        | 1,563       | 1,532       | 21        | 1.6     | debug   |
| lucene-test-framework-5.3.0.jar     | 6.23 MB        | 482         | 451         | 19        | 1.6     | debug   |
| hamcrest-all-1.3.jar                | 299.39 kB      | 249         | 204         | 23        | 1.5     | debug   |
| Total                               | Size           | Entries     | Classes     | Packages  | JDK Rev | Debug   |
| 7                                   | 11.45 MB       | 4,125       | 3,875       | 161       | 1.6     | 7       |
| test: 7                             | test: 11.45 MB | test: 4,125 | test: 3,875 | test: 161 | -       | test: 7 |

Dependency Repository Locations
-------------------------------

| Repo ID                  | URL                                                        | Release | Snapshot |
|--------------------------|------------------------------------------------------------|---------|----------|
| sonatype.releases        | <https://oss.sonatype.org/content/repositories/releases>   | Yes     | Yes      |
| oss-snapshots            | <https://oss.sonatype.org/content/repositories/snapshots/> | Yes     | Yes      |
| apache.snapshots         | <http://repository.apache.org/snapshots>                   | -       | -        |
| sonatype-nexus-snapshots | <https://oss.sonatype.org/content/repositories/snapshots>  | -       | Yes      |
| central                  | <http://repo.maven.apache.org/maven2>                      | Yes     | -        |
| elasticsearch-releases   | <http://maven.elasticsearch.org/releases>                  | Yes     | -        |

Repository locations for each of the Dependencies.

| Artifact                                                               | sonatype.releases                                                                                                                                                                                                                                                | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | central                                                                                                                                                                                                                    | elasticsearch-releases |
|------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|
| com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | -                      |
| junit:junit:jar:4.11                                                   | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/junit/junit/4.11/junit-4.11.jar)                                                                        | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/junit/junit/4.11/junit-4.11.jar)                                                                        | -                      |
| org.apache.ant:ant:jar:1.8.2                                           | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/ant/ant/1.8.2/ant-1.8.2.jar)                                                                 | -                      |
| org.apache.lucene:lucene-codecs:jar:5.3.0                              | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-codecs/5.3.0/lucene-codecs-5.3.0.jar)                                          | -                      |
| org.apache.lucene:lucene-core:jar:5.3.0                                | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-core/5.3.0/lucene-core-5.3.0.jar)                                              | -                      |
| org.apache.lucene:lucene-test-framework:jar:5.3.0                      | -                                                                                                                                                                                                                                                                | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-test-framework/5.3.0/lucene-test-framework-5.3.0.jar)                          | -                      |
| org.hamcrest:hamcrest-all:jar:1.3                                      | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                     | -             | -                | -                        | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar)                                                     | -                      |
| Total                                                                  | sonatype.releases                                                                                                                                                                                                                                                | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | central                                                                                                                                                                                                                    | elasticsearch-releases |
| 7 (test: 7)                                                            | 3                                                                                                                                                                                                                                                                | 0             | 0                | 0                        | 7                                                                                                                                                                                                                          | 0                      |

------------------------------------------------------------------------

Copyright © 2015. All rights reserved.

------------------------------------------------------------------------


