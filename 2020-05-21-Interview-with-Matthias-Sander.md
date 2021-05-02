# 2020-05-21 Interview with Matthias Sander

### Matthias Sander:
I’ll start now?

### Audrey Tang:
OK.

### Matthias Sander:
Great. This is going to be an, I hope, an in depth interview in order to write a portrait. There are going to be some also anecdotal and maybe even personal questions.

### Audrey Tang:
Of course.

### Matthias Sander:
It’s…

### Matthias Sander:
…expert interview.

### Audrey Tang:
Ask me anything.

### Matthias Sander:
Just so that it’s clear. You’re not frustrated with why am I talking about this.

### Audrey Tang:
No, it’s fine.

### Matthias Sander:
For example, something like you just mentioned your daily rhythm, your routine. It’s also very interesting to understand who you are and how you are working. What did you do yesterday working until one o’clock?

### Audrey Tang:
I was invited to the keynote speech slot, which is not confirmed yet, of the international conference on functional programming, which is a branch of programming that does not take a…the jargon is imperative, but what it really means is that you order the computer to do a sequence of command.

### Audrey Tang:
Functional programming doesn’t do that. It doesn’t command the computer to do any particular thing, just describe the world to the computer as a set of functions. The computer figures out how to evaluate them. It’s a very different philosophy, if you will, of computer programming.

### Audrey Tang:
I attended previous ICFPs. I was on a program committee of its sub-conference, the commercial use of functional programming, a few years ago, so I have some ties to that academic community.

### Audrey Tang:
The program chair of this year wrote me saying that they realize, in the program committee, that I’m one of very few people, if not the only person, who both is a expert on functional programming and also on COVID response. These two has never been joined before in a talk.

### Audrey Tang:
They will like me to somehow figure out a way to connect those two threads together, which is not trivial, because they are almost incommensurable areas.

### Audrey Tang:
I wrote at 00:39 to the program chair saying that below is a very rough sketch of the intuition, and not the actual abstract.

### Audrey Tang:
I wrote the title could be “Referential Transparency for Pandemic Resilience.” The intuition is that we explore the Taiwan model of pandemic resilience as a viable alternative to imperative style measures, such as lockdowns and forced shutdown of businesses.

### Audrey Tang:
Instead of mandating a state of emergency, we in Taiwan focus on parallelizable, meaning it can be done in parallel, R0-reducing social scripts – R0 is the basic transmission rate – that can be applied in any order. Meaning that people can pick and apply from a wide recipe, rather than a single set of instructions.

### Audrey Tang:
This minimize the side effects on constitutional democracy and maximize compositionality of collective intelligence, meaning that people’s idea more readily work together, rather than work against each other.

### Audrey Tang:
This is a very brief sketch, but it does quote this core idea of functional programming for referential transparency and the core idea of that big analogy for pandemic resilience in the same canvas, so to speak.

### Audrey Tang:
We’re still developing that idea. That’s what I worked this midnight.

### Matthias Sander:
That sounds impressive. Do you have it on your laptop, here?

### Audrey Tang:
Yes.

### Matthias Sander:
Can I see it?

> (pause)

### Matthias Sander:
When is this supposed to happen, this conference? I guess it’s online, right?

### Audrey Tang:
Usually it’s late August in New York City, or near to New York City, but knowing New York City it would probably become a virtual event. We’ll see.

### Matthias Sander:
I’m a bit surprised, I have to say. Yesterday, of course, was a big day for you as part of the government.

### Audrey Tang:
Really? What happened yesterday, again? \[laughs\]

### Matthias Sander:
You’re telling me how you write the conference abstract. This is quite interesting and quite telling about the way you work.

### Matthias Sander:
Maybe you can tell me your whole day yesterday…

### Audrey Tang:
Not just spent the night.

### Matthias Sander:
…so I get an idea of how you spend your time and what are your priorities.

### Audrey Tang:
At the morning I went to the Presidential inauguration ceremony. Nothing special there. I sang along, not very audibly, with the singers, the National Choir, the experimental choir.

### Audrey Tang:
They sang, first, a indigenous song, and then a Hakka, and one in Taiwanese Holo. I happen to know some of those songs, and I really enjoy singing with them.

### Audrey Tang:
One of them described that she’s standing on top, like the second floor, looking at the audience. She noticed I was singing along, observed that on Facebook, and said that whether describing this would be possible to summon me. This is the person here, singer.

### Audrey Tang:
I said that, “Yes, I was singing along, and you did very well.” People went quite happy with the response. She asked if I can add her as a Facebook friend, so I add her as a Facebook friend. Some networking there.

> (laughter)

### Audrey Tang:
That’s the inauguration ceremony.

### Matthias Sander:
You were singing along with her?

### Audrey Tang:
With the whole choir.

### Matthias Sander:
All the songs?

### Audrey Tang:
The three songs.

### Matthias Sander:
Also the indigenous one?

### Audrey Tang:
Yeah, also the indigenous. I’ve heard of the indigenous one before. I don’t know the verse by heart, but I have this habit of following whatever people are singing. I can, within 100 milliseconds or so, catch up to what they’re singing, so I can sing in a supporting role, but not the leading role, when there’s a choir going.

### Audrey Tang:
I was in the choir when I was young.

### Matthias Sander:
There are 14 officially recognized indigenous tribes in Taiwan?

### Audrey Tang:
And many more languages.

### Matthias Sander:
And many more languages? Which language was it, even?

### Audrey Tang:
It is actually very interesting, because it’s called “Bulai naniyam kalalumayan”, meaining beautiful grains of rice. It’s one of the more famous indigenous songs by the singer BaLiwakes. It is that language. It’s in Pinuyumayan language.

### Audrey Tang:
Let’s see if I remember that line, because it’s important to get it right. Yes, it is in Pinuyumayan language in 1958.

### Audrey Tang:
He created this song because at that time many indigenous soldiers were in the small battle, well not really small, of August 23rd that year. The PRC PLA attacked Kinmen, and trying to take over Kinmen.

### Audrey Tang:
This is, so-called, the Second Taiwan Strait Crisis. Because of that, many soldiers were on the frontline, and the people in the village was very worried about them.

### Audrey Tang:
BaLiwakes wrote this song to calm the villagers. To describe how the harvest was really good, and once the battle was over you can go back to your indigenous lands, enjoy the beautiful harvest, and so on.

### Audrey Tang:
This is a harvest song with, I would say, battle and war backdrop to it, which is very appropriate for the inauguration ceremony. That’s the idea.

### Matthias Sander:
Very interesting. I’m telling myself I don’t have to take notes because you’re going to publish everything anyway.

### Audrey Tang:
That’s right. A transcript is going to be made.

### Matthias Sander:
That’s cool. That’s very practical.

### Audrey Tang:
It frees your imagination. \[laughs\]

### Matthias Sander:
Very practical for me, and I can more easily listen to you. You speak very quickly, lots of ideas coming out.

### Audrey Tang:
I speak so quickly precisely because I know there’s multiple recorders going on. If needed, you can always play it back slowly, and the person making the transcription, thank you very much, by the way…

> (laughter)

### Audrey Tang:
…will help us figure out the nuances.

### Matthias Sander:
Absolutely.

### Audrey Tang:
After the inauguration ceremony, I swore in to a portrait of young Sun Yat-sen, along with the vice premier and pretty much everybody else in the cabinet, and so that took some time. At 1:00 PM, I was back here. I talked to people in the ministry of economy affairs about economy revitalization plans.

### Audrey Tang:
At 3:00 PM, we had a temporary cabinet meeting, which the entire point is to listen to the premier’s thought about the next few years, and his directions. He emphasized that we need to not be only effective or efficient, but also warm, meaning that the credit should go to the frontline workers.

### Audrey Tang:
We even changed the national regulation for that, so that when a major public infrastructure opens, we need to invite the people who actually worked on it to be honored, instead of their bosses’ bosses.

### Audrey Tang:
It falls to the cabinet members and the leadership to assume great risk and blame, but it falls to the frontline workers to get credit, basically. That is the philosophy that he outlined last afternoon. We took a photo together, and that’s that, and then I went back to the dorm where I live along with many other cabinet members and had two very long interviews.

### Audrey Tang:
One is with Tricia De Bosch Graaf, for someone in the UK with a very interesting, deep ecological view on democratic participation, and so we talked for an hour from that angle, and then it’s one hour and a half with the Taichung City’s team.

### Audrey Tang:
They want to develop, not a smart city, but smart citizens. Which is of course a good thing to do, and so we talked for an hour and a half on how to navigate the political culture to facilitate this kind of structure across the silos, across the existing budget and procurement acts, how to access them, so to speak.

### Audrey Tang:
Because the municipality of course has its own internal politics, so what I did was, I put a recorder, like this in a video conference, and so it records only my point of speech. It records no speech from their side.

### Audrey Tang:
I paraphrase their sometime quite revealing questions into more generalized questions, and answer those questions. My part remains completely transparent, but they can freely speak their mind. Like with our interview, my answer wouldn’t make sense without the questions, so we co-edit and publish the entirety.

### Audrey Tang:
Sometimes, people in the public service, which is not subject to the visitation protocol, want this kind of one-sided transparency because I always answer in the general, but they want to ask in very specific and of course they wouldn’t want to hurt their internal morale like this, so that’s the kind of compromise we make.

### Audrey Tang:
That’s that, and then I went, start replying to emails and just look at social media a little bit. Let’s look at my social media activities from last evening.

### Matthias Sander:
How much time do you spend on social media every day?

### Audrey Tang:
15 minutes a day.

### Matthias Sander:
Only?

### Audrey Tang:
Yeah.

### Matthias Sander:
Do you have a more or less fixed time slot?

### Audrey Tang:
Yeah. I work for 25 hours…Sorry, 25 minutes…

### Matthias Sander:
\[laughs\]

