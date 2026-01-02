---
title: My GSoC 2025 Journey
date: 2026-01-01 12:48:42
tags: 
	- Professional
---

I recently completed the Google Summer of Code 2025. This blog post serves as a reflection on my journey and a hopefully guide for future contributors as well.

<u>A word of caution:</u> This is not a step-by-step guide on how to get selected in GSoC. By no means I claim that this is the right way to do it or following this will ensure getting selected. This is just my experience and insights into the process.

## The  Timeline
I started looking for organizations around mid November 2024 when my winter break had just begun.

I finalized my organization around the end of November and started setting up codebase.

I then joined the Matrix channel and started interacting with the community while going through the list of good first issues.

My First PR was [#3411](https://github.com/metabrainz/musicbrainz-server/pull/3411) on the Musicbrainz Server repository. This was opened on November 24, 2024.
I did not know much about which project I was interested in, back then. Also, my end semester exams also started in December so I was not able to contribute much then.

Now, in my winter break (mid December, 2024), I started working on fixing issues again.

Then I took a campus transfer to BITS Pilani, KK Birla Goa Campus. I spent the next semester in Goa. You can read about it [here](https://suvid.dev/blog/My-Semester-Exchange-Saga-in-Goa/).

I looked into interesting issues and started fixing them. The issues included bug fixes and new feature requests. Working on them made me comfortable with the codebase as it was the largest codebase I have worked with till date. I also asked the mentors for help whenever I got stuck.

This continued till around March 2024. The projects were announced by my organization around April (if I remember correctly). I looked in to the projects and this one caught my eye: Importing listening history files.

I started looking into it and interacted with my mentors regarding the project.

I started writing the proposal around March 2025. The entire proposal was written by me and I recommend that you write it by yourself only. Please do not use ChatGPT or other LLM tools as its disrespectful towards mentors who will be reading it.

I made sure that there were no mistakes and got it proofread by my college seniors as well. In my organization, we were told to publicly post our proposals for review on their blog for review by mentors before submitting on the portal officially. So I drafted my proposal, worked on feedback and officially applied on the portal around April first week.

I got the email on March 8, 2025 that I had been selected for GSoC 2025!

The coding period began on June 1, 2025. The midterm evaluation was mid of July and final evaluation was around end of August.

So this was the rough timeline for GSoC 2025 that I followed.

## Pre-GSoC Phase

This phase involves selecting organizations, selecting projects, understanding codebase, interacting with the community, working on small issues or new feature requests and writing a proposal. This summarizes the pre-GSoC phase.

### Selecting an Organization
[This website](https://www.gsocorganizations.dev/) helped a lot in going through the organizations. It lists organizations according to tech stack, years in which they were selected etc. This was very useful for selecting potential organizations. I filtered organizations according to my preferred tech stack and narrowed down.

Then, I looked at the consistency of the orgs. Preferably, one should look for organizations that have a track record of participating in GSoC for last few years consistently.

[Metabrainz](https://metabrainz.org/) ticked all boxes for me. I listen to a lot of music so I naturally liked their project [Listenbrainz](https://listenbrainz.org/) a lot! I still use it sometimes to track my listening habits and get some music recommendations. Its a really nice project. I highly recommend that you check it out :)

So, all in all you should look for orgs that use your preferred tech stack, the product is interesting for you, is consistently selected and has decent number of projects to maximise your chances.

Also, I found that a BITSian senior was also a mentor in the Metabrainz. So, that also helped me a bit as I could personally DM someone from the org and ask really silly doubts that I wouldn't have otherwise asked publicly 😛

This was just an added help for me. I didn't actively look for it but was lucky to have it. Though it didn't give any actual advantage in selection as he was not even a mentor for my project. It just helped me reduce the learning curve and setup codebase quickly and get started.

I felt that this was also a factor for me so I included this in the post. But this is a bit irrelevant for most of the people. This condition was unique to me I feel.

So this was my way of selecting organizations. Again, there may be other criteria for others. There is no one size fits all approach here.

### Selecting Projects
This should be based on your tech stack and interest. For me, both Bookbrainz and Listenbrainz were fit according to tech stack. But personally, I was interested in Listenbrainz as it was a product I could see myself using daily and could relate to it. So, naturally I was drawn more towards it. Also, Listenbrainz had more project ideas in the past and more accepted projects so it seemed better. But again, interest should be the first priority in selecting the project you want to contribute to.

### Setting up and Understanding Codebase
This might be the most confusing part for most of the people. First of all, read the official README.md and CONTRIBUTING.md files for the project. Understand all the guidelines and if unsure, please do ask on the IRC or Matrix channels. Follow the coding styles mentioned and other guidelines as well.

The links to join the IRC or Matrix channels would be mentioned in the contributing section on the website or in the README.md. Join these channels to ask for help or interact with maintainers. Some orgs also have weekly meets on these platforms. Like Metabrainz has a weekly standup meet on the Matrix channel where anyone is welcome to share their progress on the assigned issues.

For setting up the codebase, usually a detailed setup guide is available for most of the projects. Following it should be straight-forward. After setting up the codebase, you should be able to run it locally and reproduce the bugs locally. This is the first step in actually understanding the bugs and identifying them.

### Working on Issues
You can go to the Issues tab on GitHub to view the issues that people have opened for the project. Some orgs don't use Github for issues. Like Metabrainz used JIRA for tracking their issues. So you need to head there to find the issues. Some orgs just host their mirrored version of repo on Github and have their own instance of Git hosted. You can find them on the website or CONTRIBUTING.md files.

I started looking for issues and selected a few based on my interest and feasibility. I also asked mentors for some good first issues.

My PRs in Listenbrainz can be found [here](https://github.com/metabrainz/listenbrainz-server/pulls?q=is%3Apr+author%3ASuvid-Singhal+is%3Aclosed+sort%3Acreated-asc).

<img src="Listenbrainz_PRs.png" alt="Listenbrainz PRs" />

These were my PRs before GSoC started. I fixed a few bugs, did some UI improvements and also some new features that were requested in the Issues by the community members. There were also few small UI bugs that I noticed myself and opened a PR for it. It got merged and I also received appreciation for it from mentors.

You need to take initiative and be active in the community. You must also help other fellow members if you can. Don't treat it as a competition. It is a healthy space where people take out their time and do it out of interest.

### Writing a Proposal
Keep an eye for project ideas when they're announced. Once the project ideas are announced, select the one you are interested in. Discuss it with mentors. Ask about expected deliverables, what do they actually expect. Don't just think as a developer! Think about what people using that product might also require. You may also add some extra features as well that might have been missed in the project ideas description. This will make your proposal stand out and also it also demonstrates that you also care about end users and community in general. It shows that you are passionate about the project.

The mentors would be able to guide you properly for understanding the project requirements and how you should approach writing a proposal. They, along with the org admins, will be the ones that will have a final call on which proposals are selected.

The proposal needs to be original and it must include these sections:
- About you
- Description about the project
- Past work done in the org (PRs, Issues etc.)
- Implementation Plan
- Architecture Diagram (if applicable)
- Deliverables
- Timeline (this needs to be detailed)
- Plans for future
- Conclusion

The sections may be added or removed according to the requirements of the org and project. But this is a general idea as to what needs to go on a proposal.

My proposal can be found [here](https://community.metabrainz.org/t/gsoc-2025-importing-listening-history-files/750069) for reference. This is the final version. I made a word document with a professional template and converted it into PDF format and submitted on the portal. It was around 20 pages long.

## During GSoC

Once you are selected, that is the beginning of a nice learning experience. You get to be mentored by some of the best engineers. You would have a fairly good idea on how to approach further if you made it to this stage.

Keep in mind these pointers for smooth experience:
- Keep in touch with your mentor
- Regularly update them on your progress
- Don't be afraid of asking for help
- Research properly and try everything before asking for help
- Complete your midterm and final evaluation on time
- Do remind your mentors if they forget about filling the midterm and final evaluation 😅
- The project scope can be modified or an extension can be requested if you feel the project won't be completed on time

Apart from this, make sure to learn as much as possible and have fun! Also, don't forget documentation! Make sure to properly add comments in the code for maintainability.

As for my experience, my experience was nothing short of wonderful with Metabrainz. My mentor was very helpful and patient. I used to regularly interact with him and also had zoom meetings whenever I wanted to discuss further plan of action and if I got stuck in something for too long.

My project can be found [here](https://summerofcode.withgoogle.com/archive/2025/projects/dawBqvjY). My project was creating an importer for importing listens from different platforms into Listenbrainz. This allowed migrating to Listenbrainz really easy. This was a feature that was pending for a lot of time. A lot of users wanted this feature and I received a lot of appreciation for completing the project. I myself wanted something like this to exist when I first created my account on Listenbrainz and connected my Spotify account to it. I couldn't see my listening history and I was a bit disappointed. I wanted a feature like this to exist. Luckily for me, it was also a project idea for the GSoC 2025!

This was the feature I had built. I worked on both backend and frontend part. I also wrote many raw SQL queries and a few unit tests as well. Working on the project gave me actual experience on how code is written and maintained in large organizations. It was the largest codebase I had worked with till date. Working on it also gave me the ability to navigate large codebases quickly without being intimidated. This is an experience that no course or college class can teach you.

The tech stack was Flask for backend, React and Typescript for the frontend and PostgreSQL for the backend. Though, I wrote raw SQL queries mostly. Apart from that, the entire project was containerized and had to work with Docker as well. It was also using RabbitMQ so I had to fiddle a bit with that as well. So it involved a lot of moving pieces and I had to identify parts relevant to my project and add my code to it.

Also, I got to interact with a lot of people from different parts of the world. I learnt how to work remotely with people from different time zones. I was working as asynchronously as possible as some of the mentors were from different time zones. So this was a thing I couldn't have experienced even in onsite internships.

After the project is finished, we have to write a blog post explaining what all we did and our experience. My final GSOC blog post can be found [here](https://blog.metabrainz.org/2025/08/30/gsoc-2025-importing-listening-history-files-in-listenbrainz/).

This is essential as it serves as a repository of completed projects for the org. It is also a form of documentation for the project.


## Post GSoC
After the GSoC was over and I had submitted the final evaluation, I received an email after few days confirming that I had successfully passed the final evaluation. I had successfully completed the Google Summer of Code 2025!

<img src="GSoC_completion_email.png" alt="GSoC Completion Email" />

Receiving this email was a great feeling. Months of hardwork had finally paid off. I had made a significant contribution to a big open source organization and had also learnt a lot of things. The stipend was also an added bonus :)

After completing GSoC, you also get a certificate of completion and letter of recommendation.

One should try to stay connected to the community and contribute further post GSoC. If possible, provide support for the features you have added. In my case as well, the importer faced a bug which had affected a few people. So, I tried to fix it and opened a PR post GSoC. It was collectively fixed my me and the mentors of the org as it was high priority. So, it is important to be connected to the org even after GSoC.

You could also apply to become a mentor next time if you want and can contribute further as well by helping future contributors.

## Conclusion
So this was my experience and some recommendations for each stage of the process. Hope it was helpful and would inspire more people to get into open source and help out the organizations. The entire world runs on open source softwares at this point. They are supported by the collective efforts of countless people who take out their time to maintain them. Google Summer of Code is a nice initiative to introduce college students to the world of open source. It is a nice experience as a contributor and I got to learn a lot from it!