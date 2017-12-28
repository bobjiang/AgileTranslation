<https://ronjeffries.com/articles/016-09ff/defense/>

Dark Scrum
Sep 8, 2016 • [Agile-Related, Dark-Scrum, increment, success]

Let’s talk about “Dark Scrum”. Too often, at least in software, Scrum seems to oppress people. Too often, Scrum does not deliver as rapidly, as reliably, as steadily as it should. As a result, everyone suffers. Most often, the developers suffer more than anyone.1

The theme behind a lot of my thinking lately is this:

Kent Beck, my original “Agile” mentor, once said that he invented Extreme Programming to make the world safe for programmers. It turns out that the world is not yet safe for programmers. Scrum can be very unsafe for programmers. To paraphrase Ken Schwaber, one of the co-creators of Scrum, in another context: “That makes me sad”.

Scrum, done even fairly well, is a good framework. I’m quite sincere about that. It’s good to have a strong connection to the business deciding what needs to be done, and what needs to be deferred. It’s good to have all the skills you need to build the product right on the team. It’s good to build a tested tangible product every couple of weeks, and it’s good to show it to stakeholders, and it’s good to review how things went and how to improve them. I’ve studied, worked with, and thought about Scrum for years, and everything about it is really quite good. Not perfect, but really quite good.

Unfortunately, that’s Scrum as a concept, Scrum as an ideal, Scrum done as intended. Like every good idea, the reality sometimes falls short. Sometimes it falls far short. I call the result “Dark Scrum”.2

Dark Scrum: Some Typical Abuses of Scrum
Let’s look at how things can go wrong in Dark Scrum, in just a few steps. In this section we observe a team experiencing Dark Scrum. The Dark Scrum leaders mean well: they’re just doing it wrong.

Self-organization is slow to happen.

Clearly it takes some time to get good at Scrum. It has new roles and activities. Even more difficult, it asks that we take on new values. We’re supposed to let our developers self-organize to do the work. It’s easy to call the Scrum meetings and call ourselves by Scrum roles. It’s not at all easy to really walk the walk.

Scrum generally starts with very few people trained, even fewer understanding it, and a lot of people who think they know what they’re supposed to do. It should be no surprise if they do it wrong, and very often they do.

Often, today’s power holders3 believe that their job is to decide what their people should do, tell them to do it, and see that they do. Scrum teaches otherwise: explain what needs to be done, then stand back and let the people self-organize to do it.

People can’t just click over into Scrum’s new mode of operation. It takes time to unlearn the old ways. It takes time to learn new habits, time to learn to trust the team. It takes time for the team to learn how to be trusted: in a way that’s the underlying message of this article. Scrum’s training begins this learning process for the people who get the training.

Dark Scrum begins when people who know their old job, but not their new Scrum job, begin to do the Scrum activities. It goes like this:

Awesome, we can help the team every day!

Every day, the team is supposed to get together and organize the day’s work. This practice, the “Daily Scrum”, is imposed on the typical team. There might be one person in the room, the ScrumMaster, who has been told how it should be done. The programmers haven’t been told. Quite often, even the Product Owner hasn’t been told. Almost certainly other power holders haven’t been told.

But the power holder already knows his job. His job is to stay on top of what everyone is doing, make sure they’re doing the right things, and redirect them if they’re not. How convenient that there’s a mandatory meeting where he can do that, every single day!

The result: instead of the team rallying around their joint mission and sorting out a good approach for the day, someone else drags information of of them, processes it in their head, and then tells everyone what to do. Since nothing ever goes quite as we expected yesterday morning, this improper activity often comes with a lot of blame-casting and tension.

Dark Scrum oppresses the team every day. Self-organization cannot emerge.

We also have convenient frequent planning!

Every Sprint, the Scrum Product Owner is supposed to meet with the team, and describe what’s needed. The team then figures out what they can do to meet the needs, and begins to build it. Well, that’s the theory. In practice, there may not even be a business-side Product Owner. Even if there is, odds are they are not trained in how to be a Product Owner.4

Well, the power holders may be new to Scrum, but they know a lot about how to handle this problem. So every two weeks they show up and tell these programmers what they have to build. Oh, those programmers will push back. They are lazy, and recalcitrant. But the power holders keep the pressure on, because that’s how you manage people. So they tell the team what to do and they’d better do it.

Of course, power holders have little or no idea how to program, and the programmers usually at least have some clue. They have no idea what the state of the code is, and the programmers usually do know. The programmers are supposed to decide how much work to take on in Scrum, but in Dark Scrum, power holders know better. They pile it on. They see that as their job: drive the team.

