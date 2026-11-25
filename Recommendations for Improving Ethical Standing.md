## **6\. Recommendations for Improving Ethical Standing**

| Recommendation | Issue addressed | Grounded in (theory and clause) | Trade-off or cost | Who acts |
| ----- | ----- | ----- | ----- | ----- |
| Make an allergen and halal field mandatory on every listing. Label every Mystery Bag “may contain common allergens”. Let users with a declared allergy hide Mystery Bags. | Allergens | Deontology (informed consent); utilitarianism (harm reduction). Cl. 1.03, 1.04 | Extra listing effort for vendors. A blanket label is less precise than a real list. | ReMeal developers and product team; vendors complete the field  |
| Change the out-of-stock default from “Replace with alternative” to “Refund me”, and ask before any substitution. | Refunds | Deontology (consent to what is received). Cl. 1.03, 1.06  | More refunds and fewer completed sales.  | ReMeal developers and management  |
| Show the refund rules and a Terms link before payment. Replace consent by a line of text with an explicit tick-box. Untick “Add store to Favourites” by default. | Refunds | Deontology (consent, honesty). Cl. 1.06, 1.02  | A slightly longer checkout; some drop in conversions.  | ReMeal developers and management  |
| Refund automatically when an item is sold out or the shop is closed at pickup. Check that each item’s time window falls within store hours before showing it. | Refunds, food quality  | Utilitarianism (loss falls on the party best placed to prevent it). Cl. 1.02, 3.14  | Vendors absorb more losses; validation logic must be built. Precedent: Too Good To Go lets consumers cancel before or during pick-up (Too Good To Go, n.d.-a, cl. 3.8). | ReMeal management and developers; vendors |
| Require a current food premises licence (or equivalent) and a food-handler certificate at vendor sign-up. Move the storage guidance (“consume within 2 hours”) onto the main listing. | Food quality  | Utilitarianism (small cost per vendor against lower illness risk). Cl. 1.03, 6.07  | Slower sign-up; may put off very small sellers.  | ReMeal management; vendors  |
| Encrypt all traffic in transit (TLS), then correct the Play data-safety label.  | Data protection  | Deontology. Cl. 3.12  | Low engineering cost; certificate upkeep.  | ReMeal developers  |
| Cut the Privacy Policy back to what ordering needs: Remove selfies, income, marital status, IMEI, and sharing with credit bureaus, background-check providers and advertisers. Get explicit consent before using allergy information. Add in-app account deletion. | Data protection  | Deontology (people are not used merely as a means); utilitarianism (small benefit of the data against breach harm). Cl. 3.12, 3.13  | Loses some advertising income and fraud-check capability.  | ReMeal management, legal team and developers  |

Priority 1: Allergen disclosure and no silent substitution

None of the 38 Mystery Bag listings showed allergen or halal information (E18–E24), and checkout swaps an unavailable item for an alternative by default (E15, E26–E31). Deontology says a buyer cannot consent to food they cannot see, and a swapped item is one they never agreed to. Utilitarianism values Mystery Bags for the food rescued and the meals made cheaper, but only while expected harm stays small, and an allergic reaction is severe and cannot be undone. The two theories differ on the remedy: deontology would keep users with a declared allergy away from Mystery Bags altogether, while utilitarianism would keep them with a “may contain” label. We recommend both, labelling every bag and letting users hide bags, which keeps most of the benefit and respects the duty. Too Good To Go already requires stores to give allergen information on request and to make sure buyers have all the contents information at pick-up (Too Good To Go, n.d.-a, cl. 4.4), so ReMeal would only be moving a familiar disclosure to before payment.

Priority 2: A fair checkout and refund process

Users see no refund policy or Terms link before paying (E16), accept the Terms through a line of text (E03), and are shown conflicting collection windows (E15, E25). Too Good To Go’s marketplace terms let consumers cancel “anytime before or during Pick-up” (cl. 3.8), which shows a surplus-food platform can offer a fairer deal. Under utilitarianism, losses should fall on whoever can best prevent them, and that is ReMeal and its vendors, who control the listing data, not the buyer.

Priority 3: Data practices

These are cheap to fix and now carry legal weight. Malaysian law has required breach notification and a data protection officer since June 2025, and fines of up to RM1,000,000 have applied since April 2025 (DFDL, n.d.). Apple also requires apps with account creation to offer deletion inside the app (Apple, n.d.), and we found no such option (E07).

Vendor vetting, the fee model and impact claims are business decisions outside developers’ control, so we address them to management and expect developers to raise concerns under clauses 1.02 and 1.04. Our cost estimates are untested with ReMeal’s vendors, and ReMeal may already have fixes we could not see.

