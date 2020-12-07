# Custom Salesforce Task Manager for Campaign Members
A Datatable in Salesforce using Aura and Apex to create a custom Task Manger component for the 'Campaign Member' Object

<h2><b>Introduction</h2></b>

<p align="justify"> Salesforce 'Campaign Member' Object dont allow records to be related to 'Tasks' or 'Events', threfore I created a solution with a custom object called 'MemberTasks__c' and a datatable, to provide a Task Manager module for each 'Campaign Member', wehre you can view, edit and add tasks.</p>

<h2><b>MemberTasks__c Details and Attributes</h2></b>

<p align="justify">Following I shared the details of the custom object I created:</p>
<ul>
  <li>API Name: 'MemberTask__c'</li>
  <li><table>
  <tr>
    <th>FIELD LABEL</th>
    <th>FIELD NAME</th>
    <th>DATA TYPE</th>
  </tr>
  <tr>
    <td>Asignee</td>
    <td>asignee_user__c</td>
    <td>Formula (Text)</td>
  </tr>
  <tr>
    <td>Asignee Name</td>
    <td>Asignee_Name__c</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Campaign</td>
    <td>Investment_Campaign__c</td>
    <td>Lookup(Campaign)	</td>
  </tr>
  <tr>
    <td>Contact</td>
    <td>Contact__c</td>
    <td>Lookup(Contact)	</td>
  </tr>
  <tr>
    <td>Create by Name</td>
    <td>Create_by_Name__c</td>
    <td>Formula (Text)</td>
  </tr>
  <tr>
    <td>Created By</td>
    <td>CreatedById</td>
    <td>Lookup(User)</td>
  </tr>
   <tr>
    <td>Due Date</td>
    <td>Due_Date__c</td>
    <td>Date</td>
  </tr>
   <tr>
    <td>MemberTask Name</td>
    <td>Name</td>
    <td>Auto Number</td>
  </tr>
   <tr>
    <td>Status Checkbox</td>
    <td>status_checkbox__c</td>
    <td>Checkbox</td>
  </tr>
   <tr>
    <td>ask name</td>
    <td>Task_name__c</td>
    <td>Text Area(255)</td>
  </tr>
  <tr>
    <td>Task status</td>
    <td>Task_status__c</td>
    <td>Picklist</td>
  </tr>
</table>
</ui>

<h2><b>Component Preview</h2></b>

<a href="https://ibb.co/djn27gC"><img src="https://i.ibb.co/jb7MHR0/Lightning-Experience-Salesforce.gif" alt="Lightning-Experience-Salesforce" border="0"></a>


