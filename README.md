# Star-Internship-Finder
The goal of this project is to design a database management system using Microsoft Access to help students find internships based on location, major, interest, and skills.
## Business Scenario
A local startup, Star, is trying to help college students obtain internships by providing a service
that delivers available internships depending on what the student is looking for. However, they
currently do not have a database management system to keep track of this data. They currently
keep track of their data using pen and paper and realize that this isn’t scalable and is inefficient.
In our business, students can apply for internships depending on many criteria. However, in order
to accomplish this, we will need information for solving this issue, such as data regarding each
internship’s company, position, location, industry, salary, release date, due date, duration, and
link. By having information about internship positions available in each company, Star can post a
variety of internships on our platform instead of having students themselves search for
internships manually.

For the system to work out as planned and for record-keeping purposes, Star needs to keep track
of which company releases an internship along with information that goes along with it like
positions, release and deadline dates, etc. We will also need to store information about students
to keep track of which company they apply to along with their contact information. To
accomplish the goal above, Star will have a unique identifier for each student to keep track of
what internship they applied to. There will also be a unique identifier for the company to keep
track of which company posted an internship on our application. A unique identifier for location
would also be needed for students to locate the area they will be interning in if accepted. In
addition, a unique identifier is needed for a requirement to allow companies to place onto
internships, allowing students who meet those requirements to have a higher chance of being
accepted. A unique position identifier allows students to search for specific occupations they are
interested in applying to. Lastly, each internship requires a unique identifier to keep track of what
company has internship opportunities along with the location, position, and requirement for
students to apply to.

Entities:

● Companies
● Positions
● Internships
● Locations
● Students
● Requirements
