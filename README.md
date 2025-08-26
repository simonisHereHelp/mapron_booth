## Store 8949 Needs

**1. to provide Assoc with better Message tools**

  - Every month, Assocs spend 2,000+ hrs on floor service.

  - Current GET method = loose, unstructured.

  - Need new tools → enable Assocs to deliver precise, high-impact messages, used together with GET practice.

**2. to build Assoc's trust in AI at work**

  - Many Assocs feel anxious about AI's role in the workplace.

  - Must show that AI is here to support their work, not replace it.

**3. to pave the way for Pro Accounts UO Program**

  - Pros can get real value from AI, but adoption’s been slow.

  - *User Onboarding* efforts (*workshops, free API access*) can build traction with Pros,and once it’s built, ensure HD’s leading edge in the long run.

##  Magic Apron TB & Localized Prompt Wizard

Magic Apron, HomeDepot's LLM, opens up new possiblities...

```
Core to this proposal is to create effective prompts for use with Magic Apron, and then convert the AI’s output into a Route Map format.
```

![MApron Booth & Prompt Wizard](schematic_line_drawing.png)
<br>
<br>


## Loc: Entrance, Next to D31

- **Features:**  
  - Touchscreen Computer with Keyboard
  - Wi-Fi Guest connection, only!
  - Local printer (for printing Route Map)


## Input: by D31 Assoc
```
Assoc: 

“Hi there. Want to see how our AI can map out the best solution for your project—right here in the store?”

```
<br>
<br>

## Setting (per the Store Manager's direction)
- **Key Settings:**  
  1. Store weekly push  
  2. Local building codes  
  3. Local weather profile (e.g., wildfire warnings).  
  4. Up-engagement strategies
 
example **Store_Setting.json**
```
{
  "store_id": "8949",
  "zip": "92064",
  "1. "store_weekly_push": [
    {"sku": "100123456", "name": "Pressure-Treated Wood Post 4x4x8"},
    {"sku": "100456789", "name": "RYOBI 18V ONE+ Cordless Drill/Driver Kit"},
    {"sku": "100567890", "name": "Westinghouse 9500DF Dual Fuel Portable Generator"},
    {"sku": "100678901", "name": "Toshiba 12000 BTU Portable Air Conditioner"}
  ],
  "2. local_weather": {
    "condition": "hot_dry, wildfire hazard",
    "recommendations": [
      "Use outdoor-rated adhesives and corrosion-resistant fasteners",
      "Apply UV-resistant exterior stain to prolong material life",
      "Maintain defensible space by clearing vegetation near fence line",
      "Select ignition-resistant or treated lumber where feasible",
      "Avoid storing flammable materials adjacent to structures"
    ]
  },
  "3. building_codes": {
    "fence_rules": "Masonry or wood fences 6 ft or less do not require a building permit; however, clear 2-ft access to water meters and no encroachment in utility easements. (Per Poway standard plan & PMC 13.11.130.A) :contentReference[oaicite:1]{index=1}",
    "wui_requirements": "Fences in high fire risk zones must comply with Wildland-Urban Interface Code—PMC 15.24.100. :contentReference[oaicite:2]{index=2}",
    "zoning": "Fence heights regulated under PMC 17.08; front yard height rules per Title 17.08.240. :contentReference[oaicite:3]{index=3}"
  },
  "4. up_engagements": [
  "Need a list of trusted landscapers for your backyard?",
  "Thinking about adding solar lighting or panels out back?",
  "Want ideas to pair your fence with landscaping or solar upgrades?"
]
}

```

<br>
<br>


## Prompt Wizard
- **Purpose:** Help Associates create optimized text prompts for Magic Apron--powered under the hood by reasoning-ready LLM (eg GPT-5)  
- **Features:**  
  - Chrome Extension.  
  - Uses Store Setting data for local relevance.  
  - Step-by-step project workflow.  
  - Generates prompts ready for Magic Apron.
  
## Magic Apron Text to Route Map
  - Captures Magic Apron text output and formats for printing.

**Route Map Examples:**  
- [Example 1: Fence Replacement](RouteMap_FenceReplace.md)  
- [Example 2: Deck New Build](RouteMap_DeckBuild.md)

**(Optional) Incentive coupon for Booth visitors**

---
<br>
<br>

## 🧩 Associate’s Step-by-Step

1. **Pick from List**  
   - Scope: [Build New], [Replacement], or [Renovation]*.  
   - Category: *Appliances*, *Windows & Doors*, *Flooring*, *Plumbing*, *Garden*, *Patio*, or *Other*.  

2. **Measure** *(refer to Pocket Guide)*  
   - Enter dimensions, quantities, and critical size constraints.  

3. **Additional Text Input**  
   - Identify current structures, materials, or installations to keep, remove, or upgrade.  
   - Note any items that can be reused.  

4. **Copy Prompt**    
   - Copy the generated text into Magic Apron for results.  

5. **Review & Print**  
   - Go over the AI-generated solution with the customer.  
   - Print as a **Route Map** and, if available, a **Route Coupon**.

<br>
<br>
<br>

## ✅ Action Items

-1. **Store 8949 Commitment** – Ready to trial once the booth is available, per David, the SM. 

-2. **Follow-Up Works** – Refine scope, design UI/UX, and define eval metrics.

-3. **Local Launch** – Local Env, running NodeJS, API access (toekn cost?), a simple pilot

-4. **Collect Insight** – on effective prompting, store perf, customer feedback, and SM+Assoc adoption/in-road

<br>
<br>

## 👤 Simon Chen — User Onboarding (UO) Program Specialist  
<img src="https://media.licdn.com/dms/image/v2/C5603AQH27wV2BY9YMA/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1636338982903?e=1756339200&v=beta&t=ZMYnUHe4BygYpMFHdyjttsYB0ZEifyZQawYvj3raww0" width="300" align="right">

career focus: Customer Engagement SaaS | UO Strategy

**Clients:** Pfizer, Roche, J&J, Eisai-Biogen  
current: Store Associate, Poway Store 8949

📞 (858) 733-1029  
📧 presenter.simon@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hsienchen/) 

<br>
<br>
<br>

## 🎯 Past UO Works

🔗 [DFC Website – Patient Recruitment](past_UO_cases.md#dfc-website--patient-recruitment)  
🔗 [Lunch Bag CME – Physician Engagement](past_UO_cases.md#lunch-bag-cme--physician-engagement)


