# 2020-02-21 Conversation with Nathan Kaiser

### Audrey Tang:
All right. There’s three digital systems about identity currently in use in Taiwan. Since you are a Taiwan national, you are probably familiar with all three, right? There’s the national healthcare part, which I’m sure that you have to say SE card, but it is restricted to medical use.

### Audrey Tang:
The second one is the National PKI card, or the Taiwan citizen certificate. A little-known fact is that it’s also issued to foreigners, although there’s a little applications for foreigners, except for I think there’s an online system to query whether you’ve banned from entering Taiwan, but I don’t think it’s very useful.

> (laughter)

### Audrey Tang:
In any case, it’s used for tax filing, of course, but also electronic signatures in general in all kinds. I think the PKI card is relatively stable, and there is a way to virtualize that card into phones already, so you don’t have to carry the physical card.

### Audrey Tang:
That is called the TFIDO, the Taiwan FIDO. This conforms to the international FIDO standard. That’s the second one. It’s based on the Taiwan National, like PKI card. The third one is based on the paper-based card, which is called the national ID card.

### Audrey Tang:
It’s not digital at all. The non-digital, paper-based card, on the other hand, has the photo, has all the information on it, and is actually, due to a very curious law, people, it’s mandated to carry with them all the time with them.

### Audrey Tang:
It actually has no enforcement rules, so if you don’t carry, I don’t really think anything happens to you. These three very different systems are in the process of virtualizing into mobile devices, using FIDO as the main idea.

### Audrey Tang:
Now, there is a lot of people who prefer if they can have the laser two cards, the National PKI card, and the paper-based ID card to be somehow glued together, so that you can have one card that serves both purposes, and add to that the NFC interface makes it easier for people to identify themselves without going through the physical IC-swiping card.

### Audrey Tang:
On the other hand, there’s people who prefer to have them as separate cards. We’re now developing technologies to allow both use cases on an opt-in basis, so that people don’t have to activate the PKI card on their ID card if they don’t want to, but they can if they want.

### Audrey Tang:
That is the current plan. There is also, in the civil society, a lot of experiments about decentralized identity, like self-signed identities, especially in the very vibrant blockchain communities, like I’m also on a foundation board with Vitalik Buterin to work on intersectional groups-based identities.

### Audrey Tang:
At the moment, that identity is only used for the general population in smaller scales. For example, the Orchid Island, which is a smaller offshore island from Taiwan. The Tao, the indigenous people, made an identity of the Tao coin, the T-A-O coin, I think.

### Audrey Tang:
That is the idea that they can have a self-signed, not only cryptocurrency, but also a kind of certificate authority to make sure that only people who identify with the Tao culture is part of their cryptocurrency ecosystem.

### Audrey Tang:
We see that as a really good expression of Taiwan’s transcultural nature to allow more than 20 national languages now to have their identities. That is currently in a more regional basis. Of course, without blockchain, the Taitung coin or whatever, they are also their own tokens of appreciation of being a virtual Taitung citizen and things like that.

### Audrey Tang:
That goes into gamification territory, and I will spare you with the details.

### Nathan Kaiser:
\[laughs\] Thanks a lot, Audrey. That was very useful. I think a lot of work has been done, and is being done, and I think that’s quite impressive. When you talk about decentralizing, I think, not edge cases, but edge concepts are…

### Nathan Kaiser:
Then obviously, interoperability, but also, how agnostic are these systems? Would they be bound to one blockchain or several? Would it be open in the sense that other people could add their identity concepts on top of a fundamental structure? How do you see that?

### Audrey Tang:
There’s two different ideas. One is about the cybersecurity, the property of the system that we use. One is about social trust. These are related, but these are not the same concept. In Taiwan, of course, cybersecurity is one of the top priorities.

### Audrey Tang:
A lot of the systems that we introduce, including the Sandstorm system that I introduced to the public service as part of our everyday virtual workspace, we ask white hat hackers to do penetration testing for extended amount of time, like six months for the Sandstorm case, a similar amount for the self-driving car lab, and things like that.

### Audrey Tang:
We are getting into a habit of just getting the white hat hackers a lot of opportunities to file CVEs before any system goes online. I think that is not strictly about social trust, but it is about this fundamental trust of the infrastructure.

