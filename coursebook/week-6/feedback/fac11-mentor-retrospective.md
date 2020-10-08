[Shot & Tape workshop](https://github.com/foundersandcoders/tdd-node-server-with-shot-and-tape):
+ Saw "walkthrough" and thought I should be walking them through it. If I were doing it again, I'd probably just let them go through the markdown file themselves and just float and help if they have any problems in setting up.
+ Confusion about payload and what it is
  + Is there a payload on the request or response? Where is it coming from?
  + Reflection of the fact that week 3 no longer has research topics? Linked students to [FAC9's readme on the structure of an HTTP requests](https://github.com/FAC9/READMES/blob/master/APIs/http-requests.md#requests-and-responses) & an explanation of body vs payload in [the HTTP spec](http://httpwg.org/specs/rfc7230.html#message.body)
+ Everyone got through exercises 1-3, maybe not to the bullet points.
+ They hadn't learned about streaming yet. Node Girls workshop touches on streaming but some students hadn't got to that point. At one point, when people where asking questions, just did a 5 minute aside, casting an example of a stream.
+ Not overly challenging. Just follow the written instructions. Gentle intro to the week.

[Error handling workshop](https://github.com/foundersandcoders/error-handling-workshop/tree/6b541b9d1190d1731e9c317d9e436b07bb210eb0):
+ Maybe better to set the expectation up front that they're not going to finish the exercise?
+ Walk through files and the structure that already exists.
+ Explain that they're just writing simple tests to begin with & to go onto shot.inject later.
+ Going forward, need more time for this workshop in general. But maybe that's not feasible this time round (Summer cohort)? Could move the node shell workshop (and make it shorter) into this slot and have the 3 hour slot on day 2 for error handling.
+ Elias went through it with us & we were more familiar with it, so we didn't really realise that it's so much to get your head around when all the concepts are new to you.
+ Readme and exercises seem kind of unrelated. Seemed like it was just too much for them.
+ Questions whilst floating weren't about exercises, because they hadn't gotten there yet. So people were dealing with the concepts and trying to get their head around it in different ways. Some were typing it into repl.it just to test it out and had questions but just because of their own typos.
+ I kind of get the theory. But even having read through it, I wouldn't really know where the right place to put try/catch in my code. I wouldn't feel confident with that. Error first callbacks, totally comfortable with.
+ Students were really worried about how little they understood from the workshop and we dedicated extra time to it later in the week
  + [Error handling - walkthrough](https://github.com/foundersandcoders/error-handling-workshop/issues/16)
    + Some people still didn't understand it. There were a lot of questions. Some students were definitely getting somewhere. Hence staying afterwards with people.
    + Put the difficulty of the workshop into perspective. It's too much. Too complicated.
    + Maybe that kind of thing should be a code along.
    + Elias is great but I'm always lost. If someone is miles ahead, maybe it's harder for them to understand the perspective of people who are struggling.
    + When we did the error handling workshop, I think I didn't totally understand. But then our version was completely different. I think a lot of our cohort didin't get it. We didn't have a lot of the context that they have now. But
    + [Old version](https://github.com/foundersandcoders/error-handling-workshop/tree/f1807cc61935c4e8d7748b075afbc089d993b660#functions-required) was much more structured: validateName, then validateAge, then validateEmail, etc. Only the bonus level required the use of shot. FAC11 started using shot in validateFilename.
    + No pre-existing code (`createRecord.js`) in old version.
    + continue: "Error handling workshop (people enjoyed this)."
  + [Error handling - extra support](https://github.com/foundersandcoders/error-handling-workshop/issues/17#issuecomment-318015872)
    + 5 students: one student cast their screen and we all wrote `validateFilename.test.js` and `validateFilename.js` together, talking through everything conceptually and each line of code.
    + Very positive feedback

[Node shell workshop](https://github.com/foundersandcoders/Node-Shell-Workshop):
+ People seemed to really enjoy it.
+ I wanted/intended to do lesson 1 at 10:00-11:30, have a short break and do lesson 2 at 11:30-13:00. But didn't want to set arbitrary time limits.
+ By 11:30, some had got to the end of lesson 1 but others hadn't. So we cast exercise 1-2. By 13:00 the slowest had just finished lesson 1 and the fastest had got most of the way through lesson 2 but didn't finish. So we cast exercises 3-4 of lesson 1 (since everyone had done those).
+ Maybe move onto lesson 2 together after the first 1.5 hours, and set that expectation up front. Then cast all the exercises of lesson 1 at the halfway point, from whichever students got that far. At the end, cast what the students have done for lesson 2, so that everyone can share each other's work for that lesson too.
+ Maybe have solutions folder?
+ Confusion in lesson 2 - students didn't understand what `writeStream.end()` & `writeStream.on('finish')` were doing. They commented out the code and it still worked. Didn't know why or what to tell them.

[Research afternoon](https://github.com/foundersandcoders/master-reference/blob/master/coursebook/week-5/research-afternoon.md):
+ [Changed structure of the afternoon](https://github.com/foundersandcoders/master-reference/issues/523)
+ Really good adjustment. The way they did it, in their project groups going through Travis & request module (things they will definitely be using), seemed like everyone was doing it and getting on with it. Instead of writing a readme of crap, more useful exercise. Everyone was switched on to the task at hand.
+ Good amount of time.
+ Most were looking at DWYL when looking over Travis. The way they say to set up your travis.yml file, the version they've put in there doesn't work with ES6.


[Request module morning challenge](https://github.com/RhodesPeter/request-module-workshop):
+ Solid content.
+ Just a little verbal explanation that helped them to kick off. Could be clarified with better comments above each function.
+ Clarify that this is a morning challenge, unconnected to the workshops from the day before. Don't worry about trying to implement new things you've learnt from the prior workshops e.g. try & catch.

[Intro to projects](https://github.com/foundersandcoders/master-reference/blob/master/coursebook/week-5/project.md):
+ Showed examples of FAC10's projects. Don't want to influence people too much. But it's a good way to show what they're aiming for in terms of functionality.

During projects:
+ People asking about why you would make API calls from frontend vs backend. For the context of this project, it is to practice doing something from the back end. You may be able to do everything from the front end. Making the browser do loads of computation will slow things down. Server having more processing power.
+ Should it update without us refreshing the page. We just expect you to do an API call and whenever you refresh the page, it updates.
+ Couple of people asking about config env. How does env2 work? - for those who haven't seen it before.
