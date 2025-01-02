### Hi there! My name is Gabe Heim 👋

#### About Me

 - 🖥️ Software Engineer at an investment firm in Austin, TX
 - 🏫 Pursuing and MS in Artificial Intelligence at the University of Texas
 - 📈 Passionate about the application of machine learning in financial markets

#### Current Focus

I am currently working on a suite of projects that work together towards the common goal of algorithmic trading and strategy generation. The logic is mostly in python, but once it is more ironed out I plan to move the portions that are sensitive to latency and reliability to C++ and/or Rust (as I learn and become more familiar with these tools). Some of them take the form of private repos, but as these components mature I plan to make them public to be accessible as libraries for those working on similar projects. This will also enable the inherent benefit of being open source and crowd-sourcing feature development, which I am a strong believer in. I tried to have a bit of fun with these projects by naming them after robot characters from pop culture, you will likely recognize a few! Below I list these projects and their current state of development.

#### Notable Repositories

##### BMO

BMO connects functionality from many of these repos and houses ongoing tasks that require continuous processing. Calls to the scripts in this repo are likely what would be in your service files on your server. When I was starting out with these projects, I used a Raspberry Pi as a server, which happens to remind me of the character BMO from Adventure Time, hence the naming choice.

##### Calculon

Calculon is perhaps the most library-esque repository in this collection. Most of the utility functions that require complex calculations live here. Think position sizing, technical indicator calculations, other feature extractions, data organization, etc. When it comes to big-number "stuff", you think it -> Calculon calculates it. The name comes from the character Calculon from Futurama, a robot whose calculation skills are unmatched, and those of which this repo attempts to live up to.

##### HAL

HAL contains code involved in the evaluation of algorithmic trading strategies, namely backtesting and plotting. HAL tends to not get deployed and is more of a local utility used alongside the research and experimentation done using some of these other repos. Its name comes from the antagonist robot in 2001: A Space Odyssey series, a series of which has a beautiful movie which I internally connected to the beautiful-ness of the Bokeh plots this repo produces. It also deals with old/historical data through its backtesting abilities, which somewhat represents the fact that the series it is named after is a bit older.

##### Linguo

None of these other projects could do their jobs without Linguo. It is in-fact the most depended upon project in this suite. The prefix "ling" comes from the Latin root "lingua, meaning "tongue" or "language", which gets at the heart of what this repo is trying to do. It is a translator of sorts, both from the outside and within the suite, for the rest of the projects within this suite. It contains many constants to ensure all of these projects adhere to the same "language", think interval (1m, 5h, etc) notations, trade actions that get stored centrally ("BUY", "SELL", "TAKE_PROFIT", etc). Linguo also deals with the nuances of different languages of outside systems, and therefore maintains api clients that interact with foreign systems. Its name comes from the grammar-correcting robot Linguo of The Simpsons, but its name sounded more like a translating robot to me.

##### Roomba

Named after your favorite household automated cleaning object, collects everything in sight. This is an Alembic- and SQLAlchemy-focused repo that contains everything "database" to help drive the central storage of the other repos in this suite. Much like a Roomba sucks up dust, this repo provides the building blocks to suck up every piece of data it knows how to structure.

##### Sonny

Sonny in the movie i-Robot represents something groundbreaking in society, his creation was a singularity-level event where an autonomous robot learned to act of its own volition. This repo represents something else groundbreaking: the intersection of machine learning and finance. Bringing the character's artificial intelligence theme to this suite, everything machine learning and strategy generation related lives here. This is the good stuff, the work that led me to create all its robot companions.

##### Terminator

The Terminator likes terminating things, much like the critical step of many deployment processes! Terminator contains the deployment portions of this suite's SDLC stack, and it primarily does this via Ansible. My playbooks for setting up servers to provide a home for these projects, as well as actually deploying them, live here. Don't worry when a service goes down, because _IT WILL BE BAAACK_.

#### Contact

Email: gabe.heim@yahoo.com

LinkedIn: https://www.linkedin.com/in/gabe-h-01450493/

<!--

##### R2-D2

Stay tuned.

##### Wall-E

Stay tuned.

<!--
**gabe-heim/gabe-heim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