### Audrey Tang:
Of course, more advanced techniques, such as proof-carrying code, all help to reduce the attack surface and make penetration testers’ work easier.

### Audrey Tang:
Now, on the social trust level, we have the national standardized OpenAPI standard from the Linux Foundation called the OAS3. We also have the national standardized schema, .gov.tw, that lists the common schema for computer age systems to interoperate.

### Audrey Tang:
We further have a procurement rule that says that, if you procure an information system that has input and output functions for people, then the procuring agency can demand the vendor to produce such OpenAPIs so that robots can do exactly the same techniques as people have for import, export, and also interactive components.

### Audrey Tang:
If the vendor says that they have to charge extra, or they cannot make it an API-first design, then the vendor can actually be disqualified for discrimination against robots. Not really that, but we use the same section that talks about disabilities.

### Audrey Tang:
Like you cannot build a website that say only people with sight can see it, but people with blindness cannot. We use that purpose section and introduce procurement rules so that whenever any agency procure anything, if they want API access, they can get it essentially for free.

### Audrey Tang:
That is the interoperability argument, and that is how we build the different systems from different back ends, like the civil IoT system, which is the integrated system from the social sector that measures air quality.

### Audrey Tang:
Also, from the public sector, also from the private sector, but because everybody talk the same OpenAPI, since are things the API in this case, we are able to then interoperate without the government mandating control.

### Audrey Tang:
Rather, we’re supporting the ecosystem of existing standards, and we use that for many other things as well. That is also why the TFIDO Project uses the FIDO standards, instead of inventing things on our own.

### Nathan Kaiser:
That makes a lot of sense. It’s not the Taiwan-only kind of approach. Absolutely. A question that’s super interesting. I’m learning a lot. Thanks, Audrey. Question, is there an underlying data strategy to the different bits and pieces that you just mentioned, or is it more bottom-up, that we have these bits and pieces, and then you build the data structure on top?

### Nathan Kaiser:
How do you see that in the future, and also, what’s the current status?

### Audrey Tang:
That is an excellent question. The main idea behind this social acceptance is actually the idea of what we call data collaboratives. Data collaboratives is not a novel idea, but I think it’s only viable in a country with a large civic space.

### Audrey Tang:
Meaning that, when the, for example, the Civil IoT Project, it is essentially thousands of people who voluntarily measure air quality by their own, without any government mandate or without any private sector investment.

### Audrey Tang:
They build more legitimacy than the government or the private sector, because…It’s actually mostly primary school teachers. Also, they teach about data stewardship for children. This is important because of two things.

### Audrey Tang:
First, that if you learn data stewardship when you are very young, then you don’t tend to view data from a consumer perspective. You tend to view data from a stewardship perspective. The GDPR rights, for example, make much more sense if you start operating an AirBox at six years old.

### Audrey Tang:
It makes no sense if you are purely a consumer, because then you will be in the illusion that the data is not yours, but rather Facebook’s or something like that. That’s the first thing. It’s about competence in data production and stewardship.

### Audrey Tang:
That’s the first strategy, an overarching strategy. It’s because, of course, on the idea of broadband as human right. That’s the first thing. The second thing, I think, is even more interesting. It’s that whenever we “standardize” anything, we make sure that the civil society still maintains higher legitimacy.

### Audrey Tang:
It’s the public sector joining the social sector’s legitimacy building enterprise. This is because, in Taiwan, the democratization starts with local level communities that led to very well-known charities, such as – Tzu Chi, CareUS Foundation, or the Homemakers Union.

### Audrey Tang:
The list goes on. The social sector organizations have actually higher legitimacy, even overseas, than the president, but the presidential election is not until 1996, but the civil society has built their legitimacy long before that.

### Audrey Tang:
It is interesting to say that, in every other jurisdiction, whenever you have something like the AirBox happening, the environmental minister will be very top-down. They will like to see their legitimacy not be challenged.

### Audrey Tang:
In Taiwan, we are OK of Taiwan’s national government’s legitimacy being challenged by the local municipal governments or by the civil society, because we start with less legitimacy, anyway. We cannot beat them. We must join them.

### Audrey Tang:
That is what led to this kind of swarm-like experimentation and the idea of the, for example, for the continental law system, where the only jurisdiction for a long time that introduced general purpose sandbox.

