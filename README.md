# release-test
This repo is a demonstration of a release pipeline in which - once a PR is merged to main - a new tag is pushed and then a release is triggered. In order to circumvent the fact that if a github action uses the repository `$GITHUB_TOKEN` other github actions will not be kicked off, I have created a personal token that is used for `new-tag.yml`. 
