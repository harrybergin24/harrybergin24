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
I am a second year Mathematics student at Durham University.

I'm working on improving my mathematics as in the future I want to do projects on risk premia investing, studying volatility and skew risk premia as well and modelling volatility for different types of options in particular interest rate options to come up with rich/cheap indicators. 

Besides this, I am interested in Football, Cricket, History and Economics. 

# Projects

### [Volatility Trading](https://github.com/harrybergin24/Trading-Volatility)

Using VIX and S&P 500 data, I develop a back test for a variance swap strategy making long/short positions, rolling 30 days. Due to not having access to historical options data, I use the VIX index as a proxy for estimating the 'fair strike' of a variance swap, due to it's same methodology of using a weighed strip of OTM options. Then I forecast future volatility as a weighted linear combination of past rolling day volatilities, then using this to create a VRP(volatility risk premium). Which then I use as a signal to enter positions using basic mean reversion. 

### [Estimating Probabilites from butterly options](https://github.com/harrybergin24/Estimating-implied-probabilties-from-Butterfly-options-/blob/608c93dbc34c6c1a3c3343246774f05a49db1944/Estimating_Implied_Probabities_using_Butterflys.pdf)

In this project I derive from Stephen Blyth's 'An Introduction to Quantitative Finance' that butterfly option prices have a condtional probaiblity density funciton embeddedin within them. This has a very nice link to my project as the derivation starts from gaining call spreads in terms of binary option prices, and then writing butterfly option prices as two call spreads. This is the same idea used in the replication method to gain a 'fair strike' value for the variance swap, that a contiummum of call options can be used to replicate different derivative contract payoff functions. 


