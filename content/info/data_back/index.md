---
title: "What is 'Data Back'?"
authors:
    - fern
weight: 1
draft: false
description: "Indigenous DATA BACK"
heroStyle: "background"
tags: ["Writings", "info"]
#series: ["Documentation"]
#series_order: 1
---
---
## What is "Data Back"?

**"Data Back"** is a movement and rallying cry for Indigenous peoples to reclaim authority over their own data, paralleling calls for **#LandBack** and **#CashBack**. At its core, **"Data Back"** demands that data about Indigenous communities, cultures, languages, and lands-regardless of how or when it was collected-rightfully belongs to those communities and must be governed by them.

### Key Principles

- **Indigenous Data Sovereignty:**  
  "Data Back" is rooted in the principle of Indigenous Data Sovereignty: the right of Indigenous nations to govern the collection, ownership, and application of their own data. This means Indigenous peoples should control how their data is collected, stored, accessed, and used, in alignment with their values and worldviews.

- **Response to Extractive Practices:**  
  The movement is a reaction against extractive, colonial systems that have historically commodified and profited from Indigenous knowledge, culture, and information-often without consent or benefit to the communities themselves.

- **Cultural Revitalization:**  
  Beyond resistance, "Data Back" inspires the rejuvenation of Indigenous cultures by supporting the protection and revitalization of language, traditions, and knowledge systems through community-controlled data practices.

### Guiding Ethos

> “Nothing about us without us.”

This phrase captures the essence of the movement: Indigenous peoples must be at the center of all decisions about their data. Internationally, this is supported by the United Nations Declaration on the Rights of Indigenous Peoples (UNDRIP) Article 31, which affirms the right of Indigenous peoples to maintain, control, protect, and develop their cultural knowledge and data.

### Why It Matters

- **Restoring Authority:**  
  "Data Back" seeks to reverse centuries of data colonialism by restoring authority to Indigenous communities over their information and representation.

- **Ethical Data Governance:**  
  The movement calls for data governance models that prioritize Indigenous consent, benefit, and stewardship, challenging Western-centric and extractive approaches.

- **Community Digital Literacy and Data Privacy:**  
  Teaching digital literacy and data privacy practices is essential to the "Data Back" movement. By equipping community members with the skills to understand, protect, and manage their own data, we empower Indigenous peoples to safeguard their information, resist digital exploitation, and make informed choices about technology. This education helps ensure that data sovereignty is not just a principle, but a lived reality-enabling communities to actively defend their rights and shape their digital futures.

In summary, "Data Back" is about returning control of data to Indigenous peoples, ensuring it is managed, shared, and used on their terms, for their benefit, and in accordance with their cultural values and rights.

### Why Individual Rights Aren't Enough

Standard data governance tools — consent forms, individual access rights, opt-out mechanisms — are structurally insufficient for protecting community data. The reason is fundamental: data about individuals is used to generate population-level inferences about everyone who shares their features — their tribe, their community, their demographic. An agency that collects health data from individual tribal members can use that data to make decisions affecting the entire nation. A researcher who gathers GPS tracks from individual fishers can reveal collective patterns of traditional use that no single individual authorized to share.

The harm is collective. Individual consent cannot govern it. Clicking "accept" on a terms of service agreement cannot protect a community from what is done with data about its members in aggregate. Legal scholar Salomé Viljoen names this the **sociality problem** in data governance: current law treats data as a matter between an individual and a data collector, but the economically and socially significant effect of data production is *horizontal* — it creates relations between data subjects, placing people into populations defined and managed by others. The remedy has to match the harm. This is why Data Back demands democratic, community-level governance of data — not just better privacy settings for individuals.

---

![data back elk](feature.png "#DataBack")

---

## What This Looks Like in Practice

Consider a tribal environmental monitor documenting eel habitat along a stretch of the Klamath for a dam removal recovery study. She knows which backwater channels the eels use to overwinter because her grandmother told her, and her grandmother knew because she had watched the river her whole life, and that watching went back further than any written record. That knowledge — hyperlocal, intergenerational, empirically verified across generations — is the most precise data in the room. But when she sits down to map it, she is using ArcGIS Online, a subscription service owned by Esri, whose servers are in Redlands, California. When the grant ends, the license expires. The maps live on a corporate server. The knowledge her grandmother's grandmother carried, now encoded in a shapefile, is behind a paywall the tribe may or may not be able to afford next year.

This is not a hypothetical. It is the working situation of tribal environmental departments, language programs, cultural resource offices, and community organizing efforts across Indian Country and in every bioregional community doing serious land and water work. The data that matters most — salmon return counts, habitat maps, traditional use documentation, environmental baselines that underpin treaty rights claims and conservation strategies — is being generated by people with irreplaceable local knowledge and then stored in systems they do not control, analyzed with tools they do not own, managed by contractors who leave when the funding cycle ends.

The failure modes of this dependency are specific and recurring:

A **GIS contractor** hired to map ancestral territory does not know which boundary line matters for a treaty rights argument and which is an administrative artifact from a 1950s federal survey. They do not know that one place-name on the map is the settler approximation of a Karuk name that means something entirely different about that site's use and significance. They produce a technically correct map that is culturally illiterate, and when the contract ends, the institutional knowledge of why the map was built the way it was leaves with them.

