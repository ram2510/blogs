---
title: How to automate your Git workflow
published: true
description: A step by step guide to use gitesy
tags: npm, node, git, GitHub 
---

<h1>GITESY</h1>
A node js based cli that can automate your git workflow!!
<center>
<img src="https://thepracticaldev.s3.amazonaws.com/i/kiyjjf11n7sq1q4kfnel.png" />
</center>

Gone are the days when you had to manually create the git repo both locally and remotely.

Now you can create the repo both locally and remotely in 3-4 clicks using <b>"gitesy"</b> 


## Installation

Type this in your command prompt/terminal

```
npm i gitesy -g
```

please note - Install this as a global package otherwise this may not work as expected

---

## Usage 

### Create a new repo
- To create a local and remote repo use gitesy -n command with the name of the repo
  ```
  gitesy -n test
  ```

- After which if you are using this for the first time you will see a prompt for entering your credentials like this
  <img src="https://thepracticaldev.s3.amazonaws.com/i/7iuy5c2sgbb0r0em0d2x.png" />

  Enter them and then you will get prompts asking details of the repo fill them and then it will automatically create the repo. Then you will get the message and start working on the project !!!!
  
 - If you are not using this for the first time you will see a prompt asking whether gitesy can use creds you entered previously
<img src="https://thepracticaldev.s3.amazonaws.com/i/gpz7871kp5p2ec0dn151.gif" />
It's very easy to create a new repo and start coding. I also added the none option too, just for creating an empty git repo both locally and remotely.

### Add a new template
- To Add a template create a template add the features and then use this command from the same directory
  ```
  gitesy -a <nameOfTheTemplate>
  ```
  ![create template demo](https://thepracticaldev.s3.amazonaws.com/i/f3ob1o27x6igr0p09urs.gif)


---

## Epilogue 
You can contribute to this project [here](https://github.com/ram2510/gitesy)

Things you can do 
- fix typos
- add more general templates

Please give me your suggestions they are valuable to me.

Visit the npm page for gitesy [here](https://www.npmjs.com/package/gitesy)

If you like this npm package please share it so that we can make this a better package with suggestions. Thank you !!!!

You can connect with me here at <a href="https://twitter.com/ram2510_" target="_blank">twitter  </a> or <a href="https://www.linkedin.com/in/ram2510/">LinkedIn.</a>

