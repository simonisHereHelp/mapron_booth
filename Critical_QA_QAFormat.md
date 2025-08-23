# Critical Q&A — Magic Apron Booth Pilot (Store 8949)


---

**Q1: How to ensure reliability, given that IT support is limited at store?**  

**A:**  
- **Simplicity and store-readiness:** The booth isn’t a complex system—it runs only a browser-based app. No heavy servers, no specialized hardware. It’s powered by NodeJS and our existing Guest Wi-Fi, which is the same setup customers already use on their phones.  
- **Associate ownership:** Day-to-day, this is associate-manageable. It’s no more complicated than running a printer or kiosk that we already maintain. If something goes wrong, associates can restart it without waiting on IT.  
- **Pilot-first approach:** We’re not rolling this out chain-wide from day one. The pilot is just at Store 8949, with Store Manager approval, so we can measure reliability in real conditions and solve issues before scaling.  

---

**Q2: For the booth to work, it needs API access to store inventory tables and to Magic Apron. Both are not available. How will that play out?**  

**A:**  
- **Inventory access:** For the pilot, no live API is required. Weekly stock tables or SKU push lists can be manually downloaded and accessed locally. Using libraries like `pandas.read_csv()` in Python or `fs/promises` in NodeJS, these can be easily loaded into the Route Map generator.  
- **Magic Apron access:** For interaction with Magic Apron, we’ll use a simple **Chrome + copy-paste workflow**. Associates will copy prompts from the Wizard into Magic Apron and paste back results into the Route Map generator.  
- **Pilot scope:** Since this is just a pilot, there’s no need for deeper integration. The focus is proving the customer engagement model, not full enterprise deployment.  


---

**Q3: Wizard Prompt system too complex to build for a pilot?**  

**A:**  
- **Framework-based design:** Rather than designing from scratch, I’ll mirror the category flows already used on HomeDepot.com (e.g., Flooring → Installation → Materials).  
- **Pilot scope:** We’ll focus only on high-level generalizations, not every scenario. The point is to demonstrate feasibility, not perfect coverage.  
- **Personal operation:** For Store 8949, I’ll personally operate the pilot. With my associate experience, I can adapt prompts to actual customer needs in real time.  

---

**Q4: Why dual models? Why Magic Apron together with one other LLM?**  

**A:**  
- **Enhancement, not replacement:** The pilot does not replace Magic Apron. It adds a reasoning layer for customer-facing sales conversations.  
- **Different roles:** Magic Apron is excellent as a catalog and product encyclopedia. GPT is used here only to scaffold Wizard flows, generate examples, and speed prototyping.  
- **Future portability:** Once proven, the same engagement framework can be fully implemented inside Magic Apron.  
- **Business goal alignment:** The end goal is not the technology itself—it’s driving sales and LTSA through more impactful customer interactions.  

---
