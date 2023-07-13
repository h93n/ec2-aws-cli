
# EC2 AWS CLI

This repository contains a set of Bash scripts that interact with the AWS Command Line Interface (CLI) to manage EC2 instances and resources.

## Prerequisites

- AWS CLI installed and configured with appropriate access credentials. You can install the AWS CLI by following the instructions in the [AWS CLI User Guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html).

## Usage

1. Clone the repository:

   ```shell
   git clone https://github.com/h93n/ec2-aws-cli.git
   ```

2. Change into the repository directory:

   ```shell
   cd ec2-aws-cli
   ```

3. Make the scripts executable:

   ```shell
   chmod +x *.sh
   ```

4. Edit the scripts and modify the variables as needed. For example, you might want to update the default instance type, security group, or region.

5. Run the scripts using the Bash shell. For example, to launch an EC2 instance:

   ```shell
   ./launch_ec2.sh
   ```

   You can explore other available scripts in the repository for different actions such as stopping instances, creating EBS volumes, and terminating instances.

6. Follow the prompts and provide any required inputs to complete the actions. Make sure to review the scripts and understand the changes they will make to your AWS environment before executing them.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Please ensure that your code changes adhere to the existing coding style and conventions.

## License

This project is licensed under the [MIT License](LICENSE).

## Disclaimer

Please note that the scripts provided in this repository are for demonstration purposes and should be used with caution. Ensure that you have a good understanding of the AWS services and the impact of the actions performed by these scripts. The authors of this repository are not responsible for any misuse or damages caused by using the provided scripts.
```

Feel free to modify and customize the README file to provide more specific details about your project, its usage, and any additional instructions or guidelines for contributors.
