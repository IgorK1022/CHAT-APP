---
layout: layouts/post.njk
title: >
      237 JSJ CLls - Ember Angular and React with Tracy Lee
date: 2016-11-09 06:00:31
episode_number: 237
duration: 50:00
audio_url: https://media.devchat.tv/js-jabber/JSJ237_CLIs_Ember_Angular_and_React_with_Tracy_Lee.mp3
podcast: js-jabber
tags: 
  - js_jabber
  - podcast
---

### TOPICS:
3:57 The exciting facets of CLI’s8:25 Advantages of CLI projects11:25 Coding in RAILS14:18 Disagreeing with conventions encoded in a CLI19:30 How REACT CLI functions20:43 Is Ember cheating by using REACT CLI?26:52 Which CLI is easiest to use29:00 How to add commands to a CLI34:00 The future of current CLI’s35:30 How well CLI’s are working for their respective communities37:00 The impact of WebPac
### PICKS:
[“How Break Points are Set”](http://majantali.net/2016/10/how-breakpoints-are-set/) Hacker News Article[Chocolate Mint Tea](http://theteaspot.com/chocolate-peppermint-tea.html?catid=253&gclid=CMWWs66nmtACFVdMDQodBF4GUA)[_Ten Things Wise Parents Know_](https://www.amazon.com/Secrets-Wise-Parents-Know-Responsible/dp/1590383303) Book[_Strong Fathers, Strong Daughters_](https://www.amazon.com/Strong-Fathers-Daughters-Secrets-Father/dp/0345499395) Book[_Boys Should Be Boys_](https://www.amazon.com/Boys-Should-Be-Secrets-Raising/dp/034551369X) Book[“How Half of America Lost its Effing Mind”](http://www.dailykos.com/story/2016/10/15/1582897/--How-Half-of-America-Lost-It-s-F-king-Mind) Blog Post[Elementary](http://www.cbs.com/shows/elementary/)TV ShowRecommendation Form for [Topics](https://devchat.tv/javascript-jabber-topic-recommendation) and [Guests](https://devchat.tv/javascript-jabber-guest-recommendation)[Amazon Smile](https://smile.amazon.com/)[Angular Cruise](https://ngcruise.com/#/)[Sweet Licorice Mint Tea](https://ngcruise.com/#/) by Choice Organic Teas[Van’s Nintendo Sneakers](http://www.vans.com/shop/vans-nintendo?cm_mmc=G_Vans_Brand_Nintendo-_-%2Bvans%20%2Bnintendo%20%2Bsneakers&KWID=185786126192.948&adID=110831845733&rmatt=tsid:1013075%7Ccid:604598387%7Cagid:29428711253%7Ctid:kwd-185786126192%7Ccrid:110831845733%7Cnw:g%7Crnd:2640400102191688267%7Cdvc:c%7Cadp:1t1&gclid=CL_-zMqomtACFQlXDQodNP8H1g)
### RESOURCES AND CONTACT INFO:
[Tracy's E-mail](mailto:Tracy@modern-web.org)

### Transcript

Charles: Hey everybody and welcome to Episode 237 of the JavaScript Jabber Show. This week on our panel we have Aimee Knight.Aimee: Hello.Charles: I’m Charles Max Wood from Devchat.tv. This week we have a special guest, Tracy Lee. Tracy: Hi, how is it going?Charles: It’s going well. Do you want to introduce yourself real quick?Tracy: Sure. My name is Tracy, you can find me on the internet @ladyleet and I do something called Modern Web, modern-web.org. We have podcast and we have some really awesome meetups both from the Silicon Valley area online and in the Triangle. I just started a new company called This Dot. Pretty stoked on that in the next basically seven to ten years of my life. I love JavaScript. I started coding almost two years from now. Ever since I picked it up it’s just been all encompassing of my entire life so it’s exciting.Charles: Nice. It sounds like a lot going on. I’m also aware that you’re involved with NG Cruise. Tracy: Yes. One of my favorite projects that came out of NG Conf. This year was just randomly talking on Angular Air and decided that NG Cruise should be a thing. It was so funny because I think the guy that set NG Conf had the same idea a year or so back, so we’ve decided to collaborate on that. NG Cruise is coming to you, May 29th through June 2nd, going to be sailing the Caribbean coming out of Miami. It should be a pretty good time, it’s presented by NG Conf. I already have a few speakers I’m about to announce, working with the team on it.Charles: That is really cool. Maybe we can get back to that at the end of the show. We brought you on today to talk about CLIs.Tracy: Yes. My favorite thing ever. Do you like CLIs? I know some of the more experienced developers their like, “But, it’s sort of obstructs the way all the important thing.”Charles: I grew up writing Ruby on Rails. Tracy: So you love it? Charles: Yeah. For me it’s like, “Oh, I don’t even have to think about any of these things. It just does it for me.” Tracy: Yeah. I definitely feel after doing Ember CLI and then moving to Angular CLI, and having to do a lot more configuration. Every time I use Angular CLI it felt like I was a better developer like, “Yeah, there’s Angular CLI built at JSON file that I never knew existed before.” Charles: Nice. Were you trying to chime in there Aimee?Aimee: I was just going to say some regards, CLI is actually more like badass if we’re talking Git, but you’re actually using the CLAN line and you’re more hard core. Charles: There you go. I want to build that Angular UI now. Just build me my Angular app. I’ll just put all the options in the UI. What is it that you get excited about CLIs? For me it’s just part of the development experience. What makes you so excited about them?Tracy: I think what excites me the most is that as a beginner when I started, I do a week of JavaScript, a week of html, CSS, and then I wanted to get on Ember right away. If you’re using Ember, you’re using Ember CLI. For me to be able to create an applications really easily and within eight hours using material design, produce a static site was really amazing and empowering. Actually just learned Node recently and learn how to setup the live server or dev server, whatever. All these things that the CLI does for you. It was cool to learn but then I was thinking, “That’s awesome but I’ve never actually had to do that.” Not having to go through an extra one to two hours each time you’re setting up a project, I think it’s pretty amazing.It’s exciting to see how all the different CLI’s and just how the JavaScript community as a whole looking at Ember, Angular, and React feed off of each other, what they enable for each other. If you look at Angular CLI, it being an add on at Ember and the fact that it’s basically enable a lot of stuff. I feel like all communities created these ideas, created these things, and barred from each other. I think as a whole, the JavaScript ecosystem is way, way, way better for it. Aimee: It’s also great for newcomers. We’re talking about Ember CLI and they’re new with Angular. Tracy: Yeah. Have you played a with it yet, the Angular CLI?Aimee: Confession. I haven’t. Tracy: I know a lot of people play with the webpack starter kit as well. I just recently started playing with an app that was built off of that and it’s exciting too but I don’t know. I love all of it. I think I just like learning new things and messing around. I’m sure you guys do more.Aimee: Amen to that though, no.Charles: Yup. Is there a CLI for the React?Tracy: There is. For React, there was a few CLIs, there was Rack CLI which I think Matt, Matt created with Michael Jackson I think. There was another random React CLI. Recently, Dan Abramov came up with Create React App. It’s way more lightweight but you just say like Create React App and then the name of your application, and then it works. It’s built using webpack. I know he has a lot of really interesting plans for it. Have you guys heard about React Fiber?Charles: No.Tracy: React Fiber, I learned about it recently. Andrew Clark talked about it, he said it’s a complete rewrite of React from the ground up. I was like, “Oh God, it’s like Angular 2.00 again.” But it sounds like they’re going to be really careful about it. It sounds like its builds using the API that currently exist. I don’t exactly know what it is but I’m really, really excited about what’s going to happen with React in the next year. With this current React app thing, the new React router before that just came out, and then we have Fiber thing that’s new. YOLO.Charles: Yup. One of the things that I’ve really like about the Angular CLI is just that it does a lot of the setup for me. If I need to generate something like a controller or something like that, then it just puts it in the right place and gets me down the road a little bit without having to make a lot of decisions about how I’m structuring my code or things like that. Is that the same advantage you’re seeing from your point of view?Tracy: Yeah, totally. When you look at CLI projects, sometimes I see people saying with things on Twitter like, “Did you know that if you remove this, or you can do this to configure CLI project to the way you want it,” It scares me because one of the things that people don’t realize about the CLI, people are like, “Oh.” I think people who are used to generating their old files look at the CLI and say, “Why do I need a CLI to do that for me, I could just create one.” If everybody could get behind Angular CLI and everybody is using Angular CLI to generate Angular projects, then what will eventually happen is that Angular is able to scale across larger organizations much faster. You should be able to open up an Angular CLI app, actually you do. If there’s no configuration that people do, customization, you should know exactly what your import and exports are called, what your selectors are called. Everything should be exactly the same, folder structure should be the same. The fact that the CLI, an Angular CLI app can help enable a developer to get productive immediately versus having to go through whatever, like a one month just through two month ramp when they’re joining a team.I think sometimes what people aren’t seeing when they look at the CLI and that’s definitely something that has been an advantage of Ember. Even when I was one to two months into coding, I could open up any Ember project and not exactly know what I was looking at but I was able to figure out where my template files were, figure out where my controllers were, know exactly where the router is, I could actually make an impact. Charles: Yeah. But isn’t that just convention over configuration. It doesn’t requires CLI to get that.Tracy: That’s true. Do you think the CLI helps reinforce that a little bit?Charles: Yeah. I totally agree, it does. It makes it easy to do it the same way everybody else is doing it. Joe: There’s no doubt about that. I was just thinking about the history maybe of CLIs. Rails for example to me seems like the first major well accepted CLI that I know of, maybe there’s other better examples there before Rails but it became such a thing that there’s the Rails way you do things, right Chuck?Charles: Yup, absolutely.Joe: That stuff is encoded into the CLI, right?Charles: YupJoe: It became this common thing where if you want to code in Rails and you do anything different in a way that the CLIs, you could probably speak better than this than I could but someone’s like, “Wait a second, you’re not doing it the Rails way.” There became a lot of homogeneity amongst project which was really beneficial when programmers move from project to project. If I go out and look at Angular 1.0 app and I look at as different Angular 1.0 app, sometimes they’re written in different frameworks. The CLI makes a big difference. Angular had a style guide for a long time. That meant that instead of any random five, you take all the Angular apps in the 5% and then look some maybe there’s 10% it looks similar. But the style guide by assumption just wasn’t enough. Tracy: I would agree. I would totally agree with that. It’s interesting because in the Ember community, the CLI is such a thing. I think out of 100 people, either zero people or one person will raise their hand and say, “No, we’re not doing CLI because xyz.” If you have Steph Penner in the room, helping explain why the CLI is the way it is, how long it takes, why xyz? It’s actually really, really powerful and interesting tool.I think the Angular CLI team has done a really good job. Still with Ember CLI, it’s a lot farther along and there’s a lot more things you can do with the CLI. Because Angular is really focused on generating things right now. They don’t have the router generation yet, etc. The team has been able to do really cool things like the configuration. Their shortcuts were doing inline styling and inline templating and different cool things like that or even try adding an NG doc and it going directly to the Angular docs. It’s really cool to see how one thing builds on top of the other but different frameworks focused on making it better for themselves.Joe: Right. While we’re on the topic of conventional, since we don’t have AJ here to be contrary, maybe I’ll try to be a ton of little bit of AJ and going to raise the question of, “Hey, what about when you disagree with the conventions that is coded in the CLI?”Charles: You’re wrong. Couldn’t help it. Sorry. Joe: I assume AJ would take this position just because he’s a contrary guy and I have an easy time taking this position as well. There are stuff in the Angular 1.0 style guide I vehemently disagree with. Vehemently, if you don’t know what that word means I’m sorry, I love using that word. It’s such a great word. I vehemently disagree with several things in the Angular 1.0 style guide, the stuff in the Angular 2.0 style guide. I also vehemently disagree within. There’s a couple of things I saw that Angular CLI doing that I didn’t like. When I played with Rails, there’s some stuff with the Rails dev that I didn’t like. I hate that stuff. I’d rather have my project be different. There is something to that whole way, why you’d do this differently?Charles: Just to pile on there, a lot of people in the Rails community really react. They really don’t like the fact that you can do basically a Rails generate scaffold which gives you a controller, a model, views, and everything else. It’s a bunch of generated code, in my opinion too much generated code. It makes a lot of assumption. Unless that’s exactly what you need, you don’t really want that but at the same time I definitely used it to generate controllers or to generate models just because a lot of that boiler plate was really easy to get together. I don’t want just the standard rest that Rails gives me when I do Rails generate scaffold so I wanted to do something different. What if I want to do something completely different than how do I think about that? Is the CLI going to get in my way? Joe: In Rails, you can use this CLI to either giant like the whole surveying or to just generate the piece that you need? Charles: Yes. You can use it to generate just the piece that you need. Joe: I assume here that either you would know, I really want the whole surveying which probably got less and less frequent over time or it was like the whole surveying made a big difference when you were new in learning Rails. Unless you got better then you started using just specific pieces of it?Charles: Yup. Yeah, exactly. Joe: Kind of enable that whole duality of I’m starting off, I need something to hold my hand more. Now I’m getting better and better and I still want the boiler plate taking care for me. I still want these conventions to be codified into the apps that I’m writing but I don’t want to be overwhelmed with too much. Yes?Charles: Yes.Joe: It is the Ember CLI, Tracy? Is that kind of the same thing?Tracy: No. Every Ember projects mostly, I’m talking like 95% to 99% of all Ember projects are Ember CLI. It’s very shocking, it’s so ingrained into Ember that like, “Why aren’t you using the CLI?” It’s really the question and it’s really weird that you’re not using a CLI. For example, if I have an Angular CLI project on Ember CLI project, I can go to anybody in the community and say, “Hey, I need help.” They’re able to screen here with me without any knowledge of what I’m doing and know where are the things are, and how my project is configured immediately. I’m able to move forward really quickly but I think, again, that’s for me as a use case, it’s like a beginner wanted to get help. Imagine, it’s seem 500 developers, maybe 100 is more reasonable. Imagine seeing 100 developers trying to do all different things and trying to figure out etc. If all of them come together, all of them understand the CLI projects, and all of them can start coding without having to make all these decisions, I think that’s something really, really, really powerful. Even more powerful than just file generation. Charles: But in order to deviate, let’s say that there’s some aspect of what the CLI gives you that you don’t like but there are some other pieces of that that you’re like, “Hm, I could use that,” or I don’t want the whole solution but part of the solutions is okay.” Does the Ember CLI allow you to generate just part of the code instead of the whole shebang?Tracy: I’ve never tried to do so I’m not sure. I have no idea.Charles: A lot of the things in Ember were based on Rails so I’m going to guess, yes. Tracy: Yeah. Ember does help. Actually think by just looking at React and React CLI and what the React CLI creates for you. It is very much about just setting up a very small, very, very basic framework for you. I’m getting something to work, sets up your survey. You can’t really do much with it. You have a starting point so I think it’ll be interesting to see how flexible they decide to make generating things in the future in the React community. I’m kind of curious to see what happens with the Angular CLI as well. Moving to webpack and then hopefully getting the router generation in. I think those are just the basic things, I can’t wait to see them really start growing off the foundation that they’re building right now.Charles: If I remember right, the Angular CLI was actually built on the Ember CLI, they took that code and they kind of reworked it. I’m wondering, is that cheating? I guess the best way to ask that.Tracy: I think it’s lovely. I think it’s great. I love the fact that we’re able to enable each other as a community and borrow from each other’s ideas. It’s not forked or taken, it’s actually an addon. Are you guys familiar with Ember addons?Charles: No.Tracy: This is what the CLI enables. What you can do is you can actually generate an addon with the CLI. You create an addon, Ember data or Ember CLI mirage, or any of those other things, or even if you want to use something like materialized CSS, or anything. You can actually create an addon and then all you have to do to install something. If you ever want to use then you can go to this website called ember addons.com. If I want to use last, or bootstrap or whatever, I don’t actually have to try to figure out how to use that on Ember app, I can just Ember install, Ember bootstrap let’s say. I can just immediately start using things. I know it’s not the most technical way to explain it. Do you guys get what I’m saying now? You get the idea of what this does. Ember data, even the deployment story for Ember is just merely an addon that you create. If you want to deploy an app the Ember way, all you have to do is Ember install Ember CLI deploy and then there’s a path to deploy things. I think what I’m excited about what the Angular CLI is once they stabilize and once they’re able to get the basic stuff down of what they want to do, then we as a community can start building on top of that. I can’t wait for Angular to have an addon community because then people can contribute small things. With Angular 2.0, you want to use x or something. All of a sudden people going to just automatically use it. I don’t know how many addons there, I think there’s something like a little under 3,000 addons or sale. Did I make any sense at all? I hope it did. Charles: Yeah. It make sense to me especially the way you’re talking about the Angular CLI. They essentially built a plugin for the Ember CLI that made it Angularis or however you want to put that. We’re benefiting from this open source project. I’m assuming the wind up contributing back to that project so everybody wins there. It makes it easy to pull stuff in, it’s as the project progresses.Tracy: Yeah.Joe: I’d like to get a better feel for that. The CLIs, their differences between Ember, Angular, and React. It does not to be like a feature by feature comparison but how do they compare with each other, how do they feel? Have you seen the Angular is the newest one? Although React’s still pretty new.Tracy: Ember and Angular are exactly the same. Joe: Oh really?Tracy: Yeah. There’s really no difference. Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yeah. There’s really no difference. Really. Create React App is so minimal that there is nothing to say. Literally, if you use Angular CLI, you’ll be completely fine using Ember CLI. Most of the commands are the same. It’s cute for example that small subtle silly differences are. When you run NG serve or Ember serve, it loads on 4,200 but then if something’s already loaded there, it won’t. The CLI cave is already in use. Whereas Dan built in this thing where it wasn’t for 3,000 but if it’s in use, it’ll say, “Do you want to load it somewhere else?” And then they load all like for 3,001.I think it’s just really convenient.Also when you start Create React App, when you do that instead of having to go to your browser window and then type in logo host, it actually just opens the apps for you. I think those are cute, small, subtle differences that I think are interesting. I think that you can generate a component and you can do –is or –it, or –inspect to decide how you want a component to be generated, what number of files. If you want the inline templating or inline styling is interesting. Those are teensy, teensy style differences. I noticed them. I think it’s interesting but I don’t think it actually affects the functionality.Joe: Is there one of the three that you feel is easier to pick up?Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I think that Create React App is so lightweight that you’re not really doing much. If you just want to play with the React app and you want to see it load or something, then you can use Create React App to do that. I think both Angular CLI and Ember CLI again are just basically the same product in many ways. Both of them are really, really easy to use.I think Ember is a little more stable right now. Maybe it’s a little easier to do that and get use to something and there’s more functionality like the router stuff is already there for you. I don’t know, you know how I am with technology, I just like to play. I was flagrant to React Native CLI recently. One of the random CLIs that I find. I want to play with NativeScript and I don’t like to have a new CLI or something. I don’t think I explained that recently.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; No, not recently. One thing that I’m wondering about with some of these is you mentioned the add ons, is that the way to add commands to a CLI, so you get NG compile or something? I know that Angular CLI already has something that will build your project. I’m saying in general, besides the code generation and the serve and the build. What if I decided, “Oh, I need this other thing,” or maybe we come up with the package manager for Angular so we’re doing the same thing where it’s NG install bootstrap and it’s doing the same thing that the Ember CLI is doing. How do I build some kind of additional functionality for the CLI?Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I think you just have to contribute to the project. I don’t know if you can necessarily do that with the CLI. For Ember addons, if you want to have internationalization in your app, it’s just an NPM package, you can Ember install Ember incl. The addon will basically provide translations for you.If you want to use a pie chart and you want to do it in canvass, there is a CLI addons for creating pie charts that’s already done for you. If you wanted to put a GitHub pages. Actually it’s interesting is, Angular, what they did was they use the idea of an Ember addon and created an Ember addon called Angular CLI GitHub pages. You can actually use that, the CLI allows you to publish really easily to GitHub pages. The reason that that’s enabled is because there was a separate thing that was created that can be used with Angular CLI.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; It’s interesting.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yeah. If you want to wrap, there’s a simple wrapper for Facebook JSSDK, whatever that means. That just works. That community has been able to do so many really cool things for the community just because there’s this addons ecosystem. There’s a lot of things started randomly figured out it for you, which is amazing.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Really cool. Now I’m going to write Angular CLI cow say or something.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; One thing I like to do is I’ve actually created Easter eggs with addons. I’ve created these add ons, I just want to add on where you can install it and then it’s a little rainbow tails. Little rainbow tails pop out of your website. Or you entering Konami code and then Mario coins pop out and make the little quickie noise. You can do fun things too.I really hope what’s going to happen with the Angular CLI is that once things are more stable and they figured out the basics, then they can have an add on ecosystem. All of a sudden, the entire community can start creating really cool amazing things for Angular and it’s going to 10x the growth immediately, the Angular community and what you can do in Angular apps. That’s my dream anyways. That’s why I get excited about Angular CLI.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nice. I want to go play with it.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; You should. Go pair with broccoli on it.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Pair with broccoli on it?Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I can tell you all the secrets. Yeah, pair with broccoli. Do you know Broccoli is?Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; No.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Mike Brocco? Mike Brocki? His name is Broccoli, just to let you know.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Okay, good to know.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Do you know what Kent C. Dodds middle name is?Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; No I don’t. I know Kent personally but I don’t know his middle name.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; It’s Chuwi Chonga. It’s true. If you call him Kent Chuwi Conga Dodds, he seems like, “What?” He’ll respond, I hope, maybe.Joe: I have to remember that.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yes. Chuwi Chonga.Joe: We’ve had Adventures in Angular, we’ve had people on talking about the CLI recently but I know a lot less about the Ember CLI and certainly Reacts. Do you know what the future is like for any of the CLIs? Is there any significant features that are coming up for any of them?Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I think for Create React App, it’s pretty stable on to where it is so Jams just can be building off a bit. I don’t think there’s anything amazingly magical that’s going to happen. I think with Ember CLI as well it’s such a stable product that they’re really more focused on horizontal growth versus vertical growth. I think if we’re looking at big, major, amazing changes, we’re probably looking at the Angular CLI mostly.I think Create React App is so lightweight. I don’t think that they’re all going to set in, like wanted to become as a convention based as Ember. I think Angular sort of like right in the middle of that. They’re probably going to add on a lot of things that the Ember community already has.Joe: Right. That makes sense. How do you feel like the CLIs fit within their communities and their respective ecosystems? Do they fit as well as people that are building them? Hope they do. Are they utilize as heavily, I guess you said that with Ember it’s like 95% of all Ember apps are built with the CLI?Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yeah. If not, more. It’s default. I’m pretty sure it took about a year, maybe even a little bit even more for it to become the default. I’m really curious actually to see if that’s going to happen in the Angular community. I think the Angular community hasn’t realized how powerful the tool it is. But then there’s so many cool things happening with like web packs, starter kit, and all these sort of cool Mingo has this seed, Angular seed is it called?I don’t know. I’m really curious to see if Angular CLi is going to become like the thing. I don’t think in React it’s going to become the thing. I think that React has just so many million different ways to do things that. I don’t know. I just start playing around with React so I actually have no idea what’s going to happen there. What you guys think, do you think Angular CLI is going to become the default for the community?Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I think it’s definitely going to go that way. The reason that I say that is because the tutorials for Angular 2.0 all demonstrate setting things up with the CLI. The other thing is that at least in the Ruby community, a lot of folks that I’m talking to are using the Angular CLI to set up their Angular apps. They’re using different means to get them into the Rails apps, besides the Rails asset pipeline. Since it integrates webpack already, it’s all just automatic and a lot of folks like that over there so I think more and more people are going to head that way.Joe: Yeah. Since it’s using webpack, I think it’s make a big difference to people. The webpack starter kit is a merely as critical as it’s used to be. It’s like, “I want to do webpack so I got to use webpack starter kit and I can use the CLI and do webpack with it.”I feel the same way. I feel like the Angular CLI is going to become very popular. I don’t know if it’ll become as popular as the Ember CLI is but I feel it’s going to become very popular.Tracy: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Why was webpack such a big thing? Why was this such a big deal to mutual webpack?Joe: There are technical reasons why it’s a big thing. Really it’s a big thing to the community because it’s a big thing to the community. That’s why.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yeah. There are definite trade offs with it.Joe: A lot of people are using it because a lot of people are using it and people are talking about it.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I will say that with tools like the CLI were, it just sets it up and automatically is configured for TypeScripts, Angular. It’s a rather complicated tool but the fact that I don’t even have to think about it till I want to do something a little bit different or add something into my app. That’s why I’m using it is because I don’t have to think about it until I have to think about it. It’s pretty popular.The other thing is that a lot of the other built processes that I’ve talked to people about using before. Bower really isn’t a build tool, it’s a way of getting stuff into your app. A lot of people had custom Grunt and Gulp. I think one of the appeals with webpack is you can just pull in the webpack plugin, or recipe, or whatever they call it and you’re most away there. I think there are a lot of things like that that go with it. There are other aspects of hot reloading and the CSS modularization, that’s also pretty nice. There are features like that too that people are pulling in.I kind of agree with Joe in a certain sense that a lot of people are using it because a lot of people are talking about it. But I know several people that have one of those handful of reasons. In fact, most of people I talked to about it, they have at least one of those reasons, that they’re using it now is that it does xyz for me and they don’t have to do a whole lot to get it to do it. And it’s focused on builts.Joe: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I have a big feeling that there’s a lot people that are using it, using Grunt or Gulp just fine. It’s because it’s the new hotness that’s not using it. I think it’s a great pile, I think it’s a great product.Charles: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Alright. I know we have some time constraints so I’m going to push us toward picks. Aimee, do you want to start us of with picks?Charles: Aimee, do you want to start us of with picks?Aimee: Sure. I apologize for being so quiet, I have a lot going on today. I haven’t been able to be in the discussion too much but I do have some picks. The first one is an article blog post I saw on Hacker News, something from last week or might have been the week before. It’s called How Great Points Are Set. It’s really a deep dive into how developers actually works, which I thought was pretty awesome so I’ll put a link to that in the show notes. The second one, I have seed one, so was it target on someday. I bought some tea, and it is chocolate mint. I’m totally blanking on the brand. It’s Harney & Sons, if I’m saying that correctly. Anyway, I’ll put a link in the show notes. It has a little bit of this chocolate flavor, it’s not too overpowering. If you have a sweet tooth then I think the tea is pretty good. That’s it for me.Charles: Joe, do you have some picks for us now?Joe: I do. I’ve been reading a series of books for the last two years. Three books that I felt like really changed how I parent a lot. If you happen to be a parent then these are picks specifically to you. There’s three books that I think together are really great and that parents should read. One of them is called 10 Things Wise Parents Know. Just a disclaimer, it is written from an LDS view point. Regardless of that, it was written by people who did a bunch of surveys so it’s basically like a scientific. It’s a book about using actual metrics and evidence based criteria about parenting. That one, 10 Things Wise Parents Know, Strong Fathers, Strong Daughters, and Boys Should Be Boys. I feel like those three books are things that all parent should read. Books all parents should read. I want to pick those. I also want to pick a blog post. I hate that ever talk about politics. I’m picking this blog post not because it talks about politics but because it talks about tolerance and understanding, given the late of today’s political environment. The name of the blog post is How Half of America Lost It’s Fucking Mind. Which sounds really bad, it’s going to be a very blown out of a portion. Can you believe that there are people who want to vote for this particular candidate? Instead, it’s a really great explanation for people who grow up in a more progressive environment cities and how to understand why there are people in America who view things certain ways. Why that might lead them to choose particular candidate especially given the current political climate that we’re in right now.By the time this comes out, two weeks away, things might be of significantly changed by then but it’s a great blog post, How Half of America Lost It’s Fucking Mind, it’s on crack. It’s all about tolerance and understanding. It’s one of the great things to let you read and be like, “Oh my gosh.” It’s now so much easier for me to see the viewpoint of somebody else. It’s easy for us to be like, “I don’t know how anybody can blank.” Have opportunities for treat articles that are like these, that give you the opportunity just see, “Oh my gosh, I can actually get another person’s viewpoint now and then have some tolerance.” I think it’s just absolutely necessary in the stand age, where even though when we get more connected we get less connected because we thrive ourselves up. That’s my other pick.For just fun, I’ve been recently I’m watching the new season of Elementary, it’s a Sherlock Holmes. I think I picked it before, great TV Show. Those are my picks.Charles: All right. I’m going to jump in with a few picks. The first one was, I’m going to be in New York City in a couple of weeks. I’m also going to be in Nashville but I’m just not going to have any time to spend with anybody home there. I feel bad.Aimee: So sad.Charles: I know. I was like, “Man, I gotta find time to hang out with Aimee.” Unless you want to hang out with me on the way to the airport, I don’t have any time. Because I’m going to Nashville for three days and then I fly home for a day, and then I’m flying out to New York City for five days. It was just hard to make it work. Anyway, I’m going to be in New York City, if you have any recommendations of places to go, or things to see, or anything like that, then I would love to hear them. You can just tweet at me @cmaxw, or you can email me chuck@devchat.tv.I’m also going to pick really quickly, we have a recommendation form for people that you would like to see on the show or for topics you like to hear us discuss. If you go to javascriptjabber.com, you can check all that out and that would be awesome. The last pick, since I’m going to New York, I actually have to have an SD card. For whatever reason my computer won’t read my 64gb SD cards. We’re going to be doing a whole bunch of podcast recording while we're out there so I went on Amazon to buy some SD cards and it reminds me now every time I log in, that I signed up for Amazon Smile. They have a handful of charities you can choose and they donate a certain percentage on whatever you buy to those charities. I’ve chosen the Wounded Warrior Project but you can pick a couple others, any of those. I’m going to pick Amazon Smile, just because I think it’s cool that the company is willing to say, “Hey, what do you care about and will some money to that.” Those are my picks. Tracy, what are your picks?Tracy: I guess I have to pick ngcruise.com. For those of you guys who want to come on on Angular Cruise with us. To rip off of what Aimee was saying, one of my favorite teas is a sweet liquorice mint tea. It’s choice organic teas and it’s whole leaf organic, sweet liquorice mint tea. You can buy it on Amazon. I highly recommend that. Aimee: Oh, that sounds so good. I guess its good tea brother, it’s just start getting cold. Tracy: Yeah. You will love this tea. Also, Simon McDonald, he spoke at my Modern Web event yesterday. He was wearing this amazing Super Mario shoes. Apparently if you go to Vans stores, you can get Princess Vans or you can get Super Mario Vans and they’re really, really, really, amazing. You should probably go buy them.Also on Amazon, I just bought coasters. The coasters are little floppy disks but they’re silicon but it’s amazing.Charles: Nice. All right, if people want to see what you’re about or follow up with you, what do they do?Tracy: You can email me at tracy@modern-web.org, or you can tweet me @ladyleet. I do this really amazing and horrific at the same time, String cast. If you Google or YouTube YOLO Grolo, and then Ember, Angular, or something like that, you’ll see this YOLO Grolo YouTube site that pops up where I just pair with people and sometimes it’s like an hour NPM installing things, and sometimes it’s really, really interesting content like learning functional programming. For beginners out there or for people who just want to laugh at funny things that happen on the internet, feel free to go check it out. Charles: All right. We’ll go ahead and wrap this show up. Thanks again for coming and we’ll catch everyone next week.Aimee: Bye.Tracy: Thanks for having me. Bye.