# GitHub-Actions-Playbook

## To Use
`export PERSONAL_ACCESS_TOKEN=<your PAT>`

Update values in `vars.yml`.

Dynamically download, register and start a GitHub Actions self-hosted runner.

## Setup Runner
`sudo ansible-playbook -i inventory setup.yml`

## Tear Down Runner
`sudo ansible-playbook -i inventory tear_down.yml`