A **database vendor** does not know that certain species location data is sensitive — that disclosing where a particular plant grows could enable poaching of a culturally significant resource, or that a specific fishing location is tied to ceremonial use and governed by protocols about who may know it. They treat all records as technically equivalent, because for them they are.

A **corporate software subscription** creates a permanent dependency. Every year, the community must pay to access its own data. Every platform update may break workflows. The vendor's product roadmap determines what is possible. And the data itself — the observations, the records, the maps built from years of community knowledge — lives on servers the community does not own, subject to terms of service written by lawyers in another state, accessible to law enforcement subpoena without the community's knowledge or consent.

When outside contractors and corporate platforms hold the technical infrastructure of a community's ecological and social work, the community has reproduced in digital form the same dependency that colonial extraction always creates: the knowledge and labor flow in, and the control flows out.

**Traditional ecological knowledge is not separable from the protocols that govern it.** In living Indigenous knowledge systems, knowing something comes with obligations about how that knowledge moves — who holds it, who may access it, under what circumstances it is shared, what relationships are required before it is disclosed. A database built by someone who doesn't understand these protocols will either exclude TEK entirely (because the contractor doesn't know how to ask) or incorporate it carelessly, stripping it of its relational context and making it available in ways the knowledge-holder never intended.

The person best positioned to build a database that properly handles Karuk traditional ecological knowledge is someone who already understands what that knowledge is, how it moves through the community, and what obligations surround it. That person may be a fisheries monitor, a language keeper, a fire practitioner, a basket weaver who also watches the birds. They can also learn to be a database administrator. A GIS analyst. A network administrator. A security practitioner. These are learnable skills — not magic, not reserved for a credentialed class of outsiders. They are tools, and tools can be taught.

The skills that ecological and social sovereignty require right now include:

- **GIS and spatial data** — who controls the maps of a territory controls how that territory is understood, managed, and contested in courts, agencies, and the public record. Communities with their own GIS capacity do not depend on outside agencies to describe their own land.
- **Databases** — for cultural knowledge, genealogy, species observation, environmental monitoring, language documentation, resource management. The difference between community-controlled infrastructure and a corporate platform is who decides who can see what, and under what conditions.
- **Groupware and coordination tools** — organizing across a geographically dispersed rural community requires shared tools. Those tools can be self-hosted and controlled, or they can be Google Workspace, where the terms of service mean that everything is available to federal subpoena and corporate data analysis.
- **Encryption and communications security** — the documentation of treaty violations, the records of a land rights campaign, the locations of culturally sensitive sites, the organizing conversations of a community resisting extraction: all of this has adversaries, and those adversaries have the same tools law enforcement and corporations have always used to surveil and disrupt movements.
- **Network infrastructure** — community-owned mesh networks, tribal broadband cooperatives, local servers: infrastructure that does not route through corporate systems, that stays up when commercial providers go down in a wildfire, that is governed by the community rather than a distant corporation.

None of this requires that every community member become a full-time technologist. It requires that technical skills exist *inside* the community — that there are people who hold them, who are rooted in the place and accountable to the people, who will still be there after the grant ends and the contractor has moved on.

This is why collective, community-based tech literacy is a dimension of sovereignty, not a nice-to-have. The goal is not to produce isolated individual experts — it is to build shared capacity that circulates through the community, held by many hands, not dependent on any single person or any single grant cycle. Knowledge shared between neighbors is harder to extract, harder to defund, and harder to dispossess than knowledge held by a contractor.

There is also a role for settlers and non-Native people who hold these technical skills — not to lead this work or arrive as experts, but to share skills when asked, to show up as learners-alongside rather than contractors-in-charge, and to understand that making technical knowledge genuinely available to Indigenous and land-based communities who want it is a form of relational allyship. Projects like the [Indigenous Mapping Collective](https://www.indigenousmaps.com/) have modeled what this looks like in practice: technically skilled people in genuine solidarity with communities doing their own mapping, on their own terms, transferring capacity rather than extracting data. Growing that kind of relationship — bringing skills into the community rather than extracting community knowledge into outside systems — is one way these skills become genuinely available to communities that want them.

---

### Find Out More...

- https://animikii.com/insights/databack-recognize-and-reclaim-indigenous-data-sovereignty
- https://databack.animikii.com/
- https://www.idsovandresearcher.com/
- https://usindigenousdatanetwork.org/

### Examples
- https://www.sentinelsnetwork.com/
- https://www.indigenousmaps.com/

---

## Further Reading

- Viljoen, Salomé. "A Relational Theory of Data Governance." *Yale Law Journal* 131:573, 2021.
- CARE Principles for Indigenous Data Governance: [gida-global.org](https://www.gida-global.org/care)
- Duarte, Marisa Elena. *Network Sovereignty: Building the Internet Across Indian Country.* University of Washington Press, 2017.

Also on this site: [A Critical History of the Internet](/info/internet_history/) · [Technocolonialism](/info/technocolonialism/) · [Animism, AI & Consciousness](/info/ai_animism/)
