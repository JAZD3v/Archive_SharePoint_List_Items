# Various Power Automate Flows

+ **Archive_SharePoint_List_Items:** A Power Automate Flow to archive SharePoint list Items/records by copying the items to an archive list then remove them from your main list.
+ **GetCurrentDate:** Work around for Calculated Columns in SharePoint List since they do not have a functionality to get the current Date/Time (Like a `Today()` or `Now()` function). This flow is configured to run everyday and updates a column called Today with the currnet date. 
+ **Email_When_Item_Added_To_List:** Sends out an email whenever a new item is added to a SharePoint list. The flow has some functions that makes the email "look" better (formats the Given Name to only capitalize the first letter in the name, and parses out the "FullPath" property so only the actual list name is shown for the subject line), and adds functionality the user can act on (Link to item created).
