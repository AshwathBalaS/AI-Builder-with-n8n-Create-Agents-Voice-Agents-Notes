# AI-Builder-with-n8n-Create-Agents-Voice-Agents-Notes
This Repository contains my "AI Builder with n8n: Create Agents &amp; Voice Agents" Course Notes from Udemy

**I) Week 1 - Automate with Workflows in n8n Cloud**

**A) Day 1 - Build Your First AI Agent with n8n and OpenRouter (No-Code Tutorial)**

**B) Day 1 - Build AI Agents with n8n: Agentic AI Workflow Automation Framework**

**C) Day 1 - Build AI Agents with n8n: Complete Learning Roadmap & Workflow Setup**

**D) Day 1 - What is an AI Agent? Understanding Agentic Workflows in n8n**

**E) Day 1 - OpenAI API Setup: Cost Optimization and Free Alternatives Guide**

**F) Day 1 - How to Build an AI Agent with n8n and OpenAI API Integration**

**G) Day 2 - Understanding Agentic AI: How AI Agents Work with LLMs and Prompts**

**H) Day 2 - How LLMs Create Illusion of Memory and Reasoning Capabilities in AI**

**I) Day 2 - How Tool Calling Works in Agentic AI Systems and LLM Workflows**

**J) Day 2 - How to Evaluate AI Agents: Stop Anthropomorphizing LLMs in Workflows**

**K) Day 2 - How to Navigate n8n Cloud: Admin Panel, Instance, and Canvas Tutorial**

**L) Day 2 - How to Build AI Workflows with n8n: Nodes, Triggers, and Automation**

**M) Day 3 - How to Integrate Google Sheets and Google Drive with n8n Workflows**

**N) Day 3 - How to Build an AI Workflow in n8n with Google Drive Integration**

**O) Day 3 - How to Automate Stock Portfolio Tracker with n8n and Google Sheets**

**P) Day 3 - How to Build an AI Agent to Automatically Draft Gmail Replies in n8n**

**Q) Day 4 - Understanding JSON in n8n: Key-Value Pairs, Objects, and Arrays**

**R) Day 4 - n8n Authentication Methods: API Keys, OAuth2, and Workflow Integration**

**S) Day 4 - How to Integrate Pushover Notifications with n8n Workflows**

**T) Day 4 - Create Telegram Bot Using n8n: Complete AI Chatbot Integration Tutorial**

**U) Day 4 - How to Integrate Telegram Bot with n8n AI Agent Workflow Automation**

**V) Day 4 - How to Build a Slack Bot with n8n OAuth Integration and Automation**

**W) Day 4 - Connect Slack to n8n Using OAuth2 and Webhook Triggers Step-by-Step**

**X) Day 5 - n8n JSON Workflow Tutorial: Webhooks, Authentication & Integration**

**Y) Day 5 - n8n Node Types Explained: Core Nodes, Subnodes, and Cluster Nodes**

**Z) Day 5 - Build an AI-Powered Portfolio Rebalancer Using N8N and Google Sheets**

**AA) Day 5 - Agentic AI Workflow Automation: Balance Autonomy and Instructions**

**AB) Day 5 - How to Integrate Gmail and Pushover Notifications with n8n AI Agent**

**AC) Day 5 - n8n Workflow Automation: Using If Nodes for Conditional Logic**

**II) Section 2: Week 2: Accelerate With Voice Agents And RAG**

**A) Day 1 - How to Build AI Voice Agents with ElevenLabs Agent Platform**

**B) Day 1 - Build Your First AI Voice Agent with ElevenLabs Conversational AI**

**C) Day 1 - ElevenLabs Voice Agent Tools: Deploy Conversational AI with Widgets**

**D) Day 1 - Building Multi-Agent Workflows with ElevenLabs Voice AI Agents**




# **I) Week 1 - Automate with Workflows in n8n Cloud**

# **A) Day 1 - Build Your First AI Agent with n8n and OpenRouter (No-Code Tutorial)**

Each of my courses has something different going for it, and for this one, it’s all about being satisfying. This is the single most satisfying course I’ve ever made. Whether you’re technical or completely non-technical, in a very short amount of time I’m going to have you delivering real, tangible business value. Welcome to Gentle Co-Builder: Low-Code AI Agents and Voice Agents Using n8n. In just three weeks, you’ll be building AI agents that actually make an impact.

But first—stop right there. Normally we’d talk about objectives, introductions, logistics, and the curriculum. No, we won’t. You’ve taken my course before. You know I hate doing that at the beginning. Let’s get straight into action. Let’s build something cool. Let’s get some instant gratification. We can come back later to all the formalities. Let’s go.

First up, open your favorite web browser and go to openrouter.ai. If you already have something like an OpenAI API key, you can skip this step if you like. Otherwise, this is a great place to get access to free or paid AI models and route between different providers. If you don’t already have an OpenRouter account, click the Sign Up button and create one. You can sign up with email and password or use Google authentication, which is what I usually do.

Once you’re logged in, you may be asked a few onboarding questions. You’ll also be prompted to create an API key. Say yes, give it a name, don’t worry about usage limits, and then copy the key to your clipboard. Paste it somewhere safe so you can access it later. If that didn’t happen automatically, you can always click your avatar in the top right, go to Keys, and create a new API key there. You can make as many as you want. Just make sure you copy it correctly—if anything looks off, you can always generate another one. This key is what we’ll use to connect to AI from within n8n.

That’s step one. We’re halfway to instant gratification.

Now open a new browser window and go to the platform where we’ll be spending a lot of time together: n8n. If you don’t already have an account, click Get Started to begin the setup. Enter your name, email, password, and choose a screen name. You can opt in or out of the newsletter, then click Start 14-day free trial. If you’ve already used a free trial before, you may need the paid version, which is currently about $24 a month. Otherwise, you should be able to start the free trial.

When you first log in, you’ll answer a few basic questions about yourself and your company. You can say it’s just you, select a team like engineering, describe your company however you want, or skip anything you prefer. You might be asked if you want to invite teammates—feel free to skip that. Once your workspace is ready, you’ll see a screen that says Welcome… Create your first workflow. This is our home for the next three weeks.

Click Start from scratch or New workflow. If you already had an n8n account, you might click Create workflow instead. Either way, you’ll arrive at a blank canvas. This is the workflow editor where we’ll build automations visually, without writing code. Click Add first step. On the right, you’ll see a list of triggers—these are what start a workflow. Choose On Chat Message. Then either click Back to Canvas or simply press the Escape key to return.

Next, click the plus button to the right of the trigger. Select AI, then AI Agent. Again, return to the canvas. You’ll now see a large AI Agent node that you can drag and reposition. This is your first AI agent.

Inside the AI Agent node, click the plus under Chat Model. Search for OpenRouter and select OpenRouter Chat Model. Then choose Create New Credential. Paste in the API key you copied earlier from OpenRouter and save it. If it tests successfully, you’re good to go. If not, go back to OpenRouter, generate a new key, and try again.

Once the credential is saved, close that window. Now go to the Model dropdown. You’ll see many available models. Most cost money, but we’re going to choose a free one. Back on OpenRouter’s website, you can search for “free” to see available options. There are many, including versions of DeepSeek, Gemini, and OpenAI’s open models. We’ll use OpenAI’s open-source GPT model.

Back in n8n, type openai/gpt-20b:free into the model selector and choose it. Then return to the canvas.

Now click Open Chat. Type something simple like “Hi there.” You’ll see the workflow execute—spinning indicators, activity in the background—and then a response appears. You just connected to an AI model in the cloud using a visual workflow, without writing a single line of code.

Try another prompt, such as: “Please tell me a joke about AI automations.” Watch it run, and there’s your answer. Maybe not the best joke ever—but that’s not the point. You’ve just built your first AI-powered workflow.

This is the beginning. This is the first time you’ve created a workflow that calls an AI agent, connects to a model through OpenRouter, and runs entirely in the cloud—completely low-code and completely free.

Congratulations. That’s a little taste of instant gratification.

Now that we’ve built something, we can step back and start answering the big questions: what exactly is this course about, and what is n8n? Let’s go do that next.

# **B) Day 1 - Build AI Agents with n8n: Agentic AI Workflow Automation Framework**

Now, you might be thinking, “Ed, that wasn’t the biggest instant gratification, because I can do all that with ChatGPT. I can just ask it to tell me a joke.” And that’s true. But what we actually just did was build our own little version of ChatGPT in a couple of minutes. We designed a workflow with a chat interface, made a call to an AI, and you can already see how we could switch out different models. More importantly, you can see how we’re planting a seed that can grow into something much bigger. We’ll be able to add more AI, more services, and more integrations, allowing us to orchestrate increasingly complex workflows—all through this very simple interface. And it only takes minutes. This is just the beginning of something much larger.

So with that, let me welcome you properly again to the Agentic AI Builder. Prepare for building. This course is hands-on. It’s about creating. We’ve got so much to build and so much impact to prepare for. What we build is going to be valuable: high-impact, meaty deliverables that you could use in your own business, in products you already build, or directly for your clients. These are real ways to deliver impact. Whether you are technical or non-technical, this course will equip you to deliver value—and it’s also going to be a lot of fun. I can say that with confidence because I’ve already built every project we’re about to go through in the next three weeks, and I had a blast. You’re going to have a blast too.

Let me explain who this course is for. There are two main personas. First, if you’re primarily a business or product person—someone who delivers products—this course allows you to work at the frontier of what’s possible with generative AI, and especially agentic AI, which is where most of the excitement is right now. You’ll be able to build products with business impact without writing a line of code. If that’s you, this course is for you.

The second persona is the AI engineer. Maybe you already know how to write software. So why would this course be for you? Because it allows you to deliver substantial business functionality in minutes, and in a way that stays aligned with your business partners or clients—so much so that they can even take over what you build. If you’re doing a project or a gig for a client who needs automation, you can build it quickly and hand it off. The fact that you’re already technical only makes this more powerful. This course empowers both technical and non-technical people. It works on both levels.

And of course, most of you probably sit somewhere in between. Maybe you’ve never written a line of code in your life. Maybe you’ve done some coding years ago. Maybe you’re comfortable with complex Excel formulas—which is basically coding. Wherever you fall on that continuum, this course is for you. I’ve designed it so that there is something valuable for everyone, regardless of where you are on the technical spectrum.

So where will you be in three weeks? What do you get out of this course? By the end, you will be able to create AI agents and voice agents that solve real business problems. I’m not a believer in building agents just for the sake of it. There should always be a business problem you’re solving and a measurable outcome you’re driving. That’s what we will focus on. You’ll be able to apply for jobs that involve building AI agents, or submit proposals for projects that require agent-based solutions. You’ll also be equipped to use agents for automation, acceleration, and amplification—either within your own business or for your clients. That is what we will achieve by the end of three weeks.

Now, just to introduce myself and show you that I’m actually qualified to teach you this—apologies to anyone who has heard this before, because I do make the same jokes every time. I’m an LLM guy, not a comedian. My name is Ed Donner. I’m the co-founder and CTO of an AI startup called Nebula. I spent most of my career at JP Morgan, where I started as a software engineer and eventually became a managing director, running an organization of about 300 engineers and data scientists. I began in London, which is where I’m from originally, worked in Tokyo for a while, and now I’m based in New York City.

Before Nebula, I was the co-founder and CEO of an AI startup called Untapped, which was acquired a few years ago. This picture you see is from the Times Square billboard announcing the acquisition—a magical moment for me. And if you squint carefully enough, you can actually see me on that billboard. I don’t just show this to brag about my Times Square moment, but also because I live right there. I live about a block away, right behind the Hard Rock Café guitar. In fact, that’s where I’m coming to you from right now.

It’s also customary to show a hobby photo, so here’s one of me after flying a plane. You might think I’m showing it to say how skilled I am—but it’s the opposite. My greatest strength in artificial intelligence is only surpassed by my complete inability to do anything involving hand–eye coordination. So if you ever walk onto a plane and see me in the cockpit, look for a parachute immediately. But if you’re on a course about using AI to deliver business impact and I’m teaching it, then you’re in exactly the right place. You’re in safe hands.

As I’ve mentioned before, I tend to talk about AI and large language models to anyone who will listen. A few years ago, my friends and family convinced me to stop giving them impromptu lectures and instead make courses and videos online. I gave it a try—and it’s been an absolute joy. People seem to enjoy learning from someone who actually works with these systems in the real world, as a practitioner. Today, around 300,000 people from 190 countries have taken my AI courses, and I’m incredibly grateful that you’re part of that.

You might be wondering how this course fits in with the others I teach. Let me explain. My first set of courses is for aspiring AI engineers: the Core Track, the Agentic Track, and the MLOps Track. These are designed for people with at least some technical background, though many non-technical learners have succeeded with them as well. Then I have a course for AI leaders—founders, managers, and executives who want to understand how to build durable, differentiated AI businesses. I actually recommend that one for technical people too, because commercial thinking is a powerful skill for engineers.

And then there is this course. This one is for AI builders. You don’t need any technical experience. It’s low-code and no-code. It’s about using n8n to build agents and voice agents that deliver immediate business impact in a very short time. This isn’t primarily for AI engineers or AI leaders—it’s for people who want to build and deliver results.

If more than one of these courses appeals to you, that’s great. They’re designed to be taken in any order and to complement one another. Yes, there’s some repetition, but repetition is actually a good thing when you’re learning. So if something else sparks your interest, go for it. But for now—for today and for the next three weeks—we’re focused on one thing: building AI with n8n.

# **C) Day 1 - Build AI Agents with n8n: Complete Learning Roadmap & Workflow Setup**

Over the next three weeks, this is what I have in store for you. This is the curriculum ahead.

There are going to be three different types of sessions. First, there will be core sessions that focus on Agentic AI, on n8n, and on the core capabilities. Second, there will be sessions purely dedicated to integrations, because integrations are such a huge part of working with AI and delivering real business impact. That is a whole topic in itself. And third, there will be real-world projects, which will form the final focus area.

So how does this fit into the three weeks?

Each of the three weeks has a punchy title that describes what we are trying to achieve. The first week is called Automate. It is about using n8n to build workflows for your business. Automate is week one.

Week two is called Accelerate. This is next-level work. Here we start adding more power to your business or your clients’ businesses. We will work with voice agents and use RAG. You may not yet know what RAG is, or you may have heard of it because it is one of the most hyped ideas right now. We will properly dig into it in week two as we focus on acceleration.

That brings us to week three, which I call Amplify. This is where we really dial up your business, your clients’ businesses, or your product using multi-agent systems. We will use MCP—another popular buzzword—and we will look at what actually delivers impact and what may just be hype. The goal is to focus on real business value. By the end of week three, you will have automated, accelerated, and amplified your business.
Each of these three weeks has five days. In week one, the first two days focus on core skills. Then we move into integrations, and we finish with a business project that you are going to love.

In week two, we again start with a core skills day, followed by an integrations day, then another core day where we go deep into RAG. After that comes another integrations day, and we finish the week by delivering a voice agent.

Week three starts with core topics again, where we self-host n8n and use local models. Then we move into advanced integrations, followed by MCP and context engineering with sub-agents—hot topics right now in Agentic AI. Finally, we conclude with a capstone project designed to amplify your business.
After all of this, you will reach a celebration moment. You will get your certificate, your cup, your chalice, and you will be able to say: I am now an Agentic AI builder.
That covers the objectives and the course structure. Now it is time to actually get started.
We will begin with a little bit of theory, and then we will move back into action—back to n8n and back to building workflows. First, though, I want to make sure we are on the same page with some basic definitions and foundational concepts. Many of you may already be comfortable with this, but it is useful to align and perhaps add a few extra insights along the way.

We should start with a definition of an LLM. A large language model is the core data-science model at the heart of generative AI. It is an AI program that generates text. It produces output based on an input. That output might be an answer to a question, or it might represent an action that should be taken. If the input asks, “What should I do next?”, the model generates the most likely next text as its response.
We are all sometimes guilty of treating LLMs in a human-like way—attributing motivations, intentions, or even relationships to them. But it is important to stay grounded in reality. LLMs are extremely powerful statistical programs. They are large-scale pattern-matching systems trained on enormous amounts of data. During training, they learn patterns in language so that when given an input sequence of text, they can predict the most likely text that should come next.
If the input is a question, the model predicts a good answer. If it is a request for what to do next, it predicts actions. It can even predict which tools to call or continue a conversation. But behind all of this is statistics and pattern matching. That is the fundamental nature of a large language model.
There are also many techniques layered on top of LLMs to make them feel conversational. For example, what we often call “memory” is usually just a clever software trick that feeds previous messages back into the model so it appears to remember the conversation. In reality, the model itself is stateless. It does not retain memory between calls. It simply receives input and produces output each time.

What is astonishing is that, at the massive scale these models operate—trillions of parameters—this statistical process creates the appearance of intelligence. People often refer to this as emergent intelligence: complex behavior that arises purely from scale.
It is also important to understand the difference between GPT the model and ChatGPT the product. GPT is the large language model itself—the statistical engine that takes input and generates output. It is stateless and has no awareness of previous interactions.
ChatGPT, on the other hand, is a software product built by OpenAI that uses GPT behind the scenes. The product adds features such as memory, tools, web browsing, and a user interface. All of that functionality is implemented in software around the model. The model provides the intelligence, while the product delivers the experience.
Earlier, when we built something using OpenRouter, we were doing the same thing: creating a product on top of a model and adding chat-like functionality. Keeping this distinction in mind—the product versus the model—is essential as you start building your own systems.

If all of this already feels familiar, that is great. If not, don’t worry. We will cover these ideas repeatedly, and they will soon become second nature.
One last concept I want to touch on is the idea of an API. People talk about APIs all the time, and many are unsure what they actually are. At its core, an API is simply a way for different software applications to communicate with each other. It allows one system to send a request to another system and receive a response, using standard formats and protocols.

Most modern APIs work over the web using HTTP—the same technology used to load web pages. Instead of retrieving a web page, you call a specific URL, known as an endpoint, to tell another piece of software to perform an action or return data. The information exchanged is usually in a format called JSON (JavaScript Object Notation). You will become very familiar with JSON in this course—it is about as “low-code” as technical work gets.

Finally, most APIs require authentication. You usually identify yourself using an API key, which acts like a password. This key tells the service who you are and allows it to track usage or apply billing. When you make a request to a service like OpenRouter, you include your API key so it knows it is you and can process your request.
That is the foundation. From here, we move into building, integrating, and creating real-world agentic systems.

# **D) Day 1 - What is an AI Agent? Understanding Agentic Workflows in n8n**

Okay, we’ve got that out of the way. I know you probably already knew what an LM and an API were, but hopefully there was still something interesting in there.

But now let’s talk about AI agents. Even if you think you know what an AI agent is, there is so much confusion, disconnect, and disagreement about what the term actually means. There are even memes about how confusing it is.

So let me clear that up. An AI agent can honestly be whatever you want it to be. It’s one of those terms that people use very loosely these days. As long as it involves AI, you could probably call it an AI agent. However, most practitioners today do have something more specific in mind when they use the term. That’s what I want to explain now.

First, let’s talk about what people don’t necessarily mean by an AI agent. For a while, OpenAI and others used a definition along the lines of “AI systems that can do work for you independently.” This included tools like the OpenAI GPT agent (formerly the Operator agent), where you could ask something like, “Find me a Chinese restaurant in New York with availability for three people at 9 p.m. tonight,” and then watch it open a browser and carry out the task on your behalf. For a long time, that was considered an AI agent.

Then, towards the start of 2025, the industry began to converge on a slightly tighter definition, popularized by Anthropic in their blog post Building Effective Agents, along with work from Hugging Face and others. This view defined agents as systems where an LLM controls the workflow. In other words, instead of hard-coding “do A, then B, then C,” you allow the LLM to decide what happens next. You might prompt it with something like: “There are three possible next steps. Please tell me which one to take.” At that point, the LLM is orchestrating the workflow. This became the evolving definition of an AI agent.

More recently, towards the end of 2025, an even clearer definition has taken hold: an AI agent is an LLM that runs tools in a loop to achieve a goal. That means the model repeatedly decides what action to take, executes a tool, observes the result, and continues until the objective is reached. We will go much deeper into this terminology throughout the course.

You have already seen an example of this in n8n, where we used an AI agent node with tools connected to it. In practice, we can be a bit flexible. On this course, any workflow that includes that AI agent node can reasonably be called an AI agent. But strictly speaking, in the practitioner’s sense, it becomes truly “agentic” only when the agent is running tools in a loop to achieve a goal. And don’t worry—our main projects will absolutely meet that definition. We will be building true AI agents.

