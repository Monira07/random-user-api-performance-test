# Project Title: Simple Petstore API Performance Testing by JMeter
## Project Name: JPetstore Octoperf

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
- For Windows: `jmeter -n -t <your-JMX-file-path> -l &lt;log-file-path&gt; -e -o &lt;Path-fo-output-folder&gt;`
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
### Load Test
https://docs.google.com/spreadsheets/d/1D9_IU2n9IpzlKomQBwRrBNMmUJSxD2WM2nUSCvSccUQ/edit?usp=sharing

### Stress Test
https://docs.google.com/spreadsheets/d/1gD_sIs_x0oi8Uu4v2mRTSMSdG3N-ZgELo4mo0sTU7wE/edit?usp=sharing

## Result
### Screenshots
**Load Test**

![Jmeter assignment 1 load test](https://github.com/Monira07/random-user-api-performance-test/assets/115618518/4c92c369-b37c-43b1-8965-35420d69c5c5)


**Stress Test**

![jmeter assignment 1 stress testing](https://github.com/Monira07/random-user-api-performance-test/assets/115618518/bc558c55-10a6-4671-8d94-e3a770190dd8)
