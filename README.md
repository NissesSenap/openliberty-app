# OpenLiberty getting started

Using this repo to run a tekton job.

I have taken the https://openliberty.io/guides/getting-started.html OpenLiberty app.
I haven't done any changes to it, except moved out the finish file to the root of project.

## docker

podman run -it -p 9080:9080 508f728a66d

## Integration-test

mvn failsafe:integration-test

## endpoints

http://localhost:9080/metrics/
http://localhost:9080/health/
http://localhost:9080/ibm/api/
http://localhost:9080/
