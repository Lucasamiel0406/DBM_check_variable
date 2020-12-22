```
- Check Variable in nutshell -
```
![Check Variable Action](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201128-182814.png)
<p>&nbsp;</p>


Check Variable is a simple action to compare a variable, not limited only to text (string) and great for several functions, you can check the content of a message, check if a channel or user exists, there are several possibilities and ways to use this action, but as not everything is flowers, blind and intelligenceless beings exist, it's necessary to say that.
<p>&nbsp;</p>
<p>&nbsp;</p>

---------

In case you didn't notice the Staff almost crucifying members in the bug channel. *The action is not broken*, there's nothing wrong, the __UPDATED__ version works __*PERFECTLY*__.
If you're having problems with this action, here is a short list of common mistakes you can make when using this action:


* **1** - (Maybe, it's rare) You are using the old action with updated `bot.js` or the other way around. <p>&nbsp;</p>
![Enable auto update bot.js](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201128-183843.png)

`Solution 1:` Enable auto update bot.js, `Options > Automacally updated Bot.js`.
`Solution 2:` Go to Steam, open your Library, right click DBM, go to Properties and `Check Integrity` to get up-to-date default actions.

* **2** - You are using the message object instead of its content (Await Response doesn't store the message content, but its object) <p>&nbsp;</p>
![You need to store the message info after storing the variable in Await Response action](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201128-184632.png)

`Solution:` Sotre the Message Object using `Await Response` and then use `Store Message Info` to store the message content.

* **3** - You forgot the damn `'` at the beginning and/or at the end <p>&nbsp;</p>
![Everyone does that at least 10 times](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201128-184215.png)

`Solution:` The name is self-explanatory, if you want to compare text you need to treat it like a Javascript [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String). For numbers you can check [this reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number).

* **4** - You used a variable in the wrong way, instead of `tempVars("Something")` you did `${tempVars(" Something")}`. (But there's especific cases where you need `${}`, be careful) <p>&nbsp;</p>
![Remove "${}" and try again](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201128-184034.png)

`Solution:` Remove `${}` and try again.

* **5** - You forgot something about the variable or made a typo, a `{` maybe, erased something, always check for missing stuff <p>&nbsp;</p>
![There's always a typo playing hide 'n seek with you](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201128-184140.png)

`Solution 1:` There's always a typo playing hide 'n seek with you, check all your `Check Variables` and look for something missing.
`Solution 2:` Do `Solution 1` again or delete the action and redo it.

* **6** - You used `'<number>'`, number related options DON'T need `'` or that can return an error/nothing. <p>&nbsp;</p>
![Just leave the number there.](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/Screenshot_Lucasamiel0406_20201201-223524.png)

`Solution:` Number related options needs numbers, trying to use it like you're comparing a string will probably return an error, check [this reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number).

* **7** - You used DBM first before using your brain and logical reasoning. <p>&nbsp;</p>

`Solution 1:` Take a break, drink some water and go back to DBM.
`Solution 2:` Use your brain.
`Solution 3:` Think about what you're trying to do, what you'll check and create a mond path to understand better *what the hell* you're doing.
`Solution 4:` Delete DBM and start learning again how to use a computer.
<p>&nbsp;</p>
<p>&nbsp;</p>

---------

If the action returned an error, __use the support channels__, don't look, think or imagine the bug channel, that channel is for **real bugs** and not for your mistakes or contraptions that go wrong, talk with people and try understand what you're doing wrong.
If you've read this far, started using the action properly and just deleted the message you were writing about `Check Variable` not working, thanks a lot, but if you persist in asking for help on this channel because something went wrong with the fully functional action, don't complain when you get a warn or someone is rude to you.
<p>&nbsp;</p>
<p>&nbsp;</p>

Regards,

me (Lucas Amiel) and all users/staff bored with the same questions. ![:seiki:](https://raw.githubusercontent.com/Lucasamiel0406/DBM_check_variable/main/src/4k%20Seiki%20because%20I%20wanted.png)
