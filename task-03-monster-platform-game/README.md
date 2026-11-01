# Task 3: Build a Monster Platform Game with AI

**Age:** 4–8 (with a parent) · **Time:** 45–90 minutes across one or more sessions · **Difficulty:** Beginner with AI assistance

**[Play the example game online](https://bmakrinik.github.io/AI-for-kids/task-03-monster-platform-game/)** (requires GitHub Pages to be enabled)

**[View or download the sample HTML game](index.html)**

## Goal

Create a playable arcade-style monster adventure **with your child**, using drawings and an AI coding assistant. The child is the game designer; the parent helps with the AI prompts, files, and testing. The goal is to practice describing ideas, iterating on AI output, and noticing and fixing mistakes—not just playing a game.

## What you'll need

- Paper, markers or crayons, and a phone/camera to photograph drawings
- An AI assistant that can work with images and generate HTML/JavaScript
- A laptop or desktop browser to run the game
- Optional: an image editor to crop monsters and remove their backgrounds

## Build your own game

### 1. Draw the heroes (10–15 minutes)

Have your child draw **four monsters**, or begin with one and add more later. Photograph each drawing separately, with good lighting. Ask your child what each monster can do: jump, fly, bounce, or collect stars. Give them temporary names **Monster 1, Monster 2, Monster 3, and Monster 4**.

**Sample AI prompt:**

> We are a parent and a young child building a friendly arcade platform game. Here are four drawings my child made. Turn each drawing into a clean game-ready character image. Preserve its recognizable colors and features, remove the paper background, and keep the character fully visible. Label the four choices Monster 1, Monster 2, Monster 3, and Monster 4.

**What kids learn:** AI can transform their own ideas, but they should inspect whether it preserved what matters.

### 2. Design the rules together (5–10 minutes)

Ask: *What should the monster collect? What should it avoid? How do we win?* Start simple: collect stars, jump over obstacles, and finish a level. Decide whether the monster can fly, and whether a collision slows the player or restarts the level.

**Sample AI prompt:**

> Make a single-file HTML arcade game for a 5-year-old. Let the player choose Monster 1, 2, 3, or 4. The monster runs automatically, jumps with Space or Up, and flies with F or Right. Add large on-screen Jump and Fly buttons. Collect stars, avoid obstacles, and show a clear success screen. Use friendly colors, large controls, and no scary content. Embed any needed images so the HTML works on its own.

**What kids learn:** Translating ideas into specific, testable instructions.

### 3. Invent four worlds (10–15 minutes)

Choose a different setting for each level. The [sample game](index.html) uses a colorful starting world, the Moon, the clouds, and a Greek island. Encourage your child to invent their own themes instead.

**Sample AI prompt:**

> Add four levels with different backgrounds and obstacles. Level 1 should be easiest; later levels can be more challenging. Show a Next Level button when enough stars are collected, and make the Enter key advance to the next level too. Keep the same four selectable monsters and controls.

**What kids learn:** Breaking a large project into smaller, manageable changes.

### 4. Make it look and feel right (10–20 minutes)

Play a few seconds, then ask your child: *What would you change?* Let them direct one change at a time—larger monsters, brighter skies, different obstacles, or a more detailed island.

**Sample AI prompts:**

> The monster has a dark rectangle around its edges. Remove the background so only the monster appears. Don't change its face or colors.

> The island level looks too plain. Make the actual playable level feel like a sunny Greek island, with white houses, blue rooftops, and sea views. Don't just show a separate concept picture.

> When the player completes level 4, show fireworks and the word CONGRATS. Add a Play Again button.

**What kids learn:** Giving precise feedback and distinguishing a nice-looking mockup from a working result.

### 5. Test, debug, and play (10–20 minutes)

Check together:

- Can you choose any of the four monsters?
- Do Jump and Fly work on the keyboard and on-screen?
- Do stars increase the counter?
- Can you move from one completed level to the next, including with Enter if requested?
- Do all four levels work, and does the final celebration appear?

When something breaks, describe **what you did, what happened, and what you expected**.

**Debugging prompt:**

> After finishing a level, pressing Enter does nothing. Please fix the keyboard handling so Enter starts the next level, without breaking the Next Level button. Explain the change simply.

**What kids learn:** AI makes mistakes; testing and clear feedback are part of creating software.

## Run the sample

Open [index.html](index.html) in a desktop browser. It is a self-contained HTML game with embedded character artwork. Alternatively, use the [GitHub Pages version](https://bmakrinik.github.io/AI-for-kids/task-03-monster-platform-game/) after deployment.

**Controls:** Space / Up = Jump · F / Right = Fly · on-screen buttons = Jump and Fly. Select one of the four monsters before playing.

## Sample files

- [index.html](index.html) — complete four-level playable example with four generic monster choices, star collection, jump/fly controls, and final fireworks.
- This README — reusable parent-and-child instructions and prompts to create a different game.

## Talk about AI afterward

Ask: *Which ideas came from you? What did AI create? What did it get wrong? How did we fix it? If we changed the prompt, what changed in the game?* Emphasize that the child is the designer and AI is a tool.

## Safety

An adult should handle the AI account and uploads. Prefer drawings to photos of children. Review generated code and avoid pasting personal information into prompts.
