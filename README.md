<h1>Microsoft Azure Management Groups – How To Assign And Review A Built-In Azure Role</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
In this project, Microsoft Azure Management Groups and role-based access control are used to organize subscriptions and manage access at scale within an Azure tenant.  You will review and assign a built-in Azure role at the management group scope to control permissions for managing Azure resources using predefined role definitions. You will access the Azure portal, navigate to Management Groups, select the target management group, and open the Access control (IAM) blade to review available roles. You will add a role assignment by selecting the Virtual Machine Contributor role, choosing the appropriate user or group as the security principal, and completing the assignment through the review and assign workflow. The selected user or group is granted the predefined permissions associated with the assigned built-in role at the management group scope. This configuration enforces role-based access control and ensures that access to Azure resources is limited to the permissions required for the assigned responsibilities.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Microsoft Azure, Management groups</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 11 & Windows Server 2025</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: RBAC = Role-Based Access Control.</b></span>  
<br/><br/><br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Microsoft Azure from https://portal.azure.com</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/pzBylF7.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Search bar (very top-middle).  Search for: Management groups.  Click: The top result: Management groups.</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/QWcVVfL.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/2tI9vvZ.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/Xpe0fvZ.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>On the Management groups webpage, Click: The management group you want to assign a role (ex: az104-mg1).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/NHuVJq3.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/3ns8G4I.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/qQvXP4R.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/bVd651b.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Access control (IAM) blade (far-left, towards bottom).</b></span>  
<br/><br/>

</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: IAM – Identity and Access Management = Defend against malicious login attempts and safeguard credentials with risk-based access controls, identity protection tools, and strong authentication options—without disrupting productivity.</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/LZ7yvkM.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/4M9oLC7.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/9gWygUr.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/1aNCaja.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Roles tab (middle, next to Role assignments and Deny assignments).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/3op03LB.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/Kbor6lO.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/TnLNZiP.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/hUJeP0v.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: +Add tab (top-middle, next to Download role assignments).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/GJYKV5Q.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/rw2lhnG.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/iSJScqi.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/zOY1vWl.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Add role assignment (under +Add, dropdown option).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/u2cDOTM.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/8WV5K84.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Search: Virtual Machine Contributor (in search box: under Job function roles, left-middle, says: Search by role name description, permission, or ID).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/u74qeop.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/CnNCZt4.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/WrG9PKu.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/FUEf3wF.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In the search results, Click: Virtual Machine Contributor row (not View – far right of the row).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/n3OaDyX.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Next (bottom-left, next to Previous).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/X0f4SNO.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/rX2OiER.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/MyNlByS.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>You will now be on the Add role assignment webpage, by default you will be on the Members tab. Click: +Select members.</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0HLneRr.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/xU85ieK.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/ftvJHw1.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In the Select members box, Search and Click: The group or members you want to add (ex: Help Desk).  The group(s) and/or user(s) you select will show in the Selected members area (above Select and Close).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/qRC0mb2.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/FHt6anF.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/yyyZUvX.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/acmMix9.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/bTG0ipn.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Select (bottom-left of Select members box, to the left of Close). You will now see the group(s) and/or user(s) added to the Members section of the Add role assignments webpage.</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/UHWGOxv.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/aGHpd6R.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/ehjESQm.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Next (bottom-left, next to Previous).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/yi1VgW3.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/osAHdQq.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>On the Conditions tab, Click: Next (bottom-left, next to Previous).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/EOkAqhf.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/oJJA701.png" height="50%" width="50%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/9nDuc33.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>On the Review + assign tab, review the information.  Click: Review + assign (bottom-left, next to Previous).</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/6QWTxzs.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/A1St7HB.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


</div>
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: You may be redirected back to the Microsoft Azure homepage. If so, you can go back to: Management groups, the group you just edited, Access control (IAM) blade, Role assignments tab.</b></span>  
<br/><br/>

<table>
  <tr>
    <td><img src="https://imgur.com/SQThWnJ.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/TkRQprD.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/RFsKh50.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


