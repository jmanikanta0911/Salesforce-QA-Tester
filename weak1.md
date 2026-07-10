# Salesforce-QA-Tester
APP URL: developer.salesforce.com

Salesforce Admin Concepts:
What is Salesforce?
A) Worlds leading cloud-based customer Relatonshp Management (CRM) platforms
   Salesforce is the most popular cloud platform on the internet

How Salesforce helps businesses?
A) Store and Manage Customer data
   Track sales leads and opportunities
   Automate workflows and processes
   Improve customer support
   Run Marketing campaigns

Tabs,Objects,Records and Fields

Tabs: Home,Opportunities,Leads,tasks etc--> These all are tabs (These are basically created for objects)
-In salesforce whatever data we store, those are stored in objects.
-To navigate around objects we need to create tabs

Lets go to Opportunities Tab:
Opportunities is a Tab which is associated with an object.
Firstly click on the opportunities Tab---> we can see the object which contains records
--> How to create a record??
- click on opportunities tab
- click on New
- Give the required fields
- click on Save ----> record created

In Salesforce we have two types of Objects:
1) Standard Objects-- These objects are Pre-installed by Salesforce no need to create them.
2) Custom Objects-- If the object has two underscores (_ _) than it is called custom object
----> To uniquely identify the each object we have API names

Custom Objects And Apps:
In salesforce object is basically a data table.
The data stored in table called as records.
Object is basically used to store different records in Salesforce.
Field name will be available automatically whenever you will be creating custom object.

--> Creating A Custom Object 
To create an Object:
1: Go to Setup---> click on Object Manager---> click on create---> custom object
2: And fill the required fields
To Create the Custom Object:
Go to Object Manager ---> click on create ---> custom Object(click)
1) Label - Property
2) Plural Labl - Properties (This plural label will be known as tab label)
3) Object name - Property (It is API )
4) Description - This is custom object
--> whenever you will be creating the customm object..one field is automatically created.
   Field is nothing but a which can stores the information.
   Object is nothing but an tabe which contains group of records.
5) Recoord Name- Property Name --> This field will be available automatically whenever you eill be creating the custom object.
                     |
              It has two data types: 1) Text - Text value as Property Name
                                     2) Auto number - This auto number will be created automatically whenever you will be creating a record for proprty object.
   When you are selecting the Auto number you need to decide two things one is Display Format and Starting Number.
6) Display Format - P-{0000}
7) Starting Number - 01
-> so this way i provided all required information to create the object.
   There are some optional features available so that you can enable as per your requirements.
   1) Optional Features:
      . Allow Reports
      . Allow Activities
      . Track Field History
      . Allow in chatter groups
   2) Object classification
      . Allow sharing
      . Allow Bulk API Access
      . Allow stream API access
   3) Deployment status
      . In Development
      . Deployed (select this)
   4) Search Status
      . Allow search
   5) Objct creation Options
      . Add notes and Attachment related list to default page layout
      . Launch New custom tab wizard ---> save ( you can see custom object is created and here we need to crate its tab)
 Creating its Tab:
 Step1: Enter the details
 Object: Property
 Tab Style: Box --> Any tab style ---> click nxt
 Step2: Add to Profiles
 . Apply one tab visibility to all profiles(select this)
 . Apply a diff tab visibility for each profile
** Profile basically decides which user can access this particular tab
Step3: Add to custom Apps
Now it is asking on which app you want to place this tab so, in sales application we can see various tabs are available. so if you want to place this tab on sales application so you need to enable that checkbox and you can disable other checkboxes.

    
   






