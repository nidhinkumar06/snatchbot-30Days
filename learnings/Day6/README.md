<div align="center">
  <h1>SnatchBot - Day 6</h1>
  <p>SnatchBot User Attributes</p>
</div>

Unique Information to do a personalized approach

User attributes are like getting the user name / subscription from the user and storing it across the bot

There are two types of attributes

* Facebook attributes
* Custom attributes

Custom Attributes

Now we will see how to get the name of the user and display the name is other interactions

1. Open SnatchBot and click `MyBots` and the select `Interactions`
2. Once the interaction is selected Click `BotMessage` and type the message `Hi, what is your name`
3. Create one more interaction named `NameDisplay` and type the message as follows

```
Hi [responseTo interaction=12345(add the id of the previous interaction), fallback=TEXT]

Hi, [responseTo interaction=1778235 fallback=TEXT]
```

4. Go to the first interaction and click `connections` and select the Fallback Connection to `Second Interaction` like below image

<div align="center">
   <img src="../../assets/Day6/Build - SnatchBot.jpg" alt="snatchbot" height="300">
</div>

First Interaction

<div align="center">
   <img src="../../assets/Day6/Build - SnatchBot (1).jpg" alt="snatchbot" height="300">
</div>

Output

<div align="center">
   <img src="../../assets/Day6/Build - SnatchBot (2).jpg" alt="snatchbot" height="300">
</div>


[Watch the different types of user attributes](https://www.youtube.com/watch?v=SvEaNg33DAs)