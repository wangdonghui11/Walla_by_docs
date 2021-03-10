Vaults
======

- Vaults

  - Wallaby Staking Farm

In this farm, users can stake using their Wallaby tokens, while getting back WHT. The APR for this farm is dependent on the performance of all the other farms, since the 30% performance fee on other farms are what is collected and given out as the reward/roi for the Wallabystaking pool. Wallaby Pool has no withdrawal fee and no performance fee.

  - Wallaby/HT Farm

In this farm, users can deposit Wallaby/HT and earn even more Wallaby tokens. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours.

  - MDX Auto Compounding Farm

The MDX farm is where you can reap the benefits of automating compounding and the high APY. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours. The 30% performance fee is collected but for every 1HT in fees collected, we give 5 Wallaby, so you’re getting free money.

  - Rest of MDXSwap Farms

Currently we have Wallaby-WHT，MDX-WHT ,HBTC-WHT, ETH-WHT pools, which exist on MDXswap. Our smart contracts automatically compound your investments, giving you a higher APY. For these pools, as profit you will be getting the respective LP Token of the pool, as well as Wallaby tokens. 30% of profits will be collected and given as Wallaby tokens. For every 1HT collected, we give 10 Wallaby. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours. Currently you can only claim your profits, if you claim & exit the pool. We may change this in the future.

  - Maximizer MDXSwap Farms

The Maximizer farms takes the profits that come out of the original compounded MDXswap farm, and puts it into the MDX auto-compounding farm, in order to give you a higher apy, while protecting your principal. There should be a withdrawal fee of 0.5% if withdrawn within 72 hours. With the Maximizer Farms, users can claim their profits, without exiting the farm.

According to our test calculations, assuming that MDX price stays constant, USDT-HT Farm APY is 30%, and MDX APR is 300%, then the APY of someone who deposits into the “Yield Maximizing USDT-HT Farm” would be 189.9%. This is much higher than the 30% achieved by simply compounding USDT-HT, yet the risk is very minimal. The only risks would be if MDX price drops significantly, or if the MDX APR drops as well. That being said even if the MDX price drops significantly the principal amount invested in USDT and HT would still be the same. Similar to our regular farms, in order to fully benefit from the compounding effect, a user must have the patience to sit back and watch their money grow exponentially over time. One small complication is that because of the way the new yield maximized farms are coded through back end development, the yields earned daily (24 hour period) get distributed the next day on a rolling cycle. This means that users who deposit from day 0 to day 1 would be at a slight disadvantage as they would not be able to receive their fair share of yields for the first 24 hours. To mitigate this effect we plan on giving these early users some Wallaby to compensate for the lost yields. The graph below illustrates the difference in returns between the original Stable-HT farm and the new Yield Maximizing Stable-HT farm.

We have provided the mathematical formula for calculating the total geometric sum. Feel free to use it to personalize your calculations.

