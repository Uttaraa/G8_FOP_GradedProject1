
# Uttara_FOP_Lab1
<H2>Credential Generation Application.</H2>
This is credential generation application for new hires in the company, implemented using concepts of foundations of java.
<br>
<br>
This application has separate <b>CredentialService</b> which have following methods:
<ul>
<br><li>generatePassword</li>
<br><li>generateEmailAddress</li>
<br><li>showCredentials </li>
</ul>
<H6>Technology</H6>
<b>Java</b>



# G8_FOP_GradedProject1
FOP-Graded Project1-Group 8 (IITR-FSD 2023 August Batch)
<H2>Departmental Updates</H2>
This assignment demonstrates a module for updates of departments in the company, implemented using basic concepts of foundations of java.
<br>
<br>

Module has three departments, which are as follows:
<ol>
<li><b>Admin Department</b></li>
<br><li><b>HR Department</b></li>
<br><li><b>Technical Department</b></li>
</ol>
  
This application has a <b>SuperDepartment</b> class which is extended by following classes:
<ul>
<li>AdminDepartment</li>
<br><li>HRDepartment</li>
<br><li>TechDepartment </li>
</ul>

<H4><ins>Additional Information</ins></H4>
<b>The following conditions are fulfilled as mentioned in assignment </b>
<ul>
<br><li>All three classes of department namely, AdminDepartment, HRDepartment and TechDepartment have return type <b>String</b>.</li>
<br><li>All three classes mentioned above do <b>not</b> accept any parameters.</li>
<br><li>Separate driver class <b>main</b> is used to create objects of HRDepartment, TechDepartment and AdminDepartment.</li>
<br><li>Each department displays all its functionalities.</li>
<br><li>Each department displays whether today is holiday or not with the help of the super Department.</li>
<br><li>SuperDepartment acts as a super class for all the departments.</li>
</ul>
<b>Additional informations of defined calsses of given documents are as follows: </b>
<br><br>
Admin department contains three methods:
<ol>
<li>departmentName</li>
  departmentName returns String "Admin Department"
<li>getTodaysWork</li>
   getTodaysWork returns String "Complete your documents Submission"
<li>getWorkDeadline</li>
   getWorkDeadline returns String "Complete by EOD"
</ol>
Hr department contains four methods:
<ol>
<li>departmentName</li>
  departmentName returns String "HR Department"
<li>getTodaysWork</li>
  getTodaysWork returns String "Fill today’s timesheet and mark your attendance"
<li>getWorkDeadline</li>
  getWorkDeadline returns String "Complete by EOD"
<li>doActivity</li> 
  doActivity returns String “team Lunch”
</ol>
Tech department contains four methods:
<ol>
<li>departmentName</li>
  departmentName returns String "Tech Department"
<li>getTodaysWork</li>
  getTodaysWork returns String "Complete coding of module 1"
<li>getWorkDeadline</li>
  getWorkDeadline returns String "Complete by EOD"
<li>getTechStackInformation</li> 
  getTechStackInformation returns String “core Java”
</ol>

<H6><ins>Technology</ins></H6>
<b>Java</b>
