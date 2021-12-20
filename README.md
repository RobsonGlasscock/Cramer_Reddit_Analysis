# Cramer_Reddit_Analysis
Data and analyses related to a Reddit thread about Jim Cramer's stock selections. 

Here is the original analysis that was posted: https://www.reddit.com/r/options/comments/mte1rw/i_analyzed_all_700_buy_and_sell_recommendations/

The author of the original post concluded that looking at Cramer's buy recommendations from around the first quarter of 2021 would result in a 555% cumulative return. The author calculated returns on around 600 individual stocks and then summed up each stock's return to arrive at this figure. In my opinion, the actual cumulative return was around 0.4%. The reason for the difference in the return figures is that the weight of each stock in the overall portfolio was not considered by the author. 

Here is my response to the author: 

In my opinion, the claim that Cramer's recommendations resulted in a 555% return is inaccurate. This result comes from summing up the returns on each stock, but I believe this misses the important step of considering the percentage that each asset in the portfolio makes up of the total amount invested.

Consider a counterfactual portfolio of two assets: Asset A and Asset B. The investor has $1,001.00 to invest in some mix of these two assets. The investor decides to invest $1.00 in Asset A and $1,000.00 in Asset B. The total amount invested is $1,001.00. Assume that Asset A has a 50% gain and Asset B has a 15% gain. The analysis in this post would say that this portfolio returned 50% + 15% = 65%. Calculating an arithmetic average results in an "average" return of 32.50%. Respectfully, both of these are misleading due to the lopsided portfolio allocations of the two assets in the portfolio.

The 50% return on Asset A earns the investor $0.50. The 15% return on Asset B earns the investor $150.00. Together, the portfolio earned the investor $150.50. A return of $150.50 on $1,001 invested is 15.03%. It is true that the investor did make 50% on one asset and 15% on another asset, but since only 0.10% of the portfolio was invested in Asset A, which earned the 50%, the overall return is much closer to the 15% return on Asset B because 99.90% of the portfolio was invested in Asset B. This pulls the portfolio's performance much closer to the performance of Asset B than Asset A.

I pulled the data from this post yesterday (12/18/21) and used Google Finance similar to the author of the post. There are a handful of firms who no longer have prices as of Dec. 18 2021 due to no longer being public (e.g., mergers, going private bankruptcies, etc.). Removing these firms results in a "Cramer Return" of 746% using the original methodology. However, each stock is a fraction of the overall portfolio. The total amount invested (i.e., the basis) of the 2021 stock picks through April of 2021 is $102,904.55. At 12/31/2021 the total fair market value of these stocks is $103,343.33.

Does investing $102,904.55 around the first quarter of the year and having $103,904.55 near year end sound like a 746% return? You're probably answering "no" to this question.

If we calculate the return based on the FMV as of 12/31/2021 and the total amount invested throughout the first quarter, and April of 2021, the return is 0.43%. The investor allocated around $100K in capital and earned just over $400. Once multiple assets are being considered during a time period, to back into how many dollars the investor actually made, I believe it is necessary to consider the relative "weight" of each asset in the overall portfolio. 

Doing this actually allows one to calculate the 0.43% return- but one must consider the percentage of each stock to the overall portfolio in the following manner: SUM[(percentage of individual stock to total amount invested in all stocks in the year) x (return on individual stock)]. This calculation results in the same 0.43% return that was previously calculated using the total amount invested through the first month of Q2 in 2021 and the total fair value as of 12/18/21.

The counterfactual portfolio math and a recreation of the original analysis may be found here:

Some closing thoughts:

My guess is anyone reading this knows that the average annual stock market return is around 10% over the last 100 or so years (+/- 2%). A 555% annual return is around 55.5 times higher than the historical average. If the average height of males in the US is around 5 foot 8, saying you know a US male who is 55.5 times taller than the average is saying you know someone over 314 feet tall. The 555% annual return in the stock market is implausible on its face. Further, if my memory serves me correctly, some very esteemed investors have annual performance (CAGRs) over decades of 30% - 80%. Is it reasonable to assume that Cramer is that much better than these investors?

Lastly, consider the performance on a portfolio as the number of stocks increases. Consider the extreme case where the investor owns every stock in the market. One could reasonably expect this portfolio to approximate the return on the overall market, and we are now back to that approximately 10% return (+/- 2%). Of course, there would be variation based on position sizing, but I hope you can see the point. After the exclusions I mentioned (i.e., firms without Google Finance data as of 12/18/21), there are 618 stock picks. Some of these stocks were recommended more than once, but to beat the market annually by 555% in a long-only strategy it is implausible to suggest that loading up on that many stocks would cause one's performance to be so far off from the annualized 10% return.

In my opinion, for performance like that to even be possible one would have to have a very concentrated portfolio with very few positions. As the number of stocks in the portfolio grows, I think it is reasonable to suggest that this portfolio will tend to perform closer to the historical market benchmark.

Others have commented on front running, prices used in the analyses, etc. My main point is that I believe that the 555% needs to be seen through the lens of an annual portfolio and not the summation of individual stock performance where each stock is essentially treated as its own 100% portfolio allocation and then summed.

References:

Statistics and Finance: An Introduction by Ruppert. See pg. 138.
Investment Theory & Risk Management by Peterson. See chapters 5 and 6.


