$ helm lint charts/*
$ helm package charts/*
$ helm repo index --url https://symfonylab.github.io/helm/ .
$ helm repo index --url https://symfonylab.github.io/helm/ --merge index.yaml .
