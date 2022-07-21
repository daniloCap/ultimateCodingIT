[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  1.484 s
[INFO] Finished at: 2022-07-21T10:32:17+02:00
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal on project swagger-coverage-rest-assured: Could not resolve dependencies for project com.github.viclovsky:swagger-coverage-rest-assured:jar:1.0-SNAPSHOT: The following artifacts could not be resolved: com.github.viclovsky:swagger-coverage-commons:jar:1.3.0, com.github.viclovsky.swagger.coverage:swagger-coverage-model:jar:1.1.4, com.github.viclovsky:swagger-coverage-commandline:jar:1.3.0, com.github.viclovsky.swagger.coverage:swagger-coverage-rest-assured:jar:1.3.0: com.github.viclovsky:swagger-coverage-commons:jar:1.3.0 was not found in https://repo.maven.apache.org/maven2 during a previous attempt. This failure was cached in the local repository and resolution is not reattempted until the update interval of central has elapsed or updates are forced -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/DependencyResolutionException
zdchaen@seliiuvd01810[10:32][Downloads/swagger-coverage-master/swagger-coverage-rest-assured]$ mvn clean install
[INFO] Scanning for projects...
[ERROR] [ERROR] Some problems were encountered while processing the POMs:
[WARNING] 'dependencies.dependency.(groupId:artifactId:type:classifier)' must be unique: com.github.viclovsky:swagger-coverage-commons:jar -> version 1.0-SNAPSHOT vs 1.3.0 @ line 72, column 21
[WARNING] 'dependencies.dependency.(groupId:artifactId:type:classifier)' must be unique: io.rest-assured:rest-assured:jar -> version (?) vs 5.1.1 @ line 95, column 21
[ERROR] 'dependencies.dependency.version' for com.github.viclovsky.swagger.coverage:swagger-coverage-rest-assured:jar is missing. @ line 89, column 21
 @ 
[ERROR] The build could not read 1 project -> [Help 1]
[ERROR]   
[ERROR]   The project com.github.viclovsky:swagger-coverage-rest-assured:1.0-SNAPSHOT (/home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-rest-assured/pom.xml) has 1 error
[ERROR]     'dependencies.dependency.version' for com.github.viclovsky.swagger.coverage:swagger-coverage-rest-assured:jar is missing. @ line 89, column 21
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/ProjectBuildingException
zdchaen@seliiuvd01810[10:36][Downloads/swagger-coverage-master/swagger-coverage-rest-assured]$ 