### Audrey Tang:
For fintech, for self-driving vehicle, for 5G, and for basically anything other than money laundering and funding terrorism, you can challenge existing regulations and have a one-year exemption from the existing regulations.

### Audrey Tang:
Then, if it’s good for society, the public sector then just standardize your approach as the new regulation. Again, this is social norm, norm-first innovation. I think it’s one of the overarching strategies, in addition of data competence and human right for broadband.

### Nathan Kaiser:
Interesting. When you say that it comes bottom-up, I can see that historically. I think Taiwan is really, it’s not the only country that has that, but it’s one of the few countries where it’s very, very clearly like bottom-up was necessary, and it worked.

### Nathan Kaiser:
At the same time, standards matter. You were also talking about FIDO. You were talking about other standards, or you were talking about the, your said your position with the…

### Audrey Tang:
…OpenAPI, and things like that, yes.

### Nathan Kaiser:
Right. What about Taiwan internationally. Can it contribute with its positive experience bottom-up? There’s always room to do more internationally, not just as a recipient of standards, but also as a contributor to standards.

### Nathan Kaiser:
I’m always talking about data and identity. What’s your view on that? What is it you do? What’s left to do?

### Audrey Tang:
It is true that in many standard-making bodies, there were confusions about Taiwan’s status and how much the Taiwan government can do in an official position, which is why a couple years ago I asked the Ministry of Civil Service to relax their rules so that public service people can also serve on the board of international NGOs.

### Audrey Tang:
For example, I’m now wearing four hats. I’m not only Digital Minister of Taiwan, but I’m also a board member of the New York RadicalxChange Foundation with Vitalik Buterin and the Digital Future Society, which I’m flying to, which is the Barcelona, the Mobile World Capital people. It’s a think tank. Then also, Counsel Foundation, which starts in Madrid but is now in Amsterdam.

### Audrey Tang:
It is a participation platform. By virtue of me having three international NGO board member status, I can contribute to the data governance and to, for example, Internet Governance Forum and so on, wearing these international NGO hats, without having the wear the Digital Minister of Taiwan hat, which is sometimes less convenient, for obvious reasons.

### Audrey Tang:
That is one of the workaround. I wouldn’t say strategy. It’s one of the workarounds that we make. The other strategy is also to bring the people to Taiwan. For example, the Web Conference, which I am also helping with to run some of the sessions, is going to take place April 20 to 24 in Taipei.

### Audrey Tang:
It’s organized by the, I think, Academia Sinica folks, as well as the Taipei City and things like that. It’s important, because then the Web Conference brings the web community, as well as all the newest developments on the open version of the standards.

### Audrey Tang:
I’m not talking about proprietary, but rather the open standard ecosystem players to Taiwan, so that they can build personal connections with the Taiwan local working groups, so that we don’t have to send the entire working group to a jurisdiction that may or may not issue us visa.

### Audrey Tang:
We can just get those international workers to Taiwan to build connections so that we can then host our own forums. That’s how, for example, the APrIGF eventually held in Taipei a few years ago.

### Audrey Tang:
I’m very happy to see that the .asia, the Asia-Pacific Internet Governance, now has a new board member, Nicole Chan, who used the head, the minister for the National Communication Commission just a while back.

### Audrey Tang:
We are just observing that our, I wouldn’t say retired, but not-on-active-duty ministers can now take place on important positions in standard-making organizations. That’s another strategy.

### Nathan Kaiser:
Which is a standard strategy, and I think it’s a proven one, so we should be doing as well from Taiwan. I agree. By the way, I can tell you that for the Web Conference and other ones, this works, because I have a couple of friends or colleagues at Berkman Klein Center who go there and who have gone there.

### Nathan Kaiser:
The word is spreading, I can assure you, yeah. \[laughs\] Interesting, OK. I’m based in Boston now for three years. I think what still is a, slightly switching topics, but what I can tell the local offices, Taipei representations or quasi consulates are still struggling, which is normal.

### Nathan Kaiser:
Every consulate of every country struggles, but how do you think that could be used better or more as a beachhead into not necessarily just the academics, but also into tapping the local startups abroad, bring the Taiwanese startups abroad, and vice-versa?