The results never vary. The team sincerely tries to do what is demanded. They know there’s no point in saying it’s impossible, even though it is. They’ll just get berated for being lazy, stupid, trouble-makers. So they do their best and it isn’t good enough.

At the end of the Sprint, results are not what was demanded. Magic has once again not happened. The developers have failed again. Fortunately we have just the chance to set them straight: the Sprint Review!

We get to critique what’s done – and what’s not.

Every Sprint, stakeholders look at what the team has accomplished and provides guidance on how to go forward. Great theory, rarely done in practice when organizations are not expert in Scrum.

In practice the Dark Sprint Review begins by someone reminding everyone what the team “promised” to do. (That is, what was demanded right before the team said “We’ll try”. That’s a promise, isn’t it?) Then we look at the pitiful failure the team brings us.

Guess what. The organization demanded more than could be done, and they didn’t get it. The team tried, and in trying, they took every shortcut they could think of to get all those unreasonable requests finished. They skimped on testing. They skimped on design. They even worked when they were too tired to think straight.

They fell short and what they did accomplish wasn’t very good. The team failed. Again.

Fortunately, Dark Scrum has power holders, Product Owners, and stakeholders for this effort. They make sure the programmers are made fully aware of how badly they’ve done. That will surely inspire everyone to do better next time. To help with that, we have the Sprint Retrospective!

We get to tell them how to improve …

In the Sprint Retrospective, the team looks back at the preceding Sprint, and at prior history. They observe what has gone well and what has not gone well. They figure out how to improve their process for next time.

In practice, Dark Scrum leaders help them with that. We remind the team that they fell short, despite how closely we were managing them. We make it clear to these developers that their failure — and it is a failure — was surely due to a combination of laziness and incompetence.

To inspire the team to do better, we point out the consequences of not improving, which will almost certainly include the rolling of heads. That always gets their attention.

Sometimes the team will offer suggestions. Let me prepare you right now for that. Here are some things they might say, and how you might answer them:

Developers: We need to do more testing to reduce the bug count.

Power Holder: No. You’re already falling behind on features. You need to code smarter. Stop putting in bugs and you won’t have to remove them. We need features, not tests!

Developers: The design is getting crufty. We need to refactor to improve it.

Power Holder: No. Why did you write a crappy design in the first place? No one told you to write a crappy design. Stop doing that and fix what’s wrong. There’s a weekend coming up. Do it then!

Developers: The requirements are unclear, they don’t get clarified, and then what we build gets rejected at the last minute.

Power Holder: We hired you to be smart and figure things out. You’re supposed to self-organize to solve these problems. Quit sitting on your asses and build what we want!

You get the idea. Keep these people’s nose to the grindstone, and their feet to the fire. That has always been what it takes to get software done. Scrum doesn’t change that.

Wow, that was depressing.
Well, of course, Scrum is actually trying to change all that. But until the hearts and minds of the organization actually change, there’ll be too much of the old-style management happening … and now it happens every couple of weeks … often every single day!

What can we developers do?
The things that happen in Dark Scrum are abuses. They really are in opposition to what Scrum tries to teach us. No real Scrum expert would recommend any of these things. People who do these things are not “doing it right”. Everyone agrees about that. Still, Dark Scrum does happen, and it happens far too often. In my view, abuses are almost inevitable until people really learn Scrum’s principles and values.

It might seem that there’s nothing a development team can do but accept oppression. Fortunately, that’s not the case. The good news is that there’s something very powerful that we can do. The bad news is that it isn’t easy. The other good news, though, is that it’s mostly about programming and we’re usually pretty good at that.

Much of the pressure from Product Owner and/or other power holders comes because they can’t see clearly what we’re working on, what we’re actually getting done. If we can make progress crystal clear,5 we can change how we’re treated.

If the product has a lot of known defects, our leadership will assume that there are even more, and they’ll be afraid. In their fear, they’ll put us under even more pressure, and since fear often manifests as anger, they’ll be angry with us. Often, very angry.
If we’re working on design or infrastructure before features, features seem to come out slowly. This makes our leaders afraid that we’ll be late or fail to deliver important features. Again, we are subjected to fear and anger.
If we slow down because our design is falling behind, we produce fewer features. Fewer features, more fear, more anger, more pressure.
When leadership cannot see working software, they become afraid about the future — and rightly so. They show that fear, invariably, in ways that are not helpful, and that are generally painful. Developers can stop that from happening. The only way I know is to deliver software. Real, live, working software. With visible features!

