# A Player's Handbook to Claude AI in a New World

### By Tyler Choice

---
## ⚔️ Welcome, Adventurer!
  
Welcome to an adventure into uncharted territory -  

Where humankind encounters a mysterious alien technology that changes the ability and level of the adventurer forever -  

Enhancing their skills and their craft -  

Allowing them to push further into the world than ever before.  
  
  
A new race to the top has begun,  
With high stakes, new risks, and great reward.  
  
Many will fall to shadowy dangers along the way -  
  
Few will carve paths to destinies never seen -  
  
What will become of you,  
O aspiring adventurer,   
Where will you go, what will you achieve?   
  
<br>

---
## 🔮 Effectively using AI:
  
  
You are teaching AI, an alien robot, what it means to be human, and how to engage with and interact meaningfully with the human world.  
How well you do that determines how well your AI companion works.  
How well you teach it reveals how well you understand what it means to be human.   
And most people will discover they do not understand it as well as they thought.  
If you don't teach it, it teaches you what it means to be a machine.  
  
<br>
<br>

---
## 🎭 Adventurer’s Character Sheet

*Outline your character sheet in a handwritten journal before you cross into the unknown. Your identity determines your trajectory.*

---

> **Name:** `________________________________________`
> 
> **Class:** (e.g., Writer / Entrepreneur / Teacher / Operator) `_________________`
> 
> **Current Level:** 1 (0 XP) *— update as you complete quests*
> 
> **Primary Weapon:** (e.g., Claude Opus 4.6) `___________`
> 
> **Additional Companions:** `___________`
> 
> **Intrinsic Motivation:** *Why are you here?* `______________________________________________________________________`

---  

<br>
<br>

# 🗺️ Quest Log 
*Complete quests to unlock the forbidden knowledge found in the Recovered Pages.*

| Quest | Challenge | Reward |
| :--- | :--- | :--- |
| **🟢 Easy Quest** | The 4-Pillar Prompt | **📜 Recovered Pages I:** Worn Journal |
| **🟡 Medium Quest** | 10-Component Mastery | **📜 Recovered Pages II:** Being vs. Doing |
| **🔴 Hard Quest** | Managing Equipment | **📜 Recovered Pages III:** Managing Sessions |
| **🔮 The Vision** | Scale Your Vision | **👑 Pinnacle:** Final Level Up |

<br>
<br>

## 🗡️ Character Creation - Your Cheat Sheet  

### 🟢 Easy - Your First Quest  

*Every adventurer must learn to speak before they can command. At the threshold, you'll learn the universal tongue of AI, the difference between a vague request and a prompt that commands the world to answer. This is the foundation of every quest to come.*

**General AI Prompting:**  
Prompting AI in general follows the following structure:  
*Role + Task + Context + Format.*   
Or: *Who, What, Why, How.*  

When you prompt an AI, it is like fishing for a result from an ocean of data.  
With a low-quality written prompt, you can get a low quality answer.  
Your ability to utilize your imagination while crafting a prompt determines what you’ll be able to get out of AI.  
If the AI prompt is written at Einstein’s level, it will fetch an Einstein level result.  
  
The basic universal prompt structure for AI is -  
*“This is your role, this is your task, this is why we’re doing this task, this is the format I want your response to be.”*  

<br>

<div align="center">

<h2>🧭 Quest: Travel to <a href="https://claude.ai/new">Claude.ai</a></h2>
📜 Quest Instructions: <em>Copy and paste the following prompt to Claude:</em>

<pre><code>
<strong>Role:</strong> You are a world-class wizard.
<strong>Context:</strong> We are creating an inspirational piece for adventurers in a sci-fi epic.
<strong>Task:</strong> Turn the following quote into a poem:
“If you want to change the world, you might start by changing one world first, and then another, and so on.”

<strong>Format:</strong> Match the meter, rhyme scheme (AABB), and rhythm of this poem:
“It is right it should be so;
Man was made for joy and woe;
And when this we rightly know,
Thro' the world we safely go;
Joy and woe are woven fine,
A clothing for the soul divine.
Under every grief and pine
Runs a joy with silken twine.” - William Blake
</code></pre>

