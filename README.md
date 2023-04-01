# ChatGPT Arms
ChatGPT Arms provides a standardized interface for hooking up ChatGPT with "the real world", aka API's and third party systems, etc...

An arm is just a npm package that implements one method called `processConversation`, as the user converses with ChatGPT every arm will get a change to process the conversation using it's own logic, if that arm detects it is needed to do something (ex: check the weather) it returns a prompt rather than sending it to chatGPT.

You can see a clear example in the [WeatherArm Package](https://github.com/TaylorHawkes/ChatGPTArms/tree/main/arms/weatherarm)


## Demo

[Here is a live demo]( http://chatgptarms.com)

See video intro below to see how this works. \
[![IMAGE ALT TEXT](http://img.youtube.com/vi/o2LiPkkIjeQ/0.jpg)](http://www.youtube.com/watch?v=o2LiPkkIjeQ "ChatGPT")

## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

This is still very much a work in progress, I'm looking for contributors to help develop the core package as well as adding "Arms". 

Contributors can join us on discord : [https://discord.gg/56QKjfpa](https://discord.gg/56QKjfpa)
## Appendix

See what we need to get done on trello: https://trello.com/b/BHtgp4zU/chatgpt-arms