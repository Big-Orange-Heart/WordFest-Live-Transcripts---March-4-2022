## Nate Finch - Wait, wuuut? Where did my CMS go?

**Yoast:** [00:00:00] Do you know, the Yoast SEO, plugin, [00:01:00] they're red, orange, and green feedback bullets that help you optimize your posts for the web. It runs on millions of websites. We tried to make SEO understandable and accessible to everyone. 

**Nexcess:** Oh great. My website crashed. I give up. Don't give up on your dreams. Jordan, who are you? It's me. You from the future. Your professional website is not at a reach. You just need Nexcess. With Nexcess managed hosting, you get lightening fast load times built-in performance monitoring and updates, and always awesome support. 24 7 365 for all your projects. Whoa. Yeah.

**Weglot:** Discover Weglot the simple translation solution for your website. All you have to do is add Weglot to your website, select the languages that you need, and that's it. Your website is now available in multiple languages 

**Bluehost:** Who says building an online [00:02:00] store has to be hard with Bluehost website. It's more than just easy. It's tell us your thing and smart AI. We'll take it from there. Easy it's WooCommerce friendly. So you can add one of these, or swap this for that easy. It's set up shop in minutes with unlimited products. Easy. Whether you sell boots, books or bowls, it's create an online store with Bluehost, easy build beyond boundaries with Bluehost.

**Matt Graham:** Welcome back [00:03:00] to WordFest, stage two. Uh, they say that lightening does not strike twice. Well, I beg to differ because we have two lightning talks that are coming up next. Uh, so we're going to watch both and then we'll do a live Q and A with the presenters after we've watched them both 

**Rachel Winchester:** So next you'll see Nate Finch with, Wait, wuuut? Where did my CMS go?.

**Rachel Winchester:** Nate has been working on the web since 2011. He loves web development because the perfect mix of problem solving, helping people and lifelong learning as a senior WordPress engineer https://strata.com, he helps build serverless serverless integrations for WordPress prior to joining Strattic. Nate worked as VP of development at thedigitalring.com where he spent his time, uh, between where he split his time between developing websites and developing developers.

**Rachel Winchester:** He spent the bulk of his career, freelancing working with hundreds of clients through platforms like top tout, top tile and codeable, [00:04:00] and has even completed a brief stint as a web engineer with 10up. Nate collects master's degrees has traveled to six continents, lived on four, speak Spanish and outside of work, family, friends, food, coffee, and cooking are his favorite activities.

**Rachel Winchester:** He lives in Wisconsin with his wonderful wife and two daughters. 

**Nate Finch:** Okay, welcome to Wait, wuuut? Where did my CMS go? This is about adventures in building a WordPress experience. Even when WordPress isn't available. You know, your clients or your customers have gone jammy, let's say when you hear things like we sell products, why isn't our checkout working?

**Nate Finch:** We use admin Ajax. Why doesn't that work? My search box, just redirects to the homepage. Our forms don't submit anymore. My regex redirects. Aren't redirecting our SEO tanked. What's going on. I thought all of this JAMstack stuff was supposed to help. Wait, why can't we fill in the blank? Why can't we do this?

**Nate Finch:** So, what are we talking about? We're talking about static, WordPress, headless, WordPress, decoupled, WordPress [00:05:00] JAMstack, WordPress, serverless, WordPress hexagonal, and content mesh and all of this other stuff. Why do we even do this to ourselves? Right. Why do our customers ask for this? Why do our clients ask for this?

**Nate Finch:** Basically, we all want simplicity. We all want speed. We all want security and scalability and probably a lot of other S words. The way that we can get a lot of this is through things like decoupled or static or JAMstack. WordPress or websites or web application implementations. Right. They just want to know that their site basically, isn't going to fall over, get hacked.

**Nate Finch:** They want to keep things simple on their end. They just, they just want all of these us words. Right? How do we get these things? Right? There's, there's a lot of talk about where we want to go static, or we want to go head less or we want to implement a jam stack. Solution. What, what are, what are the solutions here?

**Nate Finch:** So some folks so that some providers are going to tell you, Hey, don't worry about any of that. You can just go static or decoupled, headless real easily. All you have to do is replace all your plugins, your theme, et cetera, with their party services. [00:06:00] And we'll start it guys, your site, your contact forums, probably aren't going to work your search.

