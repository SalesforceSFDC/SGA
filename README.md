# SGA

### Description

I have some more feedback on this thing…
So the conflict checker is using native Salesforce functionality – it’s essentially a workflow. If there are company matches it will pull in the account owner’s email address and it also emails a couple email distribution lists.
Now the difference with SGA is it would have to connect to the SVC Salesforce instance to check for conflicts. The example my client gave is let’s say they wanted to work with Pepsi, they would use the conflict checker to see if SVC was already working with competitors. The user would have to enter competitor names (i.e. Coca Cola) and the api you create would check if the company exists in the SVC Salesforce instance. If Coca Cola WAS in the instance, the conflict notification email would pull the in the account owner of Coca Cola and the email distribution lists.
Basically, outside of the API lookup, it’s all out of the box functionality.
