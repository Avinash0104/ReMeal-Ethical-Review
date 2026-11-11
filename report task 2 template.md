# **ReMeal Ethical Review – Part 2 Report** 

COMP3041 Professional Ethics · Group I · Report due 10 Dec 2026 · 3,000–4,000 words

## **Title page**

**An Evidence-Based Ethical Review of ReMeal: Part 2 Report**

COMP3041 Professional Ethics · Group I · Module Convenor: Dr. Nabil El Ioini

| Name | Student ID |
| ----- | ----- |
| Tooba Nauman | 20712242 |
| Eunice Ying Yun Lee | 20613250 |
| Avinash Lakhwani | 20690297 |
| Tian Cheng Song | 20595032 |
| Yuze Jiang | 20593889 |

Word count (excluding title page, tables, figures, references and appendices)

| Section | Owner | Target words | Commit history  | Status |
| ----- | ----- | ----- | ----- | ----- |
| 1\. Introduction | \[tooba\] | 300 |  | started |
| 2\. Stakeholders | \[name\] | 600 |  | Not started |
| 3\. SE Code analysis | \[name, name\] | 1,100 |  | Not started |
| 4\. Ethical theories | \[name\] | 800 |  | Not started |
| 5\. Critical reflection | \[name\] | 400 |  | Not started |
| 6\. Recommendations | \[name\] | 400 |  | Not started |
| References and appendices | \[name\] | not counted |  | Not started |
| Final edit (one voice, word count) | \[name\] | not counted |  | Not started |

**Internal deadlines:**  

## **1\. Introduction**
ReMeal is a Malaysian food-tech platform, operated by ReMeal Sdn Bhd in Kuala Lumpur, that allows cafés, bakeries, hotels and supermarkets to sell their unsold surplus food at a discount. Through its mobile app, available on Google Play and the Apple App Store, consumers can buy individual items or “Mystery Bags” of unspecified contents, then collect them in store, dine in, or arrange delivery through partners such as Grab, pandago and Lalamove (ReMeal, n.d.). The platform serves two groups: price-conscious consumers looking for cheaper meals and food vendors seeking to recover revenue from food that would otherwise be thrown away.
ReMeal is significant because it applies a business model popularised internationally by apps such as Too Good To Go to the Malaysian market, where food waste is a recognised national concern. Its relevance extends beyond its users: in 2025, the Ministry of Domestic Trade and Cost of Living used ReMeal to record food saved at Ramadan bazaars under its MYSaveFood programme (Bernama, 2025). Because a surplus-food platform must balance affordability, sustainability, food safety and commercial interests, it raises ethical questions that go beyond whether the software works.
In Part 1, we identified four ethical issues through a hands-on investigation of the app and its Terms and Conditions, Privacy Policy and data-safety declaration: missing allergen information, a one-sided refund policy, limited accountability for food quality, and personal data that is not encrypted in transit. This report develops that review with new evidence, including a coded analysis of app store reviews, a price comparison, a privacy and tracker audit, and a re-examination of ReMeal’s published policies.
The report first identifies the stakeholders affected by the platform, then evaluates each issue against the ACM/IEEE Software Engineering Code of Ethics. It then applies utilitarianism and deontology to a dilemma the Code cannot resolve, reflects critically on the two approaches, and concludes with recommendations for improving ReMeal’s ethical standing.


## **2\. Stakeholders**

