### Here is an overview of my Software Development technical contributions at IBM
Generic code details - not domain specific details. Includes details about my contributions, the technologies used, and any significant results or achievements.
# Audit Contribution - GPA-Web Project (2023)

I played a pivotal role in advancing the GPA-Web project during my contribution to the Audit module. GPA-Web, a web GUI, serves as an interactive platform displaying test reports and error messages for individual chip designs. My focus encompassed enhancing both the frontend using React JS and the backend with Node.js, where I crafted dynamic queries and endpoints. Key highlights of my contributions include:

- **A/B Testing:**
  - Conducted A/B testing using a legacy app with known validity and the source database.
  
- **React Hooks Implementation:**
  - Utilized React hooks to fetch and manage data, maintaining it on state within our application and passing it down the component tree as a prop object.
  
- **User Interaction Enhancement:**
  - Implemented a feature enabling users to view test and report links with a simple click on the Cell Name column.
  - Developed modular functions (`handleCellClick` and `handleMacroCellClick`) to capture Grade and Macro clicks in a dynamic table.
  - **`handleCellClick`:**
    - Fetches and manages data using React hooks, enhancing state management.
    - Creates a structured message object with macro and test details.
    - Generates check and audit reports, offering detailed debugging insights.
  
  - **`handleMacroCellClick`:**
    - Creates comprehensive test records for Macro-related tests.
    - Enhances readability by sorting and filtering tests.
    - Generates check and audit reports for selected tests, aiding in debugging.

 
- **Test Record Generation:**
  - Engineered the `createTestDebugRecord` function for comprehensive test record creation from multiple endpoints.
  - Efficiently concatenated audit and check reports, providing detailed insights for debugging.
  - Ensured reliable performance by implementing robust error handling for various scenarios.

- **React Helper Icon Component:**
The React component enhances the GPA-Web project's user interface with dynamic data, a feature to gather current user tokens, display them in a ToolTip, and grant access to read external files.   
   ***Key Functions:***
    - **`verifyHelpers`:**
      - Asynchronously verifies Helpers and filters responses for Helpers running on AFS/GPFS.  
    - **`getCellsWithTokens`:**
      - Retrieves cell values from verified Helpers for user awareness.
    - **`useEffect` for Data Fetching:**
      - Manages asynchronous data fetching for Helper data, verification, and state updates.
      - Handle fetch errors.

  - Improved user experience with real-time Helper availability insights.
  - Enhanced user engagement through dynamic tooltips and color-coded icons for quick user feedback..
  - Contributed to analytics data for GPA module interactions.
  - Ensured efficient data retrieval and handling with modular code design.


## Additional Contributions:
- Implemented robust user interaction tracking for system analytics.

### Continuous Improvement and Code Optimization:
- Actively contributed to continuous improvement initiatives, optimizing code structure and enhancing user-facing features.
- Demonstrated meticulous attention to detail through effective logging and error handling practices.

### Technology Proficiency:
- Showcased proficiency in  modular code design.

### Additional Technical Contributions:
- Enhanced layout, formatting, and filtering for an improved user experience.
- Debugged existing features.
- Integrated `@eda/route-auth` middleware for authentication on both frontend and backend to pass a security audit.
- Updated backend Node.js code for efficient data fetching.
- Utilized React JS to implement an interactive table feature and presented mock-ups in Agile meetings.

# Infrastructure

During my tenure in infrastructure, I collaborated with mentors on a capstone project involving a React JS application to monitor server data. Key achievements:

