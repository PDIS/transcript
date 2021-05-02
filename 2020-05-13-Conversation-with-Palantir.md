# 2020-05-13 Conversation with Palantir

### Matt:
Yes. Good to see you again. I think we’ve got everybody from my end and I’d be happy to kick this off if you’re ready.

### Audrey Tang:
Perfect.

### Matt:
Let me just run through the people on the line from Palantir. You’ve got an intercontinental team. I’ve got Barret Brown who heads our office in Tokyo. We’ve got Lauren Hurwitz who’s in London and led one of our projects in Taiwan a few years ago.

### Matt:
I’ve got John and Carolyn who are going to run the demonstration today, who are here in the United States. I’ve got Clark Minor, one of our lead engineers. He can answer all the technical, can go in whatever depth we need to go – I think is out in Seattle.

### Matt:
Then we’ve got Jonathan Hong on as well, one of our other engineers. I think that’s what we’ve got from our end. We are spanning the time zones from a Palantir perspective.

### Audrey Tang:
Still all on the same planet.

### Matt:
That’s correct. Just to give you a little background on Palantir – I’m not sure how familiar with our work you are. We started in about 2004, coming out of the 9/11 Commission Report, and all the information that was available to the US government that could have stopped the 9/11 attacks was all available, but you just couldn’t put it all together.

### Matt:
Obviously, the founders of the company came out of PayPal and a number of other areas, and had taken the sorts of technologies they developed there to do fraud alerts and felt that that could be applied to a series of problems.

### Matt:
Fast-forward a number of years, and we now observe the United States and a number of its allies as well as companies that span the United States and allies of the United States and provide those services across the government and commercial spectrum.

### Matt:
Obviously, with the pandemic that began just a few months ago obviously, we kicked off efforts to be able to provide services pro bono to public institutions.

### Matt:
As we started with tracking the pandemic, we quickly added in things like tracking the supply chains of personal protective equipment, of critical medical equipment all the way back through suppliers so that we understood the full supply chain to be able to provide information on where we would need to send things.

### Matt:
As hotspots pop up, with the information we’re getting from manufacturers directly off their production lines to figure out where things should go or just where they’re needed. That work has then led to I think what we’re going to show you today, is that next stage.

### Matt:
How do companies and governments begin to think about adapting to the new situation that we find ourselves coming out of the pandemic? As global supply chain shifts, as operations have to adjust to various openings and closures, and fundamentally, the world is adapting to some new geopolitical realities, how do we help provide all of that? That’s what we’re going to show you.

### Matt:
I want to get that started and then we’ll kick it over to take questions, but feel free to interrupt anytime on our way through. John and Carolyn, I’m going to turn over to you. I’m going to go to mute and let you kick it off. First, Minister, if you’ve got any upfront questions, happy to field those before we get started.

### Audrey Tang:
No problem. Just one quick clarification. Jill may have informed you that we’ll make a transcript out of this conversation and you can edit away the parts that are confidential by law, but we do publish the transcript after 10 days co-editing. I hope that is OK with you.

### Matt:
Yeah, we’ll take a look through. I’ll make sure that we are editing out those things that would be proprietary to be able to do that. Thank you.

### Audrey Tang:
Sure. Yeah. Go ahead.

### Carolyn Mulher:
Are you able to hear me and see my screen?

### Matt:
Yes.

### Carolyn Mulher:
Great. Yeah, like Matt said, we started off at Palantir’s COVID response in the United States. It has now expanded to over 30 countries. The first couple things we started looking at were, how can I allocate resources such as medical equipment, say, gloves, masks, ventilators to where they’re most needed.

### Carolyn Mulher:
The second thing we looked at was tracking and understanding the virus through integrating open source data with the epidemiology models and regulator events, how can I understand what the virus looks like in my country and what different policy decisions are being made to help impact the spread?

### Carolyn Mulher:
These are the main things I want to walk you through today. First, we’re looking at what is my common operating picture across the globe of the current pandemic. Second, what are the policy decisions in place, and have those policy decisions impacted the projection of the disease going forward?

### Carolyn Mulher:
Lastly, how do I proactively allocate that equipment in my supply chain? The goal of this session is to show you how we’ve used together all these different data sources to give you a living, breathing data asset of what’s going on and what you can find about it.

### Carolyn Mulher:
Let’s start by taking a look at our global common operating picture. Please, as I go through this, feel through to jump in and say, “That’s interesting. Can you show me more about that?” as there’s some additional news and data that I can go into a bit more detail if it’s interesting to you.