*Target: about 600 words, plus the table (which isn't counted). The brief asks for direct users, the operating company, its developers, business partners or workers, and indirect stakeholders who never use the app but are affected by it. For each: which feature or practice affects them, how, and what evidence shows it.*

*The top band wants indirect stakeholders included and every effect backed by evidence. Fill the table first, then write a short paragraph on the stakeholders most affected.*

| Stakeholder | Type | Feature or practice that affects them | How it affects them | Evidence |
| ----- | ----- | ----- | ----- | ----- |
| Buyers with allergies or halal needs | Direct | No allergen field; Mystery Bags | \[effect\] | \[E\#, Terms §5.3\] |
| General buyers | Direct | Refund policy; 20-minute hold | \[effect\] | \[E\#, Terms §5.7–5.8, §7.2\] |
| Vendors (cafes, bakeries, hotels) | Direct (partners) | Per-sale fee; Google Maps listing requirement | \[effect\] | \[pricing page, seller FAQ\] |
| ReMeal Sdn Bhd | Direct (operator) | Fee on every sale; liability disclaimers | \[effect\] | \[Terms §9.2–9.3\] |
| ReMeal's developers | Direct | Decisions on data encryption and listing fields | \[effect\] | \[Play data-safety label\] |
| Delivery riders (Grab, pandago, Lalamove) | Direct (workers) | Delivery of time-sensitive surplus food | \[effect\] | \[evidence\] |
| Full-price customers and competing shops | Indirect | Discounted bags replacing full-price sales | \[effect\] | \[Yang and Yu, 2025\] |
| Food banks and charities | Indirect | Surplus sold instead of donated | \[effect\] | \[evidence\] |
| Government (KPDN, MYSaveFood) | Indirect | Use of ReMeal's data on food saved | \[effect\] | \[Bernama, 2025\] |
| Environment and local community | Indirect | Possible overproduction or household waste | \[effect\] | \[Zhang et al.; review data\] |

\[Write the paragraph here: which stakeholders carry the most risk, which benefit, and where their interests conflict, for example ReMeal's revenue against buyers' safety.\]

## **3\. Analysis of Ethical Issues Using the SE Code**

*Target: about 1,100 words, roughly 250 per issue. The SE Code is the primary guide here. Cite clauses by number and show where ReMeal **meets, partly meets or breaks** each one. Include at least one place where ReMeal does well; a one-sided analysis scores lower. Check every clause against the [official Code](https://ethics.acm.org/code-of-ethics/software-engineering-code/).*

### **Clause verdicts at a glance**

| Issue | Clause | Verdict (meets / partly meets / breaks) | Key evidence |
| ----- | ----- | ----- | ----- |
| Allergens | 1.03 |  |  |
| Allergens | 1.04 |  |  |
| Refunds | 1.06 |  |  |
| Refunds | 1.02 |  |  |
| Food quality | 6.07 |  |  |
| Food quality | 3.14 |  |  |
| Data protection | 3.12 |  |  |
| Data protection | 1.03 |  |  |
| \[Something ReMeal does well, e.g. waste reduction, 1.02 or 1.07\] |  |  |  |

### **3.1 Allergens and ingredient information**

* **Claim:** \[Which clause, and the verdict.\]  
* **Evidence:** \[Your screenshot (E\#), Terms §5.3, and new Part 2 evidence such as review counts or the Mystery Bag purchase.\]  
* **Reasoning:** \[Why this evidence meets, partly meets or breaks the clause.\]  
* **Counterpoint:** \[ReMeal's best defence, e.g. the Terms tell users to contact vendors. Then explain why it only partly works.\]

### **3.2 Refunds and cancellation**

* **Claim:**  
* **Evidence:**  
* **Reasoning:**  
* **Counterpoint:**

### **3.3 Food quality and vendor accountability**

* **Claim:**  
* **Evidence:**  
* **Reasoning:**  
* **Counterpoint:**

### **3.4 Data protection**

* **Claim:**  
* **Evidence:** \[Play data-safety label, Exodus Privacy report, Privacy Policy §7, re-check for changes since Part 1.\]  
* **Reasoning:**  
* **Counterpoint:**

## **4\. Application of Ethical Theories**

*Target: about 800 words. The brief is specific here: first explain precisely why the SE Code cannot resolve the dilemma, then apply **at least two theories to the same dilemma** and compare their conclusions. Don't describe the theories in general terms; apply each one to our own evidence.*

### **4.1 The dilemma the SE Code cannot resolve**

*Suggested dilemma: the Mystery Bag model. The surprise element sells surplus that would otherwise be thrown away, serving the employer and the waste goal. But it makes allergen disclosure impossible, against clauses 1.03 and 1.04. Clause 1.02 says to balance these interests without saying how. The bag model is also a business decision outside the engineer's control. Agree on the dilemma as a team before writing.*

\[Write here: state the dilemma, the clauses in tension, and why the Code gives no answer.\]

### **4.2 Utilitarian analysis**

*Weigh the outcomes using our evidence: food rescued and money saved against allergic-reaction risk, food discarded at home (Zhang et al.; Yang and Yu, 2025), and what the coded reviews show.*

\[Write here\]

### **4.3 Deontological analysis**

*Apply duty and informed consent to the same dilemma: can a buyer consent to a bag they can't see? Apply the universalisability test to ReMeal's rule.*

\[Write here\]

### **4.4 Comparing the conclusions**

|  | Utilitarianism | Deontology |
| ----- | ----- | ----- |
| Verdict on Mystery Bags |  |  |
| What ReMeal must do |  |  |
| Where they agree |  |  |
| Where they disagree |  |  |

\[Write here: what the comparison reveals that neither theory shows alone. This is what the top grade band calls "adds insight".\]

*Optional: a short virtue-ethics view (what would a responsible food platform do?) if the word count allows.*

## **5\. Critical Reflection**

*Target: about 400 words. This is not a summary of findings; the rubric marks a reflection that "mostly repeats findings" as only Satisfactory. Answer these questions in connected prose:*

* *How did applying the SE Code and then the theories change how we understood ReMeal's issues? For example, did problems that looked like engineering failures turn out to be business-model decisions?*  
* *Where did the Code and the theories give conflicting answers, and which did we find more convincing, and why?*  
* *What does this say about how far a software engineer's responsibility reaches when management sets the policy?*  
* *What were the limits of our own investigation (sample size, what we couldn't test), and how might they affect our conclusions?*

\[Write here\]

## **6\. Recommendations for Improving Ethical Standing**

*Target: about 400 words, plus the table. Each recommendation must come from our analysis and be grounded in a theory, not generic advice. Say what it costs or trades off, since that makes it practical.*

| Recommendation | Issue addressed | Grounded in (theory and clause) | Trade-off or cost | Who acts |
| ----- | ----- | ----- | ----- | ----- |
| \[e.g. allergen and halal tags on listings, plus a filter\] | Allergens | \[Deontology; 1.03, 1.04\] | \[Extra effort for vendors\] | \[ReMeal developers\] |
| \[e.g. automatic refund if food is sold out or the shop is closed at pickup\] | Refunds |  |  |  |
| \[e.g. hygiene certificate required at vendor signup\] | Food quality |  |  |  |
| \[e.g. TLS encryption in transit\] | Data protection |  |  |  |
| \[e.g. report food eaten, not just bags sold\] | Waste |  |  |  |

\[Write here: explain the two or three most important recommendations in prose, why the theories support them, and which to prioritise.\]

## **References**

## **Appendices**

*Appendices don't count toward the word limit.*

### **Appendix A: Evidence log**

| ID | Date | App version and device | What it shows | Used in section |
| ----- | ----- | ----- | ----- | ----- |
| E1 |  |  |  |  |
| E2 |  |  |  |  |
| E3 |  |  |  |  |

### **Appendix B: App review coding**

*Method (how many reviews, from which stores, date range), the coding themes, a count per theme, and how two coders checked consistency on the same 20 reviews.*

| Theme | Google Play count | App Store count | Example (paraphrased, anonymised) |
| ----- | ----- | ----- | ----- |
| Price honesty |  |  |  |
| Food quality or safety |  |  |  |
| Refunds and support |  |  |  |
| App bugs |  |  |  |

### **Appendix C: Price check**

| Listing | Vendor | ReMeal "original" price (RM) | Actual menu price (RM) | Difference |
| ----- | ----- | ----- | ----- | ----- |
|  |  |  |  |  |

### **Appendix D: Changes to ReMeal's documents since Part 1**

*Re-check the Terms, Privacy Policy and Play data-safety label, and record any differences with dates.*

