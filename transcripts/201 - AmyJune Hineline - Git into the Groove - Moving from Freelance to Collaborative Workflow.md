### AmyJune Hineline - Git into the Groove - Moving from Freelance to Collaborative Workflow

**Yoast:** [00:00:00] Do you know, the Yoast SEO, plugin, [00:01:00] they're red, orange, and green feedback bullets that help you optimize your posts for the web. It runs on millions of websites. We tried to make SEO understandable and accessible to everyone. 

**Nexcess:** Oh great. My website crashed. I give up. Don't give up on your dreams. Jordan, who are you? It's me. You from the future. Your professional website is not out of reach. You just need Nexcess. With Nexcess managed hosting, you Git lightening fast load times built-in performance monitoring and updates, and always awesome support. 24 7 365 for all your projects. Whoa. Yeah.

**Weglot:** Discover Weglot the simple translation solution for your website. All you have to do is add Weglot to your website, select the languages that you need, and that's it. Your website is now available in multiple languages. 

**Bluehost:** Who says building an online [00:02:00] store has to be hard with Bluehost website. It's more than just easy. It's tell us your thing and smart AI. We'll take it from there. Easy it's WooCommerce friendly. So you can add one of these, or swap this for that easy. It's set up shop in minutes with unlimited products. Easy. Whether you sell boots, books or bowls, it's create an online store with Bluehost, easy build beyond boundaries with Bluehost.

**Matt Graham:** Welcome [00:03:00] one and all to WordFest Live. We are just Gitting started with 24 hours of celebrating the people, the technology and the Big Orange Heart of WordPress. 

**Rachel Winchester:** WordFest Live not only delivers a festival educational content, wellness sessions and networking opportunities, but it's also a fundraiser for Big Orange Heart. Please visit that donate link at any time to support the mission of our organism. 

**Matt Graham:** WordFest Live as a 24 hour opportunity for the WordPress community to come together, to feel less isolated, learn from one another and be present with each other. 

**Rachel Winchester:** Our first speaker today is AmyJune Hineline with Git Into The Groove, moving from freelance to collaborative workflow. AmyJune is an active contributor in the open source. As the open source community ambassador, she is uniquely positioned to help individuals become more comfortable and confident as they contribute to their communities. In addition to her work, building community connections, [00:04:00] AmyJune is an avid geocasher noted Volkswagen enthusiasts and eights with her elbows on the table.

**AmyJune Hineline:** Hi, thanks for that nice introduction. Um, I love going first. It's nice to Git kind of things out of the way. There's a little bit of a hiccup, but that's okay. That's what happens when we, um, work in tech, right. We know that. Um, so I am going to be talking about, um, collaborative workflow and git today, um, all to the, kind of the theme to the eighties, which makes it a little bit more fun.

**AmyJune Hineline:** Uh, before I start, I like to do some housekeeping. There are images in the slide deck and I am an accessibility advocate. So I do understand that some folks watching or participating today might not be able to see the visual assets, if there's any pictures that add context or are, uh, need to be explained, I will, uh, I'll I'll [00:05:00] explain those as I go, but some of them are decorative and I won't describe them.

**AmyJune Hineline:** Um, for the sake of brevity, I usually include a link to the slide deck, but I accidentally put it in a red hat, uh, drive. So I'm going to redo that after the presentation and make those, uh, slides available. And I'll post those online. I. And presenting today, um, on the Aloni Lands in Northern California.

**AmyJune Hineline:** And I'd like to acknowledge, um, that I do live on a traditional ancestral unceded territory. Uh, it's important to understand the longstanding history that we all have. That's brought us to live with. Um, and land acknowledgements don't exist in the past tense. Uh, they are current, uh, colonialism is an ongoing process and we need to build our mindfulness, um, of our present participants.