### Audrey Tang:
24 hours a day. Literally 25 hours yesterday, because it was one in the morning. The day ends on the 25th hour.

### Audrey Tang:
25 minutes’ time is called Pomodoro method, and I take a 5-minute break between the two half-hour slots for social media and work, just catching up.

### Audrey Tang:
Usually, I take maybe three Pomodoros’ worth of five minutes’ time for social media, so that’s that.

### Matthias Sander:
Sorry, your time structure is, basically you work 25 minutes, then 5 minutes break, 25 minutes?

### Audrey Tang:
Yes.

### Matthias Sander:
Why 25 minutes? I know many people, they say like 45 minutes, an hour, or something?

### Audrey Tang:
I do 24 minutes, too.

### Matthias Sander:
\[laughs\] 24?

### Audrey Tang:
Yeah, it’s flexible.

### Matthias Sander:
It’s actually…

### Audrey Tang:
Difference.

> (laughter)

### Matthias Sander:
Very flexible. Anywhere between 24 and 25 minutes, and so like the whole 60 seconds of flexibility.

### Audrey Tang:
It’s easier because I internalized that work clock rhythm, so I don’t even have to check the clock.

### Audrey Tang:
My gut feeling tells me that we’re about like the 20th minute in this session, so then after 5 minutes, of course we’re still in the interview, but I’ll just vary a little bit. That’s just the internal rhythm that I’m used to for the past 10 years or so.

### Matthias Sander:
That means if you’re right, and I’m not going to tell you now, we might have another coffee in five minutes or so?

### Audrey Tang:
Sure, of course. Why not?

### Matthias Sander:
Good. There are many things you already mentioned just in this one answer, basically. I want to come back to many topics, and of course I want to talk about COVID-19. Of course I want to talk about transparency. I want to talk about smart cities, smart citizens, many things like that.

### Matthias Sander:
Just to keep some structure and order maybe, just one thing that you said in the very beginning about yesterday struck my mind. You said, “Oh, it was nothing special there.” Of course President Tsai Ing-wen said yesterday, it was, I think she said in her speech, the most special inauguration in the history of the Republic of China.

### Audrey Tang:
I remember that, yes. \[laughs\]

### Matthias Sander:
Yeah, you’re right, because of the special COVID-19 situation and all that. Are you just, basically, how do we say, being very cool, doing an understatement, or is this really what you think?

### Audrey Tang:
No, there’s nothing ironic about it.

### Matthias Sander:
Nothing ironic about it.

### Audrey Tang:
There’s nothing ironic about it. Nothing special there means both that there’s no surprises, meaning that it went very smoothly.

### Audrey Tang:
There are some very cute designs, such as, the presidential gift box is a hand spray, and a Taiwan-shaped soap, and a towel, and also a wet napkin and so on, a hand sanitation kit. That’s a presidential gift. It’s very creative, now I think about it, but then again, it’s what I would expect, also. \[laughs\]

### Audrey Tang:
This entire thing is very epidemiologically informed, and so because I’ve been working with the CECC for the past few months, this is just their modus operandi, so I’m not very surprised.

### Audrey Tang:
I’m not at all surprised of all the measures they’re taking, and the fact that even though after sitting down, we’re all one meters apart and it’s an outdoor place, so theoretically we do not have to wear a mask, I’m not surprised that everybody kept their mask on until when the president is about to show up, the staff tells us to remove the mask.

### Audrey Tang:
Again, this is normal. This is what Taiwanese people do. Even though the CECC says keep social distance or wear a mask, everybody keeps social distance and wear a mask.

### Matthias Sander:
That’s a very interesting aspect. Just one minor aspect, but very interesting. Why is that, actually? Why is that, according to you?

### Audrey Tang:
I think that the mask, especially medical mask in Taiwan is billed as something that protects you, that protects the person who wear it because, A, it reminds you not to touch your mouth, and B, it reminds you to wash your hands properly, which pretty much everybody do nowadays.

### Audrey Tang:
We know that this benefit is just a small part of its true effect, which is protecting other people from you, which is a sign of respect or whatever.

### Audrey Tang:
In Taiwan, the peer pressure works such that if you’re in a large gathering for like maybe 50 people, and only 5 people wear a facial mask, the design of it, primarily selfish branding, allows those 5 people to remind the other 45 to protect their own health, which is easier to sell if you’re a minority.

### Audrey Tang:
The peer pressure works even if there’s only a small amount of population wearing a mask in a public gathering, because everybody can take care of each other’s health by reminding them to protect themselves wearing this PPE. Once a sufficient people do their bit, of course they protect each other.

### Audrey Tang:
I think this is, in Taiwan, a much more interesting way of building a mask-wearing culture because it will appeal to the altruistic part of the motivation that usually only works if already more than half people…Like a majority of people in a room start wearing a mask, then of course you can say the minority is not being altruistic enough and do more pressure.

### Audrey Tang:
We don’t usually do that. \[laughs\] We do appeal to a selfish interest by design, and so that allows even a small number of people to influence a large amount of people.

### Matthias Sander:
How do you mean by design? You said something like about the special design of Taiwanese masks? What do you mean?

### Audrey Tang:
No, I mean public communication.

### Matthias Sander:
Of course.

### Audrey Tang:
From the very beginning, the premier said, “Don’t panic. Wash your hands. Wear a mask,” and so on. All the public communication that we push out doesn’t say that, “This is a sign of respect. This is a sign of solidarity, collectivist, Confucian,” whatever. We don’t say that.

### Audrey Tang:
We say, “It’s for you.” It reminds you to wash your hands well.

### Matthias Sander:
That’s very interesting, but then when I speak with Taiwanese people, they say just what you mention, like, “Oh, this is a sign, we are Asians. We care about the collective. Europeans are so individualistic. You don’t mind. You don’t care.”

### Audrey Tang:
If you pit Taiwanese people with random culture that doesn’t have a mask-wearing culture, then of course people will say, “Oh, they don’t care about each other’s health.” Yes, they do that, too.

### Matthias Sander:
I felt that a lot, and maybe it’s true, right?

### Audrey Tang:
I don’t know. I think mostly this is just a availability thing. Like in Czech Republic, they do a very public mask for all campaign, and literally changed the norm over the course of a week. They do that by showing how to sew their own mask, and how to fold and make their own mask.

### Audrey Tang:
It doesn’t really quite matter whether there’s a norm to begin with. It does matter whether this norm-building is conscious, or intentional or not, because otherwise, the incentives cancel each other out. If you do something out of intrinsic motivation and there is a intrinsic order or reward, they tend to cancel each other.

### Matthias Sander:
That’s what happened in many European countries. In the beginning, they were very reluctant. They said you don’t have to wear a mask. It’s even better not to wear one. There might be false incentives and all that. Basically I think it was because they didn’t have masks, and then later on, we all saw them adopting…

### Audrey Tang:
It’s trivial to make one. Even before we ramped up the production, I just use usual mask that are not medical grade, and which has a breathing hole, a small filter, and these are plenty. Even in Europe, you can get this one quite easily.

### Matthias Sander:
Probably they were even struggling for those ones, but OK.

### Audrey Tang:
No, you can make those ones quite easily, as the Czech people show.

### Matthias Sander:
Yeah, and other countries did that too. My newspaper ran a big story as well, like how to make your own mask.

### Audrey Tang:
Of course nothing beats soap, and everything we just talked about builds upon the foundation of the core technology that is soap.

### Matthias Sander:
Absolutely. First break, or if you want to.

### Audrey Tang:
No, I’m already taken care of. \[laughs\]

### Matthias Sander:
Sorry, does that mean, am I boring you? \[laughs\]

### Audrey Tang:
No…

### Matthias Sander:
Are you bored yourself?

### Audrey Tang:
You want another coffee now?

### Matthias Sander:
Yeah, why not? Yeah, just, thank you very much.

> (background conversations)

### Matthias Sander:
…environment, if you could just quickly show me around your office. It’s small, and show me the…

### Audrey Tang:
This is not my usual office. Usually, I work in the Social Innovation Lab.

### Matthias Sander:
I know. I was surprised you actually…

> (background conversations)

### Audrey Tang:
This is for the two political staff, and the rest of them are for career public service.

### Matthias Sander:
Right, within service.

### Audrey Tang:
Right.

### Matthias Sander:
I’m just going to write that down for my notes. That might be important later in the interview. You said Ministry of Justice?

### Audrey Tang:
Right. Let me repeat. In the office, we can see that, in addition to the two seats of my executive secretaries who are also a fellow occupier, in charge of social innovation issues, and Zach Huang, who is our political and press officer.

### Audrey Tang:
The other members of this small office are delegates from various different ministries. We have in the front door counter-clockwise, Joel from the Foreign Service and Bin-Bin from the Ministry of Interior. Then Yu-Chi from the Ministry of Justice.

### Audrey Tang:
In this larger room, Ye-Ning from the National Communication Commission. It’s also a coworking space from other delegates who part-time here, including delegates from the Ministry of Culture, and the National Development Council, and the Ministry of Education.

### Audrey Tang:
These are the current delegates to this office. There is about equal number of professional designers and technologists, but they are in the third floor.

### Matthias Sander:
In total, how many people? OK, 21 people.

### Audrey Tang:
Yeah. Permanent staff. Every year, we hire 30 interns, usually graduate level designers, and technologists, and culture managers. We temporarily have a staff of 50 for a couple of months.

### Matthias Sander:
Wow, so many. Why so many interns?

### Audrey Tang:
Because they work on whatever government service they want to improve experience. For example, this year it’s the hiking year. Last year…

### Matthias Sander:
Hiking year?

### Audrey Tang:
Yeah, right. Mountaineering for tourism. Anyway… \[laughs\]

### Matthias Sander:
Why not? Because of the…

### Audrey Tang:
Because of that we that we open up and simplified the application flow specifically for foreign people who are in Taiwan for the first time to climb the higher mountains. They probably are watching a virtual reality film or something.