- GitHub link: [ddServerInspector](https://github.ibm.com/ian-myers-ibm/infrastructure/tree/main/ddServerInspector)
- A/B testing was used to update legacy projects.
- Developed a dynamic MUI card component using `.map()` for servers, sorted and colored by status.
- Developed a dynamic MUI table with custom horizontal bars in cells by utilizing MUI’s `renderCell` method.
- Implemented a multi-tiered navigation bar system for seamless content access.
- Utilized Chart JS to create interactive charts for each server and hosts. Dynamic bar chart & scatter plot.
- Created a graphical hierarchy of projects breakdown and memory allocation per each chip design.
- Utilized Pandas and SQL to extract, process, and analyze data from a MySQL database, demonstrating strong data analysis skills.
- Achieved efficient querying and data retrieval using Pandas DataFrame, showcasing optimization skills for large datasets.
- Utilized `argparse` for command line argument parsing.
- Established a MySQL database connection with a stored password.
- Executed SQL queries to retrieve project metrics.
- Nested loop through SQL with Python to create hierarchical data.
- Created visualizations, including pie charts and tables, using Matplotlib.
  
Server inventory script - To prepare for data migration and upgrading of existing servers. I wrote a bash script to:
  - Cron Job ran hourly for each server listed in database to help catch other automated scripts.
  - Handled conditions for different server architectures (linux & x86).
  - After implementing several filters I extracted all running processes, sub processes, and their owners per each server.
  - Created and populated a table for extracted data.
  - Filtered all rows for unknown or forgotten processes.
    
Policy Warning report
  - Developed a Python script for policy warning reports, showcasing expertise in data manipulation and database interactions.
  - Implemented policy checks, including state management and time-based conditions, to identify inactive servers and potential issues.
  - Enhanced script readability and user-friendliness through well-structured code and informative output messages.
  - Demonstrated proficiency in command-line argument parsing and integration with external data sources for dynamic reporting.
  - Contributed to automated policy enforcement by identifying servers nearing spin-down thresholds, emphasizing practical coding abilities while providing a useful tool.
  
### My commitment to delivering high-quality, optimized, and scalable solutions, coupled with a comprehensive understanding of backend technologies, positions me as a valuable asset in software engineering roles. I am eager to contribute my skills to dynamic projects that demand excellence in database management and backend development. My proficiency is highlighted through the following key achievements:

- **Database Management and Optimization:**
  - Demonstrated expertise in database interaction, schema understanding, and efficient data manipulation. Successfully implemented solutions for creating temporary tables, adding constraints, and optimizing data retrieval.

- **Querying and Filtering:**
  - Strong command over SQL querying and filtering techniques, evident in the use of advanced `SELECT` statements with conditions, joins, and result set sorting. Ensured precision in data retrieval for various scenarios.

- **Data Analysis and Maintenance:**
  - Proven ability in data analysis through the execution of queries for row counting and selective data retrieval. Applied strategic database maintenance practices, including table renaming, to enhance operational efficiency.

- **Duplicate Handling and Integrity:**
  - Implemented robust strategies for handling duplicates, such as using `INSERT IGNORE` and attempting to delete duplicates based on unique constraints. Prioritized data integrity in all database operations.

- **Backend Development Proficiency:**
  - Complemented database skills with broader backend development knowledge. Experienced in Node.js, Django ORM, SQL in Bash and adept at creating solutions for real-world applications.
  - Proven ability to design and implement robust backend solutions using Node.js.
  - Developed generic endpoints for dynamic data retrieval, emphasizing flexibility and scalability.

- **SQL Database Integration:**
  - Successfully interfaced with SQL databases, crafting efficient queries for data analysis and retrieval.
  - Implemented strategies for data manipulation, optimization, and database maintenance.

- **RESTful API Development:**
  - Demonstrated proficiency in creating RESTful APIs to handle diverse requests and optimize data access.

- **Code Modularity and Reusability:**
  - Emphasized code modularity and reusability.

- **Query Optimization:**
  - Applied query optimization techniques to ensure fast and efficient data retrieval, enhancing overall system performance.

- **Parameterized Endpoints:**
  - Leveraged parameterized endpoints for generic and flexible data retrieval.

- **Version Control and Documentation:**
  - Maintained clean and organized codebase, incorporating version control best practices.
  - Ensured thorough documentation for clarity and ease of understanding for future developers.

- **Continuous Improvement:**
  - Actively sought opportunities for code improvement and optimization to enhance system efficiency.

- **Collaborative Problem Solving:**
  - Collaborated effectively with cross-functional teams to address challenges and deliver high-quality solutions.
    
- **Attention to Detail:**
  - Paid meticulous attention to detail in code structure, SQL queries, and overall system architecture.