Now, there is one more definition I should give you: what exactly is n8n, which is what this whole course is built around? You probably already have a good idea, but let’s go a little deeper.

At its core, n8n is a workflow automation startup. It is similar in spirit to tools like Zapier, but it is newer and more flexible. It was founded in Berlin in 2019 and has grown rapidly into a multi-billion-dollar business with millions of users. What really sets it apart is how simple and streamlined it is, both for working with AI and for building integrations. It is incredibly easy to deliver real business value using n8n, whether you are technical or non-technical.

There are two main ways you can use n8n. The first is the cloud version, which is what we used earlier. In this case, you are using their hosted installation of n8n. It is free for a limited time, and after that you pay a subscription—around $24 per month in my case. The second option is to host it yourself. You can download the software and run it on your own computer or on your own server, and in that case it is free.

This brings us to the license. n8n is not exactly open source. It uses something called a “fair code” license, which is important to understand. Fair code means that you can use the software for free, download it, run it, and even modify it. You can use n8n for your own business without paying anything if you host it yourself. You can also build projects for clients and use n8n as part of those projects without owing anything to n8n.

So what can’t you do? You cannot use n8n to directly compete with n8n itself. You cannot resell the product, host a competing platform, or take the software, modify it slightly, and sell your own version. You also cannot sell the product to your clients. What you can sell are your services—your automation work, your workflows, and the solutions you build using n8n. That distinction is at the heart of the fair code license, and it is a very reasonable model.

To summarize: you can download n8n and run it for free, build solutions for your own business, and build and sell solutions for clients. What you cannot do is sell the n8n product itself. You can either self-host for free or use the cloud version with a subscription, starting at roughly $20–$24 per month depending on the plan.

There is also a third option called white-labeling. This is for companies that want to embed n8n inside their own product. That option comes with commercial terms, as you would expect, and requires contacting the n8n team directly through their website.

So hopefully now you not only know what n8n is, but also how you are allowed to use it and how it fits into real business use cases.

# **E) Day 1 - OpenAI API Setup: Cost Optimization and Free Alternatives Guide**

Okay, we’re about to go and do some final tinkering for today with N810, but I do want to set your expectations about APIs, costs, integrations, and all that good stuff that will shape the time we’re going to spend together.

I want to say that we’re going to do a ton of different integrations, and some of them come with costs. They are all optional, and you are always in control. First and foremost, you should decide what you want to spend money on and what you do not.

There’s no need to spend anything at all, but it is up to you to make that call as you go. I will give you alternatives, and you can do some research to understand what you would rather do.

If you want to spend a couple of dollars on something like OpenAI, then you should do so. If you don’t, you don’t need to do it. There will be plenty of alternatives, and you can always look for other integrations that are free. That can always be an alternative to what we do.

So please do keep that in mind.

N810’s cloud version, which we’re going to use in weeks one and two for simplicity because it’s so quick to get up and running, has a two-week free trial, at least for me right now. After that, it becomes $24 a month.

In week three, we’re going to move to self-hosting so that it’s free and runs on your own computer. It’s just slightly more technical, which is why I’m waiting until week three to get there.

If, however, you want to do that from the get-go, then you absolutely can. If you already know what you’re doing and you’re a bit technical, then just use the self-hosted version instead. You can check the documentation, which is perfectly clear.

I also want to say again that all of the integrations we use are optional. You can always switch things up for a different integration, and almost everything we do has a free tier. One of the exceptions is OpenAI.

OpenAI, which we’ll use in a second, is extremely cheap for most of what we’ll be doing. However, they do require a minimum upfront balance of $5, which you then use on a pay-as-you-go basis.

For some people, that’s annoying, and you don’t have to use it. You can always use OpenRouter as a drop-in replacement throughout this course. As you saw earlier, OpenRouter is free.

However, with OpenRouter’s free models, there are rate limits. That means there may be times when it throws an error and you’ll have to wait before trying again. That’s simply part of life on a free plan.

If that becomes too frustrating, then you might decide to spend the $5 and get an OpenAI balance.

If you can, I would suggest OpenAI because it is so widely used. Many clients, future clients, or employers will value the fact that you have OpenAI experience. It’s a good one to try out.

That said, any of the major providers are great. If you’d rather use Anthropic, which is my personal favorite, go for it. If you like Gemini, which also has a strong free tier when you go directly through Google AI Studio, you can absolutely use that too.

All of the models work in basically the same way in N810, and you can pick whichever one you feel most comfortable with. We’ll be setting up OpenAI next for those who want it, but you can also stick with OpenRouter.

So yes, keep OpenRouter in mind as your free alternative. You can use it again, pick any free model, or even try paid ones if you prefer. It’s also an easy way to experiment with different models.

And please don’t feel like you need to stick only to the integrations I’ll be covering in this course. One of the great things about N810 is how many integrations there are to choose from.

You should focus on learning the techniques: how to set up integrations in general, not just how to use one specific tool. Once you understand the pattern, you can apply it to different integrations, experiment on your own, and try new things.

The documentation for N810 is excellent. Every integration is well documented, so you should be able to take what we do and go in a different direction if you want.

That is the best way to learn. Don’t just do exactly what I do. First, make it work the same way. Then try taking it in a slightly different direction. Experiment with a different integration. Solve a different problem.

There are so many integrations available that you’ll be able to use this to solve all kinds of different problems. That’s the joy of it, and that’s also where real expertise is built.

Okay.

With that, let’s go back to it. Let’s go and do some experimenting.

First up, we’re going to set up an OpenAI account if you don’t already have one. This is completely optional if you’d rather stick with OpenRouter.

The website to go to is platform.openai.com.

This is not the same as ChatGPT. ChatGPT is a product with a free tier and a subscription option. That’s not what we’re doing here.

We want API access so that we can connect directly to the underlying model, the LLM that sits behind ChatGPT. We’re not using the product. We’re accessing the models themselves. That’s why we go to the OpenAI platform.

If you don’t already have an account, click Sign Up. You can continue using Google, Apple, Microsoft, or just an email address. I’m signing in with Google.

After that, it will ask you a few questions, like your date of birth. Once that’s done, you’ll be prompted to enter an organization name.

If you’re doing this just to build your skills, you can simply use your name or something like “Education.” Then choose whatever role fits you best and create the organization. You can invite your team later if you want.

You may see an option to set up your API key immediately. You can skip it for now by clicking “I’ll do this later.”

You’ll then arrive inside the OpenAI platform with your account set up.

I know I keep repeating this, but it’s important: we are now in the OpenAI platform, not in ChatGPT. This is where professionals connect to the underlying AI to build their own products. There is no monthly subscription here.

Instead, you pay a very small amount each time you make a request to the AI, usually fractions of a cent per call.

There are two things we need to do now: create an API key and add the $5 minimum balance. You may have done this during the welcome flow, but if not, we’ll do it now.

First, let’s set up the API key. Go to Settings, then click on API Keys.

You’ll see a button to create a new secret key. That is your API key—the credential N810 will use to identify you when it connects to OpenAI.

Click Create New Secret Key. Leave it owned by you, give it any name you like, choose the default project, and keep all permissions as they are. Then click Create Secret Key.

You’ll see your key appear. Copy it to your clipboard and store it somewhere safe, such as a simple text file or password manager. Avoid fancy editors that might change characters.

Keep it copied for now so that you can paste it into N810 shortly. Then click Done.

If you ever have trouble connecting to OpenAI, you can always come back here, revoke the old key, and create a new one. You can create as many keys as you need.

That’s your API key. Keep it safe.

If you want to use OpenAI, you also need to add the $5 minimum balance. To do this, go back to Settings, then click on Billing.

Click Add Payment Details. This does not affect your ChatGPT account—this is only for the API.

Here, you’ll enter your credit card and add the $5 balance. Make sure auto-reload is turned off. Auto-reload would automatically add more money when your balance runs out, which you don’t want while you’re just getting started.

Once you’ve added the balance, you can check Billing History to confirm that the funds are there. In some countries, it can take a little time for the payment to clear, so be patient if it doesn’t work immediately.

You can also visit the Usage page to track how much you’re spending. You’ll likely see that you’re spending very slowly, because API usage is extremely cheap unless you scale to many users.

For good API hygiene, keep this usage page bookmarked. Check it occasionally, and only top up your account with an amount you’re comfortable with.

The worst-case scenario is that you spend the amount you’ve added, so keep that amount small and always keep an eye on your usage.

Okay.

At this point, you’ve set up your OpenAI account, created your API key, and added your $5 minimum balance.

We are now ready to go back to N810 and build an AI agent that connects to OpenAI and does real work.

# **F) Day 1 - How to Build an AI Agent with n8n and OpenAI API Integration**

All right. We’re back here in NH and I’m going to press sign in to come back in as the account that we just created a few moments ago. This comes up. That was the name that I gave my instance. I click open instance and here it is. This is looking now at the home screen. If you’re still on the previous screen we were on before with that workflow, you can just press this home button right here and you get to this screen, the home screen for this instance. And you can see here that it has my workflow, the thing we created earlier, sitting there.

We’re going to start again and create one from scratch like we did before and use OpenAI this time. So follow along with me here, and tomorrow we’ll explain what all the different terminology means. We first press Create Workflow right here and we get again this fresh screen, a new screen for us. We’ll add a first step, and again we are going to add this thing here on chat message on the right. Click there and then remember what you do next: you press escape, or you click that back button at the top left.

So here we are. Now we are going to press this plus button. You remember what we do next. We click on AI, and next we do AI agent. And here is our AI agent. And next it’s either back to canvas or it’s escape. Here we are back on this canvas. The chat model is the first thing for us to select. You may remember last time we did Open Router at this point, and you may do that again should you wish. But I’m going to this time do Chat OpenAI by typing OpenAI, and there we see the OpenAI chat model.

If you’re starting for the first time, you may see an option to get 100 free OpenAI API credits. I don’t know if you see that too, but I’m going to ignore that for now and just use the credits that we just set up. Now I’m going to click here and say Create New Credential, just as we did with Open Router. I paste in the API key that I still have in my clipboard, press save, and it works: credential successfully applied, testing successful. If it didn’t work for you, just go back, create a new API key, copy it, and paste it straight in. Don’t go through another editor — they can cause trouble.

We are now set up to be using OpenAI. In this box right here we’re going to keep it as “from list.” This is the list of all the models available on OpenAI. As of right now, the fanciest one is GPT-5.1, but we’re going to stick with GPT-4.1 Mini because it’s really fast, really cheap, and great to start with. There’s an even faster, cheaper one called GPT-4.1 nano, but we’ll use mini for now.

Now we go back and try it out. We click in the chat section and say “hi there.” Off it goes, it’s thinking, processing, and we get an answer back: “Hello, how can I assist you today?” We just connected to OpenAI. Now I say, “Hi, my name is Ed.” It replies nicely. Then I ask, “Hey, what’s my name?” And it says it doesn’t know. This is the key learning moment. The LLM itself is stateless — every call is new. The illusion of memory in products like ChatGPT comes from software built around the model.

So we add memory. We click just below Memory, choose Simple Memory Stores, no credentials required, and go back. The yellow box means something changed, so we reset the chat session. Now we repeat: “Hi there.” “My name’s Ed.” Then we ask, “What’s my name?” And it answers correctly. That’s because we’ve given it conversational memory. We’re building pieces of what ChatGPT does by connecting boxes and lines instead of writing code.

Now it’s time to add a tool. Open a browser and go to MarketStack. Sign up for a free account and copy your API key. Back in NAS, clear the chat, press the plus button under tools, search for MarketStack, create new credentials, paste in the API key, and save. Then configure the tool: leave resource as end of day data, operation as get many, set the ticker to be defined automatically by the model, leave limit at 50, and add the filter latest. Press escape, and the red warning symbol disappears.

Now we have a model, memory, and a tool. Let’s test it. I say, “Please tell me the end of day equity price for Google.” Watch what happens — the agent uses the tool. And it replies: “The end of day market price for Google on the 8th of December was 313.72.” We just had a conversation with a model that could look up stock prices using a tool. The agent connected to OpenAI, used memory to maintain the conversation, and queried MarketStack.

This is our staging ground. From this simple beginning, we’ll build more sophisticated agents and real business workflows in the coming weeks. Congratulations on building your first workflow in N810 — simple, but a stepping stone to much greater things.

You also get something extra with this course: you get me. I’m available to help you if you get stuck. You can reach me on Udemy or LinkedIn. I love connecting, so by all means, reach out. It’s always me responding, even if I sometimes use copy and paste. Ask questions anytime — that’s what I’m here for.

As you build projects with N810, post about them on LinkedIn. Share screenshots, tag me, and I’ll weigh in to help amplify your work. If you see others from the course posting and we’re connected, please like and comment to support the community. That’s part of the program.

And with that, we’ve completed the first day. One day down, fourteen to go. You’re already 7% of the way through this program. Many congratulations. I can’t wait to see you tomorrow, when we’ll go deeper into the theory of N810 and agents. I’ll see you then.

# **G) Day 2 - Understanding Agentic AI: How AI Agents Work with LLMs and Prompts**

Well, this is good news. You’ve decided to come back for more. You weren’t completely put off by what we did yesterday, and now you’re back again. Welcome. Welcome to week one, day two.

I want to be upfront with you about how I like to teach. I’m very much a learning-by-doing type of person. The way I like to teach is the same way I like to learn myself—by jumping into a product and actually using it. Today, however, is a bit of an exception. This session is going to involve more talking than usual. I’ll be giving you some foundational concepts and background that will support everything that’s coming later. We’ll be talking about Agentic AI and some of the constructs around n8n, although there will still be a bit of hands-on work, so don’t worry. Let’s get started.

Let me tell you more about Agentic AI. We’ll begin by diving into the topic of AI agents, before circling back to n8n again. This will be a quick recap of some of the things we already discussed yesterday. There are many different ways to define an AI agent, so many that it’s almost become a joke. One of the earlier definitions, used by companies like OpenAI, described agents as systems that can work independently for you, such as the Operator agent or the ChatGPT agent.

Later, another definition emerged. This one focused on AI systems where a large language model decides what to do next. In this setup, the LLM generates content that effectively describes a plan, such as “do A, then B, then C,” or perhaps “do A, then C, then B.” That generated text becomes the output of the LLM, and we interpret it as instructions for what should happen next. This idea—where an LLM decides the order of activities and orchestrates a workflow—became a common working definition of an AI agent.

More recently, the definition has evolved again. Now, an agent is often described as an LLM that runs tools in a loop in order to achieve a specific goal. That looping behavior is a key part of what we now think of as Agentic AI.

A lot of Agentic AI feels magical, but behind that magic, the reality is actually quite pedestrian. Most of what feels impressive in AI comes down to writing good prompts for large language models. A prompt is simply the input text that we send to an LLM. The LLM itself is a data science artifact—a statistical model—that takes an input and generates an output by predicting what is most likely to come next.

Every time you call an LLM, that call is stateless. It takes the input, generates an output, and then forgets about it. It doesn’t know how it was called before, and it’s being called by countless people around the world all the time. Models like GPT receive an input sequence and produce an output sequence based entirely on that input. What we control are two things: what input we send and how we interpret the output. Most of Agentic AI is about mastering these two activities—getting the input right and making sense of the output.

Typically, the input sent to an LLM is made up of several parts. It often starts with something called the system prompt. This is the text that sets the overall context. It defines the role the LLM is playing, provides background information, and specifies the tone or style of the response. After that usually comes the user prompt, which is the specific message the LLM is meant to respond to.

In many cases, the full conversation history is also included in the input. This might include an initial user message like “Hi there,” the model’s response, the next user message, another response, and finally the current prompt the model is responding to. All of this can be included in a single input sequence. This works well because LLMs were trained on data organized in exactly this way—system prompts followed by user and assistant messages—so they’re very good at generating coherent outputs that follow this structure.

The key point is that we get to decide how this input data is organized. We can apply all sorts of techniques to make it more likely that the LLM’s output aligns with our business objectives. By structuring the input carefully, we can guide the model toward producing the kind of output we want. And once we have that output, we can choose how to interpret it.

For example, the input might ask the model to respond with the order in which certain steps should be executed. The output might then list those steps in sequence, and we can interpret that output as instructions to control a workflow. In this way, the text generated by the LLM is effectively driving a process. This combination of carefully designed input and intentional interpretation of output is the real secret sauce behind Agentic AI.

In the past, this was often referred to as prompt engineering, which has become a bit of an outdated term. Today, people increasingly talk about context engineering instead. This focuses on how to best set up the context sent to the LLM so that it’s positioned to achieve a specific business goal.

Most of what feels like magic in Agentic AI can be explained by five core tricks. These are essentially five conjuring techniques centered around prompting and, to a lesser extent, how LLMs are trained. Alongside these five tricks, there’s also a common pitfall—a trap that people often fall into when building Agentic AI systems.

The five tricks we’ll cover include the illusion of memory, which many of you may already be familiar with; thinking and reasoning, including the idea of reasoning budgets; chaining LLMs together; the use of tools—what that really means and what it doesn’t; and finally, the famous agent loop. In addition to these, we’ll discuss the trap I call the human trap. You might not yet know what that means, but we’ll get to it.

# **H) Day 2 - How LLMs Create Illusion of Memory and Reasoning Capabilities in AI**

Okay, let’s talk about five tricks and one trap. We’ll start with trick number one: the illusion of memory.

This is something you’ve basically already seen before, but it’s always worth taking a minute to explain it clearly. When we make a prompt to a language model—say something like, “My name is Ed”—the model’s job is simply to complete that prompt with the most likely text that comes next. As you know, it’s really generating tokens, which are small fragments of text. In this case, it responds with something like, “Hi, Ed.”

Now suppose we give it a completely separate prompt: “What’s my name?” Every time you call a language model—and I’ve explained this many times—it is stateless. This is GPT the model, the language model itself, not ChatGPT the product. When you make a call to GPT, it takes an input sequence—“What’s my name?”—and predicts the most likely text that should come after it based on its training data. And of course, in that case, it will say something like “I don’t know your name”, or something a bit more charming in typical GPT style.

So the illusion of memory comes from a very simple trick. When you prompt an LLM and say, “My name is Ed”, and it responds, “Hi, Ed”, then later the user asks, “What’s my name?”, you do not send the LLM just the prompt “What’s my name?” Instead—and you probably already know this—you send it the entire conversation so far.

That means what the model actually sees is something like:

“My name is Ed.
Hi, Ed.
What’s my name?”

What the model is doing now is predicting what comes next. In its training data, it has seen countless examples that follow this pattern of message, response, message, response. So it expects something like that. When it generates the next tokens—the next bit of text at the end—it produces something consistent with the full conversation. That’s why it responds, “Your name is Ed.”

This is also why every time you talk to ChatGPT through the UI, it sends the underlying GPT model the entire conversation history each time you press Enter. The model then generates the next tokens based on that full history. This trick of sending the entire conversation creates the illusion that the model remembers what you said 30 seconds ago. It doesn’t. The information is simply included again in the prompt every single time. Many of you already knew this, but it never hurts to go through it again. That’s how trick number one works.

Now let’s move on to trick number two, which is arguably less about agentic AI specifically and more about reasoning and general thinking. This idea started about a year and a half ago when people discovered something that was called chain of thought. The idea was that you could ask an LLM a question and then simply add something like, “Please think step by step,” and you would often get better results just by doing that.

There seemed to be something strange going on. If an LLM generates text that describes what it should do, and then generates text to actually do it, you often get better outcomes. Nothing is actually thinking in a human sense—it’s still just generating likely text—but as a side effect, by generating text that describes a thought process, the model ends up producing better answers.

This led to the idea of thinking models or reasoning models—they mean the same thing. These are models that have been trained so that when they’re given a question, they first generate some text describing how they’ll reason through the problem step by step, and only then generate the final answer. That’s why, with some models, you see what’s called a thinking trace before the final output.

To give you a concrete example—one I use in some of my technical courses—you can prompt a small model that is not in reasoning mode, such as GPT-4.1 nano, and ask something like: “You toss two coins. One is heads. What’s the chance the other one is tails?” Quite often, the model will give the wrong answer, typically something like 50%. That answer is incorrect because this is one of those sneaky questions with a bit of trickery built into it.

If, however, you prompt it differently—“You toss two coins. One is heads. What’s the chance the other one is tails? First describe your thought process, then give the answer.”—or if you use a reasoning model that’s been trained to output its reasoning first, you’ll often see a thought process like: “Okay, this is probably a trick question. They didn’t say the left coin is heads and the right coin is tails. I need to consider all possible outcomes.” It will then reason through the possibilities and arrive at the correct answer, which is two thirds.

