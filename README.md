# PantryNode-Maintenance-Portfolio
Maintenance Portfolio for the project PantryNode

## **HIGHLIGHTS**


### **1) Pull request: https://github.com/ChicoState/PantryNode/pull/187**

**Description:** The Quagga camera was using the camera even after the stop button was pressed. There were two buttons each for the start and stop button on the screen. The scanner was also not scanning the bar code correctly.I made the changes and created the above pull request which was then approved and merged into main.

The following commits were made in the above described pull request. 

**Commit 1: https://github.com/ChicoState/PantryNode/pull/187/commits/8071564f86dc1bd9174f3aa99bd66aa8f9b4d5a7**

Description: Made changes to the following files:

 frontend/src/Components/Quagga/Header.tsx

 frontend/src/Components/Quagga/index.tsx

 frontend/src/pages/donors.tsx

 frontend/src/styles/quagga.css
 

**Commit 2: https://github.com/ChicoState/PantryNode/pull/187/commits/4a9e55b7832f4cc9edad3e38a5880c5fcf82cb71**
Description: Made changes to the file frontend/src/pages/scanner.tsx


**Commit 3: https://github.com/ChicoState/PantryNode/pull/187/commits/1439a56c4f228f2adc00ea8a2866cdc494553b21**
Description: Made numerous changes to the file frontend/src/App.tsx, frontend/src/styles/quagga.css


**Commit 4: https://github.com/ChicoState/PantryNode/pull/187/commits/e57167f389d40e699944fe3566097ae8507fd186**
Description: Made numerous changes to the file frontend/src/__tests__/donor.test.tsx



### **2) Pull Request: https://github.com/ChicoState/PantryNode/pull/191**    

The following commit was made for the above pull request.

**Commit: https://github.com/ChicoState/PantryNode/commit/5e84775685e21b126b0e330e883ac60814538149**

Description: Instead of rendering a view template, I modified the endpoint to return a JSON response. This involved removing the code that renders the view and replacing it with code that generates a JSON object or serializes our data into JSON format. 
Changed the files index.js, feed.js for removing the code that renders the view and replacing it with code that generates a JSON object.
I have also made changes to the files auth.js at that time in order to bypass the authentication for testing my changes.



### **3) Created the issue:  https://github.com/ChicoState/PantryNode/issues/130**
Description: Replacing the rendering view template in backend with the JSON response. 



### **4) Code Reviews:**
The following code reviews were added by me:

  **https://github.com/ChicoState/PantryNode/pull/110**
 
  **https://github.com/ChicoState/PantryNode/pull/122**
 
  **https://github.com/ChicoState/PantryNode/pull/153**
 
  **https://github.com/ChicoState/PantryNode/pull/196**
 
  **https://github.com/ChicoState/PantryNode/pull/224**



## **TIMELINE**

### **Sprint 1: Weeks 6-7 (February 28 - March 20):**

**Issue: https://github.com/ChicoState/PantryNode/issues/24**

Assigned myself to the above issue.
Started with the discussions about the project with the classmates to discuss the layout and the technologies to be used in the project.

Also started learning the technologies ReactJS and TypeScript from the online sources.

Used the following videos to enhance my knowledge on the technologies:

https://www.youtube.com/watch?v=Rh3tobg7hEo

https://www.youtube.com/watch?v=kq6IhAZVNh8
 
 
 
### **Sprint 2: Weeks 8-9 (March 21 - April 3)**

**Issue: https://github.com/ChicoState/PantryNode/issues/67**

Description: Assigned myself to the issue.
Discussions with the frontend and backend team to collaborate and discuss about the technologies used in order to update the documentation.
The discussion concluded with “Replacing Bootstrap with Tailwind CSS” ; after which I also started learning Tailwind CSS which is a “utility-first CSS framework” as per their own website. I learned various styling ways through Tailwind CSS.


**Issue: https://github.com/ChicoState/PantryNode/issues/68**

Description: Assigned myself to the issue and indulged in the discussions with the other team members to discuss the layout and the road map for the issue and how to proceed. 



### **Sprint 3: Weeks 10-11 (April 4 - 17)**

**Code review :  https://github.com/ChicoState/PantryNode/pull/110**

