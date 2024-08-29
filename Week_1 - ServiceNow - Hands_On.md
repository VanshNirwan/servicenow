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



 
 





