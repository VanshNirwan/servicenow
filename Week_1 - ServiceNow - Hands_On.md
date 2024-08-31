# WEEK 1
## What is ServiceNow 
It’s a platform; a piece of technology that lets people automate workflow in a business. It provides a user-friendly interface with various tools such as Global Search, Connect Chat, and Application Navigator. The platform
also includes features like ACLs, UI policies, Business Rules, and Client Scripting for customization and automation.
> ServiceNow is a SaaS provider ans was founded in 2003 by Fred Luddy, It was named as GlideSoft and changed to ServiceNow in 2006.

### Purpose in IT Service Management:

- Incident Management: Helps track and resolve IT issues quickly.
- Change Management: Facilitates planning and implementing changes to IT systems.
- Asset Management: Tracks and manages IT assets throughout their lifecycle.
- Service Catalog: Provides a centralized portal for users to request IT services.
- Knowledge Management: Stores and shares IT knowledge across the organization.
- Workflow Automation: Automates repetitive tasks and processes.
- Reporting and Analytics: Offers insights into IT performance and trends.
## ServiceNow Platform Interfaces
1. Next Experience Unified Navigation
- The Next Experience Unified Navigation is the primary way to interact with applications, records, and data in a ServiceNow instance. Access lists, forms, updates, applications, links, history, workspaces, and landing pages. 
![image](https://github.com/user-attachments/assets/bfbaeccc-fc0a-44d2-9fed-940611d0bd44)
2. Now Mobile App
  - The Now Mobile app enables employees to submit incidents and requests, manage tasks, and access company resources from anywhere! Through the mobile app, a user can also: 
    - Upload images and attachments
    - Sign documents
    - Take surveys
    - View and report issues
    - View and complete tasks
  
![image](https://github.com/user-attachments/assets/1f865751-8153-4ac3-aefc-1ef13951f51a)

3. Service Portal
- The Service Portal provides a user-friendly self-service experience by providing access to specific features using widgets. Service Portal is a great way for external (and existing, legacy) customers to engage with the Platform. When accessing the portal via web browser, type: https//<instance-name-here>.service-now.com/sp. Users can: 
  - Search for articles, catalog items, and records
  - Submit requests
  - Browse the corporate news feed, and more!
![image](https://github.com/user-attachments/assets/90560fa2-43ed-43d0-9fce-dd7c245d9b66)

4. Employee Center
- This dynamic portal improves productivity by reducing time and effort employees spend accessing information across all departments. The Employee Center experience provides a platform for communication, engagement, and content experiences for internal employees.
![image](https://github.com/user-attachments/assets/e331ad7c-ea3c-4f23-80e2-2f951115da1d)

## Now Platform Architecture
When you purchase an instance, it is ServiceNow's responsibility to support the IT infrastructure and compute resources needed to enable and secure that instance.
- Enterprise Cloud
  - Most cloud services are built on a multi-tenant architecture in which your platform and data are co-mingled with other companies. ServiceNOw is build on a **multi-instance architecture**. You have your own instance of the platform and database.
- Availability & Redundancy
  - All ServiceNow datacenters are paired with another datacenter to provide redundancy and failover. **Redundancy is built into every layer** including devices, power, and network resources.
- Backups & Security
  - ServiceNow provides **4 weekly full data backups** and **6 days of daily differential backups**. The entire platform is secured using multiple technologies which have been certified by third-party security organizations.
- Domain Separation(multi-tenancy)
  - The ServiceNow platform provides the ability to separate data, and administrative tasks on an instance into logical groupings called domains.
    - All users can potentially see records from the 'global domain', but only users who belong to a domain can see domain-specific records.
## Navigating the ServiceNow Platform and Mastering ServiceNow User Interfaces
![image](https://github.com/user-attachments/assets/2a70d546-8c27-470e-9bb2-e2c0b527b8c3)

**1. Banner Frame**
- It consists of several menus such as All menu, Filter Navigator, Pinning menus, History menu, Workspaces menu.
  - _ALL menu_
    - The All menu provides access to all applications and modules they contain. An application is a group of modules (or pages) that provide related information and functionality in an instance. For example, you'll work in the Incident application in this course, which contains modules for creating and viewing incidents.
    - ![image](https://github.com/user-attachments/assets/253a45be-3ab6-4044-a2a4-d88fd6c2fa7e)
  - _Filter Navigator_
    - The Filter Navigator is where you can quickly navigate to applications and modules. Simply begin by typing the application or module name (all, or part of, any module name). For example, if you were to search Service Catalog, you can start to type, "Service Cat" and all applications with the keyword will display.
    - ![image](https://github.com/user-attachments/assets/1dca6bdd-73c7-468d-8c21-c73b83238cdc)
  - _Pinning menus_
    - With Next Experience, when you select a menu, it will display as a temporary semi-transparent menu. If you want the menu to persist, select the Pin icon. This will place (pin) the menu to your content frame. You can also un-pin the menu by selecting the Pin icon again.
    - ![image](https://github.com/user-attachments/assets/d92e9f62-69f8-4d4b-ab83-8c8d06810984)
  - _Adding and customizing favorites_
    - Selecting the star icon next to an application or module will create a Favorite menu item. Favorites can be re-ordered, edited, or removed from the menu by selecting the Edit (pencil) icon. 
To re-order a favorite item, select the pencil icon first to edit it, then click and drag the item (or select the icon with six dots) to whichever order you'd like! 
To change the name, color, and icon of a favorited item, select the item and change one or all three options! 
While editing a favorited item, don't forget to Save your edits (select Save edits) before exiting the Edit your favorites window.
   - ![image](https://github.com/user-attachments/assets/9f34498f-99c3-4f55-887d-d0f9625771aa)
  - _History Menu_
    - Select the History menu, then select any recent activity to open the item in the Content Frame. By default, the maximum number of items displayed in the History tab is 30. 
The system creates history entries for many types of content including lists, records, and homepages. Some content types are not tracked in the history, such as UI pages and other non-standard interfaces.
   - ![image](https://github.com/user-attachments/assets/0f8ee2b6-2ede-4ec5-b6c6-b28c0207b5c5)

**2. Application Navigator**
![image](https://github.com/user-attachments/assets/56c621a8-0089-477e-baa5-8ac2e7b783df)

Navigating the ServiceNow platform effectively involves understanding its various user interfaces, from the Application Navigator to the Agent Workspace, and leveraging its tools for personalization, customization, and automation. By mastering these elements, users can optimize their productivity, streamline workflows, and maximize the value they derive from the platform.
## ServiceNow Lists and Filters
### ServiceNow List View:
 -  The List View in ServiceNow displays records from a table in a tabular format, allowing
users to view, search, and manage data efficiently. It provides a structured view of
records, with columns representing fields and rows representing individual records.
### Interface, Standard Paradigm:
 - In ServiceNow, the interface follows a standard paradigm that emphasizes consistency,
usability, and efficiency. This paradigm includes elements like lists, forms, and
dashboards, designed to provide a unified user experience across the platform. The
interface supports easy navigation and interaction with data, using familiar controls and
layouts.
### List Control
 - List Controls in ServiceNow are tools available within the List View that allow users to
manage how data is displayed and interacted with. These controls enable actions like
adding filters, sorting, grouping, and exporting data, providing users with flexibility in how
they handle the information in a list.
### Filter Conditions:
 - Filter Conditions in ServiceNow are criteria set by users to refine the data displayed in a
List View. By applying filter conditions, users can narrow down records based on specific
field values, such as date ranges, statuses, or other attributes, helping them to focus on
relevant data.
### Refresh List:
 - The Refresh List function in ServiceNow updates the data displayed in the List View.
This ensures that users see the most current information, reflecting any recent changes
or updates made to the records. Refreshing a list is crucial for keeping the displayed
data synchronized with the actual state of the database.
## Forms in ServiceNow
Forms are user interfaces in ServiceNow that allow users to enter, view, and modify data
in records. They are essential for interacting with data stored in the ServiceNow
platform.
### The Standard Layout
The standard layout of a ServiceNow form typically includes a header section with key
information (e.g., record number, status), followed by form fields organized into sections
for input and display.
### Form Field Types
ServiceNow forms can contain various field types, such as text fields, choice lists,
reference fields, checkboxes, and date pickers, each designed for specific types of data
entry.
### Saving Changes:
Users can save changes made to a form by clicking the "Save" or "Update" button,
which commits the modifications to the database.
### Insert/Insert & Stay:
"Insert" saves a new record and returns the user to the previous page, while "Insert &
Stay" saves the new record and keeps the user on the same form for further editing.
### Form Sections:
Forms can be divided into sections to organize related fields logically. This makes it
easier for users to find and input data relevant to different aspects of a record.
### Related List & Formatters:
Related lists display related records from other tables, while formatters add special
visual elements or widgets to a form, such as activity streams or approval summaries.
### Form Views:
Form views are different layouts of a form, each tailored to specific roles or purposes.
Users can switch between views depending on their needs, displaying only the relevant
fields and information.
### Form Personalization:
Users with the appropriate permissions can personalize forms by adding, removing, or
rearranging fields and sections to suit their workflow needs.
### Adding Attachments:
Users can attach files, images, or documents to a form, allowing for additional context or
supplementary information to be stored with the record.
### Form Templates:
Form templates are pre-defined forms with specific fields and values filled in. They help
users create records faster by providing a starting point for common tasks or requests.
### Creating and Editing Views:
Administrators can create and edit form views to customize how forms are presented to
different user groups, ensuring that users see the most relevant information for their
roles or tasks.

## Data Imports and Integrations
The process of importing data normally involves pulling data from a **Source** data enitity and loading it into a **Target** data entity.</br>
In ServiceNow, the import process introduces an intermediary data entity between those two steps. We will refer to that entity simply as **Staging**(ServiceNow calls it an Import Set Table). That entity is an automatically created custom table that is used to stage the imported data prior to processing and loading into the Target. It enhances the performance of the import and provides a useful tool for designing field-level mappings and data transformations.
So, a ServiceNow import actually involves 3 data entities:

1. **Source**
   - The entity containing the data to be imported into ServiceNow
   - ServiceNow is prepared to work with many sources including files(Excel, CSV, JSON, etc.), JDBC-compatable databases, LDAP, REST, and custom scripts
2. **Staging**
   - A table that ServiceNow automatically creates as part of the import process to temporarily store data pulled from the source prior to transforming and adding to the Target
   - Enhances the performance of the import and provides useful tools for designing field-level mappings and data transformations
3. **Target**
   - The ServiceNow table into which the data will be imported
   - This could be an out-of-box ServiceNow table or a custom table created specifically for our purposes

## Creating a Data Source in ServiceNow
All the data Source records are present in sys_data_source table, or you can access by</br>
navigation</br>
All - System import Sets - Administration - Data Source</br>
Creating a data Source</br>
From Sys_data_source table select new and fill the from</br>
Then Submit and go to attachments and attach the form you want to give as a data</br>
## Understanding Import Sets in ServiceNow
In ServiceNow, Import Sets are tools used to import data from various sources into the platform.
They allow organizations to bring in external data and then transform and map it to the
appropriate tables within ServiceNow.</br>
### Creating Import Sets:
1. Data Source Definition:
 - First, define a data source from which the data will be imported. This could be a
file (like CSV, Excel), a database, or even an integration with an external system.
2. Loading Data:
 - Once the data source is defined, the data is loaded into a temporary staging
table, known as an Import Set Table in ServiceNow. Each record in the imported
data becomes a row in this staging table.
3. Transform Map Creation:
 - A Transform Map is then created, which is a set of instructions that tells
ServiceNow how to map fields from the Import Set Table to fields in the target
table (the table where the data ultimately needs to go).
 - During this step, you specify which fields in the import set correspond to which
fields in the target table.
### Transforming and Mapping Data:
1. Field Mapping:
 - Within the transform map, you map individual fields from the Import Set Table to
the target table. For example, if you're importing user data, you might map the
"First Name" field in the import set to the "First Name" field in the User [sys_user]
table.
2. Transformation Rules:
 - You can define additional transformation rules or scripts to manipulate data
during the transformation process. For instance, you might convert a date format,
combine multiple fields into one, or perform a lookup to match records based on
specific criteria.
3. Running the Transformation:
 - After the mapping and rules are set, you run the transform map. This process
moves the data from the Import Set Table to the target table in ServiceNow,
applying any transformation rules defined in the process.
### Benefits of Import Sets:
● Flexibility: Import Sets provide flexibility in how data is brought into ServiceNow, allowing
for the transformation of data to fit the platform's data structure.</br>
● Custom Mapping: Individual field mapping allows for precise control over where and how
data is placed in the target tables.</br>
● Error Handling: The platform offers error handling and rollback mechanisms, so if
something goes wrong during the import, it can be addressed without affecting the target
data.
## ServiceNow Transform Maps & Field Maps
Importing, transforming, and mapping data into ServiceNow involves several key steps to
ensure that external data is accurately and efficiently integrated into the platform's database.
### 1. Importing Data:
  - Data Source Setup: Begin by defining the data source from which the data will be
imported. This can be a file (such as CSV, Excel), a database connection, or an API
integration.
  - Import Set Table: ServiceNow loads the data into a temporary table called an Import
Set Table. This table acts as a staging area where the imported data is stored
temporarily before being processed further.
### 2. Transforming Data:
  - Transform Map Creation: After the data is imported, a Transform Map is created to
define how the data in the Import Set Table should be transformed and where it should
go in the target tables.
  - Data Transformation Rules: During this process, you can define transformation rules
that manipulate the data, such as converting formats, merging fields, or applying
conditions to ensure the data meets specific criteria before it’s moved to the target table.
### 3. Mapping Data:
  - Field Mapping: Within the Transform Map, you map fields from the Import Set Table to
fields in the target table. For example, a "Username" field in the import set might be
mapped to the "User ID" field in the ServiceNow User [sys_user] table.
  - Running the Transformation: Once the mappings and transformations are set, the
transformation process is executed. This process takes the data from the Import Set
Table, applies any defined transformation rules, and then inserts or updates records in
the target table.</br>
**Benefits:**
  - Data Integrity: This process ensures that imported data is correctly formatted and
mapped to the appropriate fields, maintaining the integrity and consistency of the data
within ServiceNow.
  - Customization: The ability to define custom transformation rules and mappings
provides flexibility, allowing organizations to tailor the data import process to their
specific needs.

## ServiceNow Incident Management Tutorial and Task Administration
### Incident Management
- Manages lifecycle of incidents (unplanned IT service interruptions)
- Incident tickets created manually or automatically
- Automatic task assignment based on rules
- Focus on quick resolution and closure
### Problem Management
- Identifies and manages root causes of incidents
- Problem tickets created from recurring incidents or proactive analysis
- Involves tasks like root cause analysis and solution development
- Teams collaborate on problem tasks for resolution
### Change Management
- Controls and manages IT service changes systematically
- Change requests (CRs) include impact, risk, and implementation details
- Task assignment and approval workflows for changes
- Changes implemented, reviewed, and documented</br>
**Task Creation and Management**
  - Task Creation
     - Tasks created within incidents, problems, or changes
     - Represent specific work to be completed
     - Can be automatically generated or manually created
  - Task Assignment Rules
     - Automatic task assignment based on predefined criteria
     - Criteria include task type, impacted service, location, or required skills
  - Task Collaboration
     - Facilitates real-time collaboration among team members
     - Allows communication, document sharing, and progress tracking
  - Visual Task Boards
     - Provides a drag-and-drop interface for managing tasks
     - Tasks displayed as cards on a visual board
     - Users can move cards through workflow stages (e.g., "To Do," "In Progress,"
"Done")

## What is Low Code No Code Development?
**Low Code/No Code Software Development** refers to a software development approach that
enables users to create applications with minimal or no coding skills. It uses visual development
environments, drag-and-drop interfaces, and pre-built components to simplify the process of
building software.
### How it Works:
 - **Visual Development:** Users design applications through visual interfaces, often
dragging and dropping elements like forms, buttons, and workflows.
 - **Pre-built Components:** Platforms offer a library of pre-built components, templates, and
connectors, which can be used to quickly build functionality without writing code.
 - **Automation and Integration:** Low code/no code platforms often include tools for
automating processes and integrating with other systems, making it easier to connect
various applications and services.
 - **Customization:** While many elements are pre-built, users can usually customize them
to meet specific needs. Advanced users may also be able to add custom code for more
complex features.
### Pros:
● Speed: Applications can be developed much faster than traditional coding methods,
enabling rapid prototyping and deployment.</br>
● Accessibility: Non-developers, such as business analysts or managers, can create
applications, reducing reliance on specialized developers.</br>
● Cost-Effective: Reduces development costs by lowering the need for extensive coding
and reducing development time.</br>
● Scalability: Many platforms offer scalable solutions, allowing businesses to grow their
applications as needed.</br>
● Collaboration: Encourages collaboration between IT and business users, as both can
participate in the development process.</br>
### Cons:
● Limited Customization: While low code/no code platforms are flexible, they may not
offer the same level of customization as traditional development, especially for highly
complex or unique requirements.</br>
● Vendor Lock-In: Businesses may become dependent on a particular platform, making it
difficult to switch vendors or migrate applications to other systems.</br>
● Performance: Applications built on low code/no code platforms may have performance
limitations, particularly for very large-scale or complex applications.</br>
● Security: There might be concerns about the security of applications, especially if the
platform does not provide adequate security controls or if users are not fully aware of
best practices.</br>
● Complexity in Advanced Use Cases: While easy to start with, low code/no code
platforms can become challenging when trying to implement highly specific or advanced
features.</br>
### Career Opportunites:
● Low Code/No Code Developer: Specialists who focus on using these platforms to build
applications, often within a specific platform like ServiceNow, OutSystems, or Microsoft
PowerApps.</br>
● Business Analyst: Professionals who bridge the gap between business needs and IT
capabilities, often using low code/no code tools to prototype and build solutions that
meet business requirements.</br>
● Citizen Developer: Non-technical professionals who use low code/no code platforms to
create applications that solve specific business problems without needing to rely on
traditional development teams.</br>
● Platform Specialist/Administrator: Individuals who manage, configure, and optimize
low code/no code platforms within an organization, ensuring they are used effectively
and securely.</br>
● Consultant: Advisors who help organizations implement low code/no code solutions,
offering expertise in selecting the right platform, training users, and guiding development
best practices.</br>
</br>
Low code/no code development is growing rapidly, offering a range of opportunities for those
interested in software development, business process automation, and digital transformation. It
enables more people to participate in the creation of applications, making it an attractive field for
both technical and non-technical professionals.


