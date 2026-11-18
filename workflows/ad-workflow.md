# Ad workflow (example)

Everything below is an **example**. The business, offers and copy are made up to show the shape of the workflow. They are not real clients or results.

```
brief -> brand context -> static ad + short video script -> human approval gate -> scheduled post
```

## 1. Brief (example)

```yaml
# EXAMPLE ONLY. Not a real client.
brief:
  business: "Example Coffee Roasters"   # placeholder name
  town: "Eugene"
  goal: "Get people to call or book"
  offer: "Free tasting flight this month"   # placeholder offer, no price
  channels: ["social post", "short video"]
  must_include: "Call 541-632-9043 or book a Business X-Ray"
  must_not_include: ["prices", "invented testimonials", "unverified stats"]
```

## 2. Brand context

Collect the business's own look first: logo, colors, voice, real photos. Phoenix's paper-and-ink style is the fallback when the business has no system of its own.

| Token | Phoenix default |
|-------|-----------------|
| Paper | `#f4efe6` |
| Ink | `#12100e` |
| Ember (accent) | `#e36a2e` |
| Headline type | Newsreader serif |
| Mark | Circular monogram |

## 3. Drafts

**Static ad.** Paper background, ink headline in Newsreader, one ember rule or button, the monogram small in a corner, the call to action at the bottom. No price.

**Short video script (about 15 seconds, example):**

| Beat | On screen | Voice-over |
|------|-----------|------------|
| 0-3s | Real photo or clip of the business, paper-colored title card | "Local in Eugene?" |
| 3-10s | One offer line in ink on paper | "[Offer line from the brief]." |
| 10-15s | Monogram and phone number | "Call 541-632-9043 or book a Business X-Ray." |

## 4. Human approval gate

Nothing moves forward without a yes.

- [ ] Owner has read the copy and approved it
- [ ] Phoenix reviewer has checked facts, links and the call to action
- [ ] No price, no invented claim, no fake review
- [ ] Every link was tested and works
- [ ] Approved by (name) and date recorded

## 5. Scheduled post

Only after the gate: queue the post for the chosen time, keep the approved copy on file, and note the link so the result can be checked later.

```yaml
# EXAMPLE ONLY
schedule:
  status: "waiting for approval"   # becomes "approved" only after step 4
  post_at: "<date and time chosen with the owner>"
  approved_by: "<name>"
```

## Town variants (example headlines)

Same structure, local first line. The offer and business come from the brief. Headlines are examples.

| Town | Example opening line |
|------|----------------------|
| Eugene | "Eugene, here is a local favorite worth a visit." |
| Springfield | "Springfield neighbors, stop in this month." |
| Salem | "Salem, meet a business that answers the phone." |
| Portland | "Portland, small shop, real people." |
| Roseburg | "Roseburg, the one down the street is open." |

Every variant ends with: **Call 541-632-9043 or book a Business X-Ray.**

## CONCEPT: can-collection community benefit

> **CONCEPT ONLY.** This is not a launched service. It has no partners, no numbers and no dates.

**The idea.** A local business sponsors a can and bottle collection drive in its town. Phoenix promotes the drive as part of that business's ad campaign, so the ad is useful to neighbors and the business shows up as part of the community.

**How it would fit the workflow:**

1. The business decides it wants to sponsor a drive.
2. The brief gets a community line in place of a sales offer.
3. Phoenix drafts the static ad and short script for the drive.
4. The same human approval gate applies. Nothing goes out until the owner and a reviewer approve.
5. The post is scheduled, and the details of the drive are confirmed before they are published.

**Example ad outline (example copy, not a live campaign):**

- Headline: "Bring your cans. Help your town."
- Body: "[Business name] is hosting a collection drive in [town]. Details coming soon."
- Footer: "Call 541-632-9043 or book a Business X-Ray."

**Still to decide before it could exist:** how drives are run locally, where collected items go, and who the community partners would be. None of that is set.

---

Back to the [README](../README.md) | [phoenix-portfolio](https://github.com/williamboyd1221-bit/phoenix-portfolio)
