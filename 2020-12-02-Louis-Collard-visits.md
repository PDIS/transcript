# 2020-12-02 Louis Collard visits

### Audrey Tang:
All right, this autumn/December thing. \[laughs\]

### Louis Collard:
Yes, cool. Thanks very much for chatting with me.

### Audrey Tang:
Sure.

### Louis Collard:
I’m Louis. Should I give you a bit of background on me?

### Audrey Tang:
Sure.

### Louis Collard:
I moved to Taiwan at the end of 2017. I’m a software engineer, and I just wanted to talk to you about a project that I’m working on.

### Audrey Tang:
Is it online somewhere?

### Louis Collard:
Not yet.

### Audrey Tang:
Not yet, OK.

### Louis Collard:
It will be, yeah.

### Audrey Tang:
OK, cool.

### Louis Collard:
I guess I’ll start with some context, otherwise it won’t make so much sense. I used to work for Google in London. I worked on the display ads product. We worked with lots of publishers, and obviously, their business is making money from ads. I worked closely with them, helped them and see how they optimize their websites for making more money and stuff.

### Louis Collard:
Then, when I was working on that team, websites like BuzzFeed started to become popular. When BuzzFeed first started, it was like, “Seven Flavors of Ice Cream You Should Try Today,” or whatever.

### Audrey Tang:
Clickbait?

### Louis Collard:
Yeah, exactly. That was, I guess, they took it one step further. As well as optimizing the ad layout for monetization, they were optimizing the content itself, clickbait. At that time I thought, if people want to spend some time on Facebook and read some articles about ice cream flavor or whatever, then fair enough.

### Louis Collard:
Over time, I saw those people, people saw this and got wise to it, and those kind of content or traffic optimization techniques got a bit more advanced and more subtle. Then, at the same time, the news, people stopped buying paper newspapers, and people like my mom or whatever will read the news on her phone.

### Louis Collard:
You had two things. You had the news no longer has stable print revenue, so it’s more reliant on advertising revenue than before, and people are consuming it on their phones. The consumption patterns are different. It’s like…

### Audrey Tang:
Yeah, the second is like news feed. It shares the word news, but it’s not quite news.

### Louis Collard:
Right, yeah, and it’s competing for your attention with Instagram, Facebook, and everything else. What I learned has happened was that the good news, the broadsheet newspapers that are supposedly good quality, actually were employing a lot of the same, similar or variations of the kind of traffic optimization techniques that sites like BuzzFeed or whatever had originally developed.

### Louis Collard:
Then the reason I started to care about that was, to be honest, was Brexit. I was living in London at the time, and I don’t know how much you followed that.

### Audrey Tang:
There was a movie about it.

### Louis Collard:
Yeah, exactly, yeah. I have close friends who voted for Brexit, and that’s fine. That’s everyone’s own decision, but I think what I’ve found quite sad or not great was that there was no real proper, informed discussion. It’s super complicated. It still hasn’t even happened, really, until New Year’s Eve. I don’t think anyone really knows what’s going to happen.

### Louis Collard:
All of the coverage in the news that was out there was just very emotionally triggering and not based on fact at all. There was just a complete breakdown in discussion. Then Trump happened in the US. I guess that the real root causes are probably similar to why Brexit happened. Again, you see in the US press, it’s just like this complete…

### Louis Collard:
I started to think that there are some newspapers which you probably know that are not super-good quality, but that’s fine. It used to be, in the UK, at least, when you go into the news shops, the tabloid papers, they’re physically smaller, and the label on the top is red. The broadsheets are physically bigger. There’s a clear difference.

### Audrey Tang:
It’s called a broadsheet for a reason.

### Louis Collard:
Yeah. You know you’re getting into. Also, the papers are all laid out next to each other, so you see the other headlines, and you see the paper and read it. You get an overview of…

### Audrey Tang:
On the Internet, it doesn’t work like that… The tabloids wouldn’t just resize to fit a smaller screen.

> (laughter)

