# Lab Report Week 6
## Streamlining ssh Configuration
1. Show your .ssh/config file, and how you edited it (with VScode, another program, etc)

![Image](sshFile.png)

2. Show the ssh command logging you into your account using just the alias you chose.

![Image](sshLogin.png)

3. Show an scp command copying a file to your account using just the alias you chose.

![Image](scp.png)

## Setup Github Access from ieng6
1. Show where the public key you made is stored on Github and in your user account (screenshot).

on github:
![Image](onGit.png)

on user account:
![Image](publicckey.png)
contents :
![Image](publicKey.png)
2. Show where the private key you made is stored on your user account (but not its contents) as a screenshot.

on user account (in id_ed25519):
![Image](privKey.png)

3. Show running git commands to commit and push a change to Github while logged into your ieng6 account.

![Image](gitcommand1.png)
![Image](gitcommand2.png)

4. Show a link for the resulting commit.

[link for the resulting commit](https://github.com/leahkuruvila/test-repo/


## Copy whole directories with scp -r
1. Show copying your whole markdown-parse directory to your ieng6 account.
![Image](copying1.png)
![Image](copying2.png)
2. Show logging into your ieng6 account after doing this and compiling and running the tests for your repository.
![Image](ranAfter.png)
3. Show (like in the last step of the first lab) combining scp, ;, and ssh to copy the whole directory and run the tests in one line.

copyinng and ssh:
![Image](copying1.png)
![Image](copying2.png)

run tests one line:
![Image](oneLine.png)

