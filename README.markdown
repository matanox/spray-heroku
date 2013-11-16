## [spray](http://spray.io/) template project compatible with Heroku

This template is built on top the elegant template from https://github.com/matanster/spray-template.

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

## Important note
This template currently uses sbt 0.12.0, and changing it to use 0.12.4 or 0.13.0 [seems to not work](http://stackoverflow.com/questions/19998340/failing-to-include-com-typesafe-in-build-sbt-for-scala-and-spray-on-heroku).

## Additional resources
[spray.io](http://spray.io/)
[Heroku Scala getting started](https://devcenter.heroku.com/articles/getting-started-with-scala) - this is not spray.io specific but may add some insight