**AmyJune Hineline:** Uh, my name is AmyJune. All one word title, camel case. Uh, my pronouns are she and [00:06:00] her. I'm the senior community manager over at https://opensource.com and opensource.com is under the red hat umbrella. opensource.com is a website dedicated to sharing information about open source along with open culture. If you ever want to write for opensource.com, you know, Git ahold of me, um, you can see my links are here.

**AmyJune Hineline:** It's VolkswagenChick across, you know, LinkedIn and Facebook and Instagram and Twitter. Um, I. I want to acknowledge that. I really believe in reducing the barriers to entry for tech, not only with contributions, but tech in general, I lead contribution days, um, at the local regional and national level. Um, because everyone, uh, can contribute back to our projects, not just with code.

**AmyJune Hineline:** Here's my friend Spotty. He lives with me. Um, you might see him. So I just want to introduce him ahead of time. His long name is Spotty MacSpotsALot, but we can call them spot for short. He is [00:07:00] named after the star Trek cat. And what are we going to talk about today? We'll talk about what it's like in freelance world versus agency life.

**AmyJune Hineline:** Um, and one of the things that I really want to concentrate on are the tools that makes it easier for us to collaborate with other people. That's version control, but I'll also talk about, uh,git clients, um, uh, local environments. And I do have up here that I'll do a demo if slack, if time permits, but I do talk a lot, so that doesn't usually happen.

**AmyJune Hineline:** Moving to agency from freelance has definitely has its advantage. Um, What are some of the things we love about freelance? We love the freedom that working alone gives us, you know, we work at our own time. At any time. We don't have to worry about bothering a team and pinging them or emailing them in the middle of the night when we Git up, because we have a revelation about our code.

**AmyJune Hineline:** But along with that freedom, [00:08:00] Come some difficulties too, you know, uh, there's no one around to bounce ideas off of. There's no one to help you with code review. There's no one to help you with any sort of conflicts. Um, sometimes you just do what you need to do to Git the job done, and it can be detrimental to not have that accountability.

**AmyJune Hineline:** Sometimes I like to equate it to the wild, wild west. Because we're juggling all the roles, you know, you're the person in charge of absolutely everything. You're the project manager, you're doing quality assurance and, you know, a user experience, QA and UX. Uh you're you're the designer, you're the product owner.

**AmyJune Hineline:** You're all of those things. But many of the advantages that came with freelance work historically has started to be encompassed into agency life with the onset of the pandemic. You know, um, we see companies and agencies moving to more, uh, remote friendly conditions. We're not going into the [00:09:00] office as much.

**AmyJune Hineline:** And we're also being more inclusive about time zones these days, and teamwork offers diversity of thought and diversity of. Creativity, having a team around having that team environment, everyone brainstorms together, which in turns really increases problem solving and we're more efficient and effective at arriving at solutions.

**AmyJune Hineline:** Effective teams also allow more room for innovation, uh, in turn it creates, you know, a competitive edge, you know, uh, there's uh, Accomplishing goals and objectives, uh, uh, objectives, you know, sharing differing opinions and experiences really strengthens and holds us accountable. You know, we can make decisions faster and team effort increases, you know, um, you can do the, you can do the stages of designing, planning, implement [00:10:00] implementation, and much more effectively when a team is there to help.

**AmyJune Hineline:** And also working in a traditional full-time web development role at an established company or agency can give us the opportunity for more structured learning, you know, and free learning. You know, we have professional development budGit that we can rely on. Um, plus we have everyday exposure to experts and mentors and best practices that you don't always Git as a freelancer or maybe.

**AmyJune Hineline:** There's a barrier because of cost. When you're on your own, you assume every role, like I said, on a team, there's a place for everyone to contribute based on the roles and their specific skill sets. And this really adds accountability in the forms of checks and balances on a team. You know, we have those project managers, they help assign tasks and they act as in-betweens for developers and stakeholders, they help translate jargon and [00:11:00] find out what specifically needed tickets are submitted and they're assigned.

