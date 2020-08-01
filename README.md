<h2>UMBC Tuition Remission Verification System</h2>
<h3>Nardos Asfawe</h3>
<h3>Problem Summary</h3>

<p>Graduate students awarded Assistantships can receive tuition benefits such as having their tuition waived when they take a course at UMBC. When a student is appointed to a Graduate Assistantship, they must sign forms using DocuSign. The primary scope of this capstone project is focused on the Tuition Remission form, associated workflow and electronic signature capture.
The current process for verifying the Tuition Remission DocuSign form is very time consuming for the Graduate School. Each semester, Financial Services audits the Graduate School to ensure that all the students receiving tuition benefits have signed the required documents. Currently, the Graduate School manually requests a report from PeopleSoft that lists all of the students who have a Graduate Assistantship. The Graduate School Supervisor must then look up each student’s individual DocuSign form to verify their signature. Accordingly, the DocuSign team wants the process automated for the UMBC Graduate School.</p>

<h3>Solution</h3>

<p>We propose that REX can improve workflow utilization and verify all forms automatically. First, the Graduate School Supervisor is provided with a goURL, a URL generated by the DocuSign team that contains a number associated with the assigned DocuSign form. Second, the Supervisor then inputs the date range for the requested week. Afterwards, a PeopleSoft query search is initiated and to gather all student data which needs to be verified within a specified date range. REX then executes a report based upon selection criteria for all DocuSign forms, automatically verifying that students from the PeopleSoft query have submitted the mandatory forms. REX then compiles students from the PeopleSoft report to search for their matching Tuition Remission DocuSign from. Finally, the supervisor digitally signs and submits the Verification Form. Once completed, the DocuSign form, PeopleSoft report, and REX report will convert to a PDF file and get stored in BOX, a cloud-based file sharing service. In conclusion, it is anticipated that this system will save the Graduate School a lot of time and effort, is less prone to human error, and enhances workflow integration in the auditing process.</p>
<p>The Process Modeling Document below illustrates the system’s data flow. </p>

<h4> Context Diagram: </h4>
<p> Introduction: This section outlines the Context Diagram. This diagram is a top-level Data Flow Diagram (DFD) which will show the entirety of the Tuition Remission Verification System as a single process.</p>

![](https://github.com/NardosMe/Auditing-System-/blob/master/context_diagram.png?raw=true)

<h4>Level 0 Diagram </h4>
 
<p> Introduction: This section outlines the Level 0 Diagram. This diagram is derived from the Context Diagram and is intended to explode the DFD into smaller, more detailed sub-processes.</p>

![](https://github.com/NardosMe/Auditing-System-/blob/master/level_0_diagram.png?raw=true)

<h4>Level 1 Child Diagrams </h4>
<p>Introduction: This section outlines the Level 1 Child Diagrams. These diagrams are derived from the processes of the Level 0 DFD to further detail the inputs and outputs of data from each of the sub-processes. Below are the Child diagrams for each of the 5 Level 0 processes.
 </p>
<h5>Process 1: Create Docusign Profile </h5>

![](https://github.com/NardosMe/Auditing-System-/blob/master/process_1_diagram.png?raw=true)

<h5>Process 2: Generate Weekly Report</h5>

![](https://github.com/NardosMe/Auditing-System-/blob/master/process_2_diagram.png?raw=true)

<h5>Process 3: Archive Completed Document</h5>

![](https://github.com/NardosMe/Auditing-System-/blob/master/process_3_diagram.png?raw=true)

<h5> Process 4: Generate Departmental Report</h5>

![](https://github.com/NardosMe/Auditing-System-/blob/master/process_4_diagram.png?raw=true)

<h5> Process 5: Submit Quarterly Report</h5>

![](https://github.com/NardosMe/Auditing-System-/blob/master/process_5_diagram.png?raw=true)

<h4>Data Dictionary Definitions </h4> 

![](https://github.com/NardosMe/Auditing-System-/blob/master/Data_Dictionary.png?raw=true)

