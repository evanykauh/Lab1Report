# How to log into a course-specific account on `ieng6`

## 1. Install VS Code

To download VS Code, go to [vs code download link](https://code.visualstudio.com/) and follow the instructions designed for you're type of computer. There should be versions for all of major operating systems, but if you have something like a chromebook, you won't be able to download it for now. 

When you do have it finally installed, you should be able to open a VS code window like in the image below. 

![vs code](https://user-images.githubusercontent.com/94486303/149598386-314b0d6c-afe1-4df3-8ead-aebde3ae19a9.png)

## 2. Remotely Connecting

Now that we have VS Code, let's use it to connect to a remote computer over the internet.

First, if you’re on Windows: install a program called OpenSSH
- [ssh link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
- This is a program that can connect your computer to other computers that have this kind of account

Second, find you're course specific account. Since I'm in CSE 15L, I will use the link below
- [account link](https://sdacs.ucsd.edu/~icc/index.php)

Finally, use the instructions in the link below to connect to the remote computer using VSCode’s remote option.
- [link](https://code.visualstudio.com/docs/remote/ssh#_connect-to-a-remote-host)

Now open up a new terminal in VS Code. Your command should say "$ ssh cs15lwi22zz@ieng6.ucsd.edu" but with the "zz" replaced by the letters in your course-specific account. And since this is the first time you’ve connected to this server, you will probably get a message like this:

```
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```

Type yes and press enter, then give your password. Once you're logged in, you should see something like this: 

![terminal image](https://user-images.githubusercontent.com/94486303/149599607-ec3c087d-aa01-40ee-994b-090b60e7aaa6.png)






















You can use the [editor on GitHub](https://github.com/evanykauh/Lab1Report/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