**AmyJune Hineline:** Um, developers and designers work on the tasks. And then, you know, they're collaborative, which leads to improvement and more ideas. There are technical leads that help us merge code and settle conflicts in our code. And then after changes in conflicts are resolved. We have folks who perform that user testing for us and the quality assurance and regression testing.

**AmyJune Hineline:** You know, when we write the code, we really shouldn't. Um, Be reviewing our own code. Um, and then after the pro, after that, the project manager takes over again and decides if the changes are ready for the stakeholders and it's a rinse and repeat, and it's so much easier within a team code, workflow management becomes a great deal easier when we have tools in place like version control.

**AmyJune Hineline:** Version control is a system that records changes to a [00:12:00] file set or a set of files over time so that we can go back and we can recall those specific versions later. So this is more about the code workflow management version controls are a category of software tools that help a software team. Manage changes to the source code over time, uh, version control, software tracks, every single modification to the code and a special kind of database.

**AmyJune Hineline:** Uh, if mistakes are made developers and project managers can turn back time and make comparisons to earlier versions of the code to help really remedy any mistakes or blunders without a lot of downtime for the whole team. What are some of the requirements for implementing version control? Because there are some prerequisites first you need a computer equipped for the task.

**AmyJune Hineline:** You want to make sure we install. Git locally. Or globally, you know, [00:13:00] even if it's already installed, which may be, it could, it could be installed because maybe you have dev tools already installed, but it's always a good idea to update to that latest version. And this can be done, you know, through a package or another installer, or you can download the source code and compile it yourself.

**AmyJune Hineline:** If you're confident enough to do. And then also basic knowledge of the command line. If you're a beginner, a Git client can be used, but you should really be acquainted with some of that basic command line knowledge, not a lot, but it really helps to know what's going on behind the scenes of the client.

**AmyJune Hineline:** When you use one. And there are graphical user interfaces for the command line. Sometimes we hear them called gooeys, you know, GUI graphical user interfaces. And I want to introduce this concept because in the next few slides, I have some images for reference. Um, and after I introduced the commands, um, what they look like in the Git client and the client [00:14:00] simplifies the commands into buttons and drop downs and window, um, interfaces for the workers.

**AmyJune Hineline:** This is an image of a client. You know, we're looking at the source tree and a log across the top. You can see there's some buttons down the sides. There's more buttons. Uh, some of them aren't available. If there's nothing to do, for example, um, the merge button across the top in the middle, um, it's grayed out because there's nothing currently to merge, but the checkout, the ad branch, the cherry pick, the revert functions are all available.

**AmyJune Hineline:** And along the left side, there's checkboxes to add branches, um, uh, tags, you know, you can view those the source tree, um, and then across the, you know, the very, the very, uh, left side, there are, you can choose what files are open in the log when. And there are a lot ofgit clients available. Some are free, others are not, some have free versions with limited [00:15:00] access.

**AmyJune Hineline:** Others are free with full access. Some free versions only allow us to work on repositories that are public. So that can be limiting sometimes if our client's code bases are private or have limited access. So make sure you do your homework, you know, try some out, make sure they have features that you need.

**AmyJune Hineline:** And then something to be aware of too, is sometimes agencies have shared licenses and would like everyone to use the same client, because that makes troubleshooting a little bit easier when everyone's using the same. Many developers, developers turn to integrated development environment. Those are IDEs for short, um, integrated development environments.

**AmyJune Hineline:** And most of these, um, IDE clients, uh, they have a learning curve. Um, so sometimes the IDE might not be accessible for you but much likegit clients. Some are free, some have trials and some. And some agencies again, like have everyone use the same tool, so make sure your machine can handle the load of running an [00:16:00] IDE.

**AmyJune Hineline:** Uh, sometimes the combination of having some applications open can affect runtime and really slow down the machine. I know until I started working with a stronger machine, if I had Docker open with a complicated spreadsheet with like lots of things going on in that. And then if I turn on my slack and then, oh my gosh, if I had zoom on my machine would really start whining and the fan would spin up.

