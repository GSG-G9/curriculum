## General
Alexis & Jessica:
+ Lots went well because Alexis spend loads of time prepping. If he hadn't done that, this week wouldn't have been very successful.
+ Worried about how easy this week is to pick up and deliver. Worried in terms of replication.
+ The workshops now are good, and it's ok that mentors supplement the material. We should be helping.
+ Completely disagree - we're supposed to be there to help & support them, but material should be able to stand on their own. It shouldn't need to an extra presentation. They liked the presentations and you delivered it well. It's nice when you're introduced to a new topic, but you can't rely on all mentors being comfortable enough to do that.
+ Done at 2am = reason not being clear
+ Good basis but need to be worked on and developed further
+ The fact that you now have to speak to Nazareth over the weekend & they'll probably have to do the same for Gaza is a problem.
+ Need to incorporate what we've done in the presentations into the workshops
+ People shouldn't be merging their own PRs. I flagged an issue about the Jest tests & Ronan made PR & merged it, but the problem wasn't fixed.
+ If you're going to create a new workshop, make sure it's finished 2 weeks before. How to implement that deadline though?
+ Good week anyway, but could have been an amazing week if it hadn't been done like this.
+ Felt really stressed & underprepared. I was relieved when it was over. We weren't sleeping. The whole thing was not a pleasant experience. It's good that it's in the course! It's really valuable that it's in there. Students really loved it.
+ Be careful JWTs vs cookies.
+ Didn't even know what was going in to 3rd workshop. Would have been one thing if we'd had learning outcomes and had known what the workshop was going to contain. We could have read around the subject. Kept asking for it and the response was just "google". We can't google everything there is to know about authentication. We've got jobs and other responsibilities too. FAC11 made it a lot easier for us than they could have done.

Jen:
+ I'm hugely disappointed that these two weren't offered the opportunity to walk in to the classroom feeling prepared and confident. I think this was a big lost opportunity for FAC and the lead up to this week was pretty hard to watch. We need to make sure this kind of thing doesn't reoccur in the future. It's not fair to mentors to be put in this position, or to miss out on how fun mentoring can be.
+ The way the workshops are written is absolutely brilliant for the level of the students! All too often, our resources are aimed to high or contain explanations that use words the students don't understand. It contributes to a feeling of being overwhelmed and causes stress that is purely down to the design of the workshops. So this was hugely refreshing for students.
+ Despite the students enjoying the workshops, there were quite a few gaps and elements of confusion when it came to implementation during projects.

## [Password Management](https://github.com/foundersandcoders/ws-password-management/tree/2cfc231bd6ddb97eb4a9316c67020f3e316d334f)
Alexis & Jessica:
+ Presentation at the beginning was really good.
+ Students got what they needed to get out of the workshop, in terms of learning outcomes
+ Confusion over bcrypt solution & callbacks
  + issue is with implementing callbacks, not the concept of having to wait for something
  + some quetsions were really basic
  + e.g. when you have a function that takes a callback as a parameter, can you not just call it straight away  
  `var myFunc = function (param1, callback())`

