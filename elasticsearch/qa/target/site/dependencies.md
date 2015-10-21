<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <title>QA: Parent POM – Project Dependencies</title>
    <style type="text/css" media="all">
      @import url("./css/maven-base.css");
      @import url("./css/maven-theme.css");
      @import url("./css/site.css");
    </style>
    <link rel="stylesheet" href="./css/print.css" type="text/css" media="print">
    <meta name="Date-Revision-yyyymmdd" content="20151021">
    <meta http-equiv="Content-Language" content="en">
        
        </head>

 QA: Parent POM 

* * *

Last Published: 2015-10-21 &nbsp;| Version: 2.1.0-SNAPSHOT

* * *

 [![Built by Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

## Project Dependencies

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId | ArtifactId | Version | Type | License |
| --- | --- | --- | --- | --- |
| org.apache.lucene | [lucene-test-framework](http://lucene.apache.org/lucene-parent/lucene-test-framework) | 5.3.0 | jar | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.hamcrest | [hamcrest-all](https://github.com/hamcrest/JavaHamcrest/hamcrest-all) | 1.3 | jar | [New BSD License](http://www.opensource.org/licenses/bsd-license.php) |

## Project Transitive Dependencies

The following is a list of transitive dependencies for this project. Transitive dependencies are the dependencies of the project dependencies.

### test

The following is a list of test dependencies for this project. These dependencies are only required to compile and run unit tests for the application:

| GroupId | ArtifactId | Version | Type | License |
| --- | --- | --- | --- | --- |
| com.carrotsearch.randomizedtesting | [randomizedtesting-runner](http://labs.carrotsearch.com/randomizedtesting-runner) | 2.1.16 | jar | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| junit | [junit](http://junit.org) | 4.11 | jar | [Common Public License Version 1.0](http://www.opensource.org/licenses/cpl1.0.txt) |
| org.apache.ant | [ant](http://ant.apache.org/ant/) | 1.8.2 | jar | [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.apache.lucene | [lucene-codecs](http://lucene.apache.org/lucene-parent/lucene-codecs) | 5.3.0 | jar | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt) |
| org.apache.lucene | [lucene-core](http://lucene.apache.org/lucene-parent/lucene-core) | 5.3.0 | jar | [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt) |

## Project Dependency Graph
<script language="javascript" type="text/javascript">
      function toggleDependencyDetail( divId, imgId )
      {
        var div = document.getElementById( divId );
        var img = document.getElementById( imgId );
        if( div.style.display == '' )
        {
          div.style.display = 'none';
          img.src='./images/icon_info_sml.gif';
        }
        else
        {
          div.style.display = '';
          img.src='./images/close.gif';
        }
      }
</script>

### Dependency Tree

- org.elasticsearch.qa:elasticsearch-qa:pom:2.1.0-SNAPSHOT ![Information](./images/icon_info_sml.gif)

| QA: Parent POM |
| --- |
| 

**Description:** Parent POM

**URL:** [http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa](http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa)

**Project License:** [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)

 |

  - org.hamcrest:hamcrest-all:jar:1.3 (test) ![Information](./images/icon_info_sml.gif)

| Hamcrest All |
| --- |
| 

**Description:** A self-contained hamcrest jar containing all of the sub-modules in a single artifact.

**URL:** [https://github.com/hamcrest/JavaHamcrest/hamcrest-all](https://github.com/hamcrest/JavaHamcrest/hamcrest-all)

**Project License:** [New BSD License](http://www.opensource.org/licenses/bsd-license.php)

 |

  - org.apache.lucene:lucene-test-framework:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)

| Lucene Test Framework |
| --- |
| 

**Description:** Apache Lucene Java Test Framework

**URL:** [http://lucene.apache.org/lucene-parent/lucene-test-framework](http://lucene.apache.org/lucene-parent/lucene-test-framework)

**Project License:** [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)

 |

    - org.apache.lucene:lucene-codecs:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)

| Lucene codecs |
| --- |
| 

**Description:** Codecs and postings formats for Apache Lucene.

**URL:** [http://lucene.apache.org/lucene-parent/lucene-codecs](http://lucene.apache.org/lucene-parent/lucene-codecs)

**Project License:** [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)

 |

    - org.apache.lucene:lucene-core:jar:5.3.0 (test) ![Information](./images/icon_info_sml.gif)

| Lucene Core |
| --- |
| 

**Description:** Apache Lucene Java Core

**URL:** [http://lucene.apache.org/lucene-parent/lucene-core](http://lucene.apache.org/lucene-parent/lucene-core)

**Project License:** [Apache 2](http://www.apache.org/licenses/LICENSE-2.0.txt)

 |

    - com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 (test) ![Information](./images/icon_info_sml.gif)

| RandomizedTesting Randomized Runner |
| --- |
| 

**Description:** Foundation classes and rules for applying the principles of Randomized Testing.

**URL:** [http://labs.carrotsearch.com/randomizedtesting-runner](http://labs.carrotsearch.com/randomizedtesting-runner)

**Project License:** [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)

 |

    - junit:junit:jar:4.11 (test) ![Information](./images/icon_info_sml.gif)

| JUnit |
| --- |
| 

**Description:** JUnit is a regression testing framework written by Erich Gamma and Kent Beck. It is used by the developer who implements unit tests in Java.

**URL:** [http://junit.org](http://junit.org)

**Project License:** [Common Public License Version 1.0](http://www.opensource.org/licenses/cpl1.0.txt)

 |

    - org.apache.ant:ant:jar:1.8.2 (test) ![Information](./images/icon_info_sml.gif)

| Apache Ant Core |
| --- |
| 

**Description:** master POM

**URL:** [http://ant.apache.org/ant/](http://ant.apache.org/ant/)

**Project License:** [The Apache Software License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt)

 |

## Licenses

**Apache 2:** Lucene Core, Lucene Test Framework, Lucene codecs

**New BSD License:** Hamcrest All

**Common Public License Version 1.0:** JUnit

**The Apache Software License, Version 2.0:** Apache Ant Core, QA: Parent POM, RandomizedTesting Randomized Runner

## Dependency File Details

| Filename | Size | Entries | Classes | Packages | JDK Rev | Debug |
| --- | --- | --- | --- | --- | --- | --- |
| randomizedtesting-runner-2.1.16.jar | 207.89 kB | 173 | 159 | 5 | 1.6 | debug |
| junit-4.11.jar | 239.30 kB | 266 | 233 | 28 | 1.5 | debug |
| ant-1.8.2.jar | 1.84 MB | 1,168 | 1,090 | 59 | 1.4 | debug |
| lucene-codecs-5.3.0.jar | 408.73 kB | 224 | 206 | 6 | 1.6 | debug |
| lucene-core-5.3.0.jar | 2.25 MB | 1,563 | 1,532 | 21 | 1.6 | debug |
| lucene-test-framework-5.3.0.jar | 6.23 MB | 482 | 451 | 19 | 1.6 | debug |
| hamcrest-all-1.3.jar | 299.39 kB | 249 | 204 | 23 | 1.5 | debug |
| Total | Size | Entries | Classes | Packages | JDK Rev | Debug |
| --- | --- | --- | --- | --- | --- | --- |
| 7 | 11.45 MB | 4,125 | 3,875 | 161 | 1.6 | 7 |
| test: 7 | test: 11.45 MB | test: 4,125 | test: 3,875 | test: 161 | - | test: 7 |

## Dependency Repository Locations

| Repo ID | URL | Release | Snapshot |
| --- | --- | --- | --- |
| sonatype.releases | [https://oss.sonatype.org/content/repositories/releases](https://oss.sonatype.org/content/repositories/releases) | Yes | Yes |
| oss-snapshots | [https://oss.sonatype.org/content/repositories/snapshots/](https://oss.sonatype.org/content/repositories/snapshots/) | Yes | Yes |
| apache.snapshots | [http://repository.apache.org/snapshots](http://repository.apache.org/snapshots) | - | - |
| sonatype-nexus-snapshots | [https://oss.sonatype.org/content/repositories/snapshots](https://oss.sonatype.org/content/repositories/snapshots) | - | Yes |
| central | [http://repo.maven.apache.org/maven2](http://repo.maven.apache.org/maven2) | Yes | - |
| elasticsearch-releases | [http://maven.elasticsearch.org/releases](http://maven.elasticsearch.org/releases) | Yes | - |

Repository locations for each of the Dependencies.

| Artifact | sonatype.releases | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | central | elasticsearch-releases |
| --- | --- | --- | --- | --- | --- | --- |
| com.carrotsearch.randomizedtesting:randomizedtesting-runner:jar:2.1.16 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/com/carrotsearch/randomizedtesting/randomizedtesting-runner/2.1.16/randomizedtesting-runner-2.1.16.jar) | - |
| junit:junit:jar:4.11 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/junit/junit/4.11/junit-4.11.jar) | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/junit/junit/4.11/junit-4.11.jar) | - |
| org.apache.ant:ant:jar:1.8.2 | - | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/ant/ant/1.8.2/ant-1.8.2.jar) | - |
| org.apache.lucene:lucene-codecs:jar:5.3.0 | - | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-codecs/5.3.0/lucene-codecs-5.3.0.jar) | - |
| org.apache.lucene:lucene-core:jar:5.3.0 | - | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-core/5.3.0/lucene-core-5.3.0.jar) | - |
| org.apache.lucene:lucene-test-framework:jar:5.3.0 | - | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/apache/lucene/lucene-test-framework/5.3.0/lucene-test-framework-5.3.0.jar) | - |
| org.hamcrest:hamcrest-all:jar:1.3 | [![Found at https://oss.sonatype.org/content/repositories/releases](images/icon_success_sml.gif)](https://oss.sonatype.org/content/repositories/releases/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar) | - | - | - | [![Found at http://repo.maven.apache.org/maven2](images/icon_success_sml.gif)](http://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-all/1.3/hamcrest-all-1.3.jar) | - |
| Total | sonatype.releases | oss-snapshots | apache.snapshots | sonatype-nexus-snapshots | central | elasticsearch-releases |
| --- | --- | --- | --- | --- | --- | --- |
| 7 (test: 7) | 3 | 0 | 0 | 0 | 7 | 0 |

* * *

 Copyright © 2015. All rights reserved. 

* * *