**AmyJune Hineline:** Um, so be mindful of, you know, how, how, how much workload it takes to run some of these things altogether. So why Git and not subversion or another tool? A lot of us use Git, because Git, has become the industry standard for web development. It has a very rich set of commands for tracking cloning and workflows.

**AmyJune Hineline:** And many of these basics can be carried through to other versioning workflows. So here's where my eighties references start to come into play. Um, forgive me ahead of time. [00:17:00] We have never going to Git you up. I'm never going to Git you down. So we're going to start talking about some basics of Git, um, I have some listed here, but we're going to go into most of them in a little bit, but, um, we have Git in it.

**AmyJune Hineline:** Uh, it starts a new repository. Git status is my absolute favorite command. It will list all of the files that have been changed and are waiting to be committed. It's a good command to run before running any other command. And maybe that's why my faith it's my favorite. Cause I do it the most. Um, it works is.

**AmyJune Hineline:** It reminds you of what you've been working on. There's branching that lists all the local branches in your current repository. You can also visually indicate what branch or what branch you're currently on. And depending on how you have your terminal, you know, it might be highlighted green or have an asterisked.

**AmyJune Hineline:** Git diff shows the file differences, which are not yet staged. Git logged. This command is used to list, uh, [00:18:00] the version history of the current branch. You're on Git push since the committed branches of our main branch to our remote repositories. Again, I'm going to be talking about these in depth in a little bit.

**AmyJune Hineline:** Um, so don't feel over. Git pull fetches and merges, you know, changes to your remote server on your working directory. Git add. That's where we add our files that we've been working on. Um, we put them in a staging area, Git commit, actually commits those changes, um, Git merged. This is when we're working with others and we merge our workflows together.

**AmyJune Hineline:** So let's Git into the groove and talk a little bit about working locally. This means on your machine and not in the browser or in a cloud. So the basics of working locally, one of those main commands that we want to talk about is Git clone. It creates a working copy. Of a, of a repository locally on your machine.

**AmyJune Hineline:** And from there you start making your changes, um, Git remote. [00:19:00] If you haven't connected yet to your local repository, to a remote server, um, you add the server, so you're able to push it, your changes up. And this is used when you have created initialized a code base locally first, when we talked about that, Git in it to me.

**AmyJune Hineline:** Git pull. And I'm going to talk about this almost through every workflow. It's when your code is somewhere else and it might be different from your current work, you know, fetch and merge changes on the remote server to your working directory. Again, I'm going to talk about this command a lot. It really helps keep you up to date with what other people are working on much, like Git status.

**AmyJune Hineline:** I almost do a Git poll with everything. And here's a shot of that. Git client, you know, while we're cloning, it's a very intuitive interface. I'm not going to say easy because easy is a relative term, but it's pretty straightforward. Um, you enter the URL where the code base lives and you push a button. And most of our repositories online that we share with each other, have this [00:20:00] information readily available in their dashboard or in their read me files of how to set it up locally.

**AmyJune Hineline:** So let's talk about branching. Um, we don't want to make changes to the shared code base. So we want to create branches that mirror the code and, and we want to work on those other branches. So we don't corrupt others work.

**AmyJune Hineline:** So here's some commands around branching. We have Git branch when we enter that into our terminal or in her Git client again, this lists all of the branches in your repository, and it also tells you what branch you're currently on Git checkout. And you can amend that with Git checkout in your branch name.

**AmyJune Hineline:** This command is used to switch from one branch to another. Git checkout dash B. It actually creates a new branch right then and there for you and you switched to it. So you would say Git checkout dash B and then the name of your new branch. And then you'll [00:21:00] be deposited right on that new branch Git branch dash D deletes your current feature branch.