You can try these experiments yourself. Depending on the model you choose and how you prompt it, you can reliably reproduce this behavior: a small model without reasoning often gets the wrong answer, while the same model—or a similar one—with reasoning enabled produces the correct result. This reasoning trick is a powerful way to extract more sophisticated intelligence from a model that is, at its core, simply generating the most likely text to follow an input.

One more important detail here is how these models actually generate text. They don’t produce an entire output all at once. Instead, they generate one token at a time. Given an input, the model predicts the most likely next token. That token is then appended to the input, and the entire sequence is fed back into the model to generate the next token. This repeats until the output is complete. This process is called inference.

Because of this, if you ask a model to generate tokens that describe a thought process, it will do exactly that first. Then, when it generates the final answer, that answer will be consistent with the reasoning it already produced. This often leads to better outcomes. It sounds counterintuitive and almost too good to be true, but it works, and it’s been shown empirically to work.

Some models are trained purely for chat. They respond immediately without explicit reasoning. Other variants of the same model family are trained for reasoning, where they generate reasoning text first and then an answer. There are also hybrid models that can do both. People often gravitate toward reasoning models because they perform better on benchmarks and appear more intelligent. However, chat models can be better for certain use cases—especially in agentic AI, where you’re already driving the system step by step.

So don’t assume that a reasoning model is always better. Sometimes a chat model will perform better. The only real way to know is to try both. This entire field is highly experimental. There are no absolute right or wrong answers—only experimentation, measurement, and choosing what works best for your use case.

Finally, some models allow you to control how long they should think. This is sometimes called reasoning effort or a thinking budget. In some models, such as the latest GPT-5.1, you can set this to none (chat mode), minimal, low, medium, or high. You might wonder how this actually works under the hood—how you tell a model that’s just generating tokens to “think more.”

There are several techniques, but the most common one is surprisingly hacky. During inference, as the model generates tokens one at a time, you don’t have to feed back only the tokens it generated. You can insert additional tokens of your own. The model has no idea that it didn’t generate them—it just treats them as part of the input and continues generating text.

Someone realized that if, during the reasoning phase, you wait until the model finishes a sentence—something that looks like a completed thought—and then insert the word “wait”, the model now has to generate text that follows that word. Because the next tokens must be coherent with “wait”, the model often steps back and reconsiders. It might say things like, “Wait, I should double-check my assumptions,” or “Wait, let me review the problem again.”

This causes the model to revisit and challenge its own reasoning. Adding words like “wait”, “on the other hand”, or similar phrases encourages it to explore new reasoning paths. If you’ve ever looked closely at reasoning traces in LLM outputs, you may have seen the word “wait” appear—that’s often this trick at work.

This incredibly simple technique works remarkably well and is one of the core methods used to control a model’s thinking budget and force deeper reasoning before it produces a final answer.

# **I) Day 2 - How Tool Calling Works in Agentic AI Systems and LLM Workflows**

And this may be more theory than you thought you were signing up for, but it’s going to be genuinely useful. This theory will give you valuable intuition when we actually get to building agent systems, rather than just talking about them abstractly.

Now let’s move on to the third trick, which is a simple one: chaining LLMs.

You probably already know this idea. You can write a complicated prompt to a language model, such as: “Come up with a puzzle and then solve it.” Sometimes this is a good thing to do because it gives the LLM a lot of flexibility. We often use the word autonomy here. It gives the model the freedom to go in different directions—to come up with two puzzles and solve them both if it wants to. You’re giving it a broad remit.

However, sometimes you don’t want that flexibility. Sometimes you want exactly one puzzle and exactly one solution. You might want to be very careful to ensure that the puzzle is hard, that it meets certain constraints, and that it’s framed properly. In cases like that, it can be much better to divide the work into two separate LLM calls.

In the first LLM call, you ask it only to come up with a puzzle. You might refine that prompt carefully, adding details and specifics so the model becomes very good at generating the kind of puzzle you want. Then, once it responds with the puzzle, you build a second prompt and make another LLM call. In that second prompt, you say something like: “I’d like you to solve a puzzle. Here is the puzzle.” And you simply include the puzzle generated by the first call.

When we draw this graphically, we often show it as if one LLM is calling another LLM. But of course, that’s not really what’s happening. What’s actually happening is much simpler: you’re making one LLM call, taking the output, and inserting it into the next prompt. Conceptually, though, it helps to think of it as two workflow steps.

This pattern—breaking a task into multiple LLM calls and passing outputs forward—is what we call chaining LLMs. It’s a very obvious idea, but it’s incredibly useful. It gives you more control, and it lets you test each step independently.

Now let’s move on to the fourth trick, everyone’s favorite: tools.

Tools feel incredibly magical, but in reality, they are extremely mundane. And again, this may be something you already know, but it’s worth emphasizing.

Suppose a user asks a question like: “What’s the stock price of Google?” You have some software—maybe custom code, maybe a product like an agent platform—that receives this question. That software makes a call to a large language model that has been “equipped with tools.” In other words, it’s been told that it has the ability to look up stock prices using some external service, such as MarketStack.

The LLM appears to connect to the internet, make an API request, retrieve Google’s stock price, and then respond with something like: “The price of Google stock is X.” This feels magical. But we know that LLMs don’t actually do that. They generate output tokens by pattern matching.

So the question is: at what point did the LLM stop generating tokens and decide to connect to the internet instead? How did it suddenly gain this power?

The answer, of course, is that it didn’t. Nothing like that happened.

What actually happens is far more mundane. When your code builds the prompt that it sends to the LLM, it doesn’t just say “What’s the stock price of Google?” Instead, it says something more like this:

“You can do one of two things.
You can either answer the user directly, or you can respond by saying that I need to run a specific tool on your behalf. If you choose the tool, I will call you again with the results.”

The tool available is something like “Look up stock prices.”
The user’s question is “What’s the stock price of Google?”

The LLM receives this carefully constructed input sequence. The output it generates says something like: “Use tool to look up the stock price of Google.” Your system then interprets that output, actually calls the tool, retrieves the stock price, and sends the LLM a second prompt that includes the tool result. The LLM then responds with the final answer.

So once again, this is just a clever conjuring trick. By shaping the input, interpreting the output, running external code, and calling the LLM again, we create the illusion that the model itself is running tools. But as with so much in LLM systems, it all comes down to clever prompting.

To really drive this home, there’s a simple experiment you can try in ChatGPT. You can give it a prompt like this:

“You are a support agent for an airline. You answer user questions.
Only use a tool to fetch ticket prices.
The tool retrieves ticket prices for London or any city.

Here’s the user’s question:
‘I’d like to go to Paris. How much is a flight?’”

If you do this, ChatGPT will respond with something like: “Use tool to fetch ticket price for Paris.” That’s it. It won’t invent a price. That response alone shows you exactly how tool calling works. It’s just pattern matching based on the prompt. You can try this yourself to see it firsthand.

Now let’s move on to the fifth trick, which is the idea of an agent loop.

An agent loop is the concept of calling an LLM repeatedly, allowing it to use tools over and over again until it has achieved a goal and is finished. This repeated cycle creates the behavior where the system appears to go off and do work autonomously.

Here’s an example.

Suppose you give an LLM the following task: “Your task is to find the current value of my portfolio.” You tell it that it has two tools available. Tool one retrieves the portfolio. Tool two looks up share prices.

Given this prompt, what is the most likely next thing the LLM will output? The obvious answer is: “Use tool to retrieve portfolio.” That makes complete sense.

So you take that output and feed it back into the next prompt. You include the same original instructions, add “Use tool to retrieve portfolio”, and then add the actual result of doing that. Suppose the result is: “Three shares of Google stock.”

Now you send this entire prompt back to the LLM. The most likely completion now is: “Use tool to look up share price of Google.” Again, that makes perfect sense.

You take that output, run the tool, retrieve the share price, and build a new prompt that includes everything so far: retrieving the portfolio, the result of three Google shares, looking up the share price, and the actual price—say, $100 per share.

You send all of that in a single prompt. Remember, every LLM call is stateless, so the entire conversation so far must be included. Now when you call the model again, it responds: “The value of your portfolio is $300.”

It doesn’t call any more tools. It’s done.

And that—calling an LLM in a loop, interpreting its outputs, running tools, and feeding results back in until a goal is achieved—is agentic AI.

# **J) Day 2 - How to Evaluate AI Agents: Stop Anthropomorphizing LLMs in Workflows**

There you have it. Those are the five tricks that allow us to make calls to LLMs with structured inputs and to interpret their outputs in a way that gives the impression that something autonomous is carrying out tasks for us.

Don’t worry if you didn’t fully grasp everything yet. We’re going to revisit these ideas again and again, and over time they will connect naturally. For now, the goal is simply to build some intuition around how these systems work.

So, what about the trap? I mentioned that there were five tricks and one trap, and this trap is something I personally find quite frustrating because it happens so often. I want to warn you about it and get you thinking about it early. I call it the human trap. The more formal term for this is anthropomorphizing.

Anthropomorphizing is the tendency to treat generative AI and LLMs as if they were humans, assigning them roles and responsibilities in the same way we would assign jobs to people. This happens constantly, especially when business leaders want to automate a process, something we’ll be doing a lot throughout this course.

The typical instinct—shared by business users and even experienced engineers—is to create an “agent architecture.” This usually takes the form of a diagram with different agents connected by lines, where each agent is given a role based on how humans would organize the work. You might have agents that represent different jobs, such as researchers, evaluators, or decision-makers.

I’m guilty of this myself. In some of my courses on generative engineering, we build systems like a trading floor with traders and researchers. It’s a very natural way to think, and for toy projects or demos, it’s perfectly fine. It’s fun and visually intuitive. However, it’s not a disciplined or reliable way to design real systems, and it comes with serious problems.

The biggest problem is forgetting what LLMs are actually good at. LLMs are trained to generate realistic and compelling content. That’s their strength. If you tell an LLM, “You are an evaluation agent. Evaluate the previous output and give it a score out of ten, along with a justification,” it will do exactly that.

It will generate a score. It will generate a justification. It will sound confident and reasonable. But that doesn’t mean the evaluation is correct. It doesn’t mean it’s aligned with your true objectives. It simply means the model is following the instructions in the prompt and producing plausible text.

The real danger is that you can fool yourself into thinking you have a sophisticated system: a whole group of agents collaborating, each fulfilling its role and producing polished outputs. In reality, it may all be LLM-generated slop—content that looks meaningful but isn’t actually solving your problem in an accurate or reliable way.

So what’s the right approach? When you divide a problem into multiple agents, you should do it because it genuinely improves performance, not because the roles sound sensible or mirror how humans would work. If you have a complex problem, it may make sense to split it into steps, but you should test that assumption.

You try a simpler approach first. Then you introduce a division of labor. If the results improve, you keep it. If they don’t, you discard it. This is how you should approach agent design—scientifically, through experimentation.

The most important word here is evaluation. You must have a way to measure outcomes. You should reorganize agents or break tasks into smaller steps only when it leads to better evaluations and demonstrably superior performance. That’s the correct justification, not the appearance of having well-defined responsibilities.

Starting with human analogies can be a reasonable first step. After all, human organizations evolved for a reason. But that should only ever be a starting point. Always begin as simply as possible. Start with a single role, then gradually add complexity, experimenting as you go and measuring whether it actually helps.

That’s the right way to work. That’s how you avoid the human trap.

And with that, we wrap up the theory behind Agentic AI. I hope this has given you solid intuition as we move into building agentic workflows, along with some real-world lessons learned from deploying these systems in practice.

Now it’s time to return to N810, starting with navigation and the big-picture building blocks of the platform.

# **K) Day 2 - How to Navigate n8n Cloud: Admin Panel, Instance, and Canvas Tutorial**

As I explained last time, there are two different modes you can use with n8n. The first is n8n Cloud, where the company manages the installation and you connect to it remotely. The second is self-hosted, where you run the code yourself—either on your own computer, a server, or another environment. We’ll get to self-hosting later.

For now, we’re using Cloud, simply because it’s the fastest way to get up and running. I also mentioned a white-label mode earlier, but that’s a bit different and not what we’re focusing on here. So for now, cloud is what we’re using.

There’s one big-picture concept I need to explain next: the basic terminology and structure for navigating n8n. This can be confusing at first, so I want to make it absolutely crystal clear right from the start.

When you first sign in to n8n, you are signing in at the account level. The first screen you see contains cloud-level information about your account. This includes something called an instance.

An instance is essentially an n8n engine. It’s the running software designed to automate business processes. That running installation is what we call an instance, and it has its own set of screens. Within an instance, you can run multiple workflows, where each workflow represents a business process you’re automating.

So there are three levels of granularity to keep in mind:

The cloud / account level

The instance level (the running n8n engine)

The workflow level (individual automations)

When you first sign in, you land on a screen called the Dashboard, also sometimes referred to as the Admin Panel. These two names refer to the same thing. This screen shows cloud-level, account-level details, and the URL reflects that—it’s the app-level URL.

From there, you can open your instance. When you enter the instance, you land on a screen that’s sometimes called Home and sometimes called Overview. “Home” is the most commonly used term. This is the home screen of your instance, and the URL now includes something like /cloud/workflows.

On this screen, you’ll see a list of workflows. Each workflow can be clicked to open its own editor. That editor screen is referred to by several names: sometimes the editor, sometimes the canvas. Technically, the editor is the whole screen and the canvas is the main area inside it, but in practice people often use the terms interchangeably.

The URL for this editor includes your instance URL followed by /workflow and an ID for that workflow. That’s how you know you’re inside a specific workflow.

So again, those are the three levels:

Cloud (account)

Instance

Workflow

Now let’s actually look at n8n and see this in action.

Here I am in my browser. I see the sign-in button, and since I’ve already logged in before, I land directly on this screen. You may have seen this screen already and felt briefly confused, because it looks different from what you see inside a running instance.

This is the Dashboard, also known as the cloud Admin Panel. This is the cloud-level view. You’ll see tabs like Dashboard, Manage, Billing, and Export. These are all related to your account and subscription, not the running software itself.

For example, here I can see my plan, the version I’m running, and how many days I have left in my free trial. All of this lives at the cloud level.

On this same screen, you’ll also see a box representing an instance. This is a running installation of n8n in the cloud. To enter it, I click Open Instance.

Now we’re inside the n8n instance itself. This is the Home or Overview screen of the running engine. Notice that the URL has changed and now includes the instance name followed by /cloud/workflows.

This screen shows an overview of your workflows. This is the actual n8n software, not your cloud account. If you were self-hosting, this screen would look the same.

Right now, everything here is empty because nothing has run yet. You might already have one workflow if you created something earlier. Otherwise, you may see a prompt to create your first workflow.

On the left-hand side, you’ll see the main navigation. You can expand it to show labels. We’re currently on the Overview (or Home) page. You may also see sections like Personal, which represents a project containing a subset of workflows.

You can create projects by clicking the plus button. For now, we’ll stay on the Overview screen.

There’s also a button called Admin Panel inside the instance. Clicking this takes you back to the cloud dashboard. This is how you move between the running instance and the cloud account view.

So to recap:

From the cloud dashboard, you open an instance

From inside the instance, you can return to the cloud dashboard via the Admin Panel

Next, there’s a Templates section. Templates are pre-built workflows you can copy and use as a starting point. We’ll look at templates later, but for learning purposes, we’ll mostly build things from scratch so you understand how everything works.

There are also AI-related features and a Settings screen. The settings control configuration options for the running instance itself.

Now, from the Home screen of the instance, you can click Create Workflow. This takes you into the editor, where you work on a specific workflow that automates a business process.

At the top, you’ll see the workflow name and ID in the URL. The large central area of the screen is the canvas, where you drag and drop nodes to build your automation.

That brings us back to the three levels one last time:

Cloud dashboard (account level)

Instance home (running n8n engine)

Workflow editor (canvas)

To move around:

Use Admin Panel to go back to cloud

Use Overview or Personal to return to the instance home

Click a workflow to enter the editor

To build muscle memory, I recommend going into n8n now and switching between these three levels a few times. Once this navigation becomes second nature, everything else in the course will feel much easier to follow.

# **L) Day 2 - How to Build AI Workflows with n8n: Nodes, Triggers, and Automation**

Okay, now let’s do some quick clicking around within the product itself, and I’ll define things as we go. First, we press Create Workflow to start a new workflow. This brings up the editor, where we can create a workflow that represents automating a business process.

The first thing we do here is add a step. This step is called a node. A node is one of the building blocks of a workflow—a little piece that makes up the entire automation. Nodes come in different flavors. They can be triggers, which start a workflow, or actions, which perform a task. For example, an “on chat message” node is a trigger because it initiates the workflow when a chat message is received.

To add a node, you press the plus button, which opens the node panel. For example, we can go to AI → AI Agent, add that, and then use the connector to link it to the trigger. Nodes are linked by connectors, which simply connect the output of one node to the input of another. You can also delete or move connectors to organize the workflow visually.

Next, we can add additional nodes. For instance, I can add an OpenAI node, which remembers the credentials we set up previously. We’re using GPT-4-mini in this example. Pressing escape closes the node selection, and we can organize the nodes on the canvas. We can also add memory, like Simple Memory, which allows the agent to store context across interactions.

At this point, the workflow is functional. If I type something, like “Hi there,” the AI agent uses its memory and context to respond appropriately. The workflow now demonstrates memory in action. For example, if I say my name is Ed, the AI responds with, “Nice to meet you, Ed. How can I help you today?” This shows that the agent is using conversation history to maintain context.

We can also modify the system prompt, which sets the tone for the AI. For example, I can change it from “helpful assistant” to “snarky, humorous assistant.” After refreshing, the AI responds in the new tone: “Well, well, well, look who decided to show up. What’s on your mind, oh mighty keyboard warrior?” This demonstrates how the system prompt controls the AI’s behavior.

Additionally, we can add tools to the workflow. For example, the MarketStack tool can be integrated to fetch stock prices. Once connected, we can send a query, such as “What’s the stock price of Google?” The AI uses the tool to fetch the most recent trading data and responds accordingly. This shows how nodes, memory, system prompts, and tools can work together to create a fully functional AI workflow.

The editor also allows us to switch between Editor and Executions. Executions show the inputs and outputs of workflow runs. This is useful for debugging and understanding how the workflow behaves over time. We can rename workflows, track executions at both the workflow and overview level, and manage multiple workflows from the home screen.

To recap some terminology:

Node: A single step or building block in a workflow, either a trigger or action.

Connection: A link between two nodes, connecting outputs to inputs.

Workflow: A collection of nodes and connections that automates a business process.

Execution: A run of a workflow, either manually or in production mode.

Active workflow: A workflow running in production mode.

Template: A pre-built workflow used as a starting point.

This concludes week one, day two. We’ve covered theory, terminology, and practical navigation of n8n, setting a solid foundation for building workflows. Tomorrow, we’ll move into our first yellow day, focusing on integrations. You’ll start building multiple workflows, seeing why n8n is such a powerful tool.

Take a moment to celebrate—you’re already 13% of the way through this course. Tomorrow will be an exciting step forward.

# **M) Day 3 - How to Integrate Google Sheets and Google Drive with n8n Workflows**

There are two ways in which Nw10 truly has a real wow factor.

The first is the way AI—and especially genetic AI—is deeply woven throughout the product, making it incredibly easy to create AI agents. AI isn’t something bolted on as an afterthought; it’s embedded at the core, so building intelligent workflows feels natural and intuitive.

The second wow factor is how Nw10 handles integrations.

Historically, integrations have been one of the hardest parts of building systems—connecting different tools, making them talk the same language, and dealing with brittle APIs and edge cases. This is where most of the real pain usually happens.
Except with Nw10, it doesn’t.

Nw10 doesn’t just make integrations simple—it makes them feel almost magical.

Today marks our first day focused entirely on integrations. It’s a yellow day.
Welcome to Week One, Day Three: Integrations Day. Let’s do this.

We’re now right in the middle of week one, and this first yellow day is all about integrations. The day is split into two parts. In the first half, we’ll focus on integrating with documents—things like spreadsheets and files. In the second half, we’ll dive into email and other technical integrations.

For the technical folks watching, you know just how hard this kind of work usually is—and you’re going to be blown away.
For the business folks, you may have always wondered why tech teams complain so much about integrations. After today, you might wonder that even more, because with Nw10, it’s genuinely a cinch.

Before we jump in, let’s do a quick recap. Repetition is always useful.

As a reminder, there are three levels of hierarchy when working with Nw10 in the cloud. At the top level, you have the cloud deployment, where you can log in and view your account-level details. Within that, you have a specific instance that’s running. That instance contains multiple workflows, each representing a business process.