Description: This code aimed at removing mongoose: 5.9.11 from package.json as we are migrating to PostgreSQL #110.
I reviewed the coding parts and tested if the server was running after this.

**Created the issue:  https://github.com/ChicoState/PantryNode/issues/130**

Description: Replacing the rendering view template in backend with the JSON response. 

**Issue : https://github.com/ChicoState/PantryNode/issues/102**

**Code review :  https://github.com/ChicoState/PantryNode/pull/131#pullrequestreview-1380155984**

**Contributions: https://github.com/ChicoState/PantryNode/pull/125**

Description: Made contributions to the Sale page table issue.

**Code review : https://github.com/ChicoState/PantryNode/pull/153**

Description: Reviewed this pull request which added the API Route for Feed closing.

**Code review : https://github.com/ChicoState/PantryNode/pull/122**

Description: Reviewed and approved the above pull request wherein the README.md file was updated with latest technology stack.

**Issue : Reviewed: https://github.com/ChicoState/PantryNode/issues/143**

Description: Assigned myself to the issue and discussed the layout of the expiry page with the team.
 
 

### **Sprint 4: Weeks 12-13 (April 18 - May 1)**

**Commits: https://github.com/ChicoState/PantryNode/commit/5e84775685e21b126b0e330e883ac60814538149**

Description: Instead of rendering a view template, I modified the endpoint to return a JSON response. This involved removing the code that renders the view and replacing it with code that generates a JSON object or serializes our data into JSON format. 
Changed the files index.js, feed.js for removing the code that renders the view and replacing it with code that generates a JSON object.
I have also made changes to the files auth.js at that time in order to bypass the authentication for testing my changes.


**Pull Request: https://github.com/ChicoState/PantryNode/pull/191**

Description: This pull request was created for the issue 130 created by me for replacing the rendering view template in backend with the JSON response in files. The code changes were made and tested but the pull request is not yet merged with the main.


**Code review : https://github.com/ChicoState/PantryNode/pull/196**

Description: This pull request included a small change in the UI of the expiry page, I reviewed and approved the request after testing the code.



### **Sprint 5: Weeks 14-15 (May 2 - 15)**

**Issue :  https://github.com/ChicoState/PantryNode/issues/184**
Description: Assigned myself to this issue as this was a high priority issue about the scanner page. The Quagga camera was using the camera even after the stop button was pressed. There were two buttons each for the start and stop button on the screen. The scanner was also not scanning the bar code correctly. 


**Pull request https://github.com/ChicoState/PantryNode/pull/187**
The following commits were made by me to resolve the above discussed issued.

These commits included the changes regarding the toggling of the start and stop button. Also dealt with the functionality of the start and stop buttons. Removed the multiple start and stop buttons. Enabled the functionality of the Quagga Camera as it was not working correctly before. Enabled the performance of the bar code scanner. Also, added the header to the page.

**Commit 1: https://github.com/ChicoState/PantryNode/pull/187/commits/8071564f86dc1bd9174f3aa99bd66aa8f9b4d5a7**
Description: Made changes to the following files:

frontend/src/Components/Quagga/Header.tsx

frontend/src/Components/Quagga/index.tsx

frontend/src/pages/donors.tsx

frontend/src/styles/quagga.css

**Commit 2: https://github.com/ChicoState/PantryNode/pull/187/commits/4a9e55b7832f4cc9edad3e38a5880c5fcf82cb71**
Description: Made changes to the file frontend/src/pages/scanner.tsx

**Commit 3: https://github.com/ChicoState/PantryNode/pull/187/commits/1439a56c4f228f2adc00ea8a2866cdc494553b21**
Description: Made numerous changes to the file frontend/src/App.tsx, frontend/src/styles/quagga.css

**Commit 4: https://github.com/ChicoState/PantryNode/pull/187/commits/e57167f389d40e699944fe3566097ae8507fd186**
Description: Made numerous changes to the file frontend/src/__tests__/donor.test.tsx


**Issue : https://github.com/ChicoState/PantryNode/issues/198**
Description: Assigned myself to the above issue to improve the UI of the scanner page.

**Code review: https://github.com/ChicoState/PantryNode/pull/224**
Description: Reviewed and approved the above pull request to check the successful implementation of the expiry page.
