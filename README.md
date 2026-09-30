# unmetered VPS: What “Unlimited Traffic” Really Buys You, and How LisaHost’s Current Plans Compare

An **unmetered VPS** sounds straightforward until you compare the actual network limits. A provider can remove the monthly traffic counter while still giving you a 1 Mbps, 20 Mbps, 100 Mbps, or 500 Mbps network port. Those are very different servers in practice.

That distinction matters for exactly the workloads that usually trigger an unmetered VPS search: backups, file mirrors, media delivery, VPN relays, download services, software repositories, game servers, and other workloads where traffic volume matters more than raw CPU.

LisaHost is particularly interesting here because its current catalog contains several products explicitly labeled **“unlimited traffic”** or **“unmetered”**, ranging from very low-cost 1 Mbps CN2 GIA plans to 500 Mbps unmetered VDS/VPS options. It also sells ordinary metered VPS plans, so there is a useful price-versus-traffic trade-off to examine rather than simply assuming “unmetered” is automatically the better deal.

## What does unmetered VPS actually mean?

In hosting, “unmetered” generally describes **how traffic is billed or counted**, not an infinite amount of network capacity.

That is the first thing to keep straight.

A VPS with a 100 Mbps port can theoretically move about 32.4 TB in a 30-day month if it transmitted continuously at full line rate. A 1 Mbps port, under the same unrealistic always-maxed-out assumption, is only about 324 GB. A 500 Mbps port is around 162 TB.

Those figures are not traffic allowances. They are simply the mathematical ceiling implied by the port speed. Real utilization is affected by routing, congestion, packet sizes, remote-server speed, storage performance, TCP behavior, and the provider's network policies.

That is why two products can both say “unlimited traffic” while being dramatically different for heavy transfers.

Third-party 2026 hosting comparisons make the same distinction: unmetered traffic removes or changes the transfer accounting model, but the actual throughput ceiling remains determined by the network configuration and any fair-use rules.

There is also a useful practical lesson from recent VPS discussions: people searching specifically for “1 Gbps unmetered” tend to care far more about the **port speed** than the word unlimited itself. In one 2026 Reddit discussion, users explicitly focused on finding at least 1 Gbps unmetered connectivity while keeping CPU and RAM requirements modest. Another discussion highlighted the common mismatch between an advertised port speed and the real-world capacity available to one VPS. These are individual community reports, not controlled benchmarks, but they illustrate why reading the bandwidth column is essential.

## What LisaHost currently offers for unmetered traffic

LisaHost's current public catalog is not presented as one neat, traditional “VPS pricing” grid. Instead, the company separates products into network and location-specific product families.

For someone searching for an unmetered VPS, that catalog structure actually matters. There are several distinct options:

* U.S. CN2 GIA plans with extremely low fixed port speeds from 1 Mbps to 20 Mbps.
* U.S. 4837 unlimited-traffic plans at 200 Mbps and 500 Mbps.
* U.S. 9929 residential-IP unlimited plans at 20 Mbps and 50 Mbps.
* New York and Chicago residential-IP unlimited plans at 200 Mbps and 500 Mbps.
* Taiwan, Japan, Hong Kong, and Germany VDS/VPS products explicitly marked as unlimited traffic.

That gives you a much wider range than simply “cheap unlimited VPS.”

### All currently verified unmetered VPS/VDS plans

The table below covers the **currently visible unmetered/unlimited-traffic plans I could verify in LisaHost's public product catalog that directly match the search intent**. Prices are shown exactly as the current pages display them, in Chinese yuan (RMB), and the listed billing period is the currently displayed purchase cycle. Product pages generally label these prices as special or limited-time pricing.

