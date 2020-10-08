2 minute intro presentation
  + Useful for putting the week into perspective
  + Zooey: Very much based around me and the way that I would deliver it. I wouldn't want to give it to someone else to deliver. But something which contains similar content about why JS was created. I was asked by a student: "what is node, is it a different way to write JS?" All these people have probably started writing JS after node exists. Very brief history of JS and how node fits into that is good.

Intro workshop - Q&A:
+ Just got them to read through the Readme and do a Q&A.
+ Two things students really need to know:
  + What is node?
  + What is a server?
+ Lollipop-ed

Intro workshop - code along:
+ Went really well, despite public speaking fears
+ Split of responsibilities:
  + Ran over time because we had 1 person typing, 1 person giving in-depth explanations & no one floating. So we need to do a step, then stop and make sure everyone was up to speed, then do a step, then stop.
  + If doing it again, have the person typing be talking aloud & the other person floating.
  + Make sure the person typing is really comfortable with the material. Practice multiple times before delivery. That way, if you make an error, you can quickly look through and figure out where it is. Key that a mentor can't be reading through the notes while delivering the code-along.
+ Way more in-depth than when it was delivered to FAC10  
e.g. difference between `readFile` & `readFileSync`.
  + Code-along more in-depth is a good thing. When they do have "teaching" from the front i.e. having someone stand in front of you and tell you what it does is good. Maybe 2 presenting the code along and 1 person floating
  + People didn't have as many questions in the Node Girls workshop. Probably because they'd had the explanation beforehand, so people were able to just get on with it without too much help.
+ Refactored the code from the beginning rather than a few mins at the end - really good decision

Node Girls workshop:
+ Zooey & Yvonne: Don't know how far anyone got through the workshop.
+ Jen: Not sure, but I think it was really varied. FAC9 & FAC10 both said the last steps were really useful and it would have been good to have had time to get to those stages. But FAC11 had a different code-along experience. So let's just see whether it comes up in their SGC.

Modularisation MC:
+ Went pretty well.
+ Went through solutions branch together. That was the main thing on the SGC from FAC10 SGC - no one went through the solution. Appreciated people being nice and asking whether we wanted more time, but people are always going to say yes.
+ We were hardline about timings!

ES6 MC:
+ Both MCs were fine.
+ 1.5 hours was good. 30 mins for solutions - allowed us to work through some of their solutions a bit.
  + Zooey: Plan how long something is going to take and then make them fit that time. Especially if it's one that has been run before, you should be able to predict how long it's going to take.

Research afternoon:
+ Readmes were really good!
+ Clear instructions:
  + Zooey: Communicated to them twice that we wanted them to prepare questions to ask to the rest of their cohort, but they didn't.
  + Yvonne: But this was only via gitter.
  + Zooey: If we're telling people to ask questions again, make it clear that they shouldn't ask trick questions!  
  Wanted to say "don't answer that" when a student asked a trick quetsion. Did jump in when the recipient couldn't answer it & that student did say it felt pretty mean.
+ Presentation times need to be stricter during research afternoon. The 2nd group's presentation went along for a long time. The only one I wasn't time keeping for.

Projects:
+ During introduction, they were really shocked and asked "How do you do this? No idea where to start." Seems like the kind of struggle that's good.
  + Advice: plan it, research it. If you hit a wall, ask us. But try it and see how you go. No one came to us with a basic question. They got on with it.
  + API design is something that really requires you to think about what you're doing before you do it.
  + We very much encouraged planning _before_ you jump in.

General:
+ Timekeeping = mentor responsibility
  + One mentor per activity should be "timelord"
    + Zooey: My opinion on the way things are structured - one of the roles of the mentors is time keeping. You need to get up and say "We have 45 mins on this. Then it's done." One of the reason those things went well is because we did that.
    + Jen: Agreed. I have been "timelord" in weeks 1-3, but I've been able to be much more hands off this week. Definitely ideal if it is clear that this is a mentor's responsibility.
+ Student confusion about JS being single-threaded
  + Add into curriculum for next iteration (not necessarily in time for Nazareth)? People were confused about their server serving multiple things. Needed to clarify that it only handles one request at a time. Serves `index.html` then closes that connection, then browser starts parsing HTML, etc. Went through each event happening line-by-line.
  + Student question: isn't it more likely to error if you're trying to get multiple files at once rather than one file at once. Misunderstanding: the server does one thing at a time. That's why the asynchronisity is important & the event loop.
+ Understanding of async was pushed back. Felt like FAC10 was way more solid on async by the end of week 3, because we had it in testing week, then parallel and waterfall. FAC11 didn't struggle with parallel any less than FAC10, we've just pushed it back a week.
  + Add the event loop video?
  + Linked it in gitter but don't most of FAC11 haven't watched it.
  + People need to be able to watch the event loop video at their own speed. In API week a bit of understanding about async is useful. But when it comes to writing your own async thing, understanding needs to be there.
  + Watched it during precourse, didn't understand it. Watched it before node week and that was ok.
    + Alright after weird parts
    + Understood werid parts, didn't understand event loop video. Only makes sense once you've written some async code.
+ (**Week 2**) Finn: My morning challenge wasn't that helpful. Don't think many people got callbacks from it, so it's not really serving its purpose.
  + Zooey: MC isn't the right way to introduce them
  + Finn: No, it's not. Long workshop more appropriate
  + Zooey: then throwing people into parallel & waterfall MCs would be fine.
  + Interesting to see how it goes with Lubes' callback
+ Wouldn't introduce ESLint in week 4, directly before projects
  + Done because FAC11 requested it in the last SGC
  + Loads of errors with the new version. Students placing a lot of importance on it atm. It's causing people more time than is going to be helpful.
  + Just needs to be something that people learn to do on your own, or do it on your own.
  + Alumni often struggle with this and it affects their projects. We should just include it in the installation list & ensure it's set up during week 1.
