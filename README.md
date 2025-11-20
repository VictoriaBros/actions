# Victoria Bros. Actions for GitHub Actions

GitHub Actions used in Victoria Bros. for common actions such as Amazon ECR, Digital Ocean, SSH and language-specific actions such as running tests in Node.js.

**Available Actions**

See actions yaml file for input and output

- [aws](./.github/aws)
  - [aws-cli](./.github/aws/aws-cli/action.yaml)
  - [push-ecr](./.github/aws/push-ecr)

- [digitalocean](./.github/digitalocean)
  - [deploy](./.github/digitalocean/deploy/action.yaml)

- [node](./.github/node)
  - [build-env](./.github/node/build-env/action.yaml)
  - [build-image](./.github/node/build-image)
  - [build-vars](./.github/node/build-vars)
  - [run-test](./.github/node/run-test/action.yaml)

- [eks](./.github/eks)
  - [deploy-helm](./.github/eks/deploy-helm/action.yaml)
  - [eksctl](./.github/eks/eksctl/action.yaml)
  - [extract-image-tag](./.github/eks/extract-image-tag)
  - [setup-helm](./.github/eks/setup-helm/action.yaml)
  - [setup-iam](./.github/eks/setup-iam/action.yaml)
  - [update-kubeconfig](./.github/eks/update-kubeconfig/action.yaml)

- [python](./.github/python)
  - [build-image](./.github/python/build-image)
  - [build-vars](./.github/python/build-vars)
  - [run-test](./.github/python/run-test)

- [rust](./.github/rust)
  - [build-image](./.github/rust/build-image)
  - [build-vars](./.github/rust/build-vars)
  - [run-test](./.github/rust/run-test)

- [eas](./.github/eas)
  - [eas-build](./.github/eas/eas-build/action.yaml)
  - [setup-jdk-generate-apk](./.github/eas/setup-jdk-generate-apk/action.yaml)
  - [setup-node-pnpm-install](./.github/eas/setup-node-pnpm-install/action.yaml)

- [ssh](./.github/ssh)
  - [setup](./.github/ssh/setup/action.yaml)
  - [copy](./.github/ssh/copy/action.yaml)
