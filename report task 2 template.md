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
| 2\. Stakeholders | \[avinash\] | 600 |  | Not started |
| 3\. SE Code analysis | \[avinash, name\] | 1,100 |  | Not started |
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

ReMeal's stakeholders fall into two groups: those who use or run the platform directly, and those who never open the app but are still affected by it. Buyers with allergies or halal needs carry the most risk, because the app gives them no reliable way to know what they are eating. Mystery Bag listings consistently omit allergen and halal information (E18–E24), and even regular listings may not list ingredients (E12–E13). This risk is made worse by checkout, which automatically substitutes an alternative item when the chosen one is unavailable (E15, E26–E31), so even a buyer who selects carefully may receive something different. General buyers benefit from cheaper meals, but they carry the financial risk when an order goes wrong. The refund rules are never shown before payment (E16), and users accept the Terms without actively agreeing to them (E03). Conflicting pickup times at checkout (E15, E25) make missed collections more likely, and under s5.8 and s7.2 of the Terms, a buyer who misses pickup loses both the food and the money.
Vendors such as cafés, bakeries and hotels gain revenue from food they would otherwise throw away, but pay a fee on every sale, and joining requires only a Google Maps listing rather than a hygiene certificate (ReMeal, n.d.). This makes signing up easy, but honest vendors share a marketplace with unvetted ones, and the Terms leave responsibility for food quality with vendors (§9.2–9.3). ReMeal Sdn Bhd, as the operator, earns on every transaction while its disclaimers shift risk onto vendors and buyers. Its income grows with the amount of food sold, not the waste actually prevented, which is where its interests most clearly conflict with buyers' safety.
ReMeal's developers are direct stakeholders because many of the issues come from their design decisions: precise location is on by default (E06), location and purchase history are linked to identity (E02), there is no delete-account option (E07), and the Play Store data-safety label states that data is not encrypted in transit. Developers may also be blamed for failings decided by management, such as the refund rules, so their professional standing is at stake. Delivery riders from Grab, pandago and Lalamove carry time-sensitive surplus food (ReMeal, n.d.). Since EFSA (2018) identifies time and temperature as the main hazards for surplus food, delays could make riders part of a food safety failure they cannot control, although we have not yet gathered direct evidence of their experience.
Among indirect stakeholders, full-price customers and competing shops may lose out if discounted bags replace normal sales, as Yang and Yu (2025) found that surprise bags can lead retailers to overproduce and draw away customers who would have paid full price. Food banks and charities may receive less surplus if vendors prefer to sell it, though we have no direct evidence of this in Malaysia yet. The government is affected because the Ministry of Domestic Trade and Cost of Living used ReMeal to record food saved under MYSaveFood (Bernama, 2025), so any flaws in ReMeal's data feed into public figures. Finally, the environment and local community benefit only if the food is actually eaten. Zhang et al. (n.d.) found that people throw away surprise-bag food they dislike, yet the bag still counts as food saved.
Overall, buyers, especially those with allergies, carry the most risk, while ReMeal and vendors gain the most, and the main conflict lies between ReMeal's per-sale revenue and buyers' safety and fair treatment.


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

The SE code provides professional principles for SE engineers, but it does not offer solutions to every ethical dilemma faced by ReMeal. The Mystery Bag model is the dilemma that cannot be solved by SE code. The element of surprise box encourages customers to purchase surplus food that might be otherwise discarded, which serves the employer and the waste goal. However, this model makes the allergen and specific food information disclosure impossible. Among 38 Mystery Bag listings we examined, none of them showed allergen or halal information (E18-E24). This places Clause 1.03 and Clause 1.04 in tension with the objective of making surplus food accessible and reducing waste. Although Clause 1.02 requires engineers to balance competing interests, it does not specify how to balance environmental and economic benefits against the potential health risks faced by consumers with food allergies. The Mystery bag model is also a business decision made by ReMeal’s management outside the engineer’s control, limiting the engineer’s authority to change the underlying business model.

### **4.2 Utilitarian analysis**

*Weigh the outcomes using our evidence: food rescued and money saved against allergic-reaction risk, food discarded at home (Zhang et al.; Yang and Yu, 2025), and what the coded reviews show.*
A major branch of Consequentialism. The morality of an action is determined solely by its outcomes or consequences; max net utility
\[Write here\]

### **4.3 Deontological analysis**

*Apply duty and informed consent to the same dilemma: can a buyer consent to a bag they can't see? Apply the universalisability test to ReMeal's rule.*
The morality of an action is based on whether it follows a set of rules or duties
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

