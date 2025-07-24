# terraform-vpc-may

```hcl

module "may" {
  source  = "IsmayilJabrayilov/may/vpc"
  version = "1.0.0"
  
  vpc_cidr = "172.33.0.0/16"
  subnet_cidr = "172.33.1.0/24"
  subnet2_cidr = "172.33.2.0/24"
  subnet3_cidr = "172.33.3.0/24"
}
```