VPC: marshal-sec-labs-vpc (10.0.0.0/16)
├── Public Subnet: marshal-public-subnet1 (10.0.1.0/24) → IGW → EC2
└── Private Subnet: marshal-private-subnet1 (10.0.2.0/24) → isolated
Internet Gateway: marshal-igw
Route Table: marshal-public-rt (0.0.0.0/0 → IGW)