**Nate Finch:** Isn't going to work. You're going to have to implement a third party comment solution, et cetera. But you know, it'll be fine. Or somebody is going to say, Hey, don't even worry about it. Just hire yourself a modern Java. Okay, probably react developer team to build you a headless JAMstack decoupled, static, cool application set up a CICT process.

**Nate Finch:** Get yourself multiple environments. Use our proprietary thingamajig use, get for version control and deployments and refactor your WordPress beyond recognition. So what the heck? These aren't great options necessarily. And I'm not saying that these are bad solutions, but they just might not be for every customer or client.

**Nate Finch:** So when you're thinking about your clients and your customers, what are some good solutions for them? In this whole JAMstack'y world. Right? So let's define some terms, right? Let's look at headless decoupled, static, and serverless and see what this is all about. Okay. So what are we even talking about here?

**Nate Finch:** This is a massive diagram that just shows a bunch of overlap of all these JAMstack terms that [00:07:00] we're talking about and throwing around. Right. So why are we. Kind of presenting this high level overview, right? This is a quote. I really like your problem. Isn't the problem. Your problem is how to think about the problem.

**Nate Finch:** What we're doing here is just getting ourselves a vocabulary, getting ourselves a mental image of what we're talking about here. So hopefully this will all just help you think about how you can implement these solutions and when, and what are the best solutions for you and your clients to be implementing.

**Nate Finch:** So let's define some terms. Static is anything that can be served from the CDN, right? So you got your HTML and your CSS and your JavaScript. These types of files can be served from a CDN. The headless approach is something that uses WordPress as a CMS, but has a custom front end. So it's probably JavaScript and it's not a classic theme.

**Nate Finch:** Like we think of in the sense of like the template hierarchy, right. And all of these PHP files. Decoupled is going to be something like the content mesh. This is a term that gets be coined and that uses multiple services, multiple API APIs, and it takes the idea and the approach of using the best tool for the job. [00:08:00] 

**Nate Finch:** Serverless is custom on demand, scalable functions and services that provide a dynamic experience. So this is where, you know, the whole that the, there is no cloud. It's somebody else's computer. This is where you're using. On-demand kind of ad hoc functions as you need them for as long as you need them. This is something that can be very scalable.

**Nate Finch:** Be ready to go in an instant for you. And then finally, JAMstack this term is basically in my view, a philosophy and approach to building sites and apps. It's not an actual stack. Like we think of the LAMP or the LIMP stack or the MEAN stack or the MERN stack or whatever other stack. It's definitely more of an idea of how to approach building websites, right?

**Nate Finch:** With JavaScript, API and markup. What are your options? Let's go through and look at a few different options here for each of these, right? So if. Talking about static. Basically the idea there is that there is no WordPress, right. There is no spoon WordPress isn't there. You're just serving up HTML, CSS and JavaScript files.

**Nate Finch:** So WordPress could be used to load [00:09:00] and scrape the content, but it's not going to be available for you to use on like an admin Ajax query or something like that. So you might also be able to use classic plugins and themes with this, but they may not work in a static environment if they require real-time PHP in real time, server and database.

**Nate Finch:** Interactivity. So things like search forums WooCommerce, uh, learning management systems, membership sites are probably not going to work out of the box like they would with regular WordPress. And you could see these kinds of things, uh, with like WP Static or Shifter or some, some other providers or services that make your WordPress sites static.

**Nate Finch:** So with headless, you're going to be using something probably like Gatsby or Next or Frontity, something maybe like Grid Some, Eleventy, anything like that on your front end. And WordPress is still probably available for the front end to access. So that means something like your front end is going to live at something like example.com, but your WordPress, your actual WordPress install is gonna be let's say at wp.example.com or somewhere else completely different. So you still get a lot of [00:10:00] speed and scalability without the theme or plugin load if your WordPress site, or if your WordPress, I should say is still available to the public though, uh, people can follow those API requests that a headless site is making and still try to get into your WordPress site.

**Nate Finch:** That's okay though. Uh, we'll talk about other solutions for that later. So this might require a build and that could be a very short process, or it could be a very long process, or you could have an incremental build system set up. You're also going to be able to model data from things like custom post types are built in post types, advanced custom fields, and even blocks plugins may still work as well.

**Nate Finch:** That actually load things into your HTML or that you are calling an end point for. And then even a rest API end points. WordPress and WP GraphQL could also work for you there. Examples would be the Rudy's dot com site. That there's been a couple of case studies on that. And then as far as I understand that WP Engine's Atlas, the idea of Atlas is built on this kind of idea as well as like a headless implement.