### Carolyn Mulher:
Currently, we’re taking a look at the global pandemic one-stop shop where we have a comprehensive understanding of what’s happening in the world. Members of government on a national, regional, state, county, as well as commercial business partners, all have the same understanding of what’s happening across the globe.

### Carolyn Mulher:
Here you can dive into specific things, such as what are total death counts throughout different countries, things like what is my case’s growth rate to see potentially where the next hotspot could be. These metrics are pulled from open source data assets so that you have a picture of the whole world in one.

### Carolyn Mulher:
We can go ahead and drill into a specific region or specific state. In this example, I’m going to go ahead and drill into the US. We have granular level county data. For right now, let’s go ahead and look at a state. I’m going to go ahead and show you guys the State of California.

### Carolyn Mulher:
From this map I can see initially, it doesn’t look like California’s necessarily the worse affected state. Maybe there’s a couple others, New York, New Jersey, may be more severe. I’m particularly interested in this one, so I can do a bit of a deep dive.

### Carolyn Mulher:
I’m going to switch views because I opened this one on my WiFi a bit earlier. When I go into that California-specific view, I had some of those COVID metrics we’ve seen about cases, potentially the population, and getting a general picture of what’s going on.

### Carolyn Mulher:
I’m able to overlay this with actually that policy information about do I have things like a shelter-in-place already in this region, do I have all my non-essential businesses opened or closed. I can see how those policy decisions have been made over time and how the cases and some of those metrics around growth have also changed as my policy decision’s been changed.

### Carolyn Mulher:
This is quite helpful for giving us that picture of what’s happening on a regulator level. We also have here a couple other things around how has this progressed over time. Within these specific pockets, how many cases are developing, where do I think may be the most hours placed in my stay next.

### Carolyn Mulher:
Once I have this view of where are my cases growing across my state and what policies do I have in place. My next question is going to be how are my hospitals able to respond to this. I can drill into my hospitals a bit more and see how they’re being utilized. This here gives us a picture of what’s the bed utilization rate across my hospitals in California.

### Carolyn Mulher:
I do see different hospital types. I may only want to look at hospitals that have intensive care units rather than potentially a children’s hospital or psychiatric hospitals. I can then see what their utilization rate currently is.

### Carolyn Mulher:
This goes in line with that what’s my current state in the world, what’s the current status in my state, how severe is the pandemic in my state. Once I have that current understanding picture, I can then also take a look at what I think projections will be in the next couple of weeks.

### Carolyn Mulher:
What we’ve done is we’ve integrated open source data around the IHME projections. IHME is an International Health Metric Evaluation. It’s one of the models for the disease curve.

### Carolyn Mulher:
You could actually go ahead and substitute a different model in here, or if you have a group of analysts that actually have their own models, you can plug that in here and just have an overview on the same type of metrics.

### Carolyn Mulher:
Now that I have an understanding in my hospital capacity now, what’s my projected hospitalizations over the next couple of weeks, what’s my projected bed demand, and do I think I’ll be able to meet this need?

### Carolyn Mulher:
This is quite helpful when you’re thinking about it from a policy or from a supply chain perspective. It tells you based on the data you have so far, “This is what you can expect to see in the next couple of weeks.”

### Carolyn Mulher:
I’m going to pivot away from this for a couple of minutes to tell you guys a bit more details about the data model that faxes we’ve looked at so far. Peeling back the layers of the data that we’ve just looked at, we now have a new of we call a monocle.

### Carolyn Mulher:
This shows us over 200 different data sources that have been grouped all together to give us some of those slices and dices in granular level data we just walked through.

### Carolyn Mulher:
What I’m showing you here is essentially these nodes are different data sources. I’ll zoom in on one so you can see it. Here you’ll see there’s one called government restriction. That’s one of those things we looked at before where it was a stay-at-home order in California, for example.

### Carolyn Mulher:
That’s some of the open source data we have about COVID-19 and how policies are responding here. We then overlaid this with those IHME projections, information about hospital capacity, information about country capacity, things like this.

### Carolyn Mulher:
That’s what you’re seeing here in all these different layers. Once you go through the processes integrating these layers of data, you end up all the way on the right side of this graph.

### Carolyn Mulher:
The right side of this graph shows you things like state, like we just looked at California, you have a similar group of country or counties. Then it also shows you a hospital view. These views are a comprehensive picture on an individual level.

