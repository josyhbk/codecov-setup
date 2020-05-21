# codecov-setup


This is a simple repo to show how to setup codecov reports integration
with circleci

### Setup

Create a circleci context in this case i'll be using `dev`

Then create an Environment Variable called `CODECOV_TOKEN` and set the value to the upload token provided in the repo settings on the codecov console

Add the upload script at the end of your circleci pipeline and enjoy of the coverage reports in the codecov console. 