**Nate Finch:** Now we have decoupled. So what [00:11:00] is decoupled? So the idea here is, like I was saying, you're combining a lot of different API APIs with this content mesh idea. So there's other structured content or other data coming in besides just WordPress data or just coming from WordPress. Right. So you can use other services for forms.

**Nate Finch:** Uh, e-commerce and stuff like that. You can use a CRM or anything like that. You might already be doing something like this, honestly, with things like MailChimp or HubSpot, Shopify, uh, et cetera. That's the idea is like you are using these best of breed services for your, uh, for your website, right? So you might be pulling in like this whole mesh of things already.

**Nate Finch:** So examples of this, sometimes we don't actually know what they are, especially if they have a decoupled front end. So things like NPM js.org, which were, it was a human-made project. Couldn't pull in things from WordPress, but also things from the NPM repository. And you can see that these decoupled architectures allow for a lot of different, uh, poll and stuff.

**Nate Finch:** And this is just a, the visual, there is just a list of a bunch of. Decoupled [00:12:00] CMS says that you could use. So last thing to talk about is serverless and it's probably serverless plus static, but you also see serverless services that include a traditional WordPress site. So let's look at that. So you use WordPress in this sense for content management and then maybe.

**Nate Finch:** The site static and shut down WordPress. This is actually what we do on Strattic, right? So you can use these serverless services to make your WordPress sites static and then shut down WordPress. Then on top of that, because you have access to all of these serverless services, things like AWS Lambda or Google, Google cloud functions and stuff like that.

**Nate Finch:** Um, and then also real time databases available, uh, to these that are kind of serverless and scale really well. You can create services to maintain as much. WordPress functionality as possible. So you can build services for forms, submissions, search, SEO, media, and email offloads, multiple language stuff, like, you know, WPML to where you can actually support that kind of thing.

**Nate Finch:** You can also run a lot of [00:13:00] optimizations, like minifying code cache, optimizing. Running things on a CDN, et cetera. So examples of this are any site that's run on static.com and plugins like delicious brains offload suite. So they're Offload S3 in their offload emails. And then also things like using Netlify functions.

**Nate Finch:** Right? So if you have a site on Netlify, you're also potentially using their Netlify functions to. You know, handle API keys or something like that. So that's actually, like I said, what we do at Strattic, where we build out static first serverless WordPress integration. So you don't actually have to completely rebuild your site.

**Nate Finch:** Of course, if you want to, uh, you can do that. Definitely get some advice. And if you have any questions about doing that, feel free to hit me up. So what should I do? What should you do? What should we do for ourselves when we're building our own personal projects and which we do for clients and customers and enterprise level customers and everything like that?

**Nate Finch:** The first thing that we want to do is really have a mind shift in paradigm shift, right? We want to change the thought process around [00:14:00] building for WordPress and what's possible for clients and everything. The expansion of what's possible is really, really cool. We've talked about a lot of tools that are just getting better.

**Nate Finch:** A lot of frameworks, a lot of services that are just getting better for what we can build for ourselves and for clients and customers. This also creates a virtuous cycle, right? Uh, basically one of the things that I like to say is the more WordPress experience we support, the more we're able to support other WordPress experiences.

**Nate Finch:** Right? So for example, if you build. Um, you know, a demo site or something like that, a proof of concept, and you've got your headless site running a, an XJS, you know, app, and then it's hosted on Netlify and then you have to figure out how to implement, uh, gravity forms for a decoupled or headless WordPress implementation.

**Nate Finch:** Once you figure that. You are thinking, probably going to think to yourself, holy cow, I can do this for a bunch of other services, a bunch of other types of plugins that, you know, we can go ahead and use these kinds of processes [00:15:00] and serverless functions for. So what we also see here is that we ended up building more resilient platforms when we start to employ these kinds of tools at our disposal, right?

**Nate Finch:** Whether we are building something that's headless or static or. Decoupled or kind of full on serverless, right? We have a more resilient platform and charity majors have this great quote on a podcast recently that resiliency and reliability is not about making your systems never fail. It's about making them resilient to lots of failures, right?

**Nate Finch:** I usually like to say like, Hey, we were on the internet and like, nothing is a hundred percent. So as we build things out and make things more resilient and we offer and cover more WordPress experience right on these different, you know, decoupled or serverless, uh, instances or, uh, platforms and stuff like that, then we're able to make sure that the sites and applications that we run don't fall over as much.

