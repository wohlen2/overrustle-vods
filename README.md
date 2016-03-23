# OverRustle VODs

**OverRustle VODs** is a simple web app that plays Destiny Twitch VODs with the destiny.gg/OverRustle chat along the side in real-time. It supports pausing and resuming the chat stream when the Twitch VOD is paused but currently does not support seeking and probably won't work if the chat for the VOD spans two days.

## Running the Project

OverRustle VODs requires Ruby to run properly. I've tested with Ruby `2.2.1p85` using rvm on Ubuntu 14.04. To build the project simply run 

```
bundle install
```

to install all gem dependencies and then start the project with 

```
ruby app.rb
```
