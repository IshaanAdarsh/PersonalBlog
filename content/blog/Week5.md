---
title: "GSoC’23 at PostgreSQL (Biweekly Report 5)"
date: 2023-07-18T18:26:47+05:30
draft: false
---

> Introduction:\
> Welcome to the latest update on my Google Summer of Code (GSoC) project, where I've been focused on Postgres extension development. Over the past two weeks, I've encountered challenges, made progress in updating tutorials and extensions, and sought help from online communities. In this blog post, I will share the key highlights of my journey during this phase.

**Handling Functions and Packaging:**\
I added information about handling functions in different extension versions to the makefile. This addition helps ensure smooth functionality across multiple versions. Additionally, I packaged a final version of the quick start, providing users with an easy-to-use and comprehensive resource.

**Issue Reporting and Troubleshooting:**\
During my work, I encountered an issue with pgxn_utils, which I promptly reported on GitHub and sought assistance on Stack Overflow. By doing so, I not only sought a resolution for myself but also helped others who may face the same problem.

**Challenges and Perseverance:**\
I faced challenges while installing PL/v8. I broke down at the end and recorded my misery in this [blog](https://reqi3m.hashnode.dev/day-62-plv8-a-pain-in-the-a).

**Updating pg_sample_ext:**\
I updated pg_sample_ext to version 1.1, introducing composite types, domains, and an enumerated type. These additions enhance the functionality and versatility of the extension. Furthermore, a new update included a custom operator for performing specific data operations, and I included update scripts to assist users during the transition.

![](https://cdn-images-1.medium.com/max/1600/1*sSa6pEggo9CBDpUndGp9gg.png)

![](https://cdn-images-1.medium.com/max/1200/1*awl5orZLY1AUO8wAXphV6A.png)

**Integration of Postgres Documentation:**\
To enrich the learning experience for users, I integrated Postgres documentation links into the quick start tutorial. This allows readers to delve deeper into specific topics and access additional resources.

**Passed the Midterm Evaluations:**\
Got Great Feedback from mentors , and getting that sweet stipend is definitely a nice bonus. It's not all about the money, but hey, who doesn't love a little extra cash in their pocket?

![](https://cdn-images-1.medium.com/max/1600/1*tzkpWvEnav9Y2aRdpB45tA.png)

**Challenges with C Extension and Alternatives:**\
While attempting a C extension, I encountered system issues that hindered progress. Seeking help on Stack Overflow, I am currently awaiting a response to overcome this obstacle. Meanwhile, I have shifted my focus to exploring procedural languages as an alternative solution.

**Productivity and Travel:**\
During this phase, I had to travel back to my college as summer vacations had ended, which affected my productivity to some extent. This might slow my progress but a few extra hours to cover up won't hurt.

> Conclusion:\
> During the last two weeks of my GSoC project, I have made progress by updating tutorials and extensions, while also facing challenges with the C extension. By troubleshooting and seeking help from online communities, I am actively working towards a resolution. Shifting focus to procedural languages has allowed me to make progress where needed.