# BotScript
## Getting started
Use following code to create an entity
```
add.entity.hello: hi, hello, hey;
```
Following code allows you to create an intent from an entity
```
add.intent.sayHello: hello => Hi human;
```
## Building your first bot
This is sample bot project with botscript
```
add.entity.question: what, where, how;
add.entity.bot: you, bot, robot;
add.entity.age: old;
add.entity.home: live;
add.intent.askAboutBot: question + bot => I am fine Thank you;
add.intent.askAboutHome: question + bot + home => I live on the cloud;
add.intent.askAboutAge: question + age + bot => I have just been born;
```
