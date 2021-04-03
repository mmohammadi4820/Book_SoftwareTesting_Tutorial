# Book_SoftwareTesting_Tutorial(🔸Release March,2021)

---

## 〽️Introduction:
Software testing is an investigation conducted to provide stakeholders with information about the quality of the software product or service under test. Software testing can also provide an objective, independent view of the software to allow the business to appreciate and understand the risks of software implementation. Test techniques include the process of executing a program or application with the intent of finding failures, and verifying that the software product is fit for use.<br>
Software testing involves the execution of a software component or system component to evaluate one or more properties of interest. In general, these properties indicate the extent to which the component or system under test:<br>

- meets the requirements that guided its design and development,
- responds correctly to all kinds of inputs,
- performs its functions within an acceptable time,
- is sufficiently usable,
- can be installed and run in its intended environments
- achieves the general result its stakeholders desire

As the number of possible tests for even simple software components is practically infinite, all software testing uses some strategy to select tests that are feasible for the available time and resources. As a result, software testing typically (but not exclusively) attempts to execute a program or application with the intent of finding failures due to software faults. The job of testing is an iterative process as when one fault is fixed, it can illuminate other failures due to deeper faults, or can even create new ones.<br>
Software testing can provide objective, independent information about the quality of software and risk of its failure to users or sponsors.<br>
Software testing can be conducted as soon as executable software (even if partially complete) exists. The overall approach to software development often determines when and how testing is conducted. For example, in a phased process, most testing occurs after system requirements have been defined and then implemented in testable programs. In contrast, under an agile approach, requirements, programming, and testing are often done concurrently.<br>




| Front Book Cover  | Back Book Cover  |
|-----------|--------------------|
|<p><img src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Cover/Front_ST.jpeg"></p>|<p><img src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Cover/Back_ST.jpeg"></p>|
|  <b>Book Name</b>   |   SoftwareTesting Tutorial  |
| <b>Authors</b>    |   M.Mohammadi, M.H.Mohammadi, S.Y.Moradi|
| <b>language</b>    |  Persian   |
| <b>Printed in the</b>    |  IRAN   |
| <b>Publisher</b>    |   ...  |
| <b>First Printing Edition</b>    |   ...  |
| <b>Print Length</b>    |  ...   |
| <b>ISBN</b>    |  978-600-...-...-.   |

---

<div class="nav">