Jen:
+ You can see from [the timings of the day](https://github.com/foundersandcoders/master-reference/issues/550) that this workshop was not long enough. After their struggles with previous workshops, FAC11 were also just relieved to finally have a workshop that they could complete in the timeframe.
+ The presentation was a really nice change of pace & Alexis happens to be a really good presenter. He's able to pitch his explanations at the right level and adjust to his audience on the fly. FAC11 were lucky to have Alexis in this scenario, but I'm nervous about the idea of our course moving towards something with a more mentor-led design than peer-led. This workshop could easily be made [more interactive workshop](https://github.com/foundersandcoders/ws-password-management/issues/7).

## [Cookies](https://github.com/foundersandcoders/ws-cookies/tree/ce87bb077c2c4068e2871066c5dddcd136b218c6)
Alexis:
+ Comma vs colon when adding flags wasted a lot of time. If that was fixed in the readme, then timing would have been good.
+ A couple of pairs got to the `auth check`
+ A lot of questions getting asked were around syntax. We need to figure out all the different ways you can set a cookie & put that in the solutions.

Jen:
+ Really really good workshop.
+ Everyone would have gotten to the auth check if they had started the workshop on time. In fact, it might have been [too short](https://github.com/foundersandcoders/master-reference/issues/557) if they had had 40 minutes more on it.

## [Client-side validation morning challenge](https://github.com/foundersandcoders/mc-client-side-validation/tree/52edea3164fe227ef1eed17df62cbef957021569)
Jessica:
+ Casted 3 people's solutions.
+ They didn't get to the end

Alexis:
+ Daunted by the size of the task. Lots you could have done.
+ Is the focus making the form look good or the validation? At least one team only did the CSS and didn't get to validation at all. Other pairs did the opposite.

Jen:
+ Reflection of the fact that this morning challenge was originally going to satisfy the "more HTML & CSS" proposal, before the suggestion of client-side validation.
+ This is a decent base, but could easily be improved upon if we were to think about what we want students to be able to do after completing the mc. It's a little too open ended at the moment.

## [Session management](https://github.com/foundersandcoders/ws-session-management/tree/60b71bcd175256ea8d8ebf7f806a281b462c0482)
Alexis & Jessica:
+ Confusion over HMAC
+ Presentation done last minute, but felt like readme wasn't strong enough on its own. God read the docs for this & that, etc. Readme needs to be improved.
+ Most students understoodthe significance of JWTs & why you use them, but not everyone. One person told me they actively avoided this part of the project, so I told them I'd walk them through it again some time.
+ Weaved in hashing and cookies nicely. In readme, recap could be stronger.
+ Confusion between JWTs & cookies - cookies are just containers.

## Callback morning challenge
Alexis:
+ Didn't go well. I had to apologise to them.
+ Some people got a bit out of it. Most just copying error first callback pattern.
+ Jen's point about setTimeout - students didn't really get it.

Jen:
+ It's not necessarily a bad morning challenge. It just doesn't address any of their problems with callbacks. Most of what I've written in issues on the repo came up as questions from students while casting their solutions.
+ I think I understand where a lot of the confusion lies & I've started making a morning challenge on callbacks, but couldn't get it finished in time for FAC11.

## Research afternoons
Jen:
+ HTTPS questions didn't lead students in the right direction enough. Needs rewording (at best). But HTTPS shouldn't be left to a research topic. Passing this information over a secure connection is too essential for students not to fully internalise.
+ Stateful vs stateless produced really good flow diagrams & mostly understood the advantages and disadvantages. But there were questions about which was more secure.
+ "State" is one of those words that gets used a lot without ever really being explained. After the stateful vs stateless, I verbally explained what "state" means (i.e. in the context of authentication, you can be in one of two states - logged in or not logged in). Then I explained that stateful/stateless is referring to your _application_ i.e. is your application where the state is stored (stateful) or is it stored on the browser (making your app stateless). There were a lot of "ohhhhh!" reactions. We should incorporate this into the course better somewhere.
+ Attacks were covered well, but this could easily be put into the workshops themselves.
+ Web storage had a really nice demo & the advantages/disadvantages were clearly explained. But it felt like this group had less to say. Maybe IndexedDb could be added?
+ Note: this was the first time that some students realised they could see cookies the Application tab in dev tools, even though it mentions that in the workshop.

## Projects
Alexis:
+ Didn't progress as quickly as I would have hoped.
+ They were doing everything we wanted them to do though - hashing passwords, storing in a database.

Jen:
+ Most students stayed really really late on both days (some working after midnight). We need to make sure that we're asking a reasonable amount of students in the project brief, but we should also be teaching students about project planning, scoping & time management. After all, they'll have to do it for themselves post-course and most alumni's projects overrun.
+ This project brief may not have felt so big if students had done more with databases the week before. Most only did one get request and one post request (one team didn't do a post at all) & some of the queries were extremely simple. [FAC9 project](https://github.com/foundersandcoders/resource-sharing/blob/master/src/queries.js) vs [FAC11 project](https://github.com/FAC-11/week6-kidneybeans/tree/master/src/queries).
+ Most teams set a cookie. Most didn't remove it.
+ Many students didn't use the HTTP only & secure flags. If they don't understand how important a secure connection is, that's a problem.
+ Students had a lot of questions during project time that would ideally have been covered in the workshops e.g. what an HMAC is, how bcrypt.compare works since we're not saving the salt in the database. Some didn't know to use `bcrypt.compare`.
+ A fair bit of confusion about JWTs.
+ Most students had deeply nested if/else statements in their handlers. Maybe we should have a clearer demonstration of nicely modularised handlers in prior workshops?
+ Client & server-side validation could easily be put in the course earlier (week 5?), so that it didn't feel like we were asking quite as much from them.
+ Students aren't remotely confident enough on testing. We're still hearing that there's "not enough time" for tests, or students are _trying_ to TDD but getting confused. We need to be introducing this more seamlessly, so that it becomes second nature like git & doesn't feel like a separate task.
