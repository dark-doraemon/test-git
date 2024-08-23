### Online Exam Application

### Description 
Online Exam Hub is a user-friendly platform for creating and taking exams online. It offers customizable test formats, real-time grading, and secure access, making it perfect for educators and students alike

### Features
- Support multi-platform because it runs on the web :))
- Exam management
- Student management
- Account management
- .....
### Requirements
- Nodejs 
- JDK 18+
- VS Code (or other IDE,Code editor)
- SQL Server Management Studio (2022)

> [!IMPORTANT] 
>  How to set up ?

To begin with, your need to download NodeJS at [this link](https://nodejs.org/en) and install it <br>
After install, open your terminal and type <br>
`node -v`<br>
If you see the result like <br>
`v22.4.0`<br>
That means you have installed successfully<br>

Next, you need to install JDK (Java Development Kit).
Go to this [link](https://download.oracle.com/java/22/latest/jdk-22_windows-x64_bin.exe ) to download <br>
> [!CAUTION]
> After you have set up jdk, you need to set path variable<br>

On Windows, search  
> Edit the system enviroment variables <br>

![](https://i.ibb.co/V2xkJ2R/image.png)

Select 
>Enviroment Variables

![](https://i.ibb.co/4W64djq/image.png)

Find
> `Path` and select `Edit`

![](https://i.ibb.co/JyJ5FWg/image.png)

Click
> `New` and it will create a new row for you

![](https://i.ibb.co/sgpqP4W/image.png)

>  Enter the path to your JDK bin directory (Ex: C:\Program Files\Java\jdk<version>\bin).

Mine is  `D:\java\jdk-19\bin`

Finally, open your terminal and type `java --version`. If it shows something like `java 19.0.1 2022-10-18`, you have set up jdk successfully

# Install project 

You can download project at this [link](https://github.com/LeThinhPhuc/Test_Application/archive/refs/heads/main.zip) and extract it <br>
If you have git you can <br>
`git clone https://github.com/LeThinhPhuc/Test_Application.git`

# Start project

Once you install project and extract it, there are 2 folders you should pay attention to, they are `client` and `server`  <br>
Firstly, Open project with vs code (or something else you like to use) <br>
> [!NOTE]
> Client setup

Open Intergrated Terminal in your ide or Windows terminal or Powershell and type `cd .\client\` and hit enter button to move to client folder, continue type command `npm install` and wait a moment <br>
Enter `npm run dev` to run client side

> [!NOTE]
> Server setup
Open your `SQL Server Management Studio` <br>
1. Connect to SQL Server [](https://i.ibb.co/9cx8vfK/image.png)
Open Intergrated Terminal in your ide or Windows terminal or Powershell and type `cd .\server\` and hit enter button to move to client folder