The Power of the Increment
Scrum asks us to deliver a tested, integrated, working, shippable increment of the product, at the end of every Sprint. We’ll talk shortly about how to do that. For now, let’s imagine that we can do it: we have the ability to deliver a working product increment every couple of weeks.

Much of the fear will go away by itself, because leadership can see real results. Some will remain, however, because quite likely real results lag behind their hopes and dreams. Everyone hopes for a sports car, but sometimes you only get a bike. Maybe you wanted a pony, but you only get a dog, not even a cat, which a man could at least respect. (But I digress.)

Still, with a solid increment in hand, tested, integrated, containing the most important features they’ve given us to do, we can change the conversation:

Power Holders: You’re not getting enough done: you have to do more.

Developers: We’re doing all we can, and we’ll keep trying to improve. Meanwhile, all this works and is usable. It might be wise to use our real rate of delivery to predict how fast we’ll go. It might be best to have us work on the most important backlog items first. It might be best to trim each item down to be as lean as possible.

This won’t just work magically right away. But it will begin to help, and the more true and real our product increment is, the more it will influence people to look at reality and base their management on it. Contrary to what we often think, our leaders are not stupid. They’re doing the best they can with the information they have. If we can give them better information, in the form of working software, they’ll begin to use that information. Using that information, they’ll resort to less pressure and less abuse.

Again, this isn’t magic and it won’t happen overnight. However, I’ve seen it happen time and again. Other than in the most dysfunctional organization on earth — and only a few of you readers actually work there — it will work, if we keep at it.

There’s a catch.
There’s always a catch. The catch here is that in order to change the conversation, in order to reduce pressure and abuse, the increment must actually work. It really has to be tested, integrated, ready to ship, containing all the backlog items we’ve undertaken to do.

That isn’t easy. Worse yet, we didn’t learn in Computer Science how to do it. We didn’t learn in Software Engineering how to do it. We can’t learn how to do it at IT Tech Institutes, and we won’t find it in Your Favorite Language for Dummies. There are practices that are specially formed to allow teams to build software incrementally, keeping it well tested, well designed, focused on features, and ready to go at all times.

If we’re going to change Dark Scrum into Scrum as She Should Be Played, we need to learn these practices. Fortunately, they’re not that hard to pick up, although like all programming, they do require practice and hard work if we want to be good at them. Later in this series we’ll look at them in more detail, but let’s look at some of them briefly here:

Acceptance Testing

It is quite common for there to be disputes, at the end of a Sprint, about whether the team did or did not build what the Product Owner “wanted”. These disputes are wasteful and they tend to drive Product Owner and developers apart. We want them working closely together, not fighting with each other.

One very strong practice is for the PO and the developers to agree on concrete, executable acceptance tests for each story. It can be productive to think of these as “examples”.

Team: OK, we want the system to show all the organizations’ accounts that are 30 days in arrears, and a total of the arrearage. Here’s a table of accounts, and a table showing what the identified accounts would look like, with the sum.

PO: No, that’s not quite right. We don’t want to show them at thirty, only beyond thirty.

Team: OK, like this then?

PO: Right! Go for it!

Each little example becomes an acceptance test for the story or backlog item in question. By convention, if the tests don’t run, the team has not finished that story. Conversely, if the tests do run, the Product Owner and team agree that we have done what was asked.

It’s possible, of course, that the Product Owner won’t like what she sees. But now the conversation has changed. She can’t legitimately say “That’s not what I wanted”. It is what she wanted when we agreed. She has learned something and now wants something different. That’s just fine, it’s the PO’s job to find her way to the best possible product. Working from concrete acceptance tests helps us understand what’s being asked for, helps us know when we’ve accomplished it, and helps us know when we’re refining our understanding and asking for something to be changed.

As an important bonus, when we automate these examples, we can run all of them and show with certainty that the product is still doing what we agreed it should do.

Incremental Design

In a Scrum project, we’re supposed to deliver a tested, working, potentially shippable Product Increment after each Sprint. Obviously, we can’t have the whole design figured out at the beginning: we only know roughly what the product will even be. Equally obviously, we need to wind up with a good design at the end. Therefore, the design of our software must be created incrementally, a bit at a time.

That’s OK: when the product is small and incomplete, it doesn’t need much of a design. As it grows, it needs a larger, better, more robust design. We just need to grow the design as we grow the product.