**AmyJune Hineline:** And back to that client, you know, press a button and you can name and create a branch in a matter of seconds, you name the brand. What you, how you name the branch is really up to you. But when we work together, we want to make sure that we're consistent with what everyone else is doing. Sometimes agencies and organizations might have parameters on naming conventions, like the task or the ticket number and the name.

**AmyJune Hineline:** Um, sometimes when you're working on, uh, you know, contributing back to WordPress, you put the ticket, um, as your branch name, you know, what, what ticket you're working on in the, in the track queue. Okay. So we're going to push it now, push it real good. Right. Um, pushing refers to working with others remotely, you know, at some point you want to share your modifications or your additions that you made.

**AmyJune Hineline:** With the team and to do this, you have to push it upstream. Uh, you want to make sure [00:22:00] your branches ready. So first you do Git add that's where you add one or more to staging one or more files to stay. Um, if you want to add all of them, you do Git, add with a star or Git I'm sorry, Git ad with a period. And that adds all of your, all of the files, but you can also add files one by one by saying, Git, add, and then the file name.

**AmyJune Hineline:** So say you're working on four or five files, but you're not ready to add all of them. You can add them one by one. Uh, Git commit, uh, commit changes to your local branch. Um, we have Git comat, uh, Git commit dash M and then you put a message there, you know, that your commit message. Um, again, you know, um, Use your messaging wisely.

**AmyJune Hineline:** Sometimes agencies will want you to maybe start with your ticket number or the, or the feature branch name, you know, so, so really work with your team on commit messages as well, and then Git [00:23:00] pull, you know, fetch and Birch changes on that remote server to your working directory. Again, like I said, I referenced this a lot because that's really important to make sure your.

**AmyJune Hineline:** Current with others. Sometimes communication is less than perfect. And a few people are working on the same lines of code at the same time. You know, maybe someone's pushed theirs up since the last time you checked, this really helps with conflicts. Um, and I talk about conflicts in the next couple of slides and then Git pushed.

**AmyJune Hineline:** You know, you send your changes back to that main branch of the, of the remote repository. Here's another screenshot, you know, and this one's highlighting, uh, the button in the user interface for pushing and pulling. Uh, the dropdowns next to them allow for more choices and gives useful information. I really recommend becoming familiar with the tool tips and the information windows when you're first learning the process and familiarizing yourself with the workflow.

**AmyJune Hineline:** Often these tool tips show the relevant, Git terminal commands to. So remember how I said that basic knowledge [00:24:00] you can gain some of that. More advanced knowledge by, you know, hovering and dropping down and finding out those, uh, relevant, Git, uh, terminal commands.

**AmyJune Hineline:** So we're going to talk about merging. Before applying outside changes, you should Git your own work in good shape and committed locally. So you're not, so it won't be clobbered if there's any conflicts. So let's bring in all of our work flow together. You know, it's more than just pushing your code to a clean branch.

**AmyJune Hineline:** Um, maybe your team is working on the same code all at once. You know, it all needs to come together and be merged. Um, so this Git remote command, you know, the command is used to connect your local repository. Git pull. Remember I talk about that one a lot. We fetch and merger changes to the remote [00:25:00] server, you know, to our working directory and then Git merge.

**AmyJune Hineline:** This command merges, the specified branch history into the current branch and a client. You can look at logs and compare the two instances in time of the same file. You know, it's color coded green is for additions. Red is for taken out. You can compare different branches in different instances in time with your client.

**AmyJune Hineline:** Um, here's merging, you know, there's a button for merging. It does magic behind the scenes and pulls the code together. Um, while it can do some magic, it doesn't want to make assumptions if there's a lot of conflict. And so you have to kind of work through those conflicts yourself. So what do we do about conflicts and commotion?

**AmyJune Hineline:** I love this Twitter space. I am [00:26:00] developer, and this is so true. We've been there. We just think it's going to take a minute to clean up. You know, we've all said this before. They're famous. Last words. It will be a quick fix. But conflicts happen, you know, even with the most senior developers, the most direct way to resolve a merge conflict is to edit the conflicted file.

