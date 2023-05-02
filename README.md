Download Link: https://assignmentchef.com/product/solved-cmpt355-assignment-2
<br>
<strong>Description </strong>

This assignment will get you to design and implement an employee database from a set of requirements. The first thing you should do to get started is to model all your entities and relationships. Then you can use this information to draw a full ER diagram. After this, writing the required DDL statements should be fairly straightforward.




** Please be aware that this assignment is the basis for all future assignments, so do your best to capture all the requirements below. **




The main entities and relationship of the design are described in the scenario below, but other supporting entities/relationships are only implied. There may be useful attributes that aren’t mentioned that you could add if you see fit.




Depending on how you structure your database you should end up with around 8-10 main tables, plus any reference/lookup tables that you deem appropriate.







<strong>Scenario </strong>

You were hired to design and implement a database for the company Great Canadian National Bank. They have hundreds of employees spread across several locations and need to keep track of these employees and their organizational information.




There is information stored for every employee, including the employee’s name, gender, SSN, addresses, and phone numbers. Assume that an employee could have multiple addresses (either Home or Business) and phone numbers (either Home, Cell, or Business) stored in the system. They also want to keep track of the hire/termination/rehire dates for the employee.




As mentioned previously, the company has several locations, and each location can have several departments. However, each location has their own distinct departments; for example, the Saskatoon location will have its own IT department. The Calgary location will have an IT department as well, but the two are not affiliated.  Each location has name, a code, and a single address. Each department also has a name and a code, as well as a field for which job is the top position (management) for that department.




There are many different jobs in the company (e.g. Teller I, IT Manager, Loans Officer, HR Generalist). For our purposes, assume that an employee can only have one job at a time. Each job has a name, a job code, an effective date and expiry date. There is also a reference to the job that this job reports to. Each job is associated with a department. Additionally, there is a pay frequency attribute associated with each job (e.g. weekly, biweekly, monthly). There are also pay types associated with each job (e.g. hourly, salaried).




Each employee has a job. All jobs will be paid using the same pay frequency and type but employees in the same job can be paid different salaries. For example, all jobs with the name ‘Teller II’, will be paid salaried and biweekly. However, two employees both in the ‘Teller II’ job could be paid different salaries/rates.

<strong> </strong>

<strong>What you need to hand in</strong>

<ol>

 <li>A script (.sql file) containing all your DDL statements required to create your database.</li>

 <li>Your finalized ER diagram, using the techniques we learned in class. Make sure to include:

  <ol>

   <li>the multiplicity of each relationship</li>

   <li>the primary keys of each entity type</li>

   <li>all attributes for each entity type</li>

   <li>the final model as you used to create the database (i.e. any multi-valued attributes should be shown the way you modeled them in your DDL statements)</li>

  </ol></li>

</ol>

*Remember that your database must match all the DDL statements in your script.







<strong>Marking </strong>

<ol>

 <li>DDL statements <strong>/30</strong></li>

 <li>Database Design / ER Diagram <strong>/60</strong></li>

 <li>Style <strong>/10</strong></li>

</ol>