### Carolyn Mulher:
What I mean by that is you have a comprehensive picture on the State of California using all that data from the left-hand side. This is quite comprehensive and is meant to just give you guys an understanding of what’s the data that goes into this.

### Carolyn Mulher:
It’s clearly being mapped together, and then coming all together at the end to give you a picture of California or give you a picture of a particular hospital. The reason this is so impactful is because those different layers can essentially just continue to be layered and layered and layered.

### Carolyn Mulher:
One thing we’ve added in is leaving economic indicators for instance. In a lot of our commercial partners, we’ve gone ahead and integrated with our SAP systems.

### Carolyn Mulher:
Now we have things like plants, customer, factories, sales order data, so that they’re able to also get an understanding of their current business needs. This essentially, what I wanted to show you guys, is these different layers and how they come together to allow you to draw insights.

### Carolyn Mulher:
There’s a couple different avenues you can go about looking at those insights once we have this base understanding. One of those is how we view our supply chain. I’m pivoting to a different supply chain view.

### Carolyn Mulher:
This, in particular, we’re looking at that problem we saw earlier where we had different hospital bed utilization rates. Some hospitals were at higher capacity of utilization already.

### Carolyn Mulher:
We saw that our projections for hospitals were actually coming up quite high. Now I want to see do my hospitals have all of the equipment they need. PPE is essential protected medical equipment.

### Carolyn Mulher:
It’s things like masks and gloves. I’m going to zoom in a little bit so you guys can see what’s on this map. On the left-hand side what you have is a supplier. Then you have the material that the supplier is producing for you. Then you have a distribution network.

### Carolyn Mulher:
At the end you have a particular hospital, or for commercial partners just can be substituted for their plants. As you look at this supply chain over time, you can see how it evolves and you can get alerted when there’s problems.

### Carolyn Mulher:
If I go ahead and view the latest information about my supply chain, you’ll notice I get a lot of red alerts, indicating that there’s a problem in my distribution network. Let’s go ahead and look at my original raw material sourcer.

### Carolyn Mulher:
I see that there’s a regulator event here around exports that’s causing a problem in the rest of my supply chain. I then see, “OK, where does this flow through to?” I see there’s a problem particularly in my Anchorage hospitals but not necessarily in all other hospitals.

### Carolyn Mulher:
Once we have this level understanding about our data we’re able to make essentially intelligent connections on these different nodes. It’s relatively simple to say, “I know that my hospital in Anchorage is shipped to from these different locations and somehow I can trace that back.”

### Carolyn Mulher:
We’re able to have that layer of intelligence on top of this showing us when there’s a problem in the supply chain. Once we have that understanding, we can then go into an allocation workflow where we say, “Let’s re-allocate our supply chain to meet our needs.”

### Carolyn Mulher:
I’m going to pivot views again and show you guys one way that you could use this layer of data to make an actionable outcome. You would have over here – I don’t know what specifically yet – in this case it’s factories. It’s the same as hospitals essentially if you think about it in this way.

### Carolyn Mulher:
I want to look at Anchorage. I know they’re going to need to get more masks. What are my options for doing that? I have options to redistribute my inventory from another place.

### Carolyn Mulher:
I could say, “New Jersey, I know hasn’t been as badly as affected based on the data I saw before. I’m going to go ahead and distribute some of my masks from New Jersey up to Anchorage, or I can change a shipment that’s headed towards that Jersey City and re-allocate it towards the Anchorage.”

### Carolyn Mulher:
These are two examples of what you could do with that data model that we’ve looked at in the beginning. I can walk you guys through a bit more about some of the economic indicators, what this could look like for plants as well as sales if that’s what you’re interested in.

### Carolyn Mulher:
Yeah, I wanted to pause and give you guys a chance to ask questions about those different steps we’ve walked through. It’s a lot of information, but essentially, the main thing is, again, I had this understanding.

### Carolyn Mulher:
I can see what my current risk areas are, if it’s a hospital, if it’s a certain region, country, or city at risk. Then I can go ahead and reallocate my supply chain or potentially add policy decisions to help mitigate that risk.

### Audrey Tang:
Thank you. That was great demonstration. In the view that you just had, while there’s a history slider, I noticed that there’s a few time points where it says missing data on top. That’s next to settings. What does that mean? It means that it’s running off old data?