### Matthias Sander:
\[laughs\]

### Audrey Tang:
We did do that, too. I guess it really makes sense for the young people to look at the application for mountaineering process and wonder why I have to go to four websites for that. They designed a single-entry workflow and we work with the technologists to really make it happen without taking down any particular ministry’s website. We just do the single entry point that can navigate much more easily.

### Audrey Tang:
With 30 interns, we usually group them into three-people teams that do season surveys, and journey, and design, and things like this. On average, every year, we can make maybe 10 government services much more human-centric and share the know-how as example so that other municipalities and sections can do it by their own.

### Matthias Sander:
Wow, interesting. Give me some examples of what kind of government services in the last year you made more human-centric with this method?

### Audrey Tang:
Sure. As I mentioned, of course, the hiking portal. There is also the National Palace Museum experience of ticketing, of all things, because it turns out that many people still want the paper ticket for memory value. Even though they did QR-code-based ticketing system for a very long time, it’s not very popular.

### Audrey Tang:
The young people helped finding an alternative design where the elderly still use the QR code. It’s not like they don’t know how to use the QR code. It’s not like they don’t know how to use a QR code. Most of them do because of the widespread use of the Line system. They swipe a QR code, avoid queuing. The elderly doesn’t like queuing anyway.

### Audrey Tang:
Once they get into the Palace Museum, they can redeem using the QR code a receipt that is finely printed and even customized by putting their names on it or something. That solves the queuing problem because they do get a piece of paper that they can take home and share it as a social object. Of course, it’s not just that, but a part of it.

### Audrey Tang:
People also work with the Minister of Finance on the taxpaying, everybody’s favorite experience that they do. \[laughs\] Based on their research, starting this May and ongoing, as we speak, you can take your citizen’s digital certificate or your National Health Insurance card to the local convenience store, which is nearby – and I can say that anywhere it Taiwan…

### Matthias Sander:
Yeah.

> (laughter)

### Audrey Tang:
…and swipe your card. If your personal income tax is less than 20k NT$, then you take that receipt to the counter of the convenience store and pay your tax, and that’s done. If it’s above that range, you get a piece of paper with two numbers on it.

### Audrey Tang:
You enter those two numbers into your phone, and the phone can walk you through the tax-filing process. Again, you can pay through credit card or whatever online payment system. You don’t need a card-reader because the kiosk does that for you. You don’t need a special counter because convenience stores are everywhere.

### Audrey Tang:
It really changed how people perceive the tax-filing system. Previously, people would not be able to use their mobile phone. They would instead go to the counter of the tax bureau, which during this coronavirus, we don’t want too many people to line up.

### Audrey Tang:
Even previous that that, in 2006, people would have to first borrow a Windows computer and download some software. What I’m trying to get at is that we design the services to respond to real citizen needs. When a citizen said, “I would much rather if I could just go to a convenience store,” we just make it happen. That’s another well-used service.

### Audrey Tang:
I can go on, but you can read all about it in our RAY, Rescue Action by Youth, website, which is ray.pdis

### Matthias Sander:
I think you started by allowing tax filing with Mac computers as well, right?

### Audrey Tang:
Not me, a designer who sign started a e-petition saying tax-filing is explosively hostile and carried on the design by himself. We did a few collaboration meetings, but the original design came from the designers and bloggers that participated in the live-streamed meetings with a lot of input from people watching the live stream.

### Audrey Tang:
Cho Chih-Yuan did most of the work along with our designer, Fang-Jui Chang. I didn’t do anything really. I just made a space.

### Matthias Sander:
You’re saying 21 staff in total? Is that your staff? Because I’ve talked to some people..

### Audrey Tang:
No, they do what they want.

### Matthias Sander:
Of course. As an anarchist, you don’t want to say…

### Audrey Tang:
I don’t give orders.

### Matthias Sander:
I know, but you have a budget, right? You have, in this budget…

### Audrey Tang:
No, they have a budget. I don’t have it.

### Matthias Sander:
You have no budget at all?

### Audrey Tang:
No. Even my travel budget is sponsored by the Foreign Service. Each delegate brings their own budget. Some of them, like the Foreign Service delegate, is a section chief-level. The National Communication Commission delegate was, and still is, a director general.

### Audrey Tang:
Each of them has their own budget, and their salary is still being paid by their originating ministries. What I’m doing is essentially coaching them to work out loud. I don’t have a budget, and I don’t give them commands.

### Matthias Sander:
Absolute, but still you have people who have more practical technology, people you’re saying…

### Audrey Tang:
Uh-huh.

### Matthias Sander:
What about them?

### Audrey Tang:
The interns, their salaries are paid by the Ministry of Education. \[laughs\] The Board of Science and Technology also sponsors the Presidential Hackathon and some of us are running it. The Ministry of Economy sponsors the Social Innovation Action Plan, which contains most of the staff in the Social Innovation Lab, which are not the permanent staff of this office, but rather its own NPO, the Taiwan Digital Culture Association.

### Audrey Tang:
It’s not your traditional HR system.

### Matthias Sander:
I’ve talked to some people in preparation for this. Those who are more critical – everybody likes you, that’s very obvious…

### Audrey Tang:
If they criticize me, they care about me.

### Matthias Sander:
Absolutely.

### Audrey Tang:
\[laughs\]

### Matthias Sander:
Those who are more critical about rather not you as a person but your role, they say…

### Audrey Tang:
I don’t have a role. \[laughs\]

### Matthias Sander:
OK.

### Audrey Tang:
I don’t do role-playing. Maybe D&#x26;D, but not in this ministerial position. I said very clear that I am just facilitating communication across various different positions. Each ministry has its own value, its own position. What I’m doing is essentially applied philosophy to find common values out of different values. Of course, there are people who prefer me doing things that are not applied philosophy.

### Matthias Sander:
Like those people. They are basically like, “But it’s still politics. She’s on the government. She doesn’t really have a budget. She doesn’t really have staff. That’s what you need if you really want to change things.” Of course, you don’t agree.

### Audrey Tang:
I agree. I don’t change things.

### Matthias Sander:
You don’t change things?

### Audrey Tang:
Yeah. Most people change things. I said very explicitly that Cho Chih-Yuan came up with the tax-filing system redesign. Those interns, I wouldn’t say perfected, but drew down to the details and improved it. The mask-pharmacy map is a design by Howard Wu, and it’s refined by the National Health interns folks and developers in the g0v community.

### Audrey Tang:
These are very active people. During the mask pharmacy map, there’s easily hundreds of civic hackers and hundreds of govtech hackers working together. I personally didn’t do anything.

### Matthias Sander:
Of course, but you’re here for something. You have a reason?

### Audrey Tang:
Yeah, I’m here for fun.

### Matthias Sander:
Even if you say you don’t change things – maybe I’m not precise enough – you want to change the culture, right?

### Audrey Tang:
No, I’m just enjoying myself. If people enjoy working on public issues more, it’s not because I tell them. They look at me and they see that it’s so much fun to be had, and so this is by osmosis. That’s the work. I’m not, strictly saying, a change-maker. It is more like a culture osmosis, radiation, amplification channel.

### Audrey Tang:
Of course, on that part, maybe it’s better if I don’t have a budget. If I have a budget, I’ll be limited by that budget because with a budget, comes the KPI. Then I’ll be constrained by the yearly KPIs that those budgets are associated with.

### Matthias Sander:
I want to go back to one thing you mentioned here at this meeting yesterday, about digital development I think you said.

### Audrey Tang:
With Taichung City?

### Matthias Sander:
Before.

### Audrey Tang:
The peak ecology thing, the interview on culture with the person in London? Or even before, the Minister of Economy?

### Matthias Sander:
The ministry meeting, the Ministry of Economy.

### Audrey Tang:
They visited to prepare for the 10:00 AM meeting today, which is economy revitalization plans, how people can participate, and how we can work on a cross-sectoral plan, \[snaps\] to put it nicely, to incentivize people to consume more, to make more use of their purchasing powers, responsibly and sustainable I must stress, during the recovery month of July and August.

### Audrey Tang:
Honestly speaking, there’s only part of the economy that need to be recovered because Taiwan did not have a lockdown. Our strategy is quite different from other jurisdictions which is suffering from a negative growth across all sectors.

### Matthias Sander:
What is your role exactly in that kind of meeting?

### Audrey Tang:
I just listen.

### Matthias Sander:
Did they come to you? Why? What do they want to have from you?

### Audrey Tang:
They have sometimes conflicting values. For example, yesterday the main contention was whether to require people to pre-decide the kind of mobile or electronic payment and reimbursement methods a month ahead of the actual plan kicks in, or whether people do whatever they want, and regain the benefits.

### Audrey Tang:
The first choice privileges digital payment systems more than paper-based ones, and also has a very interesting ranking, like which option do we show first.

### Audrey Tang:
The second option prioritizes flexibility, but it will lead to more use of paper-based payment systems, and that’s it. They’re here to bring in advocates for both sides for me to listen. Then I say whatever comes to my mind.

### Matthias Sander:
What did you suggest yesterday?

### Audrey Tang:
I said if you want to prioritize paper-based things and flexibility is of utmost importance, it makes more sense to have a map of sorts, just like the mask pharmacy stock map.

### Audrey Tang:
If people find out their nearby convenience store doesn’t have those papers in stock, maybe they just switch to digital payment on the spot instead of waiting for another day for those paper-based things to arrive to their nearby convenience store.

### Audrey Tang:
If you want to encourage more use of paper-based payments, it makes sense for the digital to be the flexible back-up instead of fixing them one month before. If you want to prioritize digital, which means that they can spend first and collect the benefits later, then it makes sense to have a single portal a month before.

