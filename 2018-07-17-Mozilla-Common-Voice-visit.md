# 2018-07-17 Mozilla Common Voice visit

### Zsehong Tsai:
Hi, I’m Tsai Zsehong from the BOST.

### Audrey Tang:
He is responsible for the proper allocation of our science budget.

### Zsehong Tsai:
It’s the policy of the budget process.

### Audrey Tang:
Right, the process.

### Michael Henretty:
So you don’t have a checkbook or you do have a checkbook?

> (laughter)

### Michael Henretty:
A process of checkbooks, got it.

### Audrey Tang:
That’s right.

### Herbert Tsao:
This is Herbert. I’m from BOST. I’m a deputy director in BOST.

### Michael Henretty:
Nice to meet you. My name’s Michael Henretty. I’m currently leading a Project Common Voice for Mozilla.

### Alex Klepel:
I’m Alex Klepel. I’m leading the communications part of the Open Innovation Project.

### Michael Henretty:
Common Voice is a part of Open Innovation.

### Desigan Chinniah:
I’m Desigan Chinniah, based out of London. Audrey and I met briefly at MozFest, which you were a virtual participant.

### Audrey Tang:
That’s right.

### Desigan Chinniah:
Thank you very much. This year you have to come.

### Audrey Tang:
In a higher resolution version, like Planck-scale resolution?

### Desigan Chinniah:
Yeah, Skype was just not good enough.

### Audrey Tang:
\[laughs\] That’s right.

### Desigan Chinniah:
I’ve been at Mozilla from back when we were a hundred people. I look at the innovation and emerging technologies piece. I look at external relationships. How do we work with outside world, the real world.

### Audrey Tang:
Awesome.

### Kelly Davis:
I’m Kelly, Manager of the machine learning team. We work on things like machine learning, in terms of speech recognition, speech synthesis, translation, automatic translation, that type of stuff. We are consumers of the data sets that Common Voice is producing.

### Michael Henretty:
Common Voice was his idea. He’s been...

### Audrey Tang:
Aha, OK.

> (laughter)

### Irvin Chen:
I’m Irvin from Taipei. I’m helping the Common Voice’s Traditional Chinese staff and getting it up.

### Joe Cheng:
My name is Joe Cheng. I’m actually based out of here, in Taipei. I’m on the product team for Taiwan markets. I’m not directly involved in the Common Voice Project, but I’m here to try to understand, see how we can we can help out from what we hear.

### Audrey Tang:
Let’s get started. Who would like to give a sketch of your current progress?

### Michael Henretty:
I can give a little rundown of what Common Voice is and what we’re trying to do over the next six months. Maybe that would be a good place to start.

### Michael Henretty:
Common Voice is Mozilla’s initiative to crowdsource a large data set of human voices in every language, every accent, every dialect, every gender, to be used in speech technology, specifically speech-to-text technology, but other forms of speech technology, as well.

### Michael Henretty:
Also for things like language and cultural preservation for under-resourced languages, which is a use case that has recently emerged with languages like Welsh, and other smaller languages. It’s very simple how it works. If you haven’t seen it, it’s just the website where people can go and read sentences into their microphone on their computer and Android and iPhone.

### Michael Henretty:
People can also listen to those recordings and verify if what they said is accurate. This is also an important part of the data set collection, because we needed to be very accurate if the speech technology part is going to work. That’s the whole project. Currently, we’ve collected about a thousand total hours of human voice, mostly in English, because we started in English last year.

### Michael Henretty:
We published our first version of the data set in November last year, which was about 500 hours of English. Since then, we’ve about doubled that. We also started to collect in multiple languages. We’re currently collecting in 15 languages, big ones and small ones. The big ones are English, French, German, Italian, Turkish, and, of course, traditional Chinese Mandarin now.

### Michael Henretty:
We’re adding new ones all the time. The website, we currently have 50 more languages in progress. We’re continually trying to add to our collection of languages. That part of our effort is multiple languages, expanding the data set. Also, part of our effort for the next six months is making the site more fun to use.

### Michael Henretty:
We will add profiles to the this, so people can have identity, optionally. Of course, we will always accept anonymous donations. We want to expose a lot of metrics onto our site, so people can see how the project is progressing, so people can see how fast different languages are collecting and how quickly we can get to a viable speech technology data set.

### Desigan Chinniah:
Mike, I don’t know whether it will be useful. Has everyone yet seen the website or how it works?

### Audrey Tang:
I have donated more than 1,000 utterances.

### Desigan Chinniah:
You have.

> (laughter)

### Desigan Chinniah:
Sometimes I think it’s easier, if there’s a small opportunity, to get a laptop and show what the website is and what it does. It’s quite easy. Mike was talking about the project itself, but from a top level, if we look at voice recognition services -- Alexa, Siri, Cortana, any of those, Samsung with SV.

### Desigan Chinniah:
What we’re finding right now is the general design pattern for most of those voice recognition services are white, 35-year-old males from North America. That’s what those systems basically recognize. What all these big companies are missing out on is the fact that there are different languages in the world, different cultures in the world, different dialects in the world. We really would like to empower people.

### Desigan Chinniah:
We ourselves, at Mozilla, we don’t plan to build an Alexa. That is, it’s currrently not our focus to build such products. What we want to do is if we can find the data, we will allow other people to innovate on top of that, and potentially create niche competition for the likes of Amazon and Google.

### Desigan Chinniah:
That’s good for everyone, because once there’s innovation and competition, then we’ll see probably very cool things appearing in this voice space. Right now, we’re guided by what Amazon does or what Google does. I think that’s not great for the entire world. It’s great for North America or maybe Western Europe, but for the rest of world, not that.

### Michael Henretty:
Once we have the data, we also hope to provide software and tools for people to build speech technology with. Maybe that’s a good segue for Kelly to talk about Deep Speech.

### Kelly Davis:
We’re sort of the other end of things. One of the things we’re doing is called Deep Speech, which is our speech recognition engine. The idea is that we have implemented an algorithm, which is using some deep learning techniques, to actually create a speech recognition engine.

### Kelly Davis:
We have an algorithm out there that’s open source. What we’re doing, too, which is not done for most other engines, is we’re training models.

### Kelly Davis:
Again, we started in English, so we’re working right now on a model, which is open source under Mozilla public license, to do speech recognition in English. We’re going to do other languages, too. Actually, we just got an NSF grant, National Science foundation grant, to create speech recognition models for languages that are under-resourced. For example, Welsh would be one of them.

### Kelly Davis:
The interesting thing about that is that, while we’re building up corpora, data sets for other languages, the initial phase where we’re building out the data sets in other languages, these other languages will be under-resourced languages for a bit of time.

### Kelly Davis:
Using these techniques that we’re researching now, we should be able to create the early models for other languages outside of English. That’s basically what we’re doing. Basically, we’re breaking down the silos that exist for speech recognition right now, and then actually empowering communities to build and create speech recognition engines for whatever languages they see fit.

### Kelly Davis:
Our software is open, the models are open. They can choose to create a particular data set in whatever language they want to attack. They can use our software to create a speech recognition engine in those languages, sort of trying to break down the silos in terms of in speech recognition.

### Desigan Chinniah:
To put it in perspective, just a few weeks ago, they were talking to even what you would consider to be our competitors at Google, etc. Because all of this is out in the open, even Google Assistant or Alexa, theoretically can ingest this, and that’s super powerful. Anything we’re doing is helping anyone, using potentially any form of assistant. That’s my look on it.

### Michael Henretty:
One last kind of visionary piece, and then we’ll open it. I love to hear about what you’re working on, what some of your goals are. Maybe there’s some collaboration points. As Kelly and Dees mentioned, our goal is to open the speech and language type-wide for creators, hobbyists, universities, startups, as well as the big corporations.