**Nate Finch:** Right. We're able to scale. Uh, further, we're able to be more secure, less vulnerable to attacks and things like that. So, uh, the more that we do this kind of stuff, the more [00:16:00] resilient our platforms and our sites become. So you might be saying, hold on, just, just wait a second here. This all sounds really great and everything, and we could do all of this.

**Nate Finch:** Right. Um, but should we do that? The good old Jeff Goldbloom quote from Jurassic park, right? We're so preoccupied with whether or not you could, you didn't stop to think if you should, again, before. Take any of these approaches, think about your clients. Think about yourself, what do you want to be managing?

**Nate Finch:** What do you think they want to be managing? And especially this question here, if you're hosting websites and managing all this infrastructure for them, what happens if they want to leave? Right. If they don't have you anymore, they don't have your team anymore. And this is just the story that when I was working at a local agency, A few years, I got super into this headless and jam stack and implementing WordPress this way.

**Nate Finch:** And I thought it was great. Cause you got the speed. You got the scalability, you got the security there. All of these things were fantastic, but I sat down with one of the owners of the agency and he's looked at me and he said, but what happens when they want to leave? And instead of staying with us to where we [00:17:00] host.

**Nate Finch:** You know, WordPress and that whole infrastructure and that we're doing all the maintenance and stuff. What happens when they want to leave? Because they're not seeing the value there anymore. And they want to host on, you know, a $5 a month hosting, what do we do for them? Then they don't have a WordPress theme anymore.

**Nate Finch:** They don't have maybe all the plugins that they could use in like a regular classic WordPress environment. Now, what do we do? Do we have to have a whole offloading. Feed that they're going to pay just to get their sight back, that they spend all this money on. Let's take care of them. Right. So whenever you know, you're thinking about this, it's really great to think about all the possibilities and stuff, but it's also okay to stick with classic WordPress.

**Nate Finch:** There are a lot of big sites that do that. CSS tricks.com, white house.gov, and a lot more all still running classic WordPress and still doing. So you can be wanting to implement all this great, cool new stuff, but you know, think about your clients and your customers as well, and that you are your marketing agency or your company you're going to have to manage all this stuff.

**Nate Finch:** I would end by saying that I think this is so much fun, [00:18:00] you know, when you are dealing. Uh, headless or a decoupled or a static implementation of WordPress where WordPress isn't even there anymore. It can be hard and frustrating and challenging, but it's also very rewarding. It's really all the emotions.

**Nate Finch:** And I would just say like, it's really fun to build support for something that in the end isn't even actually there, I look forward to answering any questions you have and love talking about all that stuff. Cause I think it's super exciting. Thanks.

**Matt Graham:** Welcome back. So we have, uh, both Nate and Rick here to answer your questions.

**Nate Finch:** Hello. 

**Matt Graham:** Awesome talks. If they hit, they hit a chord, obviously different courts with meaning. Um, the last, uh, last eight months, I've been kind of going through a tough time with, uh, with my [00:19:00] mental health, but I was playing around with headless WordPress, probably I wanna say six years. I actually did it. I actually did a talk, uh, in, um, we're, uh, WordCamp Hamilton about, uh, about doing a. Um, using WordPress as like an app development, uh, framework. So yeah, what you're talking about is really cool. Yeah. 

**Nate Finch:** That's fun, man. That's a bit about too in that, uh, uh, we're using WordPress for web apps book came out, actually, I'm trying to remember the guys at WebDev Studioes 

**Matt Graham:** I haven't actually had a chance to read that one over yet.

**Rachel Winchester:** I have a question about how you first, uh, I guess, got into JAMstack and building static WordPress sites. And really like when that moment for you, when it clicked that this is the way to build.

**Nate Finch:** Yeah, that's a great question. [00:20:00] Um, I think for me, at least I think it's different for everybody, but when you see, I think like, I don't know, I grabbed a Gatsby theme first starter. It wasn't a few, it was, it started as before. And it's like, you know, you, I think you've just come out of, and they had like the, uh, WordPress course, it was really just like plug and go and how easy it was to like get started.

**Nate Finch:** Kind of get it going well, I don't know. Easiest relative term. Absolutely. Um, so back it up a little bit there, but like Netlify had their free hosting still does, like my personal site is still there. And so you just like deploy it and you're like, oh, that's there. And it's just pulling all this information from my site.

**Nate Finch:** Well, that's cool. And so the tools are there, you know, so I think it was just like, kind of the right moment when Gatsby kind of came along and, uh, Netlify came along to really have, uh, an easy way to get that up. So I know there's other solutions now, uh, through Vercel, through Strattic, through all sorts of like headless options and [00:21:00] stuff like that and static options.

