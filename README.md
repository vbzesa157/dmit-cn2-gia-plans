# CN2 GIA hosting: what it costs, which DMIT plan to buy, and what happens when your IP gets blocked (all 21 Los Angeles plans compared)

DMIT's cheapest CN2 GIA plan in Los Angeles is **LAX.Pro.TINY at $9.99/month**: 1 vCPU, 2 GB RAM, 20 GB SSD, 1 TB of traffic on a 1 Gbps port. It is also the plan most likely to be sold out when you look. When it is, **LAX.Pro.Pocket at $14.90/month** is the substitute, and the extra $5 buys a 4 Gbps port and 40 GB of disk rather than more RAM.

Below are all 21 Los Angeles plans across DMIT's three network tiers, the one pricing quirk that decides most purchases (Pro and EB cost exactly the same at every tier, with different hardware), the renewal and refund rules, the IP-blocking policy, and a short factual comparison with two other CN2 GIA options.

> **Quick pick:** one site with mainland visitors → LAX.Pro.TINY ($9.99/mo). TINY sold out → LAX.Pro.Pocket ($14.90/mo). Audience mostly on China Unicom or China Mobile → the EB tier at the same price gets you more CPU and traffic.
> 👉 [Check DMIT's current LAX plan list and stock](https://www.dmit.io/aff.php?aff=9081)

## What CN2 GIA hosting actually buys you

CN2 GIA is China Telecom's premium backbone, AS4809. It sits above the ordinary 163 network (AS4134) and above CN2 GT, and the part that matters for a website is that **both directions of the route use the premium path**. Traffic does not fall back onto congested public transit during peak hours.

The practical numbers third-party testers report for China Telecom to Los Angeles: ordinary transit runs 300 ms and up at peak with packet loss that can pass 10%; CN2 GT holds up better but wobbles when the return path drops off the optimized route; CN2 GIA sits around 150–165 ms with loss close to zero. Long-term users of DMIT's LAX network report 140–180 ms during the 9 pm window. These are measurements from individual users, not a published SLA, so treat them as a realistic range rather than a guarantee.

If your visitors are mostly in mainland China, this is the one line item worth paying for. A $3 VPS with a 163 route will make a fast site feel broken at the exact hour your customers are browsing.

## All DMIT Los Angeles plans

Prices are the currently listed monthly rates in USD. DMIT's own checkout page is the final word on price and availability, and stock on the two cheapest Pro plans moves fast.

### LAX.Pro: China Telecom and Unicom outbound on CN2 GIA, China Mobile outbound on CMI, all three returning via CN2 GIA

| Plan | vCPU / RAM / SSD | Port and monthly traffic | Price (USD/mo) | Order |
| --- | --- | --- | --- | --- |
| Pro.TINY | 1 / 2 GB / 20 GB | 1 Gbps, 1 TB (4 Mbps after) | $9.99 | [View Pro.TINY](https://www.dmit.io/aff.php?aff=9081) |
| Pro.Pocket | 1 / 2 GB / 40 GB | 4 Gbps, 1.5 TB (4 Mbps after) | $14.90 | [View Pro.Pocket](https://www.dmit.io/aff.php?aff=9081) |
| Pro.STARTER | 2 / 2 GB / 80 GB | 10 Gbps, 3 TB (4 Mbps after) | $29.90 | [View Pro.STARTER](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MINI | 2 / 4 GB / 80 GB | 10 Gbps, 5 TB (8 Mbps after) | $58.80 | [View Pro.MINI](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MICROv3 | 4 / 4 GB / 160 GB | 10 Gbps, 7 TB (8 Mbps after) | $74.99 | [View Pro.MICROv3](https://www.dmit.io/aff.php?aff=9081) |
| Pro.MEDIUMv2 | 4 / 8 GB / 160 GB | 10 Gbps, 14 TB (10 Mbps after) | $168.88 | [View Pro.MEDIUMv2](https://www.dmit.io/aff.php?aff=9081) |
| Pro.Large | 8 / 16 GB / 320 GB | 10 Gbps, 25 TB (10 Mbps after) | $338.88 | [View Pro.Large](https://www.dmit.io/aff.php?aff=9081) |
| Pro.GIANT | 8 / 24 GB / 640 GB | 10 Gbps, 50 TB (10 Mbps after) | $620.00 | [View Pro.GIANT](https://www.dmit.io/aff.php?aff=9081) |

### LAX.EB: China Telecom on AS9929/AS58807 load-balanced, China Unicom on AS9929, China Mobile on AS58807 (CMIN2)

| Plan | vCPU / RAM / SSD | Port and monthly traffic | Price (USD/mo) | Order |
| --- | --- | --- | --- | --- |
| EB.TINY | 1 / 2 GB / 20 GB | 2 Gbps, 1.5 TB (4 Mbps after) | $9.99 | [View EB.TINY](https://www.dmit.io/aff.php?aff=9081) |
| EB.Pocket | 2 / 2 GB / 40 GB | 4 Gbps, 3 TB (4 Mbps after) | $14.90 | [View EB.Pocket](https://www.dmit.io/aff.php?aff=9081) |
| EB.STARTER | 2 / 2 GB / 80 GB | 10 Gbps, 5 TB (4 Mbps after) | $29.90 | [View EB.STARTER](https://www.dmit.io/aff.php?aff=9081) |
| EB.MINI | 4 / 4 GB / 80 GB | 10 Gbps, 10 TB (8 Mbps after) | $58.80 | [View EB.MINI](https://www.dmit.io/aff.php?aff=9081) |
| EB.MICRO | 4 / 4 GB / 160 GB | 10 Gbps, 14 TB (8 Mbps after) | $74.99 | [View EB.MICRO](https://www.dmit.io/aff.php?aff=9081) |
| EB.MEDIUM | 6 / 8 GB / 160 GB | 10 Gbps, 30 TB (10 Mbps after) | $168.88 | [View EB.MEDIUM](https://www.dmit.io/aff.php?aff=9081) |
| EB.Large | 8 / 16 GB / 320 GB | 10 Gbps, 50 TB (10 Mbps after) | $338.88 | [View EB.Large](https://www.dmit.io/aff.php?aff=9081) |
| EB.GIANT | 12 / 24 GB / 640 GB | 10 Gbps, 100 TB (10 Mbps after) | $620.00 | [View EB.GIANT](https://www.dmit.io/aff.php?aff=9081) |

### LAX.T1: international routing (Telia, Zayo, Cogent), no mainland China optimization

| Plan | vCPU / RAM / SSD | Port and monthly traffic | Price | Order |
| --- | --- | --- | --- | --- |
| T1.WEE | 1 / 1 GB / 20 GB | 4 Gbps, 1 TB (100 Mbps after) | $36.90/year | [View T1.WEE](https://www.dmit.io/aff.php?aff=9081) |
| T1.TINY | 1 / 1 GB / 20 GB | 4 Gbps, 2 TB (200 Mbps after) | $6.90/mo | [View T1.TINY](https://www.dmit.io/aff.php?aff=9081) |
| T1.STARTER | 1 / 2 GB / 40 GB | 10 Gbps, 4 TB (200 Mbps after) | $12.90/mo | [View T1.STARTER](https://www.dmit.io/aff.php?aff=9081) |
| T1.MINI | 2 / 2 GB / 60 GB | 10 Gbps, 8 TB (200 Mbps after) | $21.90/mo | [View T1.MINI](https://www.dmit.io/aff.php?aff=9081) |
| T1.MICRO | 4 / 4 GB / 80 GB | 10 Gbps, 16 TB (500 Mbps after) | $32.90/mo | [View T1.MICRO](https://www.dmit.io/aff.php?aff=9081) |

T1 exists so the product line has a cheap international option. It has no China route optimization, which makes it the wrong buy for the audience this article is about. It is fine for a site serving Europe and North America.

## Pro vs EB: identical prices, different hardware

This is the part most plan tables skip. Compare the two tiers row by row and the monthly price is the same at every single level: $9.99, $14.90, $29.90, $58.80, $74.99, $168.88, $338.88, $620. What changes is what you get for it.

- At $14.90, Pro.Pocket is 1 vCPU / 2 GB / 40 GB with 1.5 TB of traffic. EB.Pocket is 2 vCPU / 2 GB / 40 GB with 3 TB.
- At $58.80, Pro.MINI is 2 vCPU / 4 GB / 80 GB with 5 TB. EB.MINI is 4 vCPU / 4 GB / 80 GB with 10 TB.
- At $620, Pro.GIANT is 8 vCPU / 24 GB / 640 GB with 50 TB. EB.GIANT is 12 vCPU / 24 GB / 640 GB with 100 TB.

The extra money in the Pro tier is spent on the route, not on the server. So the decision is not a budget decision at all: it is a question of which carrier your visitors use.

China Telecom users see the widest gap. Pro returns over AS4809 CN2 GIA, EB returns over a mix of AS9929 and AS58807, and at peak hours the difference in stability is noticeable. China Unicom and China Mobile users see much less of a gap, and EB's CMIN2 path handles those two carriers well. If two thirds of your traffic is mobile, paying the same price for half the CPU and half the traffic allowance to get a Telecom-optimized return path is a poor trade.

👉 [Compare the current Pro and EB tiers side by side](https://www.dmit.io/aff.php?aff=9081)

## What the extra $5 on Pocket actually changes

TINY to Pocket is 1 vCPU / 2 GB in both cases. You are not buying more compute. You get 20 GB more SSD, the port goes from 1 Gbps to 4 Gbps, and the traffic allowance goes from 1 TB to 1.5 TB. For a small WordPress site the disk is the part that matters, and 20 GB fills up faster than people expect once you add a few plugin backups and image uploads.

One detail worth knowing before you pick a tier: **DMIT does not cut you off when you exceed the monthly traffic allowance.** Pro and EB plans drop to 4, 8 or 10 Mbps depending on the plan and keep serving. A text-heavy site that blows through 1 TB will feel slow for the rest of the month, but it will not disappear, and that is a meaningfully different outcome from a suspended account on a cheaper host.

Renewal pricing is the other thing to check on any VPS before you commit. DMIT lists the same price for renewal as for the initial order, with no first-year discount that jumps in year two, and promo codes are recurring rather than one-time. Annual billing is cheaper than twelve monthly payments where it is offered. For Pro.Pocket, the annual rate currently lists at about $159.98 against $14.90 × 12, which is roughly one month free.

## Where DMIT is weak

**Stock.** Pro.TINY and Pro.Pocket sell out regularly, and the inventory display is not always accurate in real time. A plan can show available and reject your order half an hour later. If you see the plan you want in stock and you have already decided, buy it then.

**Support response.** Tickets that are not urgent can take 24–72 hours. This is self-managed hosting: DMIT runs the hardware and the network, and you run everything above the operating system. If you need someone to install your stack for you, budget for that separately.

**Hardware generation.** The Los Angeles fleet currently runs on AMD EPYC 9004 processors; the newer 9005 platform is reportedly paused for now. That is a roadmap item rather than a performance problem for web hosting.

**Disk profile.** Sequential SSD reads run close to 1 GB/s, which is far beyond what a content site needs. Random 4K reads are the weaker number, so a database-heavy application will hit a ceiling that a static or WordPress site never reaches.

**Two locations not covered here.** DMIT also runs Hong Kong and Tokyo, both with their own plan lineups and pricing. This article stays on Los Angeles because that is where the CN2 GIA entry price is lowest.

## When your IP gets blocked

This is the failure mode that costs Chinese-facing site owners the most, and it is worth knowing the policy before it happens rather than after. On both Pro and EB plans, **a blocked IP qualifies for a free replacement once every 15 days**. Other replacement requests cost $5. A blocked IP is usually a routing-level event, not something you did to the server, so a policy that covers it without a new machine is a real operational saving.

👉 [See DMIT's current plans and IP replacement terms](https://www.dmit.io/aff.php?aff=9081)

## Refunds, if you want to test the route first

DMIT refunds in full within 3 days of purchase as long as you have used no more than 30 GB of traffic. Refunds to account balance carry no fee; refunds back to the original payment method may lose the payment gateway's cut. Within 30 days you can get a pro-rated refund based on remaining time.

For a route-sensitive purchase this matters. Three days is enough to run latency and packet loss tests from a few locations during an evening peak and decide whether the route behaves the way you need. Payments go through Alipay, WeChat Pay, PayPal and cards, so the checkout itself is not a hurdle for buyers in China.

## How it compares with other CN2 GIA hosting options

Two names come up repeatedly in this category. Both are legitimate points of comparison, and neither suits the same buyer as the other in every case.

| Provider and tier | Route | Listed entry price | What it changes for you |
| --- | --- | --- | --- |
| BandwagonHost CN2 GIA-E (LAX DC6) | AS4809 for Telecom, CMIN2 AS58807 for Mobile, AS10099 for Unicom | 20 GB plan: $49.99/quarter, $169.99/year, no monthly billing | Free migration across 10+ locations, 2.5–10 Gbps ports, KiwiVM panel with snapshots and rDNS. Entry cost is higher and there is no $9.99 monthly option. |
| BandwagonHost CN2 GIA Ultra (Hong Kong, Tokyo, Osaka, Singapore) | Pure CN2 GIA at Asian nodes | From $89.99/month | Lower latency to China, no free migration, priced for latency-sensitive workloads rather than web hosting. |
| LisaHost (CERA, Los Angeles) | China-optimized, CERA facility | Entry plans capped at 10–15 Mbps | 50 Gbps DDoS mitigation included by default, native US IP, one-day trial for a nominal fee. Bandwidth is the constraint on the cheap tiers. |

The 20 GB BandwagonHost plan at $169.99/year works out to roughly $14.17/month, close to Pro.Pocket's monthly rate, but you buy a year at a time and there is no monthly escape hatch. BandwagonHost's 80 GB tier (4 vCPU / 4 GB / 80 GB / 3 TB) lists at $56.99/month or $549.99/year, and the 160 GB tier (6 vCPU / 8 GB / 160 GB / 5 TB) at $86.99/month or $879.99/year. Both offer a 30-day pro-rated refund.

LisaHost's pitch is different: DDoS mitigation and streaming-unlock claims rather than port speed. If your site attracts attacks, that 50 Gbps of always-on filtering is worth more than a 10 Gbps port. If it does not, the 10–15 Mbps cap on entry plans will be the thing you notice.

## FAQ

**How different do Pro and EB feel in practice?**
On China Telecom, clearly different, especially between 8 and 11 pm. On China Unicom and China Mobile, close enough that most site owners would not notice without a side-by-side test. Match the tier to your analytics rather than to the spec sheet.

**Pro.TINY is sold out. What do I buy?**
Pro.Pocket at $14.90/month, which adds 20 GB of disk, a 4 Gbps port and 500 GB of traffic. The alternative is waiting for a restock, and restocks are not on a published schedule.

**Do I need a CDN on top of this?**
For text and a handful of images, no. CN2 GIA direct to China is fast enough that a CDN adds a layer without adding much. For image-heavy storefronts or video, put a CDN in front and use the VPS as the origin, which also makes your traffic allowance go much further.

**Can I log in with a password instead of an SSH key?**
Yes. Key-based login is the default and can be switched to password authentication in the control panel.

**Will it run WordPress?**
Yes, with no special configuration. Install a panel or a LNMP stack and you are running. A 1 vCPU / 2 GB plan leaves most of the RAM free for a small WordPress site.

## Before you order

Match the tier to your traffic first, then the plan size:

- **Mainland visitors, mostly China Telecom, one site** → LAX.Pro.TINY at $9.99/mo, or Pro.Pocket at $14.90/mo when TINY is gone.
- **Mostly China Unicom or China Mobile, or you want more headroom per dollar** → the EB tier at the same price, which gives you extra vCPU and roughly double the traffic.
- **Multiple sites on one box** → Pro.MINI or Pro.MICROv3, where 4 GB of RAM and 160 GB of disk comfortably hold five to ten lightweight sites.
- **Visitors outside China** → T1, starting at $36.90/year. Skip it for anything China-facing.

Two things to confirm on the order page: that the plan shows as in stock at the moment you pay, and which billing cycle you selected, since the annual rate is lower than twelve monthly payments and the refund window is measured from the purchase date either way.

👉 [Check current DMIT LAX.Pro stock and pricing](https://www.dmit.io/aff.php?aff=9081)