## Contents
* [Chapter 1](#chapter-1): <i>Software Testing</i>
* [Chapter 2](#chapter-2): <i>SDLC models</i>
* [Chapter 3](#chapter-3): <i>Types of Testing</i>
* [Chapter 4](#chapter-4): <i>Types of Manual</i>
* [Chapter 5](#chapter-5): <i>White Box Techniques</i>
* [Chapter 6](#chapter-6): <i>Black Box Techniques</i>
* [Chapter 7](#chapter-7): <i>Types of Black Box</i>
* [Chapter 8](#chapter-8): <i>Types of Functional</i>
* [Chapter 9](#chapter-9): <i>Types of Non-functional</i>
* [Chapter 10](#chapter-10): <i>Test case development</i>
* [Chapter 11](#chapter-11): <i>Testing Techniques</i>
* [Chapter 12](#chapter-12): <i>Test Management</i>
* [Chapter 13](#chapter-13): <i>Defect Tracking</i>
* [Chapter 14](#chapter-14): <i>Other types of Testing</i>
* [Chapter 15](#chapter-15): <i>Software Testing Tools</i><br>
* [Chapter 16](#chapter-16): <i>Differences</i>
* [Chapter 17](#chapter-17): <i>Software Testing MCQ</i>

🔸 [Authors](#authors)<br>
🔸 [Demo](#demo)<br>
🔸 [BookCollection](#bookcollection)<br>

</div>

<main>

<article id="chapter-1">

## Chapter 1
- ### Software Testing
Software testing is widely used technology because it is compulsory to test each and every software before deployment.<br>
Our Software testing tutorial includes all topics of Software testing such as Methods such as Black Box Testing, White Box Testing, Visual Box Testing and Gray Box Testing. Levels such as Unit Testing, Integration Testing, Regression Testing, Functional Testing. System Testing, Acceptance Testing, Alpha Testing, Beta Testing, Non-Functional testing, Security Testing, Portability Testing.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 1</b>  |   |   | 
|-----------|--------------------|-----------|
|1-1 Tutorial |1-3 Software Development Life Cycle |1-5 Types of Software Testing |
|1-2 Software Testing Principles |1-4 Software Testing Life Cycle | |


</article>

<article id="chapter-2">

## Chapter 2
- ### SDLC models
It is the first approach and the basic model used in software development. It is a simple model that is easy to use as well as understand. The execution happens in the sequence order, which means that the outcome of the one-stage is equal to the input of another stage. That's why it is also known as the Linear-sequential life cycle model.<br>
To avoid the overlapping issues of the multiple phases, every stage should be completed before moving to the next stage. Each stage of the waterfall model involves the deliverable of the previous stage, like requirements, are transferred to the design phase, design moved to development, and so on. When we have the Life critical (hospital application) and Machine critical (Military project), we will widely use the waterfall model.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 2</b>  |   |   | 
|-----------|--------------------|-----------|
|2-1 Waterfall model |2-3 Hybrid Model |2-5 V-model |
|2-2 Spiral Model  |2-4 Prototype Model | |


</article>

<article id="chapter-3">

## Chapter 3
- ### Types of Testing
Manual testing is a software testing process in which test cases are executed manually without using any automated tool. All test cases executed by the tester manually according to the end user's perspective. It ensures whether the application is working, as mentioned in the requirement document or not. Test cases are planned and implemented to complete almost 100 percent of the software application. Test case reports are also generated manually.<br>
Manual Testing is one of the most fundamental testing processes as it can find both visible and hidden defects of the software. The difference between expected output and output, given by the software, is defined as a defect. The developer fixed the defects and handed it to the tester for retesting.<br>
Manual testing is mandatory for every newly developed software before automated testing. This testing requires great efforts and time, but it gives the surety of bug-free software. Manual Testing requires knowledge of manual testing techniques but not of any automated testing tool.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 3</b>  |   |
|-----------|--------------------|
|3-1 Manual Testing |3-2 Automation Testing |


</article>

<article id="chapter-4">

## Chapter 4
- ### Types of Manual
The box testing approach of software testing consists of black box testing and white box testing. We are discussing here white box testing which also known as glass box is testing, structural testing, clear box testing, open box testing and transparent box testing. It tests internal coding and infrastructure of a software focus on checking of predefined inputs against expected and desired outputs. It is based on inner workings of an application and revolves around internal structure testing. In this type of testing programming skills are required to design test cases. The primary goal of white box testing is to focus on the flow of inputs and outputs through the software and strengthening the security of the software.<br>
The term 'white box' is used because of the internal perspective of the system. The clear box or white box or transparent box name denote the ability to see through the software's outer shell into its inner workings.<br>
Developers do white box testing. In this, the developer will test every line of the code of the program. The developers perform the White-box testing and then send the application or the software to the testing team, where they will perform the black box testing and verify the application along with the requirements and identify the bugs and sends it to the developer.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 4</b>  |   |   | 
|-----------|--------------------|-----------|
|4-1 White Box Testing |4-2 Black Box Testing |4-3 Grey Box Testing | 


</article>


</article>

<article id="chapter-5">

## Chapter 5
- ### White Box Techniques
Data flow testing is used to analyze the flow of data in the program. It is the process of collecting information about how the variables flow the data in the program. It tries to obtain particular information of each particular point in the process.<br>
Data flow testing is a group of testing strategies to examine the control flow of programs in order to explore the sequence of variables according to the sequence of events. It mainly focuses on the points at which values assigned to the variables and the point at which these values are used by concentrating on both points, data flow can be tested.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 5</b>  |   |   | 
|-----------|--------------------|-----------|
|5-1 Data Flow Testing |5-3 Branch Coverage Testing |5-5 Decision Coverage Testing |
|5-2 Control Flow Testing |5-4 Statement Coverage Testing | |


</article>

<article id="chapter-6">

## Chapter 6
- ### Black Box Techniques
Decision table technique is one of the widely used case design techniques for black box testing. This is a systematic approach where various input combinations and their respective system behavior are captured in a tabular form.<br>
That's why it is also known as a cause-effect table. This technique is used to pick the test cases in a systematic manner; it saves the testing time and gives good coverage to the testing area of the software application.<br>
Decision table technique is appropriate for the functions that have a logical relationship between two and more than two inputs.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 6</b>  |   |
|-----------|--------------------|
|6-1 Decision Table |6-3 Cause-Effect Testing | 
|6-2 All-pair Testing |6-4 State TransitionUse Case | 


</article>

<article id="chapter-7">

## Chapter 7
- ### Types of Black Box


#### 🔹 Topics in this chapter include
| <b>Chapter 7</b>  |   |
|-----------|--------------------|
|7-1 Functional Testing |7-2 Non-Functional Testing |


</article>

<article id="chapter-8">
  
## Chapter 8
- ### Types of Functional
Unit testing involves the testing of each unit or an individual component of the software application. It is the first level of functional testing. The aim behind unit testing is to validate unit components with its performance.<br>
A unit is a single testable part of a software system and tested during the development phase of the application software.<br>
The purpose of unit testing is to test the correctness of isolated code. A unit component is an individual function or code of the application. White box testing approach used for unit testing and usually done by the developers.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 8</b>  |   |   | 
|-----------|--------------------|-----------|
|8-1 Unit Testing |8-2 Integration Testing |8-3 System Testing |

</article>

<article id="chapter-9">

## Chapter 9
- ### Types of Non-functional


#### 🔹 Topics in this chapter include
| <b>Chapter 9</b>  |   |   | 
|-----------|--------------------|-----------|
|9-1 Performance Testing |9-2 Usability Testing |9-3 Compatibility Testing |


</article>

<article id="chapter-10">

## Chapter 10
- ### Test case development
Testing documentation is the documentation of artifacts that are created during or before the testing of a software application. Documentation reflects the importance of processes for the customer, individual and organization.<br>
Projects which contain all documents have a high level of maturity. Careful documentation can save the time, efforts and wealth of the organization.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 10</b>  |   |   | 
|-----------|--------------------|-----------|
|10-1 Testing Documentation |10-2 Test Scenario |10-3 Test Case |


</article>

<article id="chapter-11">
  
## Chapter 11
- ### Testing Techniques
The test case design technique or methods or approaches that need to be followed by every test engineer while writing the test cases to achieve the maximum test coverage. If we follow the test case design technique, then it became process-oriented rather than person-oriented.<br>
The test case design technique ensures that all the possible values that are both positive and negative are required for the testing purposes. In software testing, we have three different test case design techniques which are as follows:<br>
- Error Guessing
- Equivalence Partitioning
- Boundary Value Analysis[BVA]

#### 🔹 Topics in this chapter include
| <b>Chapter 11</b>  |   |   | 
|-----------|--------------------|-----------|
|11-1 Error Guessing |11-2 Equivalence  Portioning |11-3 Boundary Value analysis |


</article>

<article id="chapter-12">

## Chapter 12
- ### Test Management
A test plan is a detailed document which describes software testing areas and activities. It outlines the test strategy, objectives, test schedule, required resources (human resources, software, and hardware), test estimation and test deliverables.<br>
The test plan is a base of every software's testing. It is the most crucial activity which ensures availability of all the lists of planned activities in an appropriate sequence.<br>
The test plan is a template for conducting software testing activities as a defined process that is fully monitored and controlled by the testing manager. The test plan is prepared by the Test Lead (60%), Test Manager(20%), and by the test engineer(20%).<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 12</b>  |   |   | 
|-----------|--------------------|-----------|
|12-1 Test Plan |12-2 Test case review process |12-3 Requirement Traceability Matrix |


</article>

<article id="chapter-13">
  
## Chapter 13
- ### Defect Tracking


#### 🔹 Topics in this chapter include
| <b>Chapter 13</b>  |   |
|-----------|--------------------|
|13-1 Bug in Software Testing |13-3 Severity & Priority |
|13-2 Bug Life cycle |13-4 Test Environment |

</article>

<article id="chapter-14">
  
## Chapter 14
- ### Other types of Testing
Regression testing is a black box testing techniques. It is used to authenticate a code change in the software does not impact the existing functionality of the product. Regression testing is making sure that the product works fine with new functionality, bug fixes, or any change in the existing feature.<br>
Regression testing is a type of software testing. Test cases are re-executed to check the previous functionality of the application is working fine, and the new changes have not produced any bugs.<br>
Regression testing can be performed on a new build when there is a significant change in the original functionality. It ensures that the code still works even when the changes are occurring. Regression means Re-test those parts of the application, which are unchanged.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 14</b>  |   |   |    | 
|-----------|--------------------|-----------|-----------|
|14-1 Regression Testing |14-8 Recovery Testing |14-15 Mainframe Testing |14-22 Volume Testing |
|14-2 Smoke Testing |14-9 Exploratory Testing |14-16 Adhoc Testing |14-23 Scalability Testing |
|14-3 Sanity Testing |14-10 Visual Testing |14-17 Globalization Testing |14-24 Stability Testing |
|14-4 Static Testing |14-11 Acceptance Testing |14-18 Mutation Testing |14-25 Spike Testing |
|14-5 Dynamic Testing |14-12 Alpha Testing |14-19 Security Testing |14-26 Negative Testing |
|14-6 Load Testing |14-13 Beta Testing |14-20 Accessibility Testing |14-27 Positive Testing |
|14-7 Stress Testing |14-14 Database Testing |14-21 Structural Testing | |


</article>

<article id="chapter-15">

## Chapter 15
- ### Software Testing Tools
Software testing tools are required for the betterment of the application or software.<br>
That's why we have so many tools available in the market where some are open-source and paid tools.<br>
The significant difference between open-source and the paid tool is that the open-source tools have limited features, whereas paid tool or commercial tools have no limitation for the features. The selection of tools depends on the user's requirements, whether it is paid or free.<br>
etc<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 15</b>  |   |   | 
|-----------|--------------------|-----------|
|15-1 Software testing tools |15-5 Performance testing tools |15-9 Mobile testing tools |
|15-2 Test management tools |15-6 Cross-browser testing tools |15-10 GUI testing tools |
|15-3 Defect/Bug tracking tools |15-7 Integration testing tools |15-11 Security testing tools |
|15-4 Automation testing tools |15-8 Unit testing tools |15-12 Penetration testing tools |


</article>

<article id="chapter-16">

## Chapter 16
- ### Differences
Automation testing is a process of changing any manual test case into the test scripts by using automation testing tools, and scripting or programming language is called automation.<br>
Automation testing is used to increase the efficiency, effectiveness, and coverage of Software testing.<br>
Automation test engineer uses automation testing tools to automate the manual design test cases without any human interference.<br>
And these testing tools can control the execution of tests, access the test data, and compares the actual result against the expected result.<br>

#### 🔹 Topics in this chapter include
| <b>Chapter 16</b>  |   |   | 
|-----------|--------------------|-----------|
|16-1 Automation Testing vs Manual Testing |16-8 Alpha Testing vs Beta Testing |16-15 Bug vs Defect vs Error vs Fault vs Failure |
|16-2 Load Testing vs Stress Testing |16-9 Black Box vs. White Box vs. Grey Box Testing |16-16 Testing vs Debugging |
|16-3 Smoke Testing vs Sanity Testing |16-10 Globalization Testing vs Localization Testing |16-17 Frontend Testing vs Backend Testing |
|16-4 System Testing vs Acceptance Testing |16-11 Test Case vs Test Scenarios |16-18 HLD vs LLD |
|16-5 Quality Assurance vs Quality Control |16-12 Test Plan vs Test Strategy |16-19 BRS vs SRS |
|16-6 Static Testing vs Dynamic Testing |16-13 Boundary value analysis vs Equivalence partitioning |16-20 Positive Testing vs Negative Testing|
|16-7 Verification vs Validation Testing |16-14 SDLC vs STLC | |


</article>

<article id="chapter-17">

## Chapter 17
- ### Software Testing MCQ
- 

#### 🔹 Topics in this chapter include
| <b>Chapter 17</b>  |   
|-----------|
|17-1 Software Testing MCQ |


</article>



---
<article id="authors">

## Authors

### The First: "Mahsa Mohammadi"

<p align="center">
  <img width="320" height="320" src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Authors/MahsaMohammadi.jpeg">
</p>

I graduated in computer software engineering, also, I have been worked for two and a half at Irisa Company which is worked with oracle database and oracle form builder and report then I analyzed data. Because I am interested in AI and data mining so I decided to get this way with python programming and machine learning.

#### My main research interests
- Artificial Intelligence, Machine Learning
- Database Design and Analysis
- Data mining

🌐 𝐏𝐞𝐫𝐬𝐨𝐧𝐚𝐥 𝐏𝐚𝐠𝐞 "𝐌𝐚𝐡𝐬𝐚 𝐌𝐨𝐡𝐚𝐦𝐦𝐚𝐝𝐢" 👉 [mmohammadi4820.github.io](https://mmohammadi4820.github.io/)<br>
📧 𝐄𝐦𝐚𝐢𝐥: mmohammadi4820@gmail.com

============================================================================

### The Second: "Mohammad Hossein Mohammadi"

<p align="center">
  <img width="360" height="276" src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Authors/MohammadHosseinMohammadi.jpeg">
</p>

Iam currently a Final-year BS.c student at the Department of Computer Engineering, Islamic Azad University, Najafabad Branch (IAUN) (Rank in CWUR) where I am a member of the Bioinformatics Laboratory (BL), advised by Prof. Mehdi Jabalameli. my research involves machine vision, deep learning, and neural networks. where I will complete my thesis on Semantic segmentation of breast cancer pathology images using the U-Net model.

Prior to BL, I finished my Diploma - Mathematics and Physics in Sheikh Ansari Highschool, in September 2015. I tried to use my Diploma to build a solid bedrock for my future research. So in addition to taking many optional bachelor-level courses on math and computer science. I spent 6 months as an intern Programmer at the "CoTech" in Isfahan.

#### My main research interests
- Artificial Intelligence, Machine Learning
- Optimization Algorithm, Neural & NeuroFuzzy Network
- Computer Vision, Signal and Image Processing

🌐 𝐏𝐞𝐫𝐬𝐨𝐧𝐚𝐥 𝐏𝐚𝐠𝐞 "𝐌𝐨𝐡𝐚𝐦𝐦𝐚𝐝 𝐇𝐨𝐬𝐬𝐞𝐢𝐧 𝐌𝐨𝐡𝐚𝐦𝐦𝐚𝐝𝐢" 👉 [mohammadimh76.github.io](https://mohammadimh76.github.io/)<br>
📧 𝐄𝐦𝐚𝐢𝐥: m.h.mohammadimir2017@gmail.com

============================================================================

### Third: "Seyed Yahya Moradi"

<p align="center">
  <img width="320" height="318" src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Authors/SeyedYahyaMoradi.jpeg">
</p>

I am Biomedical Engineer from University of Isfahan. My research interests is Non-Invasive Brain Stimulation, Neuroscience, Brain Mapping & Connectivity, Biomedical AI & IOT, Biosignal Processing.

- Brain stimulation techniques such as tDCS, tACS, tRNS, TMS, Theta-Burst Stimulation (TBS) and Magnetic Seizure Therapy (MST)<br>
- Sleep, Plasticity, Perception, Vision, Navigation<br>
- Q/EEG Decoding; Source Localization; Beamforming; Blind source separation<br>
- Causal Inference; Big Data; Unsupervised & Online learning; Expert System<br>
- Chaos and Fractal Theory<br>

🌐 𝐏𝐞𝐫𝐬𝐨𝐧𝐚𝐥 𝐏𝐚𝐠𝐞 "𝐒𝐞𝐲𝐞𝐝 𝐘𝐚𝐡𝐲𝐚 𝐌𝐨𝐫𝐚𝐝𝐢" 👉 [symoradi.website2.me](http://symoradi.website2.me/)<br>
📧 𝐄𝐦𝐚𝐢𝐥: s.yahyamoradi@yahoo.com 

</article>

---
---

<article id="demo">
  
## Demo 

👇Click on the link below to see the E-Book Demo!👇😉

## (E-Book Demo): 🔺(Coming Soon)🔺


</article>

---

## BookCollection

<article id="bookcollection">
  
  |[TensorFlow Tutorial](https://github.com/Mohammadimh76/Book_TensorFlow_Tutorial) |[ArtificialIntelligence](https://github.com/mmohammadi4820/Book_ArtificialIntelligence)  |[ComprehensiveDatabases<br>Training](https://github.com/mmohammadi4820/Book_ComprehensiveDatabasesTraining)  |[SoftwareEngineering Tutorial](https://github.com/mmohammadi4820/Book_SoftwareEngineering_Tutorial) |
|-----------|--------------------|-----------|--------------------|
|[<p><img src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Cover/Book_TensorFlow.jpeg"></p>](https://github.com/Mohammadimh76/Book_TensorFlow_Tutorial)|[<p><img src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Cover/Book_ArtificialIntelligence.jpeg"></p>](https://github.com/mmohammadi4820/Book_ArtificialIntelligence)|[<p><img src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Cover/Book_DataBase.jpeg"></p>](hhttps://github.com/mmohammadi4820/Book_ComprehensiveDatabasesTraining)|[<p><img src="https://raw.githubusercontent.com/mmohammadi4820/Book_SoftwareTesting_Tutorial/main/Cover/Book_SoftwareEngineering.jpeg"></p>](https://github.com/mmohammadi4820/Book_SoftwareEngineering_Tutorial)|

</article>

</main>



