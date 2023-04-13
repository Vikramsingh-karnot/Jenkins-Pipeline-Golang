# go-webapp-sample



## Preface
This repository is the sample of web application using golang.
This sample application provides only several functions as Web APIs.
Please refer to the 'Service' section about the detail of those functions.

Also, this application contains the static contents such as html file, css file and javascript file which built [vuejs-webapp-sample](https://github.com/ybkuroki/vuejs-webapp-sample) project to easily check the behavior of those functions.
So, you can check this application without starting a web server for front end.
Please refer to the 'Starting Server' section about checking the behavior of this application.

If you would like to develop a web application using golang, please feel free to use this sample.

## Install
Perform the following steps:
1. Download and install [MinGW(gcc)](https://sourceforge.net/projects/mingw-w64/files/?source=navbar).
1. Download and install [Visual Studio Code(VS Code)](https://code.visualstudio.com/).
1. Download and install [Golang](https://golang.org/).
1. Get the source code of this repository by the following command.
    ```bash
    go get -u github.com/ybkuroki/go-webapp-sample
    ```

## Starting Server
There are 2 methods for starting server.

### Without Web Server
1. Starting this web application by the following command.
    ```bash
    go run main.go
    ```
1. When startup is complete, the console shows the following message:
    ```
    http server started on [::]:8080
    ```
1. Access [http://localhost:8080](http://localhost:8080) in your browser.
    Login with the following username and password.
    - username : ``test``
    - password : ``test``

![image](https://user-images.githubusercontent.com/56182370/231826560-8d1f9e2e-6bcf-4ac5-8483-3d020ef4e84f.png)
![image](https://user-images.githubusercontent.com/56182370/231827401-a9e2150d-be37-497c-8576-52647e9f5bec.png)