| Product | Core configuration | Bandwidth / traffic | Price | Billing | Purchase |
| --- | --- | ---: | ---: | --- | --- |
| U.S. CN2 GIA Unlimited 1 Mbps | 1 vCPU, 1 GB RAM, 10 GB SSD, 1 IPv4 | 1 Mbps / unlimited traffic | ¥30 | Monthly | [ Check the current LisaHost plans](https://bit.ly/LIsahost) |
| U.S. CN2 GIA Unlimited 2 Mbps | 1 vCPU, 1 GB RAM, 20 GB SSD, 1 IPv4 | 2 Mbps / unlimited traffic | ¥65 | Monthly | [ View the available unmetered plans](https://bit.ly/LIsahost) |
| U.S. CN2 GIA Unlimited 5 Mbps | 2 vCPU, 2 GB RAM, 40 GB SSD, 1 IPv4 | 5 Mbps / unlimited traffic | ¥299 | Monthly | [ Check the 5 Mbps unlimited option](https://bit.ly/LIsahost) |
| U.S. CN2 GIA Unlimited 10 Mbps | 4 vCPU, 4 GB RAM, 60 GB SSD, 1 IPv4 | 10 Mbps / unlimited traffic | ¥799 | Monthly | [ Check the 10 Mbps unlimited option](https://bit.ly/LIsahost) |
| U.S. CN2 GIA Unlimited 20 Mbps | 8 vCPU, 8 GB RAM, 100 GB SSD, 1 IPv4 | 20 Mbps / unlimited traffic | ¥1,999 | Monthly | [ Check the 20 Mbps unlimited option](https://bit.ly/LIsahost) |
| U.S. 4837 Unlimited Lite | 2 vCPU, 2 GB RAM, 20 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥398 | Monthly | [ View the U.S. 4837 unlimited plans](https://bit.ly/LIsahost) |
| U.S. 4837 Unlimited Pro | 8 vCPU, 8 GB RAM, 80 GB NVMe, 1 IPv4 | 500 Mbps / unlimited traffic | ¥998 | Monthly | [ Check the 4837 Pro plan](https://bit.ly/LIsahost) |
| U.S. 9929 Residential Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 20 Mbps / unlimited traffic | ¥498 | Monthly | [ Check the U.S. 9929 unlimited plans](https://bit.ly/LIsahost) |
| U.S. 9929 Residential Unlimited Pro | 4 vCPU, 4 GB RAM, 80 GB NVMe, 1 IPv4 | 50 Mbps / unlimited traffic | ¥1,288 | Monthly | [ Check the 9929 Pro plan](https://bit.ly/LIsahost) |
| New York Residential Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥198 | Monthly | [ Check the New York unlimited Lite](https://bit.ly/LIsahost) |
| New York Residential Unlimited Pro | 8 vCPU, 8 GB RAM, 120 GB NVMe, 1 IPv4 | 500 Mbps / unlimited traffic | ¥498 | Monthly | [ Check the New York unlimited Pro](https://bit.ly/LIsahost) |
| Chicago Residential Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥198 | Monthly | [ Check the Chicago unlimited Lite](https://bit.ly/LIsahost) |
| Chicago Residential Unlimited Pro | 8 vCPU, 8 GB RAM, 120 GB NVMe, 1 IPv4 | 500 Mbps / unlimited traffic | ¥498 | Monthly | [ Check the Chicago unlimited Pro](https://bit.ly/LIsahost) |
| Hong Kong HGC Residential Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 50 Mbps / unlimited traffic | ¥899 | Monthly | [ Check the Hong Kong HGC unlimited plan](https://bit.ly/LIsahost) |
| Hong Kong HGC Residential Unlimited Pro | 4 vCPU, 4 GB RAM, 80 GB NVMe, 1 IPv4 | 100 Mbps / unlimited traffic | ¥1,899 | Monthly | [ Check the HGC Pro plan](https://bit.ly/LIsahost) |
| Taiwan Native-IP VDS 100 Mbps Unlimited | 1 vCPU, 1 GB RAM, 20 GB NVMe, 1 IPv4 | 100 Mbps / unlimited traffic | ¥299 | Monthly | [ Check the Taiwan 100 Mbps VDS](https://bit.ly/LIsahost) |
| Taiwan Native-IP VDS 200 Mbps Unlimited | 2 vCPU, 2 GB RAM, 20 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥599 | Monthly | [ Check the Taiwan 200 Mbps VDS](https://bit.ly/LIsahost) |
| Taiwan Native-IP VDS 500 Mbps Unlimited | 4 vCPU, 4 GB RAM, 40 GB NVMe, 1 IPv4 | 500 Mbps / unlimited traffic | ¥1,599 | Monthly | [ Check the Taiwan 500 Mbps VDS](https://bit.ly/LIsahost) |
| Japan ISP Residential VDS Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥1,099 | Monthly | [ Check the Japan ISP unmetered Lite](https://bit.ly/LIsahost) |
| Japan ISP Residential VDS Unlimited Pro | 4 vCPU, 4 GB RAM, 80 GB NVMe, 1 IPv4 | 500 Mbps / unlimited traffic | ¥1,899 | Monthly | [ Check the Japan ISP unmetered Pro](https://bit.ly/LIsahost) |
| Japan IIJ Residential VDS Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 100 Mbps / unlimited traffic | ¥1,099 | Monthly | [ Check the Japan IIJ unlimited Lite](https://bit.ly/LIsahost) |
| Japan IIJ Residential VDS Unlimited Pro | 4 vCPU, 4 GB RAM, 80 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥1,899 | Monthly | [ Check the Japan IIJ unlimited Pro](https://bit.ly/LIsahost) |
| Germany Dual-ISP Residential VDS Unlimited Lite | 2 vCPU, 2 GB RAM, 40 GB NVMe, 1 IPv4 | 100 Mbps / unlimited traffic | ¥1,099 | Monthly | [ Check the Germany unmetered Lite](https://bit.ly/LIsahost) |
| Germany Dual-ISP Residential VDS Unlimited Pro | 4 vCPU, 4 GB RAM, 80 GB NVMe, 1 IPv4 | 200 Mbps / unlimited traffic | ¥1,899 | Monthly | [ Check the Germany unmetered Pro](https://bit.ly/LIsahost) |

LisaHost's product pages confirm the U.S. 4837, New York, Chicago, Taiwan, Japan, Germany, and other unmetered variants above.

One important affiliate-link detail: LisaHost's product pages expose actual product IDs in their order links, and the site has historically used an `aff.php?aff=...&pid=...` structure for affiliate deep links. However, the supplied `aff.php?aff=1572` currently redirects to the LisaHost homepage, and I could not independently verify that constructing new `pid` combinations with affiliate ID 1234 preserves tracking. The safer approach is therefore to use the supplied affiliate URL rather than manufacture potentially broken or misleading deeplinks.

## The surprisingly important difference between the $30-style plan and the $198-style plan

The cheapest LisaHost unmetered option I found is the U.S. CN2 GIA 1 Mbps plan at ¥30/month.

On paper, “unlimited traffic” looks fantastic next to the price. In practice, 1 Mbps is the catch.

At a constantly saturated 1 Mbps, you are looking at roughly 324 GB of theoretical transfer over a 30-day month. That can be perfectly adequate for:

* a light VPN or relay endpoint;
* occasional remote administration;
* low-volume backups;
* a small service where bandwidth bursts are uncommon.

It is not remotely equivalent to a 200 Mbps or 500 Mbps unmetered port.

The 2 Mbps and 5 Mbps versions follow the same logic. LisaHost is effectively letting you buy a fixed network pipe and remove the traffic meter. That can be useful, but it is a very different product from a high-bandwidth unmetered server.

The 10 Mbps and 20 Mbps CN2 GIA variants illustrate the opposite end of the same family: substantially more compute and more throughput, but at ¥799 and ¥1,999 per month respectively.

So the CN2 GIA family makes sense when **routing quality toward specific destinations** matters more than maximizing raw traffic volume.

## The 4837 plans are much closer to what people normally mean by “high-bandwidth unmetered VPS”

LisaHost's U.S. 4837 family has two explicitly unlimited variants:

**Unlimited Lite:** 2 vCPU, 2 GB RAM, 20 GB NVMe, 200 Mbps, unlimited monthly traffic, ¥398/month.

**Unlimited Pro:** 8 vCPU, 8 GB RAM, 80 GB NVMe, 500 Mbps, unlimited monthly traffic, ¥998/month.

The gap is mostly about compute and port speed rather than simply “more unlimited.”

That's useful when choosing a box for sustained transfers. A 500 Mbps port theoretically represents about 2.5 times the line-rate capacity of 200 Mbps. You are paying a lot more, but you are also buying a materially different network ceiling.

There is an interesting comparison inside the same 4837 family: the regular metered versions currently show ¥68/month for 3 TB at 300 Mbps, ¥100/month for 8 TB at 500 Mbps, and ¥699/month for 20 TB at 1 Gbps. The unlimited Lite jumps to ¥398/month, while the unlimited Pro is ¥998/month.

That gives you a useful decision rule.

If your normal usage is comfortably below the included traffic allowance, the cheaper metered plan can make more sense. The reason to pay for the unmetered version is not “unlimited is inherently better”; it is that your transfer volume is high enough that a defined quota becomes the constraint you actually care about.

## New York is the standout on the current LisaHost pricing pages

The New York residential-IP family is particularly easy to notice because the unlimited variants are currently listed at:

* ¥198/month for 2 vCPU, 2 GB RAM, 40 GB NVMe, 200 Mbps and unlimited traffic.
* ¥498/month for 8 vCPU, 8 GB RAM, 120 GB NVMe, 500 Mbps and unlimited traffic.

That is a much more conventional high-bandwidth proposition than the 1–20 Mbps CN2 GIA family.

At 200 Mbps, the theoretical line-rate ceiling is about 64.8 TB over a 30-day month. Again, that is not a promised monthly transfer amount. It is simply what the port could move under continuous full utilization.

The Chicago family mirrors this almost exactly: ¥198 for the 200 Mbps unlimited Lite and ¥498 for the 500 Mbps unlimited Pro, with the same CPU, RAM, disk, and IPv4 specifications.

For people who specifically want a U.S. endpoint with a relatively wide pipe, these two product families are easier to understand than the lower-speed unmetered options.

## But “500 Mbps unlimited” still does not mean a dedicated 500 Mbps Internet path

This is the biggest caveat I would put in bold before buying any unmetered VPS.

**A listed 500 Mbps port is a throughput limit, not a promise that you will continuously receive 500 Mbps to every destination on the Internet.**

The same issue appears across the wider unmetered VPS market. Current comparison sites distinguish between “unmetered,” the advertised port, shared uplinks, fair-use policies, and effective throughput. Community discussions also repeatedly focus on the difference between an advertised link speed and the capacity actually available to an individual VPS.

LisaHost itself describes different networks using different routing approaches. Its product catalog spans CN2 GIA, 4837, 9929, BGP, residential-IP products, and multiple geographic locations. The result is that **bandwidth and route quality are separate purchasing decisions**.

For a U.S.-based media mirror, for example, 200 Mbps to a nearby audience could be more practical than a nominally “premium” low-speed route with only 10 Mbps capacity.

For a China-facing workload where route quality is the limiting factor, the trade-off can look completely different.

## What about LisaHost's 9929 unlimited plans?

The 9929 family is more specialized.

The current unlimited options are:

* **Lite:** 2 vCPU, 2 GB RAM, 40 GB NVMe, 20 Mbps, unlimited traffic, ¥498/month.
* **Pro:** 4 vCPU, 4 GB RAM, 80 GB NVMe, 50 Mbps, unlimited traffic, ¥1,288/month.

Those port speeds are considerably narrower than the 200 Mbps and 500 Mbps U.S. residential options.

So you should not look at the name “9929” and assume it is automatically a better unmetered choice for bulk transfer. The network route may be the reason you're considering it in the first place, but the actual bandwidth ceiling is much lower.

That makes these plans more relevant to workloads where **location, IP characteristics, or routing behavior** are central, rather than simply pushing the largest possible amount of data.

LisaHost describes the 9929 family as an international premium-network product with U.S. residential-IP characteristics. It also notes that some supplied IP ranges may not respond to ping, which the provider says is expected and does not necessarily prevent normal use.

## Taiwan, Japan, Germany and Hong Kong: these are specialized unmetered VDS products

LisaHost's non-U.S. unlimited plans are generally more expensive.

The Taiwan native-IP VDS family is listed at ¥299/month for 100 Mbps, ¥599 for 200 Mbps, and ¥1,599 for 500 Mbps, all with unlimited traffic. The 100 Mbps plan has 1 vCPU, 1 GB RAM, 20 GB NVMe and 1 IPv4; the 200 Mbps plan has 2 vCPU and 2 GB RAM; the 500 Mbps version has 4 vCPU, 4 GB RAM and 40 GB NVMe.

LisaHost explicitly flags these VDS plans as special products with refunds handled as website balance rather than normal payment-method refunds. That is a purchasing restriction worth noticing before ordering.

Japan has two current unmetered VDS families I could verify. The ISP residential line offers 200 Mbps and 500 Mbps unlimited versions at ¥1,099 and ¥1,899. The IIJ family offers 100 Mbps and 200 Mbps unlimited versions at the same prices.

Germany similarly has 100 Mbps and 200 Mbps unlimited residential VDS options at ¥1,099 and ¥1,899.

Hong Kong HGC's current family shows an unlimited Lite at ¥899/month with 50 Mbps and an unlimited Pro at ¥1,899/month with 100 Mbps.

These are not interchangeable with the U.S. plans. The network location is part of the product.

## Refunds and limitations deserve almost as much attention as traffic

LisaHost's homepage currently advertises **48-hour dissatisfaction refunds** for its mainstream offerings. Many of the U.S. residential and other standard VPS product pages repeat that policy.

However, the fine print is not uniform across the catalog.

Some special VDS pages state that refunds are limited to website balance. The Taiwan unlimited VDS family is one explicit example. The Japanese and German residential VDS listings also mark those products as special products with website-balance-only refunds.

That means the headline “48-hour refund” should not be treated as a universal promise across every SKU.

The same applies to trial products. LisaHost's low-cost CN2 GIA trial is a one-day trial and is explicitly shown as non-refundable.

The provider also publishes usage restrictions. Its product pages prohibit activities such as spam, phishing, attacks, malware distribution, and other abusive usage. One current residential-IP page says service may be terminated without refund after prohibited activity or an IP complaint.

That is especially relevant for an unmetered VPS because removing a traffic meter does not mean the network becomes a general-purpose dumping ground for unlimited-volume traffic.

## What do people say about LisaHost?

The independent review picture is much thinner than the marketing footprint.

Trustpilot currently shows **one review** for LisaHost, with a displayed TrustScore of 3.2. The single review was posted in January 2026 and was negative. One review is nowhere near enough to characterize overall customer satisfaction, but it does mean the Trustpilot sample is currently too small to use as strong evidence of broad sentiment.

There are also several 2026 third-party reviews and technical write-ups in the Chinese VPS community. Their conclusions vary, and some are clearly written in an affiliate-marketing style, so they should not be treated as independent benchmarks.

One technical forum review raised a specific concern about whether some products marketed as “residential” meet a conventional definition of a residential ISP connection. That is a third-party assessment, not a verified statement that applies to every LisaHost product.

Other recent review pages focus heavily on clean IPs, multi-region coverage, routing options, and cross-border use cases. Because many of those pages are promotional or affiliate-oriented, the safest way to use them is as prompts for questions rather than as proof of performance.

In other words, there is enough public material to understand what LisaHost sells, but not enough trustworthy independent benchmark evidence to claim that every unmetered plan delivers a particular real-world sustained speed.

## How LisaHost compares with other unmetered VPS approaches

The wider market helps put the pricing into context.

Current 2026 comparison articles commonly group providers such as OVHcloud, netcup, Hostwinds, BuyVM, GreenCloud, Contabo and others into the “unmetered” conversation, but they distinguish sharply between traffic policy, port speed, fair use and shared uplinks. One current comparison, for example, lists OVHcloud as unmetered while also emphasizing that lower-tier ports are much narrower than high-end tiers. Another describes netcup as having a shared 2.5 Gbps uplink, which is materially different from a dedicated port guarantee.

DreamHost takes a different marketing approach, emphasizing that it does not meter bandwidth and comparing that policy with providers that charge outbound-transfer fees. Its current VPS material still notes that fair use applies.

Meanwhile, recent Reddit discussions show that users shopping for unmetered VPS products increasingly ask a more useful question: **“What is the actual port speed and what happens under sustained load?”** That is a better technical question than simply asking whether a provider uses the word unlimited.

## Which LisaHost plan makes sense for different workloads?

For a light service where **traffic accounting is the main problem**, the 1 Mbps or 2 Mbps CN2 GIA products may be enough. Their low monthly prices make them easy to understand, but you need to accept that the network pipe is tiny.

For a **general high-bandwidth U.S. VPS**, the New York and Chicago 200 Mbps unlimited Lite products are much closer to the conventional meaning of a high-throughput unmetered server. At ¥198/month, they are also materially cheaper than many of LisaHost's more specialized unlimited VDS offerings.

For a more demanding workload that genuinely needs more CPU, RAM, storage and a wider pipe, the corresponding 500 Mbps Pro variants provide a much larger ceiling.

For **China-facing networking**, the decision becomes more route-specific. The CN2 GIA, 4837 and 9929 products are not simply different sizes of the same VPS; they are different network products with different positioning. LisaHost itself separates those families in its catalog.

For **region-specific IP or VDS requirements**, the Taiwan, Japan, Hong Kong and Germany offerings are much more specialized. They make sense when the location and IP characteristics are part of the reason you need the server at all.

## A simple way to calculate whether “unmetered” is worth paying for

Take your realistic monthly transfer volume and compare it with the metered alternative.

Suppose a normal plan gives you several terabytes per month and your workload usually stays under that number. Paying several times more for an unlimited plan buys you little.

But suppose your service regularly moves 15–30 TB per month. Then the traffic cap becomes a real operational constraint, and unmetered pricing becomes much easier to justify.

Then look at the port.

If the plan is 20 Mbps, ask how long your largest transfers can take.

If it is 200 Mbps, ask whether that is enough for your expected concurrent clients.

If it is 500 Mbps, ask whether the additional CPU, RAM and storage are actually useful to your application or whether you're paying for hardware you will leave idle.

That exercise usually reveals the right answer faster than comparing “unlimited” labels.

## Bottom line

The important thing about an **unmetered VPS** is not the word *unmetered*. It is the combination of **traffic policy + port speed + location + routing + resource allocation + acceptable-use rules**.

LisaHost currently has an unusually broad spread of unmetered products, from ¥30/month 1 Mbps CN2 GIA service to 500 Mbps U.S. residential VPS and multi-region VDS products. The biggest practical lesson is that these are not equivalent offerings simply because their traffic column says “unlimited.”

Before buying, check three numbers together:

**Monthly price. Port speed. Actual traffic requirement.**

Then check the less glamorous details: refund method, usage restrictions, IPv4 availability, and whether the product is a normal VPS or one of the special VDS offerings.

For LisaHost specifically, I would treat the current prices as **live promotional pricing rather than permanent list prices**, because many product pages label them as limited-time offers. I also did not find a first-party current coupon code that I could verify strongly enough to publish as a guaranteed discount.

[👉 Check LisaHost's current unmetered VPS and VDS availability](https://bit.ly/LIsahost)
