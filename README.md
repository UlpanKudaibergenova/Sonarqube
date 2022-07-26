# Sonarqube
#### Link: https://github.com/becodeorg/DevSecOps-Training/tree/master/hill/SAST%20-%20SONARQUBE 

### SAST with Sonarqube

Static Application Security Testing (SAST) is a set of technologies designed to analyze application and design conditions that indicate security vulnerabilities. Adopting Static Application Security Testing (SAST) methodology improves application security and helps to reduce the impact of security flaws in application lifecycle. SAST solutions analyze an application in a state of non-execution.

In today's challenge we are going to take a look at SonarQube, an automatic code review tool to detect bugs, vulnerabilities, and code smells in your code. It can integrate with your existing workflow to enable continuous code inspection across your project branches and pull requests.

### The mission
As you might have already guess, your mission today will be integrate SonarQube within your currently existing pipilines (CF: Jenkins and Gitab). You will have to make sure that your perform SAST checks before the release step. Also, you must use the email reporting capabilites of Sonarqube so that you can hava an email report after each checks.

Again, before integrating this into your pipeline, make sure it works in your terminal and interactively.

### Useful link

https://docs.sonarqube.org/latest/ - Sonarqube documentation
