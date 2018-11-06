Produced to illustrate https://github.com/gradle/gradle/issues/7634

`./gradlew generateMyResources`

```
$ ./gradlew generateMyResources
> Task :generateMyResources FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':generateMyResources'.
> Could not copy file '/Users/devin/dev/gradle-expand-test/my-resources/my-resource.txt' to '/Users/devin/dev/gradle-expand-test/build/generated-my-resources/my-resource.txt'.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 0s
1 actionable task: 1 executed
```
