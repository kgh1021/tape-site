# Tape Breadth: How It Works

I built this to answer one question I ask myself every day: where is the money actually going, and how broad is the move? After a lot of years in healthcare finance and a good stretch trading options, I got tired of eyeballing charts and guessing. I wanted an objective, repeatable read on rotation. This is that read, and it updates on its own every weekday after the close.

Here is the whole idea, plain as I can put it.

## Three questions about every stock

For all 500 names in the S&P, the board asks three things:

1. **RSI (velocity): how hard has it run?** This tells me if a name is overbought or oversold against itself.
2. **RS slope vs SPY (leadership): is it beating the market, and is that lead growing?** A stock can be overbought and still be losing ground to the S&P. RSI can't see that. This can.
3. **ADX (conviction): is there a real trend, or just chop?** A strong-looking signal in a choppy tape is noise. ADX tells me whether to trust the other two.

Velocity, leadership, conviction. Three different questions, and the interesting stuff shows up where they disagree.

## Rolling it up to sectors

Once every stock is scored, I add it up by sector: what share of each sector's names are actually leading. That gives the breadth gauge, and a one-line verdict on the whole tape:

- **NARROW:** one sector carrying everything. Fragile.
- **BROADENING:** a second sector confirming. Rotation trying to build.
- **BROAD:** several sectors participating. Healthier, broader tape.

Narrow, tech-only tapes are the ones that snap. Broad tapes are the ones you can lean into.

## The adaptive lens (the part I'm proudest of)

A fixed line, like "30% of a sector is leading," ignores context. Thirty percent means one thing in a hot market and another in a weak one. So the board also ranks each sector against its own past year. Every sector gets a tag:

- **Quality:** leading AND strong versus its own history.
- **Soft:** leading on the fixed line, but below its own norm. Looks like a leader, quietly rolling over.

That soft tag is the whole point. It catches the sectors that look strong today but are the first to fade tomorrow. The fixed number can't see that on its own.

## What it is, and what it isn't

This is a screener and a rotation map. It is not a sentiment gauge, it is not an execution system, and it is not financial advice. It runs on free data and it's meant for screening, not for sizing a trade blind. I built it with a lot of help from AI, it runs nightly on my own machine, and it publishes to a plain static page so anyone can look.

Happy to walk anyone through any piece of it. That's what it's for.

Kevin (DublinCapital)
