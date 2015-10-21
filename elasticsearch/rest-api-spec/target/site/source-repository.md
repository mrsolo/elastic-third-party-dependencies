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
    -   [Dependency Convergence](dependency-convergence.html "Dependency Convergence")
    -   **Source Repository**
    -   [Mailing Lists](mail-lists.html "Mailing Lists")
    -   [Issue Tracking](issue-tracking.html "Issue Tracking")
    -   [Continuous Integration](integration.html "Continuous Integration")
    -   [Project Plugins](plugins.html "Project Plugins")
    -   [Project License](license.html "Project License")
    -   [Project Team](team-list.html "Project Team")
    -   [Project Summary](project-summary.html "Project Summary")
    -   [Dependencies](dependencies.html "Dependencies")

[![Built by Maven](./images/logos/maven-feather.png)](http://maven.apache.org/ "Built by Maven")

Overview
--------

This project uses [Subversion](http://subversion.apache.org/) to manage its source code. Instructions on Subversion use can be found at <http://svnbook.red-bean.com/>.

Web Access
----------

The following is a link to the online source repository.

    http://svn.sonatype.org/spice/tags/oss-parent-7/rest-api-spec

Anonymous access
----------------

The source can be checked out anonymously from SVN with this command:

    $ svn checkout http://svn.sonatype.org/spice/tags/oss-parent-7/rest-api-spec rest-api-spec

Developer access
----------------

Everyone can access the Subversion repository via HTTP, but Committers must checkout the Subversion repository via HTTPS.

    $ svn checkout https://svn.sonatype.org/spice/tags/oss-parent-7/rest-api-spec rest-api-spec

To commit changes to the repository, execute the following command to commit your changes (svn will prompt you for your password)

    $ svn commit --username your-username -m "A message"

Access from behind a firewall
-----------------------------

For those users who are stuck behind a corporate firewall which is blocking HTTP access to the Subversion repository, you can try to access it via the developer connection:

    $ svn checkout https://svn.sonatype.org/spice/tags/oss-parent-7/rest-api-spec rest-api-spec

Access through a proxy
----------------------

The Subversion client can go through a proxy, if you configure it to do so. First, edit your "servers" configuration file to indicate which proxy to use. The file's location depends on your operating system. On Linux or Unix it is located in the directory "~/.subversion". On Windows it is in "%APPDATA%\\Subversion". (Try "echo %APPDATA%", note this is a hidden directory.)

There are comments in the file explaining what to do. If you don't have that file, get the latest Subversion client and run any command; this will cause the configuration directory and template files to be created.

Example: Edit the 'servers' file and add something like:

    [global]
    http-proxy-host = your.proxy.name
    http-proxy-port = 3128

------------------------------------------------------------------------

Copyright © 2015. All Rights Reserved.

------------------------------------------------------------------------


