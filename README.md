# alter way helm-charts
alter way helm charts

## How to use 

1. Add alter way repo charts : https://alterway.github.io/helm-charts : `helm repo add alterway https://alterway.github.io/helm-charts`
2. Update repo charts list : `helm repo update`

## How to contribute

1. Clone repository
2. Add your chart repo
3. Lint your repo `helm lint [your-repo-dir]` eg. `helm lint aws-helloworld`
4. Package your release `helm package [your-repo-dir] -d packages` eg. `helm package aws-helloworld -d packages`
5. Index your chart `helm repo index --url https://alterway.github.io/helm-charts/ --merge index.yaml .`
6. Add files to github `git add . && git commit -m "my release" && git push`
7. If not already done add repo `helm repo add alterway https://alterway.github.io/helm-charts`
8. Update you repos `helm repo update` 
9. Search your release  `helm search repo [myrelease]` eg . `helm search repo helloworld`
    
