# PetStore_PerformancePoc

**Assignment Overview: Load Testing of Petstore Application**
**1. Introduction:**
Application Overview:
The Petstore application exemplifies modern e-commerce platforms, designed to effectively showcase pet-related products and services with intuitive user interfaces. Developed under an open-source model, Petstore provides a simulated environment where users can browse, select, and purchase items, ensuring smooth navigation and transaction processes.\n

**2. Application Selection:**
The Petstore application was selected due to its accessibility as an open-source solution, making it ideal for conducting comprehensive load testing exercises. This choice aligns with the assignment's objectives to evaluate application performance under simulated user loads.
**3. Testing Scope:**
Scope of Testing:
This assignment targets three critical modules within the Petstore application: product browsing, shopping cart functionality, and checkout process. These modules were chosen to ensure comprehensive coverage of key functionalities crucial for the application's performance assessment.
Module Selection:
These modules were selected based on their importance in user interaction and transaction flow. Evaluating these areas allows us to gauge the application's scalability, responsiveness, and overall reliability under varying load conditions.
**4. Tools and Protocols:**
Tools Used:
For scripting and execution, LoadRunner with the WebHTTP/HTML protocol was employed. This choice was driven by LoadRunner's robust capabilities in simulating realistic user interactions and load scenarios, essential for accurately assessing Petstore's performance metrics.
**5. Test Execution:**
The load testing involved simulating 20 concurrent users over two rounds of testing. Each round aimed to test the Petstore application under controlled conditions to measure response times, server performance, and scalability metrics.
**6. Results and Analysis:**
Findings from Load Testing:
The load testing revealed performance metrics such as average response times, throughput rates, and server resource utilization. Identified bottlenecks included server timeouts during high traffic periods and database query latency during checkout processes.
**7. Conclusion:**
Key Findings and Recommendations:
In conclusion, the load testing exercise underscored the importance of rigorous performance testing in ensuring Petstore's reliability and user satisfaction. Recommendations focus on proactive measures to mitigate identified performance bottlenecks and enhance application responsiveness under varying user loads.
Refer other documents for more details.



**Instruction to run**

To run the load testing scripts for the Petstore application using LoadRunner, follow these instructions:
1. **Download Scripts:**
Download the load testing scripts for the Petstore application from the designated location or repository.
**2. Install LoadRunner:**
Ensure that LoadRunner (including the Virtual User Generator (VuGen), Controller, and Analysis components) is installed on your local machine. If not installed, download and install LoadRunner from the Micro Focus website.
**3. Setup and Configuration:**
Open LoadRunner VuGen and import the downloaded scripts. Ensure all necessary dependencies and configurations (such as server endpoints, credentials, and data files) are correctly set up within VuGen.
**4. Create Test Scenario:**
Launch LoadRunner Controller or LoadRunner Enterprise (LRE) depending on your setup.
**5. Create a new test scenario:**
Define the number of virtual users (desired user load) to simulate during the test. For example, start with 20 users.
Configure the ramp-up period: Gradually increase the number of virtual users over a specified duration (e.g., 1 minute) to avoid sudden spikes in load.
Set the steady-state period: Maintain the peak user load for a specified duration (e.g., 10 minutes) to simulate sustained user activity.
Configure the ramp-down period: Gradually decrease the number of virtual users over a specified duration (e.g., 1 minute) to simulate users leaving the application.
**6. Run the Test:**
Start the test execution in LoadRunner Controller or LRE.
Monitor the test execution to ensure that virtual users are simulating realistic user interactions with the Petstore application.
Observe performance metrics such as response times, throughput, and server resource utilization during the test.
