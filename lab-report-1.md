# Lab Report 1
For this lab you will be learning how to setup your CSE15L account for the first time. If needed, you will also be installing Visual Studio Code. These two things will be necessary to practice connecting to a remote server for the very first time!(in this class atleast)



## Setting Up Account for Lab
The first thing to do is to find your specific course account. You can do that here:

[Find Account](https://sdacs.ucsd.edu/~icc/index.php)

1. Log in with your UCSD credentials.
2. Choose your account(make sure to choose the cs15l account as there is a possibility that you have multiple accounts).
3. Follow the on screen instructions to reset your password.

![Image](account_selection.png)

**Personal Experience**
* For me logging in to the website provided was very smooth because I just used my UCSD credentials(as prompted) to log in.
* However when it came to changing my password I had to reset it twice because I forgot it when I was connnecting to the remote server(I'll talk about this later on)

## Installing Visual Studio Code
You will now need something to be able to access a terminal and connect to a remote server. Thus, we will be installing Visual Studio Code. If you don't want to install VScode for whatever reason(I suggest you do) then you can just access it on the CS lab computers.
You can Install Visual Studio code here:

[Visual Studio Code Download](https://code.visualstudio.com/download)

Make sure that you install the correct version depending on your device

![Image](vscode_download.JPG)

After you click download that is specific for your device, you want to follow the on screen instructions. When it is installed you should be able to open a program that looks like the following:

![Image](vscode_starting_page.JPG)

Congratulations! You now have Visual Studio Code installed on your device and don't have to rely on the lab computers. 

**Personal Experience**
* I personally did not have to do this step as I already had VScode installed due to prior CS courses that I took(might be the case for a lot of people).
* One important thing to remember is to make sure to download the version of Visual Studio Code that is meant for your specific device.

## Establishing Remote Access
You have now obtained and installed the necessary tools and information to be able to remotely connect to a server. In this case we will be connecting to the lab computers. We will be using our cs15l accounts to connect to a computer over the internet, could be a remote server. In order to do this we will also be using a terminal within VScode.

However, Windows users you need to take an extra step. If you are on MAC(superior system) you can skip this step. You will need to download **GIT**.
You can download it here:

[Git download](https://gitforwindows.org/)

You will also need to change the terminal in Visual Studio Code to change your terminal to use git that we just installed. Instructions here:

[How to Change Terminal](https://stackoverflow.com/a/50527994)

We will now be able to use `ssh` which will allow us to actually connect to a remote server. You want to first open up a terminal in VScode by going to the menu and selecting **terminal** then **new terminal**. We can now enter a command line with ``ssh`` that will let us connect to a remote server. It will look like this:

``ssh cs15lsp23XX@ieng6.ucsd.edu``

The terminal should then prompt you to enter a password(this password is the one that you just reset earlier on in this lab). Make sure to enter it correctly or it won't let you into the server. 
* **Note**: When you go to type your password, the terminal will not display any of the keys that you press, but it is typing.

Once you type in your password correctly and login the terminal will prompt you with a long text that is asking you to confirm authenticity of the connection to the server or something along those lines. Since it is your first time connecting to the server it will make sure that it is secure to connect your account to it. You want to say **Yes** to this message so that it allows you connect to the server.








  
