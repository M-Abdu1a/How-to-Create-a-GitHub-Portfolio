# 📚 How to Create a GitHub Portfolio

Hi, I'm Muhammad Abdullah! 👋🏻 This is a **fuss-free** guide to create your GitHub portfolio. 

It's perfect for:
- Beginners in data science looking to showcase samples of work or projects.
- Serves as a digital resume to demonstrate your technical skills. 
- A fun way to track your projects.

**Why I created this repo?**
- I used to find GitHub intimidating. When I first signed up, I didn't understand how it worked and ended up leaving it aside. 
- Since then, I've become quite obsessed with writing in Markdown 😆 and have learned how to use it. Now, I'm excited to share this knowledge with everyone. 🙂

## Table of Contents
- [How to Create Your Profile?](#how-to-create-your-profile)
- [How to Customize Markdown files?](#how-to-customize-markdown-files)
- [How to Create New Repository?](#how-to-create-new-repository)
- [How to Create Subfolders in your Repository?](#how-to-create-subfolders-in-your-repository)
- [How to Upload Projects in your Repository?](#how-to-upload-projects-in-your-repository)
- [How to Fork a Repository?](#how-to-fork-a-repository)

## Introduction 

Let's start by understanding some of the terms you'll come across on GitHub:

📌 `Repository` (or `repo`) means `folder`. Each repository represents a folder on your computer. You can create multiple repositories for different projects. 

📌 `README.md` is a default note or summary that's usually included in each repo. It acts as the "homepage" of your repo where you can introduce the project, provide a summary, or anything else.  

📌 `Fork` means `copy + paste` in layman's terms. Let's say you want to make a copy of this guide, have access to it, and edit it. Any changes you make in your copy won't affect the original guide.

You don't need GitHub Desktop to set up your portfolio. Your browser will do the job just fine. 🙂

***

## How to Create Your Profile on GitHub?

Interested in creating a personalized profile that appears on your GitHub homepage? Follow these simple steps:

<kbd><img width="1203" alt="Screenshot" src="https://user-images.githubusercontent.com/81607668/135101992-9590fe01-fbbf-4c5e-9092-f0eed8114334.png"></kbd>

**Step 1:** Click on `+` sign and select `New Repository` at the top right corner of the page.

<kbd><img width="257" alt="image" src="https://user-images.githubusercontent.com/81607668/135068335-12538e85-8090-4f27-8232-47bfcc15b2c2.png"></kbd>

**Step 2:** Create a new repository with the _exact same name as your username_.  

For example, my GitHub username is "**M-Abdu1a**", so I created a repository named "**M-Abdu1a**". This will contain the write-up of your profile.

<kbd><img width="741" alt="Screenshot" src="https://user-images.githubusercontent.com/81607668/135102196-6eeea30a-a874-4fb3-a4f6-25db97d6c825.png"></kbd>

The file format for the profile is `Markdown (.md)`. By default, the file is named `README.md`, so you can leave it as is. 

<kbd><img width="720" alt="Screenshot" src="https://user-images.githubusercontent.com/81607668/135102549-9bc47d7f-d803-4cc2-a8a2-361c900a6b96.png"></kbd>

**Step 3:** To edit your Profile or Markdown file, click on the pencil `✏️` icon on your right and select `Edit this file`.

<kbd><img width="354" alt="Screenshot" src="https://user-images.githubusercontent.com/81607668/135107847-f86bef5c-2f26-4942-9de2-104c446825e1.png"></kbd>

Now, start writing your profile! 😄 Once you're done, scroll down and click `Commit changes`.

### 📝 What to write in Your Profile?

- A brief introduction of yourself.
- Your skills, e.g., data analysis, SQL, Python, Tableau, web development, etc.
- Advanced features like visitor counts or clickable icons (optional).  
- Your projects that you're proud of.

Resources for inspiration:
- [GitHub's guide on managing your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)  
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

***

## How to Customize Markdown files?

- [GitHub's basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  
- [Guide to organizing tables](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)  
- [Guide to code blocks](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)  
- Add emojis 🌟🙌🏻📚🌤🐶 using:
  - Windows: Windows key + .  
  - Mac: Control + Command + Spacebar

***

### 🌌 To Add Images

1. Take a screenshot or download the image.  
2. Copy the image into the Markdown file and wait a few seconds for it to load.  

<kbd><img width="619" alt="image" src="https://user-images.githubusercontent.com/81607668/135247149-4cddb744-cc6e-4b20-92fa-fd768da95d7f.png"></kbd>

3. Use the `<kbd>` tag to frame the image.  
4. Click `Preview` to check the image.

***

### 📚 Table of Contents

To add a table of contents, the following code block can be used:

````
## Table of Contents
- [How to Create Your Profile?](#how-to-create-your-profile)
- [How to Customize Markdown files?](#how-to-customize-markdown-files)
- [How to Create New Repository?](#how-to-create-new-repository)
````


Note that the links in the table of contents may not work in Preview. You need to Commit changes to check if the links work.


To get the correct `(#xx-xx-xx)` for each section:

**Click on the chain logo next to the section title, right-click and open in new tab.**
<img width="508" alt="Screenshot 2021-09-29 at 6 04 22 PM" src="https://user-images.githubusercontent.com/81607668/135248350-9ba54965-863e-4408-8e02-eb8cd596c2a8.png">

**Then, navigate to the website link, scroll to the end, and copy the highlighted `##xx-xx-xx`.**
<img width="678" alt="Screenshot 2021-09-29 at 6 04 57 PM" src="https://user-images.githubusercontent.com/81607668/135248359-2ed3ea2e-2a8b-4f07-8f7c-80b053d42497.png">

Ensure that emojis are not included in the title, as they may cause issues with the links in the table of contents.

Note that the links in the table of contents may not work in `Preview`. You need to `Commit changes` to check if the links work.

***

### 🧱 Colour Code the Code Blocks

If you've seen my [8 Week SQL Challenge repo](https://github.com/katiehuangx/8-Week-SQL-Challenge), I use colour codes to highlight my SQL syntax. It's a simple technique, but it can make your code look much more professional.

To use color codes in your code blocks, follow these steps:

````
```sql -- Add 3 backticks followed by sql
SELECT *
FROM student_info
WHERE student_name = 'Katie';
``` -- Add 3 backticks
````

This is how it will turn out:
```sql
SELECT *
FROM student_info
WHERE student_name = 'Katie';
```

***

## How to Create New Repository?

Creating a new repo is as easy as creating your profile.

**Step 1: Click on `New Repository` at the top right of the page.**

<kbd><img width="257" alt="image" src="https://user-images.githubusercontent.com/81607668/135068335-12538e85-8090-4f27-8232-47bfcc15b2c2.png"></kbd>

The image below is the default setting. If you forgot to tick `Add a README.md`, you can create the file separately in the repo later.

<kbd><img width="615" alt="Screenshot 2021-09-28 at 9 55 20 PM" src="https://user-images.githubusercontent.com/81607668/135103549-c7d87461-adb5-4b6c-b65b-72842e2f374c.png"></kbd>

And, it's done. You have created your first repo! 😎

*** 

## How to Create Subfolders in your Repository?

**Step 1: Navigate to the right side of the page. Click `Add File` and `Create New File`.**

<kbd><img width="879" alt="Screenshot 2021-09-28 at 10 41 20 PM" src="https://user-images.githubusercontent.com/81607668/135109960-52721c55-810e-47d9-a463-8c19d9ece947.png"></kbd>

**Step 2: Name your file followed by the extension `.md`, or your desired format.**

<kbd><img width="610" alt="Screenshot 2021-09-28 at 10 42 05 PM" src="https://user-images.githubusercontent.com/81607668/135110652-99d4b7da-9339-4324-b564-5d217bf4cfbd.png"></kbd>

***

## How to Upload Projects in your Repository?

**Step 1: Navigate to the right side of the page. Click `Add File` and `Upload File`.**

<kbd><img width="397" alt="image" src="https://user-images.githubusercontent.com/81607668/135250389-cece0d81-19fa-4021-beb1-2bd4fb3bc09c.png"></kbd>

**Step 2: `Choose your file`, wait for file to load completely and click `Commit changes`**

Once your file is uploaded completely, it will look like the one in my screenshot below. Bigger file size would take a longer time to load. 🙂

<kbd><img width="1052" alt="Screenshot 2021-09-29 at 6 19 34 PM" src="https://user-images.githubusercontent.com/81607668/135250662-8d19c9b6-7b57-4e15-90da-efd174d5d8a0.png"></kbd>

And, that's it! It's as simple as that!

***

## How to Fork a Repository?

Let'say I'm checking out this awesome repo and I'm curious to see how he adds the icons, Twitter button, and all the cool stuffs.

<kbd><img width="1419" alt="Screenshot 2021-09-30 at 10 50 08 AM" src="https://user-images.githubusercontent.com/81607668/135378085-28f76e0e-9449-4bd9-8ceb-47a387b7788d.png"></kbd>

**Step 1: Click on the `fork🍴` icon at the top right of the page**

<kbd><img width="439" alt="Screenshot 2021-09-30 at 10 52 45 AM" src="https://user-images.githubusercontent.com/81607668/135378187-26b26415-d194-448b-aba7-9f54dc000b5e.png"></kbd>

**Step 2: It's done!**

GitHub has `forked` and copied the repo and added it as one of your repo. Now, you can edit the file and learn how to add those fancy, cool stuffs too!

<kbd><img width="661" alt="Screenshot 2021-09-30 at 10 50 44 AM" src="https://user-images.githubusercontent.com/81607668/135378329-8d0df892-ed3e-466d-8fe8-3c912065179c.png"></kbd>

Feel free to `fork` this guide and see how I've written it too! 😄🙌🏻

***

Now go and have fun creating your Github profile and start adding projects! 



