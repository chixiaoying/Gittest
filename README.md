# Gittest
测试上传github

测试

~~The C programe language~~
alert("OK")



# Annotation
## Process:realize the goal that use git protocol to send local file to Github under Windows.
### 1.Software preparing
Download two softwares  "Git for windows" and "TortoiseGit".
ps:Just  click "next" and "OK".
### 2.The process of send local file to Github
(1)Create a new directory,paste the file that you want to send in the directory.Then right click the directory->Git Create respository here... -> OK(ps:The content cannnot be emply) ->Then wait a moment ,if it complete, it will show "Initialized empty Git respository in C:\...".
(2)Create a new respository in the Github and open it .Get the path of the HTTPS.(ps:if you have already created one the path is at the ^ next to the  "Clone or download" button).
(3)Go back to the directory and right click it -> Git Commit -> "master" -> Then choose the file -> Add Signed-off-by  -> Commit
(4)Right click the directory  -> TortoiseGit -> push ->manage(at the area of the Destination)  -> Edit the URL and Push URL(use HTTPS path in(2)).  -> OK  ->  OK.

###3.Problem:Error and Warning
(1)exit code 1      exit code 128
Those appeared when I sent another file to the respository that I have send something in.After I searched with Baidu ,I known that when you want to update the respository you must take the lastest versions of the respository in the local directory so you must pull the files from respository to local directory.After this you can send the file to respository.
(2)remote name must not be empty 
When I want to save a origin in the TortoiseGit it appeared.After you save your own origin ,you should choose the option of you saved. 
Solution:click the button with notice  "pull" and "**".
