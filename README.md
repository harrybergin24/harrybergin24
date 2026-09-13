## Harry Bergin

<!-- 
**harrybergin24/harrybergin24** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
I am a second year Mathematics student at Durham University. I am currently preparing for the Simon Marais competition. 

I am fascinated by structured products and derivatives, I am researching everyday the process around how different products are created and priced.

# Projects

### [Volatility Trading](https://github.com/harrybergin24/Trading-Volatility)

I back test 30 day variance swaps, variance swaps with short time frames behave similar to selling straddles. However, this option to trade volatility is not possible for me to back test, due to a lack of access to historical options data. I have included in this project the old version and the new version I am currently working on. This starts with a motivation for volatility trading, moving on to discussing the Volatility risk premium. After, I derive the replication formula connecting it to the VIX, which supports my idea for using the VIX as a proxy for the strike value $K_{Var}$. Then developing to forecasting future volatility, implementing GARCH. Then moving on to the back test of the strategy, testing on in and out of sample data. I then compare this to the same strategies returns on the Nasdaq and will try and explain the causes of differences. I am currently working on the forecasting of volatility and working my way through everyday, this is a working project that I will continue to adapt overtime. 

Recent Changes:
- Walk Foward validiation for GARCH volatitily modelling
- Train and test split for entry paramater to enter a postion
- Replication Formula derivation for the Variance Swap

Future Changes:
- Pricing forwards on variance swaps



### [Estimating Probabilites from butterfly options](https://github.com/harrybergin24/Estimating-implied-probabilties-from-Butterfly-options-/blob/b9ce77b5b5bfa6f13370c4e48c60098c8d7963d9/Estimating_Implied_Probabities_using_Butterflys%20(6).pdf)

In this project I derive from Stephen Blyth's 'An Introduction to Quantitative Finance' that butterfly option prices have a condtional probaiblity density funciton embedded in within them. This has a very nice link to my project as the derivation starts from gaining call spreads in terms of binary option prices, and then writing butterfly option prices as two call spreads. This is the same idea used in the replication method to gain a 'fair strike' value for the variance swap, that a contiummum of call options can be used to replicate different derivative contract payoff functions. 

Future Changes:
- Pricing a Down-And-Out Call option using the replication formula obtained previously



