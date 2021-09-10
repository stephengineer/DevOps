# Hangout Point

## DESCRIPTION

Create an automated test environment for continuous evaluation of the application.

### Background of the problem statement:
An entertainment company like BookMyShow where users book their tickets have multiple users accessing their web app. Due to less infrastructure availability, they use less machines and provide the required structure. This method includes many weaknesses such as:

- Developers must wait till the complete software development for the test results.
- There is a huge possibility of bugs in the test results.
- Delivery process of the software is slow.
- The quality of software is a concern due to continuous feedback referring to things like coding or architectural issues, build failures, test conditions, and file release uploads.

The objective is to implement the automation of the build and release process for
their product.

### Implementation requirements:

1. Set up the Jenkins server in master or slave architecture
2. Use the Jenkins plugins to perform the computation part on the Docker containers
3. Create Jenkins pipeline script
4. Use the GIT web hook to schedule the job on check-in or poll SCM
5. Build an image using the artifacts and deploy them on containers
6. Remove the container stack after completing the job


### The following tools must be used:

1. EC2
2. Jenkins
3. Docker
4. Ansible, Chef, or Puppet

### The following things to be kept in check:

1. You need to document the steps and write the algorithms in them.
2. The submission of your GitHub repository link is mandatory. In order to track your tasks, you need to share the link of the repository.
3. Document the step-by-step process starting from creating test cases, then executing it, and recording the results.
4. You need to submit the final specification document, which includes:
	- Project and tester details
	- Concepts used in the project
	- Links to the GitHub repository to verify the project completion
	- Your conclusion on enhancing the application and defining the USPs (Unique Selling Points)
