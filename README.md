# Slot_Machine 🎰 [GPK adds-on]
![UI](https://www.linkpicture.com/q/SM.png)
### Summary
This is a Python Based Game, self_adjustive slot machine 🎰 with theme "Grand Peach King" 
### Original Rules
The probability is derived and modified from the original rules with minor changes. (That all tokens are identical to the ones used in GPK)
![Rules](https://www.linkpicture.com/q/rules_6.png)
### Adaptation
I have made the following Adaptations to make this python simulation of slot machine more "Addictive" and FUN!
1. **Expected Value Enginerring**: I have seen many avaliable Slot Machine (that is made by python), they all have a postive expected value per dollar. That is very unideal, since then you can actually make money out of Gambling. Which is Not what I have aimed for. So I introduced the idea of "tickets", that instead of put money directly into the machine, you purchase tickets and then the slot machine will output rewards beased on your tickets. For instance, if you purchased 10 tickets with about $20, and then you get a 🍑🍑🍑, you will receive 10 times7 = $70! And with this menchanism, I was able to design a function that alters the tickets price so that the expected value per roll is NEGATIVE. (That in long run, gambling is a BAD BAD idea) 
2. **Adjustive Expected Value** As you might have noticed in the picture above, as you "Empty" the JackPot with however the technique you got, the program is goint to make it harder for you to squezz more moeny out! This was made possible by introducing a Step-Function I enginered myself that looks like this: ![adjuster](https://www.linkpicture.com/q/adjust.png)
as you empty the jackpot, the expected value will decrease expoentially and so will the ticket price been drive up expoentially. Quite fun isn't it! (If you empty the JackPot, it will Reboot itself to $1200.)
### Hit me up if you have any suggestions @ bliao2@uci.edu, and have fun!

