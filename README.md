# airbnb-clone-project

Team Roles

Business Analyst 

      - Understands customer’s business processes
      - Translates customer business needs into requirements

Product owner (PO)

      - Holds responsibility for a product vision and evolution
      - Makes sure the final product meets customer requirements

Project manager (PM)

      - Makes sure a product or its part is delivered on time and within budget
      - Manages and motivates the software development team

Software architect

      - Designs a high-level software architecture
      - Selects appropriate tools and platforms to implement the product vision
      - Sets up code quality standards and performs code reviews

UI/UX Designer

      - Transforms a product vision into user-friendly designs
      - Creates user journeys for the best user experience and highest conversion rates

Software developer

      - Engineers and stabilizes the product
      - Solves any technical problems emerging during the development lifecycle

Quality assurance (QA) engineer

      - Makes sure an application performs according to requirements
      - Spots functional and non-functional defects

Test automation engineer

      - Designs a test automation ecosystem
      - Writes and maintains test scripts for automated testing

DevOps engineer

      - Facilitates cooperation between development and operations teams
      - Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery

Technology Stack

      - Django : This is a web framework for building RESTful APIs
      
      - MySQL : Stores and manages data
      
      - GraphQL : Provides a flexible and efficient way to interact with APIs, allowing clients to retrieve the exact data they need.
      
      - PostgreSQL : Communicates with the database servers using objects in their code. Defines complex custom data types.

Database Design 

      Users - Details of the user to be visible 

      Properties - Type of property, this means apartment, room, entire house, villa etc

      Bookings - Timeline of booking, reservations. 

      Payments - Type of payment accepted

      Reviews - This is to appear for each property, which is linked to the specific user.

Feature Breakdown

      User Management - Users are securely managed and duplication is avoided through authentication. 

      Property Management - Properties are managed by a centralised system. 

      Booking System - The booking system is seamless and makes sure there is no conflict in dates. 

      Safe Transaction - All transactions are confidentail.

      Information Security - User information is protected, incluing credit card information.

API Security

      Authorisation - This is important for payments. All transactions must be authorised by the user.

      Authentication - User data is crucial, therefore all users will be verified and privileges will be controlled. 

      Rate limiting - The rate must have a limit, to prevent exploitation

CI/CD Pipeline

      CI/CD pipeilines will be crucial for automation of the delivery process.
      Automated testing within the CI/CD pipeline helps identify and resolve issues early in the development process. 

      