### Michael Henretty:
Right now, if you look at speech technology, and if you think about the forefront of that, which is personal assistants like Siri, Alexa, Google Home, it’s only a handful of big corporations. It’s hard, because it’s only these corporations because it’s very hard to create speech technology.

### Michael Henretty:
You need, first of all, this data piece that we’re talking about. You also need the algorithmic machine learning scientists, people like Kelly. You also need very expensive compute resources. This prevents a lot of people from taking part in this technology. We hope to provide the software piece, so that people can innovate on top of the software. That’s our whole end goal with this project.

### Michael Henretty:
That’s why we’re doing, make it easy and free for anyone to create this speech technology. That’s our goal. That’s us. That’s what we’re working on. Common Voice is data. Deep Speech is the technology, software, platform. We’d love to hear more about what you’re working on and maybe what some of your goals are, if there’s questions.

### Michael Henretty:
We have some things that we’d also like to speak about, perhaps, but we’d love to hear from you.

### Desigan Chinniah:
We’re keen to get your take on this stuff. We have a number of pretty ambitious, lofty goals for what we’d like to do, but we also have a number of challenges. Later on, we can surface some of those challenges. Maybe there are ways, potentially, you and others can help on.

### Audrey Tang:
Welcome to the Social Innovation Lab.

> (laughter)

### Audrey Tang:
It is the first national social innovation lab. The lab is co-designed by hundreds of social entrepreneurs. We define here social entrepreneurs as people who have a business model, have a social mission, and it solves a sustainable development goal or a compatible goal.

### Audrey Tang:
I’m in charge of the national social innovation plan. The tagline of that line is &quot;Innovating not for the people, but with the people,&quot; meaning that people who participate in the innovation, when they see &quot;terms and conditions,&quot; they should be thought of as something that everyone has set, the agency of data, the agency of privacy, the agency of what they wish to be treated, in a social fashion.

### Audrey Tang:
Instead of having, as you said, one very biased or very non-representative, small number of elites dictating the terms and conditions for everybody in the digital economy, this idea of inclusion through social innovation is our national social innovation.

### Desigan Chinniah:
It reminds me of a very early Mozilla sticker, &quot;Internet for the people, by the people.&quot;

### Audrey Tang:
That’s right.

> (laughter)

### Audrey Tang:
If you combine it, it’s &quot;with the people.&quot;

### Audrey Tang:
At the moment, what we are looking at here is, next Parliament session, we will very probably pass a national act, the National Languages Act.

### Audrey Tang:
In addition to sign language, which I’m not sure whether you’re working on or not, mostly what it says exactly is that our values very much aligned. Any national languages here, including the Taiwanese Hoklo, the Taiwanese Hakka, all the indigenous language and everything, they’re to be treated equally.

### Audrey Tang:
Previously, as part of the Indigenous Act, we already have the law that says, in any precinct that has over half population speaking one indigenous language, then the official language should be that language. Any public servant who performs service there need to learn the language, and official document can be written in that language.

### Audrey Tang:
Any child, anywhere in Taiwan, who wish to learn this language must have sufficient resource to learn that language. With the new act, this will expand to more than 20 languages, which creates a huge logistic challenge.

### Audrey Tang:
Here in the Social Innovation Lab, we’re taking baby steps using non-AI technologies like telepresence...

> (laughter)

### Audrey Tang:
...to make sure that there’s sufficient indigenous teachers here, and any children who select such language circles, they can participate through ubiquitous broadband. Here, broadband is a human right, so they all have broadband and connect to this virtual classroom, where they can learn those languages.

### Audrey Tang:
The fact is that it’s only a few hours every week, and that’s the most we can do right now. There’s a huge potential, if you have this kind of technology, to have students essentially work with technologies. Actually, they do already work with Duolingo. Duolingo does not have indigenous languages, nor does it have Taiwanese Hoklo or Hakka.

### Audrey Tang:
It’s one of the pinnacles of identification, because it’s really a lot of fun. \[laughs\] My vision is that if there’s something like that for language acquisition between the Taiwanese national languages, which explicitly the act tasks us to build national language databases that enable this kind of language transfer and learning between cultures.

### Audrey Tang:
All this is very new, like two years ago. Now this is...

### Desigan Chinniah:
Historically, these data, even some form of this database in digital format, has not existed?

### Audrey Tang:
Historically, there is lexicons, and that’s it. The lexicons are also often -- I’m trying to use a political neutral term -- very academic-driven, so that it doesn’t actually reflect the new coined words, euphemisms, and Internet slang that people actually use. It documents a language that’s alive maybe 50 years ago.

### Audrey Tang:
There’s a lot of projects from the civil society, like the g0v Moedict project, which crowdsources Taiwan Hoklo languages, called iTaigi. It’s an urban dictionary-like format, iTaigi.tw, that crowdsources new sentences, new utterances in a way very much like what you’re doing here in Common Voice.

### Audrey Tang:
That’s just Taiwanese Hoklo, and it’s more about dictionary, mostly about lexicon. We don’t have anything that is speeched for the Taiwanese Hakka and indigenous languages. On the other hand, the Minister of Science and Technology recently has been building thousands of hours of Mandarin corpus and a little bit of Taiwanese Hoklo.

### Audrey Tang:
Part of this act also tasks our public television system and the Minister of Culture to start building, as part of their broad custom programming -- also hopefully openly licensed \[laughs\] -- databases for everybody to use.

### Audrey Tang:
We’re now looking at a landscape where we will continuously have new corpora, continuously have new content, and a strong demand in the education sector to have ubiquitous access to all those different languages.

> (laughter)

### Zsehong Tsai:
Let me explain a little bit about the government effort in the general aspect. First, at the AI level, we do have a mission-level initiative called AI Taiwan. The whole initiative was designed and started to transform our existing industry.

### Zsehong Tsai:
Hopefully, with the help of AI technology, which inform different industrial sectors, including manufacture, retail, finance, etc., or different aspect in our industry, in our economy. We promote this AI program. Currently, the government expends efforts in majorly two aspects. One is to sponsor R&amp;D programs in the university, a lot, under the Ministry of Science and Technology.

### Zsehong Tsai:
They already established four major AI research centers in four university clusters. They encourage the university to form a cluster of R&amp;D in different AI areas. Some of the AI research team, in the past, actually have already dedicate a lot of effort to speech recognition, chatbot, etc.

### Zsehong Tsai:
Within the AI Taiwan program, there are already research team dedicate to the use of AI, deep machine learning, or other techniques to improve any chatbot-like applications. Some of them are working on some fundamental issues. That’s one effort.

### Zsehong Tsai:
The other one is to encourage new startup to working in the whole AI area. We do have AI kind of program and we do provide training, AI schools for newcomers, including new start or those who are interested in bringing their own common knowledge to this area. For example, Academia Sinica, there is an AI school.

### Audrey Tang:
That’s right, the AI Academy.

### Zsehong Tsai:
AI Academy.

### Audrey Tang:
If you Google for &quot;AI Taiwan&quot;, the first hit is our national plan. The second one would be the AI Academy.

### Michael Henretty:
OK.

### Audrey Tang:
\[laughs\] That’s very convenient.

### Zsehong Tsai:
Those who participate in the AI Academy, they enjoy assistance that would give them the basic training on AI, deep learning. Then they would take it themself into some hands-on project. Even here in those kind of project, data set were already allocated there. In turn, on the university side, our ministry of science and technology initiate the Grand Challenge on AI every year...

### Audrey Tang:
That’s right, a different topic every year.

