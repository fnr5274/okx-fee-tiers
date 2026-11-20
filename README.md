# OKX Trading Fees: 0.08% or 0.20%? What Spot, Futures and VIP9 Actually Cost (Full Tier Table)

Regular-tier spot trading on OKX costs **0.08% maker and 0.10% taker**. Perpetual futures cost **0.02% maker and 0.05% taker**. On a $1,000 spot trade that's $1.00 when you buy as a taker and $1.00 when you sell, so about **$2.00 for the round trip**.

Those are the global and EEA numbers. Open OKX's US fee page and the same Regular tier reads 0.20% maker and 0.35% taker, which makes the identical round trip cost roughly $7. Neither page is wrong, and neither is out of date. Your rate is set by which regional entity holds your account and whether you've opened a derivatives (X-Perps) account, two things the headline percentage never mentions.

Below is the full tier table, the four checks that explain why your number differs from someone else's, how the fee is actually calculated, what it takes to reach the next tier, and the costs that sit outside the fee schedule entirely.

> **Most retail traders stay on Regular tier.** On the global or EEA schedule, budget 0.08% maker and 0.10% taker on spot, and 0.02%/0.05% on perpetuals. On the US schedule the equivalent figures are 0.20% and 0.35%. Your own rate is displayed on the fee page inside your account.
>
> 👉 [Open an OKX account and confirm your tier before your first order](https://okx.com/join/CASH20)

## Every spot tier from Regular to VIP9

This table comes from OKX's help page for EEA users, last updated September 3, 2026, and is denominated in euros. It applies to accounts that have opened a derivatives (X-Perps) account.

| Tier | Assets (EUR) | 30-day volume (EUR) | Maker / Taker | Open account |
| --- | --- | --- | --- | --- |
| Regular | 0 – 100,000 | 0 – 1,000,000 | 0.0800% / 0.1000% | [ Open an account](https://okx.com/join/CASH20) |
| VIP1 | 100,001 – 200,000 | 1,000,001 – 5,000,000 | 0.0675% / 0.0800% | [ Open an account](https://okx.com/join/CASH20) |
| VIP2 | 200,001 – 2,000,000 | 5,000,001 – 10,000,000 | 0.0600% / 0.0700% | [ Open an account](https://okx.com/join/CASH20) |
| VIP3 | 2,000,001 – 5,000,000 | 10,000,001 – 20,000,000 | 0.0550% / 0.0650% | [ Open an account](https://okx.com/join/CASH20) |
| VIP4 | 5,000,001 – 20,000,000 | 20,000,001 – 100,000,000 | 0.0300% / 0.0450% | [ Open an account](https://okx.com/join/CASH20) |
| VIP5 | 20,000,001 – 50,000,000 | 100,000,001 – 200,000,000 | 0.0250% / 0.0350% | [ Open an account](https://okx.com/join/CASH20) |
| VIP6 | 50,000,001 – 100,000,000 | 200,000,001 – 500,000,000 | 0.0000% / 0.0300% | [ Open an account](https://okx.com/join/CASH20) |
| VIP7 | 100,000,001 – 250,000,000 | 500,000,001 – 1,000,000,000 | -0.0020% / 0.0250% | [ Open an account](https://okx.com/join/CASH20) |
| VIP8 | 250,000,001 – 500,000,000 | 1,000,000,001 – 5,000,000,000 | -0.0050% / 0.0200% | [ Open an account](https://okx.com/join/CASH20) |
| VIP9 | 500,000,001+ | 5,000,000,001+ | **-0.0075% / 0.0175%** | [ Open an account](https://okx.com/join/CASH20) |

Three things in that table are easy to miss. The maker fee goes negative at VIP7, which means OKX pays a rebate on orders that rest in the book rather than charging you. VIP9 pays **-0.0075% maker and 0.0175% taker**. And the asset and volume columns are alternatives, not requirements you stack.

If you have not opened a derivatives (X-Perps) account, a second table on the same page applies, and Regular there is **0.200% maker and 0.350% taker**. OKX's US fee page shows the same 0.20%/0.35% pair for a Regular user. Same brand, same day, three different headline numbers.

The 24-hour crypto withdrawal limit climbs with each tier: Regular $10,000,000, VIP1 $24,000,000, VIP2 $32,000,000, VIP3 $40,000,000, VIP4 $44,000,000, VIP5 $48,000,000, VIP6 $60,000,000, VIP7 $72,000,000, and $80,000,000 at VIP8 and VIP9. The US fee page lists slightly different figures for VIP4 through VIP7, so treat this column as indicative and check the fee page in your own account before planning a large withdrawal.

## Why your rate doesn't match the screenshot someone posted

When a trade fills at a rate you didn't expect, OKX's help page points at four things to compare against that specific order.

**Which entity your account sits under.** The same brand runs separate fee schedules by region. The global and EEA pages show 0.08%/0.10% at Regular. The US page shows 0.20%/0.35%. The UAE page shows 0.40% maker and 0.60% taker. OKX puts a disclaimer on its own fee page: fees may vary depending on your region. A YouTuber quoting 0.08% and a forum post quoting 0.20% can both be reading an official page.

**Whether a derivatives (X-Perps) account is open.** This is the part almost nobody writes about. OKX's help page states plainly that the maker and taker fee on a spot order are set by your fee tier plus whether you've opened a X-Perps account, and that the two tables on the page apply to different account setups. Opening that account is what moves a Regular-tier spot trader from 0.20%/0.35% to 0.08%/0.10%.

**Maker versus taker on that fill.** A limit order that rests in the book pays the maker fee. An order that fills immediately against the book pays the taker fee. OKX's own example: with the lowest BTC ask at 1,000 USDT, a buy order at 999 USDT doesn't match right away, sits in the book, and pays maker when someone fills it.

**Which product placed the order.** Buy and Sell and Convert quote a single price with a spread built in instead of charging a separate maker or taker fee. Their cost is not comparable with an order-book fee, which is OKX's own wording, not a knock on the feature.

## How the fee is actually calculated

For spot, the fee is the rate multiplied by the amount of crypto you bought when the order filled.

Take OKX's worked example. USDT is priced at 10 USD and trader A is on 0.04% maker and 0.1% taker. A buys 1 USDT at market, pays 0.1% × 1 = **0.001 USDT**, and receives 0.999 USDT. Reverse it: A sells 1 USDT at a limit price for 10 USD, is the maker, pays 0.04% × 10 = **0.004 USD**, and receives 9.996 USD.

For perpetual and delivery futures, the fee is the rate multiplied by position value, and leverage doesn't enter the calculation. One BTC of BTCUSDT perpetual at 20,000 USDT costs 10 USDT as a taker at 0.05%, or 4 USDT as a maker at 0.02%, whether you opened it at 1x or 20x. Delivery futures add a settlement fee of 0.01%, the same for every tier.

The number worth memorising is the round trip. Two taker fills on a $1,000 spot trade at Regular tier on the global schedule cost about **$2.00**. On the US schedule the same two fills cost about **$7.00**. On the UAE schedule, at 0.60% taker each way, it's about $12.00. Two maker fills cut each of those roughly in half, and at VIP7 and above the maker side flips to a rebate.

## What it takes to reach the next tier

Your tier comes from account assets **or** 30-day trading volume. Either route is enough on its own, and volume you traded on another exchange doesn't count toward either.

The volume side is recalculated daily at 16:00 UTC. OKX converts each trade to its BTC equivalent at the price at the time of the trade, then converts that to USD using the daily BTC/USD middle price, which it defines as (opening price + closing price) / 2.

The asset side uses the **higher** of two numbers: your 30-day average asset balance and your snapshot at 16:00 UTC that day. OKX's example is a 30-day average of 1,000 USD against a snapshot of 500 USD, which counts as 1,000 USD. Crypto and fiat both count toward the total.

Tiers update daily, and OKX says it applies the latest fee level between 20:00 and 22:00 UTC. Sub-accounts don't get their own tier: the main account's tier is calculated from the combined volume and daily asset snapshots of all main and sub-accounts, and a new sub-account inherits it from 16:00 UTC on the day it's created.

One practical consequence of the higher-of rule. A large deposit lifts your snapshot above your 30-day average, so the snapshot becomes the number that counts and your tier rises immediately. Withdraw it and the snapshot falls back below the average, and so does your tier. Treat a temporary deposit as a temporary rate, not a permanent upgrade.

Zero-fee pairs won't help you climb either. OKX excludes zero-fee trading pairs from the 30-day spot volume calculation, and market makers get no credit for them in tier assessment, so grinding a zero-fee pair leaves your tier exactly where it was.

## Costs that aren't on the fee schedule

The maker/taker table is one line item. These are the others, and two of them can outweigh it.

**Convert and Buy and Sell.** No separate trading fee, but the price you're quoted has a spread baked in and is set by OKX. For anything sizeable, compare the quote against the order book; a limit order on spot usually wins.

**Funding on perpetuals.** Paid between long and short traders at set intervals. It isn't an OKX fee, but on a position held for days it can easily exceed the 0.05% you paid to open.

**Forced liquidation.** Charged at your current taker rate, on top of the loss that triggered it.

**Spread trading.** Each leg is charged at 50% of the normal spot or perpetual rate for your tier.

**Withdrawals.** Every coin and network carries its own network fee, shown on screen before you confirm. Crypto deposits cost nothing on OKX's side.

👉 [Open an OKX account and check withdrawal fees per network before you move funds](https://okx.com/join/CASH20)

## Does an invite code make trading cheaper?

No, and OKX says so directly. A referral code doesn't replace the fee schedule or the tier rules, and signing up with one doesn't by itself put the account on a different rate. If the programme you joined pays a rebate, that rebate is handled under the programme's own terms rather than by changing the rate printed on the schedule.

That matters for how you read invite links, including the one on this page. The code changes what referral rewards you may be eligible for, not your maker and taker percentages. Those still come from your tier and your account setup. The specific reward terms, tasks and deadlines for an invite are shown on the referral page in your account after sign-up, and they differ by region and by campaign, so read that page rather than trusting a number in a blog post.

👉 [Create an OKX account and review the current referral terms in your account](https://okx.com/join/CASH20)

## Questions that come up before the first trade

**Is 0.08% or 0.10% the rate I pay on spot?** Both, depending on the fill. 0.08% is the maker rate at Regular tier on the global and EEA schedule, 0.10% is the taker rate. Market orders and immediately-filled limits pay the taker rate.

**Do futures fees depend on leverage?** No. The fee is charged on position value, so 1 BTC of BTCUSDT perpetual costs the same in fees at 3x and at 30x. Leverage changes your liquidation price and margin, not the fee.

**Does holding OKB reduce my fees?** The official fee page and the help page checked for this guide set tiers by assets or 30-day volume and describe a market-maker route separately. Neither lists a holding-based discount, so don't budget for one.

**Why did my fee look wrong on one order?** Check the fill in your order history against the tier you were on at that moment, whether the order was maker or taker, which product placed it, and whether your X-Perps account was open. The fee actually charged is recorded per fill.

## Which number to use for your own account

Occasional spot buyer, a few trades a month: stay on Regular tier and use your region's number, 0.08%/0.10% on the global and EEA schedules, 0.20%/0.35% on the US one. Paying taker on both sides of a $1,000 trade is a $2 to $7 cost, and chasing VIP tiers won't change it.

Active trader doing six or seven figures a month: calculate your 30-day volume before you assume you're near a threshold. The gap between Regular and VIP1 on spot is 0.0125 percentage points on the maker side, which is real money at volume but meaningless at $20,000 a month.

Perpetual trader: the 0.02%/0.05% futures fee is the smaller half of your cost. Add funding, and add the taker rate you'll pay if the position gets liquidated.

Anyone about to place a large order: open the fee page inside your account first. That page reflects the entity you signed up with, your current tier and your X-Perps status, and it's the only version of these numbers that applies to you.

👉 [Open an OKX account and start from your own fee page](https://okx.com/join/CASH20)
