#        **English Center Management System**
### _System Analysis and Design Project_
![Logo](https://cdn.discordapp.com/attachments/911903170236665857/1148478557136371723/Logo.png)
## 📄 **Project Overview**
This is my personal project, carried out with other team members in the same course. This project is the first step for me to gain knowledge and practical experience in system analysis and design.

## 📋 **Introduction**
- ### Introduction
    - The global demand for English language learning has led to the proliferation of English centers. However, many of these centers struggle with manual or inefficient management processes. As they grow, issues like slow searches, limited functionality, and data errors become more pronounced, impacting their financial performance.
    - To address these challenges, we've developed an application tailored for English center management. Our user-friendly interface and robust features streamline operations, improve the student experience, and enhance communication between teachers and students, ultimately boosting efficiency and performance.
- ### Research problems
    - Many English centers use technology for management, but traditional desktop applications like Excel lack remote collaboration and can pose security risks. They're not automation-friendly, leading to time-consuming tasks. As English centers grow, managing data becomes challenging, causing disorganization and communication issues. Additionally, they don't offer storage for study materials, limiting student access. To address these issues, an application with automation, user-friendly UI, and diverse functionality is essential for efficient management.
- ### Objectives of the project
    Our application was created in order to achieve faster searching for large databases, and improve online communication between teachers and students. Here are some of our app’s main features:
    - Management of enrollment and placement test.
    - Student/Teacher management.
    - User management.
    - Academic management.
    - Classroom management.
    - Academic results management.
    - Revenue, expenditure and finance management.
    - Analysis/report.
    - Data recovery and Backup.
- ### Scope of project | Limitations of the study
    Due to the lack of time, human and expenses, we couldn’t finish all of the features above the objective of our projects. Here are some of our main features that we spent the most time on:
    - Assign user roles to the system.
    - Class, lesson management
    - User management.
    - Course, chapter management.
    - Generate schedule.
    - Attendance tracking.
    - Classroom management.
    - Analysis/Report.
- ### Development tools
    - Visual Studio Code/ IntelliJ IDEA as code editor.
    - Java as the main programming language.
    - Oracle database as database management system.
    - Figma for UI designing.
    - StarUML for UML Diagraming

## 🔎 **Requirement Specification**
- ### Survey of the organization
    ![Survey](https://cdn.discordapp.com/attachments/911903170236665857/1148492582280757330/image.png)
    - _The current organizational situation_
- ### Survey of business processes, major activities
    1. **Board of Directors**
        - **Boards of Directors business**: Collaborate with the Board to establish and monitor the center's financial policies and procedures. Work closely with the Board to develop a strategic plan that outlines the center's goals, objectives, and growth strategies. These plans should align with the mission and vision of the center and provide a roadmap for future development.
        - **Boards of directors works process**:
            - Setting organizational goals and strategies
            - Conducting board meetings
            - Making important decisions
            - Oversight of financial performance
    2. **Business Department**
        - **Student management business**: The student management business of an English center involves various activities and processes to ensure a positive and productive experience for students, including student enrollment, student database management.
            - **Student enrollment managing process**:
                - Handling inquiries
                - Providing information about programs
                - Assisting with application and registration
            - **Student database management process**:
                - Inserting, updating student personal information, enrollment details
                - Tracking student performance
                - Tracking attendance records of students
            - **Marketing business**: Involves activities and strategies implemented to promote the center’s program, services and brand to attract new students.
                English center’s marketing and promotion process:
                - Market research
                - Creating a strong brand identity for the English center
                - Digital marketing
                - Public relations
                - Organizing events, workshops, webinars...
                - Customer Relationship Management
    3. **Accounting-finance department**
        **Accounting-finance department management business**: The accounting and finance department management in an English center involves overseeing financial operations, maintaining accurate records, and ensuring the center's financial health.
        - **Accounting and financial management process**:
            - Financial reporting
            - Expense control
            - Revenue management
            - Financial compliance
            - Financial planning and analysis
            - Cash flow management
            - Auditing and controls
            - Financial forecasting
            - Financial decision-making 
    4. **Human resources department**
    **Human resources department management business**: The human resources department management process in an English center involves managing employees to support the center's workforce effectively. 
        - **Employee management process**:
            - Overseeing recruitment
            - Employee development
            - Performance management
            - Compliance
            - Fostering a positive work culture
    5. **Academic department**
    **Academic department management business**: The academic department involves working around managing documents used for teaching and providing an effective learning environment for students.
    **Teaching document management process**:
        - Creating documents for teaching purposes
        - Organizing documents
        - Updating documents
    
        **Providing an effective learning environment for students**:
        - Fixing issues based on feedback from students
- ### **Software requirements**
    - **Functional requirements**
        **_1. Storage function_**:
        - Account: AccountId, AccountName, Password, role ,...
        - Student: StudentID, UserID, ClassID.
        - Room: RoomId, Name, capacity,...
        - Course: CourseID, name, description, course_level….
        - Chapter: ChapterId, courseID, name, category, description,...
        - Classes: ClassesID, teacherID, name, courseID, date_start, date_end,...
        - Lesson: LessonID, ClassID, LearnDate, ChapterID,..
        - Class Attendance: LessonID, StudentID.
        - Material: MaterialD, LessonID, Path,...
    
        **_2. Searching function_**: 
        - Get information about classes, rooms, courses, users, chapters of each course, lessons of each class.

        **_3. Statistical, report_**:
        - Generate graphs about attendance rate for each lesson in a class and popular courses based on enrollments.
        - Extract reports containing information of classes such as: classID, class name, course name, teacher name, List of Lessons.

    - **Non-Functional requirements**
        - Usability: The application should be easy to learn, navigate, and use for all types of users, regardless of their technical background or language skills.
        - Reliability: The application should be available and functional at all times, with minimal downtime, errors, or crashes.
        - Performance: The application should respond quickly and efficiently to user requests and tasks, even under heavy loads or network conditions.
        - Security: The application should ensure the confidentiality, integrity, and availability of user data and transactions, and prevent unauthorized access, modification, or theft.
        - Maintainability: The application should be easy to maintain, update, and troubleshoot, with clear and concise documentation, coding standards, and version control practices

## 🔎 **Analysis and Design**
| Diagram | GO TO |
| ------ | ------ |
| Use-case Diagram | [link](1.%20Use-case/) |
| Use-case Specification and Activity Diagram | [link](2.%20Use-case%20Specification%20and%20Activity%20Diagram/) |
| Sequence Diagram and Class Diagram | [link](3.%20Sequence%20Diagram%20and%20Class%20Diagram/) |
| Class Diagram and Entity Class Diagram | [link](4.%20Class%20Diagram%20and%20Entity%20Class%20Diagram/) |
| State Diagram | [link](5.%20State%20Diagram/) |
| Mapping to Relational Model from Entity Class Diagram | [link](6.%20Mapping%20to%20Relational%20Model%20from%20Entity%20Class%20Diagram/) |
## 🛠 **Implementation and Testing**
- ### Implementation environment
    - Operating System: Window 11 / MacOS Ventura
    - Database: Oracle database
    - IDE: IntelliJ IDEA
    - Programing language: Java
    - Library: JavaFX, Lombok, PDFBox,..
- ### User Interface
    | Diagram | GO TO |
    | ------ | ------ |
    | User Interface| [link](7.%20User%20Interface/) |

## 🤝 Contribution
    
| Member | Contributions |
| ------ | ------ |
| Le Quoc Khanh | Main developer, System architect and  Project manager|
| Le Gia Kiet | System Analyst and Design, UI/UX Design and Project sub-manager |
| Ninh Thien Bao | Deverloper, Database adminstrator and Reporter |
| Nguyen Thi Thuy | Main Reporter and Testing

## 📧 Contact [Here !](g.kietle@gmail.com)