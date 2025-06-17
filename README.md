# Victoria Bros. Actions for GitHub Actions

GitHub Actions used in Victoria Bros. for common actions such as Amazon ECR and language-specific actions such as running tests in Node.js.

**Available Actions**

See actions yaml file for input and output

- [common](./.github/common)
  - [build-vars](./.github/common/build-vars)
  - [deploy-do](./.github/common/deploy-do/action.yaml)
  - [push-ecr](./.github/common/push-ecr)
  - [setup-ssh](./.github/common/setup-ssh/action.yaml)

- [node](./.github/node)
  - [build-image](./.github/node/build-image)
  - [run-test](./.github/node/run-test/action.yaml)

- [eks](./.github/eks)
  - [aws-cli](./.github/eks/aws-cli/action.yaml)
  - [deploy-helm](./.github/eks/deploy-helm/action.yaml)
  - [eksctl](./.github/eks/eksctl/action.yaml)
  - [extract-image-tag](./.github/eks/extract-image-tag)
  - [setup-helm](./.github/eks/setup-helm/action.yaml)
  - [setup-iam](./.github/eks/setup-iam/action.yaml)
  - [update-kubeconfig](./.github/eks/update-kubeconfig/action.yaml)

- [python](./.github/python)
  - [build-image](./.github/python/build-image)
  - [build-vars](./.github/python/build-vars)
