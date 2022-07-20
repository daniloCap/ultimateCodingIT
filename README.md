
com.jayway.jsonpath:com.jayway.jsonpath:pom:0.8.1.wso2v1 failed to transfer from http://0.0.0.0/ during a previous attempt. This failure was cached in the local repository and resolution is not reattempted until the update interval of maven-default-http-blocker has elapsed or updates are forced. Original error: Could not transfer artifact com.jayway.jsonpath:com.jayway.jsonpath:pom:0.8.1.wso2v1 from/to maven-default-http-blocker (http://0.0.0.0/): Blocked mirror for repositories: [sonom (http://ieatrcxb3788.athtem.eei.ericsson.se:8081/artifactory/sonom-virtual, default, releases+snapshots), prototype (http://eselivm2v238l.lmera.ericsson.se:8081/nexus/content/repositories/prototype, default, releases+snapshots), central-uk-nonproxy (http://uk.maven.org/maven2/, default, releases+snapshots)]

Since Maven 3.8.1 http repositories are blocked.

Possible solutions:
- Check that Maven settings.xml does not contain http repositories
- Check that Maven pom files do not contain http repository http://ieatrcxb3788.athtem.eei.ericsson.se:8081/artifactory/sonom-virtual
- Check that Maven pom files do not contain http repository http://eselivm2v238l.lmera.ericsson.se:8081/nexus/content/repositories/prototype
- Check that Maven pom files do not contain http repository http://uk.maven.org/maven2/
- Add a mirror(s) for http://ieatrcxb3788.athtem.eei.ericsson.se:8081/artifactory/sonom-virtual, http://eselivm2v238l.lmera.ericsson.se:8081/nexus/content/repositories/prototype, http://uk.maven.org/maven2/ that allows http url in the Maven settings.xml
- Downgrade Maven to version 3.8.1 or earlier in settings