### Carolyn Mulher:
Exactly. It could be without data, or it could be, for instance, we don’t actually have any, in this case, masks that are estimated to be delivered to the headquarters at that time. This is where you could either be alerted that, “Hey, they haven’t updated your shipments,” or that you actually have a problem in your shipments.

### Audrey Tang:
Right. That means that that red point in the sales distribution center and so on are actually numbers from three months ago.

### Carolyn Mulher:
Exactly.

### Audrey Tang:
Thank you. That clarifies the understanding. Also, the previous tab has a…Let’s look at this one. The model has a very convenient branch and fork buttons on top, meaning perhaps that this is all version-controlled, and this is merely a view.

### Audrey Tang:
That you don’t do your normal editing here, that it is basically coded from the back end. This is just a visualization where you can lay out it differently in each branch. You can easily compare between branches, but it’s not like you can click edit and drop into Visual Studio code, as GitHub is doing now. This is not an editor.

### Clark Minor:
It does. There is a built-in IDE inside of the browser. All of the data is branched with the code, so we branch data like code. We have Git repositories. You can hook into your IDE, clone, get repos. All of these transformation here are associated with Git repositories.

### Audrey Tang:
Right. Basically, you use Git to version-control all the data, regardless of their data type, schema, and things like that, right?

### Clark Minor:
Yes.

### Carolyn Mulher:
Yeah.

### Clark Minor:
The branching is like a fundamental construct of the platform itself. Is that relocated? It is what allows multiple people to collaborate and build up this shared data asset. Everyone has their own personal sandbox for doing whatever modification in testing they need to do.

### Audrey Tang:
This is a workbench, I understand that. The metadata diversioning, things like that, are all kind of a descriptive file in the Git repository for each data, and you refresh that whenever you check in new imported sorts of data. It’s something like a data package.

### Clark Minor:
Yep, and it’s all back to the other key thing here is that every piece of work and every transformation, every new dashboard analysis, anything you do in the platform, the lineage of that is tracked automatically. That allows you to do a couple of interesting things.

### Clark Minor:
The most important is that the security follows the data itself. When you combine data and provide different views, the resulting views are granularly access-controlled automatically, based on the originating data sources. It tracks it throughout all the different types of views in the platform, from the executive dashboard to the data modeling suites as well.

### Audrey Tang:
So it’s a dual of the access control list kind of security. This is actually associated with data. I see that. In the legend, what does Object Type mean? There’s Fusion Sync and things like that. What does that…

### Carolyn Mulher:
This is just right now we’re looking at like which things were essentially like high transference or coded transference, which is an object. An object is like what we saw here when we looked at California. We have this concept of a state is an object. Then you have an individual one is California.

### Audrey Tang:
So you manage your own data pipelines here.

### Carolyn Mulher:
Exactly.

### Clark Minor:
Yeah.

### Audrey Tang:
OK, that’s all I need to know. Thank you. Please go on.

### Carolyn Mulher:
Sure, OK. Another thing that we noticed with a lot of our commercial partners is that they’re very interested in understanding different economic factors. A lot of our government clients have noticed I’m more interested in potentially the growth of the disease and things like this.

### Carolyn Mulher:
A lot of our manufacturing clients, it’s a big deal which states are reopening? Which ones are going back to work and which ones are not? So we’ve also layered in a couple of economic indicators.

### Carolyn Mulher:
For example, you can look at estimated drop in retail sales year over year and see, OK, it looks like Georgia is actually being severely affected from this retail sales change.

### Carolyn Mulher:
We can go ahead and layer this in with some of that SAP data from our specific company. For example, you can layer it in with sales, things like this, and create a bit more business-specific view. I’m going to ahead and transfer over to a bit more business specific view.

### Carolyn Mulher:
Now I’m looking at a particular manufacturing company, in this case for this demo, it’s an automotive manufacturer. I’m looking at their Delta Lost Revenue in sales.

### Carolyn Mulher:
What are my sales this year versus what I had last year, and which states are most effective? This gives us a more business specific view of where I thought I was going to be and where I actually am at this point in the year.

### Carolyn Mulher:
You could go ahead and drill down just to specific product lines, which often have white different distributions, and in this case, you’ve noticed, it looks like New Jersey is particularly affected by this Delta Lost in revenue.

### Carolyn Mulher:
You can drill in a bit further to say why might that be? Is it because customer demand is dropping off? Is it because there’s a problem in my supply chain that I’m not actually able to meet all of the demand that’s even coming in?

