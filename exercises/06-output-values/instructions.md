# Exercise 6

In this exercise, you will define an output value for the public ID address of an EC2 instance.

1. Inspect the existing configuration in the file named `main.tf`.
2. Create a new configuration file named `outputs.tf` that we'll use to define output values.
3. In the configuration file for output values, define an output for the public IP address of the `aws_instance` instance named `app_server`. Provide a description for the output value.
4. Execute the `terraform plan` command and find the output value in the console output.
5. Execute the `terraform output` command and find the definition in the console output. Would you expect the output to contain the value?