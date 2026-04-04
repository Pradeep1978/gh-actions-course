# gh-actions-course
Repository containing all examples , as well as notes for the GitHub Actions course.

#list of obect way
on:
  push:
  pull_request:
  schedule:
    -cron:'0 0 * * * *'
  --6 or 5 
  workflow_dispatch:    manual trigger
  or 
https://www.freeformatter.com/cron-expression-generator-quartz.html
#list of array way
on: 
  -push
  -pull_request 
  -scedule