### Carolyn Mulher:
In this case, we have a view that we have an open order back on of over $200,000. That means that those orders that have been placed to my specific company have not actually been fulfilled in this time.

### Carolyn Mulher:
I have things going back through March and April that are still open that signals a specific problem in my supply chain. I can also check out my customer demand and see it’s really just hollering-off. Once we have that understanding of what is my business picture for the rest of the year, we can go ahead and also change our demand forecasting.

### Carolyn Mulher:
We can go through a demand forecasting exercise where we check out what is the model of disease progression. I think most, it’s the future. Then look at what is my lost demand versus what is obviously expected through the rest of the year? I won’t go too much into detail on this.

### Carolyn Mulher:
Essentially, this is a workflow where you can go through and say, “OK, I believe that my market will recover by 80 percent. I believe this will happen towards the end of the year or maybe it’s even into next year, and then when I have a picture of what I think my model will actually look like for the rest of the year, I can go ahead and submit it to the rest of my team.”

### Carolyn Mulher:
When I submit this to the rest of my team, I offer them a chance to critique what I’m planning for the rest of the year and give feedback on it. This is meant as a collaboration space to say, “OK, these are kind of the different forecasts for the rest of the year. Do we think this is realistic? Can I come back a month from now and see what scenario I’ve submitted and see if this is actually going to be the case?”

### Carolyn Mulher:
Once you have this view, you can see reallocation workflows. It’s essentially, this demand forecasting, some of that allocation work is like a Lego block that you could substitute in depending on if you want to be looking at plant and distribution, whether it’s sales per plant or hospital utilization lake. You can plug and play some of those different operational workflows once you have that base data asset.

### Audrey Tang:
That’s very clear. Thank you.

### Matt:
Lauren, or Carolyn, or John, do you have anything else you wanted to add?

### John DiFulvio:
No. There’s a lot more depth we could go in any of the topics. If there’s any specific questions, then we can answer questions, or find out from here.

### Matt:
Yup.

### Audrey Tang:
The epidemiological models that you mentioned that I can toggle and plug it in, have you actually done that? If you have, is there some place that I can look at one of the source of the alternative model or your current model? I don’t really need this back and forth field. I just want to take a quick look at what the model looks like.

### John DiFulvio:
Yes. We have the CHIME model, IHME, and LEMA models, all integrated into the stat piece. We are not epidemiologists. Our view, instead of using them for demoware, it’s, is there a specific application that we can expose these models?

### John DiFulvio:
Palantir takes a very pragmatic view on we don’t want to advocate or recommend any of the individual models. What we’ve been doing is we show IHME because it’s the most public.

### John DiFulvio:
Then, if there’s a need from both our government or commercial partners, we expose the rest of the models as well. The reason is the LEMA model, for instance, is out of Wash University in Missouri, and it requires actually quite a bit of knowledge of transmissibility, of epidemiology models in general.

### John DiFulvio:
If there’s a need, if there’s an understanding, we expose it. That’s our view on the different models.

### Audrey Tang:
A very quick test. In many models, there’s a factor that says, “If the temperature grows between the lowest and the highest, then the R0 value is decreased by, say, 0.05.” That’s just an example.

### Audrey Tang:
Where would that lie in your database? Do you have your own temperature forecast fit into it, or you just integrate it into one of the views of the models? How does that work with different counties, because they all have different temperatures as well as part of weather forecast? I choose this example because this has the least number of variables.

### John DiFulvio:
That’s a good question. We don’t have any transmissibility forecast built. We don’t have any temperature forecast currently in the platform. Actually, as of now, that hasn’t come up yet in some of the public or commercial work. We leave some of that to the JG modelers from our USG work. They do that in their own instance.

### John DiFulvio:
We would just work with you. All of it as possible. If you wanted to do an actual transmissibility forecast in Foundry as opposed to just using an R0 value, we can do that. We would leave that up to you, your teams, your healthcare…

### Audrey Tang:
For us, we’re in a very different situation. There is zero community transmission for the past months now. Our economists pretty much agree \[laughs\] on the trajectory. There really is very little competing models of what’s going on. The question we’re asking at this moment is not the same questions as this dashboard is answering.

### Audrey Tang:
The question we’re asking is, let’s just take one example, the summer gets hotter. People do not want to wear medical masks all day, especially outdoors. We do have our social distancing rules, but people follow that even more than we anticipated. They do wear a mask even outdoors and even when keeping social distance.

