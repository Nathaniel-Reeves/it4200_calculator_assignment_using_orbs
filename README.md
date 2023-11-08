# it4200_calculator_assignment_using_orbs

## Assignment: Building and Testing a Node.js Project with CircleCI

Objective: The purpose of this assignment is to guide you through the process of setting up notifications to Slack about relevant events in your build pipeline like successes or failures. This assignment will require an oAuth token to allow the Slack bot to communicate with slack. Please get this token from your instructor. Unlike most assignments this assignment will have a hard deadline as the oAuth token needs to be deleted ASAP. You will have a week to get this assignment done from it’s posting date.

## Instructions:

### Part 1: Setting Up the CircleCI Orb 
1. Use the previous project (Calculator App) for this assignment. 
2. Configure the .circleci/config.yml file with the following: 
    - Include the CircleCI/Slack orb from the CircleCI orb registry 
    - Checkout the repository code. 
    - Install project dependencies using npm. 
    - Run unit tests using a testing framework. 
    - Generate a code coverage report using a code coverage tool. 
    - Store the test results and coverage report as artifacts. 
    - Alert on Slack on at the end of your pipeline with a custom message stating “This is <> submitting the slack assignment”

### **Part 2: Documentation 
Write documentation on your process with the assignment and the knowledge gained along with some of the pitfalls to avoid. Include the following points: 
- Documentation should be written in markdown 
- Describe the process of setting up the CircleCI pipeline to handle slack notifications with examples

## Submission Guidelines: 
- Submit your CircleCI YAML files and documentation to GitHub Classroom as well has have your Slack message delivered to the “#general” channel on Slack

## Grading Criteria: 
- Successful message sent to Slack from the Slack Bot. 
- Accurate documentation that would allow another student to reproduce your steps. 
- Accurate and working CircleCI YAML

Note: This assignment is designed to provide hands-on experience in configuring a CircleCI pipeline to use Orbs, third party API’s and communication about the state of your pipeline. Your documentation will demonstrate your understanding of the assignment’s concepts and their real-world applications.
