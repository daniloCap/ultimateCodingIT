
[INFO] Total time:  2.384 s
[INFO] Finished at: 2022-07-20T11:31:25+02:00
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.7.0:compile (default-compile) on project swagger-coverage-commons: Compilation failure: Compilation failure: 
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/CoverageOutputWriter.java:[3,25] package io.swagger.models does not exist
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/CoverageOutputWriter.java:[4,32] package io.swagger.v3.oas.models does not exist
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/CoverageOutputWriter.java:[8,16] cannot find symbol
[ERROR]   symbol:   class Swagger
[ERROR]   location: interface com.github.viclovsky.swagger.coverage.CoverageOutputWriter
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/CoverageOutputWriter.java:[10,16] cannot find symbol
[ERROR]   symbol:   class OpenAPI
[ERROR]   location: interface com.github.viclovsky.swagger.coverage.CoverageOutputWriter
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/FileSystemOutputWriter.java:[5,25] package io.swagger.models does not exist
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/FileSystemOutputWriter.java:[6,32] package io.swagger.v3.oas.models does not exist
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/FileSystemOutputWriter.java:[39,23] cannot find symbol
[ERROR]   symbol:   class Swagger
[ERROR]   location: class com.github.viclovsky.swagger.coverage.FileSystemOutputWriter
[ERROR] /home/zdchaen/Downloads/swagger-coverage-master/swagger-coverage-commons/src/main/java/com/github/viclovsky/swagger/coverage/FileSystemOutputWriter.java:[51,23] cannot find symbol
[ERROR]   symbol:   class OpenAPI
[ERROR]   location: class com.github.viclovsky.swagger.coverage.FileSystemOutputWriter
[ERROR] -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException
