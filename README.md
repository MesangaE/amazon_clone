<h1>amazon_clone</h1>

![image](https://github.com/user-attachments/assets/ae121445-b862-4c10-a109-81e1e6367603)

Today we will deploy the Amazon app in AWS ec2 using Terraform as an infrastructure-building tool. Then we automate the whole process using Jenkins which allows us continuous integration and continuous deployment (ci-cd) and then we set up Prometheus and Grafana for monitoring. To start this project, I decided to first clone the repo into my local and do modifications on the Terraform files (region, ami, I created a new keypair as well so I added that resource to the resource block)