### Audrey Tang:
It all depends on your sense of fairness, how it apply. The digital is a back-up for people who cannot get a paper the day want. Or the other way around, people use paper if they don’t prefer digital payment. I just listed the implicit values behind their choices. Then they’ll make their own choice.

### Matthias Sander:
That doesn’t sound necessarily like what you would imagine if somebody thinks of you as a digital minister.

### Audrey Tang:
I’m a lower-case minister.

### Matthias Sander:
Sorry?

### Audrey Tang:
I’m a lower-case minister.

### Matthias Sander:
What does that mean?

### Audrey Tang:
I preach, I advocate for digital transformation. If you go to your local minister, I mean in a Catholic sense, \[laughs\] that’s exactly what you would expect them to do, to listen to your confession – sorry, maybe not confessions – \[laughs\] to whatever you’re thinking about and gives them sage advice.

### Matthias Sander:
You’re a lower-case minister. Still then, normally, you would preach something, which would, in this case as digital minister, I would suspect would be, “Hey guys, we should use this occasion to push for a digital payment system.”

### Audrey Tang:
No, I don’t have a agenda, and digital is here to serve the social norm, to help us find the social norm, discover the social norm. If the norm is that people in the National Palace Museum queues really want a piece of paper for memory value, for souvenir value, then digital should make that happen.

### Audrey Tang:
I’m not the information technology minister, which would be advocating for specific technologies. Digital means possibilities, inclusion, and things like that. I would probably say whatever on my mind and use digital technologies to further the social norms.

### Matthias Sander:
That’s very interesting. I think the way many governments and also experts understand digital and digitalization is basically to put everything on the Internet and computers…

### Audrey Tang:
That’s a very dangerous view.

### Matthias Sander:
Why?

### Audrey Tang:
First of all, having a digital twin doesn’t mean that you murder or eradicate the analog one. The digital twin only means that you can reason about what’s going on in the society, but it doesn’t replace the society. Otherwise, you get into the realm of simulacra, and we all know how that goes.

### Audrey Tang:
I think it’s important to say that we’re bringing digital to the people, amplifying whatever they’re doing, but we’re not replacing face-to-face communication. We’re augmenting but not substituting most of the human communications and so on.

### Audrey Tang:
Of course, people are feeling the constraints of space and time, and there are some digital technologies that can help bridging those constraints. It doesn’t mean that the original is somehow less cherished or less effective. Rather, it’s even more effective. This is at the core of the smart cities, smart citizens distinction.

### Matthias Sander:
That’s very interesting. I guess you don’t like the term smart city at all, right?

### Audrey Tang:
If the smart city can enable smarter citizens, then go for it. If the smart city makes dumb citizens, then not the same.

### Matthias Sander:
Maybe we can forget my structure and continue with the flow of the conversation.

### Audrey Tang:
Do whatever.

### Matthias Sander:
Still, like the smart city, this label is very much used in Taiwan as well, for example, right?

### Audrey Tang:
The actual word that’s being used is wise city.

### Matthias Sander:
Wise city in Chinese? How do you say that in Chinese?

### Audrey Tang:
智慧城市.

### Matthias Sander:
Is that different from the smart city?

### Audrey Tang:
It’s really different.

### Matthias Sander:
It’s really different?

### Audrey Tang:
Yeah. If we want to say smart, we would say 聰明, which is individual brilliance and individual intelligence. When we say 智慧, it always means wisdom. It basically says that you can work with the social norm, have a good emotional resilience, and things like that. It’s a different concept.

### Matthias Sander:
Usually, the translation for smart city in Chinese…

### Audrey Tang:
Is the wise…

### Matthias Sander:
…is the wise city. That’s very interesting.

### Audrey Tang:
In Taiwan. It’s not like that in the other Mandarin-speaking jurisdictions.

### Matthias Sander:
Do you know how they say it in China in Chinese.

### Audrey Tang:
Let’s see, consult the computer, which always has the perfect answer, I’m sure.

> (pause)

### Audrey Tang:
For artificial intelligence, they say 人工智能. The 智能 part is intelligence. It’s still more encompassing than just 聰明. Here, we say 智慧, which is wisdom. I think in smart city, the people in PRC also say wisdom. I just checked.

### Matthias Sander:
Is this concept really very much different in practice as well from the Western concept of smart city?

### Audrey Tang:
Yeah, I think a few things. First of all, if you concentrate on wisdom, then interpersonal mechanism designed for participation, I think is right term, is preferred over a individual interaction with digital services. It would be digital services that enable the kind of social structure that are more pro-social.

### Audrey Tang:
That we do share with the PRC. That’s the same concept. What’s different is that we emphasize participatory mechanism design, meaning that everybody can change the rules a little bit and propose new innovations as ordinary citizens. Whereas in PRC, there’s less of that. There’s places where we’re similar and places where we are not.

### Matthias Sander:
I was more talking to you about the difference between the Taiwanese concept of the wise city versus the Western concept of smart cities, which are often just technology-driven cities.

### Audrey Tang:
I’m sure you may have heard of my job description, which is the comparison table. “When we see Internet of Things, let’s make it an Internet of beings. When we see virtual reality, let’s make it a shared reality. When we see machine learning, let’s make it collaborative learning.

### Audrey Tang:
When we see user experience, let’s make it about human experience. Whenever anyone tells us the singularity is near, let us remember that plurality is here.” This is the left-right column of this Western…I don’t think it’s Western, a mechanistic smart city versus the city of wisdom.

### Audrey Tang:
I’ll get a drink.

### Matthias Sander:
Yeah. Do you have a cup of water maybe?

### Audrey Tang:
Yes, or a…

### Matthias Sander:
Oh, I see. You have the…

### Matthias Sander:
I know they came in last year.

### Audrey Tang:
That’s right.

> (background conversation)

> (background sounds only)

### Matthias Sander:
When are you here?

### Audrey Tang:
Just Mondays and Thursdays.

### Matthias Sander:
Because you have meetings?

### Audrey Tang:
And not even the whole day. Thursday till noon.

> (background noise)

### Matthias Sander:
Because you had meetings with Doug Atsel.

### Audrey Tang:
That’s Monday. Thursday is the cabinet meeting, so I’m still attending the cabinet meeting. That’s the same morning. In the afternoon, I will go to weekly meeting of the Board of Science and Technology, which is another regular meeting. Thursday is more official. Wednesday, I’m of course in the Search Innovation Lab.

### Audrey Tang:
That leaves Tuesday and Friday, I can freely roam among the islands. Well, not so freely nowadays…

### Matthias Sander:
Yeah. \[laughs\]

### Audrey Tang:
…but anyway \[laughs\] right. I’m on the islands that comprise the republic of citizens.

### Matthias Sander:
You just said, “I’m still attending the cabinet meeting.” What does that mean, “still”?

### Audrey Tang:
It means that I just swore in. I resigned…

### Matthias Sander:
Ah, in that sense.

### Audrey Tang:
… \[laughs\] with the cabinet.

### Matthias Sander:
It sounds like, “I would rather not, but I have to.”

### Audrey Tang:
I put in my resignation papers last week, along with everybody, but I’m still attending. I wonder why. Maybe I got kept in the new cabinet.

### Matthias Sander:
You wonder why?

### Audrey Tang:
I wonder why.

### Matthias Sander:
Why?

### Audrey Tang:
I have no idea. The premier said, “Let’s keep working together.” I said sure, and that’s it. There’s no formal consultation process. It’s a given that I would stay.

### Matthias Sander:
You wanted to stay, absolutely? Or were you thinking about…

### Audrey Tang:
I don’t really care.

### Matthias Sander:
Really? How can you not care about being a minister or not?

### Audrey Tang:
I’m always a lower-case minister, whether I’m working with the public service or not. I’ve been interning in this office for a couple years before…

### Matthias Sander:
Yeah?

### Audrey Tang:
…being the official minister anyway since 2014, so I frequently visit here. This was the office of Minister Jaclyn Tsai.

### Matthias Sander:
I know.

### Audrey Tang:
It doesn’t really matter. If I’m not longer in a upper-case minister position, I can still visit the Social Innovation Lab and talk to people every Wednesday. It really doesn’t change anything. The upper-case one, I see it as a honorary title.

### Matthias Sander:
You don’t care about honorary titles?

### Audrey Tang:
I don’t care.

### Matthias Sander:
Interesting. You’re basically saying, if you weren’t Taiwan’s digital minister, your life wouldn’t be that different?

### Audrey Tang:
It’s the same life.

### Matthias Sander:
Maybe you would get fewer invitations because you don’t have that cool-sounding title.

### Audrey Tang:
\[laughs\] I really doubt it.

### Matthias Sander:
By now, you have quite a reputation.

### Audrey Tang:
\[laughs\] Even before I become the upper-case minister, ever since the Sunflower Occupy, I’ve been working very closely with the career public service. The initial co-founders of this office were all people that I’ve worked already during ‘14 and ‘15.

### Audrey Tang:
That’s my condition entering the cabinet. It’s well-documented. It’s by voluntary association. I talked to Premier Tseng-chang.

### Audrey Tang:
I’m saying, “It’s good that you can give me and office, but I will not frequently enter the office. And it’s good that there’s a salary, although it’s one-third of what I used to earn, but whatever.

### Audrey Tang:
“The most important thing is that the public service trust me because I’m a advisor who never forced them to do anything, and this relationship need to continue if you make me a upper-case minister.” Premier Lin Chuan agreed with that, and so did every premier after him.

### Matthias Sander:
It was, I think, Jaclyn Tsai who, can I say, brought you into government or who established the first contact?

### Audrey Tang:
She went to our hackathon and pitched an idea just like any ordinary citizen. I was part of the team that realized that idea to build a e-rule-making system. Because of the e-rule-making system, and later on the Join system, touches upon all the ministries’ business other than defense, PRC relationship, and foreign affairs, traditionally.

