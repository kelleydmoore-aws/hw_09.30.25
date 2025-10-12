KDM-Weyland-Yutani Company Network Architecture

AWS Region:        us-east-1 (N. Virgina)  

VPC CIDR block
- IP Address:       10.50.0.0/16
- Subnet Mask:      255.255.0.0/16

Clients External Internet
- Public Subnet:    10.50.1.0/24  
- Subnet Mask:      255.255.255.0/24

Staff External Internet
- Public Subnet:    10.50.2.0/24
- Subnet Mask:      255.255.255.0/24

Executives External Internet
- Public Subnet:    10.50.3.0/24
- Subnet Mask:      255.255.255.0/24

Client Intranet
- Private Subnet:   10.50.11.0/24
- Subnet Mask:      255.255.255.0/24

Staff Intranet
- Private Subnet:   10.50.12.0/24 
- Subnet Mask:      255.255.255.0/24

Executives and C-Level's Intranet
- Private Subnet:   10.50.13.0/24 
- Subnet Mask:      255.255.255.0/24

Application server
- Private Subnet:   10.50.21.0/24 
- Subnet Mask:      255.255.255.0/24

Database server
- Private Subnet:   10.50.22.0/24 
- Subnet Mask:      255.255.255.0/24

Printer network
- Private Subnet:   10.50.23.0/24 
- Subnet Mask:      255.255.255.0/24