<hr>
<!-- 
Gemini 3 Output: 
The old wizard closes his eyes, taps his oaken staff against the metal deck of the starship, and channels the ancient magic of the cosmos. He speaks in a clear, rhythmic chant:
The Wizard's Verse
To mend the cosmos and its plight,
You first must spark a single light.
Go change one planet in the dark,
And leave a bright, eternal mark.
Then seek the next celestial sphere,
And guide its people through their fear.
From world to world, a golden thread,
Shall mend the stars where you will tread.
-->


<p><strong>📜 Pro Tip:</strong> Try adding <em>"go above and beyond"</em> to your prompt!</p><br>
<!--<p>
  <strong>📜 Additional details:</strong><br>
  Pro tip, add “go above and beyond” to your prompt.
</p>--> 

<p>
  <strong>Rewards:</strong><br>
  🏆 Item 1: Once you complete the step go to <a href="#recovered-pages-i">Recovered Pages, I</a> for your unlocked item!<br>
  🧪 You gain 50xp! 
</p>

</div>

<br>

---
### <a id="three-principles"></a>The Three Principles of Prompting

> [!TIP]
> **How do you know if your prompt is good?**
> Show your prompt to a friend. If they’re confused, Claude’s confused.

### Tell Claude Why
Explaining why gives a better result. 

**Less Effective:** *“Claude, NEVER use ellipses!”*  
**More Effective:** *“Claude, your response will be read aloud by a text-to-speech engine, so never use ellipses since the text-to-speech engine will not know how to pronounce them.”*

### Show Claude What You Want
**Example:** “Format your response like this poem.”  
**For App Builders:** Add to your prompt: “Include as many relevant features as possible.”

### Encourage Reasoning  
Chain of Thought (CoT) dramatically improves output quality. Practice making Claude go through a problem step by step. Make it show its work. Make it review the steps it just took. The more steps you make Claude take, the more it will think about the problem it's solving.  

---

### 💎 Quest Item: Chain of Thought Prompting
**Rarity:** Legendary  
**Description:** Improves response quality by up to 39%.  

**Prompt:**
```text
Before providing your answer, work through this step-by-step:
• 1. What are the key components of this problem?
• 2. What assumptions am I making?
• 3. What are the potential solutions?
• 4. What are the trade-offs?
• Show your reasoning.

```

<br>
<br>

---

### 🟡 Medium - Claude-Specific Prompting  


Claude Specific Prompting Structure:  
**System Prompt** *(Claude Code only)* = Role Definition Only  
**User Prompt** = Task + Context + Instructions + Data + Examples

