# AI-Builder-with-n8n-Create-Agents-Voice-Agents-Notes
This Repository contains my "AI Builder with n8n: Create Agents &amp; Voice Agents" Course Notes from Udemy

**I) Week 1 - Automate with Workflows in n8n Cloud**

**A) Day 1 - Build Your First AI Agent with n8n and OpenRouter (No-Code Tutorial)**

**B) Day 1 - Build AI Agents with n8n: Agentic AI Workflow Automation Framework**




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
