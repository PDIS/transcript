# 2017-08-28 Interview with Danny Lämmerhirt

### Danny Lämmerhirt：
Hello?

### Audrey Tang：
Hello. This is Audrey. Can you hear me?

### Danny Lämmerhirt：
Yes. Loud and clear. Perfect.

### Audrey Tang：
That’s great.

### Danny Lämmerhirt：
Hi. It’s a pleasure to meet you. It’s been a while. We haven’t met in person, but I saw your keynote at TICTeC 2017, in Florence. That was very nice, very impressive how you talk about the open government initiative in Taiwan, and especially also the rate with which you could answer 30 or more questions. \[laughs\]. Thank you very much for taking the time. It’s a pleasure to have a chance to talk to you.

### Audrey Tang：
Tell me about your research.

### Danny Lämmerhirt：
To give you background to our research, it all started with the Global Open Data Index, and our assessment of open licenses or license terms across more than 90 governments around the world.

### Danny Lämmerhirt：
What we saw is that governments often create bespoke licenses. We find licenses that are, even for us, hard to interpret sometimes. We identified the creation of bespoke licenses as a larger problem, which is known for many years under the term ’license proliferation’. We wanted to understand what we can do about license proliferation. We thought this is necessary, because there are some problems commonly associated to it. When governments choose to create their own licenses, it takes time and resources. Bespoke licenses can create uncertainty for licensees. They also can cause incompatibility issues across licenses. With these issues as starting point, we were asking how we can tackle license proliferation.

### Danny Lämmerhirt：
This is the larger background. Our research wants to understand what makes governments opt for creating bespoke license. What are the reasons why governments say, &quot;OK, we don’t use a standard license like Creative Commons, but we want to create our own one&quot;?

### Danny Lämmerhirt：
The second question is once a national government, for example, creates this bespoke license, how does it work that different government agencies now use this license, and not create their own license again? That’s the second set of questions.

### Danny Lämmerhirt：
Our third question, which is more of a desired outcome than a question, is &quot;What can we learn from that? Are there any best practices creating bespoke licenses, or using standard licenses? What can we learn to help governments making better use of a harmonized set of licenses, if you want, that is also compatible internationally?&quot;

### Danny Lämmerhirt：
This is the background. Now I would like to talk with you about about Taiwan’s Open Government Data License, and the process you went through in order to create the license. Also I’d like to know how you implemented it. Maybe you can talk a bit about what was the situation before you created your own license.

### Audrey Tang：
Sure, certainly. In the application, there is a link to a Hackpad, which is a shared document, which is all in Chinese. It provides some key dates, if you are interested.

### Audrey Tang：
The community actually created the Taiwan Open Government Data License at a hackathon, that’s the 11th hackathon of the g0v movement. It was proposed by Lucien and Florence, as you can see here in the Hackpad.

### Audrey Tang：
The situation back then, at the end of 2014, was that there is not, strictly speaking, a government license for the Open Data Platform ’data.gov.tw’, but only terms of use. It’s not very clearly a license.

### Audrey Tang：
Also, many, especially regional city governments, see it just as one of the data portals where they post their index, but they all have their own licenses. For example, Taipei City, New Taipei City, all have their own licenses.

### Audrey Tang：
There are, of course, other government, like city governments, like the Kaohsiung City government that said, &quot;OK, you can use our data according to the terms of use of the national Open Data Platform,&quot; but there really wasn’t the clear legal interpretation of what exactly this means, because it’s not, strictly speaking, a license, just a term of use. Another case was the National Palace Museum, which published data under their so-called open data terms of use at the time. These didn’t actually fit the open definition.

### Audrey Tang：
So the problen was not so much license proliferation, but the general ambiguity of what exactly open data is in our legal structure. It’s not open license proliferation, but rather a dilution of the term open data. The terms of use were unsublicensable, and you could not create derived works. It really doesn’t fit the open definition if you can’t make derived works. That was the situation at the end of 2014.

