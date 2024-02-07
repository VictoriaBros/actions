# Victoria Bros. Actions for GitHub Actions

GitHub Actions used in Victoria Bros. for common actions such as Amazon ECR and language-specific actions such as running tests in Node.js.

**Available Actions**

See actions yaml file for input and output

- [common](./.github/common)
  - [build-vars](./.github/common/build-vars/action.yaml)
  - [deploy-do](./.github/common/deploy-do/action.yaml)
  - [push-ecr](./.github/common/push-ecr/action.yaml)
  - [setup-ssh](./.github/common/setup-ssh/action.yaml)

- [node](./.github/node)
  - [build-image](./.github/node/build-image/action.yaml)
  - [run-test](./.github/node/run-test/action.yaml)
