<h1 style="text-align:center">TDT4175 Information Systems</h1>
<h2>Table of contents </h2>

1. 	[**An Introduction to Information Systems**](#chapter1)  
	1.1 [Data, Information, and knowledge](#chapter1.1)  
	1.2 [The Value of Information](#chapter1.2)  
	1.3 [Information Systems](#chapter1.3)  
	1.4 [Types of Information Systems](#chapter1.4)  
2. [**Information Systems in Organizations**](#chapter2)  
	2.1 [Porters "5 Powers" Model](#chapter2.1)  
	2.2 [Organizational Structures](#chapter2.2)  
	2.3 [User Satisfaction and Technology Acceptance](#chapter2.3) 
3. [**E-commerce**](#chapter3)  
	3.1 [Multistage Model for E-Commerce](#chapter3.1)  
	3.2 [M-commerce](#chapter3.2)  
	3.3 [Advantage of E-&M-Commerce](#chapter3.3)
4. [**Business Information Systems**](#chapter4)  
	4.1 [Transaction Processing Systems (TPSs)](#chapter4.1)  
	4.2 [Enterprise Resource Planning (ERP)](#chapter4.2)  
	4.3 [Supply Chain Management (SCM)](#chapter4.3)  
	4.4 [Customer Relationship Management (CRM)](#chapter4.4)  
	4.5 [Management Information Systems (MIS)](#chapter4.5)  
	4.6 [Decision Support System (DSS)](#chapter4.6)  
	4.7 [Knowledge-based DSS](#chapter4.7)  
	4.8 [Executive Support Systems (ESS)](#chapter4.8)  
	4.9 [Group Decision Support Systems (GDSS)](#chapter4.9)  
	4.10 [Knowledge Management System (KMS)](#chapter4.10)  
	4.11 [Expert systems](#chapter4.11)
5. [**Modeling of Information Systems**](#chapter5)  
	5.1 [BPMN for process modeling](#chapter5.1)  
	5.2 [BPMN Elements](#chapter5.2)
6.  [**Enterprise Architecture**](#chapter6)  
	6.1 [Zachman](#chapter6.1)  
	6.2 [TOGAF](#chapter6.2)  
	6.3 [Enterprise Architecture Modeling](#chapter6.3)
7.	[**Strategic Planning**](#chapter7)  
	7.1 [Analyze Situation](#chapter7.1)  
	7.2 [Set Direction](#chapter7.2)  
	7.3 [Define Strategies](#chapter7.3)  
	7.4 [Deploy Plan](#chapter7.4)
	
<br>
<h2>Previous exams</h2>
**Recurring themes on previous exams:**


• Developing BPMN models  
• Computer-based IS + examples of the identified components    
• Enterprise Architecture     
• Reengineering vs Continuous improvement  
• E-commerce (2017)  
• Porters "5 power" (2017)  
• Business Architecture  
• Transaction processing systems   
• Decision support system  
• Enterprise Architecture

**e.g. questions and answers:**

**reasons for the use of modelling in IS dev:** Communication; Sense making; Quality Assurance; Model Deployment; Requirements and Design.

**IT use can:** Ensure economic, personal, organisational(business) and societal gain.  
Goals of the IS-methodology –> Value creation 


## Syllabus & Curriculum
### Syllabus:

**Candidates acquire knowledge about:**  
- What an [information system](#chapter1.3) is  
- The relation between business strategy, organizational strategy and ICT strategy.  
- Taxonomies for different information [systems](#chapter5).  
- Methodologies for the [deployment](#chapter8) of information systems.  
- Methodologies for requirements engineering.  
- Ethics and use of information systems.  

**Candidates are able to:**  
- Elicit requirements for information systems.  
- Model business processes using [BPMN](#chapter6).

**General competence - candidates can:**  
- Contribute to consultancy activities in the context of the introduction of information systems in (big) organizations.

### Curriculum:
- “Principles of Information Systems” (11th/10th edition), Star and Reynolds Chapter 1,2,8,9,10,11  
- “BPMN method & style”
http://brsilver.com/bpmn-method-and-style/  
- Chapter 2.1 and 2.2 in Krogstie, J: Model-based development and Evolution of Information Systems: A quality Approach.  
*- chapter can be downloaded* [here](http://link.springer.com/book/10.1007/978-1-4471-2936-3/page/1 )  

**NB - Slides from lectures are also part of the curriculum - NB**

<br>
<a name="chapter1"></a>
## 1. An Introduction to Information System
We live in an information economy. Information itself has real value, and in order to stay competitive, organizations require a steady flow of information about their business partners, competitors, customers, employees, markets, and suppliers. Information systems are increasingly being used to gather, store, digest, analyze, and make sense out of all this information

<a name="chapter1.1"></a>
### 1.1 Data, Information, and knowledge
To be an effective manager in any area of business, you need to understand that information is one of an organization’s most valuable resources. Information is not the same thing as data, and knowledge is different from both data and information. These concepts will now be explained.

> **"Data"**  
> consists of raw facts, such as an employee number, total hours worked in a week, an inventory part number, or the number of units produced on a production line. 

> **"Information"**  
> is a collection of data organized and processed so that it has additional value beyond the facts themselves. For example, a sales manager may want individual sales data summarized so it shows the total sales for the month.  
> Keywords: Input, Process, Output and Feedback.

> **"Knowledge"**  
> is defined as awareness and understanding of a set of information and how that information can be put best to use.

Combining and converting data to useful information is called a **process**. A set of logically related tasks performed to achieve a defined outcome.
The process of defining relationships among data to create useful information requires knowledge. 
Information is essentially data made more useful through the application of knowledge.

<a name="chapter1.2"></a>
### 1.2 The Value of Information
The value of information is directly linked to how it helps decision makers achieve their organization’s goals. Fundamental to the quality of a decision is the quality of the information used to reach that decision. The importance of each of these characteristics varies depending on the situation and the kind of decision you are trying to make.

**Characteristics of quality information** (BAT SCACC):


Characteristic  | Definition
------------- | -------------
**Belivable** | Info can be trusted
**Accurate** | Info without errors <br> (bad data (*garbage in*) => bad info (*garbage out*))
**Timely** | Info is delivered when needed
**Secure** | Only accessible for authorized users  
**Complete** | Contains all important facts  
**Accessible** | Easily accessible in the right format and at the right time 
**Consistent Representation** | The same info is represented in the same way
**Consise** | Info is to the point..<br> Giving a lot of information clearly and in a few words


<a name="chapter1.3"></a>
### 1.3 Information Systems

We say that an **information system (IS)** is a set of interrelated components that collect, manipulate and process data into information, as well as providing feedback; 

![components of an IS](img/Skjermbilde\ 2018-12-11\ kl.\ 15.36.45.png)

>An information System assembles, stores,
processes and delivers information relevant to an organisation (or to society), in such a way that the information is accessible and useful to those who wish to use it, including managers, staff, clients and citizens. An information system is a human activity (social) system which may or may not involve the use of computer systems. 

>(Buckingham et al., 1987).

#### Feedback
An information system provides a feedback mechanism to monitor and control its operation to make sure it continues to meet its goals and objectives.  
The feedback mechanism is critical to helping organizations achieve their goals, such as increasing profits or improving customer service.


Characteristic  | Definition
------------- | -------------
Efficiency/Speed | Measure of what is produced divided by what is consumed
Effectiveness/Precision | Measure of the extent to which a system attains its goals
System performance standard | Specific objective of the system (for example is the system conform the GDPR?)

![]( img/Skjermbilde\ 2018-12-11\ kl.\ 15.36.35.png )

<a name="chapter1.4"></a>
### 1.4 Types of Information Systems
Information systems can be manual or computer based (**CBIS**).  
Businesses can use IS to increase revenues and reduce costs, solve problems and make decisions. An organization’s **technology infrastructure** includes all the hardware, software, databases, networks, people, and procedures that are configured to collect, manipulate, store, and process data into information. The technology infrastructure is a set of shared IS resources that form the foundation of each computer-based infor- mation system.

##### The components of a CBIS:
![CBIS components](img/Skjermbilde\ 2018-12-11\ kl.\ 15.18.19.png )

Component  | Description
------------- | -------------
Hardware | Computer equipment used to perform input, processing, storage and output activities
Software | Programs operating with computer
Databases | Organized collection of facts and information
Telecommunications | Carry out tasks through computer networks
People | Are the most important element in most CBISs
Procedures | The strategies, policies, methods and rules for using a CBIS

Using a CBIS involves setting and following many **procedures** *(a set of steps that need to be followed to achieve a specific end result)* including those for the operation, maintenance, and security of the system.  
Good procedures can help companies take advantage of new opportunities and avoid lengthy business disruptions in the event of natural disasters. Poorly developed and inadequately implemented procedures, however, can cause people to waste their time on useless rules or result in inadequate responses to disasters.

**The three types:**  
Most organizations have a number of different information systems. When considering the role of business managers in working with IS, it is useful to divide information systems into three types;

![](img/Skjermbilde\ 2018-12-11\ kl.\ 15.28.01.png )

#### System Development
Steps for creating/modifying business systems:  
<ul>
<li> Investigate  
	- understand problem
<li> Analysis  
	- understand solutions
<li> Design  
	- select and plan best solution
<li> Implementation  
	- place solution into effect
<li> Maintenance  
	- evaluate results of solution  
	- check & modify system
</ul>
**Computer literacy:** Knowledge of computer systems & equipment.

**IS literacy:** Knowledge of how and why technology is applied in business.

<a name="chapter2"></a>
## 2 Information Systems in Organizations
>**"Organization"**  
An organization is a group of people that is structured and managed to meet its mission or set of group goals. 

Organizations are considered to be open systems, meaning that they affect and are affected by their surrounding environment. Providing value to a stakeholder (customer, supplier, partner, shareholder, or employee) is the primary goal of any organization.

Within an organization, information systems
are developed, or re-developed,
with the aim to support value addition. Cost reduction, productivity and competitive advantage are some of the motivations.

<br>
<a name="chapter2.1"></a>
### 2.1 Porters "5 Powers" Model
Porters five powers is used to help [analysing](#chapter8.1) the nature of competition within an industry. It helps us understand and assess the industries profitability and attractiveness.

1. **The threat of new competitors** will raise the level of competition. Entry barriers determine the relative threat of new competitors. These barriers include the capital required to enter the industry and the cost to custo- mers to switch to a competitor.
2. **The bargaining power of buyers** determines prices and long-term profit- ability. This bargaining power is stronger when there are relatively few buyers but many sellers in the industry, or when the products offered are all essentially the same.
3. **The threat of substitute products** can lower the profitability of industry competitors. The willingness of buyers to switch products and the relative cost and performance of substitutes are key factors in this threat.
4. **The bargaining power of suppliers** can significantly affect the industry’s profitability. Suppliers have strong bargaining power in industries that have many buyers and only a few dominant suppliers and in industries that do not represent a key customer group for suppliers.
5. **The degree of rivalry** between competitors is high in industries with many equally sized competitors or little differentiation between products.

![](img/Skjermbilde\ 2018-12-11\ kl.\ 16.12.46.png)


<a name="chapter2.2"></a>
### 2.2 Organizational Structures
The way organizational subunits relate to overall organization. Organizational structures are subunits of an organization, and in which way they relate to the overall organization.


Subunits  | Description
------------- | -------------
 Traditional (tree) |Hierarchy of decision making and authority flows:<br>From the strategic management at the top down to operational management and nonmanagementemployees
 Flat | Reduced level of management layers and empowers employees at lower levels 
 Project | Centered on major products or services. Many project teams are temporary
 Team | Centered on work teams or groups. Team can be temporary or permanent, depending on tasks
 Virtual | - Uses individuals, groups, or complete business units in geographically dispersed areas.<br>- Can reduce costs for an organization<br>- Also allows colaborative work: Managers and employees can effectively work in groups, even those composed of members from around the world
 
#### Some definitions:
 
Definition | description
------------- | -------------
Organizational culture | the major understanding and assumptions for a business
Organizational change| how organizations plan for, implement, and handle change
Change model | representation of change theories that identifies the phases of change
Unfreezing | ceasing old habits and creating a climate receptive to change
Moving | the process of learning new methods and systems
Refreezing | reinforce changes to make the new process accepted
Organizational learning| adapting to new conditions or altering practices over time
***Continuous improvement*** | **Constantly try to improve business processes and add value to products and services**
***Reengineering*** | **Radical redesign of business processes, organizational structures, information systems, and values of the organization to achieve a breakthrough in business results. This implies making fundamental changes in the way a company does business.**
Technology diffusion | a measure of how widely technology is spread
Technology infusion | a measure of how deeply imbedded technology is in an area
Quality | ability of a product to meet or exceed customer expectations. 
Techniques used | total quality management and six sigma
Return of Investment (ROI) | profits generated as a percentage of the investment in IS 
Earning growth | the increase in profit

> **"Business process"**  
> consists of a set of activities that is performed in an organization. These activities are coordinated to jointly realize a business goal.

<a name="chapter2.3"></a>
### 2.3 User Satisfaction and Technology Acceptance
####Technology Acceptance Model (TAM)
- Theory that models how users come to accept and use a technology.
- Specifies factors that can lead to better attitudes about the IS.

when users are presented with a new technology, two factors influence their decision about how and when they will use it:

- Perceived usefulness (PU)
- Perceived ease-of-use (PEOU)

![](img/Skjermbilde\ 2018-12-11\ kl.\ 19.24.11.png)

<br>
<a name="chapter3"></a>
## 3 E-commerce
Business transactions executed electronically between companies, consumers or the public sector.  
Some common subsets of e-commerce are;

Subset  | Description | IMG
------------- | ------------- | -------------
Business-to-Business(**B2B**)  | All the participants are organizations. An organization will use both:<br>– Buy-side e-commerce to purchase goods and services<br>–Sell-side e-commerce to sell products to its customers | ![](img/Skjermbilde\ 2018-12-12\ kl.\ 11.30.15.png)
Business-to-Consumer(**B2C**) | Customers deal directly with an organization throug *disintermediation*<br>(The elimination of intermediate organizations) | ![](img/Skjermbilde\ 2018-12-12\ kl.\ 11.33.47.png)
Consumer-to-Consumer(**C2C**) | Consumers selling directly to other consumers | ![](img/Skjermbilde\ 2018-12-12\ kl.\ 11.37.54.png)
Consumer to Business(**C2B**) |  Consumers create value and businesses consume that value. | ![](img/Skjermbilde\ 2018-12-12\ kl.\ 11.53.10.png)
E-government | Use of information and communications technology (electronic communications devices, computers and the Internet) to provide public services to citizens and other persons in a country or region. | ![](img/Skjermbilde\ 2018-12-12\ kl.\ 12.09.41.png)

<a name="chapter3.1"></a>
### 3.1 Multistage Model for E-Commerce
![](img/Skjermbilde\ 2018-12-12\ kl.\ 12.14.37.png)

#### Challenges

Define effective e-commerce model and strategy
<ol>
<li>Components of successful e-commerce model  
- Community  
- Content  
- Commerce
<li>Dealing with consumer privacy concerns
<li>Overcoming consumers lack of trust
<li>Overcome global issues
</ol>

<a name="chapter3.2"></a>
### 3.2 M-commerce
A subcategory of e-commerce that focus on transactions via mobile devices. So people can do their business transactions anywhere they go as long as they can access the internet on their smartphones and can perform transactions with just a few taps on the screen.

### 3.3 Advantage of E-&M-Commerce
<a name="chapter3.3"></a>
- Reduce cost
- Increase accuracy
- Speed flow of goods and information
- Improve customer service

<br>
<a name="chapter4"></a>
## 4 Business Information Systems
![](img/Skjermbilde\ 2018-12-12\ kl.\ 11.21.05.png)

This chapter covers the many different types of business information systems.

<a name="chapter4.1"></a>
### 4.1 Transaction Processing Systems (TPSs)
An information processing system for fundamental business transactions involving the collection, modification and retrieval of all transaction data. The system is an organized collection of people, procedures, software, databases and devices used to record these transactions.

>**"Transaction"**<br>Any business-related exchange such as  inventory control, payments to employees, sales to customers, or payments to suppliers.<br>
>TRANSACTION = INTERACTION + EXECUTION

#### Types of Transaction Processing

 Type| Description
------------- | -------------
On-line system | Direct connection between operator and the TPS.<br> They provide immediate result and used to process a single transaction at a time. 
Batch-processing system | Transactions are grouped together and processed as a unit.

#### Objectives
- Process data generated by and about transactions
- Maintaing a high degree of accuracy and integrity
- Produce timely documents & reports
- Increase labour efficiency
- Help provide increased service
- Help build & maintain customer loyalty
- Achieve competitive advantage
- Act as main link between the organization and external entities

![Editor preferences pane](img/Skjermbilde\ 2018-12-12\ kl.\ 12.50.43.png)

<a name="chapter4.2"></a>
### 4.2 Enterprise Resource Planning (ERP)
A collection of software packages, which ties all of an enterprise's various functions into a cohesive database. These packages affect all aspects of the IS environment to support how the firm runs its business.  
An ERP system is a set of integrated programs that manage a company’s vital business processes through real-time monitoring.
>**"Business process"**  
Set of coordinated and related activities that
takes one or more kinds of input and creates an
output of value to the customer of that process

![](img/dP8lTvz.png)

![](img/Skjermbilde\ 2018-12-12\ kl.\ 13.07.32.png)

 Pros| Cons
------------- | -------------
-Elimination of costly, inflexible legacy systems <br>-Improvement of work processes <br>-Increase in access to data for operational decision making <br>-Improvement of work processes <br>-Upgrade of technology infrastructure | -Expense and time in implementation<br>-Difficulty implementing change<br>-Difficulty integrating with other systems<br>-Difficulty in loading data into new ERP system<br>-Risks in using one vendor<br>-Risk of implementation failure

<a name="chapter4.3"></a>
### 4.3 Supply Chain Management (SCM)
**A system that includes:**  
*planning*, *executing* and *controlling* all activites involved in raw material sourcing and procurement.  
Convert raw materials to finished products, and warehousing and deliver finished product to customer.  
![](img/Skjermbilde\ 2018-12-12\ kl.\ 13.31.04.png)

**The process for developing a production plan includes:**  
sales forecasting, sales and operations plan, demand management, detailed scheduling, materials requirement planning, purchasing, production and sales ordering.

<a name="chapter4.4"></a>
### 4.4 Customer Relationship Management (CRM)
A system that helps a company manage all aspects of customer encounters, including marketing and advertising, sales, customer service after the sale, and programs to retain loyal customers. That is, understanding and anticipating the needs of current and potential customers.  

>**"CRM software"**  
Software that automates and integrates the functions of sales,
marketing, and service in an organization

![](img/Skjermbilde\ 2018-12-12\ kl.\ 13.50.51.png)
**Key features of a CRM system:**

- Contact management
- Sales management
- Customer support
- Marketing automation
- Analysis
- Social networking
- Access by smartphones
- Import contact data

<a name="chapter4.5"></a>
### 4.5 Management Information Systems (MIS)
MISs produce fixed, regularly scheduled reports based on data extracted and summarized from the firm’s underlying transaction processing systems (TPSs) to managers and decision makers.


- Provides info & support for effective decision-making and feedback on daily operations
- The insight provided helps control, organize and plan more effectively and effeciently
- Helps an organization to achieve its goals

Input | Output
----- | ----- 
**TPS** and **ERP** systems | - Scheduled reports<br>- Demand reports<br>- Drill down reports<br>- Provide detailed data about a situation 

**Characteristics**  

- Provide reports with fixed and standard formats
- Produce hard-&soft-copy reports
- Use internal data stored in computer system
- Allow end user to develop their own custom reports
- Require user requests for reports developed by systems personnel

Types | Description
----- | -----
Financial MIS | provides financial information
Manufacturing MIS |monitor & control the process of converting raw materials to finished goods
Marketing MIS | supports product development, distribution, pricing decisions, promotions and sales forecasting
Human resource MIS | Concerned with activities related to employees and potential employees
Accounting MIS | Provides info on accounts payable, accounts receivable, payroll, etc.

<a name="chapter4.6"></a>
### 4.6 Decision Support System (DSS)
Organized collection of people, procedures, software, databases and devices used to help *make decisions that solve problems*.  
DSS is used for problem-specific decision making for semistructured and unstructured problems and is used at all levels in an organization.

**Programmed vs Nonprogrammed Decisions:**  

 _| Description | _
 ---|---|----
Programmed decisions|- Made using a rule, procedure, or quantitative method<br>- Easy to computerize using traditional informationsystems 
Nonprogrammed decisions |- Decisions that deal with unusual or exceptional situations<br>- Not easily quantifiable| **DSS**


**Characteristics** 
 
- Provide rapid access to information
- Handle large amounts of data from different sources
- Provide report & presentation flexibility
- Offer both textual and graphical orientation
- Support drill-down analysis

For DSS capabilities and components, see [Wikipendium](https://www.wikipendium.no/TDT4175_Information_Systems#capabilities) 

**How DSS differs from MIS:**

![](img/Skjermbilde\ 2018-12-12\ kl.\ 16.12.28.png)

<a name="chapter4.7"></a>
### 4.7 Knowledge-based DSS
Knowledge-based decision support systems are systems designed to ensure more precise decision-making by effectively using timely and appropriate data, information, and knowledge management for convergence industry. These systems refer to decision-making based on relevant knowledge, which is based on artificial intelligence, and on the application of information and communication technologies.
![](img/Skjermbilde\ 2018-12-12\ kl.\ 17.46.55.png)

 
####Rule based decisions:
The collection of rules that contribute to a “decision”
can be structured as a decision tree. The tree is simply a representation of a collection of rules.
![](img/Skjermbilde\ 2018-12-12\ kl.\ 17.53.09.png)

The rules can also be represented using a table.  
This table represents the exact same rules as the decision tree does, in the same order.
![](img/Skjermbilde\ 2018-12-12\ kl.\ 17.55.26.png)

**Problems with Rules**  
• Fail to work if a problem is not anticipated by rules.  
• Can interact in complex ways.  
• Huge rule sets are difficult to maintain  
• Are not flexible (contextualizable) 

####Case based decisions:
In CBR “knowledge” is held in a case base of real prior problems and their solutions.

e.g.
Case-based diagnosis is common:  
• physician matches new case with one seen
previously and uses the diagnosis of the old case
as a starting point.
![](img/Skjermbilde\ 2018-12-12\ kl.\ 17.59.59.png)

**Benefits of CBR**  
• May work better than rule-based or modelbasedfor natural domains.  
• Does not require extensive analysis of domainknowledge.  
• Existing data and knowledge - case histories,repair logs - are leveraged.  
• Shortcuts complex reasoning - may be quicker than rule-based or model-based.

**Problems with CBR**  
<ul>
<li> Lack of deep knowledge  
	– poor explanation  
	– danger of misapplication of cases.  
<li> Large case base can slow things down  
– (compute-store tradeoff)
<li> Knowledge engineering can still be arduous  
– designing and selecting features  
– similarity matching algorithms
</ul>

<a name="chapter4.8"></a>
### 4.8 Executive Support Systems (ESS)
Special case of DSS, designed to support higher-level decisions (strategic planning)

<a name="chapter4.9"></a>
### 4.9 Group Decision Support Systems (GDSS)
Is an interactive computer based system that facilitates a number of decision-makers (working together in a group) in finding solutions to problems that are unstructured in nature. They are designed in such a way that they take input from multiple users interacting simultaneously with the systems to arrive at a decision as a group.

Consists of most DSS elements + software for providing group support

**Characteristics of a GDSS That Enhance Decision Making:**  
• Anonymous input  
• Reduction of negative group behavior  
• Parallel and unified communication  
• Automated record keeping  

<a name="chapter4.10"></a>
### 4.10 Knowledge Management System (KMS)
Organized collection of people, procedures, software, databases, and devices to: Create, store, share, and use the organization’s knowledge and experience.

Effective KMS based on learning new knowledge and changing procedures and approaches as a result.

![KMS](img/Skjermbilde\ 2018-12-13\ kl.\ 09.34.03.png)

<a name="chapter4.11"></a>
### 4.11 Expert systems
Use heuristics to arrive at conclusions and make suggestions.


**Characteristics**  
• Explain their reasoning/suggested solution  
• Display intelligent behavior  
• Draw conclusions from complex relationships  
• Provide portable knowledge  
• Deal with uncertainty

<br>
<a name="chapter5"></a>
## 5 Modeling of Information Systems
Models are highlights of the essentials of (part of) reality. They are quicker and cheaper to make than the full artifact, but still similar, so that it is often possible to spot
consequences of decisions.  
Models are important for producing more innovative results of better quality, and provide risk-free (although not effort-free) testing of:   
	- what-if scenarios  
	- accident simulation 

<a name="chapter5.1"></a> 
### 5.1 Business Process Model and Notation (BPMN)
BPMN is the leading standard for modeling in BPM (Business
Process Modeling/Business Process Management).  
> **"Business process"**  
> A set of activities performed in an organization, coordinated to jointly realize a business goal.

**Three Levels of use** 

 | Modeling type | Description
 -----|----|----- 
Level1 | Descriptive modeling | geared towards simply documenting the process flow – **Our focus in this course**
Level2 | Analytical modeling | More accurate with respect to exceptions and events. Supports qualitative and quantitative analysis
Level3 | Executable modeling | graphical models that can be transformed into XML-based specifications that drive process engines.

**BPMN Level 1 steps:**    
• Determine Process Scope  
• The High-Level Map  
• Top-Level Process Diagram  
• Child-Level Expansion  
• Add Message Flows  

<a name="chapter5.2"></a> 
### 5.2 BPMN Elements
See [lecture five](https://ntnu.blackboard.com/bbcswebdav/pid-483013-dt-content-rid-17800273_1/courses/194_TDT4175_1_2018_H_1/Modeling%20and%20%20BPMN-intro-2018.pdf) & [lecture seven](https://ntnu.blackboard.com/bbcswebdav/pid-500669-dt-content-rid-18273258_1/courses/194_TDT4175_1_2018_H_1/BPMN2-methodandstyle-2018.pdf) for more info about Activities, Tasks, Gateways, Events, etc. 
![](img/Skjermbilde\ 2018-12-13\ kl.\ 15.14.23.png)

<br>
<a name="chapter6"></a>
## 6 Enterprise Architecture
> **"Enterprise architecture(EA)"**  
> is a conceptual blueprint that defines the structure and operation of an organization. The intent of an enterprise architecture is to determine how an organization can most effectively achieve its current and future objectives.


The main reason to develop an Enterprise Architecture is to get an overview of data flow and ISs, and to identify possible economic gains in the various process steps in the business.  

Two problems were addressed by the field of Enterprise Architecture
when it was established: 
 
- **System complexity:**  organiszations were spending more and more money on building IT systems  
- **Poor business alignment:**  organizations were finding it more and more difficult to keep those expensive IT systems aligned with business needs

**The bottom line: more cost, less value.**
![](img/Skjermbilde\ 2018-12-13\ kl.\ 15.55.16.png)

**Role of Enterprise Architecture**
![](img/Skjermbilde\ 2018-12-13\ kl.\ 15.56.23.png)

<a name="chapter6.1"></a>
### 6.1 Zachman
Is a **framework** that provides a formal way of defining an enterprise. It consists of a matrix intersecting six communication questions with five levels of concretisation.

Aspects | Description
----- | -----
Data (what)| Data needed for the enterprise to operate.
Functoin (how)| Concerned with the operation of the enterprise.
Network (where)| Concerned with the geographical distribution of the enterprise’s activities.
People (who)| Concerned with the people who do the work, allocation of work and the people-to-people relationships.
Time (when)| To design the event-to-event relationships that establish the performance criteria.
Motivation (why)| The descriptive representations that depict the motivation of the enterprise. It will typically focus on the objectives and goals.

The Zachman Framework is not a methodology because it does not specify methods for collecting and managing the information it describes. It is rather an ontology; a schema for organizing architectural artifacts.



<a name="chapter6.2"></a>
### 6.2 TOGAF
Or **T**he **O**pen **G**roup **A**rchitecture **F**ramework, is a high level approach framework to designing, planning, implementating and governing an enterprise information architecture. It is modeled at 4 levels:

 | Description
-----|-----
**Business Architecture**| describes the processes the business uses to meet its goals
**Application Architecture**| describes how specific applications are designed and how they interact with each other
**Data Architecture**| describes how the enterprise databastores are organized and accessed
**Technology Architecture**| describes the hardware and software infrastructure that supports applications and their interactions

<a name="chapter6.3"></a>
### 6.3 Enterprise Architecture Modeling
#### ArchiMate
Is an enterprise architecture modeling language. It supports the description, analysis and visualization of architecture within business domains in an unambiguous(*not open to more than one interpretation*) way. It distinguishes itself from other languages, (UML) and (BPMN), by its enterprise modelling scope.

> **"Enterprise Modelling Scope"**
> abstract representation, description and definition of the structure, processes, information and resources of an identifiable business, government body, or other large organization.

![](img/Skjermbilde\ 2018-12-13\ kl.\ 16.18.25.png)

[Important!](http://google.no/search?q=hot+man+santa+claus&rlz=1C5CHFA_enNO570NO575&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiB0r_jkp3fAhWHp4sKHd8aAlcQ_AUIDigB&biw=1444&bih=808#imgrc=_)

<br>
<a name="chapter7"></a>
## 7 Strategic Planning
Strategic planning is a process that helps managers identify desired outcomes and formulate feasible plans to achieve their objectives by using available resources and capabilities. The strategic plan must take into account that the organization and everything around it is changing..

**The following is a set of frequently cited benefits of strategic planning:**   
• Provides a framework and a clearly defined direction to guide decision making at all levels throughout the organization  
• Ensures the most effective use is made of the organization’s resources by focusing those resources on agreed-on key priorities
• Enables the organization to be proactive and take advantage of opportunities and trends, rather than passively reacting to them  
• Enables all organizational units to participate and work together toward accomplishing a common set of goals  
• Provides a set of measures for judging organizational and personnel performance  
• Improves communication among management and the board of directors, shareholders, and other interested parties

![](img/Skjermbilde\ 2018-12-13\ kl.\ 17.20.07.png)

<a name="chapter7.1"></a>
### 7.1 Analyze Situation
All levels and business units of an organization must be involved in assessing its strengths and weaknesses. A multitude of data is gathered about internal processes and operations, including survey data from customers and suppliers and other objective assessments of the organization. The collected data is analyzed to identify and assess how well the firm is meeting current objectives and goals, and how well its current strategies are working.

The most frequently used model for assessing the nature of industry competition is Michael [Porter’s Five Forces Model](#chapter2.1), which identifies the funda- mental factors that determine the level of competition and long-term profitability of an industry 

<a name="chapter7.2"></a>
### 7.2 Set Direction
The direction-setting phase of strategic planning involves defining the mis- sion, vision, values, objectives, and goals of the organization.

<a name="chapter7.3"></a>
### 7.3 Define Strategies
A strategy describes how an organization will achieve its vision, mission, objectives, and goals.

<a name="chapter7.4"></a>
### 7.4 Deploy Plan
The strategic plan defines objectives for an organization, establishes SMART goals, and sets strategies on how to reach those goals. These objectives, goals, and strategies are then communicated to the organization’s business units and functional units so that everyone is “on the same page.” The managers of the various organizational units can then develop more detailed plans for initiatives, programs, and projects that align with the firm’s objectives, goals, and strategies.