The cloud level is like the admin dashboard where you see everything. The instance has its own overview or home screen. Each individual workflow opens into the editor—primarily a canvas—which is where we’ll spend most of our time today.

Let’s also revisit some terminology.

A node represents a step in a business process. A trigger is a special type of node that kicks off a workflow—this could be scheduled (like running once per day) or event-based (such as receiving a message). An action node represents something happening, like sending an email or updating a document.

A connection links nodes together, passing output from one node into the input of another. A workflow is simply a set of connected nodes that automate a business process. An execution is a single run of that workflow—either triggered manually during testing or automatically when the workflow is active in production.

Finally, there are templates, which are pre-built workflows you can use as inspiration or starting points. We’ll mostly build from scratch, but templates are great for learning patterns and ideas.

Now, one more recap—think of it like those movies where the same scene appears again and again, just slightly changed.

Integrations will play a huge role over the next few weeks, so there are a few important things you need to understand upfront.

First, you are always in control of integrations. You don’t need to do exactly what I do. Many integrations are free, some have free tiers, and others are paid—but you decide what you use. Always check what an integration does and whether you’re comfortable with it.

I’ll demonstrate a specific set of integrations, but Nw10 offers a massive range. You can follow along exactly or take things in a different direction. If I integrate with Slack, you might choose Telegram. If I post messages, you might trigger something else entirely. That flexibility is one of Nw10’s greatest strengths.

Second, integrations can be tiresome and slippery. Things will sometimes go wrong for reasons that seem absurd—like an API key getting messed up because hyphens were converted into long dashes when copied. Suddenly nothing works, and you’re left wondering what went wrong.

This is where patience and thick skin come in. Read the documentation. Try again. Generate a new key. Nine times out of ten, there’s a simple explanation—you just have to keep pushing until you find it. And if you get truly stuck, I’m always available to help. I come with the package.

Third, every integration we do is optional. Nothing is mandatory. If an API is paid, you can skip it. If you don’t like a tool, use another one. This is always in your court.

With that said, the first set of integrations we’ll tackle is Google Drive—working with Google Docs and Google Sheets. If you already have a Google account, you’re in great shape.

If you don’t—yes, I know, you’re part of a very small group on this planet—I’d strongly recommend setting one up. Google Drive, Docs, and Sheets are free, incredibly streamlined, and frictionless to integrate with. We’ll be using them heavily, so this is the one exception where I’d suggest getting set up if you aren’t already.

# **N) Day 3 - How to Build an AI Workflow in n8n with Google Drive Integration**

And here we are at Nanaimo.

I’m going to click on the Sign In button, and up it comes. As you’ll remember, we’re now on the dashboard screen, which is the cloud-level view. From here, I’ll press Open Instance to enter the running instance.

You can see that I’ve got 21 days left on my free trial, and this instance is running version two. I’ll press Open Instance, and that takes us into the instance home page.

Here it is.

If this is your very first time logging in, it may look slightly different, but otherwise it should look just like this. You’ll notice there’s a sample workflow already there—a snarky stock price lookup—but today we’re going to build some new workflows by working with Google Drive.

So let’s get started.

I’m going to click the Create Workflow button at the top. Right away, the editor opens up, with the canvas in the middle. By now, you should be familiar with this view.

To add the first step, I’ll click the plus button. Since this is the beginning of a workflow, we’re choosing a trigger. From the list of trigger nodes, I’ll select the On Chat Message trigger—the one you already know.

Once that’s added, you can either press Escape or click back onto the canvas and then press Escape to return to the main editor view. And here we are.

Now I’ll press the plus button again. This time, I’ll go to AI and select an AI Agent. Press Escape again, and we’re back on the canvas.

We’ll configure this agent with normal memory, just the simple memory setup. Escape again. You can see that simple memory is now enabled.

Next, we’ll choose a chat model. You can use OpenRouter or OpenAI, but I’ll stick with OpenAI’s chat model. It automatically suggests using the OpenAI account, and we’ll keep the default 4.1 mini model. Press Escape, and that’s done.

This is a solid starting point, so let’s quickly test it to make sure everything works.

I’ll type “Hi there,” run the workflow, and off it goes. You can see it thinking, and then responding:
“Hello. How can I assist you today?”

Perfect. Everything is working, and we’re ready to move on.

Before we start building integrations, I want to show you a few simple things about the editor to help you get more comfortable. We’ll add a little more each time.

First, let’s rename the workflow. Right now it’s called something like “My Workflow 6.” We can click on the name and change it to First Integrations, then press Enter. That’s now the new name of the workflow.

You may remember that workflows can also be tagged, similar to how blog posts are tagged. You can use this if you want to organize your workflows, though it’s optional.

Now, while you’re on the canvas, there are several useful navigation shortcuts. You can zoom in and out using the on-screen buttons, but there’s an even faster way.

If you’re on a PC, hold down the Control key. On a Mac, hold down the Command key—the one with the clover symbol. While holding it, click and drag on the canvas. You’ll be able to move around freely.

Try this yourself. Do it a few times.

As you do, notice the small mini-map in the bottom-left corner. It’s like the radar in a video game, showing the entire workspace and where your nodes are located. The white boxes represent the nodes in your workflow. This helps you orient yourself as workflows grow larger.

Next, let’s talk about keyboard shortcuts, because we don’t want to be clicking endlessly—we want to be pro users.

If you press the plus (+) key on your keyboard (no Shift needed), you zoom in. If you press the minus (–) key, you zoom out. If you press zero (0), the zoom resets to the default view.

This works without holding Control or Command, which makes it fast and intuitive. Plus to zoom in, minus to zoom out, zero to reset.

Another useful shortcut is the Tab key. Press Tab, and the node list opens on the right-hand sidebar. Press Escape, and it closes. Press Tab again—it opens. Escape closes it again.

Try pressing Plus, Minus, Tab, and Escape a few times to build some muscle memory for navigating the editor.

Now, let’s move on to Google Drive.

If you’ve never used Google Drive before, don’t worry—it’s extremely easy to pick up. If you don’t yet have a Gmail account, just go to gmail.com, create one for free, and you’ll automatically get access to Google Drive.

From there, you can click the app launcher in the top-right corner—the little grid icon—or just go directly to drive.google.com.

Once you’re in Google Drive, it works like most file-storage systems. You can create folders, upload files, and create new documents. I’ve already created a folder by clicking New → New Folder, and I named it “stuff.”

We’re now looking at the contents of that folder. If this interface is new to you, just click around—you’ll figure it out quickly.

And remember, if you really don’t want to use Google Drive, that’s fine. You can just watch along and focus on understanding how integrations work conceptually.

Now it’s time to create a document.

When I say “Google Doc,” I mean it in the general sense. Sometimes people use “Google Docs” to refer to any file in Drive, and sometimes they mean the word-processor specifically. In this case, we’re going to create a Google Sheet.

I’ll click New → Google Sheets, and here it is. Let’s name it Portfolio.

This is going to be a very simple sheet. We’ll add three columns:

Ticker

Quantity

Price

Under Ticker, we’ll add a few examples. Let’s start with Google—always a favorite. We’ll say we own three shares. Next, Apple—we’ll say two shares. And of course, Tesla, because that’s always the example people use. Let’s say two shares there as well.

So now we have a simple equity portfolio:

A ticker

A quantity

And a price column, which we’ve intentionally left empty

And that’s exactly where automation comes in.

Now that our data is ready, it’s time to build some automations.

# **O) Day 3 - How to Automate Stock Portfolio Tracker with n8n and Google Sheets**

Now I’m going to press the plus button here under Tools, search for Sheets, and open the Google Sheets tool.

Here it is.

This is how we give our LLM the ability to access a Google Sheet. The first thing it asks for is the credential to connect with, and we’re going to choose Create New Credential.

This is the moment where we connect our Nw10 cloud instance to Google Sheets. In many systems, this step can be really difficult and frustrating. For some integrations later on, this will be more challenging. But in the case of Google Sheets, it’s incredibly simple.

There’s a Sign in with Google button right here. Ignore everything else and just press that.

If you’re using the self-hosted version, this step is a bit more involved, but for now, we’ll just click Sign in with Google. A Google authentication screen pops up. I select my Google account, press Continue, and just like that, I see Connection successful.

I close the window, and now there’s a green box that says Account connected.

Honestly, it couldn’t be simpler.

At this point, our cloud instance is connected to our Google account. We haven’t connected it to a specific sheet yet, but the access is there. So I press the X button to return to the tool configuration screen.

Now we configure the tool itself.

The tool description can stay automatic. For the resource, we select Sheet within a document. For the operation, we choose Get rows.

Next, we choose the document from the dropdown. This list shows all the Google Sheets the account has access to. I select Portfolio, which is the sheet we just created. There’s only one sheet inside it, so I choose Sheet1.

There are options to add filters, but we’ll leave everything as-is. This tool is now ready.

So now we return to the main editor screen. We clear the chat, and we’re going to have a quick conversation with our sheet.

I type “Hi there.”
The agent responds as usual: “Hello, how can I assist you today?”

Next, I say:
“Please describe the sheet that you have access to read.”

The agent starts working. It connects to Google Sheets, pulls the data, and responds:

It tells me the sheet contains stock information with the columns Ticker, Quantity, and Price, and it lists the rows for Google, Apple, and Tesla along with their quantities.

That’s it.

We have successfully connected our Nw10 AI agent to a Google Sheet, and it took minutes—maybe even seconds if you were following along quickly.

Now let’s make it do something useful.

You can probably guess what’s coming next.

I move things around slightly on the canvas and add another tool—MarketStack, which we worked with yesterday. At this point, the setup should feel familiar.

We already have the credentials. The tool description stays automatic. The resource is End-of-day data, and the operation is Get many. The ticker is set by the model, and we turn on the Latest filter.

That’s all we need to fetch the latest stock prices.

Next, we add another Google Sheets tool. This time, the resource is still Sheets, but the operation is Update row.

We select the same Portfolio document and Sheet1.

Now comes the important part—telling the tool how to update the sheet.

The tool automatically detects the columns: Ticker, Quantity, and Price. We need to tell it which column to use to decide which row to update. We choose Ticker as the column to match on.

That means our AI can say, “Update the row where ticker equals Google” or “Apple” or “Tesla.”

Next, we define what values the model is allowed to set. We remove Quantity, because we don’t want to change it. We keep Ticker (for matching) and Price (for updating).

We explicitly tell the tool that the model defines the ticker and the model defines the price.

This tool’s job is now very clear:
Match on ticker → update the price.

We tidy up the canvas a bit, and now we have three tools:

Read rows from Google Sheets

Get market data

Update rows in Google Sheets

Now I open my Portfolio Google Sheet in a separate window and place it on the side so we can watch it live.

Back in Nw10, I clear the chat and say “Hi there.”
The agent responds normally.

Then I give the instruction:

“Please update the prices in my equity portfolio sheet to reflect the latest market prices.”

Now keep your eye on the spreadsheet.

The agent starts working. Messages are spinning. Tools are firing.

And then—bam.

Tesla’s price appears.
Apple’s price appears.
Google’s price appears.

All three prices are written directly into the Google Sheet.

The workflow executed successfully.

What we just witnessed was an AI agent reading a spreadsheet, fetching live market data, and writing updated values back into Google Sheets—all automatically.

That’s pretty fabulous.

What I love about this example is how tangible it feels. You can literally watch the numbers change in real time, which makes the power of integrations very real and very exciting.

Now, I want you to dig a bit deeper into the tools themselves.

Double-click on the Update Row tool. You’ll see the inputs and outputs from the last execution. Notice that it was called three times—once for each stock. You can switch between run 1, 2, and 3 and see exactly what data went in and what came out.

On the left, you see the inputs in JSON format. If you’re familiar with JSON, great. If not, don’t worry—you’ll get comfortable with it quickly. You can also switch between JSON, table, and schema views depending on what feels most intuitive.

You’ll see that the tool matched on Apple’s ticker and updated the price accordingly. The same happened for Google and Tesla.

Now do the same with the MarketStack tool. You’ll see it was also called three times—once per ticker—and you can inspect the returned market data for each one.

Finally, look at the Get Rows tool. This one was only called once, and it returned the entire sheet. You can view the result as JSON or as a table. What came back was the original data—tickers, quantities, and empty prices—before the AI updated them.

This gives you a full picture of how the workflow executed.

Now it’s your turn.

Dig into the tools. Explore the inputs and outputs. Switch between JSON and table views. Add another column. Try pulling in highs and lows. Experiment with what else the AI can write into the sheet.

Watch it update live.

It’s a little spooky—and incredibly powerful.

And this is what it feels like to work with an AI agent deeply integrated with Google Sheets.

# **P) Day 3 - How to Build an AI Agent to Automatically Draft Gmail Replies in n8n**

Next, we want to save our current workflow, because we’re going to build a new one. On a PC, you can press the red Save button, or use Control + S (on Mac, it’s Command + S). Once saved, it confirms with a “Saved” message.

Now we can go back to Personal or click Overview to return to the main screen. It’s time to create a new workflow. Press the Create Workflow red button. The first step, as before, will be a Chat Message trigger, though in future workflows we might try different triggers.

Next, we add another AI agent. At this point, you’re becoming a pro—you don’t really need me to guide you. We’ll use Simple Memory, and for the chat model, again, we’ll select OpenAI Chat Model. Let’s test it with a simple “Hi there,” and confirm everything is set up properly.

It’s now time to add a new tool. Press the plus button, type Email, and select the Gmail tool to consume the Gmail API. We then choose Create New Credentials, which brings up the Sign in with Google button. Click it and connect it to your chosen Gmail account—this could be your personal or business email. You can grant it access to everything or limit permissions based on your comfort level. Remember, we’re always in control of what the AI can access.

With the account connected, we return to the tool setup screen. We choose the resource Messages, because we want to read emails, not send them. The operation will be Get Many, but to avoid reading all emails, we apply a filter to only pull emails received after yesterday. Instead of hard-coding the date, we switch to Expression mode, which allows us to use a small JavaScript snippet (via Luxon library) to dynamically get “yesterday.” This keeps it flexible and dynamic, and it’s a good introduction to the low-code aspect of the platform.

At this point, our AI agent has OpenAI chat, Simple Memory, and the new Gmail tool. Before running, it’s useful to know the Tidy Up button, which automatically reorganizes and resizes the canvas—very handy when adding multiple tools.

Now let’s test the workflow. I send myself an email from a different account, saying: “I have exciting news. My agent in Nw10 can read my email. This is huge.” Then in the editor, I instruct the agent: “Please read the most recent email I received and summarize its content.”

The agent connects to Gmail, fetches the latest message, and responds:
“The most recent email you received is from Edward Donner with the subject ‘Important News.’ The content snippet indicates exciting news that the agent can now read emails, which is described as huge with many possibilities.”

We’ve now confirmed that our agent successfully read a real email. It’s amazing how quickly this works with just a few clicks. You can also expand this to add more tools for reading and sending emails later.

Next, we create another Gmail tool, this time to draft emails. I want to be careful here—rather than letting the agent send emails freely, we’ll constrain it. It can create a draft email, choose the subject and message content, but the recipient is locked to my Gmail address. This ensures full control while still allowing automation.

I then instruct the agent: “Please draft an email saying I very much agree with this sentiment. This is huge news.” The workflow runs, and when I check my Gmail, there’s a draft email ready. It reads:

“Hi Edward,
I very much agree with your sentiment. This is huge news. The possibilities ahead are truly exciting.
Best regards, Edward.”

And just like that, the agent has read an email and drafted a response, fully respecting the constraints we set.

Of course, we could extend this further—have it create new emails, respond automatically, or submit them—but we chose to be careful and only give access to tools we trust. This is a good practice until you’re confident in your checks and balances.

So, to recap: today we read emails and drafted a response, showing how agents can interact safely with Gmail. The possibilities are enormous, but we take baby steps to build confidence.

With that, we wrap up Day Three of Week One. These were our first few integrations, and they were exciting ones:

We connected to Google Drive and Sheets and automated stock price updates.

We connected to Gmail, allowing an agent to read and draft emails.

The goal is not just to watch but to experiment yourself—build workflows, inspect nodes, examine tool inputs and outputs, and practice passing data between steps. Tomorrow, we’ll continue with more integrations, explore JSON and table views, and get even more comfortable with connecting AI agents to various data sources.

And just like that, week one, day three is complete. Can you believe it—20% of the course done already? We’ve built what could practically be an automated business process in just a few days. It only gets better from here.

See you tomorrow!

# **Q) Day 4 - Understanding JSON in n8n: Key-Value Pairs, Objects, and Arrays**

We have a big day ahead of us. Welcome to week one, day four. This is an important day. It’s the second yellow day focused on digging into integrations, and in addition to that, we’re also going to talk about data. We’ll also take a look at expressions, at least at a high level. Let’s get into it.

In NHSN, data is largely described using a format called JSON. I imagine that at least half of you are already very familiar with JSON. Some of you may have seen it many times, some of you might come from a JavaScript background and know it inside out, and some of you may be newer to it. You’ve probably encountered it before, even if you don’t fully understand it yet. I’ll cover it briefly, but the main takeaway is this: you will get very familiar with JSON. You’re going to see it a lot.

JSON is a very simple and standard way to describe structured data. It’s designed to be both machine-readable and human-readable, which makes it very convenient. Machines understand it, humans understand it, and that allows us to work with it together effectively.

Let’s cover the four basic ingredients of JSON. If you already know all of this, feel free to mentally fast-forward. If not, this will give you a solid foundation.

First, JSON is fundamentally a way of describing data using key–value pairs. This means that everything has a name (the key) and a value. For example, a person might have a first name with a value, a last name with a value, and an age with a value. These key–value pairs form the core of JSON. The values themselves can be text (called strings), numbers, booleans such as true or false, or a few other types as well.

The second key ingredient in JSON is called an object. An object is simply a collection of key–value pairs grouped together. For example, a person object might include first name, last name, age, and other attributes. Objects are sometimes also called dictionaries, which will sound familiar if you come from a Python background, since they are very similar to Python dictionaries.

The third ingredient is an array. An array is just an ordered list of things. It can contain multiple items, one after another, in a specific order.

The fourth ingredient is nesting. This means that a JSON object doesn’t just contain simple values like strings or numbers. It can also contain other JSON objects and arrays. Those nested objects can themselves contain more objects and lists. In practice, you often see JSON structures that are made up of many layers of objects inside objects, and arrays containing objects, and so on.

Now let’s talk a bit more about each of these in detail.

Starting with key–value pairs: all data in JSON is represented this way. You write a key, followed by a colon, followed by a value. For example, "name": "Alice", "age": 30, or "is_student": false. You could also have something like "middle_name": null.

There are a few important details to notice here. Whenever you use text (strings), you must put double quotes around it. That applies to both the key and the value if the value is text. Numbers do not have quotes around them. Booleans are written as true or false, always in lowercase. This can trip up people coming from Python, where booleans are written differently. The value null is a special value that represents “no value” or “empty,” and it is valid in JSON.

It’s also important to use double quotes, not single quotes. Another common issue is curly quotes—some word processors automatically convert straight quotes into curly ones, and those will break JSON. JSON requires straight double quotes. Additionally, while it is technically allowed to have spaces in keys, it’s best practice not to. Instead of "is student", it’s better to use something like "is_student", as spaces can cause problems in many situations.

Next, let’s look at objects. An object represents a thing with multiple key–value pairs. Objects are written using curly braces. You open a curly brace to start the object, then list the key–value pairs separated by commas, and finally close the curly brace.

For example, an object might contain "name": "Alice", "age": 30, "is_student": false, and "middle_name": null. Each key–value pair is separated by a comma, except for the last one. The final entry must not have a trailing comma. This is different from some programming languages like Python, where trailing commas are allowed.

You’ll often see objects written with indentation and whitespace to make them easier for humans to read. This formatting does not matter to the machine—it’s purely for readability. The same object could be written all on one line and would mean exactly the same thing.

Now let’s talk about arrays. Arrays are written using square brackets. An array might look like ["apples", "bananas", "oranges"]. Each element in the array is separated by a comma. Arrays can contain numbers, strings, booleans, or even a mix of different types if you want.

Arrays themselves are values, which means they can be used as the value in a key–value pair. For example, you might have "favorite_fruits": ["apples", "bananas", "oranges"]. That entire list becomes the value associated with the key.

Finally, let’s look at nesting in more detail. Arrays can contain objects. For example, you could have an array where each element is an object representing a person, such as one object for Alice with her name and age, and another object for Bob with his name and age. Writing it this way makes it clear that the array has multiple elements, and each element is its own object.

Similarly, objects can contain other objects. For example, you might have an address object with keys like street, city, and country. That address object can then be used as the value for an "address" key inside a larger object that also contains a person’s name and age. In this case, the address is not text, a number, or an array—it is itself another object nested inside the main object.