“Just”. The most dangerous word in software development. Building up the design as we go is difficult. It requires skill in design, skill in testing, and skill in refactoring. We’ll explore those here below, and in other articles in this series. Over time, we’ll point you to some resources on the subject.6

But the fundamental truth remains: if we are going to deliver a Product Increment every Sprint, we must find a way to do good design, incrementally.

Refactoring

The best way we know today to do incremental design is called “Refactoring”. Refactoring is the process of improving the design of existing code — without breaking it!

Refactoring isn’t rewriting. Certainly if we have a program with a bad design, we can write a new program, using a better design. Probably I should say here “just write”, because that trick rarely works. But in principle we could. It would take a long time, however, and in Scrum we don’t have a long time: we need a better design by the end of the current Sprint.

Refactoring is a process of transforming the code, usually in very small steps, to make it better. Modern IDEs help us with this: most of them offer a number of automated refactorings. They can extract a commonly-used bit of code and turn it into a method or function. They can move code from one class to another. They can rename things, or change the signature of a method.

Using refactoring well, we can incrementally improve our design as we go. The operative word is “well”, however. We do have to build up that skill.

Incremental design improvement is necessary. Refactoring is how we do it.

Programmer Testing

We need programmer tests in addition to acceptance tests. Every feature we build is composed of many programming steps. In any of of those steps, we could make a mistake. We avoid these mistakes using programmer testing. One very good form of programmer testing is Test-Driven Development, which goes like this:

Think of some small next step on the way to our feature. Write a test that should run when that step is complete. Run it: make sure it doesn’t work now.
Build the code to make the step complete. Run the test: make sure it works now.
Check the code to see if it looks clear enough. If not, refactor it. Run the test again to be sure everything still works.
Repeat until the feature is done.
This isn’t the only way we can do things, but it’s one of the best we know right now. One way or another, it’s very helpful to have a lot of little tests supporting each larger acceptance test, because the little tests tell us which bit we got wrong, while the acceptance test just screams “Something Broke!”

These tests also help us with larger refactorings. I suppose a perfect TDD programmer could do all her design improvement in the TDD cycle, but my experience is that sometimes I don’t notice a design problem right away. When that happens, I may need to put in some extra refactoring effort the next time I’m working with that code. Just like when we develop a feature, our tests can help us be sure we haven’t broken anything with our design change.

Continuous Integration

Scrum requires a running, thoroughly-tested, usable increment, containing the value of all the backlog items from previous Sprints: a complete, running, tested, operable program.

Obviously, this requires that all the team’s work must wind up integrated, tested, and working together by the end of the Sprint. Delayed integration uncovers problems, many of which require substantial debugging. The longer we wait, the worse it gets. Conversely, if we integrate after making small working changes, it becomes much easier.

An automated build process, running the system’s test suite, turns out to be an essential part of a Scrum team’s development process. For most teams, the more frequently they build, the better things go. Building “all the time” seems to go best, which is why this practice is called Continuous Integration.

Surviving Dark Scrum
TL;DR

There is a common, perhaps inevitable Dark Scrum stage in many Scrum installations;
Dark Scrum situations follow a common pattern;
The Dev Team can make things better for themselves, and can move Dark Scrum toward real Scrum, a better place to be.
If you’d like to provide input, my email is open at ronjeffries at acm dot org.

Alexey Krivitsky has translated this article to Russian, and oh boy is it dark! ↩

This seems to me to be a good term to describe abusive forms of Scrum. If you agree, please begin to adopt the term. If you’re so inclined, I’d appreciate a tip of the hat for giving a name to an important topic in the history of “Agile” and Scrum. ↩

In this article, I’ll be using the term “power holders” to mean all the people who, especially in Dark Scrum, have and exert power over the developers. These people all mean well. However, in Dark Scrum, the use of power is often misguided, whether by a development manager, a team lead, a Product Owner, or even a ScrumMaster. All these people have legitimate places in real Scrum. In Dark Scrum, they just haven’t found those places yet. ↩

As of September 2016, there were 388,000 Certified ScrumMasters, 82,000 Certified Scrum Product Owners, suggesting that nearly 80 percent of teams are without a trained Product Owner. These figures also suggest that there may be as many as one or two million programmers “under” these ScrumMasters. There are between ten and fifteen million professional programmers in the world. We have a ways to go before they’re all safe. ↩

No pun intended. ↩

See, for example, The most dangerous word in software development. ↩