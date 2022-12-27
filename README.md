# CI-CD

## 1. What is needed to implement continuous integration and what benefits does it bring?

### The basic prerequisites for implementing continuous integration include:

1. Automating builds.

2. Automating testing.

3. More frequent commits to a single source code repository.

4. Providing visibility of the process and real-time access to CI status to the team.

### major phases of CI:

1. Commit: The developer commits code regularly to the version control system.

2. Build: The code is then built using suitable build tools to obtain an artifact. 

3. Unit Test: The developer generally writes unit tests to test functionalities at ground level. These are run along with the build. 

4. Deploy to Development Environment: The build is then deployed onto a common Development Environment where devs can test how their code works when combined with other developers’ code.

### benefits:

1. "No merge hell".

2. Keeps developers productive.

3. TIt gives us a constantly testable build.

## 2. What is the difference between continuous delivery and continuous deployment?

They are vey similar. Continuous delivery is just a little bit more cautious than deployment.

*<strong>Continuous delivery</strong> means that you had deploying often using automation but it may involve a manual step for example when you will need to approve a deployment. Despite this manual step, deployment itself is still automated and can be repeated, also is safe to do.

*<strong>Continuous Deployment</strong> is full automation, every code change is deployed all the way to production. It means there's no manual intervention of approvals.

## 3. What role does test automation play in continuous delivery?

1. Reduces manual efforts when the same test must be run repetitively. This frees up more time to perform rigorous manual tests.

2. Gives immediate feedback.

3. Tests can be more accurate and cover more test cases.

4. Helps generate and compare multiple test results, ensuring product consistency. 

<strong>continous delivery</strong>-"how do I quickly get code into production"
In continous delivery we use technology like Jenkins CD to automate deployment.

## 4. What is GitOps and how it is related to CI/CD?

*GitOps is an operational framework that takes DevOps best practices used for application development such as version control, collaboration, compliance, and CI/CD tooling, and applies them to infrastructure automation.

*GitOps uses Git repositories as a single source of truth to deliver infrastructure as code. Submitted code checks the CI process, while the CD process checks and applies requirements for things like security, infrastructure as code, or any other boundaries set for the application framework.

## 5. Which open-source tools are frequently used for CI/CD automation?

1. Jenkins

2. Gradle

3. GitLab

4. CodeShip

5. Buddy GoCD

## 6. What tools does public cloud providers (AWS, GCP, and Azure) offer for the same purpose?

*Their cloud platforms - AWS, Azure, and GCP offer clients various storage, computing, and networking options. Some features common to the three platforms include self-service, instant provisioning, security and compliance, and identity management.

*There are some tools that can be used on all three cloud platforms. For example you can use Terraform to create a single script that works on all of them. 

