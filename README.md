# Discord-Bot-Stream-Notes

# Discord Bots Walkthrough

## Introduction
During the live stream we are going to be taking a look at the [Discord.js](https://discord.js.org/#/) NPM Module, which allows us to interact with the [Discord API](https://discordapp.com/developers/docs/intro) with ease. 

To name but a few of the things we will be aiming to cover:
 - The fundamentals basics of building a Discord bot with Javascript and Node
 - Some of the common places you can host your bot and the limitations found in each host
 - My experiences, failures and Aha moments, through creating and maintaining several bot of all sizes and functionalities. 
 - Interactive coding sessions, where you can suggest ideas and features, help us write the code and maybe even test it along the way. 
 - We will also be taking questions throughout the live stream, so post them in ##mentor-live-coding-chat, remember no question is a silly question!

#### What is Discord.js
> Discord.js takes a much more object-oriented approach than most other JS Discord libraries, making your bot's code significantly tidier and easier to comprehend. Usability, consistency, and performance are key focuses of discord.js, and it also has nearly 100% coverage of the Discord API. It receives new Discord features shortly after they arrive in the API.
> 
> | Why Discord.js? | | Statistics |
> | --- | --- | --- |
> | • Object-oriented |  | ![npm](https://img.shields.io/npm/dy/discord.js?label=NPM%20Downloads&style=for-the-badge) |
> | • Speedy and efficient|   | ![GitHub commit activity](https://img.shields.io/github/commit-activity/y/discordjs/discord.js?label=Commit%20Activity&style=for-the-badge) |
> | • Feature-rich |  | ![GitHub contributors](https://img.shields.io/github/contributors/discordjs/discord.js?label=Contributors&style=for-the-badge) |
> | • Flexible |  | ![GitHub stars](https://img.shields.io/github/stars/discordjs/discord.js?label=Github%20Stars&style=for-the-badge) |
> | • 100% Promise-based |  | ![GitHub last commit](https://img.shields.io/github/last-commit/discordjs/discord.js?label=Last%20Commit&style=for-the-badge) |
>

## Future of Discord and its bots!
Over the last 5 years Discord has come a long way from the gamers voice and text chat application it started out as in 2015. It now has over 250 million registered users with 14 million of them sending 963 million message every single day. 

Since Discord launched its official API back in April 2016, more than 3 million bots have been created and alone they have send over 9.5 **billion** messages. 

Discord have recognised this and recently vaguely outlined their plans for a bright new future for bots and applications in [this blog post](https://blog.discord.com/the-future-of-bots-on-discord-4e6e050ab52e). Myself and the team behind zeroBot are super excited about some of the changes being hinted at, as it will open up a bunch of new opportunities and different implemenations of the bots functionalities to make it more helpful and less spammy. 

## Hosting Options
There are a range of hosting options available for you to choose. Which one you should chose is going to vary on your needs and budget. Each of the options have their pros and cons, which you will need to weigh up against you requirements. In order of my personal favourites, the most common options are:

**[Digital Ocean](https://m.do.co/c/872bc7d3700d)**
Personally his is my favourite method, although this option isn't for everyone due to the requirement for an understanding of devops, this method provides a lot of freedom, customisability and a complete tailored solution. You can also run multiple bots on the same droplet. 

| Pros | Cons |
| --- | --- |
| • Cheap | • Not Free |
| • Freedom | • Complex setup |
| • Allows dynamic files | • Complex CI/CD |
| • Multiple Bot per acc | • Security Risks |

AWS and similar VPS services, would also fall into this category. And whilst hey are all valid options, I generally default to Digital Ocean due to familiarity and ease of use. 

**[Heroku](https://www.heroku.com/)**
I started out hosting my bots on Heroku and will occasionally still use Heroku for simple bots that are maybe under collaborative development, due to the simple CI/CD options available. 

| Pros | Cons |
| --- | --- |
| • Free | • No dynamic files |
| • Easy Setup | • Sleeps when inactive |
| • Easy CI/CD | • Less configurability |
| • Set it & forget it |  |


**[Vercel (formerly now.sh/zeit)](https://vercel.com/)**
I haven't really used this enough to really pass judgement and they have likely undergone major changes since I last used them. The service was fairly similar to Heroku, however the installation and configuration was more complex and time consuming than it needed to be. 

**Your own PC**
Running the bot from your machine during development is one thing, However I really wouldn't recommend this option, especially long term.


## Time To Code!
Coding a Discord bot is fairly straight forward, most people are often shocked at how little code is required to get a basic bot running. But before we look at any code, lets take a quick look at the requirements. 

#### Requirements: 
1. **Javascript Knowledge** - You can create Discord bots in a range of different languages, but we are going to focus on Javascript here. However, I would imagine some of it will translate across languages. 

Obviously the better you know Javascript, the easier you will find coding your bot. But a basic understanding is all it takes. Zerobot v1 was born in my first month of learning Javascript!

2. 


## Resources
- [Future Update](https://blog.discord.com/the-future-of-bots-on-discord-4e6e050ab52e)
- [Event Cheat Sheet](https://gist.github.com/koad/316b265a91d933fd1b62dddfcc3ff584)
- [An Iditos Guide](https://anidiots.guide/)
- [Super simple bot example](https://github.com/amishshah/discord.js-guide/blob/master/development/first-bot.md)
- [Discord JS Documentation](https://discord.js.org/#/)
- [Heroku Hosting Example](https://www.youtube.com/watch?v=NM8IMyqpvqU)