### Audrey Tang:
The question we want to ask the data is, for example, given the hand sanitation level, given that you can deduce from water use, for example, and things like that. With the baseline that we have now, and you can see that baseline of R0 value proxied from the flu and things like that, and see how that works.

### Audrey Tang:
Why would we, for example, try telling people when you’re outdoors and you’re keeping reasonable social distance as shown by, say, the telecom’s aggregate data of people clustering of average density, places with low average density where people can conceivably keep one meters apart? What if we just emphasize that people don’t have to wear a mask anymore? How will that affect the R0 value?

### Audrey Tang:
That’s one very specific question that if we had all the data workbench, we would be working on right now. We don’t. We’re relying on epidemiologists’ models on non-COVID values, such as the flu, which we do have data. That’s a moderately good proxy.

### Audrey Tang:
If we can plug in the predictive model from the practical, not RCT anymore, pragmatic trials from the UK, then we can just augment the existing flu models with observed data after this policy change, maybe on a smaller area first, and then see how that affects our baseline.

### Audrey Tang:
Because at the end of the day, the idea is that maybe we have some R budget that we can use, but without increasing the R to above one. This is a slightly more complicated example, but still very minimal. We are \[laughs\] working with many other questions that involves more variables than this. That’s just one small example.

### John DiFulvio:
We aren’t quite there in terms of those studies. Obviously, with the with the correct data integration, Foundry can help with that type of problems.

### John DiFulvio:
What we are doing that’s in a similar vein, instead of using that comparison with flu-like symptoms and then understanding as people go outside during the summer months, if transmissibility decreases, what does that do to the model? Can we change our policy decisions based on what we see? That’s exactly what Foundry is meant to answer.

### John DiFulvio:
Here’s an example from an economic standpoint. It basically does the same thing that you said, but it’s from an economic standpoint. Here, these different industries come from credit card transaction and sales data across the United States.

### John DiFulvio:
Credit card transaction and sales data should be one of the leading indicators that you have for economic recovery. What we’ve done is, as I’m sure you’re aware, different states across the country have been reopening at different times.

### John DiFulvio:
What we do is a similar study to what you talked about, and instead of a healthcare perspective but the parallels are there, is saying, “Texas and Georgia have actually already reopened. What does their recovery look like? Can we use that to understand what it could look like in states like Michigan, for instance? States that haven’t reopened yet?”

### John DiFulvio:
You can think about from your perspective, if there’s different locales, different regions across the country, it’s, “Can I use some of that information?” Just like you mentioned, where the population densities are different. There’s different social distancing practices.

### John DiFulvio:
It’s using all of that information very, very rapidly, to make the best projections, make the best policy decisions going forward. The idea is we fully expect that a lot of…We just saw in South Korea, where they had been reopened. Very recently, over the weekend, they reclosed restaurants and bars based on a new outbreak.

### John DiFulvio:
The goal is having a platform like Foundry allows you to take action very, very rapidly because you can see some of those changes and then integrate it into decision workflows. That’s what we want to empower. It’s basically everything we talked about, making sure it’s all integrated in one place, so we can see the real-time impact as things happen.

### Audrey Tang:
Thank you. This view, which is really good, it’s like a executive summary. Do you have something like a published mode, in a sense, for non-data scientists to work with? What I mean is that instead of a full workbench for professionals and so on, if we are going to translate this into public communication material or interactibles, I’m not even sure that’s a word. \[laughs\]

### Audrey Tang:
Basically, a interactive sandbox for the general population to experiment, because part of the Taiwan model is that each predictive model, our Vice President, the person who wrote literally the epidemiology textbook, record MOOCs and teaches the entire population epidemiology.

### Audrey Tang:
There’s a lot of YouTubers, professional communicators that could really benefit from interactibles that they can then weave into their storytelling materials. Everybody can check for themselves, adjusting a few sliders here and there, without going into the Python transformations. Is there a storytelling mode of this?

### John DiFulvio:
\[laughs\] Excellent question. On the left-hand side, there’s lots of different applications that come out of the box with Foundry. What Carolyn showed you at the beginning was this view, like you talked about the workbench, I can see the actual code. When it comes to the dashboards, this is actually built in what’s called slate.

### John DiFulvio:
The Object Explorer views are also a point-and-click report, which then makes it very, very easy to consume information. None of those things require anybody using them to have a knowledge of SQL, Python, or anything. It’s just point and click, they can change the filters directly. Yes, absolutely, that’s available in Foundry.

