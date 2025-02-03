# Parallax Technical Analysis Package

A 2+1 component technical analysis tool collection.<br />
It consits of Parallax Main (PX) and Parallax Extension (PX-E) open-source scripts, and the TradingView built-in Volume indicator as a basic extension.<br />
Written in PineScript, and can be used on TradingView. Just copy and paste the code, and add the Volume indicator from the built-in library.<br />

## Parallax Main Functions

- Logarithmic Regression Band with built-in curve projection (for Bitcoin only)
- Bull Market Support Band
- EMA 350X-based Fib. multiplier Bands
- Bollinger Bands
- Adaptive Fibonacci Retracement (Lookback-based)
- Bottom Band (market bottom detector)
- PI Cycle Top Indicator with MAs
- Gaussing Channel
- Golden/Death Cross Markers with fine tunable sensitivity
- Multiple, important MAs (EMAs, SMAs)

## Parallax Extension Functions

- RSI (Relative Strength Index)
- SRSI (Stochastic RSI)
- ADX-DI-based BUY/SELL indicator
- MACD (Moving Average Convergence/Divergence)
- "Range Lerp" (lookback-based lerp oscillator, similar to Williams R%)
- Log. 20W SMA dist. marker
- EMA 21-99 Distance (normalized)
- EMA 21-99 Integral (normalized area between the two MAs)
- Bollinger Bands Low-High Distance
- BTC Hash Ribbons

## Technical details

- The purpose of the collection is to let every TradingView user to access quality and sufficient TA. TradingView limits the number of indicators that can be applied to one chart. This is a solution.
- The main module is - of course - overlay styled, while the extension is not.
- The main script is not converted to be compatible with the latest version of PineScript due to plotting issues, it runs on v5.
- The extension script runs on PineScript v6.
- Functions that are specific to certain instruments and timeframes are automatically blocked on others.

## Shout-out

As this is a collection, some code is not mine but has been modified by me to achieve the desired results. <br />
Credits for the TradingView users for the original code:
- Log Regression Band: @memotyka9009 and @Quantadelic
- Gaussian Channel: @DonovanWall, @e2e4mfck
- ADX-DI: @BeikabuOyaji
- MACD: @ChrisMoody
- BTC Hash Ribbons: @capriole_charles