### Audrey Tang：
The Open Government Data License was the general idea of the community. They are acutely aware of license issues and potential solutions. Lucien and Florence, who proposed the license, both worked on the Creative Commons license, both the third version, which had to be localized to Taiwan, and also the fourth version, which is universal. They both worked on that as part of the Creative Commons Taiwan group. They applied their knowledge learned from the CC Taiwan project, and created something according to three strict design goals.

### Audrey Tang：
The first, according to their slides -- I’m reading off their slides now.

> (laughter)

### Audrey Tang：
The first is a clear interpretation of legal framework that this is a license. Part of the framework of the open data platform is to clearly delineate the license versus the term of use. Term of use describe how people can use the Open Data Platform in general, but each data set carries its own license field. Those two must not be mingled together. That’s the first design goal.

### Audrey Tang：
Second goal is that technically, it needs to be interoperable internationally. The idea is to list open definition as the requirement of open data for government-published open data, and then design this license to comply with the open definition. This does not mean that we asked Open Knowledge right away to approve the license, but we aimed for a one-way transition clause to CC 4.0, which is already meeting the open definition.

### Audrey Tang：
That’s the second goal, is that internationally, we don’t need additional interpretation for it to actually work.

### Audrey Tang：
The third goal is for the government, at the time, to easily adopt it. Their draft version, as well as all the community revisions -- which we all participated in -- are relinquished under the Creative Commons Zero license.

### Audrey Tang：
One of the g0v movement strategies is that most of our products that are intending to be official at some day, are CC0. The government doesn’t really need to ask our copyright if they somehow make it the official version. That’s pretty much it.

### Audrey Tang：
It took about eight months to arrive at a national version, which is mostly the same as the initial community draft. It has a disclaimer, I think, but I don’t think there’s any substantial differences. Once that happens, now we have something that we can refer to when saying that all the government agencies must publish data under a open definition conforming license.

### Audrey Tang：
When they need to choose one, they are now faced to either invent their own bespoke license and then submitting to meet the open definition, or they can just take the one that, by definition, fits the open definition. Most choose the latter.

### Audrey Tang：
Now, even the National Palace Museum publishes under this license, so we don’t have a proliferation or ambiguity of licenses as a result of this.

### Danny Lämmerhirt：
Maybe you can talk about the design goals a bit. I find that it makes a lot of sense, and the design goals are very clear. It seems that they are good guidelines to design a bespoke license, which is compatible, and addresses other concerns of license proliferation.

### Danny Lämmerhirt：
Maybe you can talk a bit about the delineation of the use cases you mentioned, and maybe also the choice of law when drafting the license. Were there any problems of drafting these points, for example? Were there discussions around use cases that you didn’t want to include, for example.

### Danny Lämmerhirt：
Do you know anything about this process?

### Audrey Tang：
Yeah, certainly. During the community discussion, there is actually a lot of issues raised in the Hackpad discussion.

### Audrey Tang：
For example, there was a use case where the providing agency, as they often did, requested a copy of any derived work from the data - be it an application or whatever, as a tracking mechanism, if you will.

### Audrey Tang：
That’s actually one of the very common clauses before open data, when we only had the freedom of information, Public Information Publishing Act, is that if you make derived works, let us know somehow, as part of the terms of use.

### Audrey Tang：
There was quite a few discussions around this clause, because there’s clearly a need by the providing agency, but it’s actually not so clear that it actually fits open definition. I may want to make something that really requires a very high barrier of entry, and I don’t want to provide a copy of that to the providing agency.

### Audrey Tang：
After some debate, it was deleted from the community version, because it’s not part of any of the three initial design goals. It’s more of a request, because it wouldn’t then fit the open definition definitions, so they took it out.

### Audrey Tang：
There were some other issues as well. There was about whether usage of this data or misuse can cause the damage in reputation for the providing agency, and whether the user of this data should provide the warranty or compensate for any damages.

