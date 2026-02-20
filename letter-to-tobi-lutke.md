# Open Letter to Tobi Lütke Regarding Reduced Metafield Limits

**To:** Tobi Lütke, CEO of Shopify
**From:** A Concerned Shopify Developer
**Date:** February 20, 2026
**Re:** The Catastrophic Reduction of Metafield Value Sizes

---

Dear Tobi,

I am writing to express my deep concern and frustration regarding Shopify's recent announcement to reduce metafield value sizes from approximately 2,000,000 characters (~1.9 MB) down to a mere 16 KB, effective with API version 2026-04.

**This is not a reduction. This is a demolition.**

Let me put this into perspective: you have reduced the limit by over 99%. That's not a policy adjustment—that's pulling the rug out from under every developer who built applications trusting your platform's documented capabilities.

## The Impact

1. **Existing Applications Will Break**: Merchants and developers who have been responsibly using metafields for complex data storage—product configurations, translation data, custom integrations—will suddenly find their metafields locked into a read-only state. Their businesses depend on this functionality.

2. **No Adequate Migration Path**: Making oversized metafields "read-only until updated" is not a solution. For many use cases, there is no way to compress years of accumulated data into 16 KB. What exactly are we supposed to do—delete our merchants' data?

3. **Trust Erosion**: Developers build on Shopify because we trust the platform to be stable. When you change limits by two orders of magnitude, you're telling us that any capability we rely on today could be arbitrarily restricted tomorrow.

4. **The Timing**: Announcing this change and then enforcing it leaves insufficient time for developers to architect entirely new solutions, migrate data, and test thoroughly. Complex applications cannot be refactored overnight.

## Questions That Deserve Answers

- Why was such a drastic reduction chosen instead of a more moderate adjustment?
- What data storage alternatives does Shopify recommend for apps that legitimately need more than 16 KB per metafield?
- Will there be a grace period or grandfather clause for existing metafields?
- Was there any consultation with the developer community before making this decision?

## A Request

I respectfully request that Shopify:

1. **Reconsider the limit** — Even 256 KB would be dramatically more workable than 16 KB while still achieving whatever resource goals you have in mind.
2. **Provide a longer transition period** — Give developers adequate time to migrate.
3. **Offer alternatives** — If metafields are no longer meant for substantial data storage, provide a sanctioned alternative that is.
4. **Communicate transparently** — Explain the reasoning behind this decision so developers can understand and plan accordingly.

We chose to build on Shopify. We've invested countless hours learning your APIs, building apps, and serving merchants. We deserve better than to have the foundation shifted beneath us without warning or recourse.

I hope this letter finds you well and prompts genuine reflection on the impact this change will have on the ecosystem that makes Shopify valuable.

Respectfully but firmly,

A Developer Who Expected Better

---

*P.S. — 65,000 characters is approximately 63.5 KB. Under the new limits, even a modest JSON configuration would exceed the cap. This isn't edge-case complaining—this affects mainstream use cases.*
