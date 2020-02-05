# SRE/DevOps Online Assessment

(v1.0) The purpose of this test is to evaluate experience using Docker to containerize applications, and deploying such applications on AWS.

This application (app.py) is a simple **Flask 1.1.1** server for **Python 3.7.5**. Once deployed, this Flask web application should be exposed on **port 80**. *You must not modify app.py.*

Your task is to:

1. read instructions / specifications and make a **public fork or clone** of this repository on **GitHub**
2. **containerize** this application with **Docker**
3. be sure to set the necessary **environment variables** referenced in app.py
4. commit and include the completed **Dockerfile** in your repository, as well as any other related files
5. deploy the wrapped application to **AWS**, in any way you choose
6. create and commit a file in your repository named **ip.txt**, which stores *only* the **public IPv4 address** of your instance of the application on the first line, so that we may evaluate the submission quickly with the command **curl $(cat ip.txt)**.
7. **Email / respond with your solution**, which will be:
   * the URL of your GitHub repository, including all required files mentioned above