# Pine Scripts

A collection of TradingView Pine Script indicators for technical analysis and trading strategies.

[![Donate with PayPal](https://img.shields.io/badge/Donate%20with-PayPal-00457C?logo=paypal&logoColor=white)](https://paypal.me/garrykeneth)

## Indicators

### Spyfrat All-in-One v3 + ZF Bounce + Goku

A comprehensive trading indicator combining multiple strategies:

**Features:**
- **Price Bollinger Bands (50, 0.20)** - Main trend indicator with light gray shading
- **RSI (30)** - Primary momentum indicator with visual levels at 50, 70, and 80
- **RSI Bollinger Bands** - Secondary volatility measure on RSI
- **Weekly RSI** - Trend confirmation from the weekly timeframe

**Trading Strategies Included:**

1. **Bebemon Strategy** - Detects price interactions with Bollinger Bands combined with RSI confirmation
   - Watches for price/basis interactions
   - Requires RSI confirmation above 50
   - Includes BEBE? watch for upcoming setups

2. **ZeeFreaks Bounce Play** - Reversal strategy based on candlestick patterns
   - Requires 3 consecutive red bars
   - Detects hammer, inverse hammer, or doji candles
   - Filters for oversold RSI conditions
   - Optional volume confirmation
   - Includes 3-bar exit logic

3. **Parabolic Trading** - High momentum entry and exit system
   - Daily and weekly RSI alignment required
   - PHR (Parabolic High Region) and ePHR (Extended PHR) signals
   - Price and RSI-based entries

4. **Goku Precedence Pattern** - Breakout strategy after volatility compression
   - Detects tight price compression (ATR below average)
   - Triggers on breakout with strong RSI
   - Watch spacing filter to reduce clutter

**Display Options:**
- Show/hide Bebemon signals
- Show/hide Bull/Bear crossovers
- Show/hide Parabolic signals and watch levels
- Show/hide ZF Bounce signals
- Show/hide Goku pattern signals

**Alert Conditions:**
Full alert coverage for all trading signals including:
- All entry signals (Bebemon, Parabolic, ZF Bounce, Goku, Normal)
- Exit signals (Parabolic, Normal)
- High probability regions (PHR, ePHR)
- Trend confirmation (Bull/Bear)

## Settings

All inputs are configurable through the indicator settings:
- Bollinger Bands parameters (length, deviation)
- RSI parameters (length, levels)
- Strategy-specific settings (tolerance, lookback periods, requirements)
- Display toggles for signal filtering

## Usage

1. Add the indicator to a TradingView chart
2. Configure settings based on your preferred trading style
3. Enable desired strategies and signals
4. Set up alerts for trading signals

## Version History

- **v3 Full** - Latest version with ZF Bounce, Goku, Bebemon Watch, and Bollinger Band shading
