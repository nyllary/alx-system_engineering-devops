Command Line For The Win

After performing the tasks of solving 27 of the Command Challenge, divided into three sets, nine for each.
I took screen shots of each task after completing.
Saved them into three different folders, nine in each as instructed by the task.

#Creating Readme file
Logged into my webterm, navigated to the tarket directory  and created my readme file with the command "echo 'content' > README.mdd".

#Transfering with SFTP
I then copied the ssh key of my ubuntu. -> Pasted it in my command prompt to log-in at sftp mode. -> Navigated into the remote repository for the project. -> Created the directory for the project (Command: mkdir <directory_name>) -> Navigated into my local directory where the screen shot files were saved (Command: lcd <path>) -> Then I navigated into the remote directory(Command: cd <path>) where the the files will be transfered to. -> Then transfered the files into the remote directry(Command: put -r <path_to_local_directory>).
Because I was transfering a folder, the -r tag makes the files copy into the directory recursively.
Comfirm if the files have been successfully transfered by opening the sandbox directly.