### Louis Collard:
Right. Anyway, what I wanted to think about and work on is that I think a lot of the supposedly quality newspapers – for example, the Guardian, the New York Times, or the Financial Times, or these – are actually often much less good quality than people realize, I think. They’ve been forced to adapt, obviously, and just in terms of you see spelling mistakes frequently in headlines.

### Louis Collard:
Any computer’s going to adapt. How quickly did you push this out? Obviously, people’s level of trust in those publications is still pegged on previous.

### Louis Collard:
All that to say, my starting point for this project was to build a quality measure for news based on how that website has gone about optimizing their content for traffic and about monetizing it, and explicitly avoiding anything to do with fact-checking or political bias. Those are all just huge emotional triggers that will be very difficult to communicate to somebody that doesn’t want to hear them.

### Louis Collard:
My starting point was to build a quality ranking for news websites based on, for example, how often they AB test different headlines, or how often they repost duplicate content from the day before, or what percentage of their articles have more than one spelling mistake in them, or something like this.

### Audrey Tang:
What about the monetization part? Do you also measure paywalls or advertisement supports or things like that?

### Louis Collard:
I want to measure content density, so probably not ad density, because there’s so much other random stuff on there.

### Audrey Tang:
I know, yeah.

### Louis Collard:
Yeah, content density. Doing it on mobile is easier, because you have a…There’s a percentage of that height that’s actually whole words versus filler.

### Audrey Tang:
That’s fair, and it could be objectively measured.

### Louis Collard:
Right, and that’s exactly…

### Audrey Tang:
Is the whole point.

### Louis Collard:
Yeah. It should be not just some AI black box that tells you, “This is bad,” but something that is measured…

### Audrey Tang:
That you can calculate with a ruler.

### Louis Collard:
Yes, everything you should be able to work out by yourself, if you wanted to. Just like, it will take too much time, so here it is. You don’t have to find it.

### Audrey Tang:
Sure.

### Louis Collard:
I set about doing this, and then I got to a point which I knew I was going to get to. I was just like, “Cool,” and now, I haven’t finished building that yet. I was like, “Cool, well, let’s build this, and then what?”

### Audrey Tang:
Conceptually, it was like Lighthouse. People go to test their site on Lighthouse, because they know it will lead to better Google ranking.

### Louis Collard:
Right. I guess the way I had originally seen it is people don’t want to read bad news, and people think they’re reading good news. If I just show them that, actually, it’s not good news, then they’ll figure it out and go and do something better.

### Audrey Tang:
Right, and, “Here’s the good news.” \[laughs\] OK, yeah.

### Louis Collard:
Then I was like, “Hang on, this is probably not going to happen, is it?” Habits are hard to change, and what are they going to do instead? I moved onto, “OK, cool, I should build a better way to read news, based on these principles that guide you to do the right thing.”

### Louis Collard:
Anyway, I guess the main thing I wanted to ask is, in your experience, do you think that, given the right information, people will tend to just go and do the right thing, or do you think that you need incentives, structure, and guidance to…? Even if people know and want to do the right thing, do you think it’s still important to focus on…?

### Audrey Tang:
I think what you just said on the publisher side, this evolutionary pressure, or perceived evolutionary pressure, that, I think, is what’s really driving so much of the change that we have seen in online publishing.

### Audrey Tang:
For that behavior to change, an expectation of – I wouldn’t just say good news – what news is supposed to look like, that need to be established as a social norm, without which I don’t think people who actually work in the newsrooms have a lot to say about how their work is being laid out on the World Wide Web. These are actually two very different groups of people.

### Audrey Tang:
Unless here is a clear norm around this, like for example, there was a norm that says you should gracefully degrade, even if the phone isn’t the latest phone. It should still display some content and respond to the different size, because for the elderly, they will usually resize the font to be large.

### Audrey Tang:
Instead of requiring horizontal scroll, if you will react with the width of the device as it’s measured by that particular user, not by centimeters, then it’s responsive content, and which is good. I think Google even helped to do the AMP and stuff like that toward that goal.

