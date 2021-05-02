# 2020-04-07 Interview with Shafi Goldwasser

### Shafi Goldwasser:
What is the situation right now?

### Audrey Tang:
The situation is pretty calm. People feel protected. We’re like this island where we’re back to the single-digit of new cases every day, and almost all of it’s from international travelers returning home. People are feeling safe. Every two weeks, people can get 9 surgical masks if they’re adults, or 10, children’s.

### Audrey Tang:
The social distancing is advisory. There’s no penalty yet, but people are following the social distancing ideas very diligently. It is mostly just about putting on a mask if you happen to be indoors, and around one meter from people. It’s very mild. The tourism industry, of course, is taking a hit, as is air travel.

### Audrey Tang:
Otherwise, everyday industries such as restaurants operate normally. Movies are open but reconfigured their seatings so that it’s below 100 people each in a audience. Life is normal.

### Shafi Goldwasser:
Early on, I guess, my expectation would have been that you would have been the second-hard hit after China.

### Audrey Tang:
That’s what everybody expects, including us, which is why we started mitigating last year, whereas most countries started mitigating this year.

### Shafi Goldwasser:
Actually, the things you’ve mentioned, federated learning and differential privacy, as you’ve said, these are great areas of research, great areas to use theoretical techniques in practice and maybe get less accuracy. It doesn’t matter in the applications that mostly you would be using. Here, this is not the case, right? We’re talking about, as you say, single digits.

### Shafi Goldwasser:
You want to know very accurate information, which is in very high resolution. My question is, when you said you already did some legwork because of SARS, to go through the constitutional process, and to see what’s acceptable, not acceptable. Does this mean what level of privacy is acceptable, or whether it’s acceptable in such a situation not to worry about that?

### Audrey Tang:
It’s about constraining essential freedoms. During SARS, there was a case where the entire hospital was barricaded, and people within there are forbidden to go out, including medical workers. That, of course, is a constitutional question, whether not endangering people outside of the hospital warrants putting people essentially within the barricade.

### Audrey Tang:
The Constitutional Court said that it is not unconstitutional, but the existing laws are lacking in terms of the due processes involved. Our laws then went through changes that explicitly spells out these processes. One, the main thing that you’re concerned about, is about out of purpose use of collected private information.

### Audrey Tang:
That is in our Privacy Act, which is GDPR compatible-ish. We’re getting adequacy soon. Before we get an adequacy, I would not say it’s fully compatible, but it’s quite compatible because it’s based on a European Union Privacy Act before the GDPR.

### Audrey Tang:
It specifically said that you can only use the collected information such as the whereabouts of the phone of the telecom companies, if it protects other people, the general public, from harm, and/or it protects the person themself from harm.

### Audrey Tang:
In the Constitutional Court ruling, if barricading people so that they cannot leave a institution, a building, is ruled constitutional, then certainly getting this out-of-purpose signal data from the telecom providers is constitutional, because it’s used only for the purpose of digital fence.

### Audrey Tang:
Digital fence in its worst form is exactly the same as a barricade. It’s almost always better than the physical barricades, from the constitutional human right viewpoint. The legality of this is not disputed this time.

### Shafi Goldwasser:
Even when you talk about this, saying that the law says that you are allowed to collect information in this particular case, a virtual collection, as long as it helps protect the patient himself or the public, then there’s a question of whether even there there’s a restricted amount of information that you can collect.

### Shafi Goldwasser:
What’s deemed to be necessary and what’s not deemed to be necessary.

### Audrey Tang:
When we say outside of purpose, we mean that we don’t actually touch the data collection phase. It is mostly the data processing and application face that we’re touching. The telecoms are already collecting the signal strength.

### Audrey Tang:
The amount of data collected is minimal, for people under home quarantine for 14 days. We’re just sending them instant messages where they reply, with their temperature, whether they show symptoms, and any suggestions they have to the quarantine experience. That’s the only data that we collect. It’s minimal, and we can prove it’s necessary.

### Shafi Goldwasser:
I guess what I meant is not that you’re collecting new data, is that you’re processing data on everyone, or you’re processing the data on people who…?

### Audrey Tang:
For people under the home quarantine, they’re clearly informed of it, although there is no consent process because constitutionally, there is no requirement for a consent process.

### Shafi Goldwasser:
Good. This made sense early on, where you could control some of the people who would go into quarantine.

### Audrey Tang:
It’s a large amount of people, like 50K, but yes.

### Shafi Goldwasser:
They’re the people went to the border, you say, and now they’re in quarantine, and now you want to make sure that they are not leaving the quarantine, or if they are, who they’re meeting, or that’s not a question at all. At that point, it was just a question of enforcing the rules and staying in quarantine?

