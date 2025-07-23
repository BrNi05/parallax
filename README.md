# Parallax Technical Analysis Package

A 2+1 component technical analysis tool collection for traders.<br />
It consists of Parallax Main (PX) and Parallax Extension (PX-E) open-source scripts, and the TradingView built-in Volume indicator as a basic extension.<br />
Written in PineScript, therefore can only be used on TradingView. Just copy and paste the codes into two separate empty script, and add the Volume indicator from the built-in library.<br />

## Parallax Main Functions

- Logarithmic Regression Band with built-in curve projection (for Bitcoin only)
- Bull Market Support Band
- EMA 350X-based Fib. multiplier Bands
- Bollinger Bands
- Adaptive Fibonacci Retracement (Lookback-based)
- Bottom Band (market bottom detector)
- PI Cycle Top Indicator with MAs
- Gaussian Channel
- Golden/Death Cross Markers with fine tunable sensitivity
- Multiple, important MAs (EMAs, SMAs)

## Parallax Extension Functions

- RSI (Relative Strength Index)
- SRSI (Stochastic RSI)
- ADX-DI-based BUY/SELL indicator
- MACD (Moving Average Convergence/Divergence)
- "Range Lerp" (lookback-based lerp oscillator, similar to Williams R%)
- Logarithmic 20W SMA distance marker
- EMA 21-99 Distance (normalized)
- EMA 21-99 Integral (normalized area between the two MAs)
- Bollinger Bands Low-High Distance

## Technical details

- The purpose of the collection is to let every TradingView user access quality and easy-to-use TA tools. TradingView limits the number of indicators that can be applied to one chart. This is a solution for that problem.
- The main module is - of course - overlay-styled, while the extension is not.
- The main script is not converted to be compatible with the latest version of PineScript due to plotting issues. As for now, it runs on v5.
- The extension script runs on PineScript v6.
- TradingView also limits compute time and maximum plot number for each script. Both PX and PX-E have adequate headroom for further development.
- Functions that are specific to certain instruments and timeframes are automatically blocked on others.
- Inputs (like lookback, sensitivity, etc) are clamped both mathematically and logically.

## Shout-outs

As this is a collection, some code is not mine, but has been modified by me to achieve the desired results. <br />
Credits for the TradingView users for the original codes:

- Log Regression Band: @memotyka9009 and @Quantadelic (Log Growth Curves)
- Gaussian Channel: @DonovanWall and @e2e4mfck
- ADX-DI: @BeikabuOyaji
- MACD: @ChrisMoody
- BTC Hash Ribbons: @capriole_charles
