# SGA

### Description

Once a conflict check is submitted, an email is sent via workflow (see second image).  The other action that happens is the SVC opportunities would be pinged to see if there is a potential conflict with SGA working with that client.

I have some more feedback on this thing…
So the conflict checker is using native Salesforce functionality – it’s essentially a workflow. If there are company matches it will pull in the account owner’s email address and it also emails a couple email distribution lists.
Now the difference with SGA is it would have to connect to the SVC Salesforce instance to check for conflicts. The example my client gave is let’s say they wanted to work with Pepsi, they would use the conflict checker to see if SVC was already working with competitors. The user would have to enter competitor names (i.e. Coca Cola) and the api you create would check if the company exists in the SVC Salesforce instance. If Coca Cola WAS in the instance, the conflict notification email would pull the in the account owner of Coca Cola and the email distribution lists.
Basically, outside of the API lookup, it’s all out of the box functionality.

Here are the answers to your questions. Note – SGA is the subsidiary, SVC is Sard Verbinnen. We will only be working on the SGA instance.  However we will have access to the SVC org so you will basically be able to copy and paste things like workflows, fields, objects, etc. from one org to another.
If the SGA build goes well then we may take over the SVC build which will be better.
I will be sending more information shortly on their layout. I think you’ll see that we should be able to do this fairly efficiently.
 
- How many users?
               - 10 SGA (4 account staff, Myself, IT, Security, Admin, extras) 
               - 125 SVC (Growing to 150 by end of year) - This would be taken over after SGA implementation

- How many records are we importing and from which systems?
               - 0 

- Which telephony system? - This is more for SVC
               - They are on the following in offices
                   - NY - CIX 670
                   - SF,LA,CHI, TX - CIX100
               - IP Edge upgrade in 2017   
- Can we find out more about their objects, fields, sales processes?
               - Yes (Which objects, Fields, Process?)


### Quick Links

 * [Intro to Salesforce to Salesforce](https://developer.salesforce.com/page/An_Introduction_to_Salesforce_to_Salesforce)
