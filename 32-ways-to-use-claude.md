# 32 Life-Changing Ways to Use Claude in 2027: Every Prompt

These are copy-paste prompts to recreate the 32 use cases from the video. Fill in anything in `[brackets]`.

**Where to paste each prompt**
- **Claude chat:** the normal Claude app or claude.ai.
- **Cowork:** the Claude desktop app's mode that can work in your files and your browser.
- **Claude Code:** Claude's coding tool. It runs on your computer and can write and run code for you.

Each prompt links to the person or company the idea came from.

---

## 1. Make a 4K short film for about $20
**Use:** Claude Code, with Blender installed.

```
I want to make a 2-minute animated short film entirely in Blender, using only Python scripts you write.

Story: [one paragraph: main character, setting, what happens, how it ends]
Look: [style, e.g. soft stylized 3D with warm lighting]
Output: 4K, 24 fps

Before you write any code, give me a plan: characters and props, sets, a shot list with camera moves, and an estimate of render time and cost. Wait for my OK.

Then build every character, prop, and set in code, animate every shot, and render a low-resolution preview of each shot for me to review. After I approve, render the final frames and put them together into one video. Don't spend more than $[budget] on cloud rendering without asking me first.
```
Source: [Riley Brown on X](https://x.com/rileybrown/status/2121642720045261185)

---

## 2. Find a lost phone with a 60-second program
**Use:** Claude chat or Claude Code, on a laptop near where you lost the phone.

```
I lost my phone somewhere in [the office / my house], and Find My isn't working because [reason]. The phone is probably still on with Bluetooth enabled.

How can I find it using just my [Mac / Windows] laptop? If tracking the Bluetooth signal strength works, write me a small program that shows a live signal-strength meter for nearby Bluetooth devices so I can walk around and watch the number go up. Tell me exactly how to run it.
```
Source: [Ben Zhang on X](https://x.com/un1c0rnioz/status/2084686552299634805)

---

## 3. Figure out why an old car keeps failing smog
**Use:** Claude chat or Claude Code, plus an OBD-II reader plugged into your car.

```
I have a [year make model] that keeps failing the [state] emissions test. Here are my last test results: [paste or attach them]. I can read live data from the car with a [OBD-II adapter / Arduino].

1. Help me set up the reader and log live engine data while I drive.
2. Explain what the data and the test results say is causing the failure.
3. List the repairs or maintenance most likely to fix it, cheapest first, and what a mechanic would charge for each.
Keep everything legal and emissions-compliant.
```
Source: [Muhammad Zulali on X](https://x.com/zulali/status/2120204711790023128)

---

## 4. Turn years of texts into a wedding website
**Use:** Claude Code on your own computer. Export your messages first, and get your partner's OK.

```
I'm getting married on [date]. I've exported [number] years of text messages between me and my partner into [folder/file]. Keep all of this data on my computer.

1. Analyze the messages: total count, messages per year, most-used emojis, how many times we said "I love you," busiest months, and anything fun you notice.
2. Ask me which stats and moments to include and which to leave out.
3. Build a wedding website with our story, those stats as charts, and the details: date, venue [venue], schedule, RSVP link [link].

Don't put any private message text on the site unless I approve it.
```
Source: [Austin Lau, via Shopifreaks](https://www.shopifreaks.com/anthropic-employee-uses-claude-to-turn-12-years-of-texts-into-an-ai-wedding-website-goes-viral-over-one-angry-emoji/)

---

## 5. Catch mistakes on your insurance (and cut subscriptions)
**Use:** Claude chat. Attach your statements and insurance documents.

```
Part 1: Here are my last 3 months of bank and credit card statements. List every recurring charge with the amount, how often it bills, and the yearly total. Mark the ones that look unused, duplicated, or cheaper elsewhere, and add up what I'd save per year by cutting them.

Part 2: Here's my insurance application and quote. Check every answer against these facts: [roof year, home details, cars, drivers, claims history]. Flag any answer that's wrong or missing, any discount I don't actually qualify for, and anything that could cause problems if I ever file a claim. Explain each one in plain English.
```
Source: [Bryce Watson's blog](https://brycewatson.com/blog/37-life-admin-with-claude/)

---

## 6. Work through a hard problem in your field
**Use:** Claude chat with the most capable model you have.

```
I'm working on this problem: [describe it, what's already known, and where people have gotten stuck]. Here are the key papers: [attach or link them].

1. Explain in plain English why this problem is hard.
2. Lay out the approaches that have been tried and where each one stopped.
3. Pick the most promising path and work through it step by step, showing every calculation.
4. Check your result against special cases where the answer is already known, and tell me honestly how confident you are and what an expert should check first.
```
Source: [Anthropic: Claude Fable 5.2 announcement](https://www.anthropic.com/news/claude-fable-and-mythos-5-2)

---

## 7. Read a home inspection report before you buy
**Use:** Claude chat. Attach the inspection report.

```
I'm thinking about buying this house for $[price] in [city]. I've attached the inspection report.

1. Make a table of every issue: page number, plain-English explanation, how urgent it is, and whether it needs a licensed pro.
2. Give a rough cost range for each item and a total range, labeled as estimates I need to confirm with real contractor quotes.
3. Tell me which items are deal-breakers, which are worth asking the seller to fix or credit, and which are normal wear.
4. Write the questions I should ask the inspector and contractors.
```
Source: [The Philadelphia Inquirer](https://www.inquirer.com/real-estate/homebuyers-home-sales-real-estate-agent-ai-technology-20261004.html)

---

## 8. Book your trips while you work
**Use:** Cowork with Claude in Chrome, signed in to your airline and hotel accounts.

```
You're my travel booker. My preferences:
- Home airport: [airport]
- Airlines and loyalty programs: [list]
- Seats: [aisle/window], [cabin]
- Hotels: [brands, budget per night, must-haves]
- Budget per trip: $[amount]

My trips: [list each trip with dates and cities].

For each trip, find the best flights and hotel that fit my preferences and show me one table with the options and total prices. Don't book or pay for anything until I reply "approved" for that trip. Then book only what I approved and give me every confirmation number.
```
Source: [Boris Cherny's setup, written up by Mika Reyes](https://www.mikareyes.com/ai/how-to-book-flights-with-claude)

---

## 9. Get rid of an annoying gadget pop-up
**Use:** Claude chat. Attach the manual if you have it.

```
My [device brand and model] keeps showing this pop-up: [describe it]. I've attached the manual [or: here's the model number].

Explain what the pop-up is for and whether I actually need it. Then walk me through every official setting, menu option, or firmware update from the manufacturer that turns it off or makes it show up less, step by step. Tell me if turning it off could hurt the device.
```
Source: [Chaz Schlarp's blog](https://schlarp.com/posts/everything-i-own-owned/)

---

## 10. Make a game playable for blind players
**Use:** Claude Code, with a screen reader and a game that supports mods.

```
I'm blind and I use [screen reader]. I want to play [game], which supports mods through [mod loader]. I've never coded before.

Build an accessibility mod that reads out [menus, map, units, resources, notifications] through my screen reader and lets me do everything with the keyboard. Start with the smallest useful version so I can test it, and explain every step in a way that works with a screen reader. After each test, I'll tell you what's missing.
```
Source: [Rashad Naqeeb, GAConf](https://www.gaconf.com/speakers/rashad-naqeeb/)

---

## 11. Build a history game with your kid
**Use:** Claude Code, with a free game engine like Unity or Godot installed.

```
My [age]-year-old and I want a game about [historical event]. I've created an empty [Unity/Godot] project at [folder].

Build a first-person educational game where you walk around, talk to people, and learn what happened. Split it into chapters that follow the real timeline, and use real times, names, and facts. List your sources for me. Tell the hard parts gently, because it's for a [age]-year-old.

Make a playable first version, then we'll playtest it together and send you changes.
```
Source: [Yasin Ucar on LinkedIn](https://tr.linkedin.com/in/yasin-ucar)

---

## 12. Get a shooter game from a three-paragraph prompt
**Use:** Claude Code.

```
Build a first-person shooter that runs in a web browser using Three.js.

It should have a small map with cover, enemies that move and take cover, a few weapons with recoil and reloads, and a health and ammo display. Make every model, texture, and sound effect in code, with no outside art or audio files.

Plan the systems first, then build and test each one. Play it yourself after each step, list what feels worse than a real game, fix it, and keep going until it's playable start to finish.
```
Source: [Matt Shumer's Claude of Duty on GitHub](https://github.com/mshumer/Claude-of-Duty)

---

## 13. Run your job search
**Use:** Claude Code (or try the free framework linked below).

```
Help me run my job search. Start by interviewing me, one question at a time, about my experience, skills, what I want in my next role, and my deal-breakers. Save the answers as my profile.

Then for each job posting I give you:
1. Score how well it fits my profile and explain the score.
2. If it's a good fit, write a tailored resume and cover letter using only real experience from my profile. Never invent skills or results.
3. Write interview prep for that role.
Keep a tracker of every application and its status.
```
Source: [Mads Lorentzen's ai-job-search on GitHub](https://github.com/MadsLorentzen/ai-job-search)

---

## 14. Build your own YouTube recommendations
**Use:** Claude Code.

```
I want better video recommendations than YouTube gives me. I care about [topics]. 

Find a public source of real people recommending videos, like [Hacker News comments / a subreddit / a forum]. Write code to collect the YouTube links people share there, count how often each video is recommended, and get each video's title and length. Then build a simple website that shows the most-recommended videos, lets me filter by topic, and remembers what I've watched in my browser.
```
Source: [Andrej Karpathy on X](https://x.com/karpathy/status/2116957135661945283)

---

## 15. Run your business with software you made
**Use:** Claude Code. Start with an export of the spreadsheet you use now.

```
I run [type of business]. I plan [production / scheduling / inventory] in this spreadsheet: [attach it]. I'm not a programmer.

Ask me questions until you understand how we plan, what goes wrong, and what takes the most time. Then build me a simple planning tool that does what the spreadsheet does, plus:
- warns me when we're going to run short of anything
- compares prices for the same item from different suppliers
- lets me change a plan and see what else that affects
Explain everything in plain English.
```
Source: [Caleb Schlegel in Greenhouse Grower](https://www.greenhousegrower.com/?p=181151)

---

## 16. Edit a church video without an editing app
**Use:** Claude chat that can run code, or Cowork, with your video clips.

```
I have [number] interview clips in [folder]. Clips with SKIP in the name are bad takes. Everyone answers this question: "[question]."

First, transcribe every clip with timings and pull still frames from each one. Then make a [length] video: the best take from each person, the question as a title card, an opening and closing card with our logo [file], captions in [font, color, position], and background music [file] that gets quieter whenever someone speaks.

Before you show me, check the frames around every cut, check that voices match lips, and set the volume for social media. I'll give you notes with exact times.
```
Source: [Ubon on X](https://x.com/ubonanalyst/status/2122401884291891430)

---

## 17. Check a famous math result yourself
**Use:** Claude chat or Claude Code.

```
In July 2026, a counterexample to the Jacobian conjecture was published. Explain in plain English what the Jacobian conjecture says, why it stayed open since 1939, and what a counterexample means.

Then write a short Python script using SymPy that checks the published counterexample: confirm that its Jacobian determinant is a nonzero constant, and show that it is not one-to-one. Run it and explain each step of the output.
```
Source: [Smithsonian Magazine](https://www.smithsonianmag.com/smart-news/ai-disproves-a-decades-old-mathematical-idea-the-biggest-conjecture-that-the-tech-has-played-a-role-in-yet-180989189/)

---

## 18. Turn a proof into one a computer can check
**Use:** Claude Code, with Lean installed.

```
I want to see how proofs get checked by computers. Take this proof: [a proof from a class or textbook, or "the proof that there are infinitely many primes"].

Write it in Lean 4 so a computer can check every step. Explain what each line does in plain English, run the checker, and fix anything it rejects until the proof is fully verified.
```
Source: [Anthropic: Claude Fable 5.2 announcement](https://www.anthropic.com/news/claude-fable-and-mythos-5-2)

---

## 19. Build a tiny operating system
**Use:** Claude Code, with the QEMU emulator installed.

```
Starting from an empty folder, build a tiny teaching operating system that boots in QEMU. It should print a welcome screen, take keyboard input, and run a few built-in commands like help, clear, and time.

Plan it first and explain each part (boot, memory, keyboard, screen) in plain English. Then build and test it one piece at a time, booting it in QEMU after each step.
```
Source: [Anthropic: Claude Fable 5.2 announcement](https://www.anthropic.com/news/claude-fable-and-mythos-5-2)

---

## 20. Find out if you're underpricing your work
**Use:** Claude chat or Cowork. Attach your job records.

```
I run a [type of business]. I've attached my [payroll, time tracking or GPS logs, and job records with the price I charged] for the last [period].

For each job, work out how many labor hours it really took and what that labor actually cost me, then compare that to what I priced in. Show me which kinds of jobs I'm underpricing and by how much, and suggest new rates that hit a [target]% margin. Explain your math.
```
Source: [RuntimeWire](https://runtimewire.com/article/claude-helped-landscaper-spot-labor-underpricing-owner-says-350635)

---

## 21. Find out why your PC keeps crashing
**Use:** Claude Code or Cowork on the computer that's crashing.

```
My [Windows PC / Mac] keeps crashing [describe: blue screen, freezes, restarts], about [how often]. 

Look through the crash logs and system event logs, find what the crashes have in common, and tell me the most likely cause in plain English. Then give me the safest fix first. Ask before changing or uninstalling anything.
```
Source: [Bryce Watson's blog](https://brycewatson.com/blog/37-life-admin-with-claude/)

---

## 22. Get your hardware working on Linux
**Use:** Claude Code on the Linux computer.

```
My [device, e.g. scanner or laptop camera, with model number] doesn't work right on Linux. Here's what happens: [describe it].

Figure out why. Check which driver it's using, what the system logs say, and whether there are existing drivers, settings, or community fixes for this model. Then walk me through the fix step by step, explaining each command before you run it, and test that the device works afterward.
```
Source: [Christian Schaller's blog](https://blogs.gnome.org/uraeus/)

---

## 23. Build the app you've always wanted
**Use:** Claude Code.

```
I've wanted a [type of app] since [when]. Here's what it should do: [list the main things].

Before building anything, ask me questions about who will use it, on which devices (phone, computer, or both), and what matters most. Then plan it, build the smallest version I can try, and keep improving it as I give you feedback. Make it work on phones from the start.
```
Source: [Beyzanur on LinkedIn](https://tr.linkedin.com/in/beyzanur-b-a678161a8)

---

## 24. Build a 3D world in your browser
**Use:** Claude Code.

```
Build a playable 3D scene in Three.js that runs in a web browser: [describe it, e.g. a boat ride down a river through a Japanese valley].

Include changing weather, a day and night cycle, water reflections, and a few characters. Build all of it in code. Then score each part of the scene (water, landscape, buildings, characters) from 1 to 10, and keep improving the weakest part until everything scores at least 8.
```
Source: [Meng To on X](https://x.com/MengTo/status/2102760783344189761)

---

## 25. Turn a worksheet into a game
**Use:** Claude chat or Claude Code. Attach the worksheet.

```
Turn this [math] worksheet into a browser game for a [grade] student. Every right answer should set off a fun effect, and the effects should get bigger the longer the streak goes. Add levels that get harder, a review mode for missed questions, and a simple progress tracker. Keep everything in the browser with no account.
```
Source: [AI IDE List on Dopa Drill](https://aiidelist.com/blog/dopa-drill-claude-opus-5-5-math-game)

---

## 26. Order dinner inside Claude
**Use:** Claude chat, in the US, with the Square plugin turned on.

```
I'm in [city or neighborhood] and want [type of food] for [number] people, ready around [time], for [pickup / delivery]. Find a few nearby restaurants on Square, show me their menus and prices, and help me pick. Don't place the order until I confirm it.
```
Source: [Square press release](https://squareup.com/us/en/press/claude-chatgpt-integrations)

---

## 27. Design a simple electronic device
**Use:** Claude Code, with KiCad installed (it's free).

```
I want to design a simple [device, e.g. a USB-powered temperature and humidity display]. I'm a beginner.

Explain how it works, pick the parts, and give me a parts list with prices. Then create the schematic and circuit board design in KiCad, run the design checks, and fix any errors. Finally, explain how to order the board and put it together.
```
Source: [Anthropic: Claude Fable 5.2 announcement](https://www.anthropic.com/news/claude-fable-and-mythos-5-2)

---

## 28. Turn your numbers into a narrated video
**Use:** Claude Data, on a paid plan.

```
Here are my [business / team] numbers for [period]: [attach a spreadsheet or connect the data]. Build a dashboard of the key numbers, then draft a two-minute narrated video that explains what changed, why, and what we should do next. Keep the narration plain and short.
```
Source: [Claude on X](https://x.com/claudeai/status/2120206365759094857)

---

## 29. Plan your lessons (free for US teachers)
**Use:** Claude for Teachers, free for verified US K–12 teachers.

```
I teach [grade and subject] in [state]. Plan a [number]-day unit on [topic] aligned to my state standards. For each day, include the goal, a warm-up, the main activity, a quick check for understanding, and versions of the activity for students who need more support or more challenge.
```
Source: [Anthropic: Claude for Teachers](https://www.anthropic.com/news/claude-for-teachers)

---

## 30. Run the back office of a small business
**Use:** Cowork with Claude for Small Business turned on and your tools connected.

```
I run [business] and use [QuickBooks / PayPal / HubSpot / Canva / DocuSign]. Every week, help me with:
1. A summary of money in and out, plus any unpaid invoices.
2. Follow-up emails for unpaid invoices, drafted but not sent.
3. A short list of the leads I should contact first.
Don't send, post, or pay anything until I approve it.
```
Source: [Anthropic: Claude for Small Business](https://www.anthropic.com/news/claude-for-small-business)

---

## 31. Build a budget in one sentence
**Use:** Claude Sheets, on a paid plan.

```
Make me a monthly budget spreadsheet for [household / business] with income of $[amount]. Include categories for [list], a column for planned vs. actual spending, a running total, and a chart that shows where the money goes. Add a savings goal of $[amount] by [date] and show whether I'm on track.
```
Source: [Claude on X](https://x.com/claudeai/status/2120206365759094857)

---

## 32. Lay out a messy plan on a whiteboard
**Use:** Claude Whiteboards, on a paid plan.

```
Here's everything in my head about [project]: [paste your notes, or just talk it through]. Lay it out on a whiteboard: group the ideas, show what depends on what, mark the open questions, and suggest the first three steps.
```
Source: [Claude on X](https://x.com/claudeai/status/2120206365759094857)
