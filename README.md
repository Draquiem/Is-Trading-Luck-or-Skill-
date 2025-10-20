# Is-Trading-Luck-or-Skill-
Beware of trading gurus! (And don't quit your day job)

Trading Gurus will never cite metrics that you should actually care about, only things that will peak your interest."I make $10,000 - $20,000 a month trading", "I have 99% win-rate strategy", "etc."
  - These are never going to be ways that real traders measure their performance (ie. sharpe ratio, trade journal, true CAGR, models, backtests)

I can literally give you a strategy right now with a 99% winrate on options lol. Selling options with a crazy spread between strikes will give you a near 100% WR, but doesn't tell you anything about my strategy or performance.
One of my biggest frustrations come from people constantly falling for these "Trading Schools" and expect to be profitable. Of course, maybe one or two may find what works for them, but how many people must lose money in the process?

Tl;dr, Trading Gurus are profitable from your money, not because they know how to trade. People who actually transacts with the stock market will disburse their knowledge in a much different manners than those that don't. 

Now I will support this notion, mathematically. 

Gambling, Poker, Trading, and Edge
  - Gambling is inherently different from Poker and Trading, the main difference comes down to edge.
    - Any game where a house edge exists becomes gambling, because no matter what you do, there is no optimal decisions to make.
    - The outcome is fully governed by a probability mass function, ie. your expected value for playing this game is set to be a net negative. Example: EV of roulette is -5.26%
  - I chart this wealth path of multiple players playing roulette at the casino.
    - Notice the difference between the 100 plays vs 3000 plays. Each outcome is random, but in the long run everyone loses money. No matter what you do, you are accumulating negative EV.
   
Games of Incomplete Information
  - Just because it is difficult to learn to play optimally, it does not mean that there is negative edge against you (CRITICAL DISTINCTION)
    - Poker Bot will outperform any typical players because they are learning to optimize for EV.
    - There is no need to act with net positive EV because if you are playing vs noobs, you will profit from their poor decision making (zero sum game).
  - Just because there is possibility to act suboptimally, it does not mean that the entire space is gambling. Your action and inaction will influence EV over series of hands, trades, etc.
  - Example of reinforced learning to maximize EV of a game based on a policy.
    - Optimal Players vs Non-Optimal Players
  - Trading and Poker are two COMPLETELY dynamic games
    - Too many variance exists for us to quantify everything.
      - Poker: People at the table, how you played your last hands, etc..
      - Trading: Market Regime, News, etc..
    - Optimal policies are constantly changing based on the environment.

Day Trading
  - Analyzing sets of Net Zero EV traders
    - 100 day traders trading 1000 times, notice where these traders finish.
    - Same net zero EV strategy, but some lose and some win. This means... on average you should not be accumulating wealth.
  - Some traders may luck out and have crazy cycles where they accumulate tons of wealth, even though their strategy has a net-zero EV. Clear case of luck.
    - Even if its a crappy strategy, some people will still accumulate wealth simply based on luck.
    - Non-ergodic with slight positive EV in some cases, some may even receive extreme wealth; this is statistically plausible, but it can also be a fluke or outright lying.   
Distribution of Final Returns (Net Zero EV)
  - 7 individuals from the previous simulation accumulated wealth.
    - What about everybody else? Think of this in term of a trading school. If you have a school where you teach 1000 people how to trade, only 70 of those individuals are profitable...
      - THIS IS A TERRIBLE SCHOOL LMAO.
      - "You weren't dedicated", "You didn't quite get how to apply the course", "You didn't tune into enough Zooms", etc.

Profitable Day Trading Operation
  - Analyzing sets of positive EV traders
    - 100 day traders trading 1000 times, notice the trendline is different.
    - Losers won't lose as much and winners will win more.
Distribution of Final Returns (Positive EV)
  - 32 individuals accumulated wealth.
    - EVEN with a positive edge, 94 individuals experienced drawdowns from their initial investment.

Reality
- If you approach some sort of "day trader" or "crypto millionaire", propose time-series regressions, they would absolutely have no idea what you are talking about.
  - Institutional grade strategies, iterations, acquring/cleaning/pre-processing data, backtesting engine, etc..
  - These people are just parading around win ratios and $/month. THESE ARE NOT ACTUAL METRICS. Stop falling for BS. 
