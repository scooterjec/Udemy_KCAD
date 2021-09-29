# Udemy_KCAD

## CNCF Certification

[Certified Kubernetes Application Developer](https://www.cncf.io/certification/ckad/)

[Candidate Handbook](https://www.cncf.io/certification/candidate-handbook)

[Exam Tips](https://docs.linuxfoundation.org/tc-docs/certification/tips-cka-and-ckad)

  __Keep the code - DEVOPS15 - handy while registering for the CKA or CKAD exams at Linux Foundation to get a 15% discount.__

## Course resources

* [Course documentation](docs/KodeKloud-Kubernetes+-CKAD.pdf)
* [Networking](docs/Networking.pdf)
* [Services](docs/Services.pdf)

## Formatting Output with kubectl

```sh
kubectl [command] [TYPE] [NAME] -o <output_format>
```

Here are some of the commonly used formats:

`-o json` : Output a JSON formatted API object.

`-o name` : Print only the resource name and nothing else.

`-o wide` : Output in the plain-text format with any additional information.

`-o yaml` : Output a YAML formatted API object.

Example:

```sh
kubectl create namespace test-123 --dry-run -o yaml > ns-test-123.yaml
```
More info [here](https://kubernetes.io/docs/reference/kubectl/overview/) and [here](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
