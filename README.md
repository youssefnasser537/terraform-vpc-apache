# Terraform AWS VPC + EC2 + Apache

This project provisions a simple AWS infrastructure using **Terraform**, including:

- A custom **VPC** with CIDR block `10.0.0.0/16`
- A **Public Subnet** (`10.0.0.0/24`)
- An **Internet Gateway** with proper routing
- A **Security Group** allowing inbound SSH (22) and HTTP (80)
- An **EC2 instance** running **Apache HTTP server**


---

## 🧰 Technologies Used

- Terraform
- AWS: EC2, VPC, Subnet, Route Table, Security Group, Internet Gateway
- Apache Web Server

---

<pre> ## 📐 Architecture Diagram ``` Internet │ ▼ [Internet Gateway] │ ▼ [Route Table] │ ▼ [Public Subnet] ───────► [Security Group: ports 22, 80] │ ▼ [EC2 Instance with Apache] ``` </pre>


