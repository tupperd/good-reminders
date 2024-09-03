# good-reminders

## The Premise
Over the course of our days, weeks, and months, we get exposed to *so much* insightful information. The impulse for peole like me (and maybe you as well) is to record this information, whether it's through written or digital notes, pictures, etc. 

The issue with that is these notes are often "write once, read never" - *what good is that insight if it's locked away in notes that will never read?*

`good-reminders` gives you a way to regularly re-expose yourself to that information you'd like to keep top of mind. It isn't backed by a scientifically elaborate spaced repetition mechasism, but rather a simple randomization algorithm. 

The idea is that you never know what information might help you unlock a solution to a problem or motivate you to stay the course. By keeping the app in a place that's readily available, you can easily remind yourself of the wisdom you've gathered over time!

## User Guide
### Demo App
[https://tupperd.github.io/good-reminders/](https://tupperd.github.io/good-reminders/)

### Useful Keystrokes
* Press `s` to shuffle the quote being displayed
* Press `c` to toggle available controls
* Press `g` to toggle a fun surprise!

## Motivation / Backstory
I wanted a system like this, but couldn't find anything quite like it. I was searching for something that was easy to display, could add/subtract content easily, and had a simple interface. 

As someone with a limited development background, I didn't want to take the time required to create/debug/test something like this. I took the opportunity to test the capabilities of [Claude 3.5 Sonnet](https://www.anthropic.com/news/claude-3-5-sonnet) to develop a simple web app. 

There has been significant discourse around whether AI can or will replace SWEs - I'm not educated enough to comment on that. What I can say is that I was floored by how easily the model could translate my pseudocode, narrative descriptions of what I wanted to functional HTML/CSS, JavaScript, and Python.

## Backlog 
* Support for both images, videos, etc.
* Formatting nice-to-haves (slightly less wide, newlines for quoted individuals, etc.)
* Documentation for others to replicate for themselves
* Easier ability for adding / subtracting quotes
