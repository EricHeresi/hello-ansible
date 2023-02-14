# hello-ansible
ansible.cfg - config to skip host checking with SSH and use aws plugin
aws_ec2.yml - used as aws inventory

ec2-launch.yml - creates a single aws instance and installs httpd
vue2048aws.yml - deploys vue2048 on all hosts with tag:APP: vue2048, apache required

ec2-launch2.yml - creates an aws isntance and deploys vue2048 in the same step

ec2.yml - single script to deploy apache and vue2048 on a remote AWS instance defined by inventory
inventory - old hardcoded aws instance, IP address needed to be modified in order to work

ping.yml - ping on all hosts