### Audrey Tang:
AMP is obviously not just about accessibility, but because it works with accessibility instead of against it, and accessibility is a norm, so it ends up getting people’s mindshare. Many publishers did change, not only because it saves their bandwidth costs or whatever, but also, because it’s accessible and better for the elderly, people with seeing difficulties, and so on.

### Audrey Tang:
My point is that it probably needs to have that kind of buy-in from the mindshare of the viewership before the publisher will radically change their layouts and their behaviors to match, without which I don’t think individual incentives, like a tweak in the algorithm of PageRank or whatever is large enough to drive that sort of change.

### Louis Collard:
I definitely agree on that. In my original fantasy grand vision, that was what I’d been thinking, is to get the publishers to change enough people. I hadn’t thought, that’s an interesting point. Do you mind if I make some notes?

### Audrey Tang:
Sure, of course. We’re going to provide you a transcript, anyway.

### Louis Collard:
Oh, cool.

### Audrey Tang:
That’s another norm that we are trying to set here.

### Louis Collard:
To get that to happen, obviously, enough people need to shift their behavior or adopt something else.

### Audrey Tang:
That’s right. You probably have to single out something and say, “It’s not OK.” Just like back in the day, when we work on the MoE Dictionary, the M-O-E Dictionary, the rallying cry was that, on my phone, if I log into the Ministry of Education’s official revised dictionary, and that website will not only ask me to scroll horizontally.

### Audrey Tang:
Also, because it didn’t anticipate the phone as a form factor, after a while of inaction, it will actually log it out, but there is no login button. It’s quite absurd. It was designed back in the days, I think, of HTTP 1.0, where there was no keep-alive connection. The website really has some history.

### Audrey Tang:
By saying horizontal scrolling and logging people out, that’s just a nonstarter, we were able to then get many people who get almost outraged about how dated that website was, and provide a responsible alternative to it, which is the MoE Dict.

### Audrey Tang:
That put enough pressure on the Ministry of Education so that they eventually not only open data, but strictly speaking, license under Creative Commons their dataset, so that alternate implementations can be made. They eventually changed their layout, so there is no horizontal scrolling, anymore.

### Audrey Tang:
I use this as an example, because there’s just like one or two things that we highlight. There’s maybe 100 things wrong with the original website standard, but it’s not worth pointing them out, because what you’re trying to look at it is something that people will commonly agree is wrong.

### Audrey Tang:
It’s like a broken window. If horizontal scrolling is considered OK, then everything else is OK as well. Just singling out one or two main issues, I think that will really help.

### Louis Collard:
That makes a lot of sense. You mentioned that people didn’t like this, and ended up putting enough pressure on…

### Audrey Tang:
On the Ministry of Education.

### Louis Collard:
Yeah, so that they changed. That’s definitely, I think that’s how I had originally been imagining this, was building stats or tools so that people can see, “Oh, hey, you’re being tricked by this stuff. Are you cool with that?”

### Audrey Tang:
Yeah, and especially if you’re paying for it. The BBC is an edge case of the world.

### Louis Collard:
Right. I guess you’ve watched “The Social Dilemma,” so I imagine most people that watched that thought, “Oh, wow, that’s bad,” and then, “I wonder what they said on Twitter about this.” I wonder how much real-world impact that really…

### Louis Collard:
It’s a gradual process, and it raises awareness in the Net, but do you think that that kind of route is the best route, or do you think it’s better to just say, “Hey…” Instead of putting on pressure on them only to open source their dataset and whatever, an alternative would have just been to build another one.

### Audrey Tang:
Write a browser plugin or something.

### Louis Collard:
Yeah, just work around whatever the problems are, and just provide a better alternative.

### Audrey Tang:
Yeah, and we were doing that as well. We said it’s fair use, because we web scrape each and every term, it’s questionable whether it’s fair use or not. Because there is many of us doing this, there’s no way the MoE can sue all of us. It’s a two-pronged approach. There’s always the outside game of showing what an alternative is like.