### Zsehong Tsai:
...on different topics. Chatbot is one of the Grand Challenge topic.

### Michael Henretty:
Which one is it?

### Audrey Tang:
The first one — semantic understanding and speech recognition.

### Zsehong Tsai:
All the university R&amp;D team of some graduate students. Many of them prepared to participate this Grand Challenge, and hopefully something good will come out of this challenge.

### Michael Henretty:
When is the challenge?

### Zsehong Tsai:
Usually held near the end of the year.

### Michael Henretty:
As for output from some of these challenges, is commercial output viable? Can you build something that could make you money, to be a commercial entity?

> (laughter)

### Michael Henretty:
Or is it all social good?

### Zsehong Tsai:
The IPR is a separate issue. Any know-how or any new specialization models, already built or built during this process, actually the use of such technology is on the hand of this R&amp;D team.

### Michael Henretty:
Oh, they own the IP.

### Zsehong Tsai:
Government give the research grant, but the university owns most of the rights, IPR. It’s co-owned by the research team and the university. Some of them, I think they will be willing to dedicate their resource for social benefit. Some of them may wish to have a new startup. It’s OK.

### Zsehong Tsai:
The government will also encourage a new startup to attract more investors, to have more industrial collaboration, etc. Currently chatbot has been used in many different sectors. Sometimes our government service is also included in one of the area. Some of our local government, for example Taoyuan City, they have a chatbot to serve their citizens. They already started such service.

### Zsehong Tsai:
We already see the Taipei City government is also exploring this possibility. We call it the 1999 system. It’s a telephone line that will answer all the question from the citizens. Within the database, they’re already making use of AI.

### Zsehong Tsai:
Once they capture some key words, they quickly get maybe a canned response. \[laughs\]

### Zsehong Tsai:
That’s already in progress. We definitely may use some technical people who know AI. So far, the government has done and has started, but there are many new areas.

### Zsehong Tsai:
I should talk about the third part. The third part is that, during this process, the government also provide incentive for major IT company to come to Taiwan to establish their AI research center. Two major ones, Google and Microsoft, came. They both make already announce in public that they will make a lot of efforts here.

### Zsehong Tsai:
Some of the topics they are working on now are speech related. Google, in Taiwan, they said in public they will make a lot of effort in hardware, software related to integrative R&amp;D. For pure software, I don’t think they need Taiwan. In their headquarters, they have good brains, there are Google brains there.

### Zsehong Tsai:
But when speech-related R&amp;D, when it is hardware-related, they find out that Taiwan’s an excellent environment. We provide some hardware component, and sometimes they will look to try different combination of hardware and software. They said in public that that’s the direction they wish to achieve in Taiwan. On the Microsoft side, I think...

### Audrey Tang:
They set up a AI center here, like 100 and up to 200 AI engineers...

### Michael Henretty:
Wow.

### Audrey Tang:
...which makes it one of the largest AI-focused R&amp;D centers here. After their internal reorganization, I think there’s a single unit now with perception and things like that. They’re also expanding to what they call multi-modal, sensor fusion, or whatever thing that is used to describe this idea of edge plus cloud fusion of machine intelligence. It’s very vague, but you know what I’m talking about.

> (laughter)

### Zsehong Tsai:
We find out, when we talk about the data set for AI-related application, speech-related AI applications, they all need a good data set. That’s the common demand in all these different R&amp;D community.

### Michael Henretty:
It’s nice to hear.

### Audrey Tang:
The Grand Challenge, I think the Ministry of Science and Technology provides some 4,000 hours of Mandarin Taiwan data set. The initial phase is on Kaggle, which is through the end of this year. At the end of this year, they will select 30 teams.

### Audrey Tang:
Those 30 teams will enroll in a two-month competition, to February, that tests not only recognition and synthesis, but also semantic understanding and much more complex tasks. It’s conceivable that no team will end up meeting. That’s what Grand Challenge means.

### Audrey Tang:
If at February next year some of them manage to hit goal, then it’s one million US dollars or something prize, which is OK for this kind of thing.

### Michael Henretty:
What kind of goals are they setting?

### Audrey Tang:
They basically have a contextual, normal conversation, Turing test-ish \[laughs\] environment set up, not unlike how Google books reservations.

### Michael Henretty:
Like that or not like that?

### Audrey Tang:
Not unlike that, so a little bit similar to that.

### Michael Henretty:
So NLP stuff...

### Michael Henretty:
...speech.

### Audrey Tang:
Just the recognition part will tailor to the local version of Mandarin, which is why they need to seed the teams with thousands of hours of local corpora. Many of the teams, they’re using existing speech sets, and it’s not really representative of the local way that people speak Mandarin.

### Michael Henretty:
That’s awesome. Can you tell us more about this data set, like how it was collected and curated? What’s the licensing? Do you know much about the 4,000 to 5,000?

### Audrey Tang:
The MOST data set?

### Zsehong Tsai:
Currently, this data set actually is a joint effort by two ministries, the Ministry of Culture and Ministry of Science and Technology. Many of the original voice were recorded in public broadcast group...

### Audrey Tang:
That’s right.

### Michael Henretty:
Are they...?

### Zsehong Tsai:
By public television, public radio stations, from the source, to make sure the voice is authentic. \[laughs\]

### Michael Henretty:
...conversational, I guess.

### Zsehong Tsai:
The carefully select the anchor’s name.

### Zsehong Tsai:
Then the additional tagging and other effort also, to make everything machine readable, such effort is done by the Ministry of Science and Technology. Because this Grand Challenge is planned to be held every year, we can believe that next year, one year later, they will prepare additional data set, so that the Grand Challenge will not be the same every year. \[laughs\]

### Zsehong Tsai:
They can add something new. I think, in this process, we can talk to Ministry of Culture, as well as Ministry of Science and Technology, to understand their direction. Sometimes, we can provide them with some additional guidance about what kind of additional language data set which should be added.

### Desigan Chinniah:
Am I right to assuming that the original data set is only read by one-thousand group of people?

### Audrey Tang:
It’s a lot of people.

### Desigan Chinniah:
What I mean is just say, for example, we ingest it within Common Voice, we can get it read by many thousands, of not tens of thousands, hundreds of thousands more people. That would be interesting, because it would give different accents.

### Audrey Tang:
Certainly. That’s one of the goals of the Grand Challenge. It’s not saying that the people who participate in the Grand Challenge must be exclusively using the MOST data set. It’s the other way around. They’re encouraged to make the most of the MOST data set. Pardon the pun.

> (laughter)

### Audrey Tang:
That’s the idea. About license, I think at the moment it is provided to all the contestants who enter the Grand Challenge. There, I believe, is no commercial use restriction for any of the teams participating in the Grand Challenge, but you do have to participate in the Grand Challenge to have the access.

### Desigan Chinniah:
We’re going to get the list of the Taiwan communities that participate in the Grand Challenge?

### Audrey Tang:
That’s certainly one of the...

> (laughter)

### Audrey Tang:
The point is that it’s an ongoing process. The Ministry of Culture will collect more data sets as time goes by. What we’re trying to do here, it’s not a one-shot thing. Once people are used to ingest corpora in this format, they will just continuously get much more public broadcasting materials in the future.

### Kelly Davis:
This sounds like a valuable data set. Aren’t there larger data sets with complete information about, say, conversations? For example, we may have just the audio data set transcriptions from people presenting on TV. Is there a larger data set that may be purely text, containing only conversations?

### Audrey Tang:
Well, all my meetings are transcribed and published.

### Irvin Chen:
One question is that I need to make sure that it’s public domain, and...

