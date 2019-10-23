# serverless-terraform-variables-cwd



This is a fork of [serverless-terraform-varialbes](https://github.com/sbchapin/serverless-terraform-variables). For normal use refer to serverless-terraform-variables documentation.

In your serverless.yml file you can now add 'terraformCwd:' to the 'custom:' property to specify a different directory for you terraform files. This can be usefull for larger projects.

#### Example serverles.yml
```
custom:
  terraformCwd: /directory/where/you/have/your/terraform/files
```