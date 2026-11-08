# Austin, TX Apartment Locator & Client Intake Dashboard

A lightweight, automated client-matching and MLS inventory dashboard built to streamline the apartment-hunting workflow for real estate agents and locators in Austin, Texas. 

### Why I Built This
Finding the right rental in a fast-moving market like Austin involves juggling multiple custom parameters—neighborhoods (Downtown, SoCo, The Domain), bedroom counts, strict pet policies, move-in/move-out timelines, and specific client rental histories (such as second-chance or broken-lease friendly properties). 

This tool replaces manual searching and messy spreadsheets with an instant, interactive filtering engine that matches prospective tenants with qualifying units in milliseconds.

### Key Features
* **Multi-Tiered Filtering:** Instantly cross-references ZIP codes, bedroom counts, pet restrictions, and client rental history.
* **Timeline Validation:** Automatically checks unit availability dates against client move-out and target move-in timelines.
* **Resilient Data Architecture:** Built with an async fetch pattern designed to interface with live property APIs (like RentCast) while maintaining an integrated mock fallback adapter to ensure 100% uptime and seamless client presentations.
* **Secure Config Management:** Uses a local configuration pattern (`config.js`) separated via `.gitignore` to protect API keys and credentials.

### Tech Stack
* **Frontend:** HTML5, CSS3 (CSS Grid & Flexbox), Vanilla JavaScript (ES6+ `async/await`).
* **API Integration:** RESTful endpoints with custom JSON mapping adapters.
* **Version Control:** Git & GitHub Pages for rapid, zero-cost deployment.