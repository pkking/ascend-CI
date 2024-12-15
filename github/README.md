There are two ways to provide Ascend hardware to projects hosted on github for PR CI or daily CI.

# projects who accept to install a github app
The github app will acquire github action runners permission, after the permission were granted an Ascend powered runner will be provided into the org.
For developer in the org who installed the github app, just change the github action workflow by setting `runs-on: ascend-ci-runners`

# projects who do not accept to install a github app