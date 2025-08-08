# 🛠 MApron Booth & Localized Prompt Wizard

## 1. Store Setting (per the Store Manager's direction)
- **Key Settings:**  
  1. Preferred target products--weekly update.  
  2. Local building codes  
  3. Local weather profile (e.g., wildfire warnings).  
  4. Up-engagement strategies
 
example setting.json
```
{
  "store_id": "8949",
  "zip": "92064",
  "1. preferred_products": [
    {"sku": "100123456", "name": "Pressure-Treated Wood Post 4x4x8"},
    {"sku": "100234567", "name": "Quikrete Fast-Setting Concrete Mix (50 lb)"},
    {"sku": "100334455", "name": "Galvanized Fence Brackets"}
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

## 2. MApron Booth (In-Store, near D31 Cust Services)
- **Purpose:** In-store station for demos and engagement.  
- **Features:**  
  - Touchscreen Computer with Keyboard, operated by Operator
  - Wi-Fi Guest connection (no access to the HD net)
  - Local printer (for printing Route Map)

```
Store Associate: 

“Hi there. Want to see how our AI can map out the best solution for your project—right here in the store?”

```


## 3. Prompt Wizard
- **Purpose:** Operated by Associate, to generate optimized Magic Apron prompts and project guides.  
- **Features:** 
  - Chrome Extension powered by GenAI tools
  - Integrates Store Setting data for local relevancy.  
  - Guides the Associate through a structured project workflow.  
  - Generate optimized text prompt for use with Magic Apron.
  
## 4. Magic Apron Text to Route Map
  - Captures Magic Apron text output and formats for printing.

**Route Map Examples:**  
- [Example 1: Fence Replacement](RouteMap_FenceReplace.md)  
- [Example 2: Deck New Build](RouteMap_DeckBuild.md)

**(Optional) Incentive coupon for Booth visitors**

---


## 🧩 Wizard Workflow (operated by Store Associate)

1. **Select Project Type**  
   - Choose project scope: *Build New*, *Replacement*, or *Renovation*.  
   - Select category: *Appliances*, *Windows & Doors*, *Flooring*, *Plumbing*, *Garden*, *Patio*, or *Other*.  

2. **Enter Measurements** (refer to **Pocket Guide**) 
   - Provide dimensions, quantities, and any critical size constraints.  
   - Optional: upload photos or plans for reference.  

3. **Identify Legacy Builds**  
   - Note any existing structures, materials, or installations to integrate, remove, or upgrade.  
   - Highlight potential reuse of components.  

4. **Generate Magic Apron Prompt**  
   - Prompt Wizard combines user inputs with **Store Setting** data (products, weather, code compliance).  

5. **Capture & Format Output**  
   - Store Associate or customer reviews the AI-generated solution.  
   - Output is formatted into a **Route Map** and optional **Route Coupon** for printing.



## 👤 Simon Chen — User Onboarding (UO) Program Specialist  
<img src="https://media.licdn.com/dms/image/v2/C5603AQH27wV2BY9YMA/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1636338982903?e=1756339200&v=beta&t=ZMYnUHe4BygYpMFHdyjttsYB0ZEifyZQawYvj3raww0" width="300" align="right">

career focus: Customer Engagement SaaS | UO Strategy

**Clients:** Pfizer, Roche, J&J, Eisai-Biogen  
current: Store Associate, Poway Store 8949

📞 (858) 733-1029  
📧 presenter.simon@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hsienchen/)  



### 📁 Past UO Works  
- 🔗 [**DFC Website – Patient Recruitment**](./README-cases.md#dfc-website--patient-recruitment)  
- 🔗 [**Lunchbag CME – Physician Engagement**](./README-cases.md#lunchbag-cme---physician-engagement)
