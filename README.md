# aws-encrypt-policies
The best way to force encryption in your AWS environment is to prevent resources from being created that aren't leveraging either encryption in transit or encryption at rest.

This repo is a collection of IAM policies that you can use to force encryption on various AWS services. The recommended deployment methodology is to combine them into one policy and use them as a service control policy in your organization.
