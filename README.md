# 𝒯𝒽𝑒 𝒜𝓇𝒸𝒶𝒹𝑒 𝒞𝑜𝓃𝓈𝓉𝒾𝓉𝓊𝓉𝒾𝑜𝓃

Arcade is a game where you get prizes for building, documenting, and shipping projects.

The spirit of Arcade is for you to build stuff in a hacker mindset. Start a project, push it to an MVP as fast as possible, publish it, then iterate quickly. We have rules and standards for review, but the ultimate thing those rules are trying to get at is "are you doing real work on personal projects in a hacker mindset".

This is the first draft of a living document defines "what counts" for the Hack Club Arcade. It should be a short and sweet reference for Arcade players and reviewers alike. Comments, pull requests, and questions are welcome.

## The Essential Phases

Arcade has three essential phases:

1. **Build** projects and log your hours with `/arcade`
2. **Document** progress in a git-based versioning system
3. **Ship** a shareable version in #scrapbook when it's ready

After you ship, you'll get a ticket for every hour that passes review. Spend these tickets with `/shop`

### What counts as a "Project"?

A project is a self-directed creative effort toward an output that other people can meaningfully experience.

<details>
<summary>Fine Print</summary>
<ul>
<li>leetcode or similar challenges do not count</li>
<li>Homework or work done for a job/commission are not self-directed and therefore don't count</li>
<li>Projects started (but not finished) before Arcade are okay, but only the work done during Arcade can be logged</li>
<li>Tutorial projects that are 1:1 copies of the tutorial do not count. If you're doing a tutorial, you need to "make it your own" in some way</li>
</ul>
</details>

<!-- <details>
<summary>Examples</summary>
❌ Homework (not self-directed, usually no output that someone else can experience)
✅ Personal projects

❌ A drawing of a circuit (cannot meaningfully experience)
✅ A manufactured circuit

❌ Cooking a meal (insufficiently meaningful output)
✅ Publishing a recipe you developed over multiple iterations

❌ Completing the donut Blender tutorial (not self-directed)
✅ Modeling something you dreamed up and sketched

❌ Messing with Unity's particle system (no specific output)
✅ Publishing a playable game or demo online

❌ Watching a video on how to knit
✅ Knitting a sweater

</details> -->

### What counts as "Documenting progress"?

The journey of each project must be shared in a public git repository, with at least one update committed per hour logged.

<details>
<summary>Fine Print</summary>
<ul>
<li>Every update needs a link to the git commit for that hour</li>
<li>For code or other text-based content, put the actual code in the repo. For everything else, images or videos are fine—in the repo though!</li>
<li>Any git-based system is allowed, but GitHub is preferred. Many of our review automations are built around GitHub, so other systems may be more annoying for you to use.</li>
<li>When submitting a single session scrapbook, you are required to include 2 mini-scraps throughout the session to help our reviewers clearly understand your progress. It is a progress update (not necessarily a git-commit) showing your progress through this part of the session. This could be screenshots of art or CAD or product of your code, or git commits, multiple times throughout your session and sent in the thread.
</li>
</ul>
</details>

<!-- <details>
<summary>Examples</summary>
❌ Screenshots of your code
✅ Links to commits on GitHub

❌ A description of your latest game feature in Slack
✅ A screenshot of your latest game feature on GitHub

More examples!!

</details> -->

### What counts as "Shipped"?

A shipped project must be shared in a way that other people can experience to the greatest possible extent.

<details>
<summary>Fine Print</summary>
<ul>
<li>Your repo needs a README</li>
<li>Ships must be shared in the Hack Club Slack with a post in #scrapbook. They also need a screenshot or video or URL to experience the thing</li>
<li>There must be a component of the ship that can be experienced by people in Slack</li>
<li>For digital but non-code projects, a file—and, for some online tools, a link—of the "most native" type for the project must be included. STL and .blend for Blender, PNG and project link for Figma, Gerber file and CAD file for PCBs, STEP export and STL for CAD (with a link for OnShape projects), PNG for and source file (PSD, XCF, etc) for digital art…</li>
</ul>

Some examples of "native" websites diffferent types of projects are below. Keep in mind, this isn't an exhaustive list, but a big part of "shipping" a project is getting others to experience it & this is a good way to do that.

- 3D printing files
    - https://thingiverse.com
    - https://printables.com
    - https://makerworld.com
- Blender files
    - https://blendswap.com
    - https://sketchfab.com
- Games
    - https://itch.io
    - https://gamejolt.com
- Web projects
    - https://vercel.com (if a website)
    - https://github.com (Using GitHub Pages)
- Game mods (different for every game)
    - https://www.spigotmc.org (for Minecraft mods)
    - https://modrinth.com (for Minecraft mods)
    - https://hangar.papermc.io (for Minecraft plugins)
    - https://www.moddb.com/ (for source games)

## Python projects

In particular we find python projects are often the hardest to ship. A couple approaches you can take:

- If you have a package, you can publish it to PyPi
- If you make a game or executable, you can publish it with pygame or pyinstaller
- If all else fails, you can publish it to GitHub and include a `requirements.txt` file & a `poetry.lock` file & cut a release

Many python projects end up being just a `script.py` file in a repo, which isn't a real project because it may only work on your machine. Keep in mind that the goal is to make your project accessible to others & everyone has different versions of python and different dependencies installed.

</details>

<!-- <details>
<summary>Examples</summary>
❌ A scrapbook post verbally describing your website
✅ A link to a deployed version of the website

❌ A picture of your robot just sitting there
✅ A video of your robot completing its task

More examples!!

</details> -->

## The Essential Vibes

The gray areas of "what counts" are ultimately resolved with a vibe check. Here are some vibey questions we may ask ourselves when assessing whether something counts for Arcade:

- **How technical is this project?**
- **Is this person pushing themselves?**
- **Does this project feel wholesome?**
- **Is this a highly self-directed project?**
- **Is this a good story?**
- **Am I amazed?**

These are not criteria or requirements, they are just vibes. But when a project is in a gray zone, these vibes guide our decisions.

## Other Rules

<ul>
<li>This is a living, changing document. Rules have changed and will continue changing. For practical reasons we have to enforce whatever the latest rules are, even for hours that were submitted before the change.</li>
<li>You can't bank more than 25 hours at a time, because of arcane technical reasons, but also because you should be shipping and iterating on a loop tighter than 25 hours</li>
<li>If you use an AI tool to generate code, explain broadly which tool and how you used it at the top of the file. Using AI is fine but we are going to make a judgment call on how much we consider it to be "your work". Undeclared AI is considered plagiarism, so please be honest</li>
<li>If we think you have knowingly submitted something fradulent, we will either give you negative hours or just ban you outright</li>
<li>Nothing that breaks the law or facilitates breaking of laws, please</li>
</ul>

## Happy Hacking!

Build stuff, get stuff, repeat. All summer. _(ends August 31st)_