**Nate Finch:** And everything's. Yeah, but I think for me, it was just like seeing the speed and, you know, Gatsby has the, um, what is it called where you hover over a link and it like, pre-loads the page. So it was just like, just so fast and the images look so crisp and clean and there's just so little that you have to do or whatever.

**Nate Finch:** So, yeah, I was like, this is cool. That was great. 

**Rachel Winchester:** Nice. I been getting into JAMstack about a year now. Um, but not as a developer WordPress, um, and while getting into it, I've been listening to so much heavy metal. So I like how Rick. To heavy metal and that people can listen to whatever music that you like.

**Rachel Winchester:** So I'm curious, what kind of music do you listen to throughout your day? What do you like to work to? 

**Rick Alday:** Oh man, like my music taste is really all over the place and um, you know, I, I can [00:22:00] share some way in my playlist and some of them I'd rather than that, but yeah, I mean, I just listened to. Well, I'm working at drink to loosen, to like some like low-fi music.

**Rick Alday:** Uh, but again, it depends on my mood and what I'm doing. Uh, I definitely, you know, head bang sometimes, and I have my kid like working next to me. She's taking a homeschool at moments, or I cannot put out my music too loud. I use my headphones and, but, um, yeah, I mean, It depends on my mood. So it varies quite a bit.

**Matt Graham:** Yeah. So I guess speaking of variability, what is that one thing that you need to do every day to. Yourself, like I want to stay sane, but really the, the thing is focused. What is that one thing that you [00:23:00] always need to do? 

**Rick Alday:** Okay. Um, what works for me is taking a lot of breaks. Like a lot of five minute breaks, every 40 minutes every hour.

**Rick Alday:** I need to just step out of the office and. I just, just go, ah, what are my plants and our yard? And that's like, what I like to do. I like to do gardening on my time off and that just like completely, completely just takes me away. Any, uh, anything I'm working on online? So, uh, one of my coworkers, he lives in the near the woods.

**Rick Alday:** He has like a large property in South Carolina. So, you know, he, he almost with the, like coming to slack, I'm going to take a walk in the woods and that was for him. And so, yeah, but that's something I need to do. I need to go outside and look at green style, look at plants, look a flower, you know, But I do.

**Rachel Winchester:** Yeah. I definitely understand that. I think, uh, well, [00:24:00] I don't know where, where everyone's located in the world, but where I am in the winter, you can't get too much sunlight during the day. So I have to leave and go outside during lunch to even, get some sunlight. Um, so yeah, I definitely, I definitely feel that, um, going outside during your work day and making a point of it.

**Rick Alday:** And just because I dunno, I guess most of us work, you know, we're sitting down all day, you know, working. So just getting up, even getting, you know, grabbing a cup of coffee or just walking around like five minutes, it really, you know, helps you out with your back pain and, you know, physically, mentally, it just kind of resets you a little.

**Rachel Winchester:** Yeah, unless you're too excited about the develops develop the WordPress static site that you're developing. [00:25:00] 

**Nate Finch:** I was actually the, 

**Matt Graham:** yeah, that's the question I wanted to ask you, Nate. So I I'm a developer. And I ha I feel like it could, I don't know what it is, but I have this rollercoaster of this is so cool too. I hate this. How do you go into that? 

**Nate Finch:** Oh man. Well, yeah. And it's, it's also, you know, a thing of like, oh, this is only going to take me five more minutes. I know. And then five hours later, you didn't go outside. You didn't take your walk. You didn't, you know, like say hi to your family or something, working at home or whatever and all that.

**Nate Finch:** Um, yeah. I don't know. I'm still trying to figure that out sometimes because I know that I'll, you know, if I could I'd work like all day and all night, and I just love figuring all this stuff out is one of the things I love about development, right. Is that you're solving problems, like figuring out puzzles and stuff like that.

**Nate Finch:** So, um, yeah. How do you deal with that? I think like part of it is like, You know, setting a timer for things, for sure. Kind of like Rick was talking about, you know, um, [00:26:00] I think the other side of it too, is to have multiple things that you're trying to figure out, um, that you're, or that, and if you have other tasks you need to be doing that, you're like, okay, I can only spend like 30 more minutes on this before I have to move on to something else.