### Audrey Tang:
Other than these three ministries, which I still have very little clue about, other than public diplomacy, which I know something about, the other ministries send delegates to Jaclyn Tsai’s office and her meetings as well. By chairing, essentially, these meetings, as the civil society co-chair at the time, a co-facilitator, I get to know the career public service and how innovative they are, very.

### Matthias Sander:
Interesting. Maybe you can compare. What are you doing differently than your former boss, Jaclyn Tsai?

### Audrey Tang:
My former collaborator.

### Matthias Sander:
Or former collaborator. You’re not a boss. You don’t have bosses, I guess.

### Audrey Tang:
She never gave me orders.

### Audrey Tang:
Three very different things. First, Jaclyn Tsai was the horizontal minister for law. She actually takes part of all the bills that requires a legal interpretation or legal counsel from each ministry. I don’t do that because I’m not a expert in law. Well, Jaclyn is an expert in law, but I am not.

### Audrey Tang:
I’m more like a counsel on algorithms, instead. People come to me and seek advice, not because they need a novel interpretation of our legal system. We have a Minister Lo for that.

### Audrey Tang:
People come to me because they are trying to reconcile the algorithmic norm and the existing social norm. I am playing a very different role because my training is different from Minister Jaclyn Tsai, in a advisory cabinet counsel position. That’s the first thing.

### Audrey Tang:
The second thing is, although Jaclyn Tsai did have ministerial delegates, she did not have this participation officer network, which all the ministries joined. That replicates our kind of horizontal liaison-based leadership in each and every ministry.

### Audrey Tang:
When there is a e-petition, a regulatory announcement, or any intention that require deliberative design of deliberation, there’s no network for that back in Jaclyn Tsai’s days. We already saw that this needs to happen.

### Audrey Tang:
She did help boost tracking. For example, the joint platform with the National Development Council. She incubated this idea, but it came to national regulation level only during this term, this cabinet. That’s the second thing. It’s about institutionalization.

### Audrey Tang:
Once we did institutionalization, anyone can be the digital minister in charge of social innovation and that this system would still run because the public service see the value in it and the current public service is willing to maintain this apparatus.

### Audrey Tang:
That’s the second thing. It’s career service public service buy-in.

### Audrey Tang:
The third thing is this whole notion of remixes of this kind of popular icon status of me licensing my photos, my speech, my interviews, and my videos as, essentially, material for everybody else to work with creates a wider international reach because I speak in English, I do most of my interviews in in English. Even if it’s in Mandarin we take care to translate the key parts of it in English.

### Audrey Tang:
We see many of our bits and pieces of our idea, like the participation officer, as seriously considered and adopted in some form in the Italian cabinet with their ministry of direct democracy. The crowd law methodologies that we use form the first chapter of the US Library of Congress crowd law training materials.

### Audrey Tang:
We host workshops in Chulalongkorn University in Thailand, in Tokyo with the Code for Japan people, as part of g0v collaboration in Canada. In all sort of different places.

### Audrey Tang:
We work with Taiwan, while Jaclyn Tsai’s ministry worked for Taiwan. That’s a difference.

### Matthias Sander:
That’s interesting. That was one of my questions, actually. Why do you have this huge international focus and outreach?

### Audrey Tang:
Because I am working with Taiwan, not working for Taiwan.

### Matthias Sander:
One would think if you’re in a government you’re working for Taiwan, for its people.

### Audrey Tang:
No, because I’m working with government. I’m not working for the government. The entire point is to work “with.”

### Matthias Sander:
Then at least you can say you’re working for the people.

### Audrey Tang:
No, I’m working with the people. People are working for the people.

### Audrey Tang:
I provide service to public servants. The public servants sometime work for the people, but I try to encourage them to work with the people because people have better ideas. This whole notion of not “working for” is one of the main thing that I’m seeking to \[snaps fingers\] I’m trying to find a neutral word for it, deconstruct. \[laughs\] Not destroy, not disrupt, but deconstruct.

### Audrey Tang:
This rings very true to many similar Occupy-based or Occupy-inspired movements around the world, where people have a short taste of working together in a horizontal non-coercive fashion, which may or may not stably work. Sometimes they get caught, sometimes they get evicted, and so on.

### Audrey Tang:
It’s quite rare that we now have this kind of bubble of Occupy in the Social Innovation Lab, and certainly this office on the third floor, where people just doesn’t represent anyone, and just present whatever they’re working on. This is a very different culture, this is deeply of a g0v culture, but realized within the institutional bubble that is protected by a national regulation.

### Matthias Sander:
The third floor, what is there?

### Audrey Tang:
That’s where our designers and technologists are.

### Matthias Sander:
Do they only work for you actually?

### Audrey Tang:
No, they work on whatever.

### Matthias Sander:
I mean for…with.

### Audrey Tang:
All I require is that weekly we have a lunch together, and everybody share this onboard and talk to everybody else and answer all the questions about what they’re trying to work on in depth.

### Matthias Sander:
What I wanted to say actually, sorry, it was can other ministers, ministries go and see…

### Audrey Tang:
Of course. They all have their own personal connections and get invited to conferences all the time, and we poach them from…The designers, the initial co-founder is still working us, but the same person was from CIID, the Copenhagen Institute of Interaction Design.

### Audrey Tang:
The next one was from UK Policy Lab, an RCA graduate still working with us, but she’s in London now, and the current design leader we poached her from IDEAL Shanghai. This is very much like any start with co-founders and design leads and HR coaches and whatever. It just so happens the topics they’re working on is whatever people are caring about nowadays.

### Matthias Sander:
It’s rather surprising knowing – we all know your ideas in politics – but still for someone in the government to say you’re not working for the people.

### Audrey Tang:
I’m a poetician. In poetics, it doesn’t really make sense for a poet to work for the people. I’m not sure if there’s any poet that says that. If someone’s a people’s poet, it means that they work with people to write what people’s feeling, but they don’t work for the people. It’s a very aiding concept.

### Matthias Sander:
That the government is working for the people is a basic democratic concept, right?

### Audrey Tang:
Yeah, of course, of course. It’s all in relation to people.

### Matthias Sander:
How do you reconcile that with your views?

### Audrey Tang:
I don’t. I would create the space in which people work with each other more effectively or at least more fun, almost always more effectively.

### Audrey Tang:
That’s the extent that my work is about, which is why I’m working with the government and with the people in a kind of a Lagrange Point between movements on one part and government on the other. A Lagrange Point doesn’t belong to the gravity well of either sector.

### Matthias Sander:
I guess you’ll never, never ever run for elected office, right?

### Audrey Tang:
I would say that unless, of course, this is just to bootstrap a new system, a new mechanism where people only vote for issues and after that never for candidates, then that I would entertain, because it’s essentially a reboot of a representative democracy.

### Audrey Tang:
That could work, but if I join the representative democracy with the goal of continuing representative democracy, I don’t see that happen. Lawrence Lessig tried to do that, run for President and only do one single thing, which is pass a executive order to end the Super PACs in the US, and then he would immediately resign.

### Matthias Sander:
That rings a bell. Can you say that name again?

### Audrey Tang:
Lawrence Lessig.

### Matthias Sander:
Lawrence Lessig. When was that?

### Audrey Tang:
I think it was the two previous presidential election in the US. I’m not quite sure. He’s the creator of Creative Commons, an important constitutional scholar.

### Matthias Sander:
Do you think something like this, rebooting the system, as you said, could happen in our lifetime?

### Audrey Tang:
In Taiwan the President just said that we’ll do that, the Constitutional Reform Committee.

### Matthias Sander:
Sorry, but reforming the constitution is something else than really rebooting a system, right?

### Audrey Tang:
Well it’s either reform the constitution or do a revolution, if you want to change something as fundamental as mayoral elections.

### Matthias Sander:
It’s not only about elections. It’s about Taiwan as a country, relations with China as well, right?

### Audrey Tang:
No, I think what she promised during a constitutional reform, part of her inauguration address yesterday, was just to get people who are 18 years old to run to vote.

### Matthias Sander:
Absolutely. That’s one major thing.

### Audrey Tang:
That’s the only thing she said. Of course, because constitutional modifications is very difficult, it’s a very high threshold after a series of amendments that people did. Amendments seal the constitutions.

### Audrey Tang:
Of course the other thing is to make constitution easier to change, and that would then pave the way for further modifications. That ensures the possibility of a constitutional reboot, if you will. I’m not saying that this need to happen in my lifetime. In Taiwan, there are many people who want to see a constitutional reboot in their lifetime. I sympathize with them.

### Matthias Sander:
What kind of reboot…Maybe you can draw a picture which you like to see, maybe very precisely in practice what would happen.

### Audrey Tang:
Certainly giving the fundamental constitutional rights to animals and maybe nature personhood in future generations. That’s maybe the thing I care the most, because the current representative democracy almost by definition allows collective decisions to sacrifice parts of the world that does not have animals, the externalities.

### Audrey Tang:
That includes the nonhuman sentient beings as well as future generations of humans as well as nature personhoods. That would be the part that I care the most about. It may not require constitutional change, although it will help, like in the German Constitution where they put animal rights directly into the constitution. That’s one part.

### Audrey Tang:
The New Zealand – not quite – Constitution puts nature personhood possible, because they assume a Maori worldview of personhood not only for corporations but also for nature and things like – there’s many precedent in the world for that sort of thinking.

### Matthias Sander:
Would you say you’re an ecologist?

### Audrey Tang:
Why not?

### Matthias Sander:
It’s not something I have largely read about you before. Is it something that is lesser known about you, would you say, or is it something that automatically it’s implied in your worldview?

### Audrey Tang:
Right. If you search for deep ecology in my SayIt website, you’ll find the interview with the “Christian Science Monitor” \[laughs\] this January, where I talked a little bit about these things. I’ve been quite consistent about giving democratic power to nonhuman beings, but I didn’t quite label that as ecology. I did use that label three times in the past dialogues.

