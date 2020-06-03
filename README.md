# Terraform Key Pairs in AWS

## Examples

For examples how to use, please refer to the examples folder.

## Usage

```
module "keys" {

  source = "jason-morsley/keys/aws"

  name = "example"

  tags = {
    Terraform = "true"
  }

}
```