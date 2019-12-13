# sharepoint-commands

<b> Connect SharePoint Online Management Shell </b>
<br/>
Connect-SPOService https://contoso-admin.sharepoint.com

<br/>
<br/>

<b> Create Site Collection App Catalog </b>
<br/>
Add-PnPSiteCollectionAppCatalog -Site https://Contoso.sharepoint.com/sites/contoso

<br/>
<br/>

<b> Allow Custom Script on SharePoint Site Collection level </b>
<br/>
Set-SPOsite https://Contoso.sharepoint.com/sites/contoso -DenyAddAndCustomizePages 0