**Nate Finch:** And for me to like part, I was a freelancer for, you know, six, seven years or whatever, and joining a team, uh, whether it's at a design agency or now like Strattic where we're a hosting company, um, You know, having other people around you that have those like have skills or can be your rubber duck or, um, give you insight and stuff like that to all that.

**Nate Finch:** Like, if you can just like talk to the people, like again, requisites so much great advice, Rick, that, uh, uh, it's super helpful. Just feel like, figure those things out and get unblocked and move forward. You know, team like the sum, the total is greater than the sum of its parts, right? Yeah. 

**Matt Graham:** Um, no, actually, uh, AmyJune, which was one of the, uh, one of the speakers earlier, uh, [00:27:00] posted the, um, the, from the developer Twitter account. It's like, this'll just be the five minutes fix. 

**Nate Finch:** Yeah. Five minute fixes every day. 

**Matt Graham:** Yeah. Right, exactly. Right, right. Exactly. That's that's well, that's the limit because if you go above that, then you know, it ends up being an eight hour fix.

**Rachel Winchester:** Well, I, I guess I have one more question. Um, I'm curious, uh, w w with who you deal with that at your job, um, do people come to you excited about static or do you have to convince them.

**Nate Finch:** Yeah. So a lot of the folks that come to Strattic are, you know, mid-size or enterprise level folks that have been running WordPress for years, and they have worked on other hosting platforms with their hosting companies [00:28:00] and they there's like this kind of sweet spot sweet spotat Strattic where we can take your WordPress site as it is and make it static and then put that out.

**Nate Finch:** And we also like build in these serverless integrations, like for gravity forms or contact form seven, or need WordPress search or the list goes on. Right. Um, but they have been. I told that if they want to do something static, something fast and scalable and secure that they need to rebuild their site and stuff.

**Nate Finch:** Well, you know, they've spent years on this or, you know, tens of thousands of dollars or hundreds of thousands of people, hours or whatever on the site that they have in the set up that they have. And their marketers love it. Their SEO, few people love it. Their content writers love it. They don't want to switch.

**Nate Finch:** You know, a non WordPress platform or whatever. Uh, and they don't want to have like a deployment, like a, uh, a build process necessarily where they have everything he coupled where there's like, you know, next she has her Gatsby on the front end and WordPress on the backend. And they're still dealing with that security [00:29:00] then too, because they still have their WordPress site up and it could still be taxed.

**Nate Finch:** The folks that come to us are basically saying like, Hey, when you shut down WordPress, that means that our WordPress can't be hacked. That's great. And then you have all these awesome integrations and stuff that other hosting static hosting platforms or a static kind of integrations don't have out of the box.

**Nate Finch:** Like I said to the PML for like one multinational site and stuff like that. So those are the kinds of things that are like really important and like the headache, like we were just talking with somebody else who was like, you know, you all have. Not to say that we cost somebody their job or whatever, but it's like, you know, if we were doing what we were doing before we came to strata, we'd still have another person and a half or something like that on staff.

**Nate Finch:** That's just, just watching our site. Right. Like they're not doing anything productive or whatever, they're just trying to help us with the thing. So, yeah. So yeah, it's, it's cool. That's kind of the same story, uh, you know, two dozen different ways and [00:30:00] stuff like that. Uh, come on. 

**Rachel Winchester:** Yeah. Yeah. I'm very interested in, in, in, um, how people are transitioning, because I know it's, it's, it's kind of new or it's coming back.

**Rachel Winchester:** Um, but it keeps trying to, uh, to, to, you know, get even more popular, which is really interesting. 

**Nate Finch:** Yeah. Right. Yeah. Everything's uh, that was old is new again or something like that. Right. So.

**Matt Graham:** All right. Well, thank you gentlemen, for, uh, for being able to be part of our Q and A I'd like to also thank our sponsors, Bluehost, Cloudways, GoDaddy Pro, Nexcess, Yoast and Weglot. Please be sure to visit their tents and chat with them and you might even win some prizes. So don't forget to get your photo snapped in photo booth as well, and tweet it out with the hashtag word, WordFest Live.

**Matt Graham:** Also thank you to our [00:31:00] media partners and our micro sponsor. Uh, right now in the community tent, uh Cloudways or sorry, that's in the next hour. Cloudways is, will have their hourly giveaway. There is a, uh, well, it's probably only about a nine minute break in the schedule right now. Uh, so head on over to the community tent and we will be back in nine minutes with, uh, starting off at the Asian continent.

**Matt Graham:** You all make our Big Orange Hearts full.