### Audrey Tang：
It was then discussed after quite a few discussion that existing civil code actually covers this already. It really doesn’t matter whether it’s part of the license or not, so that was taken out. I think that’s the two substantial debates that we have.

### Danny Lämmerhirt：
That’s interesting. I have the impression the more I talk with government officials, the more I see these concerns replicate. This really a phenomenon that occurs in a lot of governments.

### Danny Lämmerhirt：
Another point that’s interesting is one-way transition clause. As far as I’m aware of, you are the only government that has this specific clause. Obviously, I don’t know all license text of bespoke licenses. Were there any issues in creating this one-way transition clause?

### Danny Lämmerhirt：
From other governments that they pick specifically standards, international licenses like CC BY 4.0 in Finland, because they say international compatibility is important to us, so we want to use this license. I was curious how this went about.

### Audrey Tang：
There are a few things. The first is that this one-way transition clause is actually very familiar to us, especially to me, because the first open-source license that I encounter was the Artistic License as used in the Perl community.

### Audrey Tang：
Larry Wall designed it, Artistic License specifically, to make people using the GNU Public License happy, because they can, if they want, transition from Artistic License to the GPL.

### Audrey Tang：
At the time, GPL has a very large number of users, and Artistic License is only used by Perl or a few other software packages. He wanted to make sure that it’s considered part of the larger free software movement, so this device is promoted to us.

### Audrey Tang：
As why do we not just choose CC 4.0? Was that the question?

### Danny Lämmerhirt：
Yeah.

### Audrey Tang：
At that time, there is no Chinese version of Creative Commons 4.0. It was not translated until 2016, if I am not mistaken. It wasn’t an option. While we could of course use CC BY 3.0 Taiwan, but that doesn’t really work.

### Audrey Tang：
Until we have a truly international Creative Commons license, I don’t think it’s easier or any more comfortable than a local license with a transition clause. That was back then. I’m not sure if we do the whole exercise now, wouldn’t we just choose CC 4. Maybe we would, but that’s beside the point.

### Danny Lämmerhirt：
How does the transition clause work in practice. It would mean that, for example, if I would choose to create derivative work based on the data you publish on your data portal, I could just license and sublicense that as CC BY 4.0, and would be compliant, basically.

### Audrey Tang：
That’s exactly right. We take, for example, the data has its origin URL. You use that as the attribution, and that will completely state the license quite well.

### Danny Lämmerhirt：
This is a great tool. When I did my initial research, digging into, for example, the teaching materials that Creative Commons provided, I did not come across this very intuitive mechanism. It’s a great idea.

### Danny Lämmerhirt：
The point you made about governments need to easily adopt...must be easy for them to adopt a license, you said that governments can currently choose between which license they want to apply?

### Audrey Tang：
As long as it’s fitting the open definition. For example, they can also choose the CC Share-Alike license.

### Danny Lämmerhirt：
Where is it documented? Do you have an open data strategy or something, where you have the document?

### Audrey Tang：
Sure. I’m pasting you that. Actually, all the relevant documents is listed in one single page in the open data platform. I’ll paste you that. You can follow all the links. Here we go.

### Audrey Tang：
It also talks very clearly about how all the new ICT systems must produce open data by default, unless its maintenance cost over the past three years is one million euros or more, or things like that. You can see the open definition is our definition of open at the very first paragraph in section two.

### Danny Lämmerhirt：
I will go through this page later. I had another question: I know that some agencies publish data both on a national data portal, as well as on their own websites, which sometimes have their own terms of use. They might not be updated or anything so that the same data is published online in different places under different terms.

### Danny Lämmerhirt：
Do you have any governance mechanisms for that in place, or is it regulated through the platforms?

### Audrey Tang：
We actually do. Let me find a power adapter. I’ll be back in a minute.

### Danny Lämmerhirt：
OK.

> (pause)

