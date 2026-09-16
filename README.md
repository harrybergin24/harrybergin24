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
I am a second year Mathematics and Statistics student at Durham University. I am currently preparing for the Simon Marais competition. 

I am fascinated by structured products and derivatives, I am researching everyday the process around how different products are created and priced.

# Projects

### [Volatility Trading](https://github.com/harrybergin24/Trading-Volatility)

In this project I back test 30-day variance swaps, which behave similarity to straddles due to their short expiration date. However, I cannot back test how straddles would have performed due to a lack of historical options data. This is an issue I repeatedly run into throuhgout the project. However, I realised there was a connection between the replication formula for a variance swap and the VIX, I adapt this VIX value to be the strike of the swap. The motivation for back testing this strategy is this idea of the Volatility Risk Premiumum. This is central to the project, the volatitliy risk premium is a premiumum investors are willing to insure agaisnt large market moves. It can be thought as being parrell to the keynesian beauty contest as its not about individual and investors and other higher moment belefis having a certain view about a future market moves, it is the fact investors despite what ever market conditions dislike negative returns. However, the VRP would be constant if investors beleifs did not impact the risk premium, so its not a link that 

Recent Changes:
- Walk Foward validiation for GARCH volatitily modelling
- Train and test split for entry paramater to enter a postion
- Replication Formula derivation for the Variance Swap

Future Changes:
- Pricing forwards on variance swaps



### [Estimating Implied Probabilites From Butterfly Options](https://github.com/harrybergin24/Estimating-implied-probabilties-from-Butterfly-options-/blob/b9ce77b5b5bfa6f13370c4e48c60098c8d7963d9/Estimating_Implied_Probabities_using_Butterflys%20(6).pdf)

In this project I derive from Stephen Blyth's 'An Introduction to Quantitative Finance' the result that butterfly option prices have a conditional probability density function embedded within them. This has a very nice link to my variance swap project as the derivation starts from gaining call spreads in terms of binary option prices, and then writing butterfly option prices as two call spreads. This is the same idea used in the replication method to gain a 'fair strike' value for the variance swap, that a continuum of call options can be used to replicate different derivative contract payoff functions. 

Future Changes:
- Pricing a Down-And-Out Call option using the replication formula obtained previously



