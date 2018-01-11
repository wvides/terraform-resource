# AWS instance resource


## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| ami | The ami to create the web server | string | `ami-40d28157` | no |
| instance_type | The instance type or size | string | `t2.micro` | no |
| tag | A tag for the instance, could be empty | string | `` | no |

## Outputs

| Name | Description |
|------|-------------|
| aws instance public ip | Aws instance public IP |

