# http-cfn

Version 1 - > AWS Cloud formation template to deploy;
•	1 x ELB
•	1 x EC2 (httpd & index.html configured via cfn-init bootstrap)
•	1 x Security Group
How to deploy;
1.	Login to AWS
2.	Change region to Oregon
3.	Services > CloudFormation
4.	Create Stack 
5.	Select “Upload a template to Amazon S3”
6.	Browse to the file http-cfn.json
7.	Click create 
8.	Choose Key Pair (you may need to create one)
9.	Await stack to complete
10.	The ELB DNS record will be listed under Outputs
