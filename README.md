# Proedge

Design and build the following: 
1. A frontend which accepts a comma separated list of roll numbers (front end must be in React or Nextjs)

2. On entering the value and pressing submit, a request should be sent to the backend (write a backend api in nodejs to accept this from frontend)

3. From the backend, you have to call an external API to get the pass/fail result, as follows:
http://proedge.me/test.php?rollnumber=123 

In the above, rollnumber is the value to be passed, and it will return pass or fail results. This external API only accepts 1 rollnumber per call.

4. From the backend, when all the rollnumber results are known, return the results to the frontend

5. On frontend, display the roll numbers and their result in a tabular format

6.  Run the above for this input: 5,6,9,12,18,20,25,30,32,36,37,38,40,42,45,47,49,50

Expected solution: 
1. The source code of the frontend and backend to be uploaded to github along with a readme file. 

2. Readme must 
- explain components of the code 
- mention all libraries and plugins used
- list all test cases run along with test data and screenshots

3. Extra points for hosting this solution on heroku or AWS (free tier) or somewhere online
