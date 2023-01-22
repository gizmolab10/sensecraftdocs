# Software Architecture

Do we have a strategy to follow? If we break down the application into independent modules that communicate solely through an api, we can optimize our engineering and software efficiency. One approach is [micro services](https://microservices.io/).

What is a good list of modules? Here is Aaditya's attempt:

![[modules.png]]  

Here's my attempt.

1. authentication
2. roles, rules & actions
3. web services for data store
4. manage tree
5. scoring & levels
6. groups, quests & guilds
7. UI
	1. forms
	2. render tree
	3. help