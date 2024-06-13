# Project Title: Simple PetStore API Performance Testing by JMeter
## Project Name: PetStore

## Objective
PetStore is a dedicated API testing demo that focuses on interactions related to pet data. Testers can scrutinise API endpoints, perform CRUD operations, and ensure data integrity and accuracy within the application. Performance testing was conducted to ensure the API can handle various levels of traffic and to identify its maximum capacity. Click [here](https://petstore.octoperf.com/actions/Catalog.action) to visit this site.

## Prerequisites:

- jdk (Latest LTS)
- Set environment for java JAVA-HOME
- Jmeter
- Set environment for jmeter JMETER-HOME

## How to run?

### Execute following commands:

- `git clone <repo_url>`
- `./jmeter` (For Linux) or
- `.jmeter` (For windows)
  
## How to generate the report
  
### For JMeter 5.1.1 version or higher:
To generate the report in Non-GUI mode, execute the test using the below command:
- For Windows: `jmeter -n -t <your-JMX-file-path> -l log-file-path -e -o Path-fo-output-folder`
- For Linux: `./jmeter.sh -n -t “<your-JMX-file-path>” -l “<log-file-path>” -e -o “<Path-fo-output-folder>”`
  
The output folder contains the generated report in HTML format at the end of the test.

## Tests Conducted
### Load Test
Load testing was conducted to determine how the API performs under expected user loads. The test aimed to identify response times, throughput, and potential bottlenecks.

### Stress Test
Stress testing was performed to determine the API's behavior under extreme conditions. This test helps identify the point at which the API fails or experiences significant performance degradation.

### Capacity Analysis
Capacity analysis was conducted to establish the maximum number of requests the API can handle before its performance becomes unacceptable or it fails.

## Documents
### Excel Reports

[Load Test Report](https://docs.google.com/spreadsheets/d/1D9_IU2n9IpzlKomQBwRrBNMmUJSxD2WM2nUSCvSccUQ/edit?usp=sharing)

[Stress Test Report](https://docs.google.com/spreadsheets/d/1gD_sIs_x0oi8Uu4v2mRTSMSdG3N-ZgELo4mo0sTU7wE/edit?usp=sharing)

## Result
### Screenshots
**Load Test**

![Jmeter Assignment-1Load test](https://github.com/Monira07/random-user-api-performance-test/assets/115618518/9c99ef62-e187-4b67-beb3-7a394ff6f770)


**Stress Test**
