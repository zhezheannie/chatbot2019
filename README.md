# 什麼是Chatbot

聊天機器人(又稱Chatbot)，能夠經由對話或文字與用戶進行交談，透過人工智慧針對使用者輸入的問題、指令，提供相對應的回覆。

# 聊天機器人是如何與使用者互動？

大致可以分為兩類：問答式介面、按鈕式介面。

## 按鈕式介面

透過聊天機器人內建置的預設腳本內容，供使用者選擇。 相較於問答式互動，按鈕式互動提供明確的選擇方向，在使用者開始使用聊天機器人時，避免陷入茫然不知從何開始的窘境。適合電商、零售、媒體產業**運用在：商品介紹、店點查找、文章查詢、引導下載APP**等。

![repo-settings-image](images/chatbot_01.png)

 [Youtube](https://youtu.be/5IlIVZtoeuc)

## 問答式介面

依據使用者輸入內容，透過自然語意分析(Natural Language Processing, NLP) 與設定的關鍵字回覆使用者。適合金融、汽車、房地產、補教等產業**運用在：獲得潛在客戶名單(Leads generation)、問卷調查、抽獎等情境。**

![repo-settings-image](images/chatbot_02.png)

 [Youtube](https://youtu.be/ryN6EBbZJi4)

## Rename this repository to publish your site

We've already set-up a GitHub Pages website for you, based on your personal username. This repository is called `hello-world`, but you'll rename it to: `username.github.io`, to match your website's URL address. If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

Let's get started! To update this repository’s name, click the `Settings` tab on this page. This will take you to your repository’s settings page. 



Under the **Repository Name** heading, type: `username.github.io`, where username is your username on GitHub. Then click **Rename**—and that’s it. When you’re done, click your repository name or browser’s back button to return to this page.

<img width="1039" alt="rename_screenshot" src="https://user-images.githubusercontent.com/18093541/63129466-956cc580-bf85-11e9-92d8-b028dd483fa5.png">

Once you click **Rename**, your website will automatically be published at: https://your-username.github.io/. The HTML file—called `index.html`—is rendered as the home page and you'll be making changes to this file in the next step.

Congratulations! You just launched your first GitHub Pages website. It's now live to share with the entire world

## Making your first edit

When you make any change to any file in your project, you’re making a **commit**. If you fix a typo, update a filename, or edit your code, you can add it to GitHub as a commit. Your commits represent your project’s entire history—and they’re all saved in your project’s repository.

With each commit, you have the opportunity to write a **commit message**, a short, meaningful comment describing the change you’re making to a file. So you always know exactly what changed, no matter when you return to a commit.

## Practice: Customize your first GitHub website by writing HTML code

Want to edit the site you just published? Let’s practice commits by introducing yourself in your `index.html` file. Don’t worry about getting it right the first time—you can always build on your introduction later.

Let’s start with this template:

```
<p>Hello World! I’m [username]. This is my website!</p>
```

To add your introduction, copy our template and click the edit pencil icon at the top right hand corner of the `index.html` file.

<img width="997" alt="edit-this-file" src="https://user-images.githubusercontent.com/18093541/63131820-0794d880-bf8d-11e9-8b3d-c096355e9389.png">


Delete this placeholder line:

```
<p>Welcome to your first GitHub Pages website!</p>
```

Then, paste the template to line 15 and fill in the blanks.

<img width="1032" alt="edit-githuboctocat-index" src="https://user-images.githubusercontent.com/18093541/63132339-c3a2d300-bf8e-11e9-8222-59c2702f6c42.png">


When you’re done, scroll down to the `Commit changes` section near the bottom of the edit page. Add a short message explaining your change, like "Add my introduction", then click `Commit changes`.


<img width="1030" alt="add-my-username" src="https://user-images.githubusercontent.com/18093541/63131801-efbd5480-bf8c-11e9-9806-89273f027d16.png">

Once you click `Commit changes`, your changes will automatically be published on your GitHub Pages website. Refresh the page to see your new changes live in action.

:tada: You just made your first commit! :tada:

## Work with GitHub on your computer using GitHub Desktop

**GitHub Desktop** is a free app from GitHub for Windows and Mac that allows you to easily work with your GitHub repositories from your computer. You just saw how you can commit to a repository from GitHub.com, but most developers do the majority of their work from their computer (locally) before pushing it up to GitHub. So let’s try that out!

[Download GitHub Desktop](https://desktop.github.com/)

## Practice: Use GitHub Desktop and an editor to make a change from your computer

Start by downloading GitHub Desktop if you haven’t already done so, and install it on your computer. Go through the GitHub Desktop onboarding steps, and when you get to the “Let’s get started” screen, go ahead and choose the repository you were just working with on GitHub.com, and click “Clone.”

### Using an editor to make changes

Let’s make sure you have a text editor on your computer - this is what you'll use to actually make changes to your files. If you already know you have an editor, then skip to the next step. Otherwise, download and install either [Visual Studio Code](https://code.visualstudio.com/) or [Atom](https://atom.io/) and restart GitHub Desktop before proceeding to the next step.

Let’s make a change to your GitHub Pages site, just like you did on GitHub.com, except this time we’re going to do it all from your computer. From GitHub Desktop, click the “Open in…” button in the middle of the screen to “open the repository in your external editor” that you just downloaded. 

![Open-in-editor](https://user-images.githubusercontent.com/721500/63188833-82fb9600-c030-11e9-8777-a67c1713d59f.png)

In the left sidebar, click the `index.html` file to open it, and go ahead and add another line. Maybe, “Building websites is fun! You should try it too!” or whatever you want to add. 

![Make-changes](https://user-images.githubusercontent.com/721500/63188832-82fb9600-c030-11e9-9f7b-7d15385a16f0.png)

Now switch back to GitHub Desktop, and you should see the change you made.

![View-changes](https://user-images.githubusercontent.com/721500/63188835-82fb9600-c030-11e9-8980-43a8231ca23a.png)

### Commit your changes

Now you can commit your changes by typing a message in the `Summary` box at the bottom left, and then click the blue `Commit` button below that.

![Commit-changes](https://user-images.githubusercontent.com/721500/63188831-8262ff80-c030-11e9-809a-f87d8b544935.png)

### Push your changes to GitHub.com

One of the great things about working on things on your computer is that you get to control when other people see them. Now let’s push your commit to GitHub.com as well so it’s saved there and you can publish it to your site. Click the “Push origin” button to push your commit to GitHub.com. 

![Push-to-GitHub](https://user-images.githubusercontent.com/721500/63188834-82fb9600-c030-11e9-9d8e-6c6ed6d48504.png)

Now click the “View on GitHub” button to get back to your repository’s page on GitHub.com.

![View-on-GitHub](https://user-images.githubusercontent.com/721500/63188836-82fb9600-c030-11e9-9bc5-cf304398500d.png)

### Deploy and see your changes live on your GitHub Pages website!

Once you commit your changes, they are automatically published on your GitHub Pages website. Refresh your browser to see it live!

### Celebrate!

Hooray! Now you have your repository linked between your computer and GitHub.com. In the future, you can use GitHub Desktop to push any changes you decide to make from your computer.

## Extra Credit: Keep on building!

Change the placeholder Octocat gif on your GitHub Pages website by [creating your own personal Octocat emoji](https://myoctocat.com/build-your-octocat/) or [choose a different Octocat gif from our logo library here](https://octodex.github.com/). Add that image to line 12 of your `index.html` file, in place of the `<img src=` link.

Want to add even more code and fun styles to your GitHub Pages website? [Follow these instructions](https://github.com/github/personal-website) to build a fully-fledged static website.

![octocat](./images/create-octocat.png)

## Everything you need to know about GitHub

Getting started is the hardest part. If there’s anything you’d like to know as you get started with GitHub, try searching [GitHub Help](https://help.github.com). Our documentation has tutorials on everything from changing your repository settings to configuring GitHub from your command line.
