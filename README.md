# sharepoint-commands

Connect SharePoint Online Management Shell
<br/>
Connect-SPOService https://contoso-admin.sharepoint.com

<br/>
<br/>
<br/>

Create Site Collection App Catalog 
<br/>
Add-PnPSiteCollectionAppCatalog -Site https://Contoso.sharepoint.com/sites/contoso

<br/>
<br/>
<br/>
Allow Custom Script on SharePoint Site Collection level
Set-SPOsite https://Contoso.sharepoint.com/sites/contoso -DenyAddAndCustomizePages 0