### Audrey Tang:
When I decide to publish this, do I just give everybody, every citizen a link to palantirfoundry.com? \[laughs\] Or, should I export it into some other format?

### John DiFulvio:
It’s a good question. Clark, you can jump in as well. If you’d like to onboard people to the platform, that’s definitely possible. For instance, with the US government, we’re onboarding not only the federal teams, but a lot of states teams as well. Those are still government people who are accessing the platform. It’s growing very rapidly to hundreds and thousands of users.

### John DiFulvio:
There’s also print to PDF. You can do PowerPoint. You don’t have to give everybody a link to Palantir. You can just do the PDF version as well. It’s definitely possible to expose these…

### Audrey Tang:
I’m not sure that your silver’s in PDF scripting that you can do these drill-downs and sliding the PDF.

### Audrey Tang:
It’s technically possible. I’ve done a few of those. \[laughs\] I’m not sure it’s the best use of your time, in any case. What we’re looking at specifically is to give people the knowledge model that they can adapt to their local situations.

### Audrey Tang:
What Taiwan have been doing consistently is, for example, our PPE availability map. The raw data is published every 30 seconds at that time. Now every three minutes, so that all the application makers, including voice assistants, like literally in Taiwan, if you ask Siri where the mask is, it will actually tell you \[laughs\] the nearest pharmacy that has the mask in stock.

### Audrey Tang:
To enable that integration with the civic technologists that are now, I don’t know, they have users, the numbers to half the population, so they’re also civil engineers now. \[laughs\] These civic tech/civil engineering projects, it’s essential that all data in the pipeline, we publish also our on open data platform so they can reproduce this result without using any proprietary technology.

### Audrey Tang:
Proprietary technology is also very useful because it informs with no coding abilities a very easy interaction view. I really do also think that your platform, at this stage and from what I see, is designed to have 10 million people using it every day. \[laughs\] It may not be the best kind of workbench.

### Audrey Tang:
Unless you have, like in Google Docs, they have a view mode, or Google Spreadsheet, they have a view mode, that if you click Publish, it takes a static snapshot along with all the data associated with it. You can still toggle between predefined views and slide a little bit if I’m talking about Google Spreadsheet.

### Audrey Tang:
That does not consume their CPU that much, because all the computation is done in client-side JavaScript. For that view, that’s going to be the best of both worlds, because it’s backed by real data that people can verify by their own if they want, but most people don’t. \[laughs\] Still, it’s interactive and explains how the data modelers think.

### Audrey Tang:
This is just like our Minister of Health and Welfare, also our CECC commander, offering free courses to the journalists on epidemiology \[laughs\] so that they can talk on the same terms and contribute to knowledge finding.

### Audrey Tang:
This citizen empowerment angle, I’m not sure if any other jurisdictions have asked you that, maybe Korea, but I’m sure that you’ve been thinking along these ways as well. I just want to know what the current offers are.

### Clark Minor:
There’s a variety of ways that we could do something like that. In one country, for example, you see on the side here, one of the tabs is Data Connection. We have robust ability to integrate with third-party systems as well. They use it to power their websites. We do a similar thing for a map in other countries that goes to all of their truckers for road conditions relating to this.

### Clark Minor:
In another country, we have emails that go out to all the different hospitals, where they’re able to report data directly from the hospitals into the platform. There’s a variety of different ways to restrict access to people that may want to just look at a report or have a couple widgets that you can toggle.

### Clark Minor:
For example, the Reports tool does have a View mode, as well as an Edit mode. You parameterize a report, and then you can allow people to toggle with just a couple of different things. It’s pretty flexible in that way.

### Clark Minor:
It is hooked up to a lot of external systems, because the data asset itself alone is very powerful, just bringing together so many disparate sources and keeping them all up to date. It’s used to power external views as well.

### Audrey Tang:
Did I hear correctly that you’re offering to other countries CECCs and CDCs, all of those pro bono, including your professional services and hours? \[laughs\] Is it entirely humanitarian package? Or, did I miss something?

### Barret Brown:
That’s right. Essentially, we collaborated with AWS. If you’re looking for a hosted instance, which I assume you are, in this case, then we can give an initial version of a lot of the workflows that you saw, very, very fast, connect up to date, or use the open source data along with the data that you have already that we don’t have integrated to get started very quickly and provide…

### Barret Brown:
Yes, we will have our engineers support and standing up the instance, getting all the data, and helping you configure the workflows.

