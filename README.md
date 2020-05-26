# Automation of Git | GitHub | Jenkins | Dockerfile | Python 
 
## Project description

### Project_Aim
- Use Dockerfile concept for setup the Jenkins_environment and Integrate with various tools to achieve the great use case of automation.
1. Git
2. GitHub
3. Jenkins
4. Docker

### Problem_Statement
1. Create container image that’s has Jenkins installed using dockerfile
2. When we launch this image, it should automatically starts Jenkins service in the container.
3. Create a job chain of job1, job2, job3 and job4 in Jenkins

### Job1 : 
Pull the Github repo automatically when some developers push repo to Github.

### Job2 : 
By looking at the code or program file, Jenkins should automatically start the respective language interpreter install image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed ).

### Job3 : 
Test your app if it is working or not. if app is not working , then send email to developer with error messages.

### Job4:
If container where app is running. fails due to any reason then this job should automatically start the container again.
