# xerris-control-tower

Xerris has put together the series of steps required to deploy the control tower in AWS. There are multiple moving parts hence we cannot automate the entire deployment process.
The benefits of deploying the control tower are : https://aws.amazon.com/controltower/features/

![image](https://user-images.githubusercontent.com/89942074/146816766-726f0dfc-1dd4-4c5b-80e5-91617c9221e6.png)

There are 2 main steps when you plan to deploy control tower :
1. To deploy the core control tower which will give you the landing zone alongwith the audit and logging accounts enabled. (This document will help to achieve this)
2. To create accounts in the control tower accross environments (This is automated, follow https://github.com/xerris/xerris-terraform-control-tower-aft)

## Xerris Control Tower Setup Guide   >  https://bit.ly/3GWr1NG

**Usage:**

1. This document was developed by Xerris and hosted on Google Drive
2. You are free to add comments if you would like to contribute. Our team will review and ammend the changes.
3. You are free to download the document for your your usage
4. Once you are through with your step by step deployment, you can visit https://github.com/xerris/xerris-terraform-control-tower-aft for the next steps


