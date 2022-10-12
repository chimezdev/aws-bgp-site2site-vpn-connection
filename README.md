# IMPLEMENTATION OF A DYNAMIC, HIGHLY AVAILABLE, ACCELERATED AWS BGP SITE-TO-SITE VPN CONNECTION

## SCENARIO
Your company headquarter has just migrated fully to AWS cloud and wants one of its branch offices that still operates a private remote cloud to be able to access the head-office resources in AWS Virtual Private Cloud, VPC and vice versa. This has to be done through a secured connection over the internet already in use by the branch office and also allow for exchange of routing information using Border Gateway Protocol, BGP. One of the ways to achieve this is to establish an AWS Site-To-Site VPN connection.

- In this advanced demo, I implemented a dynamic, highly available, accelerated VPN connection that uses BGP to share route information with other Autonomous Systems following the original work by Adrian Cantrill

## Prerequisites

Good understanding of CloudFormation template and Stack creation. AWS VPC, Subnets and EC2 Instances. Ability to navigate through the AWS Management Console easily. Fundamental knowledge of Linux and Linux commands

# Visit my medium post for a step-by-step guild on how you can replicate this project: [Guidelines](https://medium.com/@ochuba/mplimentation-of-a-dynamic-highly-available-accelerated-aws-bgp-site-to-site-vpn-connection-b3d18596be99)
