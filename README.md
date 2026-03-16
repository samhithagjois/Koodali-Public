**Hello, and welcome to the information repository of Koodali, Namma Kannada Shaale's student administration tool!**

Namma Kannada Shaale is a voluntary organisation based in Munich, Germany, 
which teaches the Indian language **Kannada** (spoken by ca. 110 million native speakers in the state of Karnataka, India) to children of Kannada heritage in Europe over online, as well as in-person classes in Munich, Erlangen and Ingolstadt.

The administration team of the school has been struggling with the growing number of registrations of both students and teachers. 
In the year-end teachers' meeting, the old way of tracking certain areas of administration over chatting platforms like Whatsapp and multiple data spreadsheets on Google sheets was deemed not sufficient and inefficient, and the need for a platform to cover all the different administration needs was expresses.

Koodali is a simple application that provides teachers and administrators a stable database for the following administration needs : 

1. Structural Overview of the school
   - List of students registered, attending, and former students
   - List of teachers registered, teaching, and former teachers
   - Personal information of each student and teacher
   - List of sections (classes) with location and schedule as well as students/teachers in section
2. Trackers 
   - Student attendance tracker
   - Textbook distribution tracker
   - Teacher availability tracker
   - Student homework submission tracker
3. Miscellaneous
   - Homework score leaderboard

Please note that this project is not completed and is still in development.

# Information on the tech stack used in this project :
Client-side
- Java
    - Spring Boot
    - REST API (HTTP calls)
    - Spring MVC (pattern)
    - JpaRepository (database)
    - gradle (building)

Server-side :
- Angular
    - HTML/CSS (templates)
    - TypeScript (Angular framework)

# Models and Diagrams

## UML Class Diagram of the Model (Entities)

![UMLClassDiagram (3).png](UMLDiagrams%2FUMLClassDiagram%20%283%29.png)

## UML Class Diagram of the DTOs used 
![Bridge.png](UMLDiagrams%2FBridge.png)

## Example Communication Diagram of the Repository/Service/Controller interactions
![Communication Diagram.png](UMLDiagrams%2FCommunication%20Diagram.png)

# How to run the project (for now)

- run the Angular CLI server with 'ng serve'
- run the Spring Boot Application with 'gradle run' or the green run button

# Current progress : 
The major features of requirement group 1 (list/information of students, teachers and sections) are fully completed on the server side and at about 80% completed client-side. Angular components like the student profile or the teacher overview are under development.

The features of requirement group 2 (trackers) and group 3 (miscellaneous) are not completed on both server and client side. 

### Contact the development team (me) under : 
- samhitha.girish-jois@tum.de
### Contact the NKS administration team under : 
- admin.nks@nksgermany.com

