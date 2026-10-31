# Task 2: Monster Guess Who

**Age:** 4–8 (with a parent) · **Time:** 15–30 minutes · **Difficulty:** Beginner

## Goal

Play a monster-themed Guess Who game against a computer-selected secret character. Children ask yes/no questions about visible features, cross out monsters, and guess the answer.

## What you need

- A laptop or desktop with Chrome
- The [example game HTML file](index.html)
- Optional: a microphone for voice questions

## First: Build your own monster game with AI (parent + child)

**The main activity is creating the game together, not just playing it.** You do not need to know how to code. The parent operates an AI assistant that can generate HTML; the child makes the creative decisions, tests the results, and tells the AI what to change. Allow **30–60 minutes** for creation, or split it into two sessions.

### 1. Invent your monsters (5–10 minutes)

Ask your child: *What kinds of monsters should we have?* Pick a theme (space monsters, silly pets, underwater creatures), invent **6–8 monsters** to start, and decide on distinguishing traits: color, number of eyes, horns, wings, spots, or hats. Give them names. A smaller board is easier to test; you can expand to 16 later.

**AI prompt to try together:**

> We're a parent and a 5-year-old making our own Guess Who game. Help us invent 8 friendly, funny monsters. Ask my child one simple question at a time about their names, colors, eyes, and special features. Keep track of the monsters in a table. Make sure we can tell them apart with yes/no questions.

**AI skill:** Describing an idea clearly and giving the model constraints.

### 2. Ask AI to build the first version (10 minutes)

Use an AI coding assistant that can produce a self-contained HTML file. You can show it this folder's [example game](index.html) as a reference, or start from scratch.

**AI prompt:**

> Create a child-friendly, single-file HTML Guess Who game using our 8 monsters and their attributes. Show a colorful card for each monster, let the computer secretly choose one, answer typed yes/no questions about the monsters' features, let us cross out cards, and let us guess the secret monster. Include a New Game button. Use large buttons and simple words for a 5-year-old. Explain how a parent can save and open the HTML file. Keep the answers based on the monster attributes, not invented by AI during play.

The parent can save the code as `index.html` and open it in a browser. **If the AI produces something broken, that's part of the exercise.** Describe what happened and ask it to fix the problem.

**AI skill:** Turning a natural-language request into working software.

### 3. Make it your own (10–15 minutes)

Let your child choose **one change at a time**. They might want purple backgrounds, bigger monster eyes, a rainbow button, a funny victory message, or their own drawings instead of generated characters. Ask the AI to implement each change, then refresh and inspect the result.

**AI prompts:**

> Make the monsters look more like friendly fluffy aliens. Keep their names and attributes unchanged.

> My child drew this monster. Can you help us use the uploaded drawing for its card while keeping the game rules working?

> Add a celebration when we guess correctly. Keep the rest of the game the same.

**AI skill:** Iterating, giving feedback, and checking whether AI followed instructions.

### 4. Test the AI's work together (5–10 minutes)

Before playing a full round, deliberately check the rules:

- Ask a question about a feature you can see. Does the answer match the secret monster when you reveal it?
- Can you eliminate cards and undo an elimination?
- Does **New Game** really start over?
- Can you find a question or monster that confuses the game?

When something fails, tell the AI **what you did, what happened, and what you expected**. For example:

> We asked "Does it have wings?" and the game answered incorrectly for one monster. Please check the monster data and question logic, fix the bug, and explain the change in simple words.

**AI skill:** Testing, spotting mistakes, and debugging with AI instead of trusting every output.

### 5. Play, reflect, and improve

Now play the game you made. After a round, ask your child: *What did we tell AI to make? What did it get right? What did we have to correct? What should we add next?* Try adding more monsters or voice questions in a second session.

**Parent tip:** Let the child make the choices and speak the instructions; the adult handles typing, file saving, and browser permissions. Avoid entering personal information or uploading photos of children. Use drawings instead.

**Want to play first for inspiration?** Try the [ready-made example](index.html), then return to the steps above to create your own version.

## Run the game

1. Download this folder, including `index.html`.
2. For basic play, open `index.html` in Chrome.
3. For microphone access, serve it from localhost. Open Terminal in the folder and run:

   ```bash
   python3 -m http.server 8000
   ```

4. Visit [http://localhost:8000](http://localhost:8000) in Chrome.
5. Allow microphone access when Chrome asks.

Speech recognition depends on browser support and may require an internet connection. If it does not work, use the typed-question controls.

## How to play

1. Click **New Game**. The computer secretly chooses one of 16 monsters.
2. Ask a yes/no question, such as “Is it green?”, “Does it have one eye?”, or “Does it have wings?”
3. Listen to or read the answer.
4. Click cards to cross out monsters that no longer fit. Click again to restore them.
5. Continue until you are confident, then choose a name from the guessing dropdown and submit your guess.
6. Start a new game and try to use fewer questions.

The game tracks question history and can remember progress in the same browser.

## What children learn

- **Classification:** Grouping objects by observable attributes
- **Reasoning:** Using yes/no answers to eliminate possibilities
- **Question quality:** Some questions remove more possibilities than others
- **Voice interaction:** Spoken language can control software, but recognition may be imperfect
- **AI literacy:** Discuss how a conversational AI assistant differs from a fixed-rule guessing game

**Important distinction:** The standalone game uses predefined monster attributes and rules; its yes/no answers are not generated by a large language model. The AI-learning activity comes from designing, improving, and discussing the game with an AI assistant.

## Make it an AI creation project

Ask your child to invent a monster and describe its eyes, color, horns, wings, and name. Then, with an adult, ask an AI coding assistant:

> Help us add a new monster named [name] to our HTML Guess Who game. It is [color], has [number] eyes, and [other features]. Keep the rest of the game working.

For a more advanced variation, draw a monster on paper, photograph it, and ask an assistant to add the actual drawing as a playable card.

## Questions to ask

- Which question would eliminate the most monsters?
- How does the game know whether to answer yes or no?
- What happens if the microphone hears the wrong words?
- Which parts of this game are programmed rules, and where did AI help us build it?

## Troubleshooting

- **Microphone doesn't work:** Use Chrome, allow microphone access, and use localhost rather than `file://`.
- **Answers seem wrong:** Try shorter, concrete questions about color, eyes, horns, or wings.
- **Want to restart:** Click New Game.
- **Cards disappear:** Click a crossed-out card again to restore it.

## Safety

An adult should supervise microphone use. No child account is required for the standalone game. Browser speech recognition may use a remote service, depending on the browser.
