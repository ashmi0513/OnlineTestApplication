
>> Github repo url: https://github.com/ashmi0513/OnlineTestApplication.git
============================================================================================================

>> Steps Performed:
===========================================================================================================
1. Created a folder named OnlineTestApplication

2. In terminal browse in that folder using: 
command: cd OnlineTestApplication

3. Created new Angular Project and added Router at the time of creation:
command: ng new Resto

4. Installed Json-server to mock database and RESTAPI.
command: npm i -g json-server

5. Created a folder named DB inside OnlineTestApplication.

6. Created db.json file inside DB folder.

7. Updated db.json with candidates data.

8. Inside Index.html, added CDN for Bootstrap
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>

9. Created 6 Components -
CandidateHome, ListCandidates, RegistedCandidates, SelectedCandidates, OnlineExam and ExamInstructions

10. Created a service name CandidateAPI so that it can act as a gateway for communication between components and Json-server.

12. Executed Json-server through command: npx json-server --watch db/db.json

13. Execution provided the url for restapi holding candidates data.

14. Updated the url in CandidateAPI service and wrote code for fetching data from API.

11. Updated rest of the components by putting relevant code into it.

12. Executed the angular project in another terminal through command: ng server