**AmyJune Hineline:** Um, Git status. Remember that's my favorite one. You know, you list the files and you've changed, and those that still need to be added or committed. Um, we use the Git diff command. Dif helps us find differences between the states of the repository or the files. And this is useful in predicting and preventing merge conflicts.

**AmyJune Hineline:** We have Git logged dash dash merge where we can view all of the merge conflicts and then Git push that's where we send our changes back to the main branch of our lo of our remote repository. So. Here's a [00:27:00] screenshot of the Git client. Again, you can see there's three versions of the same code compared to each other.

**AmyJune Hineline:** And this is the time to review and check. There are really two things you can do with this information. You can decide not to merge, or you can fix the conflicts. So when the decision is made not to merge in the code, um, say your code just isn't playing nice together. Too many people have made too many changes at once.

**AmyJune Hineline:** So. We'll use a command, Git fetch origin, this fetches the latest history from the server and it points your local main branch. Git reset. And then, um, the commit, this command undo all of the commits after the specified commit and preserves the changes locally, Git reset dash hard with, um, the commit number, this command discards all of the history and goes back to the specified.[00:28:00] 

**AmyJune Hineline:** Then there are buttons to help you with the nuclear option to, you know, push a button, but what's nice is Git, clients are really polite. Um, they make sure we really want to blow up or dissolve our work. So you can see in this screenshot, you know, are you sure you want to do. Um, and it gives you that warning.

**AmyJune Hineline:** So it's really easy to see. So, um, even if you're like really comfortable on the command line, sometimes it's nice to Git back into that, Git client on some of these more, uh, uh, with the merge conflicts and stuff, web based version control platforms. These are things like. Uh, GitHub bit bucket, Git lab.

**AmyJune Hineline:** These are platforms that provide us with a rad visual interface, which also can really help us track and manage our version control projects locally. Um, you know, the workflow is kind of the same, you know, you create a branch, you work in a space away from that production site. You add commits, revise the code and add them to [00:29:00] branch.

**AmyJune Hineline:** You create pull requests. This starts the process of code review and an interface for everyone to see, um, and then code reviews where we discuss and collaborate everything, you know, because maybe I made a change. Um, but when made a different change and we need to talk about those things. And then merging is where we move our code into the main branch.

**AmyJune Hineline:** Uh, here is a screenshot of a GitHub repository, you know, um, this is mine cause I like to be polite. Uh, you can see that the files are listed. You can see, um, some of the things that I've changed over time, you know, there's buttons across the top. It's that interface for my code repository online. And this is a pull request.

**AmyJune Hineline:** Someone looked at my report and said, oh, something's not quite right. So they put in a pull request, which is like, kind of like a merge request. Um, and with the click of a button, I'm able to do that, uh, online. A local server plays a [00:30:00] vital role for developers. The purpose of a development environment is to have a place that allows development and testing on a local machine without the concerns of losing internet connection or accidentally creating temporary security holes or constantly uploading files, a local environment is really a place for developers or designers to test everything they want.

**AmyJune Hineline:** Without worrying about it affecting any end users or content editors working on the live website and much like Git there some prerequisites that go involved with, you know, uh, setting up your local host environment at a minimum. Uh, you need a PHP server. This is for WordPress PHP server, a database server, um, and PHP for WordPress.

**AmyJune Hineline:** You also need a computer that's equipped for the task, you know? Some of us are still on older machines, not on our M ones. You know, if you're using a Mac, [00:31:00] you want to make sure, you know, some of the minimum requirements might be something like, you know, a two core 86 compact press processor with maybe four gigabytes of memory or gigabytes of Ram, and then, you know, 25 gigabytes of available disc space.

**AmyJune Hineline:** But all these local hosts, when you set them up will tell you what they prefer. Um, some of the more complex agents might be. To work at an optimum. Um, you might need an eight core processor. So do your research when selecting which service you want to use, and then a local server plays a pivotal part for most of all offers.