### Audrey Tang:
We also say we relinquish the copyright of our fork of the MoE, which is essential under the Taiwan fair use law. If we’re making a profit, even only over advertisement, about it, then our case of it being fair use would be much weaker. We say, “No, we’re just doing a format conversion, and we relinquish all the copyright under the CC0.”

### Audrey Tang:
Whenever the MoE feels like, they can just take our work and call it the new official website. This is called forking the government. Then, when we do that, eventually, after a couple years, the MoE turned around.

### Audrey Tang:
Especially when we participated in their typo spotting activity, and using assistive intelligence and collective intelligence, we were able to basically dominate the typos spotted in the original dataset. For them, it’s not just a format conversion, but a way to get more people interested in improving the data quality, which is always a good thing from a public service viewpoint.

### Audrey Tang:
I think that’s around the time where they thought, “Yeah, maybe open source, or at least Creative Commons, is a good idea for the public dataset.” Always keeping an outside game, I think, is also important.

### Louis Collard:
For the two things I’m imagining building, one is this kind of tool that shows you, “Hey, this stuff is not great. You should care about it.” On the other side is, “Hey, you’ve realized it’s not great. Here’s the better thing.”

### Audrey Tang:
Yeah, “Here’s the good news.”

### Louis Collard:
If I could, I feel like the good news app, you almost don’t need it. If enough people care enough, then the publishers will just change. Then the problem goes away, and then we’re all happy. On the other hand, I could be like, “OK, well, everything else is bad. That’s great.”

### Louis Collard:
Take it to the other extreme, like, “Let’s not tell anybody how bad it is, and just build a much better thing. Then I can make loads of money from this aggregated product.”

### Audrey Tang:
That’s very much worth doing, too.

### Louis Collard:
How would you balance those? Obviously, money is good, too, but my motivation is really to, I wanted to solve this, or help improve this situation. How would you go about balancing those two?

### Audrey Tang:
You can always do this and use, I don’t know, Affero’s GPL or something, which is like strong copyleft, so that people who want to learn from your way of doing things could do so, and it’s auditable, more accountable, anyway. The key components that you use could be licensed for other people to use, if they don’t want the AGPL deal.

### Audrey Tang:
If they are not-for-profit, chances are they will take the AGPL deal. This is what we have seen for many utilities, such as the Pol.is, which is what we use for crowd consensus. They use AGPL precisely for this reason. Basically, people can improve on it, but they have to share their changes. If they want only to use it in a commercial fashion, they probably have to pay up. It’s called dual licensing.

### Louis Collard:
If you were me, how would you choose where to allocate your time? Would you be trying to raise awareness of the issue, or trying to build a better alternative?

### Audrey Tang:
It’s certainly easier to argue for your cause when you have a prototype that’s demonstratively better. I think initially it’s the same work. Later on, of course, it would be between advocacy and also making sure that people understand what’s bad is bad. That’s one part, and, of course, just improving your core service or product.

### Audrey Tang:
It’s too early for me to say without actually looking at the prototype. Chances are, whichever feels right to you. That’s why many startups ends up having two or three co-founders. It’s just that the initial founder have a direction that they feel are more natural for them to work on, but the complementary work, still somebody got to do it.

### Louis Collard:
OK, cool. I don’t know, do you have any other thoughts on…?

### Audrey Tang:
No, I think it’s a very interesting angle, and I really would look forward to try out any of the prototypes.

### Louis Collard:
Cool. Well, hopefully soon. I’ve been building lots of… \[laughs\]

### Audrey Tang:
Awesome, great.

### Louis Collard:
Cool. OK, well, thank you very much for your time.

### Audrey Tang:
Thank you, thank you. Let’s keep in touch. Cheers.

### Louis Collard:
Yeah, thanks.

> (pause)

### Louis Collard:
My mom watched a webcast that you did, she was very impressed.

### Audrey Tang:
Ah, OK.

