Rest API Specification

------------------------------------------------------------------------

<span id="publishDate">Last Published: 2015-10-21</span>  | <span id="projectVersion">Version: 2.1.0-SNAPSHOT</span>

[Rest API Specification](./ "Rest API Specification")

------------------------------------------------------------------------

##### Project Documentation

-   [Project Information](project-info.html "Project Information")
    -   [About](index.html "About")
    -   [Plugin Management](plugin-management.html "Plugin Management")
    -   [Distribution Management](distribution-management.html "Distribution Management")
    -   [Dependency Information](dependency-info.html "Dependency Information")
    -   **Dependency Convergence**
    -   [Source Repository](source-repository.html "Source Repository")
    -   [Mailing Lists](mail-lists.html "Mailing Lists")
    -   [Issue Tracking](issue-tracking.html "Issue Tracking")
    -   [Continuous Integration](integration.html "Continuous Integration")
    -   [Project Plugins](plugins.html "Project Plugins")
    -   [Project License](license.html "Project License")
    -   [Project Team](team-list.html "Project Team")
    -   [Project Summary](project-summary.html "Project Summary")
    -   [Dependencies](dependencies.html "Dependencies")

[![Built by Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

Reactor Dependency Convergence
------------------------------

|                                         |                                                                 |
|-----------------------------------------|-----------------------------------------------------------------|
| ![success](images/icon_success_sml.gif) | All projects share one version of the dependency.               |
| ![error](images/icon_error_sml.gif)     | At least one project has a differing version of the dependency. |

|                                                        |                                                     |
|--------------------------------------------------------|-----------------------------------------------------|
| Number of sub-projects:                                | 29                                                  |
| Number of dependencies (NOD):                          | 52                                                  |
| Number of unique artifacts (NOA):                      | 52                                                  |
| Number of SNAPSHOT artifacts (NOS):                    | 0                                                   |
| Convergence (NOD/NOA):                                 | ![success](images/icon_success_sml.gif) **100%**    |
| Ready for Release (100% Convergence and no SNAPSHOTS): | ![success](images/icon_success_sml.gif) **Success** |

### Dependencies used in sub-projects

#### com.amazonaws:aws-java-sdk-ec2

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.10.19</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.amazonaws:aws-java-sdk-s3

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.10.19</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.carrotsearch.randomizedtesting:randomizedtesting-runner

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.1.16</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.carrotsearch:hppc

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">0.7.1</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.fasterxml.jackson.core:jackson-core

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.6.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.fasterxml.jackson.dataformat:jackson-dataformat-cbor

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.6.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.fasterxml.jackson.dataformat:jackson-dataformat-smile

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.6.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.fasterxml.jackson.dataformat:jackson-dataformat-yaml

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.6.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.github.spullara.mustache.java:compiler

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">0.8.13</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.google.apis:google-api-services-compute

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">v1-rev71-1.20.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.google.guava:guava

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">18.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.google.jimfs:jimfs

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.microsoft.azure:azure-management

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">0.7.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.microsoft.azure:azure-management-compute

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">0.7.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.microsoft.azure:azure-storage

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.0.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.ning:compress-lzf

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.0.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.spatial4j:spatial4j

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">0.4.1</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.tdunning:t-digest

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.twitter:jsr166e

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.1.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### com.vividsolutions:jts

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.13</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### commons-cli:commons-cli

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.3.1</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### io.netty:netty

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">3.10.5.Final</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### joda-time:joda-time

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.8.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### log4j:apache-log4j-extras

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.2.17</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### log4j:log4j

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.2.17</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-client">org.elasticsearch.qa:smoke-test-client</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### net.java.dev.jna:jna

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">4.1.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.httpcomponents:httpclient

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">4.3.6</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-analyzers-common

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-analyzers-icu

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-analyzers-kuromoji

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-analyzers-phonetic

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-analyzers-smartcn

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-analyzers-stempel

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-backward-codecs

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-core

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-expressions

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-highlighter

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-join

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-memory

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-queries

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-queryparser

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-spatial

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-suggest

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.apache.lucene:lucene-test-framework

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">5.3.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa">org.elasticsearch.qa:elasticsearch-qa</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-client">org.elasticsearch.qa:smoke-test-client</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.codehaus.groovy:groovy-all

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.4.4</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.elasticsearch:elasticsearch

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.1.0-SNAPSHOT</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-client">org.elasticsearch.qa:smoke-test-client</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.hamcrest:hamcrest-all

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.3</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.deb:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.tar:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions/elasticsearch">org.elasticsearch.distribution.zip:elasticsearch</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/distributions">org.elasticsearch.distribution:distributions</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa">org.elasticsearch.qa:elasticsearch-qa</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-client">org.elasticsearch.qa:smoke-test-client</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.hdrhistogram:HdrHistogram

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.1.6</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.joda:joda-convert

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.mozilla:rhino

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.7R4</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.python:jython-standalone

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">2.7.0</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

#### org.slf4j:slf4j-api

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><img src="images/icon_success_sml.gif" alt="success" /></td>
<td align="left"><table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left">1.6.2</td>
<td align="left"><ol>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-icu">org.elasticsearch.plugin:analysis-icu</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-kuromoji">org.elasticsearch.plugin:analysis-kuromoji</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-phonetic">org.elasticsearch.plugin:analysis-phonetic</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-smartcn">org.elasticsearch.plugin:analysis-smartcn</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/analysis-stempel">org.elasticsearch.plugin:analysis-stempel</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-aws">org.elasticsearch.plugin:cloud-aws</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-azure">org.elasticsearch.plugin:cloud-azure</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/cloud-gce">org.elasticsearch.plugin:cloud-gce</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/delete-by-query">org.elasticsearch.plugin:delete-by-query</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/discovery-multicast">org.elasticsearch.plugin:discovery-multicast</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/jvm-example">org.elasticsearch.plugin:jvm-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-javascript">org.elasticsearch.plugin:lang-javascript</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/lang-python">org.elasticsearch.plugin:lang-python</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-murmur3">org.elasticsearch.plugin:mapper-murmur3</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/mapper-size">org.elasticsearch.plugin:mapper-size</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins">org.elasticsearch.plugin:plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/plugins/site-example">org.elasticsearch.plugin:site-example</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-multinode">org.elasticsearch.qa:smoke-test-multinode</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch-qa/smoke-test-plugins">org.elasticsearch.qa:smoke-test-plugins</a></li>
<li><a href="http://nexus.sonatype.org/oss-repository-hosting.html/parent/elasticsearch">org.elasticsearch:elasticsearch</a></li>
</ol></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

------------------------------------------------------------------------

Copyright © 2015. All Rights Reserved.

------------------------------------------------------------------------