This should give you a good sense of how JSON works and how flexible it is. Objects can contain arrays, arrays can contain objects, and everything can be nested as deeply as needed. If this is all new to you, don’t worry—once you start seeing JSON regularly, it will quickly become second nature.

With that overview in place, next up we’re going to talk about expressions.

# **R) Day 4 - n8n Authentication Methods: API Keys, OAuth2, and Workflow Integration**

This is not a no-code course. It’s a low-code course, which means that occasionally we will take small steps in the direction of coding. One of the main ways we do that is through expressions—and you’re going to love expressions.

Expressions give you much more flexibility in how your workflows run. They give you significantly more power over what happens in your automations. Instead of using fixed values everywhere, expressions allow you to determine values dynamically. You can decide what should be used at runtime rather than hard-coding things upfront.

A good way to think about expressions is like formulas in Excel. Instead of typing a fixed number into a cell, you write a formula that calculates the value. Expressions work the same way. And honestly, they are not complicated. They may look intimidating at first—much like Excel formulas—but once you understand the idea, and once you have a few expressions in your toolkit that you can reuse, they become very easy to work with.

We’re going to look at some expressions now, and then we’ll start using them properly in real integrations. If this part feels a bit theoretical, don’t worry—we’re about to put all of this into practice very soon.

In NHSN, there are many fields where you’ll see a small toggle above the field. This toggle lets you switch between a fixed value and an expression. That’s where we’ll be using expressions today. You can choose to say, “I always want this value to be 3,” or you can provide a small formula that dynamically calculates what the value should be.

Expressions are always surrounded by double curly braces—two opening curly braces and two closing ones. You’ll get very used to seeing these everywhere. When you see double curly braces, that should immediately click in your mind: this is an expression, and there’s logic happening here.

There’s a very important shortcut to know. If, inside an expression, you want to access the incoming data from the previous node, you use a special variable: $json. This means “give me the incoming data in JSON format.”

A lot of working with expressions comes down to navigating through JSON objects. Remember that JSON is made up of key–value pairs, and the value itself can also be another object with its own key–value pairs. Very often, you’ll be doing things like taking a person object and pulling out the first name, or taking an address object and extracting the country from it.

To do this, you use a dot (.). For example, if you have a JSON object representing a person with a name, age, and address—and the address itself has a street, city, and country—then writing $json.name will extract the person’s name. Writing $json.address will extract the entire address object. Writing $json.address.city will extract just the city value.

If you look at the examples carefully, you’ll see how those dots allow you to drill deeper into the JSON structure and pluck out exactly the piece of data you need. That’s really all you need to understand about JSON data structures and how expressions navigate through them.

At various points, we’ll also use expressions that are slightly more advanced than simple $json lookups. You don’t need to understand these right now—I just want you to recognize what they look like. We’ll work with them properly later, and they’ll make much more sense when you see them in action.

For example, $json gives you access to the incoming data for the current node. But what if you want to access data from an earlier node in your workflow? In that case, instead of $json, you use $node. You write $node["Node Name"] and then continue drilling into its data structure. This allows you to grab data from any previous node in the workflow.

This is powerful because it means you can write expressions that combine information from multiple points across your entire workflow, not just the immediately previous step.

Another useful thing to know is how to convert JSON data into a string. Sometimes you want to pass data as plain text, for example when sending it to a language model. In that case, you can use JSON.stringify(). You write JSON.stringify() and pass in whatever data you want inside the brackets—such as $json. This converts the JSON object into plain text.

If you’re new to all of this and it doesn’t fully click yet, that’s completely fine. Just hold onto the general idea. The understanding really comes when you start building things and experimenting. If you already know JSON, then these are simply a couple of extra expressions worth adding to your mental toolkit.

As a general principle, you never need to memorize expressions. Don’t try to memorize syntax. As long as you understand what expressions do and how they work conceptually, you can always look up the exact syntax when you need it. The documentation in n8n is excellent, and tools like ChatGPT or Claude can tell you exactly which expression to use. What matters most is recognizing what the correct solution looks like when you see it.

That’s enough on JSON and expressions for now—just enough to allow us to build a lot more integrations. Before we start doing that, though, I want to introduce the topic of the integrations we’ll be working on today, because they’re going to be a lot of fun.

Often, the trickiest part of building an integration with a third-party service is authentication. Authentication is about proving to the third party that you are who you say you are. There are many different ways to do this, and today we’ll be using several of them.

Here are the authentication approaches we’ll be using, listed in order of increasing complexity.

The simplest method is using an API key. In this approach, you generate an API key with a third-party service and then provide that key to n8n. Once the key is validated and turns green in n8n, you’re connected. That’s what we did with OpenRouter and OpenAI, and we’ll do the same with many other services.

An API key is essentially a password or secret. Once it’s set up, everything just works. If only all integrations were that simple.

Things get more complicated when you don’t just want a single generic connection to a service, but instead want to log in as a specific user. For example, you don’t want to connect to Gmail in general—you want to connect specifically to your Gmail account. That requires authentication at the user level, and that’s where OAuth 2 comes in.

OAuth 2 is the standard method used for secure, user-specific authentication with third-party platforms. The next two authentication types we’ll use are both different flavors of OAuth 2.

The simpler OAuth 2 pattern is what we used with Google Sheets and Gmail. In this case, n8n Cloud already has a pre-configured OAuth setup. You click a button, a Google login screen opens, you sign in, and you’re done. You are authenticated as a specific user.

This only works in n8n Cloud, and only for services where n8n Cloud has already built the necessary infrastructure. Google Sheets and Gmail are good examples. The bridge between n8n and Google is already in place, so the process is quick and painless.

The hardest case is full OAuth 2, where that shortcut doesn’t exist. This applies when you’re running self-hosted n8n, or when you’re using n8n Cloud with a service that doesn’t have a pre-built OAuth connection. Slack is a good example of this.

In these cases, you have to build the OAuth scaffolding yourself. You need to configure callback URLs, permissions, and multiple steps in the authentication process. Proper OAuth 2 is quite fiddly. It often requires patience and a thick skin. You may need to try two or three times before everything finally works.

The good news is that once the authentication is done, it’s done. After you’ve successfully authenticated with a service like Slack, you can reuse that authentication across your workflows simply by selecting it from a dropdown. It’s a one-time setup per service.

Now that you know this, we’re ready to build some integrations. Enough talking—let’s get practical.

We’re going to build three integrations today, all focused on communication and connectivity.

The first one is push notifications to your phone. This is one of my old favorites because it’s simple, fun, and very satisfying to see something pop up on your phone as a result of a workflow. This will be a gentle, API-based integration.

The second integration will be Telegram. You may or may not use Telegram, and that’s okay. Even if you don’t plan to use it, it’s still a great example of how integrations work in n8n. The same principles apply to many other services, so it’s worth seeing how it’s done.

The third integration is Slack—and Slack is going to be painful. Prepare yourself. This will involve the full OAuth 2 flow, and it can be frustrating. If you don’t feel like doing it yourself, you can simply watch and learn. It’s still valuable to see how the process works.

As a quick survival guide for integrations: if something goes wrong, try again. Many integrations fail the first time and succeed on the second or third attempt. Pay close attention to error messages and clues about what might be wrong.

Post questions in Udemy if you get stuck. I may or may not be able to reproduce your exact issue, but someone almost certainly can help. Share screenshots, explain what you’re seeing, and we’ll try to figure it out together.

Also, read the documentation. The n8n docs are very clear and extremely helpful. Use them alongside experimentation.

And if all else fails, just pick a different integration. One of the amazing things about n8n is how many integrations it offers. If Telegram isn’t working for you, try Slack. If Slack is too painful, try push notifications. There are plenty of options, and at least one of them will work.

With that, let’s go back to n8n. We’re going to build three communication-focused integrations. Have a thick skin—but it’s going to be fun. Let’s do it.

# **S) Day 4 - How to Integrate Pushover Notifications with n8n Workflows**

Okay, first up, we’re going to build an integration that sends push notifications directly to our phones. For this, I’m going to use a tool called Pushover. It’s a really neat little service that I love and use in all my courses. It’s extremely straightforward to set up, and it’s free for the first month at least. After that, it costs a very small amount, but you only really need it for the duration of this course—unless, of course, you end up loving it and want to keep using it.

The first thing you should do is go to pushover.net. This is what the site looks like. Once you’re there, click on Sign Up and create a new account.

After you create your account and log in, you’ll immediately see an API key on the page. This is called your User Token or User API Key, and it starts with the letter U. You’ll find it at the top right of the screen. This is the first of two tokens that you need for this integration.

When you log in, you’ll see a screen like the one I’m showing here. My own user token is visible on my screen, but I can’t show it to you because it would give full access to my account. Just know that this user token is printed right on the main page after login, and it always starts with the letter U.

The second token you need comes from creating an application. To do this, click on Create an Application / API Token. Inside that page, give your application any name you like—it doesn’t matter what you call it. Once you create the application, you’ll be given a second token. This one is called the Application Token, and it always starts with the letter A.

At this point, you should have two tokens:

A User Token starting with U

An Application Token starting with A

The final setup step is to install the Pushover app on your phone, whether you’re using an iPhone or an Android device. Once you install it and log in, your phone will appear in the list of devices on the Pushover website. At that point, everything is connected, and you’re ready to start sending push notifications from n8n. You can also use the Pushover website to test that notifications are arriving correctly.

Now, let’s go back to n8n.

I’ve already logged in and selected my instance. Since you’re pros at this point, I’m going to create a new blank workflow by clicking the Create Workflow button.

Next, I’ll add the first step by clicking Add First Step. I’m going to choose Chat Message, and then I’ll press Escape to come back to the main workflow view.

After that, I’ll click the plus button again and add an AI Agent, then press Escape once more. I’ll assign a chat model to it—OpenAI in this case—but you can use any model you like. Now the chat model is set up.

I’ll also add Simple Memory, which is exactly what we’ve done before and should feel very familiar by now.

Now it’s time to add a tool. Before doing that, just a reminder that you can click the Tidy Up button to make everything look neat and organized.

I’ll press the plus button under tools and search for Pushover. Sure enough, there is a Pushover tool available. Once I add it, the first thing we need to do is authentication.

To authenticate, we select Create New Credential. This is the simplest type of authentication—just an API key. The important thing to remember here is that the API key you paste into this field must be the Application Token, the one that starts with the letter A. If it doesn’t start with A, it’s the wrong token.

I paste in the application token, click Save, and n8n thinks for a moment. If everything is correct, the credential turns green. That’s exactly what you want to see. If it doesn’t turn green, something is wrong—go back and double-check that you used the token starting with A.

Once that’s done, we move on to the next field: User Key. As you might guess, this is where the User Token goes—the one that starts with the letter U and appears on the Pushover dashboard when you log in. I’m not pasting it on screen because it shows in full, but that’s what goes here.

There’s also a Message field. Whatever you put into this field will be sent as a push notification. If you typed the word “bananas” here, every time this tool runs, it would send “bananas” to your phone. That’s not very useful.

Instead, we want the language model to decide what message to send. To do that, we click the button that says Let the model define this parameter. This allows the AI to dynamically generate the message content, which is exactly what we want.

After pasting in the user key, we save again. It’s worth making sure the workflow is actually saved. You can press Ctrl + S on Windows, Command + S on Mac, or click the Save button. Once it says “Saved” and the red highlight disappears, you’re good.

Now let’s tidy things up again to keep the workflow looking clean.

Next, I’m going to add one more tool. I’ll click the plus button and search for Date. I’ll add a Date & Time tool and choose the operation Get Current Date. There are several options here, but we’ll just leave it at that. This tool allows the language model to access the current date. It’s simple, but it might come in handy.

Now let’s test everything.

I’ll type “Hi there” as a starting point. The assistant responds with something like, “Hello, how can I assist you today?”—which we’ve all seen many times by now.

Next, I’ll say: “Please send me a push notification with today’s date.” Keep an eye on the right-hand side as it runs.

And there it is. Did you hear the notification sound? I got a push notification on my phone with today’s date. It worked.

If you didn’t hear a sound, that’s okay. Pushover has notification settings that control whether a sound is played. I personally set the priority to high so it makes a satisfying noise, but that’s entirely optional.

The important thing is that the notification arrived. If it didn’t work for you, don’t panic. Go back, double-check the keys, and try again. This is the simplest type of integration using API keys, and once it works, it works reliably.

And that’s it. You’ve now built a working integration using API-key-based authentication. You can send push notifications to your phone from any workflow you build in n8n.

That’s a powerful capability—and it’s just the beginning.

# **T) Day 4 - Create Telegram Bot Using n8n: Complete AI Chatbot Integration Tutorial**

First, I’m going to save this workflow as the Push Workflow. Once that’s saved, I’ll go back to the Personal workspace. At this point, the push workflow is ready.

Next, we create a new workflow specifically to integrate with Telegram. This workflow is only meant for Telegram users. If you’re not a Telegram user, you can skip this part. Telegram is very similar to WhatsApp and is especially good for this kind of automation. I’ll walk you through the entire process.

Telegram integration is API key–based, which makes it very simple. If you’re using Telegram on your phone or desktop app, the first thing you need to do is search for a specific user called BotFather. You’ll find it by typing botfather into the search bar. Even though the name sounds odd, BotFather is what Telegram uses to create and manage bots.

Once you open a chat with BotFather, you’ll see a screen similar to mine, showing that you’re chatting with BotFather, which has millions of monthly users. The first command you type is /start, which displays a list of available commands.

From there, you type /newbot. This tells Telegram that you want to create a new bot. Telegram will then ask you to provide a name for your bot. In my case, I named it something like TG_convo, but you can choose any name you like.

After naming the bot, Telegram will ask you to choose a username for it. This username must end with “bot”, for example tetris_bot or tg_convo_bot. I named mine tg_convo_bot, but again, any name is fine as long as it ends with “bot”.

Once that’s done, Telegram responds with a congratulatory message confirming that your bot has been created. It also provides a link to your bot and mentions that you can add a description, profile picture, and other settings later. At this stage, the bot is operational.

Immediately after this, Telegram provides you with an API key. This key is extremely important. You should carefully copy it, making sure there are no extra spaces at the beginning or end. This API key is what we’ll use to connect Telegram to N8N.

There is also another way you might encounter BotFather, where it opens in a separate interface with menu options like “Create New Bot”. Either way, the end result is the same: you create a bot and receive an API key. Once you have that key, you’re ready to integrate Telegram with N8N.

Now we move to N8N. Inside N8N, click Create Workflow. Add a first step and search for Telegram. When you select Telegram, you’ll see a list of triggers—these are events that can start a workflow.

Choose the trigger called On Message. This means whenever a message is received in Telegram, the workflow will start. Once selected, the Telegram node opens and asks for credentials.

Click the credentials dropdown and choose Create New Credential. It asks for an access token, and this is where you paste the Telegram API key you copied earlier. After pasting it, click Save. If everything is correct, the connection turns green and shows “Connection tested successfully”.

With that done, your trigger is ready. Now we add the second step. Click the plus button, go to AI, select AI Agent, and choose OpenAI as the chat model. Disable memory (use simple memory or none) and don’t add any tools initially.

Optionally, you can add a tool to provide the current date and time to the AI agent. Once that’s configured, move on to the next step.

Click the plus button again. This step defines what happens with the output of the AI agent. Search for Telegram again, but this time select Actions, not triggers. Choose Send a Text Message.

For credentials, it automatically uses the same Telegram credentials you already set up. You don’t need to create them again. The text we want to send back should come from the output of the previous AI agent node.

There’s an extra complication here. Telegram conversations are tied to a chat ID, and when sending a message back, we must make sure it goes to the same chat that triggered the workflow. This means we need to correctly pass the chat ID along with the message.

To understand how this works, the easiest approach is to first test the workflow without fully configuring everything and see what breaks.

Before testing, deactivate the Send Text Message node by clicking the power button so it’s turned off. Also deactivate the memory node, as it can interfere during testing. Then click Execute Workflow.

At this point, N8N starts listening for Telegram messages. Now go to Telegram, open the chat with your bot, and press Start. As soon as you send a message, the workflow will likely fail.

When it fails, you’ll see an error saying “No prompt specified”. Double-click on the AI Agent node to inspect what’s happening.

On the left side, you’ll see the incoming data from Telegram in JSON format. This includes several nested objects, such as message, which itself contains fields like text.

The problem is that the AI agent is expecting a chatInput field, which does not exist in Telegram’s JSON payload. Telegram is not a chat trigger—it’s an API trigger—so we need to explicitly tell the AI agent where to get the prompt text from.

The correct input is the message text sent by the user in Telegram. You can clearly see it inside the JSON under message → text.

To fix this, go to Source for Prompt in the AI agent node. Instead of selecting a chat trigger, choose Define below and use an expression.

Now click and drag the text field from the JSON panel into the prompt input. N8N automatically generates an expression like {{$json.message.text}}. This tells the AI agent to use the Telegram message text as the prompt.

You could also manually type this expression, and you’ll see the resolved value (for example, /start or hi there) displayed below it.

Now the AI agent is correctly receiving input from Telegram.

Click Execute Workflow again. Go back to Telegram and type a message like “hi there”. The workflow runs successfully.

If you open the AI agent node, you’ll see that the input text (“hi there”) was correctly extracted and sent to the language model. The model responds with something like “Hello! How can I assist you today?”

This confirms that the integration is working. We successfully extracted Telegram input using expressions, passed it to the AI agent, and received a valid response.

This is a slightly more advanced integration compared to basic workflows, but as you can see, it works end to end once everything is wired correctly.

# **U) Day 4 - How to Integrate Telegram Bot with n8n AI Agent Workflow Automation**

Now it becomes a bigger deal, because we’re going to hook up the output of the AI agent so that it sends messages back to Telegram. This is the final and most important part of completing the integration.

To begin, we turn the power back on for the Send Text Message node. Double-click the node so we can see its configuration again. Remember, to send a message back to Telegram correctly, we need to provide two things: the chat ID and the text. The chat ID ensures that the reply goes back to the same person who sent the original message.

Let’s start with the Text field. On the right side, you’ll see a toggle between Fixed and Expression. This toggle is critical. Fixed means the bot would always reply with the same static text, like “bananas,” no matter what the user says. That’s not what we want.

We want the text sent to Telegram to be dynamic, based on the output of the AI agent. So we switch the toggle to Expression.

Now, what exactly are we pulling in? If you look at the data coming from the AI agent, it’s JSON. Specifically, it’s a single object containing one key-value pair. The key is called output, and the value is something like:
“Hello! How can I assist you today?”

That output field is exactly what we want to send back to Telegram.

To do this, we enter an expression using curly braces. When you type two opening curly braces, the closing ones appear automatically. Inside the expression, we start with $json, which refers to the incoming JSON object. Since the object has a field called output, we simply append .output.

So the full expression becomes {{$json.output}}. As soon as you enter this, you’ll see a preview showing the actual text value, such as “Hello! How can I assist you today?” That confirms it’s working correctly.

At this point, the Send Text Message node is now correctly wired so that whatever the AI agent produces will be sent back to Telegram.

There is an easier way to do this, of course. Instead of typing the expression manually, you can simply drag and drop the output field from the AI agent’s JSON into the Text field, and N8N will generate the expression automatically. However, walking through it manually helps you understand exactly what’s happening under the hood.

Next comes the Chat ID, which is slightly trickier.

Once again, we don’t want a fixed value here. Each Telegram conversation has a unique chat ID, and we must respond using the same one that triggered the workflow. So we switch Chat ID to Expression mode.

Now the question is: where does the chat ID come from?

It comes from the Telegram trigger, which is the very first node in the workflow. In the incoming data panel, there’s a dropdown that lets you inspect data from earlier nodes. Select the Telegram trigger node from that dropdown.

When you look at its JSON, you’ll see fields like message ID, chat, and inside chat, a chat ID. That’s exactly what we need.

Wouldn’t it be nice if you could just drag that chat ID directly into the Chat ID field?
Good news—you can.

Click and drag the chat ID value into the Chat ID field and release it. N8N automatically creates the correct expression for you. Even if the expression looks complex, you don’t need to worry about writing it yourself. Drag-and-drop handles everything.

You’ll also see a preview value, which confirms that the chat ID is being resolved correctly.

Now everything is wired up. The AI agent produces an output, that output becomes the Telegram message text, and the chat ID ensures the reply goes back to the correct conversation.

Let’s test it.

Click Execute Workflow so the workflow starts listening for Telegram messages. Open Telegram, bring the chat window into view, and send a message such as:
“Hi there, what’s two plus two?”

