# api-testing-assignment_5
# API Testing Assignment - JSONPlaceholder

This repository contains the complete deliverables for the API Testing assignment, featuring functional API tests built in Postman and performance/load tests built in Apache JMeter targeting the `JSONPlaceholder` API.

---
 Tools & Technologies Used
* **Postman**: For functional API testing, collection creation, automated assertions, and endpoint validation (`GET`, `POST`, `PUT`, `DELETE`).
* **Apache JMeter (v5.6.3)**: For load and performance testing.
* **JSONPlaceholder API**: `https://jsonplaceholder.typicode.com/`

---

 Repository Contents
* `JSONPlaceholder API Tests.postman_collection.json`: The exported Postman collection containing all functional test requests and test scripts.
* `results_it.jmx`: The JMeter test plan configured for the load testing scenario.
* `result.png`: Screenshot showing successful functional assertions and response payloads in JMeter.
* `summary_report.png`: Screenshot showing aggregate performance metrics (throughput, average response time, and error rate).

---

 How to Run the Tests

### 1. Running the Postman Collection
1. Open the **Postman** application.
2. Click on the **Import** button in the top left corner.
3. Select and upload the `Postman_Collection.json` file from this repository.
4. Once imported, select your environment (or set your `baseUrl` variable to `https://jsonplaceholder.typicode.com`).
5. Run the collection individually or via the Postman Collection Runner to view functional test results.

### 2. Running the JMeter Load Test Plan
1. Ensure you have **Java (JDK)** installed and your `JAVA_HOME` environment variable configured.
2. Download and extract **Apache JMeter 5.6.3** into a directory without spaces (e.g., `C:\apache-jmeter-5.6.3`).
3. Launch JMeter by navigating to your terminal/command prompt and executing:
   ```cmd
   cd C:\apache-jmeter-5.6.3\bin
   jmeter.bat
