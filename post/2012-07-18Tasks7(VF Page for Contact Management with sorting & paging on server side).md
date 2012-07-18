###-=Basic=-  
###To create a vf page with standard controller on Contact, extensions in your personal Org. Please be sure NOT in the custom org, questions? Please ask... This page should have dynamic title, sectionheader. On this page, there two modes.

###View: show the contacts in a table.

###Edit: the user can add or remove his Contacts in a table. And he can also update one or more Contacts at the same time. 

###Colunms of this table should be View(Link to the Contcat detail page, new window), FirstName, LastName, MailingCity, MailingCountry, Phone.

###-=Advanced=-  
###1. Use custom labels on the page (titles, buttons...)  
###2. Table sorting by clicking on column header only in View mode. Just use the character: ▲▼ to indicate the sort direction  
###3. Table paging...  
###4. Use field set to define the fields on contact to show on the page, If no field defined in the field set, then show error...    
###5. Use custom setting (Config) and URL-param to determine which field to be sorted on page load: 
###If no valid param then use value in custom setting
###Else If no valid value in custom setting then use first field defined in field set  
###6. In View mode, there will be a "+" icon in action colunm for every row. On clicking a page block section (collapsible=false) with detailed info of this records will appear unter this row. Use another field set to define the fields to be shown. The "+" icon would be switched in "-", on clicking the section disappears and return to original status.  
###7. Define a button to expand/close all these sections (JS).