### Audrey Tang：
I’m back. Batteries are the only technology that doesn’t improve exponentially.

> (laughter)

### Audrey Tang：
We do have an automated machine-to-machine protocol to syndicate between data portals. That is to say both the regional city portals and national city portals exchange through this machine-to-machine interface. That answers the technical part of the question.

### Audrey Tang：
As of whether the agencies themselves still publish the URL to this page that clearly says the license applies to all the data provided online. They are more and more doing so. We are not 100 percent yet, but whenever someone sees something, then we send a letter for them to change. So far, there’s no resistance.

### Danny Lämmerhirt：
It’s a two-stage process. Do you automatically then map the terms of use? You try to track terms of use through this endpoint, you said? Is that right?

### Audrey Tang：
The same data is provided often in two forms. It’s provided as data set over at data.gov.tw, which we handle through M2M, machine-to-machine APIs.

### Audrey Tang：
On the other hand, it may be also offered as a download link, for example, to a ZIP file or to a CSV file, from its normal website. I’m referring more to the latter, where the term of use of one specific website also overlappingly refers to the data that may be followed through their website.

### Audrey Tang：
We’ve updated the template. We are at the moment not strictly speaking saying that all the agencies must switch over to the new license. Sometimes, an external user or experts would make the suggestion. So far, all the ministry that received the suggestion, that I’m aware of, made the change.

### Danny Lämmerhirt：
It’s a bit similar to how Northern Ireland is dealing with this. What they do is they rely on uploads from other agencies, and as soon as the data is uploaded on their national portal, there’s only one license to apply.

### Danny Lämmerhirt：
It’s slightly different as a process, because as far as I understand, you need to be aware of the terms of use that are applied, and they are not stored in metadata or something in your case, right?

### Audrey Tang：
In our case, it’s actually, we don’t provide a way for agencies or city governments to upload their data, per se. The national Open Data Platform only uploads the metadata. The actual download still goes to the respective agencies.

### Danny Lämmerhirt：
Now I get it. This is interesting, because these are exactly the best practices we wish to identify. Being conscious of the time, another question I had was why did you apply for the open definition? Why did you apply for official approval? Hardly anyone does. It would be interesting to hear the reasons.

### Audrey Tang：
Again, because the community wants it. I’m just the sounding board for the community. In this case, it was proposed by Lucien, the same person who originally drafted this license.

### Audrey Tang：
It’s important because we are moving toward defining open data as fitting the open definition, and perhaps -- I’m guessing, here -- that he wants not just the one-way transition clause part, which automatically fits the open definition, but the design itself to be verified by the open knowledge community.

### Danny Lämmerhirt：
This resonates with our experience that the open definition really lives from the community pull. Unfortunately, there’s not a strong pull at the moment to make governments apply for the official approval, for example. It is definitely an important point to strengthen the community in this field, which doesn’t seem to happen in every county at the moment. The link you provided -- the API link -- is there documentation? Let me quickly check. Do you have any schema or something for the M2M communication, how the data is uploaded on your portal?

### Audrey Tang：
Yeah. That’s documented in the OAS standard. It’s a updated version of Swagger. We actually also adopted that as a national standard. We’re the first, at the moment, the only one to do so.

### Audrey Tang：
Again, for all the newly-constructed systems, the agency can, as part of IFP, to require at zero or very little cost, a production of the OAS schema, in addition of the open data set -- not open, or any structured data set.

### Danny Lämmerhirt：
I’m going to note that. What I’m going to do now is writing up the final conclusions. We are not sure if we are going to publish the report externally. If we do, I’m happy to share it with you, also in advance, should I intend to quote you directly.

### Audrey Tang：
Sure. It’s just fine. All right.

### Danny Lämmerhirt：
Thank you very much for your time, and have a great day.

### Audrey Tang：
Yeah, you too. Thank you for the interview. Bye.

### Danny Lämmerhirt：
Bye.