**AmyJune Hineline:** It really allows. And I like to iterate this, reiterate it, it allows development and testing on a local machine without the concerns of an internet connection. I've listed some options for setting up local servers. Uh, you can have, you know, Linux, you can use Mac iOS, windows development. You can use a virtual machine development of [00:32:00] virtual machines.

**AmyJune Hineline:** Sometimes you'll hear the, uh, them called VMs. It's a full self-contained server running in its own environment and operating system. On your machine kind of separate from your machine and then Docker development environments. Docker's a great tool, um, for local development environments as well because of the small print, a small footprint it has, and the fast startup times.

**AmyJune Hineline:** So this is like, you might hear it called containerized develop. So why have a local server? You know, there are a few reasons that pretty much require you to build your web stuff locally. Um, you might have limited access to the client server. You know, you're building a website or an app for someone else, and you don't have access to their web server.

**AmyJune Hineline:** You don't have access to their private repository. Uh, If you're building a new version of an existing website or application, you know, which means that you don't want to mess [00:33:00] around with production, um, while you're tinkering and experimenting and possibly making mistakes with the new code. So it really allows for more experimentation without the risk of blowing up the library.

**AmyJune Hineline:** And then no local internet connection is required. You don't need a web hosting service, or even an internet connection. You know, everything runs conveniently on your computer. You can concentrate on coding and leaving the deployment of the site until you're ready. You know, you can work while you're waiting for your kids at gymnastics.

**AmyJune Hineline:** While you're waiting in line for the gym membership, you know, things like that. And you can really customize your setup, you know, test your development before going live. It really takes away that risk of building new features and makes development less stressful. And then there's the idea of just having more control.

**AmyJune Hineline:** And you can tell I'm excited about this. Um, particularly when you're debugging, you know, say you're new and you don't know what you're [00:34:00] doing, you know, It's sometimes helpful to have more control over your environment, you know, um, and have special tools in place that you don't want on your production site.

**AmyJune Hineline:** Cause it might bog bog it down, but the good news is, you know, those requirements. We mentioned a couple of slides back, you know, the web server, a database server and the PHP part. There are a lot of local hosts that can do all of that work for us. And we don't have to set it up ourselves. You know, usually some of these hosts will come with a web server, a data management system to run on the web server.

**AmyJune Hineline:** They have server side programming languages. Um, they often have interfaces for controlling the web server, you know, starting stopping. Pausing, and then an interface for accessing and manipulating the database, which we don't always have a more working online. And this is new. Uh, I work in the Drupal space a lot and we [00:35:00] work with, uh, Git pod and I spun up a WordPress site, uh, yesterday using Git pod.

**AmyJune Hineline:** It's a new browser based environment that allows for collaboration. It's Git pod. It's really straightforward to spin up an automated dev environment in the cloud. And it doesn't take very much time. It's integrated with vs code, or you can use a JetBrains IDE within its environment, and it's very customizable.

**AmyJune Hineline:** And what's super nice about this. Git pod is you can share the URL with somebody and you can see them working in the code online at the same time. And that is the end of the presentation. So I want to thank everybody again. Um, and Volkswagen Chick across all of the media and that's spelled V O L K S W A G E N C H I C K.

**AmyJune Hineline:** It's really long, but you can do it. And then, um, when I share that slide [00:36:00] deck, I do have some really good information on, uh, resources on Git, and I'll actually put more resources up there because I want to put that, Git pawed link of there. Cause it's very exciting local environment.

**AmyJune Hineline:** And with that, I'll stop sharing. And I'm not sure if we're going to do questions. 

**Matt Graham:** Um, well, I mean, I have a few questions for you. Um, so first of all, I think you need to be in charge of karaoke if that's ever a thing for, for WordFest, because then you could be like a combination of like a tech version of Weird Al with your, your, with your eighties references. Cause I started grooving to those songs. 

