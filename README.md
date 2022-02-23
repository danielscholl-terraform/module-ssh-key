# A simple helper module for the creation of an SSH Key

Module for creating a private SSH Key

## Usage

```
module "ssh-key" {
  source = "git::https://github.com/danielscholl-terraform/ssh-key?ref=v1.0.0"
}

```


<!--- BEGIN_TF_DOCS --->
## Providers

| Name | Version |
|------|---------|
| local | n/a |
| tls | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:-----:|
| public\_ssh\_key | An ssh key set in the main variables of another module | `string` | `""` | no |

## Outputs

| Name | Description |
|------|-------------|
| private\_ssh\_key | n/a |
| public\_ssh\_key | n/a |
<!--- END_TF_DOCS --->
