<<<<<<< HEAD
<h1>amazon_clone</h1>

![image](https://github.com/user-attachments/assets/ae121445-b862-4c10-a109-81e1e6367603)

Today we will deploy the Amazon app in AWS ec2 using Terraform as an infrastructure-building tool. Then we automate the whole process using Jenkins which allows us continuous integration and continuous deployment (ci-cd) and then we set up Prometheus and Grafana for monitoring. To start this project, I decided to first clone the repo into my local and do modifications on the Terraform files (region, ami, I created a new keypair as well so I added that resource to the resource block)

=======
Deployment of Amazon clone app using Terraform and jenkins ci-cd

Pre-requisite
aws account
basics of terraform and jenkins

Let's do it
before do anything →
open your terminal and make a separate folder for amazon →mkdir amazon
cd amazon
clone the github repo
git clone https://github.com/Aakibgithuber/Amazon-app-Deployment-using-terraform-and-jenkins.git

Completion steps →
Step 1 → Setup Terraform and configure aws on your local machine
Step 2 → Building a simple Infrastructure from code using terraform
Step 3 → Setup Sonarqube and jenkins
Step 4 → ci-cd pipeline
Step5 → Monitering via Prmotheus and grafana
Step 6 → Terraform Destroy

My blog link for this project-->https://aakibkhan1.medium.com/project-7-deployment-of-amazon-clone-app-using-terraform-and-jenkins-ci-cd-32483787ea67
                
>>>>>>> master