### Audrey Tang:
Yeah. If they break out of the quarantine, of course, the automated system, as you see on the picture, notifies the county governments, the neighborhood managers, the police dispatch if they went too far from the quarantine, if necessary.

### Audrey Tang:
Of course, we then use the digital fence checking to make sure that if they significantly overlap with other people’s phones, then they may be also at risk. That is only if you escape quarantine.

### Shafi Goldwasser:
Like you said, they went to the store or something because they need to.

### Audrey Tang:
Exactly.

### Shafi Goldwasser:
This part of finding out whether they overlapped with someone else’s phone, that means you want to have access to the information of the other phones as well, and then checking whether the GPS are in the same place, to be defined, or the Bluetooth. It talks about…

### Audrey Tang:
I don’t think we use signals other than the ones provided by the telecoms. It’s mostly base station data. This system is developed in Taiwan. It’s one of the major telecoms, the Chunghwa Telecom developing it. The other four telecoms voluntarily participated. They settle on an API so that even across different telecom providers, this system can calculate proximity.

### Shafi Goldwasser:
The thing is, I guess that the issues that people are dealing with right now is, who is doing the recording? Who’s entitled to that information? Obviously, the telephones companies have that information. The other question is does it ever leave the phone or doesn’t leave the phone?

### Shafi Goldwasser:
You’ve probably have heard this particular idea of a scheme, just because it’s probably the first thing people come up with. Your phone generates some random numbers every time it’s in a location, just a random number and location. Later, people who have been in the same…if you get sick, you advertise those random numbers and somebody can…

### Audrey Tang:
Of course. Something like that. This application layer, that is the location history tool, it’s developed by civil society here in Taiwan. It’s also been incorporating data from Korea as well as from Israel. It relies on an application-level feature of Google called Location History, which is for a phone installing Google Maps or an Android phone in general that enable location history tracking.

### Audrey Tang:
Then you get the Google Maps timeline. The basic idea of this simple tool, which is a web-based tool, is that it automatically ask you to download the last period of your Google history as well as any API-compatible service, and also downloads the available data of specific cases so that it calculates overlaps entirely locally.

### Audrey Tang:
It doesn’t tell you what to do. It just shows how the contact worked. In this way, your location history is not shared. It doesn’t really leave your phone. It’s between you and the nav sources.

### Shafi Goldwasser:
On my phone, within my phone, I can tell when I was in proximity, also when I should be, but it’s not only me that knows it. That information also goes to…

### Audrey Tang:
No, the information, with this tool, because this tool is general-purpose, it’s for people not under home quarantine. We do not have the constitutional right to force them to share anything.

### Shafi Goldwasser:
Still, let’s say they were exposed. Now they know that they were exposed, because their phone tells them that. At this point, they are at risk. They are a risk to society, possibly, because they can transmit it further.

### Audrey Tang:
Right, so they wear a mask and get a check from the local clinic.

### Shafi Goldwasser:
My question is, how do you enforce that?

### Audrey Tang:
Well, I guess that’s like asking how do we enforce washing your hands with soap? We do not enforce that, but people do that.

### Shafi Goldwasser:
True. The assumption here is that people are going to report – in some sense, take care of themselves, or go and ask for masks.

### Audrey Tang:
Because people don’t want to be sick, and we have a single-payer health system. They are not going to pay much for the treatment, and the surgical masks are plentily available.

### Audrey Tang:
Putting on a mask, protecting others, going to a clinic to get a check is the logical thing to do if you know that you’re going to be protected and you’re not going to cost a fortune.

### Shafi Goldwasser:
Essentially, what you’re saying is that the privacy issue then are between the telephone company, which has the information anyway, and yourself.

### Audrey Tang:
Yes. Or between Google and you, but yes.

### Shafi Goldwasser:
Those are the people who haven’t been quarantined. For people who have been quarantined, then it’s a weird question. You know that they’re part of the system, the governmental system that wants to make sure that they were being monitored and is able to track their movements.

### Audrey Tang:
Their whereabouts, yes.

### Shafi Goldwasser:
There is a system here, and obviously it’s been successful. Are there statistics? Tell me about this application that the telecom company has about the quality of this proximity-checking. Is there any kind of feedback from this experiment?

### Audrey Tang:
Of course. Every person under quarantine, as I said, other than their temperature and their symptoms, we collect their feedback to the system. It’s continuously being updated by people’s feedback. There’s a lot of challenges, of course.

### Audrey Tang:
There will be, for example, spammers that masquerade as the SMS checkers, and it’s solved using crowdsourcing, it’s called Whoscall, it’s another technology.

