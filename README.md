Test project (API) developed using:

   Visual Studio 2019, .Net Core, C#
   Used attribute routing (“api/Questions” and“api/ExampleQuestions”)
   Unit test project added to test the service.


API contains created two endpoints.
   Api/Questions: endpoint created with parent-child relationship for question title and questions under the specific title.
   Api/ExampleQuestions: endpoint created asper case study given. 


The project has implemented a service-repository pattern.

MS Unit is used for the unit test project.

Moq testing is used to test the businesslogic. 

Dockerfile and Run.sh file is located in the “Totaljobs/Totaljobs.Question” folder.


Run.sh has a script to open URLs:
http://localhost:5000/Api/Questions
http://localhost:5000/Api/ExampleQuestions
