# Installing and running locally used commands, example found in p0dxd/website check issues and PR
`npm i -g renovate`
`renovate`
`renovate --platform=local`
`LOG_LEVEL="debug" npm renovate --platform=local --repository-cache=reset`
`renovate --write-discovered-repos=/tmp/renovate-repos.json`