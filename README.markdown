## [spray](http://spray.io/) template project compatible with Heroku

This template is built on top the elegant template from https://github.com/spray/spray-template.

Follow these steps to get started:

1. Git-clone this repository.

2. Change directory into your clone.

3. Launch SBT:

        $ sbt

4. Compile everything and run all tests:

        > test

5. Start the application:

        > re-start

6. Browse to http://localhost:8080/

7. Stop the application:

        > re-stop

8. Learn more at http://www.spray.io/

9. Start hacking on `src/main/scala/com/example/MyService.scala`

## Additional resources
+ [spray.io](http://spray.io/)
+ [Heroku Scala getting started](https://devcenter.heroku.com/articles/getting-started-with-scala) - this is not spray.io specific but may add some insight

## Eclipse integration
This template is also compatible with eclipse (verified on Kepler). 
To generate an eclipse project for it, run `sbt eclipse` after having installed the sbtecilpse plugin version that matches your version of sbt. 
You can then import and run the project in eclipse, by locating in eclipse to the `Boot.scala` source file, and clicking the `run` icon. In the import wizard, select to import an existing project.