### Audrey Tang:
My speeches are all in public domain.

### Irvin Chen:
...and you don’t have a specific...

### Audrey Tang:
It is in public domain.

### Irvin Chen:
Like Kelly mentioned, the transcription of your talk and all of your meetings.

### Audrey Tang:
All my speech in meetings are published on GitHub in the archive.tw.

### Irvin Chen:
Although we started, the other people’s speech meetings, also, the speech are also in public domains?

### Audrey Tang:
The idea here is that I have a visitation protocol.

### Audrey Tang:
According to our new copyright law, none of those government proceedings can hold copyright, anyway, which is why the repository, I put a Creative Commons Zero, universal declaration on it.

### Audrey Tang:
To be precise, it should be public domain. It shouldn’t be CC0. I put CC0 there just because, in some jurisdictions where the idea of public domain is in question, they can fall back to this CC0 license, which turn out to be the same thing.

### Irvin Chen:
Both the data sets for governments, I spoke to the law professors, they studied the standard the data sets. The data set for our Grand Challenge data set is under the Non-commercial and Research only. That’s the main problem, that we cannot get access.

### Audrey Tang:
That’s right.

### Irvin Chen:
Another problem is that it’s transfusion of the public TV and the broadcasting. The content of the service now, is that under the free license? We have to confirm that before we can use the data set.

### Audrey Tang:
I do agree.

### Michael Henretty:
I would imagine this data set of four to five thousand hours of traditional Chinese Mandarin is not a public domain, licensable data set.

### Audrey Tang:
We can talk about it.

### Michael Henretty:
We’d love to talk about that.

> (laughter)

### Michael Henretty:
It sounds like a hugely valuable data set to at least bootstrap research projects or start up projects. From that, you can continue to build upon that data set. We’d love to use something like that as a base, but it’s not necessary.

### Michael Henretty:
One thing I would love to hear a little bit more about are these databases that you will set up through the Indigenous Languages Act. Can you give us some information about what those databases look like? It seems like we could collaborate on that.

### Audrey Tang:
Sure.

> (laughter)

### Audrey Tang:
It is up for the Ministry of Culture, as part of the description here, to announce, periodically, the &quot;Development Report of National Languages.&quot; The primary goal of that report is to revitalize, to inherit, and to record the existing languages, and especially the languages that are in danger of disappearing.

### Audrey Tang:
The act does not say explicitly about the data format or about the modality of the media. The act almost never says that. It’s up for the regulations level thing to do that. One of the early discussions when this was in a public consultation was whether we focus on a few languages and make them really on par to each other.

### Audrey Tang:
Or, do we just open the pipeline of building such language databases and for the civil society and the academia of each language community to determine how best to do it? Basically, centralized versus federated or partnership deal. So far, the minister of culture have signaled that, at least for Taiwanese Hoklo, Hakka, and Mandarin, they’re going to be one, if not the, primary source for these three languages.

### Michael Henretty:
Centralized database.

### Audrey Tang:
At least, as you said, to bootstrap the process and demonstrate the pipeline. I have not yet talked to our new administration’s spokesperson. The spokesperson, Kolas Yotaka, is indigenous in the Amis nation. She has always advocated a orthography that’s based on Latin scripts, multi-ethnicity, and things like that for indigenous languages.

### Audrey Tang:
I think that is a political question that we will very quickly see whether we would also like to signify our commitment to bootstrapping the indigenous language movement by providing such databases under the auspices of the Ministry of Culture or not. This "Council of Aboriginal Affairs" is a misnomer. \[laughs\] It’s "Council of Indigenous Peoples" now.

### Audrey Tang:
The idea is that they already have a lot of efforts, but mostly, as I said, on the lexicon level. At the moment, as far as I know, they have the radio station and television station for the indigenous languages, but so far it is not yet merged with the MOST pipeline.

### Zsehong Tsai:
For your information, in our public broadcast system, we do have a Hakka channel. We have indigenous channel...

### Michael Henretty:
Excellent.

### Zsehong Tsai:
... \[laughs\] in addition to Mandarin channels.

### Audrey Tang:
After this act, we’ll also have a Taiwanese Hoklo channel.

### Michael Henretty:
I have some ideas on stuff we’d love to collaborate. Before I go into that, are there any other questions off the top of your head? If it comes up, we can talk more. There are a couple things that we would love to collaborate with you, something we can talk about.

### Michael Henretty:
First of all, the way we see Common Voice and Deep Speech, we don’t see this as a tool for Mozilla to go out and collect language data. We see this as a tool to allow communities to build up this data set for themselves, and then use this data set how they see fit. That said, we stipulate public domain for all of our materials, because we believe this will have the most impact on the world.

### Michael Henretty:
CC0 or just public domain is what we publish. We would love to help with the recording and preservation of languages. Of course, this is a big goal of ours. It’s not just cultural preservation through technology, but also speech technology. We think people should be able to speak to the Internet in their own language, what language they want to. Technology should empower them rather than restrict.

### Michael Henretty:
We would love to talk to you about these databases and how we can work together to create the databases. We already have quite significant infrastructure for doing such things. We could talk about mirroring or how we could work together from a technical perspective. That would be easy for us to work out. That’s probably our core competency is Internet technology and Internet infrastructure.

### Michael Henretty:
This is something we would love to work with you on. This data set, that four to five hours of traditional Chinese with Mandarin, is a very valuable data set. We can do a number of things to help with this. One thing that Common Voice does is, as Des says, we expose to hundreds of thousands of people. Not so many traditional Chinese Mandarin speakers, but we are growing.

### Michael Henretty:
In fact, over the last few weeks, because there was news here about Common Voice, we’ve had a lot of Taiwanese users. If we could take some of the text from this and have people read it, if you want, we can also validate some of the transcription. As part of this process of creating this corpus that you’re talking about, you need to, first of all, have it transcribed, which it might have for closed captioning.

### Michael Henretty:
Then you need to do what’s called alignment, which is chunking it up into sentences and have those sentences transcribed, like breaking this down into small pieces. We can help with the verification of that if that was something you would like. We can get this in front of people, so they can listen and say yes, no, this is what we want. We can help curate the data set.

### Michael Henretty:
That’s another thing that we would love to help with. Of course, we would love to link to your data set, in general, and just say, &quot;Hey, here’s a great Mandarin, traditional Chinese corpus that you can use.&quot; Those are two things. The third thing is, in general, we are always looking for texts in any language, traditional Chinese would be one.

### Michael Henretty:
These Latin-based indigenous languages would be great, as well to get people reading and creating data sets on Common Voice itself. If you are open to creating these databases for these indigenous languages with an open license and public license, we could help you get that spoken and create a vocal corpora for those texts, if that’s something that you’re interested in.

### Desigan Chinniah:
Or the slightly other way around, which is when you talk about young school children today that, as part of it, they had the opportunity to learn...

### Audrey Tang:
There’s probably still some of them right here... \[laughs\]

### Desigan Chinniah:
I saw a group of children when I came in.

### Joe Cheng:
Maybe somebody get a few hours a week. I’m making this up, because it’s the first I’ve heard about it. Maybe for 20 minutes a week or something, if they chose a language, we can present them with this text, where they read it out. Maybe that’s helpful to them in their learning. I don’t know.

### Joe Cheng:
We’ve been talking to the British Council recently. For them, they want to see something that’s useful to their students. They would be happy for their students, in say India or China, to read back sentences. The reading back of sentences they say is just one piece. For a student to actually find it useful, they need to understand how well they’ve read the sentence.

