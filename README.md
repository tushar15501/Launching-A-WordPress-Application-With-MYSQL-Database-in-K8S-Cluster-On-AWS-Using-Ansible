# Launching-A-WordPress-Application-With-MYSQL-Database-in-K8S-Cluster-On-AWS-Using-Ansible
What is Wordpress ?
WordPress is the simplest, most popular way to create your own website or blog.
In fact, WordPress powers over 40.0% of all the websites on the Internet. Yes more than one in four websites that you visit are likely powered by WordPress.
Wordpress is a CMS (content management system)
A content management system is basically a tool that makes it easy to manage important aspects of your website like content without needing to know anything about programming.
For example, not only does WordPress power a huge number of business sites and blogs, it’s also the most popular way to create an eCommerce store as well! With WordPress, you can create:
Business websites
eCommerce stores
Blogs
Portfolios
Resumes
Forums
Social networks
Membership sites
What is MySQL ?

MySQL is the most popular Open Source Relational SQL Database Management System. MySQL is one of the best RDBMS being used for developing various web-based software applications
MySQL is used by many database-driven web applications, including Drupal, Joomla, phpBB, and WordPress.
What is AWS Cloud ?

what is aws
Amazon Web Services (AWS) is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.
These cloud computing web services provide a variety of basic abstract technical infrastructure and distributed computing building blocks and tools.
One of these services is Amazon Elastic Compute Cloud (EC2), which allows users to have at their disposal a virtual cluster of computers, available all the time, through the Internet.
AWS’s version of virtual computers emulates most of the attributes of a real computer, including hardware:
central processing units (CPUs)
graphics processing units (GPUs) for processing
local/RAM memory
hard-disk/SSD storage
a choice of operating systems
networking
pre-loaded application software such as web servers, databases, and customer relationship management (CRM).
What is Ansible ?

Ansible is an open-source automation tool, or platform, used for IT tasks such as configuration management, application deployment, intraservice orchestration, and provisioning.
Benefits of Using Ansible
Free: Ansible is an open-source tool.
Very simple to set up and use: No special coding skills are necessary to use Ansible’s playbooks (more on playbooks later).
Powerful: Ansible lets you model even highly complex IT workflows.
Flexible: You can orchestrate the entire application environment no matter where it’s deployed. You can also customize it based on your needs.
Agentless: You don’t need to install any other software or firewall ports on the client systems you want to automate. You also don’t have to set up a separate management structure.
Efficient: Because you don’t need to install any extra software, there’s more room for application resources on your server
Prerequisite
Your Preferred Choice of OS (I am using Redhat 8)
Ansible Installed
AWS account
Steps to Follow:
🔅 Launch ec2-instances on AWS Cloud eg. for master and slave.
🔅 Create roles that will configure master node and slave node separately.
🔅 Launch a wordpress and mysql database connected to it in the respective slaves.
🔅 Expose the wordpress pod and client able hit the wordpress ip with its respective port.
