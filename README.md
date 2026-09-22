# Agenda 
1. ChatGPT
2. Copilot (VsCode)
3. Claude code
4. Data Centers / Slop / Mush
5. Programmer Escape Velocity

# Script
### Subscriptions
Hello! Before we begin I will be using two subscriptions throughout this lecture.
🟠 The first I will be using it GitHub Copilot which can be gotten for free by making a free GitHub account and activating the student plan. You can go to [github.com/education/students](https://github.com/education/students) to activate this. 

🟠The second one is codex through ChatGPT pro. You can get four months for free but you do need to input a debit or credit card for this to work and you will be charged after having it for four months, just a warning

I had to submit my Student ID, visual schedule builder, and this semesters bills for this one to actually activate. Although, I will say it activated instantly so maybe it just wanted to see how persistent I was.

But you can try and get these working while the lesson goes on as I will probably start using these about 25% through the lesson today, so you have some time

The link for this one will also be sent in the lesson discord channel. So go here to get students discount to unlock Codex : [link](https://chatgpt.com/students/2026/)  

Also, if you literally have any technical problems, point directly at the ceiling!!! This will alert our beloved HacKSU officers that you are experiencing an issue! I promise this will not interrupt the lesson, the only reason I am up here is to help you understand computer science better. 

### Questions
Who here has heard of Artificial Intelligence? ` I raise my hand too `

Who here believes that AI can be useful? ` I raise my hand too `
`then call out somebody that didn't raise their hand and ask them why they believe AI can't be useful`

Who here sometimes gets uncomfortable by AI or AI makes you a bit nervous or the way others may use it makes you nervous? ` I raise my hand too `

### Intro
Okay, I just wanted to make sure we were all on the same page in that we all understand that AI can be useful but we also all understand that AI is kind of scary.

AI is really difficult to make and really easy to use. But I think using it responsibly is the most important thing I can teach you, as there isn't exactly a warning label on this stuff.

But before we get to any of that, we have to understand how we got here. Now history began when Sam Altman was born.

### A Brief History
🟠 Samuel Harris Altman is born on April 22nd, 1985. And he looks to his mother and says, "I, Samuel Harris Altman in 30 years, I am going to create an AI startup that will take over the world".

And then, respect to him, he did just that. 
🟠So OpenAI is co-founded by Sammy bears on December 8th, 2015 and Sammy bears becomes CEO of the company in 2019. Then in on November 30th 2022, they launched ChatGPT. 

🟠Then in January of 2023, they hit 100 million users. ([source](https://www.reuters.com/technology/chatgpt-sets-record-fastest-growing-user-base-analyst-note-2023-02-01/)) 
And, at the time I was in the second semester of my junior year of High School and I was watching everyone around me generate their essays in my language arts class. 

It was pretty decent but still pretty bad. Around this time people started to immediately discuss how nobody will ever work again. But luckily for us, in June of 2023, Sammy assured us that nobody would lose their jobs and people would just become more efficient. [source](https://ia.acs.org.au/article/2023/sam-altman--ai-won-t-take-all-our-jobs.html)

🟠And the data backed him up too. This is a graph of Software Development Job Postings on Indeed in the United States. [source](https://fred.stlouisfed.org/series/IHLIDXUSTPSOFTDEVE) 

Dang 100 million users, there must be something to this, we gotta learn how to use it!

---

### ChatGPT (January 2023)

Okay! So now lets go over ChatGPT.

`open chatgpt`

So now that we have Gippity open, we can ask it any question.

I will ask it "Tell me about CCN."
Then, I immediately made a mistake. I need to specify Computer Communication Networks.

So it is telling me about CCN and whatever, 
But then I just realized! I don't care at all about CCN! I only care about learning how to program C++, so I will make a new chat and ask away!

I will also switch the model to Medium as I find this is the best tradeoff for quality and speed. Then it will start chatting.

`Ask it like teach me about C++ and stuff like that`  

But what if I want to truly focus on C++. Like maybe learn C++ to excel in, some sort of course I might be taking? Well this is where I recommend making a project.

You can make a project by clicking here in the left sidebar `Name is Nesty's Dojo`  

Then in the project you can begin. Now I recommend this setup for learning stuff in project form. Start with the regular question. Make sure you do `@` web search to get an actually good response.

I honestly think the web search is the best innovation for these LLM's simply because of the fact that they can get real up to date data.

`ask it a question about how to learn C++ in the prompt and press send`

Now it will give me an output. And you can use this and read this and that will be all good but this just isn't enough. What I want it an actual learning experience, like a course if you will.

Now what I am going to do is paste in a message into the user prompt of the project. This will essentially, in really simple terms, just paste this before any prompt in my project. So if I say "are apples green, it say give me a guideline dot dot dot, are apples green" 
`copy and paste this code block into the system prompt of the project`
```
Give me a guideline to follow for a project system prompt for ChatGPT. This must be less than 8,000 characters. Use a script to verify it is actually less than 8,000 characters. 

Create an course outline to follow of all of the C++ topics I need to learn to go from knowing nothing to knowing everything I need as a student who worships at the altar of C++. Do online research to find the best course of action that aligns with the Kent State C++ standards and global standards for learning C++. 

This system prompt will tell the future ChatGPT to output following this structure. Lesson at the top then lab at the bottom. What I want you to do is give me a lab that I can complete in less than 7 minutes. This lab will explain everything I need to know about C++ at an intro level. The instructions must be included in the code block so that I can copy and paste it. Only move on to the next topic when I say so. You will also include a grade out of 5 at the top of the lab so I can verify where I have gone wrong. Make sure to have a lesson section at the top then a lab section at the bottom. The lab section at the bottom will always be output in a code block. Remember, the most important part of this prompt is that the lab section at the bottom is always output in a code block.

Return this entire system prompt for a ChatGPT project in a code block.
```

`Read this code block after you paste it in and submit it. Also paste it in the lesson chat for others to use.`

So now, when you speak in a chat in this project it will create you a lesson and lab to complete. Now don't be afraid to correct it on mistakes it makes in it's output. The project system type of prompt only will get you so far. Also, if you are learning something in class ask it to cover that as well.

`Show off my previous 7 Minute Drills project in VSCode.`
[link to 7 minute drills final page of commits](https://github.com/AndrewRoddy/7-Minute-Drills/commits/main/?after=999fc16039e2037003271d49a5948ce502195393+174)
I have been doing this method since September 23rd 2024, which will be two years ago tomorrow, so if you start using this to learn C++ in CS1, you will literally be exactly in my shoes. I have literally used this for so long to learn how to program and still use it today at work. I find this to be a very effective method for learning programming and probably one of the ways you can push these LLM's in the browser the furthest. 

Anyway, now lets try and do the lesson. 

Ask it to generate a first lab. `Then try and do the first lab.`
`do the lab`

`when done with the lab`
But yeah, this is about as complicated as the chatbots in the browser's get. But this is still a great learning tool if you are interested!

### Unemployment
🟠Anyway! So remember, we are still in January of 2023 and in about a year and a half, or two years ago from tomorrow, Andrew Roddy will use it to study hard for CS1.

🟠Enter : Nathaniel Dourif Friedman, born August 6, 1977 in Charlottesville, Virginia

🟠He is the current CEO of GitHub and in June of 2021 GitHub released their AI coding assistant tool called Copilot: [link](https://github.blog/news-insights/product-news/introducing-github-copilot-ai-pair-programmer/)
This little guy can do a lot but was basically just really good autocomplete, and was honestly just mostly annoying.

Anyway, that is just what it was in 2021, but in March of 2023, remember, only two months after ChatGPT hit 100 million users, 
🟠Copilot added a chat feature. ([source](https://techcrunch.com/2023/03/22/githubs-copilot-goes-beyond-code-completion-adds-a-chat-mode-and-more/))

And because of LLMs and AI, the job market was already not doing great
🟠 But this really didn't help. This basically allowed the user to tell the AI to code stuff and it, well coded it.

🟠Then later in September of 2023 this feature was rolled out to all individuals. ([source](https://github.blog/news-insights/product-news/github-copilot-chat-beta-now-available-for-all-individuals/)) 

🟠Then in October of 2023 the CEO of Microsoft announced that GitHub Copilot hit 1 million paid users. Not just users in general but people who are giving them money. 
([source](https://www.cnbc.com/2023/11/08/microsoft-launches-github-copilot-enterprise-to-help-with-private-code.html))

🟠And the job market, once again, responded accordingly.

Very cool, so AI can now code for you. So is Computer Science over? Have we solved it?
I don't know why any of us are here if we can just so easily ask the computer to code itself?

Well, that was the narrative. You *will* not get a job in computer science. In fact nobody is hiring! But nonono. Sam Altman assured us, no "You're not going to lose your job to an AI, but you're going to lose your job to someone who uses AI." [source](https://www.yahoo.com/news/openai-ceo-sam-altman-says-161828662.html?guccounter=1). So you gotta start learning now or you will be unemployed by tomorrow!

### Copilot (October 2023)

Alright! Lets go over Copilot! You don't want to end up unemployed do you?

So what we are going to do to install copilot is we are going to go to out extension section in VSCode. For you it will probably be like somewhere on the left here. Then we are going to search GitHub Copilot Chat, now you might already have this installed courtesy of Microsoft themself, I just had to click "Enable AI Features" for mine to work but yours might just ... well ... work.

Anyway, if we click in the bottom right it will either ask us to sign in or already be signed in for us.

Then, we will find this icon.

And I am just going to leave it on `Auto` for which LLM it selects because when I open the page to select an LLM it crashes ... so I am just not going to even touch it.

I am going to ask it...
```
Can you make me mario bros for NES in pygame? Just the first level :)
```

And then I am going to say
```
use uv please instead of pip
```

And then I am going to press allow a few times, now notice that there is now a keep or undo thingy at the bottom asking me if I would be open to approving or not approving the changes it is making.

Now also notice that I don't even have to look at the code.

But I will anyways. I mean the code looks fine. I would have broken it up a bit myself but overall its not terrible.

If I click the dropdown next to allow I can then set it to always allow anything it wants.

`Then play the game and commentate over it` 
1. `Check if you can change the screen width and height`
2. `Check things that shouldn't be checked`
3. `Then check how much usage it used to create the game`

`Then press keep the code`

But now lets read over the code.

So this is the state of Copilot in 2026 but it hasn't really changed since its massive popularity in October of 2023.

Now lets see what me, in 2023, was able to create. Eh, not as good, very laggy, very low framerate, and well, the graphics aren't the best, but ... lets look at the architecture.

If you wanted to modify where some of the blocks were on the map, you can very easily do so. And, honestly, this code sucks. That's why there are so many comments, but there are a lot of simple choices that I got to make when I created it.

And, now I know how to program in Python.

I made you look at the code. Looking at the code was NEVER a requirement. In fact, they recently added a feature to remove it.

Send:
```
Make the game btter. I want more koopas!
```

And I can just sit here, wasting my time while I wait for the AI to do stuff for me. I can press allow when it asks me yes, or disallow when it asks me no.

Okay, lets check out what it did!

So now, I am going to go back into VSCode and see what it did!

Wow! This looks amazing.

`Then play the game and commentate over it` 
1. `Check if it fixed:` `Check if you can change the screen width and height`
2. `Check things that shouldn't be checked`
3. `Then check how much usage it used to create the game`

So, that is how to use Copilot in VSCode, this is actually still a decent way to interact with an LLM in a coding environment. I personally wouldn't use this silly agents mode but if you do want to try and use AI to enhance your programming, this is the way to go.

### Claude (October 2023)

🟠This was Dario Amodei. And now 
🟠this is Dario Amodei, a higher quality looking man

Dario Amodei was born in 1983 in San Francisco. Him and his sister Daniela Amodei founded Anthropic on January 26th, 2021.

🟠They both used to work at OpenAI and decided that they did not like the direction the company was going in. Dario Amodei, Daniela Amodei, Jared Kaplan, Sam McCandlish, Tom Brown, Chris Olah, Jack Clark, and Ben Mann all used to work at OpenAI and all founded Anthropic.

But, they chose Dario Amodei to be the spokesperson and CEO. Anyway, their ChatGPT equivalent 
🟠is Claude.

🟠In November of 2023 Sam Altman said OpenAI should be ashamed if they aren't the first major company run by an AI CEO. [source](https://www.businessinsider.com/sam-altman-openai-ai-ceo-2025-11) 

🟠Confident, Sam Altman rested, knowing he has won the AI game, but just four years after those IDIOTS, left his company OpenAI, 

But then, rising from the ashes
🟠Dario Amodei peeked over the edge of what was possible using AI

🟠And on March 27th 2024 Claude surpassed ChatGPT on LMArena making it to the top LLM to beat. ([source](https://www.tomsguide.com/ai/claude-takes-the-top-spot-in-ai-chatbot-ranking-finally-knocking-gpt-4-down-to-second-place))

🟠Then in September of 2024 Sam Altman released a manifesto called "The Intelligence Age" where he said we could have superintelligence within the next few thousand days. [source](https://ia.samaltman.com/) 

🟠Then in October of 2024 Dario Amodei released a very long manifesto called "Machines Love Grace" where he said "the vitality of democracy depends on harnessing new technologies to improve democratic institutions" [source](https://darioamodei.com/essay/machines-of-loving-grace) 

And that the human lifespan will reach 150 and "Once the human lifespan is 150, we may be able to reach escape velocity" basically saying we will increase the average lifespan faster than we are living it

🟠 Then on February 24th 2025, Claude Code released to the public. [source](https://www.anthropic.com/news/claude-3-7-sonnet) 
🟠And our job graph, never, ever looked so rough, wow, what a beautiful sight

🟠After this in April of 2025 the OpenAI's Codex released and by May 16th they reached 100,000 downloads
🟠Then, Claude Code reached 1 million downloads. [source](https://github.com/AndrewRoddy/cli-tool-installs) 

🟠Then, on May 28th, 2025 Dario Amodei told Axios that AI could wipe out half of all entry-level white-collar jobs and the government needs to stop "sugar-coating" what will happen. [source](https://www.axios.com/2025/05/28/ai-jobs-white-collar-unemployment-anthropic) 

🟠Well geez, if half of white color jobs will be gone it looks like we need to learn how to use this AI to stay employed!!!

🟠Well good for us! We have the CLI tool right here for free courtesy of the student plan giving us 4 months!

### Codex / Claude Code (May 2025)

We will be learning the codex CLI for this lesson because I think that working in the command line with AI models is the most effective way to learn how to use them.

So if you do not already have the CLI tool installed you can input
```
npm install -g @openai/codex
```
to install it.

Also, as a reminder, there are a lot of people in the audience who are super good at helping others with computer problems so if you just point towards the sky, that will be a great way for me to know you aren't asking me a question and instead need help with the lesson.

So I am going to make a new directory using `mkdir` in my windows terminal, then I will type in `codex`.

Now, it defaults to `astra` which is a terrible idea if we want to do literally anything without hitting our usage limit. So instead what we are going to do is switch to `luna`. 

We are going to type `/model` and use the arrow keys to bring it down to `gpt-5.6-luna`, then press enter, then select `high` mode.

This is the one that seems the most efficient while using the least tokens.

So what I am going to do is have it make me a portfolio site using my LinkedIn. I am going to open my LinkedIn and scroll down, then I am going to copy only the information I need, then paste it all in. Now I also recommend
```
This is information from linkedin.com create a portfolio site for this individual. Make it simple static HTML. [paste stuff here]
```

And now it is going to start working. Now while that works and goes. I am going to open a new window to just go over the different commands you can do in codex.

We already saw the `/model` command. The next most important command is `/status` this one shows how much of your usage limit you have left. This is important because both claude code and openAi's codex have specific usage limits that you are given.

There is also the `/compact` command. The command is very important in managing context.

Context in an AI model is essentially the amount that the AI needs to remember. Basically, every single time the AI has to output information, it needs to re-read the entire chat before adding more or responding. So if you have been chatting for a while, it is actually in your best interest to have the LLM summarize the conversation, so it only has to re-read a summary before outputting more information.

ChatGPT and Claude on the web actually do the same thing just automatically. When you see the LLM "organizing its thoughts" or something similar it means it is silently compacting the chat history in the background.

My favorite command is actually not in codex, its when running codex. In the terminal if you type `codex resume --last` it resumes your last messages with it. This is very useful, as you will often find yourself just using only one conversation and just compacting it often.

Then rapid fire of some other commands is `/usage` for checking token usage activity over a long period of time, `/pets` for setting up a really cool pet, then also `/resume` to reopen an older chat without having to exit the current one.

```
--- when codex finishes ---
```

Okay so lets open our website to see what it has created for us to far! So if we open a new terminal window and `cd` into our directory. Then run `start index.html` we can open the website it built us.

`Look through the website and see if it is good or not or if it is bad`
1. `click links and see where it takes us`
2. `make fun of it because it will probably be bad`

Okay, so this needs to be better right?

Well one good way to improve things is to just add more AI right? 
So lets do just that.

I am going to re-run codex using `codex --yolo`, this will dangerously skip all permissions but could ruin everything and anything I can touch with my CLI is up to be destroyed. Good thing I have nothing to lose!!! Lets go!

I am going to ask it:
```
/goal keep going until I say stop: every 5 minutes spin off a subagent that will add a small feature. This subagent will think of the feature and complete and add it in less than 5 minutes. This feature can be anything you think will make the website look better or stand out. Make this website amazing and something everyone will want to see and the portfolio site of the ages.
```

So what `/goal` does is it keeps going until it is done and if I just tell it to never be done it will just keep going. I also asked it to use subagents, which is basically just it internally running another codex instance. This will also allow the subagents to keep working while it spins up the next task.

### Codex -> NGMI transition

I am just going to run this while the lesson goes on and we will check in on this at the end.

🟠Well, if you want to just sit there and press 'accept' every 10 minutes, that is fine by me ... but what if we didn't need someone to press accept, 

🟠what if it could just go forever on its own? Well that is what we just did ... so do we need developers anymore?

🟠Lets check in on those CS majors again! hmm

🟠What if these get so good that nobody is ever a programmer again and there is a finite set clock of time and when we finally achieve AGI or Artificial General Intelligence and it can iterate on itself forever and ever and create clones of itself forever and ever then the only people who will survive are the people who already built all of their wealth while it was being created?

🟠What if that happens, are we going to make it?

### NGMI (You are not going to make it) (about may 2026)

🟠NGMI, NGMI is a term said in silicon valley and San Francisco invented during the Crypto boom, 

🟠it was initially used as a term to describe different crypto coins, ones that are going to make it and ones that are Not Going To Make It aka NGMI. [source kinda](https://www.kraken.com/learn/what-is-wagmi-ngmi) 

🟠It has now been repurposed to describe people, I am now valued as a prospect like a crypto coin is valued on the blockchain. Some people are going to make it in the age of AI, and others ... are not.

🟠If you take a vacation day, you are NGMI, 
🟠if you stop building your massive startup, NGMI, 
🟠if you even think for half a second about something that isn't building your startup called Stinker, A Bathroom Locater And Review App, which will turn FAANG to FAANGS when you are done with it!!!, you are NGMI
🟠if you waiver for a second, you are NGMI.

🟠There are no jobs available and in the future there will be less. 
🟠We are all now just racing to make all of the money we can before somebody, inevitably, makes AGI.

### Somebody, inevitably, made AGI
🟠On September 3rd, 2026, or just 3 weeks ago OpenAI released their latest model GPT-6 Astra. 
🟠This model scored 99.95% on the AGI benchmarks. [source](https://arcprize.org/results/openai-gpt-6-astra)

🟠And honestly... nothing really changed. Actually, recently, it feels like a lot of the larger voices in the AI space are getting ... quieter. 

🟠On May 26th 2026 Sam Altman famously said : "I’m delighted to be wrong about this. I thought there would have been more impact on entry-level white-collar jobs being eliminated by now than has actually happened," [source](https://www.businessinsider.com/sam-altman-ai-jobs-prediction-wrong-white-collar-openai-australia-2026-5)  

Sam Altman has really been backtracking on a lot of his AI hype even though he still believes we will achieve superintelligence by 2028. Actually, even some of the quotes I said before he has recently retracted.

But not everyone in the AI space is retracting their statements, 
🟠Dario Amodei is actually acting crazier than ever.

🟠In January of 2026 he said that we are 6 to 12 months out from an AI agent swarm being able to take over the entire internet. [source](https://darioamodei.com/post/we-must-pace-the-frontier ) 

🟠Then in June of 2026 he released a 5,000 word write up called "Policy on the Exponential" where he explained that AI needs more safeguards and FAA style regulation. The craziest line by far though is "A nation that possesses powerful AI facing one without it—or even facing one that is behind in AI by 3 years—could be the equivalent of an army of World War II Marines facing an army of medieval swordsmen." [source](https://darioamodei.com/post/policy-on-the-ai-exponential) 

But the difference here is, nobody is really talking about them. It really feels like the boy who cried wolf.  And now that AGI is allegedly here, and the entire world isn't upside down, we can finally start to discuss what has actually changed. 

🟠Lets look at those jobs again... And update!
🟠BANG! Huge numbers! 
🟠We are actually going up a bit

🟠But aside from crushing reality? What did we actually learn from this entire fiasco?
Well if you are currently in elementary or middle school ... you are probably learning nothing.
🟠

### You Learned Nothing

We are getting dumber, overall, in total. And honestly, I don't know who's fault is it.

It could be short-form content, it could be degrading quality of the education system, or it could be the fact that i

🟠69% of students in high school self report 
to using AI to cheat on their homework. [source](https://newsroom.collegeboard.org/new-research-majority-high-school-students-use-generative-ai-schoolwork) 

SELF REPORT, do you know how much you have got to be cheating to be like 'yeah, all the time' to the COLLEGE BOARD. These are the people who are directly responsible with deciding which college you go to. They ADMINISTER the SAT.

You really know these students are getting dumber for admitting stuff like this. Everyone must be cheating, ... 69% of students admit it and 31% of students are smart enough to not.

whoo, anyways

🟠It also, turns out that like ... the world is lowering in performance on math and reading scores. 
🟠I mean, this doesn't mean we are dumber necessarily though, just worse at math and reading. [link](https://abcnews.com/GMA/News/us-students-reading-scores-dive-new-data-shows/story?id=136272199) [source](https://www.oecd.org/en/data/dashboards/pisa-education-and-skills/performance-trends.html?oecdcontrol-chart-control-bar-92d7c1b41b-var1=G884)  

I mean ... it just makes sense right? If, instead of thinking, you decide to not think and use AI, you will not flex your brain muscle, so you will be less smart.

Its kind of annoying that we have this amazing learning tool and we keep using it to learn less.

🟠Using AI as an assistant means you only have to learn as much as you feel like, and when a kid is in 1st grade the amount they usually want to learn is like zero.

But that is okay, AI is going to handle all of the jobs anyways 
🟠so at least when the kids grow up they can go outside and relax all day, in the bright vibrant sun, on the green rolling hills

right next, to their favorite
🟠data center

🟠
### You Learned Nothing and The Planet is Burning
🟠Do you remember cryptocurrency? If you don't know, cryptocurrency essentially exists as a ledger that GPUs run to upkeep. There was a point in time in which you could run GPUs 24/7 and make money while doing it. This was also bad for the environment yes, but nobody seemed to care because a lot of these crypto farms were either in someone's bedroom, in the back of someone's shed, or literally in a barn.

Running AI is kind of the same thing. To run a large model, you can use a computer that fits in a barn, in a shed, or even in a bedroom.

See, now that we have amazing open source quantized models, you can really run good AI anywhere. The environmental cost is a lot less because you can just run it using whatever energy your laptop has.

And also, even if you aren't running it locally, Prompting AI takes roughly the same amount of energy as a single google search.
And even when you search google it runs an AI query anyway, so you might as well just go straight to the source!

So what is all the fuss about, asking AI doesn't do much. One prompt won't hurt ...

But what if you want to 
🟠train a model? (image of Sam Altman)

🟠It is estimated that Grok 4, took roughly 0.31 terawatt-hours to train, which is equal to about 310 billion watt hours. Or in more human terms, if every single human in the united states played a video game on XBOX for roughly 4 and a half hours.

And that's Grok 4. 
🟠Grok 4 is garbage

Uh oh! Recently, in Oregon they built a datacenter, and their energy bill went up about a billion dollars! Why? Well, that is probably because, this company is running enough GPUs to be like every citizen is running a million Xbox's simultaneously.

🟠And the city is now running low on water! Wait, the last time I poured water on my XBOX it stopped working, why do they need water?

Well. AI specific GPU's get really hot. They basically pack a lot of computing into a small space, and more computing usually means hotter. So, they put water on it to make it cooler. 

But I don't know about you. but when water gets hot, it doesn't just go away? It might evaporate, but its still somewhere? What if we just closed the loop? Well some people are, but that is more expensive, so data center companies are just choosing not to do it.

But we have a lot of water in places, even if you don't use the closed loop cooling, you can still get a decent bit of water right?

Well the problem is, people just keep building data centers in cities that rely on well water to live. Then the data center companies takes all of the water, and are confused why people are getting mad at them when the 'well literally runs dry'. We have closed loop cooling. This is a thing.

🟠Anyway, the largest problem that people believe exists with data centers seems to be water ... but I think that was more of a short term hiccup than an actual problem. There are solutions, and the companies are choosing profits over people, which kind of makes you sad, and kind of angry.

🟠In fact, nothing is bringing people together more in the Divided States of America more than our hate of data centers. [source](https://news.gallup.com/poll/709772/americans-oppose-data-centers-area.aspx)  

But that's where my knowledge stops for the data centers and environment. Some people think legislation is the answer and others believe that stopping consumption is another answer.

Personally, I eat burgers, and ask Claude. So I have no pedestal to preach from. 
But anways.

🟠
### AI is not a tool, its an accelerant

So, what's my conclusion, well on September 22nd 2026 some guy named 
🟠Andrew Roddy coined the term "Ai is not a tool, it is an accelerant." and I think he was mostly right when he said it. 

It can accelerate how fast a project is made, but sometimes you need that slower speed to really understand the code before you make a stupid decision.

🟠If you give a someone who doesn't know how to architect a project AI, they will use it to create a poorly architected project.
If you give a bad writer AI, they will very quickly write a bad novel.
If you give a bad game developer AI, they will quickly realize their bad game idea.

But does AI accelerate learning? It can! 
But just using it doesn't really teach you anything, because AI is also kind of like a poison steroid.

🟠
### AI is a Poison Steroid 

Steroids accelerate muscle growth and poison hurts you. Basically, when you use AI you seem a lot stronger at the given topic than you are, but you don't ever actually increase your muscle growth under the hood.

The more you program with AI you don't get better at programming at all. You just continue to appear exactly as strong as you are with no increase.

Here is the little experiment.

🟠Sam and Tom are in a programming competition. Their goal is to become a the 
🟠best programmer given 60 years. Whoever is the better programmer at the end of the 60 years wins. 
🟠Sam only vibe codes and Tom only handwrites code 
disgusting, sorry that was my inner Altman

🟠See Sammy over here, never actually learn everything so his knowledge stays flat.
🟠While Tom begins learning things, and starts to grow in his knowledge.

And after around 50 years of this going on, 
🟠Tom finally passes Sam.

But honestly, I don't think this takes 50 years. In fact, 
🟠I think you can do this in exactly 4 years.

If you really focus and try hard enough, 
🟠you can escape

### You Need to Escape

See, 
🟠Everyone and everything is trying to convince you that you need to learn AI to survive. But you can learn how to use AI in 5 days, or maybe 1 hour if I did a good job. Everything else you need to learn can be found in documentation, a YouTube video, a book, or, the best way to learn, programming something yourself.

🟠You can't fall into the trap of using AI for everything. People will expect you to program ridiculous projects in tight deadlines but you can't fall for that now. Now is your time to surpass the AI. I am not saying have an entire knowledge of the world, and yes, Claude can one-shot make certain games, but you can too, and if you need to explain your code to a colleague, or make any modifications, you can, because YOU wrote it.

🟠I call it the Programmer Escape Velocity. Getting to a point where you are comfortable writing code, and are consistently writing better code, than the vibe coders around you. 

🟠And if you think this person doesn't exist, there are a lot of people in this room who I believe have already achieved this.

People like TJ, Austin, Ian, Noah, Logan, and many others, I believe are better programmers, than most people, just using AI.

See, the AI companies are trying to make you scared so you give up, they want you to believe you need them, they want to get you hooked on their product, so you can't think for yourself, and you are reliant
🟠because AI won't replace you, someone who doesn't need it will, and that hurts their bottom line.

Thank you.

(hopefully applause here)

### Kent Code Quick
🟠🟠But! If you want to achieve Programmer Escape Velocity literally in two days we are running an event called Kent Code Quick! This is a now AI allowed event with only documentation and mentors at your disposal so you can truly learn, how to program. No experience required we will teach you everything, and it will be a lot of fun!

### Questions?
Before I end, what if I told you all that this entire presentation was written ... by hand, I wrote it by hand, no amount of tokens could come up with this (your desired expletive)!

Anyways, are there any questions? seriously I am stoked for the questions I want to answer all of your questions!!

(Someone should inevitably ask about the codex looping and if they don't I should say, "does anyone want to check out how codex is doing?") if nobody has any questions.


