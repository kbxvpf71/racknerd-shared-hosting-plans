# shared hosting providers: what the sticker prices hide, and how to pick a plan that actually fits your site

Most people searching for shared hosting providers want three answers up front: what it costs per year, what happens if they want out, and whether a cheap plan can actually run a real website. This guide covers all three, using RackNerd's shared hosting as the working example — a budget host whose annual promo price works out to roughly $0.87/month, and whose refund policy needs to be understood *before* you pay.

The short version: RackNerd's shared hosting runs on cPanel with LiteSpeed servers, daily off-site backups, free SSL, and free migration, starting at **$5.59/month** on standard plans or **$10.49/year** on annual promo plans. The one thing to know before anything else: there's no standard money-back guarantee, so the monthly plan is your safety net if you're unsure.

> **Quick pick:** One personal blog or small WordPress site → the **30 GB annual plan at $10.49/year** (≈ $0.87/month). Hosting more than a couple of sites → the **85 GB plan at $24.99/year**. Not ready to commit → the **30 GB monthly plan at $5.59/month**, cancellable anytime. 👉 [See RackNerd's shared hosting plans and current pricing](https://my.racknerd.com/aff.php?aff=11397&rp=/store/shared-hosting)

## RackNerd shared hosting plans: the full price list

RackNerd sells its shared hosting in two tracks. The standard monthly plans use SSD storage and can be cancelled at any time. The annual promo plans use NVMe storage, cost less per month, and require paying a year upfront. Here's the complete lineup:

| Plan | Storage / Bandwidth | Domains | Price | Billing | Order |
| --- | --- | --- | --- | --- | --- |
| Shared – 30 GB | 30 GB SSD / 2 TB | Unlimited | $5.59/mo | Monthly | [ Order the 30 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/shared-hosting) |
| Shared – 100 GB | 100 GB SSD / 3 TB | Unlimited | $9.59/mo | Monthly | [ Order the 100 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/shared-hosting) |
| Shared – 200 GB | 200 GB SSD / 5 TB | Unlimited | $15.59/mo | Monthly | [ Order the 200 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&rp=/store/shared-hosting) |
| Promo 30 GB | 30 GB NVMe / 3 TB | 2 | $10.49/yr | Annual | [ Get the 30 GB plan at $10.49/year](https://my.racknerd.com/aff.php?aff=11397&pid=933) |
| Promo 85 GB | 85 GB NVMe / 10 TB | 10 | $24.99/yr | Annual | [ Get the 85 GB plan at $24.99/year](https://my.racknerd.com/aff.php?aff=11397&pid=934) |
| Promo 200 GB | 200 GB NVMe / 30 TB | Unlimited | $59.00/yr | Annual | [ Get the 200 GB plan at $59.00/year](https://my.racknerd.com/aff.php?aff=11397&pid=935) |

All six plans ship with the same core feature set — cPanel, free SSL, daily backups, free migration — so the practical differences are storage, bandwidth, and how many domains you can host.

The domain counts on the promo plans deserve a note, because the listings don't all count the same way. RackNerd's own promo listings state 2 domains on the 30 GB plan and 10 on the 85 GB plan; one detailed third-party review counts the primary domain separately, arriving at 3 and 11. Either way, the conclusion holds: the cheapest annual plan is tight on domains, and the 85 GB promo plan is the sensible cutoff if you're hosting several sites on annual pricing. Storage rarely becomes the constraint instead — a full year of WordPress content typically stays under 3 GB.

The promo plans also sit on newer hardware than the standard line: Ryzen 7950X processors with Gen4 NVMe storage running CloudLinux OS 9, per RackNerd's own listings. The standard monthly plans don't advertise the same platform specs, so if peak I/O performance matters to you, that's another point in the annual plans' favor.

## What's actually included in every plan

The feature list is identical across all tiers, which is where RackNerd differs from hosts that gate basics behind higher plans:

- **cPanel** — the industry-standard panel, so migrating in from any other cPanel host feels familiar.
- **LiteSpeed Web Server with LSCache** — this is the piece that genuinely matters for WordPress. LiteSpeed's cache speeds up WordPress far beyond what a standard Apache stack manages at this price.
- **Daily backups via JetBackup** — stored fully off-site and re-replicated across multiple disaster recovery datacenters. RackNerd's own FAQ confirms this applies to *all* shared hosting servers, and you can view and restore backups yourself.
- **Free SSL** via Let's Encrypt on every domain.
- **Softaculous** one-click installer for WordPress and 400+ other scripts, plus the SiteJet AI site builder on the promo plans.
- **CloudLinux and KernelCare** — CloudLinux caps how much any single account can hog the server; KernelCare applies kernel security patches without reboots.
- **Free migration from your old host** — if your current provider is cPanel-based, submit a ticket with your old login details and RackNerd's staff move your files, databases, and email accounts for you. Note this covers moving *in* from another host; it doesn't mean plan-to-plan changes are a managed service.
- **Instant activation** — the official page states all shared hosting packages activate immediately after ordering; the company blog puts it at 5–15 minutes in practice.

Daily off-site backups and LiteSpeed on the cheapest tier is the combination most $2–3/month mainstream plans don't match — several well-known hosts reserve daily backups for pricier tiers or skip them entirely.

## The fine print most reviews skip

This is the section that changes purchase decisions.

**There is no standard refund guarantee.** RackNerd's terms state that "refunds are issued on a case-by-case basis since by default no refunds are provided once payment is received." No 30-day window, no automatic refund. Practically, that means the $10.49 annual plan is a real commitment. The workaround is simple: start on the monthly plan at $5.59, confirm the service works for you, then switch to annual once you're confident. You pay a few dollars more for the test month, and in exchange you're never locked into an unrefundable year.

👉 [Start on the monthly plan, upgrade after you're satisfied](https://my.racknerd.com/aff.php?aff=11397&rp=/store/shared-hosting)

**No published uptime SLA.** RackNerd doesn't offer a formal uptime guarantee with compensation. Independent monitoring by Hostalog recorded a 30-day average of **99.993%** — roughly 30 seconds of downtime per month — which clears the 99.9% marketing number most hosts advertise. User reports on Trustpilot and Reddit generally land at or above 99.9% uptime, though a few Reddit users have mentioned occasional packet loss and CPU steal on the cheapest VPS nodes; shared hosting feedback has been steadier. One Reddit poster complained about a cPanel account performing poorly after 11 months, without much detail, so long-term consistency isn't a closed case.

**Renewals are typically honest — with one asterisk.** Hostalog's review notes that renewal prices usually match the initial promotional rate, avoiding the sticker shock that's near-universal in this industry. The caveat: RackNerd hasn't publicly committed to keeping promo pricing at renewal forever. If you want certainty, checkout offers multi-year prepay options (two or three years) to lock the rate.

**Skip the coupon hunt for shared hosting.** RackNerd doesn't issue promo codes for shared hosting — the deals are built directly into the special plan pages, and there's nothing to stack on top. Discount codes do circulate for the VPS lines (several reviews list 30% recurring codes for KVM and Windows VPS), but one review flags some of those same codes as third-party bait, so treat any code you find elsewhere as unverified until it shows the discount at checkout. For shared hosting, the prices above are already the deal.

**Small extras worth knowing:** EU customers may owe VAT, overdue invoices carry a 10% late fee, an assisted service transfer costs $8, moving between datacenters later requires a support ticket and involves temporary downtime (there's no self-serve migration tool), and not every datacenter location supports IPv6. Choosing Singapore on the annual promo plans adds **$8/year**.

## Shared hosting providers compared: RackNerd vs. the mainstream names

The comparison articles dominating this keyword typically recommend hosts starting at $2.69–$2.99/month with free domains, free SSL, weekly backups, and 30-day money-back guarantees. Stacked against that, the honest comparison looks like this:

| Factor | Typical mainstream entry plan | RackNerd |
| --- | --- | --- |
| Headline price | $2.69–$2.99/mo | $5.59/mo, or ≈$0.87/mo annual |
| Real billing terms | Promo rate usually requires 2–4 year prepay | Annual promo needs 1 year; monthly has no commitment |
| Renewal behavior | Promo expires, rate resets upward | Usually matches promo rate, not guaranteed |
| Backups | Weekly on entry tiers | Daily, off-site, on all plans |
| Money-back guarantee | 30 days, standard | None — case-by-case |
| Free domain | Yes, year one | No |
| Web server | Typically Apache/nginx | LiteSpeed + LSCache |

If a guaranteed refund window and a free first-year domain matter more to you than the bottom line, the mainstream picks serve that better. If minimizing actual hosting spend matters more — and you're comfortable testing on monthly first — the annual promo price undercuts everything on renewal-adjusted cost, with a stronger base feature list.

## Which plan fits which situation

- **One blog or small business site:** the 30 GB promo plan at $10.49/year. 2–3 domains covers one site with room to spare, and 3 TB of monthly bandwidth covers small sites many times over.
- **Several sites, five to ten:** the 85 GB promo plan at $24.99/year — 10 hosted domains, 10 TB bandwidth, NVMe storage.
- **Client work or many small sites:** the 200 GB promo plan at $59.00/year with unlimited domains, or RackNerd's reseller line (from $34.88/year on promo, or $14.59/month standard with 20 cPanel accounts) if you need separate accounts to hand to clients.
- **"I just want to try it":** the 30 GB monthly plan at $5.59/month. Cancel whenever.

Worth knowing what shared hosting *won't* cover: high-traffic WooCommerce stores, forums, or anything CPU-hungry will eventually hit shared resource limits on any provider. RackNerd's own VPS line (KVM, from $21.99/year on ongoing specials) is the usual next step when that happens — and the company notes shared hosting accounts can be upgraded from the client area as needed.

## How to order, step by step

The process per RackNerd's official guide:

1. Pick a plan and click Order Now.
2. Enter your domain — register a new one, transfer, or point an existing domain's nameservers here. Known quirk: if the domain is already hosted in your account, the form can throw an error; switching the extension or using a different domain clears it.
3. Choose billing cycle and datacenter location. Promo plans require annual prepay; monthly plans offer monthly, annual, two-year, and three-year terms.
4. Pay via PayPal, credit card, cryptocurrency, or bank transfer.
5. Your account activates within 5–15 minutes; manage everything from the client area.

Choose the datacenter based on where your visitors are: Los Angeles is the safe default for most audiences and the best value, Singapore adds $8/year on promo plans but makes sense if your traffic is Asia-centric. Locations include multiple US sites plus Germany, France, and a newer New York City node on the promo platform.

If you're migrating in, open a support ticket early with your old host's credentials. RackNerd's support runs 24/7 with a stated 10-minute average ticket response — reviews report replies anywhere from a few minutes to a few hours, so the official number is the best case, not the floor.

## FAQ

**Is the $10.49 price really for a whole year?**
Yes. It's the annual prepay price for the 30 GB promo plan, which works out to about $0.87/month. The $5.59/month figure belongs to the separate monthly plan — they're different products, not two billing options for one plan.

**Does RackNerd offer refunds?**
No standard guarantee. Refunds are case-by-case by default once payment is received. Monthly billing is the practical hedge.

**Will my renewal price match what I paid?**
Third-party reviews report renewals typically matching the promotional rate, but RackNerd hasn't publicly committed to that for promo plans. Multi-year prepay at checkout locks the rate.

**Is it good for WordPress?**
Yes — Softaculous handles the install, and LiteSpeed with LSCache gives WordPress a measurable performance edge over same-price Apache-based hosts.

## Final picks, and two things to check before paying

One site on a budget: 30 GB promo at $10.49/year — or monthly first if you want an exit. Several sites: 85 GB at $24.99/year. Heavy storage or lots of sites: 200 GB at $59.00/year. If you value a 30-day refund guarantee and a free bundled domain over raw price, the mainstream hosts in this keyword's results fit that better than RackNerd does.

Before checking out, confirm your datacenter matches your audience's geography, and decide whether the annual prepay is money you're fine not seeing back — because that's the deal you're making. 👉 [Order RackNerd shared hosting from $10.49/year](https://bit.ly/RacKnerd)
