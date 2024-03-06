# Hosting and Formatting Resume


## Purpose
The purpose of this document is to guide you through the practical steps of hosting and formatting your resume using different technologies. We will use Markdown language for editing, a markdown editor, GitHub Pages, and Jekyll(a static site generator). Additionally, this document will also relate these practical steps to the general principles of modern technical writing, as outlined in Andrew Etter's book "Modern Technical Writing."

## Table of Contents 
 * [**Prerequisites**](https://github.com/malucorreia/malucorreia.github.io/tree/main?tab=readme-ov-file#prerequisites)
 * [**Instructions**](https://github.com/malucorreia/malucorreia.github.io/tree/main?tab=readme-ov-file#instructions)
 * [**More Resources**](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#more-resources)
 * [**Authors**](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#authors)
 * [**Acknowledgments**](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#acknowledgements)
 * [**FAQs**](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#faqs)

## Prerequisites
Before proceeding, ensure you have:
* **Markdown Editor** - you would require a basic markdown editor which can be [VS Code](https://visualstudio.microsoft.com/#vscode-section). 
* **Resume formatted in Markdown** -  a resume formatted in Markdown language and a tutorial on how to use Markdown is attached in the [More Resources](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#more-resources) section. 
* **GitHub account** - we are going to be using [GitHub](https://github.com) as it is the most widely Distributed Version Control in the market. 


## Instructions

**Step 1: Creating a resume** - To begin, you will need a resume formatted using a lightweight markup language called Markdown. Andrew Etter emphasizes the purpose of lightweight markup as simplifying the creation of well-formed XML, crucial for website development. Markdown is a lightweight markup language that offers simplicity and readability while providing enough formatting options to create professional-looking documents, such as resumes. Hence, we will be using this language to create the resume. The editor mentioned in the [Prerequisites](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#prerequisites) can be used, which has a live preview tool to track your progress. Below is a GIF demonstrating the live preview feature in action.

![VS Code Preview](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/vs_code.gif)


**Step 2: Sign in to your Github Account** - Sign in using the credentials. Etter emphasizes the importance of utilizing version control systems like Distributed Version Control Systems (DVCS) to manage project history and facilitate collaboration among team members. DVCS, such as Git, offers several advantages that make them preferable tools for both technical writers and developers alike. These benefits include better performance, offline capabilities, and support for concurrent edits. By leveraging DVCS, technical writers can ensure that their documents and code branches stay in sync, facilitating smoother collaboration and ensuring that all team members have access to the latest version of the resume. Additionally, DVCS makes it easier to share the resume with a lot of people, as it provides a centralized repository that can be accessed by anyone with the appropriate permissions. 


**Step 3: Creating Repository** - Create a repository on GitHub to host your project files.

* On the main page click on new beside the repository section

![Repository](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/new_repo.png)


* Enter the repository name as `username.github.io`, the username is your GitHub username.

![Name](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/repo_name.gif)

**IMPORTANT** - You cannot use any other repository name. 

**Step 4: Uploading Resume** - Upload the resume file to the newly created repository by Add file -> Upload files. 
</br> For the next step GitHub Pages will look for an `index.md` file as the entry file for your site, rename the document that you uploaded to `index.md`. </br>

![Uploading](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/upload_file.gif)


**Step 5: Hosting Your Resume using GitHub Pages** - Static websites are accessible to everyone, as Andrew pointed out. One major benefit is their speed; without complex background processes, static websites load quickly. This means users don't have to wait long for pages to load, enhancing the user experience. Additionally, static websites are easy to create and maintain. They don't demand advanced coding skills or special software, making them accessible to people with varying technical expertise levels. Plus, they can be hosted on various platforms without any inconvenience. Another advantage is their security; static websites are less vulnerable to hacking because they lack the complex features that can be exploited by cyber attackers.

* Go to the repository Settings. 
* Scroll down to the GitHub Pages section, under Code and Automation. 
* Under the Branch section, choose the branch where your `index.md` file is located (typically `main` or `master`) and save the changes.

![GitPages](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/github_pages.gif)

**Step 5: Configure Jekyll** - According to Andrew Etter, Jekyll is the most popular choice and offers distinct advantages for creating static websites, particularly for documentation purposes. Its specialization in generating documentation websites ensures a robust system with features like nested navigation menus, specifically designed to meet the needs of documentation projects. Additionally, Jekyll's ease of configuration via the `_config.yml` file allows users to customize settings according to their preferences, enhancing flexibility and enabling easy adaptation to specific design requirements. 


* Create a `_config.yml` file in your repository.
* Add the midnight supported GitHub Pages theme in the `_config.yml` file, by adding the code: ```remote_theme:pages-themes/midnight@v0.2.0```. 
* Add a title to your page by adding the code : ```title: Resume```. You can name your page whatever you like. 

![confi](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/config.gif)

 
Note - If you want to use your own custom them then refer to the link in [More Resources](https://github.com/malucorreia/malucorreia.github.io?tab=readme-ov-file#more-resources) section. 
Or if you want to use another supported theme check the [list](https://pages.github.com/themes/). 


**Step 6: Verify Your Resume Website** - Visit the provided URL (`https://yourusername.github.io` ) to view your hosted resume.

And Congrats! You are ready to showcase your resume!! 

![resumeReady](https://github.com/malucorreia/malucorreia.github.io/blob/main/images/resume.gif)


## More Resources
- [Markdown Tutorial](https://www.markdowntutorial.com/)
- [Custom Jekyll Theme Tutorial](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
- [Modern Technical Writing by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [GitHub Supported Themes](https://pages.github.com/themes/) 

## Authors
- Maria Luisa - Instructions on hosting and formatting Resume - (malucorreia)[https://github.com/malucorreia]

## Acknowledgements
- Alejandro Labra - Peer Reviewed the Readme.md 
- Shanaya McMillan - Peer Reviewed the Readme.md 
- Matt Graham - Provided Jekyell Theam Template - [Midnight](https://github.com/mattgraham)


## FAQs
### Why is Markdown better than a word processor?
Markdown is better than a word processor because Markdown offers a straightforward approach to text formatting, making it easy to style text using basic symbols. This simplicity enhances productivity and encourages a focus on content rather than appearance, which is especially valuable for creating professional documents like resumes. Additionally, Markdown is free to use, making it accessible to everyone. Furthermore, for technical documentation that needs to be live online and kept in version control, Markdown's compatibility and ease of integration with version control systems make it an ideal choice. In contrast, traditional word processors are not well-suited for creating websites and lack the seamless integration with version control systems that Markdown offers.

### Why is my resume not showing up?
Ensure that your index Markdown file is correctly formatted and pushed to the designated branch in your GitHub repository. Also, verify that the GitHub Pages settings are configured correctly, including the choice of theme and branch for deployment. If issues persist, check the repository's build logs for any errors that might provide insight into the problem.


