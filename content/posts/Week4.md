---
title: "GSoC’23 at PostgreSQL (Biweekly Report 4)"
date: 2023-07-04T18:26:47+05:30
draft: false
---

> Introduction:\
> Welcome to another update on my Google Summer of Code (GSoC) project, where I've been making significant strides in Postgres extension development. From Day 43 to Day 56, I focused on finalizing the tutorial content, working on sample extensions, addressing issues, and incorporating official documentation references. In this blog post, I will share the key highlights of my progress during this phase of the project.

> Github Repository: <https://github.com/IshaanAdarsh/Postgres-extension-tutorial>

**Extension Management and Upgradability:**\
To ensure comprehensive coverage, I initially completed the summary of the extension management and upgradability section. However, I realized that additional details were needed to provide a thorough understanding of these concepts. Therefore, I finalized all ten sections of the tutorial and devoted attention to troubleshooting and fine-tuning the MVP code.

**Working with SQL and Python:**\
I expanded my work on SQL and Python by incorporating necessary sample code for extensions. While encountering challenges along the way, I persevered and resolved issues to ensure the smooth execution of the development process.

**Changed my approach:**\
After a discussion with my mentor, David Wheeler, it was recommended that I shift my project approach. Instead of focusing on reference documentation, I will now create a quick start guide for a simple SQL-only extension, gradually expanding on it. It was also advised to ensure the accuracy of information in the documentation by including examples or linking to official documentation. While this requires starting over, I am confident in completing the project on time.

**Regression Testing and Version Control:**\
To validate the functionality and stability of the extensions, I performed regression testing. During this process, I encountered issues that I carefully documented to ensure a seamless development experience for users. Troubleshooting these issues allowed me to refine the extensions and make them more robust. Used the GitHub Issues to record the problems i faced and their solutions. (added StackOverflow links also)

**Created a PGXN Account:**\
To get first-hand experience on distribution of a Postgres Extension, i created a PGXN account

> Requi3m --- <https://pgxn.org/user/requi3m>

Here i will uplaod my sample extensions and all the updated versions.

**Packaging and Uploading to GitHub and PGXN:**\
To make the extension accessible to users, I packaged it and uploaded it to GitHub and PGXN. While facing some hurdles during the packaging process, I resolved them by updating files, ensuring the correct version number, and seeking assistance from the Stack Overflow community. This collaborative effort enabled me to create a reliable and accessible package.

![](https://cdn-images-1.medium.com/max/1600/1*sQs3gNBJc59AuN2c5QJJ_g.png)

![](https://cdn-images-1.medium.com/max/1200/1*BflBWMBS7TrtUujUr1D2tw.png)

> Github Repository: <https://github.com/IshaanAdarsh/my_extension>

**Upgrading the Extension:**\
Continuing my work on the extension, I upgraded it to a new version. This involved adding new functions, updating file changes, correcting syntax errors, and providing necessary documentation. Resolving issues with the META.json file and finalizing the required files were crucial steps in completing the upgraded extension.

![](https://cdn-images-1.medium.com/max/1600/1*kfQ-3MgW27RPr8OJ4Kyb8A.png)

**Updating the Tutorial and Sample Extensions:**\
To enhance the tutorial's comprehensiveness, I addressed issues in the second version of the extension. I added new functions, updated the extension version, and rectified any syntax errors. I also included documentation files and removed unnecessary ones to finalize the extension.

**Creating Sample Extensions:**\
Taking a step further, I started creating sample extensions to demonstrate different function types and PostgreSQL's extensibility. I provided detailed examples and explanations to facilitate effective learning for developers.

![](https://cdn-images-1.medium.com/max/1600/1*w9ZGaBG7zfu54SdvFb_qSQ.png)

> Github Repository: <https://github.com/IshaanAdarsh/pg_sample_ext>

**Incorporating References to Official Documentation:**\
To complement the tutorial and provide additional resources, I included references to the official PostgreSQL documentation. This allows readers to delve deeper into specific topics and broaden their understanding of Postgres extension development.

> Conclusion:\
> During the Day 43 to Day 56 phase of my GSoC project, I made substantial progress by finalizing the tutorial content, then i pivoted on my approach and started working on sample extensions, and addressing issues with the help of official documentation and external resources. By incorporating references, I aimed to enrich the learning experience for readers and encourage self-learning. With each step, I have moved closer to creating an informative and accessible tutorial, while also gaining a deeper understanding of Postgres extension development.