### Audrey Tang:
Or we can switch to the LINE system, which has a verified account. It’s like WhatsApp. A chatbot can then automate most of the daily checking, so that we free up some chores from the local managers.

### Audrey Tang:
There’s also the challenge of people simply going into the quarantine not expecting to pay for the accommodation, but actually, the conversation comes after getting them the accommodation. If people come to Taiwan but with no cash and so on, the local government need to find them somewhere, and so there’s dedicated dormitories and now hotels dedicated for this purpose.

### Audrey Tang:
The volume went beyond the original expectations, but now, we’ve been expanding such accommodation places, and so on. It’s a daily-improving system, so what we are describing now may well change tomorrow, but the constitutional and algorithm’s principles stays the same.

### Shafi Goldwasser:
In terms of international collaboration, there’s the Taiwan system and then people are leaving Taiwan saying they’re going to another airport, whether they’re doing it now or not doing it in the future. There’s going to be a lot of travel, so there has to be a lot of collaboration between governments. Is there any thought given to that?

### Shafi Goldwasser:
Again, the social privacy of your citizens, protected by your constitution…

### Audrey Tang:
Our citizens can return any time. Currently we’re banning all foreigners arriving to Taiwan, unless for a specific purpose. They need to be reviewed on a case-by-case basis. In this time period, the problem you raise does not present itself. Eventually, of course, we need to solve that.

### Shafi Goldwasser:
Eventually there has to be some kind of…We want to continue with this idea that we can travel globally and do business globally. It requires being the right person. It has to be some thinking about how much…

### Audrey Tang:
Yeah, or maybe with which everybody switches to telepresence and immersive reality, and methodically cut down carbon emission.

### Shafi Goldwasser:
Yeah, there has been talk about that. Certainly there is some upside to this shelter-in-home. One other thing that is not privacy related, but when I read about it in the beginning, is that you were checking for symptoms of people arriving to Taiwan. As far as they understand now, a lot of people are asymptomatic.

### Shafi Goldwasser:
Any thoughts about that? That there are people your system didn’t check mark as going into quarantine?

### Audrey Tang:
If they’re showing symptoms, they’re going to a hospital. They’re not going into home quarantine.

### Shafi Goldwasser:
Oh, I see. Everybody gets quarantined unless they have symptoms. Then they go to the hospital.

### Audrey Tang:
Right. The difference is between if you show symptoms, then you go to a hospital for a quarantine. If you’re coming from a highly dangerous area, highly risky area, then the entire airplane goes into a quarantine center. Well not the airplane itself, all the passengers.

### Audrey Tang:
If you’re from a mild place, and you show no symptoms, then you’re put into the digital fence and you’re at your home doing the 14-day quarantine. Everybody is quarantined.

### Audrey Tang:
I think it has a lot to do with hospitals’ preparedness. If the hospital has – in computer science, it’s called redundancy or high-availability plans – then you can afford to do that. If you don’t, then the hospital itself needs to undergo reconfiguration. Certainly it cannot overwhelm itself during the reconfiguration. Again, it is a question of preparedness.

### Shafi Goldwasser:
You say as a result of SARS…

### Audrey Tang:
Yes. We were not prepared during SARS. We decided 37 people died is 37 people too many. There was a whole recap of not just the medical procedures, but as I mentioned, also the constitutional rulings and things like that.

### Shafi Goldwasser:
Do you find that there’s a lot of people coming to you for finding out, like what I’m doing right now, what you’ve done?

### Audrey Tang:
Yes. There’s a lot of publications as well, and journals. A lot of focus that we’re putting on now is on useful knowledge sharing between bilaterals because every municipality, to be precise every outbreak epicenter, is very different. We think it’s very useful to work bilaterally instead of a universal playbook thing.

### Shafi Goldwasser:
Absolutely. So, are you working with the Israelis?

### Audrey Tang:
Hmm, I personally did not have calls with people in Israel. We understand our, for example, Department of Cyber Security and so on did do briefings on many countries with similar values. I don’t know whether it includes Israel or not. We do know that your prime minister cited us as an example of the digital fence.

### Audrey Tang:
That apparently has some constitutional controversies, watching from afar. I did not have any conversations, nor do I know anyone who did have direct conversations with your prime minister.

### Shafi Goldwasser:
Very interesting. About all the other things, in a usual day, like federated learning or the venture pharmacy, the work we’re doing with MPC and homomorphic encryption. It’s a big anti-money-laundering type of use or form of encryption, which is very similar to what you need here.

### Shafi Goldwasser:
You need to query information and only get back without letting them know what you’re querying, and so forth. I’d be very happy to talk to you in the future.

### Audrey Tang:
Yes.

### Shafi Goldwasser:
Thanks a lot for your time.