The workflow runs, and a moment later, Telegram replies:
“Two plus two equals four. How can I assist you further?”

It worked.

At this point, we’ve successfully created a full conversational loop. A message comes in from Telegram, the workflow triggers, the AI agent processes the input, and the response is sent back to the same Telegram chat using the correct chat ID.

Now there’s one more important detail: memory.

The Simple Memory node needs a session key so it knows how to associate messages with a specific conversation. By default, it assumes it’s connected to a chat trigger, which isn’t true in this case. That default setup won’t work.

We need to define our own session key.

Open the Simple Memory node and change the session key source to Define Below, then switch it to Expression mode. What should we use as the session key? The chat ID makes perfect sense.

So we drag the same chat ID expression into the session key field. This ties the memory directly to that Telegram conversation.

Turn the Simple Memory node back on—it was disabled earlier—and press Execute Workflow again.

Now let’s test memory.

In Telegram, send:
“Hi there, my name is Ed.”

The bot responds appropriately.
Then send another message:
“What’s my name?”

The response comes back:
“Your name is Ed.”

That confirms the memory is working.

You can experiment further here. Instead of using the chat ID as the memory key, you could use the Telegram username. That way, the memory would persist even across different chat sessions with the same user. Depending on your use case, that might be an even better approach.

At this point, we’ve built a two-way Telegram integration. Telegram messages trigger the workflow, the AI agent processes them, responses are sent back to Telegram, and memory is maintained per conversation.

There’s just one last wrinkle.

Up to now, we’ve had to keep pressing Execute Workflow every time we wanted to test a message. That’s fine for testing, but it’s not how a real automation should work.

Everything so far has been running in test mode.

To make this workflow truly live, we need to publish it.

First, save the workflow. Then press the Publish button. You’ll be asked to provide a version name and optionally a description. Enter whatever you like and confirm.

Once published, N8N tells you that the workflow is now live and listening for events from Telegram. At this point, you won’t see nodes lighting up anymore—because the workflow is running in production.

Now try messaging your Telegram bot again.

Send:
“Hi there.”

The bot responds immediately.

Ask something like:
“What’s the current date?”

If everything is set up correctly, the AI agent will call the date tool and respond with today’s date. The workflow is now fully deployed, running live, and handling messages automatically.

This confirms that the Telegram integration works end to end, including tool usage and memory, and is now running in production.

Once you’re done experimenting, you can stop it by clicking the three dots at the top and selecting Unpublish. You’ll see a confirmation that the workflow has been unpublished.

You can rename it something like Telegram Workflow, save it, and head back.

That completes the Telegram integration. It was a deep one—covering triggers, expressions, memory, responses, and publishing to production.

Now, if you thought this one was a bit intense…
the next integration is even more grueling.

It’s time for Slack.

# **V) Day 4 - How to Build a Slack Bot with n8n OAuth Integration and Automation**

Okay, welcome to Slack time. This is our third and most hardcore integration, and it’s with the business messaging platform Slack.

To do this integration properly, you need access to a Slack workspace where you have admin permissions, because we’ll be creating a Slack app and bot. If you don’t have admin access, that’s totally fine—just follow along and observe. This is still very valuable because it exposes you to OAuth-based integrations, which are common and important in real-world systems.

In my case, I’m in my own Slack workspace where I do have admin permissions. You can tell because I see the admin controls. The first thing I do is go down to Apps and workflows and select it. This takes us into the app-management side of Slack, where we’ll set up a Slack app and Slack bot.

When I click this, Slack opens a web browser and lands me on the Installed Apps page. You’ll see a list of apps already installed in the workspace. In my case, there are a couple of previous attempts—I’ve actually done this twice already, successfully, but with quite a bit of frustration along the way. Still, it works, and so can yours.

One important thing that often takes a while to remember is where to start. Look at the top-right navigation. There’s a menu, and from there, you need to click Build. This takes you to the app-building interface.

On the Build page, you’ll see a button that says Create New App. Click that, and then choose From scratch. Slack now asks you to give your app a name. I’m calling mine N8N3, because this is my third attempt, but you can name yours anything you want.

Next, you select the workspace where this app will live. Once that’s done, click Create App. Slack creates the app and drops you into a configuration screen. There’s a lot here—many menus, many settings—and we’ll be touching several of them. Many of the IDs and tokens found here will later be required inside N8N.

The first—and arguably most important—section we need to visit is OAuth & Permissions. This is where Slack defines what your app is allowed to do.

OAuth uses the concept of scopes, which specify permissions. Scopes define exactly what actions your app and bot are authorized to perform. We need to add several scopes for our bot to function correctly.

Click Add OAuth Scopes. A long list appears. I’ll walk you through the exact ones we need. I discovered these mostly by trial and error—adding too few, hitting errors, and then coming back to add more.

The first scope to add is app_mentions:read. As you type, Slack filters the list, making it easy to find. This allows the bot to read messages where it is explicitly mentioned.

Next, click Add again and select channels:history. This allows the bot to read messages from channels it’s part of.

Add another scope: channels:read. This lets the app read channel information.

Next, add chat:write. This is critical—it allows the bot to send messages into Slack channels.

Then add im:history, which allows the bot to view direct messages in channels where it has been added.

Finally, add users:read, which allows the app to read information about users in the workspace.

Once all scopes are added, click Install to Workspace. Slack will ask you to confirm that the N8N3 app is allowed to access the workspace with these permissions. Click Allow.

At this point, Slack generates a Bot User OAuth Token. This token is extremely important—we’ll need it shortly inside N8N.

Next, we move to Event Subscriptions, which is the section right below OAuth & Permissions.

Event subscriptions define when Slack should call out to an external system—in our case, N8N—to notify it that something has happened.

Turn Enable Events on. Slack will ask for a Request URL, which is the URL Slack will call when an event occurs. We’ll come back to this later, once N8N gives us that URL.

Before that, we need to specify which events we care about. Under Subscribe to Bot Events, click Add Bot User Event and select app_mention. This means Slack will trigger events only when someone mentions the bot in a message.

At this point, we’ve enabled event subscriptions and defined the type of events we want Slack to send. The plumbing on the Slack side is partially in place.

Now it’s time to move over to N8N.

In N8N, click Create Workflow and add a first step. Search for Slack. We’re adding a trigger, and the trigger we want is Bot App Mention.

Select that trigger. Now we need credentials. Click Create New Credential. The first required field is the Access Token.

To get that token, go back to Slack. Navigate to your app, open OAuth & Permissions, and copy the Bot User OAuth Token.

Return to N8N, paste the token into the credential field, and click Save. If everything is correct, you’ll see Connection tested successfully, which is a very important confirmation.

There’s an optional field here for a Signing Secret, which Slack recommends for added security. You can find it under Basic Information in the Slack app settings. However, in my experience, using it caused technical issues, so I’m skipping it for now. You’re free to try it if you want, but be prepared to debug.

Now let’s finish configuring the Slack trigger.

The next step is selecting which channel the trigger should listen to. For that, we need to go back to Slack one more time.

In Slack, I create a new channel. I go to Channels, click Create Channel, and name it convo3 (since I’ve done this a few times already—you can call yours whatever you want). I leave it as a public channel and press Create.

Once the channel exists, I invite the bot into it by typing:
/invite @N8N3

Now the bot is a member of the channel.

Next, I need the channel ID, not the channel name. To find it, I click the three dots (More actions), choose Edit settings, scroll down to the About section, and there I see the Channel ID. I copy it to the clipboard. This step is easy to miss and took me a while to find initially.

At this point, the channel exists, the bot is in it, and we have the channel ID copied.

Now we go back to N8N again.

In the Slack trigger configuration, for Channel to Watch, select By ID, and paste the channel ID you just copied. This tells N8N exactly which Slack channel to listen to for bot mentions.

With that, the Slack trigger is now correctly configured.

There is still one more major step left, and it’s an important one—but that’s coming up next.

This part alone already shows why Slack is the most complex integration so far: OAuth scopes, tokens, event subscriptions, channel IDs, bot invitations, and back-and-forth setup between Slack and N8N.

And we’re not done yet.

# **W) Day 4 - Connect Slack to n8n Using OAuth2 and Webhook Triggers Step-by-Step**

At this point, you’re probably feeling like Slack is trying to personally hurt you. And honestly, that reaction is completely fair. We’re only halfway through, and this is already the hardest integration so far. But here’s the good news: this is about as hard as it gets. Once you’ve done a few integrations like this, you start seeing the same patterns again and again. You build a mental toolkit—OAuth, webhooks, scopes, triggers—and each new integration becomes easier.

Now we’re back in N8N, looking at the Slack trigger node, exactly where we left off. We’ve already configured the channel ID and most of the settings. But there’s one critical thing we intentionally left unfinished earlier.

Back in Slack, when we were setting up Event Subscriptions, we left the Request URL blank. This is the URL Slack needs in order to call N8N when a message arrives. To solve that, we need to use webhooks from N8N.

In the Slack trigger node, there’s a collapsed section called Webhook URLs and webhooks. These are the endpoints external systems can call to trigger this workflow. N8N conveniently gives us two URLs: one for testing and one for production.

We’ll start with the test webhook. Toggle to the test URL, click Copy, and it’s now in your clipboard. Before going back to Slack, there’s one very important step: press Execute Step on the Slack trigger node. This puts the workflow into listening mode, waiting for Slack to call that webhook.

Now we go back to Slack.

We open our app again and return to Event Subscriptions. At this point, I realize something important—I forgot to press Save Changes earlier. This is very easy to do in Slack, and it will absolutely break things if you miss it. So we carefully redo this section.

We turn Enable Events on. Under Subscribe to Bot Events, we add app_mention again. Then, in the Request URL field, we paste the test webhook URL we copied from N8N.

Immediately, Slack shows Verified. That only happens because N8N is actively listening. If you don’t see “Verified,” Slack will show “Not verified,” and you’ll have to retry—sometimes multiple times. Once it’s verified, we press Save Changes.

At this point, the Slack trigger is officially wired up. Slack can now send events into N8N.

Back in N8N, we continue building the workflow. As usual, we add an AI Agent node. By now, this should feel familiar. We select an OpenAI chat model. For now, we’re not adding memory or tools—we just want to complete the round trip.

Next, we add a Slack node on the output side. This time, it’s an action, not a trigger. We configure it to send a message. The resource is Message, the operation is Send, and we choose Send to Channel.

For the channel, we again select By ID and paste in the same channel ID we copied earlier from Slack. This ensures messages are sent back to the same channel.

For now, we keep the message text very simple. We leave it as a fixed string and just type “bananas”. This helps us verify the plumbing before adding expressions.

Now we test.

We press Execute Workflow so N8N starts listening. We go back to Slack, open the channel, and send a message mentioning the bot—for example, “Hi there.” We press Enter and wait.

The workflow runs. The Slack trigger fires. That’s a huge win already. If it didn’t fire for you, it means something earlier was misconfigured and needs careful checking.

However, the workflow errors with “No prompt specified”. This should look familiar. We saw this exact issue during the Telegram integration.

When we open the AI Agent node, we see what’s happening. The agent thinks it’s connected to a chat trigger and is looking for chatInput, but Slack doesn’t send data in that format. Instead, Slack sends a JSON payload.

So we fix it the same way as before. We change the prompt source to Define below, giving us full control over how we pass data to the model.

Instead of plucking out just one field like the message text, we take a different approach here. We decide to pass the entire Slack JSON payload to the AI and let the model interpret it.

We type a prompt like:

“Please respond to this message from Slack.”

Then we add a couple of blank lines. After that, we insert the full JSON payload.

If we simply insert $json, it doesn’t work properly—it shows up as a JavaScript object reference. To convert JSON into readable text, we wrap it using JSON.stringify($json). This converts the entire payload into a text string the model can read.

Now the AI receives the instruction plus the full Slack message context.

We test again.

We press Execute Workflow, go back to Slack, and send the same message again. This time, the workflow completes and sends a response—but it sends “bananas.”

That’s expected. The workflow works end-to-end, but the final message is still hardcoded.

Now we fix the last piece.

We open the Send Slack Message node. We switch the message text from Fixed to Expression. Instead of typing the expression manually, we simply drag the output field from the AI Agent node and drop it into the message field.

This automatically creates the expression {{$json.output}}, which pulls the AI’s response dynamically.

We test one more time.

Execute workflow. Go back to Slack. Send “Hi there.”
This time, Slack replies:

“Hi there. How can I assist you today?”

That’s it. We just completed a full OAuth-based Slack integration with a webhook trigger, AI processing, and message response.

Now there’s one final step: production deployment.

Up until now, everything has been running in test mode using the test webhook URL. To go live, we need to switch to the production webhook.

We open the Slack trigger node again and toggle from Test URL to Production URL. We copy the production webhook URL.

However, when we try to paste it into Slack immediately, Slack doesn’t verify it. That’s because the workflow hasn’t been published yet.

Before publishing, we optionally add one more node—like a Date & Time tool—to demonstrate tool usage. Then we press Publish. We give the version a name and confirm.

Now the workflow is running live.

We return to Slack, go back to Event Subscriptions, replace the old test URL with the production webhook URL, and Slack verifies it successfully. We press Save Changes (very important).

Finally, we test in production.

We send “Hi there” in Slack. No boxes light up in N8N anymore—because this is live. And the response comes back immediately.

We try another message: “What’s the current date?”
Slack replies with the correct date, proving the tool is being used correctly in production.

At this point, everything is working.

We’ve completed three integrations:

A simple one-way push with Pushover

A two-way integration with Telegram

A full OAuth-based, webhook-driven, production-grade Slack integration

Along the way, you learned OAuth scopes, webhooks, triggers, expressions, JSON handling, JSON.stringify, and environment separation between test and production.

If this felt intense, that’s normal. What matters is that you now recognize the patterns. From here on, integrations get easier—and much more fun.

Tomorrow, the real payoff begins: building an actual business project using these integrations.

You’re officially 27% of the way through building serious workflow expertise.
Take a breath. You earned it.

# **X) Day 5 - n8n JSON Workflow Tutorial: Webhooks, Authentication & Integration**

Look, I hear you.

Yesterday was grueling. We got through a lot. The integrations were perhaps slightly more than you bargained for, but we got it done. We’re through it now.

And today is redemption day.

Today is about putting everything into action. We’re going to build our first proper business project in n8n — the kind of thing you could realistically build for your own clients, or as part of creating an AI agency. This is where things really start to happen. This is where the commercial value lives.

So let’s get into it.

First, a quick recap.

One of the first things we covered yesterday was JSON. Most of you are probably already familiar with it, but if not, hopefully you developed some intuition. You’re going to be seeing a lot of JSON going forward, and it shouldn’t worry you in the least.

At its core, JSON is just a collection of key–value pairs. Something colon something, where those values can be strings, numbers, booleans, or — as you later discovered — lists, objects, or even null values.

JSON contains objects, which are also known as dictionaries, and these are represented with curly braces. Inside them, you have key–value pairs separated by commas. JSON can also contain arrays, which are represented with square brackets, and those arrays can contain objects. Objects can contain other objects, and you can compose larger structures from smaller ones made up of strings, numbers, lists, and more.

Before long, you get very used to seeing JSON everywhere — the curly braces, the structure, and the way it represents complex information as a hierarchy of smaller pieces.

That was JSON in four steps.

Next, we looked at expressions in n8n. Often when you’re filling in a value in a node, you can choose between a fixed value — a piece of static text — or an expression. An expression is dynamic: it gets evaluated at runtime and replaced with an actual value.

You can toggle between fixed values and expressions, and expressions are always surrounded by double curly braces. A single curly brace is just part of JSON syntax, but double curly braces indicate an expression.

We also introduced the $json shortcut, which means “grab the JSON output from the previous node.” We used this several times, and hopefully it’s starting to click. You can also use dot notation to drill into specific keys.

For example, if you have a JSON object representing a person named Alice, who is 30 years old and has an address object inside it, you could access the name with $json.name, or drill further into the address with $json.address.city to retrieve the city value.

We also used another important trick: if you don’t want the data from the immediately previous node, but instead want to reference data from an earlier node in the workflow, you can do that using $node. You specify the node name in square brackets, followed by .json, to access its output.

You don’t need to memorize this syntax. The important thing is to recognize it and understand what it’s doing. You can always look it up when you need it.

Another thing we covered was how to turn a blob of JSON into plain text so it can be passed into an LLM. For that, we used JSON.stringify. Again, no need to memorize it — just know that this option exists and that it’s useful when you want to feed structured data into a language model.

Then we moved on to authentication — how n8n connects to third-party systems and identifies itself.

There are a few different approaches here.

The simplest is using an API key. This is the ideal scenario. You just connect to a service like OpenAI, paste in your API key, get the green confirmation box, and you’re done. There’s no user-specific authentication involved.

The next level is OAuth 2 with preconfigured integrations. This is what we used with Google Sheets and Gmail. It’s still OAuth under the hood, but n8n has already done most of the heavy lifting. You click connect, a popup appears, you authenticate, approve access, and you’re done.

The hardest approach is full OAuth 2, which is what you need when building proper integrations with third-party platforms like Slack. In this case, you authenticate as a specific user or bot, configure scopes, manage permissions, and work with OAuth tokens.

With Slack, you also had to deal with webhooks. This isn’t strictly part of OAuth itself, but it’s another important integration concept, and we introduced it yesterday.

Webhooks are something many of you may have seen before, but for some this may be new.

Here’s the basic idea.

When we connect an action node in n8n to a third-party service like Slack, we typically call an API endpoint — a web address — using an HTTP request. This is a request–response interaction: n8n makes a request, Slack responds, and an action is performed, such as posting a message.

But there’s another type of interaction that isn’t request–response based.

Sometimes, we want Slack to notify n8n when something happens — for example, when a user sends a message. This is where webhooks come in.

In this case, n8n exposes a URL and tells Slack, “When this event happens, call this URL.” Slack then makes an HTTP request to that endpoint whenever the event occurs. That request triggers a workflow in n8n.

This exposed endpoint is called a webhook — essentially a hook that external systems can call to notify you that something has happened.

In our setup, we told Slack, “Here is the URL to call when a message comes in.” In n8n, we configured a trigger node that listens on that webhook URL. We then pasted that URL into Slack’s event subscription settings, telling Slack exactly when and how to notify us.

Slack doesn’t really know anything about n8n. All it knows is that when a particular event happens — like a bot mention — it should make a request to the URL we provided.

That’s why webhook nodes in n8n are trigger nodes. They exist to react to events that originate outside the system.

So, webhooks are simply endpoints that external systems call to notify you that something has happened. They make a web request to your endpoint, and that request triggers your workflow.

If any of this still feels a bit fuzzy, that’s completely fine. The important thing is to get the gist. We’ll be doing this over and over again, and each time it will become clearer. By the end of the three weeks, making HTTP requests and handling webhooks will feel completely normal.

These patterns are extremely common, and they’ll solidify with repetition.

Now, with that recap out of the way, there’s just a little bit of new material left — and then we finally get into the project.

# **Y) Day 5 - n8n Node Types Explained: Core Nodes, Subnodes, and Cluster Nodes**

I know how much you love terminology, so I’ve got a little more terminology for you. This is just to make sure you’re comfortable with the way n8n talks about nodes, and that the language you see in the docs feels familiar.

Nodes are the steps in a workflow. They’re the things we’ve been dropping onto the canvas. Nodes come in a few different flavors.

First, there are core nodes. These are the main building blocks you’re already familiar with — the things that appear directly on the canvas. Each core node carries out a node operation, which is one of two things: either a trigger that starts a workflow, or an action that represents a specific task.

When you select a new node, you press Tab to bring up the node picker. You choose a node type, like Slack, and then you choose an operation — either one of the available triggers or one of the actions. What appears on the canvas is the core node configured with that specific operation.

So that’s the distinction: a node is the block on the canvas, and a node operation is what that node actually does when it runs.

In addition to core nodes, there are sub-nodes. A sub-node is a smaller constituent part of a core node. It’s a step within a larger step.

A good example is a tool. You can’t drop a tool onto the canvas by itself. A tool must be associated with an AI agent, which means it only exists as part of something bigger. That’s the difference between a core node and a sub-node.

There’s one more term to introduce: cluster nodes.

A cluster node is a group of nodes that together make up a single logical step. It has a root node and one or more sub-nodes attached to it.

You’ve already seen an example of this. When you drop an AI agent onto the canvas, what appears isn’t just a single box. There’s the main agent node, plus required components like the model, and optional components like memory and tools. All of these hang off the main node.

That whole structure — the AI agent, its model, memory, and tools — is a cluster node.