### Joe Cheng:
There needs to be a feedback mechanism that says, &quot;Thank you very much, Audrey. You’ve read 10 sentences today,&quot; or, &quot;a hundred sentences. But you got 70 of them correct based on feedback from our community. Here are the 30 that you may need to reread to improve.&quot; That would be seen as something that’s useful for learning.

### Joe Cheng:
If it’s just, &quot;Read these 100 sentences,&quot; and there’s no feedback, then it’s maybe not useful...

### Audrey Tang:
Duolingo did that for translation, and it’s very, very useful. They also sell the translation service...

> (laughter)

### Audrey Tang:
I’m very happy to talk to social enterprises. \[laughs\] It’s much easier.

### Audrey Tang:
That’s mirroring and linking of data sets. Validation and rereading, really, crowdsourcing of the expansion of the MOST data set. Also, the integration with indigenous communities, as long as they agree to a open license. Those are three main topics.

### Michael Henretty:
As Dees said, longer term, we would love to explore maybe tools for helping teach languages. Part of our work in the next year is gamification of our websites. If there’s a use case around accent training, spoken language training, or learning to understand spoken language, we would certainly work with you on product. That’s longer-term stuff.

### Michael Henretty:
The things that I mentioned, those are immediate. We could start working on this today, basically. But as our relationship develops, if we decide that our visions are aligned and our goals are aligned, we would love to talk about how we could evolve Common Voice and Deep Speech, the tool set to meet the needs of the community.

### Michael Henretty:
We would consider Taiwan and its various languages part of the community. That’s how we see it. As Dees said, those are longer-term things that we would love to continue to talk about. Shorter term, lets help each other build this data set if we can all agree on public domain and open license.

### Desigan Chinniah:
One thing, and it is something to possibly table, considering we have communication people in the room. It would be good to understand, just from a higher level, when the ministry, for example, works with commercial partners or even social enterprises or not-for-profits, how do you typically communicate?

### Desigan Chinniah:
Are there protocols to press, PR, communications? Obviously, we’re not aware of how you work, for instance...

### Audrey Tang:
Sure.

### Desigan Chinniah:
That thing Alex said would be interesting. They’d need to understand those sorts of things.

### Desigan Chinniah:
...getting exposure helps these projects grow. Mozilla and the Taiwanese ministry is a strong combination, but are there rules, guidelines, principles that you follow when working with commercial entities?

### Zsehong Tsai:
Something I can talk about is the direction about using tool from your site, then make it to be used to help our student in their language learning, whether this is indigenous or on some special languages.

### Zsehong Tsai:
There are technology programs under the Ministry of Education. It’s very specialist. When we would talk about the language therapist data set, it’s a joint effort between the Minister of Science and Technology and Minister of Culture.

### Zsehong Tsai:
When we talk about designing a new language learning tool or providing a new approach in language training, usually such project is under the Ministry of Education. We do sponsor several projects, use our science budget, every year to help the Minister of Education to build on these efforts. Certainly, the work a lot on different things. Sometimes they work on AI. Sometimes they work on 5G.

> (laughter)

### Zsehong Tsai:
Many new stuff. I think this is definitely one possibility. We can talk to our counterpart in Ministry of Education in understanding how the use of such tool can be integrated in their budget.

### Zsehong Tsai:
Other way, there are different educators or teachers in these communities. Some of them are specialized in different language or the native languages trainings. Some of them are in linguistics. When we talk about new technology, IT-enabled language training, we may need some other IT background faculty members to jointly work with traditional language-related faculties.

### Zsehong Tsai:
This is not the first time we formed such a participant team under the science project. We can talk to the Ministry of Education to work on this. That’s one possibility.

### Michael Henretty:
Sounds great.

### Audrey Tang:
Yeah, that’s great. That is specifically the nice clause in the Language Act. The Language Act, and I’ll quote very quickly. Basically, in the K-12 education, kindergarten to basic education, all different curriculum assets need to be made available in all national languages.

### Audrey Tang:
If the school choose to teach, say, mathematics or physics, using Taiwan Hoklo or Hakka or indeed any of the indigenous languages, they are allowed to do it. Then, the Ministry of Education towards this goal, should reward various academic faculties providing research and development support to enable such kind of immersive programs. That’s what the law requires.

### Audrey Tang:
Frankly speaking, nobody knows how to do all of it yet.

> (laughter)

### Michael Henretty:
How many languages is...?

### Audrey Tang:
I think 25 or something.

### Michael Henretty:
A big effort.

### Desigan Chinniah:
But it’s the expectation when one is available, 24 others are available? Or can it be progressive?

### Audrey Tang:
This is a political question.

### Audrey Tang:
Let me just say that for all the efforts that we’re making, we’ll be working closely with various language communities. It will be contingent on the strength and the solidarity within a language community on how quick this pipeline will proceed.

### Audrey Tang:
We will ensure that all the pipeline developments in the various language communities is non-exclusive so that any language community can have access to the how-to of building such language pipelines so that if they have the effort and the same amount of energy, they will not be discriminated.

### Audrey Tang:
Sorry for being very political. \[laughs\]

### Desigan Chinniah:
We say the same thing about Common Voice, where we provide the initial technology and the alacrity with which the languages develop.

### Audrey Tang:
Right, and just without my language engineering hat, there’s a lot of expectations for resources, languages citing recent papers about transferred learning and about other developments. In Hakka, we have six different tonal variations of Hakka language.

### Audrey Tang:
There’s a lot of people saying, &quot;You can just algorithmically transfer between those tonalities.&quot; The same goes maybe for the regional accents of Taiwanese Hoklo. Many indigenous languages, they also have a heritage continuation relationship, like between Amis and Sakizaya, for example.

### Audrey Tang:
People always, after reading some papers, say that there’s no technical reason why you can’t do this equally, but it is not that simple as that.

### Michael Henretty:
It’s a research project, right, like the distance between...

### Audrey Tang:
The thing is that, if you put it into premature use, just like in one of the international forums, I think it’s Boao Forum, they used speech recognition and automated translation. Whenever someone switch between the Chinese Mandarin and English, then it start to repeat itself like, &quot;For, for, for, for what, what, what, what.&quot;

### Audrey Tang:
It shows the limits of the existing way. If you cross a certain boundary of similarity between the different language semantic clusters, then the machine gets very confused, and so transfer of learning had not been an easy answer. \[laughs\]

### Kelly Davis:
That’s one of the things that we’re going to experiment with, is using transfer learning to indeed transfer some knowledge, say from American English accent to a Australian English accent. We’ve also been trying to, for languages that are not so closely related, see how far we can go. But I agree, it’s more research as opposed just turn a switch on and it works.

### Audrey Tang:
People would have to understand that this is risky, experimental, and often wrong. Accepting those preconditions, they may of course use this technology, but it is not the ground on which to demand equal treatment at day one. Maybe 10 years from now, but it is not today.

### Kelly Davis:
I think one of the big things that’s actually going to mitigate that, too, is to get the expectations right.

### Audrey Tang:
A lot of our work is just expectation management. \[laughs\]

### Kelly Davis:
Us, too.

### Michael Henretty:
In fact, the tools that we’re building that’s exactly, as you said, and Kelly called this out. We see it as a pipeline with documentation for these communities to build it up based on how quickly they want to move. I see a lot of overlap there. What I’d love to talk with you about now is licensing.

### Michael Henretty:
We feel very strongly about public domain for data and we think that data in pure public domain has the potential to have the most impact.

### Audrey Tang:
What’s your case against attribution?

### Michael Henretty:
This is a continual discussion, so there aren’t any right answers that we have hard and fast decided on yet. Our experience of attribution so far with creating Common Voice data set is that attribution, at its core, creates this sort of license baggage.