### Audrey Tang:
Thank you for the offer. Just yesterday, we closed off the submission of the hackathon called Cohack. It’s at cohack.tw. We’re now reviewing the data-driven communications, which is the six of the six areas, but also many other including the PPE distribution and things like that.

### Audrey Tang:
What we will do then is, first, among the six categories, we’ll announce three, five, or six winners. Initially, they only get a laser engraved from the US and Taiwan, these are the joint statements in a modern rice cooker that they can use to revitalize their PPE. There’s a recent Stanford paper on that. In any case, \[laughs\] it’s purely symbolic.

### Audrey Tang:
The part of the prize is our promise to implement their ideas into the decision-making workflow of our CECC. What we’ve seen from the incoming submissions is that many of those cases, whereas they have really great solutions, they use primarily open source data. One of the eligibility criteria is their code must be MIT-licensed as well, so it can be used internationally.

### Audrey Tang:
What we’ve seen is that they are solving problems, except for the post-corona team category, everything else is on the places where Taiwan is not very much needed anymore. For example, our partnering other bilateral epicenters are still needing it a lot. That creates an incentive for our researchers.

### Audrey Tang:
For example, our AI Labs, social sector, nonprofits, they’re working at a Bluetooth tracing app thing that has a better incentive design. The Taiwan people don’t need to use it now — hopefully never.

### Audrey Tang:
Now they’re offering their source code to the UK. Because it’s open source both in terms of open source intelligence, open source code, it transfers much more easily.

### Audrey Tang:
Just as you said, they can just choose a AWS instance and spin it up. The AI Labs doesn’t need to know whether UK government changes the code to fit their needs. We will probably soon see a few winning cases from the Cohack Hackathon. Many of them will probably want some communication material that I just alluded to of the interactibles from your Foundry platform.

### Audrey Tang:
For their ideas to actually work in jurisdictions other than Taiwan, they will also need a orange-to-orange way to integrate their data pipelines. If you’re willing to work with these essential international champions, \[laughs\] we can, of course, offer your service as something that’s value-added to the traditional rice cookers \[laughs\] for the winning teams. That’s perhaps the easiest.

### Audrey Tang:
At the moment, what I’ve seen is really impressive. I’ll probably have to personally use it to build a few models, to actually work out the rough edges of that platform and see how it fits. So far, it looks like really powerful. Thank you very much for an offer.

### Barret Brown:
That’s fantastic. Thank you.

### Matt:
Thank you. I don’t know if Barret, you had anything else to add on the last sets of ideas there. You can certainly get back with your team and talk some of those things through. Just over to you, Barret, real quick.

### Barret Brown:
Sure. As you know, were doing this in lots of countries around the world. Lauren knows more about it than I do. I just know Asia. Essentially, the goal is to help people as fast as possible.

### Barret Brown:
As you mentioned, Taiwan is in an amazing place compared to everyone else on this. If there’s something that is important to Taiwan in this regard that is related to COVID response, then we should certainly talk about how we can get you using the platform.

### Audrey Tang:
Awesome. Thank you. That’s all from me. Joel, do the Foreign Service \[laughs\] have anything to remind us of? You’re good? OK. That’s pretty much it. I’ll just see if the transcript works well. The AI is getting very good at this. We mentioned quite a lot of domain-specific words. \[laughs\] Just give us a while to edit that. I really learned a lot. Thank you so much for this conversation.

### Matt:
Thank you. I really appreciate it. Joel, there were a couple of things that we mentioned up front that I’ll just need to make sure that we’re…

### Audrey Tang:
Sure, of course.

### Audrey Tang:
MOFA, the Foreign Service is actually the entity that runs along with the de facto embassy of US in Taiwan, AIT, the Cohack Hackathon. Joel is part of all this. How Cohack may connect to your platform, Joel is the go-to person.

### Matt:
Perfect. Thank you so much for your time. I really appreciate it. Have a great day. Absolutely, congratulations, Taiwan, on all the great works that you guys have been doing. It’s really impressive. Thank you so much.

### Audrey Tang:
Thank you.

### Barret Brown:
Thank you.

### Audrey Tang:
Thank you. Have a good local time, everyone. Thank you. Cheers.

> (laughter)

### Matt:
Thank you. Bye-bye.

### Audrey Tang:
Bye.

### Barret Brown:
Bye.

### Carolyn Mulher:
Thank you. Bye.

### Audrey Tang:
Bye.