### Nathan Kaiser:
That being said, I’m talking with MassChallenge, where I’m an expert, whatever that means. That’s just a title they give you. It doesn’t mean much. \[laughs\] You don’t have to accept it. I’m also thinking of helping their colleagues, the existing relationship with Taiwan, I think that program that they’re going to renew this year.

### Nathan Kaiser:
How do you see that? Again, just back to the consulates. What could be done more, or what do you see their role?

### Audrey Tang:
When you say the consulate, do you mean that the Ministry of Science and Technology’s delegate?

### Nathan Kaiser:
Yes. In Boston, that’s the one it is, actually, right. I call it the…Yeah.

### Audrey Tang:
You know Jonathan Chen, right? Have you met with Jonathan?

### Nathan Kaiser:
Yes. Actually, I’ve met with him once or twice here, and also Victoria.

### Audrey Tang:
Yeah, that’s great. They’re a relatively new dispatch. I think they’re the newest MoST dispatch. Of all the most dispatches which started – the Science and Technology, I mean – which starts, I think, in EU and in Canada, France, UK, Los Angeles, Houston, and so on, I think the Boston one is the most new. Please mentor them well, I guess. \[laughs\]

### Audrey Tang:
It is true that we are not currently having a lot, especially around Boston, the same engagement that we are having with the Asia Silicon Valley Project. The Asia Silicon Valley Project, I guess, unfortunately, by virtue of their name spend much more amount of time on the other coast.

### Audrey Tang:
The other coast, which is the other side of the Pacific. Anyway, the ASVDA Project is probably the one that your outreach around these sort of startups, especially around machine learning, but of course, also around IoT and things like that.

### Audrey Tang:
That’s our lecture project, to build the startup-based connections to send the startups from both ways into their respective markets. There is quite a few contact windows in the West Coast about the ASVDA Project, but I’m not sure whether the Boston delegate have tapped into similar structures or whether they’re interested in building complementary structures.

### Audrey Tang:
That is the idea. That is the goal. It is what we call talent circulation. We’re not afraid of brain drain. Brain drain is the best. I’m one of the drained brains.

> (laughter)

### Audrey Tang:
When those brains circulate back, they tend to bring with them not only themselves, but the entire ecosystem. \[laughs\] I think talent circulation is certainly our goal. I think one of the more important ways that people can contribute is, again, not through the consulate system, but through the private sector and social sector systems.

### Audrey Tang:
I’m pasting you the Talent Circulation Alliance, or the TCA. It’s, I think, one of the most interesting and exciting new approaches, where they used digital dialogs like crowdsourcing and all sort of ways to co-write a talent-based white paper that can connect not only Silicon Valley, but the entire US, Taiwan, and other jurisdictions as well.

### Audrey Tang:
The result of which will become official recommendations of the Amcham white paper, The American Chamber of Commerce, which then will be then overseen by private sector people as well, because Taiwan circulation, by default, benefits them as well as the public sector.

### Audrey Tang:
I think I would encourage you to maybe reach out to the TCA folks and see what they can do on the East Coast. That will be much more enlightening for our consulate paper, rather than them having to drive this effort toward the complete realization of our shared goals.

### Nathan Kaiser:
Interesting. I wasn’t aware of the talent circulation. I’m going to look that up and reach out. I’m also aiming to meet up with them in Boston next week. I’ll try to get that going, and I’ll try to give you some feedback by email or so.

### Audrey Tang:
Yeah, please do. That would be awesome. MassChallenge looks really interesting. This is the first time I’m aware of this work.

### Nathan Kaiser:
I’m on my phone, and by the way, Audrey, my phone battery is almost dead. I managed to not charge it well. The half an hour is almost done. Let me, thanks a lot. Can you share the call later, the recording, or something?

### Audrey Tang:
Yeah, I’ll send you the video, and I’ll also make a transcript and send that you in a couple days.

### Nathan Kaiser:
Super nice, thanks. Then let me reach out to you again by email or so. We can take it from there.

### Audrey Tang:
No problem. I am very accessible, so we can just write anytime. OK.

### Nathan Kaiser:
Hey, thanks a lot. It’s just really, thanks a lot.

### Audrey Tang:
No problem, no problem.

### Nathan Kaiser:
You’re the best.

### Audrey Tang:
Yeah, you, too. OK, cheers. Bye-bye.

### Nathan Kaiser:
Cheers. Bye-bye. Thanks, bye-bye.