### Michael Henretty:
I can explain a little bit about what that means. Let me give you an example. Common Voice is a remix of many other data sets because we have to have people speaking sentences. A lot of times, those come from other data sets. There’s one data set in particular that we really want and still working on it. It’s called Stanford Natural Language Course.

### Michael Henretty:
This is a couple hundred thousand sentences. This is, in itself, a mix of some other data sets. We went to the person who is curating the data sets, Sam Brown. He’s at NYU now. We said, &quot;Can we use your data set in Common Voice? The license doesn’t work with us because we promised our users CC0. Is this CC4, I think?&quot;

### Audrey Tang:
Attribution 4.0.

### Michael Henretty:
Attribution 4.0. Also, Share-Alike. He said, &quot;I’d be open to publishing CC0, but we’re based on these other data sets, specifically this one called Flickr 30k. This is an attribution as well. If they were to open-source it, we can open source for ours.&quot;

### Michael Henretty:
For instance, we could change Common Voice to support various forms of attribution, but then we have this very complex structure of attribution that we have to follow. Anybody who remixes our data set has to also trace those sources of data and include that in their license.

### Michael Henretty:
This is hard to do and it prevents what we think is innovation or prevents people from remixing it easily because they have to try to understand this license, how these different licenses apply to different parts of the data set and preserve that dependency.

### Michael Henretty:
We instead tried to get them to go for CC0. First, we had to talk to Sam, and then we had to talk to the owner of his derivative data sets. There was this woman in University of Illinois who had this other data set. We had to try to convince her. It was this process that is continually going. We’re talking for a year to try to get them to open it up.

### Michael Henretty:
It’s hard to, first of all, remix the data set and adhere to the license. It makes it prohibitively expensive, let’s say, in people time. Second of all, to try to get people to the public domain, you have to be able to get in front of people. Luckily, we have Dees who can reach out to Sam, who can reach out to Julia, who can reach out to people.

### Michael Henretty:
If I was a university student and I wanted to make a technology that is commercial, let’s say, then I’m basically stuck or it’d be very hard for me understand the technology I’m creating actually adheres to these licenses. Because this license, when you’re talking about remixing data, it comes in this baggage. It’s like a infinitely variable tree that you have to try to adhere to.

### Michael Henretty:
We think CC0 or public domain is this way of solving it by making it easy. Just have it be open and use it however you want. We think that this attribution piece, we’ve done some research as to why people choose attribution, at least in university.

### Michael Henretty:
It seems like people choose attribution because they want to, first of all, they want to be recognized for this hard work that they did. They want to be able to incite it when their work is used, and they want to be able to get grant money when their work is used. What we found with Common Voice...

### Audrey Tang:
That’s right. It’s a proof-of-stake. \[laughs\]

### Michael Henretty:
Exactly, proof of stake, right? What we found with Common Voice is that at least...Maybe there’s stuff we don’t know about, but in general, we know about two papers that were written with Common Voice data. They will all always print this anyway because they want their paper to be reproducible.

### Michael Henretty:
If their paper’s reproducible, they have to quote to their source, so we can get attribution from the academic realm. For reading speech technology in the commercial realm, we don’t necessarily need the attribution, right, because what if these products are very privacy-centric products?

### Michael Henretty:
It could prevent somebody from making a doctor personal voice assistant from using our data and make it a good thing because they would have to adhere to our license, which is a public, which may be like attribute Mozilla and maybe that doesn’t meet their business standards for some legal reasons.

### Michael Henretty:
We see CC0 as a way of, we still get a attribution. We still have ways of measuring our impact in the academia world, but it’s also way of having the non-academia world, the commercial world have the most impact there. That’s what we care about.

### Michael Henretty:
We think that CC0 can actually unlock a lot of potential for data sets. We think that you can still get the things you want from the attribution maybe without having the actual attribution license because this reproducibility. This is our theory. This is what we’re going off of.

### Michael Henretty:
We are continually talking about this with partners. At some point, we may change and say we want to support attribution at some point. For now, it was a great starting point to say let’s open this data pure public and let’s see if we can measure the impact, first of all, and let’s try to understand if this is having a higher impact because it’s public.

### Audrey Tang:
Thank you. Yeah, I can make the same argument because even my source code and all my contributions on GitHub are CC0 anyway. I use it as soon as it came up. I used to use the SQLite &quot;do no evil with it&quot; non-license that doesn’t quite work, so I’m very grateful that there’s CC0.

### Audrey Tang:
Truth to be told, it creates a challenge for us. Speaking of official capacity, Irvin was asking about the text of my conversation and also in my PDIS forum, there’s a lot of people posting public questions and answers. Theoretically, everything that I said or wrote, or my public servant colleagues said or wrote, they should be in the public domain anyway.

### Audrey Tang:
We shouldn’t even put a CC0 on it. On the other hand, my visitors, when they came to the website, they essentially agreed to a creative common attribution license because that’s the default license we put to our discourse forum. That creates a kind of double standard, right?

### Audrey Tang:
For a public servant, it’s public domain and for private sector contributors, they can always fill that endpoint to our governor open data license, which is CC Attribution 4.0. There’s a fallback for the private sector people.

### Audrey Tang:
They can always say, &quot;I wanted attribution. Even though I didn’t say it explicitly, it should be understood because the Taiwan standard government open data license is CC BY 4.0 and our discourse forum is CC BY 4.0.&quot;

### Audrey Tang:
They could always go back and say, &quot;You know, although I did not say that I want attribution,&quot; again you don’t have a regulation or law that says, &quot;I relinquish my attribution rights just by talking to you, Minister.&quot; \[laughs\] It creates a challenge for us if everything needs to be in CC0. Also, it creates a problem for the Ministry of Culture and the minister of science and technology.

### Audrey Tang:
We have a national regulation that says all the ICT systems that’s built and maintained for the last past three years under around US$1 million must have all its output to be published as open data, using Creative Commons for attribution. That is a very strong regulation, and this is how Taiwan get to the number one on the OKFN Open Data Index.

### Audrey Tang:
There’s no legal basis for us to say that the government-procured data sets using taxpayer money that isn’t using the open government data license should be even more lax rather than even more strict. We can always argue for even more strict. Like, &quot;This is dictionary data. Obviously, it’s non-derivative.&quot; You can’t change the stroke numbers or whatever. It’s a easy argument to make.

### Audrey Tang:
It’s a very hard argument for us to make, saying, &quot;We’re not using attribution anymore.&quot; That is politically very difficult for us. Operationally, you mentioned the burden of having to basically, like at the end of the movie, have a wall of short URLs. That preventing commercial uses, I can sympathize with that. When I worked with Apple, there’s an entire department doing that. \[laughs\]

### Michael Henretty:
If you’re the size of Apple, it’s not so hard, because you can have a whole...

### Audrey Tang:
It’s very streamlined at Apple.

### Michael Henretty:
Our hypothesis is most people don’t have a legal support for these sorts of things.

### Audrey Tang:
I do agree.

### Michael Henretty:
It’s something we can continue to talk about. We would love to. It sounds like we’re values-aligned, at least, on how to do these. There are ways to work together, even if we don’t agree on the license.

### Audrey Tang:
Sure.

### Michael Henretty:
For instance, there can be special ribbons around mirroring that data, which we have worked on in the past. I would say this is a conversation that we can continue to have and figure out if there are ways that we can satisfy both the direction that we are taking...

### Audrey Tang:
Because this is on public record, it is also conversation with all the stakeholder.

> (laughter)

### Michael Henretty:
We will use this. People will be speaking non-words and common words maybe.

> (laughter)

### Audrey Tang:
That’s right. We have everybody’s exclusive consent that this is Creative Commons Zero, right, \[laughs\] not attribution?

