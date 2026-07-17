Fields in Salesforce:
Salesforce provides two types of Salesforce:
                              1) Standard fields- Automatically created by salesforce
                              2) Custom fields- If we require more fields then we have to create those as custom fields

How to create Fields:
                  - Move to Object manager---> As we created custom Object "Property"(so i am going to create fields for that object)
                            |
                        Create on New Button (It will show all the data types as per the requirement you can select which type of field you want to create. I want                                                to  create a field to store name of Property  so i am selecting text)
                            |
  Step2:                click next--> Fill the details required
                                                 |
                                        Field Label: Property Name
                                        Length: 255 (Please enter the max length for the txt field below)
                                        Field Name: Property_Name
                                        Description: Stores names of the property
                                        Help Text: Please enter the property name
                        And we have certain options like required unique external ID & default value, so if you want to fill these information you can fill otherwise                         you can simply click on next
                  
  Step3:                                            |
                                   Establish field-level security:
                          So if you want to restrict this field should not be available for a particular profile user so accordingly you can enable or disable                               these checkboxes.
                          Field Level security for profile:                       Visible                     ReadOnly

                          * So if you enable this visible checkbox for all the profiles or for a Particular profile,then this will be available for both reading                               and editing
                                                  |
                                              click next
                                              