**AmyJune Hineline:** I actually do another presentation in the accessibility community where I talk about alternative texts and I use eighties imagery for that too. Super fun. 

**Matt Graham:** So, um, one of [00:37:00] the questions that, uh, I mean, just from the title of, of your, of your talk, I do a lot of, well, I'm a freelancer, but I also work with agencies as a freelancer. So do you have any kind of maybe like tips or tricks for those of us who kind of straddle the line a little bit? 

**AmyJune Hineline:** Well, no. 'cause you should know, like, you know, you might have your own workflow, but again, like working with agencies is different, you know, and every agency is a little different. So learning their workflow, you know, uh, I think could be more complicated as a freelancer working with different organizations, because some people might name their branches different or there might be using different local hosts or they might be using different version control systems, you know?

**AmyJune Hineline:** So. I, I think that complicates being a freelancer when you work with agencies, because you have to learn everyone's workflow. So I don't have any tips for you except for okay. 

**Matt Graham:** Well, that's fair. That's fair. I, [00:38:00] you know, I figure I'd take a shot at it. Um, yeah. Cause it's, it's true. Like you're, you're you're right on the money.

**Matt Graham:** It's it is the wild west. And I mean, depending on. Uh, as a freelancer, depending on how much time you're given you might be doing it by the book as, as an agency would, or you might just be like, oh, I've got to code this as fast as I can. So yeah, I mean, it's, it's, uh. 

**AmyJune Hineline:** I think part of it. That's hard, especially if you've been a freelancer for so long as you don't have that accountability with the team.

**AmyJune Hineline:** Right. So you're like, take those shortcuts or you name the branch, this is a branch, or this is a fix. And I, you know, instead of like doing your commit messages. Right. So, um, there's definitely like more accountability, you know, when you're working with a team, I think. 

**Matt Graham:** Yeah, absolutely. Well, and it's funny too, cause like I've also been the only [00:39:00] developer in an agency. Uh, and that's almost as much a wild west as it, uh, as being a freelancer. So it's kind of a, again, straddling the line, but, you know, and you still Git the same kind of thing. Am I going to do this right? Or if this do you know, six days before actually before I can physically Git it done. So, um, I think, um, yeah, uh, yeah, it doesn't seem like we're Gitting any meeting, any questions.

**Matt Graham:** Um, 

**Rachel Winchester:** Well, I guess I have a follow-up question to what you just asked Matt I'm AmyJune. Do you have any experience, I guess, uh, consulting and, and helping people transition from, uh, freelance development into working for a larger agency? 

**AmyJune Hineline:** No, but I have experience contributing back to open source, which is sort of that same workflow. You know, we work with others, you know, of most of the time, when we think about like contributing back to work, uh, WordPress, we [00:40:00] have the track queue, which kind of mirrors, agency workflow. We all work together. We submit tickets, we're collaborative. We do merge requests. We make patches. So I do have that kind of experience, but, um, I don't typically, uh, uh, That's like everyone has their own skills and roles.

**AmyJune Hineline:** Right. And that's the role of the technical manager or the technical project manager, which I am not.

**Matt Graham:** All right. Um, well, I guess we'll wrap this up. Um, I want to thank our sponsors, uh, for this, for WordFest. It's Bluehost, Cloudways, GoDaddy Pro, Nexcess, Yoast, and weglot, please be sure to visit their tents and chat with them there. You might even win a prize. So don't forget to get your photo snapped in the photo booth and [00:41:00] tweet it out with the hashtag WordFest Live.

**Matt Graham:** Also thank you to our media partners and our micro sponsor. So in the community tent for the next, uh, 53 minutes, uh, we have Cloudways, uh, they're delivering launch with words, tent takeover with Bridget Willard. Um, so there is a one hour break in the stage two sec schedule right now. So head over to the community tent, we'll be back on the hour at 01:00 UTC. You make all our Big Orange Hearts full.[00:42:00] 

