# PetStore_PerformancePoc

**Assignment Overview: Load Testing of Petstore Application** <br />
**1. Introduction:** <br />
Application Overview:
The Petstore application exemplifies modern e-commerce platforms, designed to effectively showcase pet-related products and services with intuitive user interfaces. Developed under an open-source model, Petstore provides a simulated environment where users can browse, select, and purchase items, ensuring smooth navigation and transaction processes.<br />
**2. Application Selection:**  <br />
The Petstore application was selected due to its accessibility as an open-source solution, making it ideal for conducting comprehensive load testing exercises. This choice aligns with the assignment's objectives to evaluate application performance under simulated user loads.
**3. Testing Scope:**  <br />
Scope of Testing: <br />
This assignment targets three critical modules within the Petstore application: product browsing, shopping cart functionality, and checkout process. These modules were chosen to ensure comprehensive coverage of key functionalities crucial for the application's performance assessment.  <br />
Module Selection: <br />
These modules were selected based on their importance in user interaction and transaction flow. Evaluating these areas allows us to gauge the application's scalability, responsiveness, and overall reliability under varying load conditions.  <br />
**4. Tools and Protocols:**  <br />
Tools Used:  <br />
For scripting and execution, LoadRunner with the WebHTTP/HTML protocol was employed. This choice was driven by LoadRunner's robust capabilities in simulating realistic user interactions and load scenarios, essential for accurately assessing Petstore's performance metrics. <br />
**5. Test Execution:**  <br />
The load testing involved simulating 20 concurrent users over two rounds of testing. Each round aimed to test the Petstore application under controlled conditions to measure response times, server performance, and scalability metrics.  <br />
**6. Results and Analysis:**  <br />
Findings from Load Testing:  <br />
The load testing revealed performance metrics such as average response times, throughput rates, and server resource utilization. Identified bottlenecks included server timeouts during high traffic periods and database query latency during checkout processes.  <br />
**7. Conclusion:**  <br />
Key Findings and Recommendations:  <br />
In conclusion, the load testing exercise underscored the importance of rigorous performance testing in ensuring Petstore's reliability and user satisfaction. Recommendations focus on proactive measures to mitigate identified performance bottlenecks and enhance application responsiveness under varying user loads.  <br />
Refer reults documents for more details.  <br />



**Instruction to run**  <br />

To run the load testing scripts for the Petstore application using LoadRunner, follow these instructions:  <br />
1. **Download Scripts:**  <br />
Download the load testing scripts for the Petstore application from the designated location or repository.  <br />
**2. Install LoadRunner:**  <br />
Ensure that LoadRunner (including the Virtual User Generator (VuGen), Controller, and Analysis components) is installed on your local machine. If not installed, download and install LoadRunner from the Micro Focus website.  <br />
**3. Setup and Configuration:**  <br />
Open LoadRunner VuGen and import the downloaded scripts. Ensure all necessary dependencies and configurations (such as server endpoints, credentials, and data files) are correctly set up within VuGen.  <br />
**4. Create Test Scenario:**   <br />
Launch LoadRunner Controller or LoadRunner Enterprise (LRE) depending on your setup.  <br />
**5. Create a new test scenario:**  <br />
Define the number of virtual users (desired user load) to simulate during the test. For example, start with 20 users.
Configure the ramp-up period: Gradually increase the number of virtual users over a specified duration (e.g., 1 minute) to avoid sudden spikes in load.
Set the steady-state period: Maintain the peak user load for a specified duration (e.g., 10 minutes) to simulate sustained user activity.
Configure the ramp-down period: Gradually decrease the number of virtual users over a specified duration (e.g., 1 minute) to simulate users leaving the application.  <br />
**6. Run the Test:**  <br />
Start the test execution in LoadRunner Controller or LRE.
Monitor the test execution to ensure that virtual users are simulating realistic user interactions with the Petstore application.
Observe performance metrics such as response times, throughput, and server resource utilization during the test.
