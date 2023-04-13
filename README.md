# CICD Pipeline for go-webapp using Jenkins 



## Preface
This repository is the sample of web application using golang.
This sample application provides only several functions as Web APIs.
In this folder I have written a jenkins pipeline code which helps in integration and deployment 

Also, this application contains the static contents such as html file, css file and javascript file which built [vuejs-webapp-sample]
So, you can check this application without starting a web server for front end.
Please refer to the 'Starting Server' section about checking the behavior of this application.

If you would like to develop a web application using golang, please feel free to use this sample.

## Install
Perform the following steps:
1. Install "Go Plugin" in Jenkins and make changes in global configuration tools for golang. 
1. Create a new pipeline and copy paste the code from jenkinsFile. 
1. build it.  

## Access Aplication from Browser
1. Access [http://localhost:8080](http://localhost:8080) in your browser.
    Login with the following username and password.
    - username : ``test``
    - password : ``test``

##Output snippits

![image](https://user-images.githubusercontent.com/56182370/231826560-8d1f9e2e-6bcf-4ac5-8483-3d020ef4e84f.png)


![image](https://user-images.githubusercontent.com/56182370/231827401-a9e2150d-be37-497c-8576-52647e9f5bec.png)

