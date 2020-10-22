# Slot_Machine 🎰 [GPK adds-on]
![UI](https://www.linkpicture.com/q/SM.png)
### Summary
This is a Python Based Game, slot machine 🎰 with theme "Grand Peach King"
### Original Rules
The probability is derived and modified from the original rules with minor changes. (That all tokens are identical to the ones used in GPK) 
![Rules](https://www.linkpicture.com/q/rules_6.png)
### Adaptation
I have made the following Adaptations to make this python simulation of slot machine more "Addictive" and FUN!
1. **Expected Value Engineering**: I have seen many available Slot Machine (that is made by python), they all have a postie expected value per dollar. That is not very ideal , since then you can actually make money out of Gambling. Which is Not what I have aimed for. So I introduced the idea of "tickets", that instead of put money directly into the machine, you purchase tickets and then the slot machine will output rewards based on your tickets. For instance, if you purchased 10 tickets with about $20, and then you get a 🍑🍑🍑, you will receive 10 times 7  = $70! And with this mechanism, I was able to design a function that alters the tickets price so that the expected value per roll is NEGATIVE. (That in long run, gambling is a BAD BAD idea)
2. **Adjusting Expected Value** As you might have noticed in the picture above, as you "Empty" the Jack Pot with however the technique you got, the program is going to make it harder for you to squeeze more money out! This was made possible by introducing a Step-Function I engineered myself that looks like this: ![adjuster](https://www.linkpicture.com/q/adjust.png) as you empty the jackpot, the expected value will decrease exponentially and so will the ticket price been drive up exponentially. Quite fun isn't it! (If you empty the Jack Pot, it will Reboot itself to $1200.)

### Hit me up if you have any suggestions @ bliao2@uci.edu, and have fun!