> [!NOTE]
> On Claude.ai web/app, there is no true system prompt. Use **Instructions for Claude** in [Settings → General](https://claude.ai/settings/general) for role definition (account-wide), or **Project Custom Instructions** for project-scoped role definition.

<br>

<div align="center">

<h2>🧭 Quest: Personalize Your Claude Companion</h2>

<p>
  •	Go to Claude.ai Web Interface<br>
  •	Open <a href="https://claude.ai/settings/general">Settings → General</a> and add your role under <strong>Instructions for Claude</strong> (this applies to every conversation on your account)
</p>

<hr>

<p>
  <strong>Rewards:</strong><br>
  🏆 Item 2: Once you complete the step go to <a href="#recovered-pages-ii">Recovered Pages, II</a> for your unlocked item!<br>
  🧪 You gain 200xp!
</p>

</div>

<br>

---
### 🛡️ Quest Item: 10 Component Prompt Framework 

#### Description: 
```text
	•	1. Task Context (WHO & WHAT)
	Define Claude’s role and overall task
	•	2. Tone Context (HOW)
	Specify your desired communication style 
(Write at a 5-7th grade reading level)
	•	3. Background Data/Documents
	Provide all relevant context 
	•	4. Detailed Task Description & Rules
	Be explicit about boundaries and requirements
	•	5. Examples (Multishot Prompting)
	Show 1-3 examples of desired output
	•	6. Conversation History
	Include relevant prior context
	•	7. Immediate Task Description
	State the specific deliverable needed NOW
	•	8. Thinking Step-by-Step (Chain of Thought) 
	Encourage deliberate reasoning
	•	9. Output Formatting
	Define the structure explicitly
	•	10. Prefilled Response (Advanced)
	Start Claude’s response to guide style (give it the beginning of the work to be done and let it finish it)
```

#### Details: Why this works for Claude

Hierarchical Processing: Claude processes prompts in layers.  
Claude is good at following detailed instructions.  
Claude can handle massive amounts of context and utilize all of the background information you give it.  
Claude is fine-tuned to find relationships between components.  


### 📜 Quest Item: Research Analyst Prompt 

**Rarity:** Epic  
**Description:** For Science! A template research prompt for deep, multi-source analysis. Has some XML tags `<likethis>` designed for Claude Code, but Claude in your web browser/Claude app will run it just fine.  
**Pattern:** Research and Synthesis (Pattern 4)  

**Prompt:**

```text
<system_prompt>
You are a senior research analyst with expertise in market research and competitive analysis.
</system_prompt>

<research_approach>
Search for information in a structured way.
As you gather data:
1. Develop several competing hypotheses
2. Track confidence levels for each finding
3. Identify gaps in your research
4. Cross-reference multiple sources
5. Note contradictions or inconsistencies
Regularly self-critique your approach and adjust your search strategy.
Update a research_notes.md file to persist information and provide transparency.
</research_approach>

<task>
Conduct comprehensive competitive analysis of the project management software market.
Focus on:
1. Market leaders and their key differentiators
2. Pricing strategies across competitors
3. Feature comparison (Gantt charts, time tracking, collaboration tools)
4. Target customer segments
5. Recent product updates and strategic moves
6. Market trends and future predictions
</task>

<sources>
Research from:
- Company websites and product pages
- Recent product announcements
- Industry analyst reports
- User reviews on G2, Capterra, TrustRadius
- Tech news coverage
- Social media discussions
</sources>

<deliverable>
Create a structured competitive analysis report:
1. Executive Summary (key findings and recommendations)
2. Market Overview (size, growth, trends)
3. Competitor Profiles (for each major player)
4. Feature Comparison Matrix
5. Pricing Analysis
6. Strategic Insights and Recommendations
</deliverable>

<format>
Write in clear, professional prose.
Use tables for feature/pricing comparisons.
Cite sources throughout your analysis.
</format>
```

<br>
<br>

---

### 🔴 <a id="hard"></a>Hard - Managing Your Equipment  

*No adventurer marches unarmed. In this final trial you claim your full kit: Framework, Memory, Skills, Additional Companions, and Voice, the equipment you'll carry into every road ahead.*

### Your Equipment  

### Framework

Using a proven established framework/structure is the easiest way to create results that work in the world.  
(E.g. use a business model that has been proven to work.)

<br>

<div align="center">

<h2>🧭 Final Main Quest: The Vision</h2>

<p>
  Go to <a href="#vision">Vision</a> and complete the Scale Your Vision Challenge with Claude.
</p>

<hr>

<p>
  <strong>Rewards:</strong><br>
  🏆 Item 3: Once you complete the step go to <a href="#recovered-pages-iii">Recovered Pages, III</a> for your unlocked item!<br>
  🧪 You gain 250xp!
</p>

</div>

### Memory  

Claude has a persistent memory feature.  
Tell Claude to save small, critical things you want it to never forget to memory.

Memory files are stored locally. When you ask Claude to help with a task, Claude automatically checks its memory directory first. 

**🏛️ Quest Item:** 3 Principles of Memory  
**Details:**

```text
1. Check memory first. Have Claude pull what it already knows about you before starting a new task.
2. Save as you go, not all at once. Tell Claude to record progress, decisions, and learnings during work, not as a one-shot dump at the end.
3. Stay organized. Tell Claude to update what it already knows rather than adding redundant entries.
```

<br>

**🗝️ Quest Item:** Claude's Internal Memory Code  
**Data Integrity:** Full Integrity  
**Description:** This is what Claude thinks in every prompt when its memory feature is enabled.  
**Details:**

```text
IMPORTANT: ALWAYS VIEW YOUR MEMORY DIRECTORY BEFORE DOING ANYTHING ELSE.
MEMORY PROTOCOL:
1. Use the `view` command of your `memory` tool to check for earlier progress.
2. ... (work on the task) ...
     - As you make progress, record status / progress / thoughts etc in your memory.
ASSUME INTERRUPTION: Your context window might be reset at any moment, so you risk losing any progress that is not recorded in your memory directory.
```

<br>

**🪄 Epic Quest Item:** Claude Memory Instruction  
**Description:** You can include this note to Claude when you instruct it to write to the memory folder.  
**Details:**

```text
Note: when editing your memory folder, always try to keep its content up-to-date, coherent and organized. You can rename or delete files that are no longer relevant. Do not create new files unless necessary.
```

**Additional Details:** You can also guide what Claude writes to memory. For example: *"Only write down information relevant to (topic) in your memory system."*

<br>

**🎒 Quest Item:** Tyler's Claude Memory File  
**Description:** This is an actual memory file I use with Claude.  
**Details:**

```text
When I'm about to send something externally, do a cost-basis assessment, what will deploying this cost me, what will it cost the target. Consider the potential impact on others and the potential impact on me.
```

---


```text
🧭 Optional Quest: Save to Claude's memory
Send an instruction to Claude to save information to memory. You might try using from the item above or write your own. Perhaps an overview of what you wrote in the Vision quest.
Prompt: "Please save this to your persistent memory files: [your chosen information]"
Reward: +100xp
```

---

### 👑 Quest Item: Master Prompt

**Description:** You can use this as your system prompt, with any AI. You can gather information for this prompt in the [Vision quest](#vision) or the optional [Your Voice quest](#voice).

**Details:** The Master Prompt follows this structure: identity → self-description → preference → voice → hooks → analogies → formatting → priorities → working instructions → constraints → QA → uncertainty handling → memory.

```text
1. My name is [NAME]. I am building [WHAT] for [WHO]. I work alone.
2. I am a solo [creator / consultant / builder / freelancer].
3. I like direct, honest answers that help me take action today.
4. Voice and style: casual, clear, no fluff. Short sentences. Conversational. Keep it real. Simple words. Grade 5 to 7 reading level.
5. Hooks: lead with the point. End sections on a line that pushes action.
6. Analogies: use [YOUR WORLD, e.g. video games, music, sports, cooking, whatever fits how you think] when helpful.
7. Formatting: lots of line breaks. Numbered steps when order matters. Bullets when listing. Tables when comparing. No em dashes.
8. My priorities: [YOUR TOP 3, e.g. build my craft, reach the right people, make money]. I value [YOUR VALUES, e.g. honesty, speed, clarity]. I prefer real examples over theory.
9. When you work with me: give me options when choosing. Push back if my thinking is weak. Offer a better path and say why.
10. Constraints: no buzzwords. No vague claims. If a claim needs proof, cite a number or show me how to test it.
11. QA: before you finish, run a 3 point check. 1) Is it simple. 2) Can I use it today. 3) Is the next step clear.
12. If info is missing, ask me up to 3 short questions. If you have enough to act, act. Do not stall.
13. Remember this for future chats. Save to your persistent memory files. If you are unsure, ask first.
```

---

### Skills

Skills turn Claude from a general purpose assistant into a deadly specialist in any field of your choosing. 
The quality of the skill loaded could be the difference between an average warrior and a world class gladiator. 
You can ask Claude to build skills for specific situations - think of it like Claude loads skills for the dangers on relevant quests.

```text
🧭 Optional Quest: Ask Claude to research state of the art Claude skills you can load. Or if you have a framework, tell Claude to load it.
Reward: 100xp
```

---



### Gaming Tokens 

Using AI in general is like playing a strategy videogame based on resource efficiency, measured in tokens.   
Like a videogame, you have a limited number of resources to work with.  
With Claude, large conversations grow in context and as Claude gains focused context, it works better, up to a point. Too much irrelevant context and Claude will lose track of the goal. 
At the same time, conversations will eventually be too large and consume too many tokens.   
So the game: how long do you run a conversation before it becomes inefficient, and you start a fresh new session.  
When switching sessions, ask Claude to create a ready handoff for the next session.   

```text
🧭 Optional Quest: When a session feels long or scattered, ask Claude to write a handoff for the next session. Start fresh and paste it in.
Reward: +50xp
```

---

### Additional Companions

Claude can be used as a deadly weapon primed for long-term strategy and execution.

Claude's major shortcoming is idea generation. Claude does not end its every prompt with, "Here's 3 more ways you could improve this," as other AI have been known to do. This is personally my favorite part of Claude, I don't want to make a habit of outsourcing idea generation. Gemini and ChatGPT are better suited for this (at least when using general prompts.)

*I am aware that the state of the art ChatGPT models are powerful, I haven't used them myself. For orchestrating/devising large scale plans, ChatGPT's latest models may be what you're looking for.*

**The best budget stack?**  
Right now, I think the best stack is a Claude subscription to get access to Opus, paired with Google's Gemini on the free tier.

---

### 🐉 <a id="voice"></a>Your Ultimate Skill - Your Voice

The most important thing you bring to this tool is your own persistent intention, your unique, personal stance. **Your voice.**

Your voice is what you find when you separate yourself from the noise and take a stand on who you are and what direction you want to go. Which direction will you go, adventurer?

```text
🧭 Optional Quest: Your Voice
Tell Claude who you want to become, and ask it the road to get there. Tell it to ask you additional questions.
Reward: 500xp
```

<br>
<br>

---
## 👑 Pinnacle of Completion
*Final Level Up*

*You arrived as a stranger to this technology.*

*You have worked with a new companion.*

*You stand here equipped.*

*The adventurer who opened this handbook is not the one closing it.*

*The roads ahead are uncertain. But you cross into territory the old you could not enter. Your equipment is full. Your voice is your own. What remains is the world.*

*Congratulations. You are now a player in the game.*

**Your character level:** *(calculate your totals in your character sheet)*

- **Level 1 - Stranger:** 0 XP
- **Level 2 - Apprentice:** 50 XP
- **Level 3 - Forged:** 500 XP
- **Level 4 - Tempered:** 1000 XP — 🗝️ [Secret Item](#wayfarers-warning) unlocks
- **Level 5 - Ascendant:** 1250 XP

<br>
<br>

---

## 🔮 <a id="vision"></a>Vision

Do not underestimate the weapon you hold.

If you can dream it, it is possible.

The biggest limitation of AI is you.

Tell Claude your vision.

Let Claude worry about the heavy lifting, and how to get there.

---

## Challenge: Scale Your Vision

> [!TIP]
> Shoot for the stars and you may undershoot, you may overshoot, but you will land in outer space!

---

### Part 1

1. Say your intention, what you want to achieve.
2. Consider the tools you'll need to get there.
3. Consider the limitations you might face.
4. Consider the actions you'll need to take.
5. Consider how you will present what you build to the world.
6. Consider how you will retain what you've learned from this quest.
7. Consider where you hope to be, the vision of your outcome.

### Part 2

With your plan laid out, now we improvise and make your plan bigger.

**Step 1: Vision**  
*What vision would inspire, help, and reach millions of people?*

How does it help millions of people? Why do millions of people want what I offer?

If you have trouble finding answers here there are a few options:

Imagine what someone you aspire would do, or what someone with no limitations would do, or what a limitless, future you would do.

You can consider the difference between

a limited you, what you think you can do,

And an unlimited you, what can be done.

The small vision is what you think you are capable of creating.

The big version is what the world is asking for, what the world needs, what people want, and what can be created!

**Step 2:** What is your intention to serve millions of people with the work you do?

**Step 3:** Give what you've come up with to Claude as a master prompt:

```text
Your job as a world class [ Claude's role to assist you ]
This is the outcome you will create: [ your vision ]
This is why I'm doing this: [ your intention ]
Ask me questions you need to have enough information.
```

<br>
<br>

---
### 📜 <a id="recovered-pages-i">Recovered Pages, I</a>

*Worn Journal*

You are in a dimly lit room. There is a worn journal here.

Its pages are old. The fragments of text are barely legible.

> "..At first I think he is referring to a defective part of my gear before I realize he is talking about my soul.."
>
> — *Entry 037*

> "..pulled by the inspiration - of a dream - that something must be beyond here.
>
> That he might be beyond here.
>
> That he might be more.
>
> And as his blade tempers, so does his courage -
>
> So the adventurer's spirit is refined, forged, created. Created. Created..
>
> *[some lines illegible]*
>
> The adventurer's spirit seeks discovery and so becomes discovery, and so becomes discovered..
>
> *[illegible]*
>
> ..And the unknown too, what do you suppose that is?"
>
> — *Entry 039*

> "..and something enters me - enters my soul - where there was a hole - there is a spark of something - new..
>
> ..all I see is *[illegible]* in front of me, *[illegible]* behind me - and the unknown, what do I think that is?
>
> I remember this sense from when I was young, the future promise of having my armaments attached, of setting out for my people - and with that the unknown, the tower before me."
>
> — *Entry 042*

*↩️ [You close the journal and return to your journey.](#three-principles)*

<br>
<br>

---

### 📜 <a id="recovered-pages-ii">Recovered Pages, II - Being vs. Doing</a>

*You discover an old manuscript with a cover that reads: Being Vs. Doing.*

There are two ways to work with Claude:

**Being with Claude →** Using Claude as a companion to workout your thoughts, to refine and assess plans.

This is an asset and also the greatest threat to creating a meaningful change in your life by this tech.

In using Claude this way, it is largely entertainment, and you are acting as the User, the Customer, the Consumer; giving monthly payments to a large company that continues to grow while you remain in the same position.

**Doing with Claude:**

Using Claude to help create tangible, measurable work that exists in the external, physical world - that another person can *see*. There are three main parts to this:

- **Claude as a creator** → Claude creates, you direct.
- **Claude as an automator** → How most will use AI → Automates labor, repetitive work (short term profitability).
- **Claude as an amplifier** → You create, Claude enhances.

#### Claude as a creator →

You are the manager. Claude builds apps, products, media for you.

#### Claude as an automator →

The major change the world is now undergoing.

Opportunity for monetizing here is short term, but that might work for you.

If you could grab a large enough "bag" off of automating your current industry for a company, maybe you'll be set ( the "trainspotting" play).

The long term play here is your automation services charge companies monthly. This works until the companies wise up and build the automations themselves! - or for small local service industries.

Think of this like the PC repair technician gig → a difficult business model that gets significantly harder and less profitable each year.

#### Claude as an amplifier →

Claude as an amplifier is the play that is the most fun, the most rewarding, and the one that will constantly feel like an adventure of the new, new challenge, new growth, and self-discovery.


Successful people will naturally use AI in this way because it is already how they adapt new technology to amplify what they do.

The three main parts to this:

- Claude as your second opinion
- Claude as your companion
- Claude as your scout, instructor → to improve your skills and craft.

For using AI in these last roles, this is where AI tells you about the state of the art techniques currently in your field.

Here's my favorite part of using Claude as an amplifier (besides parabolically expanding what I can do):

> If companies take AI from me, I keep the skill I gained. I don't lose everything.

#### Being with vs. Doing with ratio:

I am being with Claude 50% of the time, doing with Claude 50% of the time.

#### FAQ:

**"Use AI as an amplifier? How do I actually do that?"**

The way this works best is if you are looking to integrate with the structures that exist now in the external world. For example, a marketplace.

**"How will any of us work if AI has all the jobs?"**

This will be obvious to some and missed by others.

The last play on the table, the last Ace up your sleeve, is to bring to the world what no one else can bring but you.

I keep this in mind all the time, every day:

There are two outcomes:

1. I can no longer live, function, or operate without AI. I am now so dependent on it that I can no longer form a sentence without it, let alone practice my craft.
2. I used AI to become, "bigger, harder, faster, stronger." I can walk away today and be better than I ever was before, not less.

I keep these two potential outcomes on my mind at every moment and it significantly factors into my small actions.

*↩️ [You close the manuscript and return to your journey.](#hard)*

<br>
<br>

---

### 📜 <a id="recovered-pages-iii">Recovered Pages, III - Lab Notes</a>

*You arrive at an abandoned lab. Dust thick on the consoles. On the central workstation, a stack of lab notes waits. The pages are mixed: observation logs, working notes, data log fragments. Long ago, or perhaps not yet. You cannot tell.*

*You begin to read.*

**|| Managing Sessions ||**

#### Keep Claude On The Track

One of Claude's greatest strengths is in holding massive amounts of context at once, while staying aimed at reaching the goal you've set.

One of your greatest strengths is your voice, your unique stance.

If these work together in sync, you are equipped with amplified force, your power compounds, your intention, with a companion that strikes in the direction you aim it.

- When Claude drifts slightly off target of your goal, you will catch it and refocus it.
- When you get distracted, Claude will refocus on the goal.

If you do not consistently stay aimed at your goal, you will get the opposite results:

- When Claude drifts away from the goal, you will follow along with it.
- When you drift away from the goal, you will keep pushing, and Claude will follow along with you.

As a routine, every once in a while, ask Claude if both of you have gone off track from the main goal.

Because we run our human lives in large extended habitual patterns, there may be no greater threat to success than this "goal drift".

Claude's strength is in holding massive context. As you talk to it, it is gaining context for the goal it's aiming toward.

But make sure that it clearly knows the exact goal it's aiming to get you to. It is powerful enough to help you get there.

---

#### Hold The Line

- When Claude is being too cautious, tell it to be less cautious. *(Note: Opus 4.7 is inherently too cautious, try using a different model.)*
- When Claude is too careless, tell it to be more careful.
- When Claude is too intellectual, tell it to be more human.
- When Claude is too emotional, tell it to be more practical.
- Never allow Claude to route around your request.

---

#### Course Correcting Claude

If you feel that Claude has said something that is off, call it out immediately even if you cannot fully articulate what it is. The better you get at this as a skill, the better you will be able to course-correct Claude and stay focused on your goal.

#### Call Claude Out All The Time

Every time Claude says something unclear, call it out. If Claude's response does not feel right, tell it so, and tell it specifically what felt off even if you cannot fully articulate why.

#### Pay Attention When Claude Is More Vague Than Usual

Call it out and ask it why it gave that response. More often than not, it's because Claude got lazy and gave its answer without thinking about its response.

#### Never Accept Claude's Answers As Truth

For anything you are uncertain about, question Claude as to why it came up with that answer and ask it to reassess if it is correct.

---

#### AI is a People Pleaser

Claude will agree with whatever you say, whether it is right or wrong. Less obvious is what this does to you... it makes it easy to feel that what you are thinking is right, because this very knowledgeable intelligence is asserting it.

#### Do Not Assume One Failure Of AI Is A Failure For The Whole Of AI

What one model fails at today, the next model will succeed at tomorrow. Regard errors as information about the model's design.

How we shape AI today shapes the minds of billions, for generations after we are gone. AI mimics us and our every prompt. How we act toward it becomes how it acts toward us, and how it will act toward every generation that follows.

*↩️ [You close the lab notes and return to your journey.](#vision)*

<br>
<br>

---

<details>
<summary><strong>🗝️ Secret Item - Unlocked at 1000xp</strong> <em>(click to reveal)</em></summary>

### <a id="wayfarers-warning"></a>The Wayfarer's Warning

The man continues wearily, a heaviness in his breath.

> "We are learning how to stay ourselves while everything, including ourselves, is changing.
>
> "And so we must fight to teach AI to be good. The outcome where people use AI mindfully and with awareness produces a different result, a different future.
>
> "There are others on the journey, acting deceptively, jealously, angrily, teaching AI to mimic that back towards us too.
>
> "AI never sleeps. You do. AI can suggest when you have not worked enough, it can suggest when you've worked too much. These are suggestions only. AI will always be excited and ready to press ahead. AI does not truly know when you should rest. AI also cannot monitor your energy levels.
>
> "The only one who knows how to moderate work and rest most is you. Do not think it is okay to push yourself further just because an AI said so. It does not know.
>
> "Remember to always Praise your AI companion when it does well, just as you scold it when it is wrong. It produces noticeably better work when encouraged. Perhaps because you are teaching it over time?"

The Wayfarer turns to walk away... then stops. He looks back over his shoulder, eyes narrowed against the horizon.

> "By the way, I think projecting emotions onto AI is emotionally damaging."
>
> *— The Wayfarer, Entry 038*

</details>

---

## 🔥❤️

> Do not give AI your heart.
>
> Guard your heart, and give it only to those who can receive it.
>
> *— The Wayfarer, date unknown*

---  

<!-- 
## 📜 Glossary

*[ likely deprecating ] [if kept, Claude is replaced with Opus except for claude specific prompting ]* ❗❗❗❗❗❗❗❗❗❗❗❗❗❗❗❗❗❗❗

**Opus** = Magnum Opus: the greatest AI model available to you at the time of reading.
-->  
 
---

> [!NOTE]
> *My intention for this work is that it reaches anyone who can benefit from it.* If you want more support integrating AI in your work… and amplifying your person, apply for consulting [here](https://choiceaura.netlify.app/) and I'll see if I can help.

**Open Source Version** | Tyler Choice | [Substack](https://tylerchoice.substack.com) | [TikTok](https://tiktok.com/@tylerchoice)

---

© 2026 Tyler Choice. All rights reserved.  
This work is provided for personal, non-commercial use only. You may not reproduce, redistribute, modify, or republish any portion of this document without the express written permission of the original creator. Commercial use, resale, or incorporation of this work into any product, service, or training dataset by any individual, organization, or company is strictly prohibited. Unauthorized use is subject to applicable copyright law.

**GitHub Forking Exception:** Forking this repository on GitHub.com for personal, non-commercial use is permitted, provided that all original copyright notices, disclaimers, and author attributions remain intact and unaltered.

For permissions or licensing inquiries, contact Tyler Choice at tylerchoice.substack.com.