It’s not absolutely critical to memorize these terms, but they do appear in the documentation, and it’s useful to know what people mean when they use them. We’ll refer back to this terminology when looking at diagrams later.

Now, there’s one important technicality I mentioned earlier that we need to cover.

When data flows through your workflow, nodes don’t work on a single object. They work on something called items.

You may remember that when we looked at the JSON coming into a node, it wasn’t just a JSON object. It had square brackets around it. It was an array — an array containing a single item.

That might have seemed odd. Why is it an array at all?

The reason is that what gets passed between nodes in n8n is always a list — an array of items. Each node is written as if it processes one item, but in reality it processes all of the items in the list.

For example, if you use an expression like $json.fruit.toUpperCase(), you write it as if you’re working with one item. But under the hood, that expression is applied to every item in the input array.

The output is another array, containing the transformed version of each input item. The top box would represent the input array, and the bottom box would represent the output array.

This is a bit of a technical detail, and it’s not super critical right now. The key idea is that in n8n, you’re often working with multiple items at once, even if it looks like you’re only handling one.

So far, we’ve only been dealing with workflows that pass a single item around, which is why this distinction hasn’t mattered much yet. But later, when we work with many items, this will become important.

Because of this, $json is actually a shortcut. The full version would be $input.item.json, meaning: take one item from the input, and access its JSON. The shortcut exists because this pattern is so common.

If you’re familiar with programming concepts, you can think of this as an implicit loop. n8n is effectively iterating over each item and applying your expression to all of them.

Again, this is just a technical clarification. You don’t need to master it right now — just be aware that this is how things work under the hood.

And with that, it’s time to move on to our commercial project.

We’re going to build an equity portfolio rebalancer.

This will be an AI agent that has access to a stock portfolio and can carry out instructions to rebalance it. It will be able to read a portfolio from a Google Sheet, look up equity prices, make rebalancing decisions, and then email the trades that need to be executed and send a push notification.

This project checks a lot of boxes. It uses multiple integrations, it has real-world relevance, and it’s something you could realistically build for a client. The goal is to introduce a few new ideas while reusing many of the integrations we’ve already set up.

You might want to try building this yourself first and see how far you get. If not, we’ll go through it together step by step. At the end, I’ll also leave you with some extra challenges to take it further.

All right — without further ado, let’s get into it.

Here we are in n8n. I’ve opened my instance and brought up the workflows screen. We’re going to press Create Workflow to start building our business workflow.

This is exactly what you would do if you were running an automation agency and building something for a client.

The first thing we’ll do is give it a name, because it’s always good to keep things organized. We’ll call it Equity Portfolio Rebalancer.

This is now our business workflow.

Next, we add a step. The first nodes we see are trigger nodes — nodes whose operation is to start a workflow. There are several options here.

We could run this on a schedule. We could trigger it from a chat message. We could trigger it with a webhook call, meaning any external system hitting a URL would start the workflow.

Instead, we’re going to use On Form Submission. This lets us create a simple web form that users can fill out. When the form is submitted, the workflow runs.

This is our first web form in the build.

Setting up the form is similar to tools like Google Forms or Typeform. You’re simply constructing a questionnaire for the user.

We’ll give the form a title: Portfolio Rebalancer. You can add a description if you want, but we’ll skip that.

Now we add an element to the form — the actual question. We could add many questions, but we’ll just add one.

The question is:
“How would you like to rebalance your portfolio?”

It’s a text field, and we’ll give it a default value:
“Ensure the portfolio is 60% equity and 40% fixed income.”

If you’re familiar with investing, this will make immediate sense. If not, don’t worry — this is the kind of instruction a real client might give, and our system needs to be able to handle it.

With that done, we press Escape and return to the canvas.

Now we have the start of our workflow, with a trigger node in place. The lightning bolt icon next to the node indicates that it’s a trigger operation.

And with that, we’re officially off to the races.

Next up, we’re going to look at the Google Sheet that will define our portfolio.

# **Z) Day 5 - Build an AI-Powered Portfolio Rebalancer Using N8N and Google Sheets**

Continuing with our business project.

So this is a look at a Google Sheet I've set up to represent my stock portfolio. The idea is that I will of course share this sheet. You can recreate it if you wish, or you can just use one that's set up. It's going to be set up with a bunch of stock tickers. Here they are. These are in fact in my portfolio. They are tickers that represent what's called ETFs, or they are sort of investments in a group of different shares.

Each one of them, I've got some quantity of them and they represent some of them are 100% equities—they are all stocks. Some of them are all bonds, all fixed income products, and some of them are a blend between the two. Columns C and D represent how much is stocks, how much is equity, and how much is fixed income. And that is the breakdown.

It’s common, particularly with retirement accounts, but also with longer-term savings and with many portfolios, that you have this breakdown between equity and fixed income. And it's common that you might want to rebalance it—and in fact, pay people to do this for you to take some cut of your money in return for rebalancing your portfolio. But there's no need, because an agent can do it for you, and it can do it for free.

That's what we are building today: our own financial planner that is able to rebalance the portfolio by making trades to set your balance of equity and fixed income to what you want, or really to do any kind of rebalancing that you might wish.

In this spreadsheet, there are a few sets of things that we're going to want our agents to fill in. One of them is this column here, “Price.” Price represents the current value of this equity in the market. We've already seen an agent fill in this column, and we'll be able to do that again. But this one is a new column. This is for the agent to fill in to say how many shares should we have—how much quantity of these different tickers after we've made some trades to rebalance the portfolio. It will fill in this column as it makes its decisions.

When it does that, there’s going to be a new total value coming up, and we will find out what kind of proportion between equity and fixed income it gets at the end of it. Of course, you can add in other kinds of metrics, like whether it's global or national investments, should you wish to rebalance in different ways.

That's the spreadsheet setup. Obviously, the price is all blank here. But if I put in a price like 100, then it fills in the value. And if I put in a new quantity after rebalancing of three, then the total value goes in there and the other things fill in. But we're going to leave it blank for now. This is a spreadsheet that we are going to be equipping our agent with, and it will operate on this.

Let's go and do that.

We go back to Nw10. Here it is. We are going to add in an agent and let's take a look at it. There it is. We've got lots to do with this AI agent. We're going to give it a chat model. I'm going to use OpenAI—you can use whatever chat model you wish. We are going to choose GPT 4.1.

The reason for that is that I want it to be a really smart model that does it well. You can choose what you want to use. It costs a few cents a pop with GPT 4.1, and of course, it's a fraction of that with GPT 4.1 mini. You should go with whatever you're comfortable with. I do find that the latest models like GPT 5.2 for me right now actually don't perform as well because they do too much reasoning and take too long. The outcomes for me are better just using GPT 4.1, which for this kind of thing is one of my favorites.

So I'm selecting GPT 4.1, but of course you can do anything over OpenRouter. You could be using Gemini—use whatever you want. Back we go. I'll press the tidy up button to make it a bit cleaner. And we will then keep going with some tools.

We're skipping memory—we don't need memory for this because it's just on a form submission. There's no chat history to have to remember. We go straight to tools, and we're going to go to Sheets—of course, Google Sheets tool. It's already set up with the right credentials. We know we can connect. Fine.

We're doing a sheet with a document. We want to get rows. This is going to be the way that we fetch the contents of our portfolio. The documents we're going to get is going to be from a list. We're going to choose the portfolio, and the sheet is also going to be from a list. We're going to choose sheet number one.

So I chose portfolio from the list here. And I'm now choosing sheet one right here. I'm not going to set any filters—I want it to be able to retrieve the whole thing. Okay. That has set up our Google Sheets access. Let's press the clean button.

Now we will give this a try and see what happens. Hopefully you're expecting something to go wrong. Let's see. Okay, I'm now going to press Execute Workflow and bam—up pops this window. It's a form. It says "Portfolio Rebalancer." It's the very form that we just described. It has the one question that is the field we put in there: How would you like to rebalance your portfolio? The default answer is 60/40. I'm going to press Submit.

Pressing Submit is basically sending an HTTP request which Nw10 has configured as a webhook. It is expecting this to come through, and bam—it has come through. If I click back here, you'll see that the workflow has run and it says there's a problem, just as we were expecting. Or are you expecting? I hope you're expecting.

Now let's go in and fix that problem. You'll see the error message tells us "No prompt specified." You'll recognize that because we've had it before. If you open up AI agent, we'll see more details that it was trying to bring in JSON chat input. It thinks it's connected to a chat trigger node, and it's not—it's connected to something very different.

The first thing we need to do is to change this from saying the source for the prompt is a chat trigger node to "Define." Below, we want to tell it how to look in the inputs and choose what should be the prompt to the LM. This is the input. This is the webhook that got called. As a side note, notice that it is of course an array of items. As I explained, what really gets moved between these nodes are these arrays of items—but there's only one. It's the submission of our web form, and it only has this one question: How would you like to rebalance your portfolio? This is what we want to be sent to the LM.

So let's drag and drop that in there. Let go. You'll see that it's put in there the right JSON to use. It then selects How would you like to rebalance your portfolio. That's working nicely. It's going to take this content and make it the prompt to the LM.

Going back to the canvas, I'm pressing Execute Workflow. Up comes this pop-up, and I'm going to submit it. This time it will hopefully be sending this exact instruction to the agent when this goes through.

What I think we'll find is something a bit curious happens, because we've not done a very good job of telling the agent what we want it to do. We've just said ensure the portfolio is 60% equity and 40% fixed income, but we haven't told it that the portfolio is in this Google Sheet. We haven't really given it good directions.

This used to be called prompt engineering. We've not done a good job of prompt engineering. The new expression is context engineering, which is the way to best position your whole agentic workflow to equip your agent with the best possible information. We've not done a good job of any of that.

Let's see what it says back now that it's just successfully run. You can see that in the output it said to ensure a portfolio is allocated 60% equity and 40% and follow these instructions. It has given us some sort of bland, generic content about what to do. It never used the tool because it didn't know that the tool was going to tell it our portfolio. It just gave back some random instructions.

We need to improve the prompt so that it knows what it has to do, and we also need to give it a few more tools so it can do it. And that's what we will come to next.

# **AA) Day 5 - Agentic AI Workflow Automation: Balance Autonomy and Instructions**

So this whole week is about automation—automation of business processes. A big part of automation when you're using AI agents is positioning an AI agent so it can carry out your business process in the best possible way. A lot of that comes down to what they once called prompt engineering, and is now, of course, context engineering. For the time being, we're just going to do pretty simple prompting stuff.

I'm going to double-click on the AI agent and up it comes. This, you'll remember, is the user message. We're taking the stuff that's coming in here and we're just shoving it into the prompt. The thing about these expressions is that you can mix and match. You can put normal English above this. When we've got this expression right here, you can see what the result will be.

Well, look at what I can do. I can put a couple of lines up here and I can say “bananas,” and then this is what the result will be—bananas. That wouldn't be very helpful for our agent, but maybe this would be more helpful. I just pasted in something I wrote earlier: You have access to the user's equity portfolio, which is in a Google Sheet. You also have access to market data. The user has asked you to rebalance their portfolio with this instruction. And then I've got the expression.

When we look at the results in the field immediately below, look what's happened. We've got the text I just typed, and then we've got the actual contents of this instruction. It's kind of obvious when you see it. So that's a really nice way to make a prompt and add in the user's input as well.

But wait, there's more. Right underneath this prompt, I'm going to put some more stuff as well. You could put “bananas” here too at the end, but that’s not very helpful. Instead, I’m going to paste something more wordy. Let me read this to you. I'm saying, in order to achieve this:

Read the portfolio from the sheet.

Fetch the latest prices of the positions.

Update the table with the prices.

Make decisions on portfolio rebalancing.

Update the table with the portfolio rebalancing decisions.

Read the table again to check that your rebalancing met the objectives. Make any further changes.

Iterate if necessary.

Finally, send an email with the trading decisions and a concise push notification.

You can see the tools I’m about to add.

So, what do you make of this? Have a think about what I've done here and what might be your counterpoint. What might feel a bit funny about what I've done just here? Well, here's the thing. If you were the challenging sort, which I know you're not, you might say to me: “Look, you've kind of written out a workflow there. You've got steps, even numbered steps. Why would we need an AI for this? If we've got steps to do, we could just lay out a workflow. We could use workflow tools, or there are a lot of other simplistic non-AI workflow products where you can just do one step, then another step, and another step. Surely the whole point of agentic AI is that you're just giving it a goal and letting it figure it out.”

To which I would say: yes, you're right, very good challenge. But these are quite loosey-goosey steps. These are not steps that would be easy to turn into code. Look at this step: “Read the table again to check you achieved the objectives and make any further changes to improve the rebalancing.” This is kind of hand-wavy, rough human-like instructions—like you might tell a person. You’re not just giving one very high-level goal, rebalance the portfolio. You're giving it some guidance so it knows how to do it, but only in a high-level, flexible way.

That gives it some autonomy, as I like to say, to decide exactly how to achieve this, how many iterations to do, how to read the spreadsheet. We're leaving a lot up to the agent. This is the kind of balancing act that is all about getting the most ability, the highest performance out of agentic AI. It's about figuring out how to keep the instructions high-level, so that it has the flexibility to be intelligent and nuanced about your instructions, while also giving it enough rails so that it sticks to what you want it to do.

There's something of an art to this, and the best way to get it right is by experimenting. There's no right answer—the best way is to try. Originally, when I first built this, I did just have a very simple objective: rebalance the portfolio. I found that it wasn't reliable. I got to this point with some iteration, and that's what you have to do too. I certainly encourage you to experiment with different levels of detail and find out what balance works best. Each model will have a slightly different balancing point, and you may find that if you're using Gemini, it’s able to work with higher-level instructions and be very reliable. So best thing to do is experiment. I wanted to give you that understanding of why one does it this way and how I came up with these steps.

Okay, onwards. To achieve all of this, we now need to add in some tools. Have you been paying attention to what we need to do? Let's go back. Maybe you could have a shot at this before I do it with you. Let’s move, give ourselves some space, and add in the first tool.

What should we do? Well, let's go for MarketStack. Add in MarketStack. Here it is. We're going to get end-of-day data. We want to get many, we let the model choose which ticker. And we just say here we have to add a filter and say “latest.” That is all set. That is MarketStack configured.

I should confess that you get 100 free lookups, and I exceeded my 100 free lookups, so I upgraded to the paid plan. You should be able to stay well within the 100 lookups for this project, but if you experiment like I did, you might go above that number. You can choose what to do, but I decided it was worth it. That is the next tool: MarketStack, one back to an old friend added to our agent.

Two more tools. Now they are both about updating the sheet, updating the Google Sheet. There are two ways in which the sheets might need to get updated, so let's do them right now. This is going to be using Google Sheets. This time we want it to be an “update row.” We're going to update that same spreadsheet so it can update the prices. This tool will allow it to update the prices.

I've selected my Google Doc “Portfolio” from the documents, for the sheet I select Sheet 1, which I think is the only sheet in that document. The document looks like this: it has a Price column and a New Quantity After Rebalancing column. What I'm doing now is setting it so that it can filter on the ticker and set the price.

That is one of our tools added. Now we're going to do exactly the same thing. Another tool, also Google Sheets, this time allowing it to change the portfolio—the rebalancing decisions will be added. Update row again. I’ll choose the document and set it up.

I’ve chosen “Portfolio,” Sheet 1. This time we’ll filter on the ticker, and we’ll change the column “New Quantity After Rebalancing.” Still fetching the columns. Let it finish. On week three, we’ll be self-hosting, so we’ll be able to run at our computer’s speed.

Finally, it says “select column to match on.” We say the ticker, using that to match, and set the New Quantity After Rebalancing. That is our other tool.

Let’s take stock. We have tools for our agents: a tool to get the contents of the sheet, look up market data, update rows in the sheet for pricing, and update rows in the sheet for rebalancing (the New Quantity After Rebalancing column). This is all pretty exciting. One more tool—do we have any more tools? Let’s go and do those final tools.

# **AB) Day 5 - How to Integrate Gmail and Pushover Notifications with n8n AI Agent**

So, yes, as well, we have the tools left to put on our communications tools—to send a push notification and an email. You now have a whole bunch of these tools in your toolbox, and you should feel free to use any of them. If you would rather have it send decisions via Slack or Telegram, then go for it. But we're going to stick with the ones I picked, which is my favorite, Pushover.

Let's add in Pushover. The Pushover tool will send a push notification. We’ll let the model decide what message to send us; that becomes part of this tool. We have to put in our user key here—the one that begins with the letter “U.” Obviously, rather than reveal it publicly, I just copy and paste it in. I also changed the priority to high because I needed it to make a noise on my phone.

Now the email tool. I press Tools and go to Gmail, consuming the Gmail API. This time, I’ll have it actually send an email for real. Before, I was a bit hesitant because I didn’t want to give it too much power, but this time we’re going to fix that. The email will be sent to me, using my Gmail address, with a fixed subject: Equity Rebalancer Trading Decisions. The message itself will be defined by the model, and it will be sent as an HTML email. That tool is now set.

Next, I press the clean-up button to make everything nice and tidy. I also zoom out a bit to get a better view. Now we’ve got everything laid out and are almost ready to go. There’s one more thing we can tweak to make it better. Over in the portfolio sheet, I added another row showing the proportion of fixed income. Now we can see both equity and fixed income breakdowns. For example, if I put in 100 as the price for everything, the portfolio shows a 60/40 split. After rebalancing, the portfolio makeup changes based on the new quantities. This improves the clarity of the spreadsheet.

Along with that, there’s a change we can make to the workflow. In the tool that gets rows from the Google Sheet, there’s a field called Tool Description that we’ve left at its default setting. By default, it just says “Get rows in sheet in Google Sheets,” which is what the LM sees when deciding whether to use this tool. We can do better. I pasted in a description I wrote earlier: This tool provides details of the user's portfolio in a Google Sheet. It includes the positions and the equity/fixed income breakdown. Use this tool to retrieve the Google Sheet before updating prices and making rebalancing decisions. You must also use this tool after rebalancing to check if the breakdown achieves your goal. If not, keep iterating. This makes the instructions very clear for the LM and is part of good context engineering.

I also updated the AI agent’s user message prompt, adding a note: Important: you must confirm you’ve achieved your goal. Only respond “OK” when your mission is complete. This helps ensure that the agent only signals completion once everything is done.

One more adjustment is the maximum iterations. This controls how many times the agent can use tools before stopping. The default is 10, which may not be enough, so I bumped it up to 30. That gives the agent plenty of iterations to think through what it needs to do.

Without further ado, let’s give this a try. We check that our portfolio is in good shape and press Execute Workflow. This is a classic example of automation. We’re taking something manually intensive and running an agent workflow to handle it, automating a process that currently requires a lot of manual work.

The agent is now running. You can see it’s thinking about what to do. On the executions tab, we can track a detailed trace of what’s happening. It’s already set all the prices and is now thinking about the rebalancing. The workflow updates the rows and adjusts quantities to achieve the target 60/40 split. Meanwhile, I received the push notification on my phone: Portfolio rebalanced to 60/40. Everything ran smoothly and faster than the traces could show.

Looking at the executions page, we see that all tasks were completed successfully. The OpenAI chat model was called ten times. The sheet was accessed four times, MarketStack was called four times for share prices, and the two update-row tools were used multiple times—once to set prices, then again to rebalance, and finally to adjust quantities to achieve the exact target. The push notification and email were sent, and everything was executed in a single workflow.

The email arrived with the rebalancing instructions, confirming that the workflow worked as expected. This shows how sophisticated this agentic workflow can be. We achieved a 60/40 split, updated quantities accurately, and kept the total portfolio value consistent.

Finally, a little more about the executions page. You can see a visual trace of everything running with numbers. Clicking Logs shows all the calls and actions, and switching to the Details tab shows exactly what happened at each point—inputs, outputs, and prompts. For example, it fetched a row, made adjustments to achieve the 60/40 split, and even made a final adjustment to the BND ticker. This is a very powerful debugging tool. If the workflow doesn’t behave as expected, you can review the logs, tweak prompts, and iteratively improve performance until it reliably achieves the desired outcomes.

# **AC) Day 5 - n8n Workflow Automation: Using If Nodes for Conditional Logic**

Okay, so I want to add one more element to our workflow—some traditional workflow logic. One of the great things about Nan is that it combines the best of agentic AI with traditional workflow tools, similar to Zapier, allowing API integration with visual workflow capabilities. That’s what we’re going to do here.

The AI agent’s output is supposed to be the word “okay”. This is something we can test for. I want to set it up so that if things go wrong and it doesn’t achieve the expected outcome, it will alert me with a push notification marked as a warning. If it goes right, I also want a push notification—but just a normal, non-emergency one. Essentially, we want two different notifications: one for problems, and one for “all is well,” chosen depending on whether the AI agent’s output is “okay” or not.

