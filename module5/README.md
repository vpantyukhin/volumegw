### Workshop Title

© 2020 Amazon Web Services, Inc. and its affiliates. All rights reserved.
This sample code is made available under the MIT-0 license. See the LICENSE file.

Errors or corrections? Contact [ttasker@amazon.co.uk](mailto:wttasker@amazon.co.uk).

---

# Module 5
## Workshop clean-up

To make sure all resources are deleted after this workshop scenario, execute the steps in the order outlined below (you do not need to wait for CloudFormation to finish deleting before moving to the next step):

1.	From the AWS console, click **Services** and select **Storage Gateway**.

2.	Select **Gateways** on the left panel and highlight the gateway on the right.
3.	Click **Actions** and **Delete Gateway**.
4.	Click **Confirm** and then **Delete**.
5.	From the AWS console, click **Services** and select **EC2**.
6.	Select **Instances** on the left panel and highlight the storage gateway on the right.
7.	Click **Actions** and **Instance State -> Terminate**.
8.	Highlight the **EC2 Initiator Instance** on the right.
8.  Click **Actions** and **Instance State -> Terminate**.
9.	Click **Confirm** and then **Delete**.
10.	From the **AWS console**, click **Services** and select **CloudFormation**.
11.	Select **Volume Storage Gateway Workshop stack**.
12.	Click **Delete**.
13.	Click **Delete Stack**.
14.	It will take a few minutes for the CloudFormation service to delete the stack. Click on the stack name and **refresh the page** to see an updated status. The Volume Storage Gateway Workshop stack will be removed from the list if everything has been deleted correctly.
15. From the AWS console, click **Services** and select **EC2**.
16. Click **Volumes** on the left.
17. Find and select the **Snapshot volume**.
18. Click **Actions -> Delete Volume**, and then click **Yes, Delete**.  
19. Click **Snapshots** on the left.
20. Find and select the **Volume Storage Gateway snapshot**.
21. Click **Actions -> Delete**, and then click **Yes, Delete**.


To make sure that all CloudFormation templates have been deleted correctly, confirm that any EC2 instances created in this workshop are in the **terminated** state.
