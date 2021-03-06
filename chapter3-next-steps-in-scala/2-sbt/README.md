SBT Basics
===

This file contains the `sbt` exercises. For each exercise, you have to create a simple `sbt` project in this directory. You only have to submit the final state of the project; the intermediate steps that some of the exercises have are still important for your understanding, but don't need to be submitted.

1. Create an SBT project in a directory `1-hello-world`, with code in `src/main/scala`. When running this project with `sbt run`, it should print `Hello world!`

2. Create an SBT project in a directory `2-dependencies`, make it use scala version 2.11.7. Add a dependency on Joda Time, and open a console. Create a Joda DateTime in the console. Add a test-dependency on Scalatest, write a test for Joda Datetime that fails. Keep tests running with a tilde task. Change the test until it passes.

3. Create an SBT project in a directory `3-errors`, add a source file with at least 5 errors. Change a setting interactively to make SBT only show you 3 errors. Then save the setting (this is not what you'd normally do, but required to review the solution ;)).

4. Create an SBT project in a directory `4-updates`, and add an older version of Joda Time as a dependency. Setup the `sbt-updates` plugin in the project and get it to tell you that you should update Joda time.