This sounds like it might need code—an if statement—but there’s also a simpler, low-code way using an if node. The if node allows us to visually lay out simple logic: if the agent did what it was told and answered “okay”, we’ll send a happy push notification. Otherwise, we’ll send an upset push notification.

To do this, I pressed the plus button and typed if to add an if node. The node routes items to different branches based on a condition. For value one, I used an expression: $JSON.output, which is the output field from the LM. If this is equal to the fixed text “okay”, the node considers it true. This gives us two branches: true and false.

On the true branch, we add a Pushover node to push a message. I pasted in my user key and set the priority to low, with the message “Rebalancing successful”. On the false branch, we also use Pushover, with the user key, but this time set it to emergency priority, with the message “Rebalancer failed”. After setting the user tokens, the workflow had no errors, and everything was ready.

Here’s an important distinction: the Pushover node used here is a core node in the workflow, not a tool called by the LM. As a core node, it’s always executed when the workflow reaches it, independent of the LM. When a node is used as a tool, it’s called at the LM’s discretion, and the LM can decide whether or not to call it and can even define some inputs dynamically. That’s the key difference between a tool node and a core action node.

With that done, I cleared the portfolio sheet and executed the workflow again. The workflow triggered successfully. The AI agent ran, rebalanced the portfolio, and I received two push notifications: one saying “Portfolio is rebalanced”, and another saying “Rebalancing successful”. The if node worked perfectly, routing to the correct branch and sending the appropriate message. This shows how you can add logic to your workflow to enforce stricter business processes.

The final step is deploying to production. I copied the production URL from the form submission, ensured everything was saved, and pressed the publish button. This made the workflow live. With an empty portfolio, I submitted the form, triggering the workflow. The agent immediately ran, set prices, and started rebalancing. I received push notifications as expected, and the email with portfolio rebalancing instructions arrived successfully.

The executions and logs confirmed that the workflow ran correctly. You can even see how many tokens were used by the AI agent, which is helpful for context engineering. One limitation to note: with larger portfolios, the agent can start losing coherence. Solutions include providing more information in the sheet, equipping the agent with a calculator for computations, or improving the tools to guide rebalancing decisions. The mission is to make this workflow more reliable, industrial-strength, and autonomous while still keeping it simple enough for the AI agent to make quick, accurate decisions and notify you.

This completes our deployed workflow. It’s a real-world example of automating a business process. You could even extend this trigger from a web form to a scheduled task, letting it run automatically once a day and notifying you of portfolio rebalancing decisions. That is a fitting conclusion to our first week of the program: automating workflows with AI agents.

Congratulations—you’re a third of the way through the program! Next week, we’ll explore voice agents and 11 Labs, which is going to be a lot of fun. But for now, take a moment to celebrate the progress you’ve made.

# **II) Section 2: Week 2: Accelerate With Voice Agents And RAG**

# **A) Day 1 - How to Build AI Voice Agents with ElevenLabs Agent Platform**

Well, I’m really happy you’re back for more. Last week was quite intense—we covered a lot of material and ended up with a pretty substantial project by the end. There was a lot going on, and I hope you enjoyed working through it. Now, though, we have a couple of really fun days ahead.

This is Week Two, Day One of the Agentic AI Builder program, focused on AI agents and voice agents in n8n. For today, however, we’re not going to touch n8n at all. I’m very excited to welcome you to ElevenLabs Day. Today is a purple day, which means it’s all about core skills—specifically, building new expertise in the area of voice agents.

Last week was all about automation. This week is called Accelerate, because the focus is on using the latest frontier technologies to do more—and do it faster. ElevenLabs is a perfect example of a product that enables acceleration. It’s somewhat magical, honestly, and I hope you feel the same way once you see it in action.

ElevenLabs is both a company and a product, as is often the case in tech. It was founded very recently, in 2022, and it’s already a unicorn company. It’s widely considered the leading company in audio generation, especially when it comes to quality. While it is more expensive than many alternatives—including free and open-source options—you truly get what you pay for. In terms of audio realism and quality, ElevenLabs is considered top shelf.

The company was founded by a former Googler along with someone from Palantir, who came together to build the business. On the website, ElevenLabs positions itself around two main sibling products. The first is the Creative Platform, which focuses on generating audio and building audio avatars. The second is the Agents Platform—and you can probably guess which one we’re going to use. Most of our time will be spent in the Agents Platform.

In many ways, the Agents Platform feels a bit like n8n itself. You’ll notice some familiar canvas-style layouts and workflows, but it’s highly specialized for voice agents. As you’ve already seen in the curriculum, we’ll be building workflows that connect ElevenLabs and n8n, and we’ll make decisions about which responsibilities belong to ElevenLabs and which belong to n8n.

Regarding pricing, as I mentioned earlier, ElevenLabs is on the pricier side—but it does offer a free tier. You can follow along with this entire course without paying anything. I’ll admit that I personally signed up for the Starter plan at $5 per month, because I’ve been using it quite a bit and really enjoying it. That said, it’s absolutely not required—you can stick with the free tier, which is quite generous.

Let’s take a look at the product itself. If you go to elevenlabs.io (one word), you’ll see the tagline: “The world’s most realistic voice AI platform.” Right at the top, you’ll notice two navigation options: Creative Platform and Agents Platform—the two platforms I mentioned earlier. Each has its own set of use cases and documentation.

There’s also a dedicated Developers section that includes documentation and API references for both platforms, side by side. If you click on Pricing, you’ll see the free tier along with paid plans like Starter, Creator, and Pro. Pricing may vary by region and can change over time, so what you see might not exactly match my screen, but hopefully the free tier is still available—and maybe even more generous.

On the homepage, there’s an instant demo where you can press play and hear a sample voice narration. The quality is genuinely impressive. You might think it’s cherry-picked because it’s on the landing page, but ElevenLabs really is that good—you’ll see it for yourself once you start using it.

The Creative Platform offers things like text-to-speech, audiobook creation, and even music generation. The Agents Platform, on the other hand, is where you build voice agents, which is exactly what we’ll be focusing on. You can also explore voice replication examples—like Michael Caine or Matthew McConaughey—though using those yourself typically requires a paid plan.

Overall, ElevenLabs is an industry leader in audio quality. It’s not the cheapest option, but the quality more than justifies the price, and the free tier is sufficient for learning and experimentation.

To get started, click Sign Up. During the signup flow, you’ll be asked which platform you want to use—choose the Agents Platform. You can switch platforms later, so you’re not locked in, but this is the right place to start. You’ll likely be prompted to create an agent immediately—just choose the Start from Scratch option. The process is straightforward.

Once logged in, you’ll see a dashboard. On the left side, there’s a toggle that lets you switch between the Creative Platform and the Agents Platform. While the Creative Platform includes features like speech, audiobooks, video, and music generation, we’ll be staying firmly within the Agents Platform for now.

Inside the Agents Platform, the main navigation is divided into Configure, Monitor, and Deploy. We’ll start by clicking Configure Agents. You may see an existing test agent if you’ve already experimented. Other sections, like Tools, will become clearer as we progress.

For now, we’ll begin our first experiment by clicking the New Agent button.

# **B) Day 1 - Build Your First AI Voice Agent with ElevenLabs Conversational AI**

Okay, here we go.

To begin, I click New Agent. The interface asks, “What type of agent would you like to create?” I select Blank Agent. Next, it asks for a name that reflects the agent’s purpose. I’ll call it First Agent. I keep Chat Only turned off and then press Create Agent.

The agent is created, and the configuration screen appears. The first thing we see is the system prompt, which defaults to “You are a helpful assistant.” You already know what that means—it sets the overall behavior and personality of the agent.

Below that is the first message, which starts with: “Hello. How can I help you today?” You’ll notice a note explaining that you can add variables using double curly braces, which should feel very familiar if you’ve used expressions in n8n.

The default voice selected is Eric, described as smooth and trustworthy. We’ll be the judge of that. The language is set to English, and we can also choose which LLM model to use. By default, it’s Gemini 2.5 Flash.

If we open the model selector, we can see additional options, including experimental GPT-4o-style models. There’s also Gemini 3 Pro, but notably not Gemini 3 Flash, which makes sense because that model was only released very recently. For now, we’ll stick with the default setup.

At this point, everything is configured, so it’s time to try it out.

I click Preview to run the agent. An avatar appears along with a “cool AI agent” button. Let’s give it a shot.

The agent greets me: “Hello. How can I help you today?”
I respond, “Well, hello there.”
The agent replies smoothly and naturally, asking how it can help.

I ask for a fun fact, and it tells me that a group of flamingos is called a flamboyance—a delightful and fitting name. I then ask for a joke about flamingos, and it delivers one with good timing and humor. After thanking it, the agent politely asks if there’s anything else it can help with.

That interaction is genuinely impressive. Of course, credit goes to Gemini 2.5 Flash for the intelligence behind the responses, but ElevenLabs deserves real credit for how fast, seamless, and natural the voice interaction feels. It genuinely feels like speaking to a real voice agent, and the frictionless experience is fantastic.

Next, let’s take it a bit further and try a business-style conversation.

I update the system prompt so that the agent is now a helpful assistant for an airline. The agent assists customers with their travel needs. I also provide some reference information: a return ticket from New York to London costs $599.

Now that we’ve added context, let’s change the voice. We browse the available options:

Miss Walker – warm, reassuring, and round

Jason – calm and soothing

Stokes – relaxing, casual, and warm

We decide to go with Miss Walker.

With that done, I press Preview again to test the agent.

The agent greets me, and I say I’d like to go on a trip. It asks for my destination and travel dates. I tell it I want to travel from New York to London next week. The agent immediately references the price we included earlier—$599—and asks if I’d like it to check availability.

This confirms that the agent is successfully using the context and information provided in the system prompt. It’s relatively simple functionality, but what stands out is how quickly and easily it’s put into action.

Now, let’s explore some of the more advanced features of ElevenLabs by navigating through the tabs.

We start with Workflow, which is marked as new. This should look familiar—it closely resembles the n8n canvas. You can add nodes, connect agents, and even use tools to route conversations between different agents.

That said, we’re not going to spend much time here. We’ll be using n8n for workflows instead, since we already know it well and want to invest our effort there. This workflow tool in ElevenLabs is still somewhat raw, as indicated by its “new” label, but you’re welcome to experiment with it.

If we click Templates, we can choose something like Qualification Flow. This template shows an agent whose job is to decide whether a user has a technical issue or a billing issue. Based on that decision, the LLM routes the conversation to a different agent using a tool.

Each agent has its own prompt and can respond differently depending on the issue type. This allows you to set up multiple voice agents and route conversations dynamically based on conditions. It’s fairly self-explanatory, so we’ll move on for now.

Next is Branches, where you can create and test different versions of your agent.

Then we come to Knowledge Base, which is where things start to get really interesting. This is where you provide your agent with background knowledge or subject matter expertise.

Let’s try it out. I click Add Document and choose Create Text. I name the document Apple Product Details. I then paste in a chunk of text that ChatGPT generated for me—summarized information about Apple products based on their website.

Once I click Create Text, the document is added to the agent’s knowledge base.

Now we go back to the agent and update the system prompt to say: “You are able to answer questions on Apple products.”

Let’s test this. We’ll switch voices again and choose Jason, described as calm, meditative, and soothing.

I press Preview and start the conversation. I ask about buying an Apple Watch, specifically asking for the latest version and its price. The agent responds accurately, referencing the Apple Watch Series 11, its approximate price, and also mentioning other models like the SE and Ultra versions.

This confirms that the agent is successfully consulting its knowledge base to answer questions.

This is our first real glimpse of RAG (Retrieval-Augmented Generation). Later this week, we’ll build this in a much more robust, industrial-strength way using n8n, and we’ll connect that system to ElevenLabs. But even here, you can see how easy it is to give an agent domain expertise just by uploading documents through the UI.

And with that, we’ll leave it here.

You should absolutely give this a try yourself.

# **C) Day 1 - ElevenLabs Voice Agent Tools: Deploy Conversational AI with Widgets**

Okay, moving on through the remaining features of ElevenLabs using the main navigation.

The Analysis section is where you can review previous conversations that have taken place with your agent. You can see the history of interactions and confirm that they’ve all run successfully. This is useful for validating behavior and checking how your agent has responded over time.

Next is Tools, which is exactly what it sounds like. This is where you equip your agent with tools, very much like you would in n8n. This section is particularly important because it’s one of the two ways we can connect an ElevenLabs agent to n8n. In practice, one of these tools can be configured to call out to an n8n workflow. We’ll be doing this tomorrow when we add our first custom tool.

There are also system tools—built-in tools that you can enable with a simple toggle. These allow the agent to do things like end a conversation gracefully instead of continuing indefinitely. There’s also a custom button option that allows you to surface additional information to the user, as well as a detect language tool, which lets the agent automatically identify the language being spoken and continue the conversation accordingly.

One particularly important tool is Transfer to Agent. This is how you can build workflows across multiple agents. You define a description that tells the model when it should transfer control, specify the conditions under which the transfer should happen, and define the transfer message. Essentially, one LLM decides that it’s time to hand off control to another agent with a different prompt or responsibility. This is the core mechanism for chaining agents together using tools.

You can achieve similar results using the newer Workflow feature or by selecting a template, which is essentially a shortcut for configuring all these tools automatically.

That covers Tools.

Next is Tests, which is where you can define different test scenarios and review past runs. This helps you validate agent behavior under various conditions.

The Widget section is a very important one. This is where you configure how your agent actually appears to users. You may remember the nice blue avatar you saw earlier—this is called the orb. This is where you customize it.

That said, you’re not limited to the orb. You can upload an image instead—perhaps a photo of yourself or a brand mascot. You can also provide a URL pointing to an image if you already have one hosted elsewhere.

Crucially, this section also gives you an embed code. You can paste this directly into a webpage to surface your agent there. For example, if you’re using WordPress, you can embed this as a script tag, and your agent will appear directly on your site. The same applies to any platform where you can deploy HTML. If you’re working with a technical team, you can simply hand them this snippet, and they can add it to your website. Once embedded, the blue orb will appear and connect directly to this agent. It really is that simple.

If you scroll further down, you’ll find extensive configuration options for styling and coordinating the avatar, as well as adding more details to the widget itself. There’s a lot here that can be customized without needing to be particularly technical.

You can then share the widget wherever you like. There’s also a newer Widgets V2 option, which I haven’t personally used yet. This version is more sophisticated and supports headers, lists, code blocks, and additional layout controls, giving you even more flexibility over how the widget is embedded and displayed.

Overall, this is a major step forward—it allows you to embed a live, interactive voice agent directly into your website with minimal effort.

Next is Security, which includes various configuration options. You can require authentication so that users must log in before interacting with your agent. You can also control what users are allowed to do—for example, whether they can switch to text-only mode instead of voice. By default, this option allows users to choose whether they want to type instead of speaking, but you can restrict or expand this flexibility as needed.

There’s also support for webhooks, which ElevenLabs can call at the beginning and end of a conversation. By now, you know exactly what webhooks are and how they work. This allows ElevenLabs to call out to another system via a URL you provide. You can also set usage limits, such as the maximum number of calls per day for a particular agent, to ensure things don’t go off the rails.

Finally, there’s the Advanced tab, which contains additional settings. You can configure the agent to be text-only if needed. There’s also a newer feature called Scribe for automatic speech recognition.

You can define keywords that are likely to come up in conversations—such as product names like Apple Watch. This is especially useful for unusual or branded terms, as it increases the likelihood that the speech recognition system correctly identifies them.

There are also parameters that control the personality and behavior of the agent—how quickly it jumps into the conversation, how long it waits before asking something like “Are you still there?”, and how it handles silence. I believe I adjusted these from the default at one point because the agent was responding too quickly. You can experiment with these settings to find what feels most natural.

You can also configure the agent to automatically end the conversation after a period of silence, along with a few other behavioral tweaks.

At this point, I strongly encourage you to explore these settings yourself. Play around with the fields, press the Preview button frequently, and get a feel for how everything works. Definitely experiment with the Knowledge Base as well.

ElevenLabs makes building voice agents incredibly simple—and this hands-on experimentation is the best way to really understand it.

# **D) Day 1 - Building Multi-Agent Workflows with ElevenLabs Voice AI Agents**

Okay, we’ll bring this home by building a quick agent workflow to solve a small business-style problem. Nothing too serious—just a toy example to show what’s possible.

We’ll start by going to Knowledge Bases and adding another document. This time, we’ll create a new text document and call it Stock. This document represents what the store currently has available. For our example, the stock will include a few Apple products: an Apple Watch Series 11, an iPhone 13 Pro Max, and a MacBook Pro M4. Of course, in a real scenario this could be a much longer and more detailed document. Once that’s done, we create it as another knowledge base.

Now we’re going to set up a small agent workflow using the Workflow feature. To get started quickly, we’ll pick a template—specifically, the Qualification Flow template that we looked at earlier. This gives us a solid starting point for our experiment.

Let’s begin editing the workflow. The first agent is called the Qualification Agent. We’ll repurpose this to act as the main agent, the one that kicks off the conversation. We’ll keep things simple. The conversation goal (the prompt) will be: “You’re a customer support representative at a store that sells Apple products. You direct the user’s question as appropriate.”

We turn on Override Prompt, which means this prompt completely replaces anything defined in the agent tab. For the voice, we’ll choose Miss Walker to answer the call. We also make sure that this agent does not inherit any knowledge base, meaning she comes into the conversation without product or stock knowledge. That’s intentional—her job is just to route the conversation.

That completes the setup for the first agent.

Next, we move on to what was originally called Technical Support. We’ll rename this agent to Product Support, which is more accurate. The prompt here will be: “You’re able to answer general questions about Apple products.” We again enable Override Prompt.

For the voice, we’ll choose someone new—Russell, who’s described as outgoing and excited. This agent will need access to product knowledge, so we disable inheritance and explicitly attach the Apple Product Details document to this agent’s knowledge base. Now the Product Support agent has both the right prompt and the right information.

With that done, we move to the final agent, which was originally Billing Support. We’ll rename this one to Stock Specialist. This agent’s job is to answer questions about what the store currently has in stock. The prompt reflects that purpose, and we again override the previous prompt.

For the voice, we’ll choose Stokes. This agent also needs a knowledge base, so we disable inheritance and attach the Stock document we created earlier. At this point, the Stock Specialist is fully configured.

The last thing we need to do is define the edges—these are the conditions that determine how the main agent routes the conversation.

We select the first edge, which is an LLM condition. It’s currently labeled “Technical Issue,” so we change that to Product Question. The condition becomes: “The user has a general question about Apple products.”

Next, we select the second edge, also an LLM condition. We rename it from “Billing Issue” to Stock Question. The condition is: “The user has a question about what Apple products the store has in stock.” These conditions are clear and unambiguous, which is exactly what we want.

With everything set up, we’re ready to test the workflow.

We press Preview and start the AI agent. The main agent answers the call and greets the user. We ask about the latest model of the Apple Watch. The system correctly routes the conversation to the Product Support agent, who answers using the Apple Product Details knowledge base. The response is accurate and natural, and once the interaction is complete, the conversation terminates cleanly. We rate the conversation as very good.

Let’s try a second test, this time triggering a different route.

We start again and ask what models of the MacBook Pro are in stock. This time, the conversation is correctly routed to the Stock Specialist, who consults the stock knowledge base and confirms that the MacBook Pro M4 is available. Another successful test run.

What you’ve just seen is a simple but powerful example of intent-based routing. The user asks a question once, and that question is routed seamlessly to the correct specialist—there’s no need for repetition. In a more advanced setup, you could add additional edges to allow conversations to bounce back and forth between agents as needed.

We’re not going to dive deeper into this tool, because our real focus will be on connecting voice agents to n8n. However, it’s important to know that if you have simpler use cases—such as a customer support agent with a knowledge base and basic routing—ElevenLabs can handle everything on its own.

It’s easy to use, high quality, and surprisingly powerful. So feel free to experiment with it and explore what it can do.

That wraps up our first day experimenting with ElevenLabs and building voice agents. I hope you were genuinely impressed by how easy it was to create multiple voice agents, add knowledge bases, and introduce basic workflows.

We won’t go much further inside ElevenLabs alone, because the real magic happens when we combine it with n8n. That integration—the marriage of ElevenLabs and n8n—is incredibly powerful, and that’s what we’ll start building tomorrow.

Before we move on, though, take a moment to appreciate the progress: we’re already 40% of the way through. I hope you’re starting to feel more like a pro—because once we hook these two platforms together, you definitely will.