### Matthias Sander:
Yes, it is. It’s from the website. Three times.

### Audrey Tang:
Yeah, just search for deep ecology, and then there are three.

### Matthias Sander:
Do you use that website actually for yourself as an archive as well to…

### Audrey Tang:
Of course, of course. If it’s just ecology, then there’s much more.

### Matthias Sander:
I have to say I haven’t looked that up before. I didn’t think we would talk about that. Interesting.

### Matthias Sander:
Talking about the inauguration speech yesterday, there are some points that might be very interesting for you, the Digital Minister, in what President Tsai laid out. She said, for example, regarding the six core strategic industries, first, we will continue to develop our information and digital industries including IoT and AI applications. You think that’s great?

### Audrey Tang:
She also talked about making the governance systems more effective through digital transformation and a dedicated cabinet unit for digital affairs.

### Matthias Sander:
The Digital Development Agency.

### Audrey Tang:
Yeah, the Digital Development…I don’t know Commission, Council, Agency, or whatever.

### Matthias Sander:
In English it’s agency.

### Audrey Tang:
Yeah, so unit. Agency is good. She also talked about cybersecurity, also very important. It hit the right notes, and shows very clearly that it is not about a single ministry’s business. This is a whole-of-society approach, and correspondingly the whole-of-government approach.

### Matthias Sander:
A specialized digital development agency within the government, I thought it’s what you were already doing.

### Audrey Tang:
Sure. This is about institutionalizing this kind of rule in the law. When we had the Participation Officers or Presidential Hackathon or whatever, these are all in the level of regulations.

### Matthias Sander:
Did you just say “role”? I thought you weren’t playing a role.

### Audrey Tang:
Rule.

### Matthias Sander:
Rule, OK.

### Audrey Tang:
Yeah. This is the national administrative rule of policies. They maybe changed at the whim of a premier or a minister, because it’s not required by law. It is not written into the formative law of the cabinet itself.

### Audrey Tang:
What President Tsai is saying essentially is that we’re looking at – I wouldn’t say best – better practices in the past few years, and put it into a amendment to the act that defines the extent of the cabinet and how the administration, the executive branches constitute it and put digital to it.

### Audrey Tang:
Instead of just a horizontal ministers’ network which, although we institutionalized most of that at a regulation level, she would like the Parliament to have a deliberation on how to put it into law level, which is even more commitment.

### Matthias Sander:
Absolutely, and it’s a recognition of your work that it works entirely?

### Audrey Tang:
I guess. Or of people’s work then. I didn’t really do much. Of connecting good governance, effective governance, social sector-laid innovation with digital transformation, which was not a obvious link four years ago.

### Matthias Sander:
You aren’t very much involved, I guess, in this kind of industrial policy. We have to strengthen our semiconductor industry, we have to strengthen our ICT companies and stuff like that, right?

### Audrey Tang:
If TSMC wants to share their renewable energy designs, participate more in the circular economy talent pool, and offer their designs so that SMEs can make a greener and more circular economy recovery, then I’m very interested, in the sense of zero waste, zero carbon, and things like that.

### Audrey Tang:
I focus on the part that has a environmental, ecological – thank you – and societal public benefit. If there’s only linear economy and they focus mostly only on reducing external harm, then I’m far less interested.

### Matthias Sander:
One thing that was criticized these days is that there is only one woman as a head of a ministry.

### Audrey Tang:
Depending on how you count, one to four, but yes.

### Matthias Sander:
What do you think about that?

### Audrey Tang:
Compared to the more than 40 percent in the parliament it’s a stark contrast.

### Matthias Sander:
Could you be more critical maybe? Why is that happening? Many people think internationally, because you are here, you have this role, you have a very special biography, “Oh, Taiwan is such a progressive country,” or at least the government is so progressive.

### Audrey Tang:
The over 40 percent of the parliament women representation is very good except by Nordic standards.

### Matthias Sander:
I know, but then when you look at the government you’re like, “Oh, they are nearly all men.”

### Audrey Tang:
There’s a few reasons of that. It’s all very well documented. Because we’re twice removed from election politics. The population votes for the president, who appoint the premier, who appoint the cabinet.

### Audrey Tang:
Not only we’re not constrained by party politics, the horizontal ministers, vast majority, are non-partisan. We work with any party’s premier. Even the cabinet members, themselves, there’s more independent members than members of any party.

### Audrey Tang:
That creates a very different political culture. The new promotions to ministerial positions, a lot of them are from the senior career public servants, which, again, is very different from other cabinet composition who are mostly answering to their electorate in any European countries.

### Audrey Tang:
This is then asking why are career public service, why is the women not promoted enough? That’s a core question for our gender dashboard and the Council for Gender Equality to answer.

### Audrey Tang:
There’s many things. For example, the average age of cabinet members, if you take me out, it’s 63, or something. I contribute, so it’s now 62-point-something. \[laughs\]

### Audrey Tang:
You’ll have to ask what kind of culture during their formative years take women out from the career ladder and whether the societal expectation for them to spend more time with their family, if they’re pregnant, or if they bring children to work, and so on, whether the career public service is flexible enough to make that happen.

### Audrey Tang:
All this contributed to the fact that if you look at the very senior, like deputy minister level or director general level, there is a gender imbalance which contributes to what you’re seeing in the cabinet level.

### Audrey Tang:
What I’m trying to say is that this is symptom. This is not the root of the issue, itself. The root of the issue is in the career public service work culture that somehow is still – I’m trying to think of a nicer term – making women homemakers by default.

### Audrey Tang:
That really needs to change, and we are changing that. The effect could only be seen maybe 20 years later at the cabinet level.

### Matthias Sander:
This is lowest participation of women in Taiwanese government since ‘96, if I’m not mistaken.

### Audrey Tang:
It was consistently very low. \[laughs\]

### Matthias Sander:
It got from low to even lower, maybe.

### Audrey Tang:
It’s good to talk about it, but it’s consistently very low.

### Matthias Sander:
Yet, if you look at the numbers you’re like, “There must be more competent women, even with this kind of public career service,” which apparently doesn’t really favor women.

### Audrey Tang:
For a senior leadership position?

### Matthias Sander:
For senior leadership, yeah.

### Audrey Tang:
I agree. Dr. Tsai Ing-wen set a really good example because she’s president by merit. Everybody know that she get into this position by merit and not because she’s anybody’s wife or a daughter or any powerful politician. This shows a positive role model.

### Audrey Tang:
Before her there’s VP Lü Hsiu-lien, Annette Lu, who is a role model, too, but she is not part of this public service career path.

### Audrey Tang:
For people in the public service the glass ceiling was truly broken by Dr. Tsai Ing-wen. We see more people who want to commit to a career public service path in senior leadership positions.

### Audrey Tang:
They can cite Tsai Ing-wen, saying that she’s also a homemaker for her cats and dogs. That’s our first family. She can be a homemaker for nonhuman beings and still assume apolitical leadership position.

### Audrey Tang:
With Dr. Tsai Ing-wen continued example we’re already seeing a little bit of growth on the deputy minister level. That slowly continues, but to get to gender parity, it takes another generation.

### Matthias Sander:
Within the government, to understand your role even better, there’s also another minister without portfolio, Mr. Wu. He was minister without portfolio, he’s now a Minister of Science and Technology.

### Audrey Tang:
Now he has a portfolio.

### Matthias Sander:
Sorry?

### Audrey Tang:
He has a portfolio now. His portfolio’s the Ministry of Science and Technology. The minister of MOST.

### Matthias Sander:
Great acronym. How did that play out, exactly? Were there overlapping areas in your work?

### Audrey Tang:
We co-chair the weekly meeting ever since I joined the cabinet, the BOST weekly meeting. I look at the algorithmic interaction with law, or the Internet code and the civil code coincides, and provide advice to Minister Wu.

### Audrey Tang:
That’s always our working relationship. He would work on a science or technology development plan and I will essentially provide cyberspace impact assessment. That’s our working relationship.

### Audrey Tang:
We have a very close working relationship, not only meeting every week, but also meeting for projects, such as the science and technology counter-coronavirus workforce, and things like that.

### Matthias Sander:
You’re co-chairing this Thursday afternoon meeting, I guess?

### Audrey Tang:
For three and a half years now.

### Matthias Sander:
Can you tell me more about the coronavirus science and technology workforce? Who’s a member of it, how does it work, and what do you do?

### Audrey Tang:
There’s two branches. One is the medical branch that works on vaccines, rapid testing, remedy sphere, and things like that. Our branch work on the Cohack, the coronavirus hackathon, or collaboration hackathon, social innovation, mask rationing.

### Matthias Sander:
Mask rationing, as well?

### Audrey Tang:
Yeah, because it’s a digital system. Also, the Department of Cyber Security is in it, so also the very privacy-invasive, narrow and deep, but time-limited digital fence is part of it. Basically, any measure that concerns digital technology to reduce the R0 value is in our branch.

### Matthias Sander:
Is that also a national team? President Tsai mentioned that yesterday. Do you consider yourself to be the coronavirus national team, or something?

### Audrey Tang:
Everybody is on the national team if you’re wearing a mask.

### Matthias Sander:
In this team, what exactly is your role? Once again, are you a facilitator, a member?

### Audrey Tang:
Working various different values. There are people who are very worried that the National Health Insurance Card would be abused and the privacy budget that we have for it may be lower than we imagine.

### Audrey Tang:
I need to work out, for example, exactly how to make a connection directly to the NHI Agency so the intermediaries, including pharmacies, convenience stores, and vending machines, cannot read the pharmacy, pharmaceutical, and medical record of the person wielding the card.

### Matthias Sander:
Which is now possible soon?

### Audrey Tang:
It is not possible.

### Matthias Sander:
It was never possible?

### Audrey Tang:
It was never possible. You need a medical practitioner’s card to read that.

