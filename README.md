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
