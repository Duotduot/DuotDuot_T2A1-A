1. **Describe the architecture of a typical Flask application**  
A Flask application usually consists of a project directory that contains the application code, configuration files, templates, static assets, and other related resources.At the core of the application, Flask provides the basic infrastructure for handling web requests, routing, and managing the application's lifecycle. It is responsible for managing the application context, request-response handling, and serving static files.Flask uses routes to map specific URLs to functions called view functions or endpoints. These view functions are responsible for handling requests and returning responses. Routes are defined using decorators, allowing developers to specify the URL pattern and HTTP methods.The views in a Flask application contain the business logic for handling requests and generating responses. They typically interact with the database, process data, and render templates to generate dynamic content.Flask uses a template engine, such as Jinja2, to separate the presentation logic from the application logic. Templates are HTML files with placeholders for dynamic data. The view functions pass data to the templates, which are then rendered and sent as responses to the client.Flask applications often incorporate models to represent the application's data and interact with the database. Models are usually implemented using an Object-Relational Mapping (ORM) library like SQLAlchemy, which provides an abstraction layer for database operations.  
2. **Identify a database management system (DBMS) commonly used in web applications (including Flask) and discuss the pros and cons of this database**  
One commonly used database management system (DBMS) in web applications, is PostgreSQL. PostgreSQL is a powerful and open-source relational database system that offers several advantages, but also has some limitations.  
**Pros**  
- **Reliability & Stability**- PostgreSQL is known for its robustness and stability. It has a reputation for being a reliable choice for handling critical data in web applications.  
- **Advanced Features**- PostgreSQL offers a wide range of advanced features, such as support for complex queries, indexing mechanisms, stored procedures, and user-defined functions. These features enable developers to implement complex data operations efficiently  
- **Scalability**- PostgreSQL can handle large amounts of data and high concurrent user loads. It supports parallel processing, which allows it to efficiently distribute the workload across multiple processors or cores  
**Cons**  
- **Complexity**- Its advanced features and capabilities require developers to invest time in understanding and mastering its intricacies.  
- **Memory Usage**- PostgreSQL can consume significant memory resources, especially when dealing with large datasets or complex queries.  
- **Administration**- Managing and configuring PostgreSQL may require more effort and expertise compared to simpler databases. Tasks like setting up replication, backups, and fine-tuning performance parameters might require advanced knowledge. 
3. **Discuss the implementation of Agile project management methodology**  
Agile follows an iterative approach, breaking down the project into smaller increments called "sprints" or "iterations." Each iteration focuses on delivering a working product increment. This allows for regular feedback and adaptability to changing requirements.Agile promotes cross-functional teams comprising individuals with diverse skill sets. These teams collaborate closely throughout the project, fostering effective communication, knowledge sharing, and a sense of collective ownership.The project requirements are captured in a prioritized list known as the product backlog. This backlog is continuously refined and adjusted as new information and feedback emerge, enabling the team to adapt and reprioritize their work.Agile methodologies emphasize close collaboration with stakeholders, including customers and end-users. Their feedback is actively sought throughout the development process, ensuring that the product meets their evolving needs and expectations.  
4. **Provide an overview and description of a standard source control workflow**  
A standard source control workflow typically follows a pattern that includes several key steps. Developers start by cloning a repository from a central version control system, such as Git. They create a local branch to work on a specific feature or fix. Once the changes are complete, they commit them to the local branch. After thorough testing, the changes are pushed to a remote branch. The team then reviews and approves the changes through a pull request process. Upon approval, the changes are merged into the main branch. This workflow ensures that changes are tracked, reviewed, and integrated smoothly, enabling collaboration and maintaining the integrity of the codebase.  
5. **Provide an overview and description of a standard software testing process (e.g. manual testing)**  
The standard software testing process, such as manual testing, involves several key steps to ensure the quality and functionality of a software application. It begins with test planning, where the testing objectives and scope are defined. Test cases are then designed, outlining the specific steps and expected outcomes. Testers execute the test cases manually, carefully following the steps and recording any observed results. They validate the application's behavior, functionality, and user experience. Any defects or issues discovered are reported and tracked for resolution. Regression testing may be performed to ensure that existing functionality is not affected by the changes. The testing process continues until the application meets the desired quality standards, providing valuable feedback to the development team for improvements and bug fixes. Manual testing enables testers to evaluate the software's performance, usability, and adherence to requirements, ensuring a reliable and user-friendly final product.  
6. **Discuss and analyse requirements related to information system security and how they relate to the project**  
Information system security requirements encompass various measures to protect the confidentiality, integrity, and availability of data within the project. This includes implementing access controls, encryption, firewalls, intrusion detection systems, and regular security updates. The project must align with industry best practices and regulatory frameworks such as ISO 27001 or NIST SP 800-53. Compliance with these requirements ensures that sensitive information is safeguarded against unauthorized access, data breaches, and other security threats. Additionally, secure coding practices and regular vulnerability assessments are vital to mitigate risks. The project team must conduct a comprehensive risk assessment to identify potential vulnerabilities and implement appropriate security controls to address them, thereby safeguarding the project's information assets.  
7. **Discuss common methods of protecting information and data and how you would apply them to the project**  
Common methods of protecting information and data include encryption, access controls, regular backups, network segmentation, and strong authentication mechanisms. Encryption ensures that sensitive data is transformed into unreadable format, thereby preventing unauthorized access. Access controls restrict system and data access based on user roles and privileges. Regular backups help to recover data in case of incidents or system failures. Network segmentation separates critical systems from public networks, reducing the attack surface. Strong authentication mechanisms such as two-factor authentication add an extra layer of security. For the project, these methods should be implemented by integrating encryption protocols, role-based access controls, automated backup systems, network segmentation measures, and robust authentication mechanisms to safeguard information and data throughout the project's lifecycle.  
8. **Research what your legal obligations are in relation to handling user data and how they can be met for the project**  
When handling user data, legal obligations may include compliance with data protection and privacy laws such as the General Data Protection Regulation (GDPR) or the California Consumer Privacy Act (CCPA). These obligations generally require obtaining user consent for data collection, implementing appropriate security measures, ensuring data accuracy, and providing users with rights to access, rectify, and delete their personal information. To meet these obligations for the project, it is essential to incorporate privacy by design principles, conduct a thorough data inventory and classification, implement robust data protection measures, establish data retention and disposal policies, and provide clear privacy notices and consent mechanisms. Regular audits and reviews should also be conducted to ensure ongoing compliance with relevant data protection regulations.  
9. **Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.**  
The relational database model organizes data into tables, with each table representing a specific entity or concept. Tables consist of rows (also known as tuples) and columns (also known as attributes). Rows represent individual instances or records, while columns define the attributes or characteristics of those instances. Each table has a primary key, which uniquely identifies each record within the table. Relations between tables are established through keys, such as primary keys and foreign keys. Foreign keys in one table reference the primary key of another table, forming a relationship. This allows for the creation of complex data structures and the ability to retrieve related data by performing joins between tables.  
10. **Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.**  
The relational database model enforces several types of data integrity to ensure the accuracy and consistency of data. These include entity integrity, referential integrity, and domain integrity. Entity integrity ensures that each row within a table has a unique primary key value, preventing duplicate or null values. Referential integrity guarantees that relationships between tables are maintained correctly, with foreign keys referencing valid primary key values. This prevents orphaned or invalid references. Domain integrity enforces constraints on the values that can be stored in specific columns, such as data types, ranges, and formats. These integrity aspects can be enforced through the use of primary key and foreign key constraints, uniqueness constraints, check constraints, and triggers.  
11. **Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.**  
The relational database model provides various operations to manipulate data. The four primary manipulative aspects are adding (inserting), removing (deleting), changing (updating), and retrieving data. Adding data involves inserting new records into tables, specifying values for the appropriate columns. Removing data entails, deleting records from tables based on specific conditions. Changing data is achieved through updating existing records, modifying values in specific columns. Retrieving data involves querying the database using structured query language (SQL) to extract specific records or subsets of data based on conditions or criteria. SQL provides a rich set of commands, such as INSERT, DELETE, UPDATE, and SELECT, enabling developers to manipulate data effectively and perform complex operations like filtering, sorting, and aggregating data.  
12. **Conduct research into a web application (app) and answer the following parts:**  
A. **List and describe software used by the app**  
The web application I chose to work with is Gumtree. Here's a list of the softwares used by the app:  
- HTML - this is a markup language for the structure & content of the website  
- CSS - styling language for website  
- Javascript - scripting language for the website  
- React - libary for user interface  
- Nginx - web server  
- Google cloud hosting - cloud hosting service 
- Java - programming language  

