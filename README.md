# AI-Builder-with-n8n-Create-Agents-Voice-Agents-Notes
This Repository contains my "AI Builder with n8n: Create Agents &amp; Voice Agents" Course Notes from Udemy

**I) Week 1 - Automate with Workflows in n8n Cloud**

**A) Day 1 - Build Your First AI Agent with n8n and OpenRouter (No-Code Tutorial)**

**B) Day 1 - Build AI Agents with n8n: Agentic AI Workflow Automation Framework**

**C) Day 1 - Build AI Agents with n8n: Complete Learning Roadmap & Workflow Setup**

**D) Day 1 - What is an AI Agent? Understanding Agentic Workflows in n8n**

**E) Day 1 - OpenAI API Setup: Cost Optimization and Free Alternatives Guide**

**F) Day 1 - How to Build an AI Agent with n8n and OpenAI API Integration**




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
