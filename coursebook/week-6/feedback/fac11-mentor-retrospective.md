## [Postgres week](https://github.com/foundersandcoders/master-reference/blob/443760c4dfd035546d610f56a311a6074f5ef56b/coursebook/week-6/README.md)

#### London

Alice & Philippa:
+ Much better than ours (FAC10's). They got it pretty well. All the installation issues were sorted out.

@macintoshhelper:
+ The week seemed good. Installation and pg went well. The `postgres-workshop` workshop went a little slowly - might be worth cutting out easier questions, and have some explanations/resources for JOINs here, maybe a code-along for explaining JOINs.
+ Could have covered some things in more detail: JOINs, schemas, user permissions/security

Jen:
+ This week feels very much like a work in progress to me. FAC10 struggled so much with this week that it feels like a lot of it hasn't been fully user tested before. So this week there was a real push around raising issues as/when they arose.
+ Really need to rename the workshops to something more descriptive & define learning outcomes for each one, so there is a clear separation between the things people are supposed to gain from each one.
+ Some things that were in research topics for FAC9 now feel like they're missing from the course:
  + _How_ to design a schema. FAC10 & FAC11's schemas (so far) have been extremely simple, but as soon as they get bigger, it will throw up more questions. e.g. Understanding concepts like when to add another column to a table and when to pull this out into a table of its own.
  + Solid explanation / workshop that explains different types of JOIN.

#### Nazareth

+ Shireen, Yvonne: went really well

### [Steve's talk](https://docs.google.com/presentation/d/1OHoYDQoMkSiJI8X_SEq28z3tkw6MDbHRfHtKDwAphZg/edit#slide=id.p)

#### London

Alice & Philippa:
+ Same as what we had in FAC10. Really good intro to the way databases work. Nothing I would change.

@macintoshhelper:
+ Good overview. People didn't seem to wonder/question what a database is needed for, which seemed to be an issue before.
+ A more in-depth explanation of static file vs database might be nice.

Jen:
+ If we're going to include more mentor-led material, it's essential that this is recorded, so we can make it available to other campuses.
+ I would advocate for the same presentation being used in other campuses! It's pitched at _exactly_ the right level & each section is necessary knowledge:
  + High-level concept of ["what is a database?"](https://docs.google.com/presentation/d/1OHoYDQoMkSiJI8X_SEq28z3tkw6MDbHRfHtKDwAphZg/edit#slide=id.g234bb6de5c_0_42)
  + Analogies with real-world problems (e.g. a database being like a physical library)
  + Throwing out questions to the students is great for keeping it interactive :heart: & engaging their creativity
  + Distinction between concepts: an actual database, the language itself, the DM system, a schema, the client. Students actively requested for [this slide](https://docs.google.com/presentation/d/1OHoYDQoMkSiJI8X_SEq28z3tkw6MDbHRfHtKDwAphZg/edit#slide=id.g234bb6de5c_0_69) to be shared around
  + Students suggesting "relationships" to go in [this table](https://docs.google.com/presentation/d/1OHoYDQoMkSiJI8X_SEq28z3tkw6MDbHRfHtKDwAphZg/edit#slide=id.g234bb6de5c_0_79) (it was empty at the start). Great way to explain one-to-one, one-to-many & many-to-many conceptually. But taking suggestions from the students could be hard for someone less experienced (Steve used to be a Database Administrator). I think "siblings" would have been hard for another mentor to answer accurately.
+ FYI, the talk only took 45 mins, not quite an hour. I seem to remember that this might have been true during FAC10 too.

#### Nazareth
+ Talk was done by Shireen and Zooey
+ Yvonne: Shireen and Zooey did really good job

### [Installation](https://github.com/macintoshhelper/learn-sql/blob/master/postgresql/setup.md)

#### London

Alice & Philippa:
+ Some misleading things but they're all in issues. Elias might even have sorted them out?
+ Remember [one thing that caused confusion](https://github.com/macintoshhelper/learn-sql/issues/8) - some commands for MAC installation that would have made sense as one big script but had comments in, so needed to be done line by line.

@macintoshhelper:
+ This went much better than before. The main issues should be solved now.
+ Any further feedback would be great, especially on Linux (people using other distros, etc).

Jen:
+ Elias did an amazing job. The instructions are really comprehensive. But there were still [a few issues](https://github.com/macintoshhelper/learn-sql/issues?q=is%3Aopen+is%3Aissue). The reason this wasn't a problem was because the mentors and I were very very active in floating and helping.
+ With something like installation instructions, it's very difficult to cater for all the different scenarios that might arise, especially since this is the first time Elias' setup instructions had been used with a cohort. One thing that _really_ helps is to really hammer home the message for students to raise issues based on their experiences. You can gain a lot from them screen shotting their error messages, for example.

#### Nazareth

+ Yvonne: why not just install psql during installation party?
+ Lubes: why not install it the weekend before?
+ Zooey: people who had problems were those less comfortable with their linux systems.\
+ Yvonne: agree for FACN3, should install beforehand
+ Suha: have office hours on Sunday morning to help those that didn't manage to install.
+ Zooey: there's better troubleshooting documentation coming soon.

**AP: get people to install it the week before, raise issue on MR week 4**

**AP: have office hours on Sunday morning w6**

**AP: Stefano should raise issues documenting how he solved his issue**

**AP: document all problems**

### [SQL commands intro workshop](https://github.com/foundersandcoders/sql-commands-intro/tree/d859783e708f655fbe307a4746fe9e26fdf41777)

#### London

Jen:
+ Really solid intro to the commands! But it was the first time this has been delivered, so there were [some inevitable teething problems](https://github.com/foundersandcoders/sql-commands-intro/issues) & [this PR](https://github.com/foundersandcoders/sql-commands-intro/pulls) with the solutions still to be merged.

#### Nazareth

+ some people didn't do it bcos installation
+ Yvonne: not a big deal, it's all in the next workshop.
+ Yvonne: but those who have installation problems are probably those who might have more problems picking up the stuff.

### [Day 1 Afternoon workshop](https://github.com/foundersandcoders/postgres-workshop/tree/156cc84cc7af703977c9c9f4e171c96276a2672a)

#### London

@macintoshhelper:
+ This went quite well, but people didn't get much time to do some of the JOIN/subquery stuff. Removing more basic questions and replacing with simple JOINs with explanations would be good.

#### Nazareth

+ Generally good.
+ Suha: main problem this week with workshops was timing. Not that people don't get stuff, just not enough time.
+ Zooey: makes sense, do as much as you can is a good format for a workshop
+ Lubes: sometimes there is really important stuff people don't get to
+ **Zooey: generally, I recommend being really strict on timing.**
+ Lubes: sometimes if you feel something is less important, you could cut into that time
+ Zooey: make sure it's the mentors making that decision, not the students.

### [Code along](https://github.com/foundersandcoders/pg-walkthrough/tree/80cf77383662a782a104daa60ce97f3f2fb3c641)

#### London

Alice & Philippa:
+ Code along took a lot longer than planned (10am-1pm). Maybe a lot of time needs to be set aside for that? FAC11 were asking a lot of questions. If you're really going to understand what's going on on every line, you need to ask, but then it inevitably slows things down.
+ Questions around ES6 syntax.
+ There's a lot of conceptual stuff to get your head around in `db_connection.js`. Still felt like complete magic to me. Actually learned a lot of it myself while Elias was walking students through it.
+ Jen and Alina were ill that day & I (Alice) was there when they were caught up & Yahia was explaining it to them so well. He knew it line by line!
+ Kind of find code alongs useful, because things get explained to you in more depth than you usually do. But because everything is new to you, you don't actually understand everything as fully as you think you do at the time. Then later you realise there are all these holes in your knowledge and you don't really get it.

@macintoshhelper:
+ This was good, better than FACN1. An emphasis on understanding it completely resulted in it taking a long time.
+ I've refactored the mentor walkthrough so code is written first in chunks, then explanations are given after on ES6, pool, etc.
+ Making sure people have an understanding of how pools/connections work, number of max connections is good - so people avoid database apps from crashing due to pool query callbacks hanging.
+ Encouraging people to write notes in comments would be great - so they can return to their own explanations.

#### Do code alongs even work??
+ Alice: I find the explanation line by line really really good. But I don't know whether they need to be typing it out themselves at the same time.
+ Philippa: With code along you're concentrating on the syntax without really learning it. Half the time the reason you've missed something is because you've missed it on the screen.
+ Jen: One of the most useful code-along experiences I've had was when other people were having more environment-related problems than me, so I had time to take notes on what the mentor was saying. I have comments for each line of code that was written...until everyone else sorted out their problems and then I was back to frantically writing down the lines as they were speaking.
+ Alice: I would absolutely love it if we had time to take notes.
+ Philippa: Sometimes you don't quite get it because you don't know what's coming up. Like if someone is writing a line where they're initialising a variable and you're going "ok sure...don't know why yet" but you just have to trust that it's necessary & it will all become clear later.  
If you were with someone you might say "what they hell is this". But you don't have time and the pressure is on to just keep typing to keep up.
+ Philippa: So maybe if you had the document in front of you, already written, and your job was just to take notes while someone is presenting?
+ Jen: Wouldn't that be even more of a distraction? How can you read through existing code and listen?
+ Philippa: Being able to look through yourself and try to understand what's coming next could feel quite empowering.
+ Philippa: Sometimes you have vague understanding from skimming and then there are things that you need to fill in gaps on. People might have better questions if they've already had a chance to skim it. Going into it blindly, it's just so hectic. So you assume that.
+ Jen: That's really interesting. Sounds a lot like some techniques I was taught on a Teaching English as a Foreign Language course!  
And interestingly, that was the exact feedback from a few people in FAC11 about week 3's workshop on HTTP requests & APIs (i.e. readme, then Q&A format). They said that telling people the questions up front let's them know what they're looking for when they do the reading. I think it might even have been the students who have a background in teaching that were making those suggestions.

#### Nazareth

+ Lubes: went on for 2.5 hours, can't be sped up at all.
+ Yvonne, Suha: was good, and important.
+ Lubes: I felt this codealong had too much to write before actually running anything.
+ Lubes: was good recommending them to write their own comments
+ Shireen: have some files ready, some have to be coded-along

#### Gaza

@noureldeansaed:
+ Having separate steps could work against not with the wanted results from the codealong, if everything was directly attached and intact from the beggining to the end, FAC students would grow better understanding of what is what and which is which.

#### Codealongs in general
+ Noureldean: I think the only reason this partiular codealong is different is that there's an almost-identical workshop after it that allows the FAC students to immediately. To me I think codealongs are awful, when I was a student I got mostly nothing out of codealongs, but this way, it could work.

**AP: lubes raise issues on the workshop maybe**

### [Afternoon workshop](https://github.com/foundersandcoders/pg-workshop/tree/c1afd3edcc424060d19435e5d81942452c38c25e)

#### London

Alice & Philippa:
+ [Issues with solutions. Said it doesn't work.](https://github.com/foundersandcoders/pg-workshop/issues/32)
+ Philippa: No CSS challenge. Tacked on at the end.
+ Alice: One student did it in their own time and totally nailed the CSS task.
+ 1.5 hours late so they only had half an hour for it. They all did it for another half an hour during research afternoon.
+ Most people got to the post bit.
+ I'd happily go home and do the POST challenge, but I wouldn't bother with the CSS bit. I would if it were during the time allotted for the workshop, but since it wasn't...

Jen:
+ You really want to make sure everyone gets to task 3. I don't think everyone got there and if they don't, they might not post anything in their projects. It's the perfect way to introduce people to the fact that you can send a request to an endpoint from within an HTML form.

#### Nazareth

+ Suha: was good because of the code-along, but they asked a lot of questions, but they 20/20/20'd well
+ Suha: timing maybe an issue

##### Aside 
+ Zooey: had a moment of 'why are you asking me this? you should be debugging this yourself'
+ Yvonne: depends on philosophy of mentoring, should we be teachers or is it more peer-led?
+ Lubes: improvements need to be made in curriculum
+ Yvonne: they need to trust each other more
+ Zooey: maybe try to enforce 20/20/20 more, they need to rely on themselves more, especially as we near the 2nd half of the course
+ Suha: we should agree as mentors beforehand how much help to give, maybe workshop specific (e.g. fine in codealong), as students will just ask the next mentor, damn them!
+ Zooey: workshops, agree, let people struggle a bit more, less mentors in the room
+ Yvonne: sometimes goes off to research a student's questions on her own, and they fix it when she returns...

**AP: enforce 20/20/20, and call them out for not researching it**

### [Research](https://github.com/foundersandcoders/master-reference/blob/27e8a245ff2f1e80b954b775120dad0c3a7219a0/coursebook/week-6/research-afternoon.md)

#### London

Alice & Philippa:
+ Testing still needs clarification. Hard to find examples online with tape. Haven't found a good "test your database with tape" article / resource anywhere.
+ Ideally have some kind of session on testing where we work through it together instead.
+ Sometimes research afternoons are more beneficial than others. This isn't one of them.

@macintoshhelper:
+ Might be nice for people to collaborate on improving a central README for their topic. For database testing, it would give people somewhere to start, but they might find a way of improving it.

Jen:
+ Lots of mounting frustration with research topics. Especially when the questions aren't fully vetted. Ideally, when the week gets created, people would be attempting the research themselves, based on the questions that are being asked, to see whether it's achievable to google those terms and get something useful back. Or at least have in mind what we want students to get out of that research topic.
+ During presentations, students often ask mentors about things which they couldn't find the answer to themselves. At that point, it becomes obvious that there was no particular plan for what the students were supposed to get out of answering the question.
+ Often, we end up sharing FAC9 and FAC10's research afternoon readmes with them. It seems like a waste for one cohort to do a really good readme, then have that knowledge go unused and get lost for the next cohort.

#### Nazareth

+ we dropped testing.
+ and had less time, as workshop ran over
+ Yvonne: script injection was quite important, but maybe not done that well
+ Suha, Zooey: script injection should be covered elsewhere
+ Yvonne: this week was much worse than last week's fun projects

### [Morning challenge](https://github.com/foundersandcoders/db-morning-challenge/tree/681fbba3e70c4ab9c882e50558673aab68d6e7e1)

#### London

Alice & Philippa:
+ Good but maybe move no.2 into "bonus" section?
+ Really there's 4 questions. Don't know why 2a and 2b.
+ Question 1 is not the easiest amongst those questions. So maybe just re-order them. At least one of the question 2s is nicer.

Jen:
+ People loved having clear instructions on hosting with heroku and found this very useful during their projects.
+ Lots of people didn't finish challenge 1.
+ This feels like a huge jump from the relatively simple things they were doing in the days beforehand. Maybe a slightly more gradual step up first?
+ Would be good to have the schema written somewhere in the readme.

#### Nazareth

+ Suha: was good, even had a student demonstating at the front of the class and a lively discussion
+ Mario: we only did the first task
+ Zooey: maybe change the 3rs to optional extra stretch
+ Generally went well

### [Project](https://github.com/foundersandcoders/master-reference/blob/7f2c1668ab25658a042ca4077678f0e456c722fe/coursebook/week-6/project.md)

#### London

Alice & Philippa:
+ Seem really good with projects. They're way ahead of anything we did.
+ Some of the groups are alright now. But lots of questions about how to test e.g. whether they're supposed to have 2 databases. Didn't feel confident because we're no experts.
+ Better introduction to environment variables? It's introduced via a research topic and some people don't seem to totally understand them.
+ This week was a bit weird. Felt like they didn't really need us.
+ Had a few questions during office hours and had people come upstairs once. But very little.
+ Had an easier time than us because we scrapped ElephantSQL :+1:

@macintoshhelper:
+ Having specific SQL query requirements would be good: such as requiring a JOIN, SELECT, INSERT INTO, subquery, etc.

Jen:
+ Project brief could be improved to ensure that students end up using more complex SQL commands? (debatable)
  + Giving students more free reign led to some really interesting and different code. There was a lot more variation between the things that teams were trying to do, so presenting to one another was much more interesting! e.g. server-side validation, more complex DOM manipulation than you ever normally get to see in FAC projects
  + On the flip side, if the learning outcomes of the week are about postgres, most teams had only 2 SQL queries and they were sometimes very basic. If we wanted them to focus more on databases themselves, we could update the brief so they are required to make a post request (and therefore insert something into their database rather than just using `SELECT`) & specify a requirement that would get them to make at least one type of join.

#### Nazareth
+ generally going ok
+ Zooey: most questions related to setup, not SQL