B. **Describe the hardware used to host the app**  
The web server Nginx is one of the hardwares used to host Gumtree. It enables handling and addressing of HTTP requests for content from clients. Gumtree also uses distributed serve networks for cloud hosting(Google Cloud hosting) and content delivery networks(Amazon Cloudfront). Geographic distance separates the servers for Google cloud hosting and Amazon Cloudfront. Because of this, locations near these serves can use these services with decreased latency and travel times.  

C. **Describe the interaction of technnologies within the app**  
When a user requests content from the app, it is sent as a HTTP request to the web server; Nginx. Nginx  then sends back a response which could use a combination of HTML, CSS, Javascript or any other technologies which form the basis for a responsive website. The server might also transfer it to Amazon Cloudfront, which would then try to send it back to the user through the fastest route possible.  

D. **Describe the way data is structured within the app**  
A relational database model is used in the web app, Gumtree. To get into the structure of the data, the tables needed for this web app are User's table, Password and Username. A table for listings is needed too since a user can have one to multiple listings. Listing is one of the main purpose of the web app.  

E. **Identify entities which must be tracked by the app**  
- Users (email, password, name, ratings)
- Contact details (user_id, email, location, phone number, listing_id)
- Listings (price, description, posting date, condition, contact details, product category)
- Ratings (user_id, rating)
- Product categories (category, description)
- Watchlist (listing_id, user_id)
- Messages (user_id, user_id2, message)  

F. **Identify the relationships and associations between the entities you have indentified in part (e)**  
- Users - zero or many listings
- Users - zero or many ratings
- Users - zero or many messages
- Users - zero or many listings in watchlist
- Users - one contact details
- Listings - one product category
- Listings - one user
- Listings - one contact details
- Listings - zero or many watchlists
- Messages - one user
- Ratings - one user
- Product Categories - zero or many listings
- Contact details - one user
- Contact details - zero or many listings
- Watchlists - one user
- Watchlists - zero or many listings  

G. **Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)**  
![ERD diagram](./Docs/erd.png) 

**References:**  
1. https://opensource.com/article/18/4/flask
2. https://dev.to/detimo/python-flask-pros-and-cons-1mlo
3. https://www.wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/
4. https://www.atlassian.com/agile/project-management
5. https://www.postgresqltutorial.com/postgresql-getting-started/what-is-postgresql/
6. https://www.atlassian.com/git/tutorials/why-git
7. https://stackshare.io/gumtree-com/gumtree-com
8. https://www.gumtree.com.au/
9. https://builtwith.com/gumtree.com