### Michael Henretty:
Yes, please. If I could wear a pin that said that.

### Audrey Tang:
\[laughs\] Yeah, we should make a CC0 pin that just has a zero in it.

### Michael Henretty:
Yes, we’re all CC0.

### Audrey Tang:
We can re-purpose the g0v pin. \[laughs\]

### Audrey Tang:
That settles the mirroring and data set part. As of opening the text to read, that may be easier, actually.

### Michael Henretty:
Great.

### Audrey Tang:
Maybe we can talk to the MOST people, not at first about the speech wave data, just the captions. I think it’s part of the public broadcast. It should be much easier if they just published the text part. We’re within the period of Grand Challenges, so any change to the underlying corpus or whatever it is actually is kind of difficult.

### Audrey Tang:
The earliest point to re-license the thousands of hours is either through a special memorandum, or just wait until the end of the year. I think we can talk ahead of time about captioning, opening the caption to text. Maybe we can talk about it with MOST. Anything else that I missed?

### Zsehong Tsai:
On the education community, our Ministry of Education has strategically done is to allow the flexibility to those teacher or professors view the course material, including all the related side products. Certainly, the Ministry of Education has some basic rule. They have to make some of their developed courses on a shared basis, shared with the...

### Audrey Tang:
Also, Creative Commons.

### Zsehong Tsai:
Yes. It is kind of Creative Common, but within Taiwan’s education community, so that the course material built by one university or high school can be shared by some teachers in another high school.

### Zsehong Tsai:
When we talk about any language training-related courses or some materials, basically the rule is the same, some minimal requirements set by the Ministry of Education that also allow the teacher to voluntarily open up into to the extreme basis, maybe CC0.

### Audrey Tang:
I think it’s CC BY. It’s CC attribution. There is a grant index, what they call Education Market in the Ministry of Education that you can look up. It’s mostly teachers and publishing their course materials.

### Audrey Tang:
Nowadays, some people also have their own YouTube channel and become, essentially, YouTuber teachers. \[laughs\] Again, YouTube allows them only to select between the standard license and Creative Common attribution. It doesn’t get more free \[laughs\] than the Education Market.

### Michael Henretty:
Yes, of course.

### Zsehong Tsai:
That’s another possibility. Another interesting part is that, in the past, in this community, they welcome all kind of open source materials. It’s already encouraged by our minister of education in the past, for many years. Even teachers in any corners in Taiwan can easily access some education tool on their demand.

### Zsehong Tsai:
Therefore, maybe you need the whole community and all the correspondent ones here in Taiwan to help to do this, to spread out the information data you have. You’re not only helping this Taiwan education community, you’re also linking the effort to the external community working on similar projects.

### Zsehong Tsai:
That will convince more and more of them to make use of your tool and hopefully also producing some data that’s useful.

### Michael Henretty:
We’d love to make ourselves available to that if you were to help set up the connections. We can provide an application. If there’s even changes to the product itself that would help support the education effort, we would love to talk about those things.

### Audrey Tang:
That’s great. I think that leaves only the communication critical.

### Desigan Chinniah:
Just one thing on the education piece. I know we talked about indigenous languages and local languages. If I flipped it slightly around, what about actually people learning, improving their English. Is there any efforts in that regard?

### Audrey Tang:
Oh, yes. The minister of education is now working on a revised plan of making English primary education systems, on the order of our new premier, William Lai, who has always advocated that the students who want a English primary education should get a English primary education.

### Desigan Chinniah:
That’s obviously something that we already are pretty strong at. I’m not trying to win the round, but just throwing it into the mixture.

### Audrey Tang:
Very much so. On the other hand, there’s huge amount of startups also here, some open source, some social enterprises, and also some pretty well known internationally, working on English-language acquisition. Duolingo specifically have a lot of users here.

### Audrey Tang:
There’s also a Taiwanese startup called VoiceTube that’s using YouTube to learn English. There’s literally dozens of such efforts. Maybe they have their own community. I’m not actively participating in that, but yeah, introducing you to that community as one of allies.

### Desigan Chinniah:
I think, in general, getting into the startups, locally, looking at voice and speech would be an interesting side conversation that we might want to add, just to understand, &quot;What are they doing? What are they trying to achieve?&quot; and, &quot;Is there any way that Mozilla could be supporting, helping, benefiting, whichever way?&quot;

### Audrey Tang:
That would be a separate conversation. If you had raised it up earlier, I would have invited more people.

> (laughter)

### Audrey Tang:
Maybe next time around? Now I’ll make sure to follow-up with the local team.

### Desigan Chinniah:
We have local people, as well. They can also...

### Joe Cheng:
We have a meeting on Thursday with the local English startups and the local researchers. Thursday afternoon.

### Audrey Tang:
The English as primary plan is not yet national law or regulation. We expect it to be more solidified under the new Minister of Education -- \[laughs\] like new as of this week -- sometime this year. It will also take extra time. It requires legislation changes. Don’t hold your breath for it. \[laughs\] We’re working on this, and English is not a traditional language here, or indigenous.

> (laughter)

### Audrey Tang:
We’re still working with this in our capacity as ministry officials. As a civic hacker, I’m happy to introduce to the local group.

### Audrey Tang:
Next, communication. What would you prefer?

### Audrey Tang:
When we talk with, for example, Microsoft, about something very similar to this plan, also using the National Language Act, we basically had a joint communique thing where we have an English and a traditional Chinese version that we basically hand to the CNA, the Central News Agency, and which will then get syndicated to every other press.

### Audrey Tang:
If you look for my name and Microsoft, you will see the joint communique is also posted on my Facebook. That’s just a standard affair. When we visited Microsoft, we just have them check the communique and they just EMA and an hour later, it’s all the media. I don’t know what...

### Michael Henretty:
We obviously have to do it in all the other indigenous languages...

### Audrey Tang:
It would be very symbolic.

### Michael Henretty:
...because that’s the statement we’re making.

### Audrey Tang:
At least we can get the Amis MoeDict team to speak in Amis. \[laughs\] That will create some excitement because just this week, the mainstream media is talking about orthography because Kolas insists that the media use the Latin alphabet to spell her name instead of the kanji.

### Audrey Tang:
I think all the media actually agreed. I see &quot;Kolas&quot; spelt in Latin characters everywhere. I think also because it saves a half-width character. It’s better for the press anyway. It’s shorter than three full-width characters.

> (laughter)

### Audrey Tang:
It’s shorter if you print it in Latin, especially if you use a proportional font.

### Audrey Tang:
In any case, I think we can write this communication if it’s deemed as useful to you. It’s purely optional.

### Michael Henretty:
It sounds like a no-brainer that we would like to do it, even though pure symbolic, would you need support from us? How do these things work?

### Audrey Tang:
Have you read my communiqué after visiting Microsoft?

### Michael Henretty:
I have not.

### Audrey Tang:
Please do read it. There’s something that we can work based on. Our communication staff here, Sheau-Tyng... She will be the contact person. She is in charge for the tri-weekly column at the business weekly and other high-profile mainstream media stuff.

### Audrey Tang:
For social media and face-to-face media communication, there’s another staff. We will have to talk also internally about how we position this, whether as serious mainstream stuff or as a more lightweight call to action to the community.

### Audrey Tang:
I imagine, unlike Microsoft, what you ultimately want at this stage is more people participating in Common Voice. We’ll talk about positioning. Please look at the memorandum a little bit and we’ll work based on that.

### Michael Henretty:
We’ll do that. I can’t imagine there’s any problems but we’d love to see how that works. Sounds great. Thank you, by the way, for your, is it radical transparency?

