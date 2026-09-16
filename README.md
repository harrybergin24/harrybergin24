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

I would always appreciate any advice or suggestions, please contact me at: harrybergin@gmail.com

# Projects

### [Volatility Trading](https://github.com/harrybergin24/Trading-Volatility)

In this project I back test 30-day variance swaps, which behave similarly to straddles due to their short expiration date. However, I cannot back test how straddles would have performed in the past due to a lack of historical options data. This is an issue I repeatedly run into throughout the project. This project is broken up into several different parts, each giving a mathematical and conceptual explanation for the results. I start by giving a motivating example, the large returns of selling puts previously generated. I then move on to why this explains the presence of the Volatility Risk Premium(VRP) and what this concept is. Then I move onto the method of extracting this premium from the market, variance swaps. After discussing this product I derive the replication formula, famously discovered by a team at Goldman Sachs. I then show the connection between this formula and the methodology of the VIX, supporting my method of using adapted VIX prices to estimate the swap’s strike value. To make our VRP I forecast realised volatility using GARCH and subtracting this from the 30-day Implied volatility, which the VIX calculates. I then use the mean reversion of the VRP, to make a signal based on the deviations from a mean(I test rolling and expanding as well). Then I optimise this signal for entry parameters having different entry requirements for short and long volatility. This then generates returns over time, I am now working on analysing these returns and attempting to spot a pattern across indices where the strategy performs well or badly on. 

Recent Changes:
- Walk Foward validiation for GARCH volatitily modelling
- Train and test split for entry paramater to enter a postion
- Replication Formula derivation for the Variance Swap

Future Changes:
- Pricing forwards on variance swaps



### [Estimating Implied Probabilites From Butterfly Options](https://github.com/harrybergin24/Estimating-implied-probabilties-from-Butterfly-options-/blob/b9ce77b5b5bfa6f13370c4e48c60098c8d7963d9/Estimating_Implied_Probabities_using_Butterflys%20(6).pdf)

In this project I derive from Stephen Blyth's 'An Introduction to Quantitative Finance' the result that butterfly option prices have a conditional probability density function embedded within them. The derivation starts from gaining call spreads in terms of binary option prices, and then writing butterfly option prices as two call spreads. Then I use this connection between risk-neutral densitys, option prices and expected payoffs to answer two questions from the back of chapter 11 in Blyth's book, whose answers reveal an very important result for derivative pricing, the idea of replicating a payoff using put and call options.  

Future Changes:
- Pricing a Down-And-Out Call option using the replication formula obtained previously