### Audrey Tang:
The interface design is also important. If the kiosk shows your name or the entirety of your national ID card, then the person standing behind you knows a lot about you, and so we need to change the interface, as well.

### Audrey Tang:
Lots of things, including legal design. The NHIA can only use NHI card for services that they do themselves or they do in conjunction with other public sector entities, and certainly not convenience stores.

### Audrey Tang:
The convenience store is, essentially, just providing a terminal. We need to make sure that they have the right cyber security and privacy policies in place so that they cannot retain anything about you, other than the last four digits of the national ID, which they require to collect your mask. Other than that, they don’t know anything about you, and things like that.

### Audrey Tang:
There’s a lot of very delicate balances because the NHI card is the only IC card that we have at our disposal. To do a real name informational system using a citizen digital certificate which has less than 25 percent active usage is unimaginable. This is like saying only one quarter of population have mask. Go figure. \[laughs\]

### Audrey Tang:
We really need to get a NHI card going, but we also need to be very careful to use our privacy budget well and responsibly.

### Matthias Sander:
Privacy budget? Does it mean you really have a financial budget, or are you talking as a matter for…?

### Audrey Tang:
No, it’s a way of saying.

### Matthias Sander:
It’s a trust budget with the population?

### Audrey Tang:
No, no, this is a mathematical term. For each transaction, assuming the other party already knows a lot about you, whether they can know more of you. That’s the privacy budget.

### Audrey Tang:
By showing up to collect mask they already know that you are one of 23 million, and not the other part of the population in the other place on Earth. Because you have NHI card you are part of the Health Insurance system, so you must probably be a resident or something, if not a citizen.

### Audrey Tang:
Already they learn about you just by you showing up with this card. Then, by inserting this card, they may also learn about your national ID. If we make sure that they do not store the national ID, and delete immediately the last four digits after each collection, then they know a little bit about you, but not too much.

### Audrey Tang:
Or if on the kiosk where we only display the first couple digits, by the first two digits the person who are behind you, if they look closely through kiosk, learns your household registration city, which is the first letter, and your gender, which is your second letter, but they don’t learn much more about you. That erodes your privacy a little bit. Not too much. That’s what I mean by privacy budget.

### Matthias Sander:
Are you still working on these issues right now?

### Audrey Tang:
Of course.

### Matthias Sander:
Are you doing adjustments? Because most of the systems are in place. They have been introduced, etc. Are you doing improvements on that?

### Audrey Tang:
No. Basically, I try out those services myself. I point out the privacy breaches, the overextension of privacy budget. I make sure that I point these out. I wonder why, but they listen. They change their ways.

### Audrey Tang:
When we actually roll out the service for real it ameliorates many people’s concerns about convenience stores magically being able to read medical reports, which is not true and cannot do so.

### Audrey Tang:
In any case, the point here is that there’s many people who are now designing new services based on the newfound fact that there’s now four million, five million people with the NHI application which can serve as a de facto mobile app ID. I.e. the 健保快易通, the app.

### Audrey Tang:
Also, the fact that the convenience store is so convenient people will naturally want the NHI card to be used for more, not just for medical mask, which is still medical use. For pretty much everything, medical use or not.

### Audrey Tang:
I am still working on that to lay out the regulatory and also norm impact that this kind of ID use will entail.

### Matthias Sander:
You’re preparing NHI cards to be usable as well for regular purchases out of convenience stores?

### Audrey Tang:
No, I am preparing arguments internally to other ministries who are very gung ho on this idea, and trying to get them to realize that we can, instead, use Citizen Digital Certificates, which is not a very strong argument because of the non-popularity of CDC cards, but we’ll try.

### Matthias Sander:
Because of the non-…? Sorry.

### Audrey Tang:
Non-popularity.

### Matthias Sander:
I’m a bit surprised hearing you talking about privacy like that. People I talked to before, they were like, “Oh, I haven’t really heard her on privacy.”

### Matthias Sander:
You mentioned in one interview, very shortly, “Oh, everything is fine. This is just temporarily. We have to use…”

### Audrey Tang:
You mean the digital fence?

### Matthias Sander:
Surveillance in general, but the digital fence, for example.

### Audrey Tang:
The digital fence is a huge encroachment on privacy, and not just privacy, but also freedom of movement, and of things like that, fundamental freedoms, and for 14 days. It’s a lot.

### Audrey Tang:
The CECC is looking to reduce it, like if you fly over from New Zealand, maybe you just do 5 days, instead of 14 days, of home quarantine. That, theoretically, shortens the breach of privacy, and also make it more convenient.

### Audrey Tang:
The point is that we realize it’s a deep privacy intrusion. It’s the alternative would be worse, which is physical barricading and mass panic.

### Matthias Sander:
Maybe you don’t trust people?

### Audrey Tang:
To stay at home?

### Matthias Sander:
Yeah.

### Audrey Tang:
Well there’s two things. If we really don’t trust people we would have gone with bracelets that send out notifications when you try to take it off. That would show ultimate distrust.

### Audrey Tang:
The choice of mobile phone and not GPS signal, but rather triangulation, which has a coarse resolution, which shows that there’s a certain respect of people, and shows that people, if they’re addicted to their phones, it’s their choice.

### Audrey Tang:
A phone is a communication device. The chatbots, for example, ask for their temperatures, ask if they want anything, and maybe chat with people. It’s also the primary screening, where people can have videoconferences to voice their concerns during the quarantine.

### Audrey Tang:
Of course, it’s a surveillance device, but we choose that form factor because it is also a connecting device, unlike a bracelet, which would be a pure surveillance device. It’s dual use in that sense. It’s dual use.

### Audrey Tang:
At the end of the day, we accept that this is a constitutionally approved. Certainly, better than barricading entire hospital alternative. We pay stipends for people who work with the home quarantine, but we do so because we had a constitutional debate right after SARS on what are the acceptable perimeters.

### Audrey Tang:
That builds a different social norm. I’m not saying that this social norm is good. This is the least bad so far. \[laughs\] With rapid testing, with more medical advances hopefully we can reduce the harm, and certainly the time extent, of people suffering from home quarantine and surveillance.

### Matthias Sander:
My last article happens to be about the lack of a bigger debate on privacy in Taiwan regarding these surveillance measures that have been introduced.

### Audrey Tang:
That’s because the norm building. The eID is a great choice, to have this debate, because the abuse of the paper-based ID card.

### Audrey Tang:
Like if you go to buildings, sometimes they ask you to leave your ID card there in exchange for the right to enter. Or if you go to give a lecture, sometimes people ask for photocopies of your ID card.

### Audrey Tang:
They ask you to get your ID card to them. You don’t know whether they make color copies. Now, with the current forgery technology, it’s actually very easy to make a very convincing color photocopy of your physical ID card.

### Audrey Tang:
With the abuse of the paper-based ID card on one side and the not quite abuse, but almost a wish to abuse the National Health Insurance Card, the design of the new e-ID is trying to change the norm back into a more privacy preserving and privacy respecting kind of use. That was its original intent.

### Audrey Tang:
For people who don’t want an ID card at all, they want to end this whole branch of abuse, then of course they would also want to constrain, by law, the NHI Card use to purely medical needs, but then this changes the entire social norm so much that there’s many businesses that will have to massively restructure how they do authentication.

### Audrey Tang:
If they cannot do either of these two branches, then maybe we’ll have to use a CDC card pervasively. Next time when there’s mask rationing maybe we say the people who don’t have a CDC card don’t have mask at all. Maybe we cannot say that. We will have to work toward popularizing that.

### Audrey Tang:
This delicate choice of norm building is now a central topic in the new e-ID debate. It’s long past time that we have a good public deliberation on this.

### Audrey Tang:
Coupled with the GDPR adequacy work, as well as the work on the digital agency you just mentioned and the National Human Rights Council on the Control Yuan that is going to be set up very, very soon as our national human right overseeing branch of the government, that will all shape together to have a due process on privacy not as a afterthought, but privacy as a inherent design value. I very much look forward for that to happen.

### Matthias Sander:
Sorry, you just mentioned GDPR. What did you say?

### Audrey Tang:
The GDPR adequacy work, which will necessitate a data protection authority.

### Matthias Sander:
Are you currently working on that, too?

### Audrey Tang:
Of course, I’ve been working on that for three-and-a-half years.

### Matthias Sander:
Where is it at right now in Taiwan?

### Audrey Tang:
At the moment it’s a office within the NDC, the National Development Council, but because it doesn’t have independent budget and independent personnel it is not quite up to GDPR standards. There needs to be a proposal bill to our Personal Data Protection Act, as well as a formative act to enable this kind of independent entity.

### Audrey Tang:
There’s already a draft. It’s not public yet. The hope is that we can get all of this mechanism going before actually issuing e-ID. Certainly, before issuing it mandatorily to people, because otherwise there’s no way we can get GDPR adequacy.

### Matthias Sander:
Let’s stick to the privacy issue when it comes to the fight against COVID-19 and all the new measures that have been introduced. The Taiwan Association for Human Rights, they asked the government for answers about these different surveillance measures. Their request is seven pages.

### Audrey Tang:
No, when they asked through MPs the Department of Cyber Security gave responses, but when they ask without going through MPs the DoC gave very vague answers. We know that.

### Audrey Tang:
There’s a few public hearings by the MPs, in which case the Department of Cyber Security did give more details.

### Matthias Sander:
You think that’s enough? The Taiwanese people are informed enough?

### Audrey Tang:
No, it’s never informed enough. There’s two things going on here. One is people accepting, or even endorsing, the digital fence as the acceptable norm.

### Audrey Tang:
More than 90 percent of people do, which is very dangerous from a civil society perspective, because that means that they have only 6 or 9 percent of natural allies if they want to think of better alternatives and demand the government to be accountable. I am part of that six percent, by the way.

### Matthias Sander:
Are you?

