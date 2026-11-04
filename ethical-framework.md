**4\. Ethical Framework Proposal**

**Issue 1: Exclusion of Mandatory Allergen Transparency**

SE Code Application:

- Clause 1.02 (Balance competing interests):   
  Shifting verification burdens onto vulnerable consumers to contact vendors through remarks which may be overlooked prioritizes corporate liability shielding over public health.

- Clause 1.03 (Approve software only if it is safe):   
  Omitting mandatory allergen disclosures for mystery bags approves software that facilitates high-risk transactions, failing to ensure consumer physical safety.

- Clause 1.04 (Disclose actual/potential dangers):   
  Hiding allergy disclaimers inside lengthy legal terms (Term 5.3) rather than displaying prominent reminders on ordering pages fails to properly disclose potential health hazards.

Under Deontology, a food platform accepting service fee holds an absolute moral duty to safeguard consumer health for charging vendors’ service fee. Contractual disclaimers do not erase this non-negotiable obligation.

A tension exists between clauses and practical platform boundaries: vendors may supply incomplete data, and auditing costs exceed low profit margins. As the Code is silent on handling third-party data liabilities, Deontology is essential to justify that system designers must still mandate basic vendor allergen tags and prominent UI warnings regardless of financial or legal constraints.

**Issue 2: Refund Policy**

SE Code Application:

- Clause 1.02 (Balance competing interests):  
  The refund flow protects revenue while buyers of unseen mystery bags have no remedy.  
- Clause 1.06 (Be fair and avoid deception in all statements):   
  Refunds can be refused at ReMeal’s “sole discretion”, and that rule is buried in terms users must accept but rarely used.

Deontology gives a universalizability test for rules. “Platforms may refuse refunds at will” cannot be willed as a universal law without destroying trust in online marketplace. Under Utilitarianism, disputes are few but each loss falls entirely on the buyer. Unfair refunds erode trust, leaving fewer users and less food rescued.

The SE code is silent as the decision lies outside the engineer’s control. The fund policy is set by management and legal teams. Engineers only build the flow, and the code covers engineers’ own work. Deontology and Utilitarianism are needed to judge the policy itself, not just how it is implemented.

**Issue 3: Quality of the food**  
SE Code Application:

- Clause 3.14 (Maintain data integrity):  
  Stale vendor photos for surplus food that changes daily are exactly outdated data stated in the code clause.  
- Clause 6.07 (Do not deceive others regarding the characteristics of software):  
  Listing photos may not match the food received, and Terms clause 9.3 disclaims their accuracy.

Deontology justifies that the issue concerns responsibility for a sale ReMeal takes part in. ReMeal takes payment as the vendor’s agent (Terms 1.1) yet disclaims the product. Taking the money essentially creates a duty. Under Utilitarianism, the app’s goal is reducing waste as a scale. Poor quality bags drive users away, so the waste goal fails.

The SE code is silent and the decision lies outside the engineers control. Food quality is decided in vendors’ kitchens. The Code says nothing about how responsibility is shared between a platform and its vendors. Deontology and Utilitarianism are needed to decide whether acting as the agent of a sale creates a moral duty beyond a legal disclaimer.

**Issue 4: Waste incentives**  
SE Code Application:

- Clause 1.04 (Disclose actual/potential dangers):   
  Mandates disclosing potential dangers to the environment. The platform lacks consumer-side consumption prompts, failing to mitigate the risk of encouraging impulse purchases that lead to food waste.  
- Clause 1.07 (Consider factors that diminish access to software):   
  Requires considering broad social impacts like resource allocation. Although intended to reduce food waste, ReMeal’s flat per-item listing fees without volume caps may indirectly incentivize vendors to overproduce food, relying on the platform as a safety net for surplus stock.

Under Utilitarianism, the system must minimize overall social harm. Unchecked overproduction and consumer food waste increase environmental pollution and waste production resources, reducing overall societal utility.

The SE Code is largely silent on indirect environmental consequences driven by user and vendor behaviour, as purchasing choices and kitchen production volumes lie outside an engineer’s direct control. Utilitarianism is necessary to evaluate the system’s net ecological impact and justify architectural solutions such as implementing smart inventory caps for vendors and dynamic ordering reminders for consumers to prevent systemic waste.

**Issue 5: Data protection**

SE Code Application:

- Clause 1.03 (Approve software only if it is safe):  
  Transport encryption is a basic security test the app appears to fail.  
- Clause 3.12 (Develop software and documents that respect privacy of those affected by software):  
  ReMeal’s Play Store declaration says data isn’t encrypted, so personal information and device IDs are exposed to interception.


Under Utilitarianism, the risk affects every user at once. Breach harm to all users far outweighs the low cost of enabling encryption.

The SE Code is minimal. This decision is within the engineer’s control. Encryption is a technical choice, so clauses 3.12 and 1.03 apply directly. If the declaration is simply wrong, clause 6.07 (Do not deceive others regarding the characteristics of software) applies instead. Utilitarianism is mainly to weigh severity. The Code already gives a clear answer here, which contrasts with issues 2 and 3\.  
