

# Description of Tasks for Data Platform Engineer      
Welcome to your onboarding challenge as a Data Platform Engineer position! This task is designed to help you think critically about the role, deepen your knowledge of GitHub Enterprise which is a platform widely used in our company, and tackle practical challenges you'll encounter. If this task seems complex, take your time and approach it step-by-step. If you cannot do all of them, do not fall into despair. Try to do what you can to showcase your aptitude for the position. We look forward to your presentation. And one last note, if you want to use AI tools, that is ok (we use them too) but it is **important** that you understand the solution yourself so that you can explain it to us.

Go into the challenge with the mindset to learn.
We want to see how you tackle complex problems, how you think while solving them, and how you communicate your findings.
Ideally both you while doing the challenge and us listening to your presentation will learn something new.

## 1) GitHub Repository Documentation

As a platform engineer that looks after GitHub Enterprise you need to ensure that people who create new repositories also create certain default community health files. GitHub assigns special significance to these files. They make it easier for collaborators to find them. 

### Goals of this task: 

**Research**: Explore what these health files are and create a list of **a few** recommended documentation files essential for every GitHub repository and specify what content each of this document should include. 

**Demo**: Create a demo repository with these files and present it to us. 

**Enforcement**: You need to enforce that **every** new repository in the whole organization (not just yours) contain these documents and if they do not, they should be disabled. Using GitHub Actions workflow, could you implement a GitHub Action that that does it across the whole GitHub organization? 

**Communication Strategy**: Users in the company currently do not know about these requirements. How could you communicate the above to the users, and what should that communication include? 

During the presentation you may be asked to make some changes to it, therefore make sure you know how to do it. 
 

## 2) Security and Vulnerability Management in GitHub

Security and Vulnerability Management in GitHub focuses on proactively identifying, addressing, and mitigating risks in repositories 

### Goal of this task:

**Code Vulnerabilities**: GitHub has got a ready-made solution to minimize security vulnerabilities of the code stored in GitHub repositories. Research the GitHub security solution and present your findings to us. This part should only take you a few minutes and be high level overview. The goal is to show that you understand GitHub built-in solution that is already there.

**Live demo**: Provided that you have found a GitHub solution for security vulnerabilities, you would like to try it out. Set up a repo, store some code with security vulnerability or vulnerabilities in it, enable GitHub security solution and check if the vulnerability has been discovered. The outcome should be a presentation of the repo together with the mechanism that detects the vulnerability. 

**Growing number of security vulnerabilities** After implementing GitHub security solution to detect security vulnerabilities in GitHub repositories, the number of security vulnerabilities across multiple repositories is growing ie they are being detected by GitHub solution for security vulnerabilities (that you have shown in Live Demo step above) but no one is acting or doing anything with them. You and your colleagues have become concerned about this situation. The goals of this subtask are:

a) decide what types of security vulnerabilities could be tolerated and which ones should definitely be removed.  
b) propose a solution that would improve the situation ie make users act on the security vulnerabilities detected on their repos rather than ignore them. 


## 3) A new company-wide compliance requirement

Our software architects have advised us that some 3rd party GitHub actions used in our GitHub organization are not secure. Up to know, we have allowed users to download actions from [marketplace](https://github.com/marketplace?type=actions). This week we have detected that one of the actions called buggy-actions/expose-passwords contains a very serious vulnerability.   


### Goal of this task:
**Move away from current setup**: The goal here is twofold:
- find out which repositories have been using buggy-actions/expose-passwords action (we have over 500 repositories, so you cannot do it manually)
- propose a solution to prevent such a situation in future (there are many other actions in the marketplace that could have similar or worse vulnerabilities). 

**Communication**: create a communication with the users

**Implement the solution**: Implement your solution in a test GitHub organization and present your finding.


## Final note

Please create a GitHub repository, save all your solutions there and share it with us before the day we meet.

Finally, tasks presented here are a stepping stone to showcasing your research skills and your ability to work with the platform and automate it with tools such as GitHub Actions and programming using Python. We keep our fingers crossed and wish you good luck! Please try to lock this task up to 6-8 hours and remember that asking question is ok, so if you have any let us know.

## Please ignore the part below

## Roles and Responsibilities
[Roles and responsibilities for this project](SUPPORT.md)

## Description
An onboarding challenge as a Junior Data Platform Administrator position

## Documentation
IT-Service Portal und future Github

## Process model
Agile