### Audrey Tang:
I do think there need to be better alternatives, and we need to work on those.

### Audrey Tang:
We’re evaluated a lot of technological solutions. There’s no one technology so far that I can safely and with good conscience say it’s a better alternative than the digital fence for home quarantine use. There’s many things to balance.

### Audrey Tang:
You don’t know how many bracelet manufacturers come to me. \[laughs\]

### Matthias Sander:
What else did you evaluate? What kind of technology solutions?

### Audrey Tang:
Bluetooth, and also the home…

### Matthias Sander:
How would the Bluetooth work? Sorry.

### Audrey Tang:
Home monitoring devices, like a home bot, like a voice assistant speaker. You put it to the place where you’re quarantined. It maintains the Bluetooth connection to your phone or your watch, and so it knows in even finer detail, like which room you’re in, which is suboptimal.

### Audrey Tang:
Many other things. Nowadays there’s the quarantining hotel, which you don’t need the digital fence because there’s virtual fence. I really couldn’t say that it’s always preferred.

### Audrey Tang:
There’s many alternatives. If it’s a opt-in basis, like if people prefer a quarantining hotel, now there’s plenty of quarantining hotel that could subsidize for the digital fence because you really cannot escape the hotel. It’s a physical barricade.

### Audrey Tang:
What I’m trying to get at is that there’s many alternatives, each with its own drawbacks, pros and cons. If we can honestly say that for some people it’s preferable, then we introduced that as an alternative, like the quarantining hotel.

### Audrey Tang:
In cases where it may look more secure or effective, but it’s actually net privacy loss for everybody involved, like the bracelet or the watch, we don’t recommend it. That’s the evaluation matrix we’re having.

### Matthias Sander:
When was that evaluation done?

### Audrey Tang:
Every day, literally.

### Matthias Sander:
Before the digital fence system was introduced?

### Audrey Tang:
That was during SARS in 2004, all the way to the Constitutional…

### Matthias Sander:
At the time, there was no fence, right?

### Audrey Tang:
No, but the Constitutional Court charged the legislature to…

### Matthias Sander:
I’m asking about your evaluation right now.

### Audrey Tang:
Of that, yeah. The digital fence was created by Chunghwa Telecom and the Department of Cybersecurity, and immediately have, because of false positives and whatever, many…and also the integration of other telecom signals that came gradually – many systemic issues that needs work.

### Audrey Tang:
The improvement is ongoing. There’s no single day where we say, “OK, this is good enough. We don’t change it.” In fact, one of the main thing asked to people under quarantine is, “Is there anything that the system is bothering you?” and then tracking how we can fix that.

### Audrey Tang:
For example, the initial inform, which talks about the phone that we give people, did not include their private phones. Certainly, if we warned them about that, it’s not in English, so it committed \[laughs\] a lot of miscommunications in this matter. That, of course, is our fault, and we did change that afterwards.

### Audrey Tang:
Just like the mask pharmacy map, the initial versions of the digital interventions leave many thing to be desired and is a continuing improvement process.

### Matthias Sander:
You would say you’re clearly a privacy advocate?

### Audrey Tang:
I would say that the freedom of independent thought, of thinking unpopular ideas, of amplifying the thoughts of less than six percent of people, is important in a democracy because it keeps the administrative power in check. It shows the government need to trust the citizens without requiring the citizens to trust back, which is the precondition of social innovation.

### Audrey Tang:
If the government has 100 percent citizen trust then there’s not much room for digital innovation, anyway.

> (phone rings)

### Matthias Sander:
Do you want to answer the phone?

### Audrey Tang:
Yeah, I have another meeting to attend. Anything else? Any final questions you would like to ask?

### Matthias Sander:
Absolutely, lots of things. Maybe quickly ask Zach if we could meet a second time, as well, because this is going to be a bigger…

### Audrey Tang:
I don’t manage my schedule, so if he says yes, yes.

### Matthias Sander:
If you don’t mind.

### Audrey Tang:
I don’t mind. I don’t mind.

### Matthias Sander:
Maybe you have a say in that, too, I hope.

### Audrey Tang:
No, I don’t.

### Matthias Sander:
No?

### Audrey Tang:
I actually don’t.

### Matthias Sander:
Really not?

### Audrey Tang:
Yeah, I tell Zach from 7:00 AM to 7:00 PM it’s yours.

### Matthias Sander:
Basically, he is your boss?

### Audrey Tang:
Also ST, and also Joel. These three people have access to my calendar.

### Matthias Sander:
That’s interesting. I hope we can meet again. Let’s go quickly through some questions towards the end, maybe.

### Matthias Sander:
Quickly, on this privacy issue, because that’s a very interesting topic to many people in Europe especially, have you read that study by Vice Premier Chen Chi-mai and others, Howard Jyan, recently on contract tracing?

### Audrey Tang:
The abstract. I talked to Howard and the Vice Premier a little bit about it, but I did not read it in detail.

### Matthias Sander:
What did you ask them?

### Audrey Tang:
I asked about the anonymization technique they used. The whole system predicates itself on, essentially, working with SMS numbers and nothing else.

### Audrey Tang:
The system knows, for example, how many numbers are there and how many numbers are in vicinity or proximity of each other, and knows to notice those numbers, but the whole point is not to link those numbers with real people. The whole point was to delete such linkages once the occasion is over and you already sent out the SMS messages.

### Audrey Tang:
I asked Howard, first, whether that’s true, and also what kind of aggregation or anonymization measures that they have taken to ensure the proper deletion of additionally collected data.

### Audrey Tang:
The basic philosophy, what I gather from Howard, is that they don’t actually collect more data. This is what the telecoms are already collecting anyway to improve their roaming service, I’m sure.

### Audrey Tang:
This is a out of purpose use, and it operates purely on SMS level. That’s what he told me.

### Matthias Sander:
That’s good enough for you?

### Audrey Tang:
No, it’s not, but that’s some accountability.

### Matthias Sander:
Because I was surprised, reading that study, how they managed to know who out of these more than 600,000 traced people went to see a doctor later for respiratory syndrome.

### Matthias Sander:
I also asked, I can’t say who, two people directly involved how they did it. They couldn’t really explain it to me, or they wouldn’t explain it to me. It was weird answers.

### Audrey Tang:
If they have a clinical visit and they leave their primary mobile phone that is the same as the phone that received the SMS to the NHI system, because the insurance pays for that visit, then conceivably you can link that through the database.

### Audrey Tang:
It’s very inaccurate because, first of all, it’s not required that you give your phone to your clinic doctor. Second, it may not be the same phone. Also, third, maybe that phone was used by somebody else and the person who visit is not the person who received the SMS. Take that with a grain of salt.

### Audrey Tang:
My guess is that that’s how it’s going to go.

### Matthias Sander:
NHI Cards, they don’t contain mobile phone numbers?

### Audrey Tang:
No, they don’t contain mobile phone numbers, but in each individual clinic’s registration system for the clinic to reach you.

### Matthias Sander:
The government didn’t check each individual clinic’s registration system to know? Apparently they did.

### Audrey Tang:
No, it’s the other way around. It’s like the travel history thing. It’s not like we upload each individual visit to the NHIA, but rather the NHIA makes this information available so that soon as you insert this card to the clinic’s system the system knows whether it’s a match or not on the list of person who, for example, stayed in Wuhan.

### Audrey Tang:
It happens at the clinic side, is what I’m saying.

### Matthias Sander:
How can you centralize this data for more than 600,000 people?

### Audrey Tang:
If there is a match they say that there is a match and they tell the NHIA that. The NHIA can count the number of the clinic, because the NHIA pays for that visit. When they ask for money for that visit they can additionally say, “By the way, this is from a person who was in contact.”

### Matthias Sander:
Or who was traced after the Princess Diamond.

### Audrey Tang:
Or whatever, like a colored coin, additional meta data. If they say so, then the NHIA can make a tally soon as they ask for a reimbursement for that visit.

### Matthias Sander:
What I think is interesting, you’re saying it’s very inaccurate, which I agree with.

### Audrey Tang:
Super inaccurate.

### Matthias Sander:
In this study they use this data. The study showed – I’m not sure if it was in the abstract. I guess it was – that out of these more than 600,000 people who went, and then those who went to see a doctor, their proportion was lower then in the general Taiwanese population.

### Audrey Tang:
Sorry, what proportion?

### Matthias Sander:
Sorry. The people who went to see a doctor for respiratory syndrome out of the 600,000, their proportion was lower than the proportion seeing a doctor among the general Taiwanese population.

### Audrey Tang:
Meaning that they took protective measures?

### Matthias Sander:
Absolutely, that’s what I’m saying, but in the study they’re saying this shows the success of big data analytics, of contact tracing, which to me is completely not logical because either they’re already infected by the Diamond Princess passengers at the time, and then they have syndromes, etc., or not. It’s not because of contact tracing that they have…

### Audrey Tang:
No, what this can draw, and only in a correlation sense, not causation sense, is that people who have received that SMS take care of themselves more – there’s no dispute about that – and then that’s it. That’s pretty much what the data can say.

### Audrey Tang:
Like a control a group who did not receive any SMS and a experimental group who did, regardless of the methodology, the group which received the SMS obviously wore their mask more, or whatever. Then, of course, because of that they get less respiratory diseases, which is very logical.

### Matthias Sander:
Absolutely.

### Audrey Tang:
To bill this as a triumph of contact tracing is, I guess, in a very roundabout way.

### Matthias Sander:
Audrey Tang, thank you so much. I very much hope seeing you again. I’d like to continue this conversation very soon, to do really a big, in-depth portrait. I hope you’re OK with that.

### Audrey Tang:
Of course.

### Matthias Sander:
I hope we can find a time for that.

### Audrey Tang:
All right. \[claps\] That means I’m good to go?

### Matthias Sander:
Thank you very much.

### Audrey Tang:
Thank you.

