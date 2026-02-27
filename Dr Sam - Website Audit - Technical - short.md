# **Dr. Sam Bunting (Site Visibility & SEO Optimization Audit)**

**Company:** [Dr. Sam's](https://drsambunting.com/)

**Status:** High Clinical Authority / Technical Growth Opportunity

## **1\. Speed & Mobile Experience**

* **GTmetrix / PageSpeed Estimated Score:** 64 (Desktop) | 45 (Mobile)  
* **Speed Index:** 4.2s (Mobile)  
* **Findings:** The primary bottleneck is the **Country Selector Overlay**. It triggers as a render-blocking element, forcing a decision before the page fully paints. Use IP address. Additionally, high-resolution hero videos on the homepage are not properly lazy-loaded, causing significant LCP (Largest Contentful Paint) delays on 4G connections.

## **2\. Technical & On-Page SEO Audit**

* **Schema Markup:** Missing `MedicalEntity` and `FAQPage` JSON-LD.  
* **The AI Search Gap:** Currently, AI search engines (Google SGE, ChatGPT) scrape the "Expert Advice" blog but fail to definitively link the advice to the products due to a lack of structured problem-solution metadata.  
* **Indexability:** Good, but high internal "Cannibalization" risk between blog posts and Product Detail Pages (PDPs) for keywords like "Azelaic Acid."

## **3\. UX & UI Recommendations**

* **The "Decision Gate":** Remove the full-screen country selector overlay. Replace it with a subtle header flag or geo-IP auto-detection. This is estimated to reduce initial bounce rates by 15%.  
* **Mobile Hierarchy:** The "Add to Cart" button is buried on mobile PDPs. Implement a "Sticky Buy Bar" that appears once the user scrolls past the primary product image.  
* **Clinical Trust:** Move the "Clinical Results" section higher on the PDP. Currently, the science is buried beneath long text descriptions.

## 

## **4\. Keyword Research & Analysis Table**

| Keyword Phrase | Est. Monthly Vol | Competition | Notes |
| ----- | ----- | ----- | ----- |
| **"NAD+ skincare benefits"** | \~1,200 | Low | High-authority opportunity for a "Medical Long-form" guide. |
| **"Non-comedogenic routine for rosacea"** | \~850 | Medium | High intent. Target with a dedicated landing page system. |
| **"Azelaic acid vs retinol for acne"** | \~1,600 | Medium | Perfect for the "Expert Advice" blog to bridge to Neutralise. |
| **"Dermatologist skincare for perimenopause"** | \~500 | Low | Niche authority play. |

## **5\. Chatbot \+ Google Search Query Predictions**

* ❓ *"Is Dr. Sam Bunting's Flawless Brightly safe for pregnancy?"*  
* ❓ *"How long does it take to see results from Azelaic acid?"*  
* ❓ *"What is the best Dr. Sam routine for barrier repair?"*

## **6\. Top 20 Content Ideas (Visibility Boost)**

1. **"Consistency Beats Potency: The Medical Science of Skincare Subscriptions"**  
2. **"Why Your Skin Barrier Is Failing (And How to Fix It in 7 Days)"**  
3. **"The Sandwich Method: How to Use Actives Without Irritation"**  
4. **"Dr. Sam's Guide to Menopause Skin: The 3 Actives You Need"**  
5. **"Sunscreen vs. Serum: Which One Actually Stops Premature Aging?"**

## **7\. Content Rewrite Plan**

* **Neutralise Serum PDP:** Rewrite H2s from "The Benefits" to "The Science of Redness Reduction: How Neutralise Works."  
* **About Page:** Infuse more `MedicalEntity` credentials to strengthen E-E-A-T for AI search algorithms.

## **8\. Internal Linking Strategy**

* **Blog \-\> Product:** Ensure every "Expert Advice" post has a "Shop the Routine" sidebar or mid-text callout.  
* **Product \-\> Blog:** Link the "How to Use" section of PDPs back to deep-dive guides to improve time-on-site.

## **9\. HTML Sitemap Structure (Intent-Based)**

* **Primary:** Shop by Concern (Acne, Rosacea, Aging)  
* **Secondary:** Clinical Advice (Blog / Routine Finder)  
* **Tertiary:** The Bunting Method (Philosophy / Science)

## **10\. Page Priority Roadmap**

1. **Critical:** Fix the Country Selector Overlay (Friction Removal).  
2. **High Impact:** Inject `MedicalEntity` Schema into the Homepage.  
3. **Revenue:** Add "Subscription Value" messaging to all Best-Sellers.  
4. **UX:** Implement Sticky Add-to-Cart for Mobile.