### Audrey Tang:
Yeah.

### Michael Henretty:
It’s very much appreciated. This sort of work. This is how we tend to think about things. We try to be very intentional about how we’re working so that others can get involved. It’s a very hard process, I imagine, at the level that you’re working, this is a big effort. Thank you for that.

### Michael Henretty:
We hope that we can continue to work together not with just our values but on actual goals in terms of this language and cultural preservation. Thanks for having us today. We hope that we can continue to work with you as we move forward.

### Audrey Tang:
Anything else?

### Michael Henretty:
No.

### Desigan Chinniah:
One thing, just to table while we can. We’re specifically talking about common voice, languages and voice speech but obviously even from this, there’s 101 other things. Are there interesting things that you would like to bring up?

### Audrey Tang:
I invited Ashley Boyd, I think, to our annual Social Enterprise Summit. That’s something that we can talk about because Mozilla says, on your front page, that you’re a social enterprise, which is very rare, even for social enterprises.

> (laughter)

### Audrey Tang:
It’s not just something you do — It’s something that you’re proud of.

### Desigan Chinniah:
It’s part of our DNA.

### Audrey Tang:
That’s exactly right. That aligns a lot with our social innovation plan, which talks about social enterprise not as something that’s only applicable to startups. You have to start from scratch to solve a sustainability developmental issue, which is great but there’s many more.

### Audrey Tang:
You can either work with existing large charities to figure out how they fit into the supply chain or large, existing for-profit organizations like Netscape Inc. and figure out how that work can be part of the ecosystem instead of a narrow silo.

### Audrey Tang:
I was there in ’97, working with the pro-community and the other communities to try to keep it from free software to also open source. I think a lot of strategies that we talked about long ago, 20 years ago, I think that’s still applicable now.

### Audrey Tang:
It’s not just open source now anymore. It’s open innovation and social innovation. It’s widely applicable. What I would like to position is that Mozilla is leading this edge, being the pioneer for 20 years now and resulting in innovations that are household names like Firefox.

### Audrey Tang:
We would encourage other established enterprises to also think in this way, even if they’re not ICT companies, but everybody can learn from open innovation and be part of the wider ecosystem. For maybe our next years, summit in for social enterprises, I would love to have a Mozillian presence.

### Desigan Chinniah:
...a connection to Patrick and Suzy who also talked about open innovation. We’ve done extensive research with years and years of community input that’s finally being digitalized, taking a few months’ process through Katharina or Sharon in IT. There’s tons of stuff we potentially could implement in 2018.

### Audrey Tang:
Just able to get the contents localized. Basically, what creative commons did here in Taiwan, do something like that here because CC Taiwan, there’s also a concerted effort in the early 2000s to localize the content, to translate it to appeal mostly to education interests and things like that. See now the Ministry of Education used these devices for almost everything that they fund.

### Audrey Tang:
There’s something that we can also talk to the private sector, not just the public sector. This is the movement, I think, succeed completely in talking to public sector into adopting it culminating in the national regulation of open data. I think the private sector now also needs to hear the message but it’s not CC licensed. We need something more. Open innovation, social innovation may just be it.

### Desigan Chinniah:
Next year you have a summit or a conference.

### Audrey Tang:
Every year, on social entrepreneurship. It’s called Tomorrow Asia.

### Desigan Chinniah:
When is that?

### Audrey Tang:
Mid May-ish. Anything...?

### Joe Cheng:
What we do here in Taipei, we’re actually a product team. We’re actually building products and releasing them. We’re trying to make products useful to people. Being able to reuse your conversation, first of all, in building up the language database is awesome.

### Joe Cheng:
I think what the team here in Taipei can do is perhaps making use of the technology and building a product and release it to market, really helping users here in Taiwan. For example, recently we saw research in Taiwan to see how we can help the people here in Taiwan, especially who work let’s say on the elderly people.

### Joe Cheng:
Our society’s turning towards this ageing society, where most people are growing older and need universal access. \[laughs\] We’re trying to see how we can help out here. I think there is probably some kind of opportunity here that we can think about when it comes to exploring use cases and building mobile apps that can really help people.

### Joe Cheng:
I think what people are saying, if you go to the learning English piece, and it’s the same use case, that we can support that.

### Audrey Tang:
What I’m hearing, you’re focusing on universal design, with a focus on elderly?

### Joe Cheng:
The team based here in Taipei, we are a product team. We actually develop mobile apps and building services to users. Our focus has been mostly on end-users in the past. It started recently. We have a small team of researchers that’s starting to do a bit more research...

### Audrey Tang:
That’s great.

### Joe Cheng:
...in Taiwan to see how we can tap into opportunities here in Taiwan. There are a lot of opportunity and a lot of potential here. One area that we specifically chose was to see if we can add into the elderly society and how we can help the people, for example people 40, 50 and up, to get them to make use of technology and to get them online. We think most interfaces could be more interesting.

### Desigan Chinniah:
I think, in general, what we we realize is, we build Firefox as a product, that’s a very global product, and obviously, lots of people use it, there are definitely use cases and lots of possibilities with more niche products.

### Desigan Chinniah:
For example, as Joe said, it’s very product oriented. They both are working on Firefox and they have lots of expertise in mobile Firefox. It came out the last year, but they went out to Indonesia and brought a specific product called Firefox Rocket that has a very specific use case that meets the needs of those users in Indonesia.

### Desigan Chinniah:
Now they may be looking at things locally in Taiwan. That could look at elderly users on the Internet. Their needs will be very different to a millennial’s need, who will be very different to our needs. How can we perhaps build products that specifically empower the older user segment, if you want?

### Joe Cheng:
We have pretty strong research team that’s in our user research team. What we do a lot here is we turn to the user, try to do user research, and then we build prototype and see if the product will actually make sense for those users. Those are a lot of the things that we do here based out of Taipei.

### Audrey Tang:
Are you working on your own or with various established non-profits here, focusing on aging, such as 弘道 or 智榮, those groups working on aging?

### Joe Cheng:
So far, we just got started, so we’re on our own for now. For example, those other orientation that we can follow...

### Audrey Tang:
Background is that many large elderly-focused charities are now pivoting into setting an arm on social enterprise, because they also want young people, design teams, UX research, and so on. The existing formulation as a pure charity sometimes holds them back. We also work on cases where a non-profit association or foundation essentially retains control of the underlying corporation.

### Audrey Tang:
The corporation donates back or distributes the profits back to the mission. The foundation or the association controls, through special voting stock or some other ways, the mission of this corporation, which allows it to raise funds, not straying away from the mission.

### Audrey Tang:
Many elderly-focused associations and charities are now doing exactly that. I always refer it to the Mozilla Model, because it is exactly the Mozilla Model. \[laughs\]

### Michael Henretty:
That’s exactly how we do it.

### Audrey Tang:
Thanks for being an inspiration.

> (laughter)

### Michael Henretty:
Not me. I’m new five years go. Dees is the guy.

### Audrey Tang:
Thank you for being an inspiration. That’s it for now?

### Michael Henretty:
Yeah.

### Audrey Tang:
See you at the dinner?

### Michael Henretty:
I think that’s it. Yeah, we’ll see you tonight at dinner. Thanks for having us.

### Audrey Tang:
Cool. Thanks for dropping by.

### Desigan Chinniah:
As usual, in Mozilla style, we have gifts.

> (laughter)

### Audrey Tang:
Awesome.

### Desigan Chinniah:
Everyone likes them.

### Audrey Tang:
Firefox Developer Edition. That’s my browser of choice.

### Desigan Chinniah:
I also have, not too many, but T-shirts.

