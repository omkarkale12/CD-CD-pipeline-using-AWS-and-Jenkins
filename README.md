# CI/CD Pipeline 

The repository contains a simple Java application which outputs the string
"Hello world!" and is accompanied by a couple of unit tests to check that the
main application works as expected. The results of these tests are saved to a
JUnit XML report.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline)
you'll be creating yourself during the tutorial and the `jenkins/scripts` subdirectory
contains a shell script with commands that are executed when Jenkins processes
the "Deliver" stage of your Pipeline.
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/c7d91ade3676dde78a1c5a6297b11c4ff4c99a5f/Screenshot%202024-12-23%20165332.png)
Dashboard of Jenkins after installation
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/0740409546657cb9b2bdf96c353c911f68641ac7/Screenshot%202024-12-23%20165630.png)
Creat Pipeline project process
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/3792b2b5e1a273ef830718ef8a543ca00f7b84fe/Screenshot%202024-12-23%20185338.png)
We write the script for Test Build & Deploy purpose
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/3792b2b5e1a273ef830718ef8a543ca00f7b84fe/Screenshot%202024-12-23%20193439.png)
After the script, WE pull java code from the github repository by using gitrepo URL
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/3792b2b5e1a273ef830718ef8a543ca00f7b84fe/Screenshot%202024-12-23%20193612.png)
Run another script for "Test result graph"
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/8a0ffcef5a2640ba41a8e2f3d52fc6927177065c/Screenshot%202024-12-23%20194157.png)
BUuild the pipeline for the "stage view" IN satge view we see the logs of code
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/8a0ffcef5a2640ba41a8e2f3d52fc6927177065c/Screenshot%202024-12-23%20195105.png)
Add scrpt for if code fail "send Email notification to devloper team" & If success show the archive artifact 
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/8a0ffcef5a2640ba41a8e2f3d52fc6927177065c/Screenshot%202024-12-23%20214901.png)
Test result analyzer
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/8a0ffcef5a2640ba41a8e2f3d52fc6927177065c/Screenshot%202024-12-23%20215149.png)

![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/8a0ffcef5a2640ba41a8e2f3d52fc6927177065c/Screenshot%202024-12-23%20215208.png)
All build code result in one formate
![image alt](https://github.com/omkarkale12/CD-CD-pipeline-using-AWS-and-Jenkins/blob/8a0ffcef5a2640ba41a8e2f3d52fc6927177065c/Screenshot%202024-12-23%20215517.png)
