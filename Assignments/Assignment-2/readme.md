# CHAPTER 2: WEBSITE DEVELOPMENT PROCESS - 

## 🟢 GROUP A: SHORT QUESTIONS (2 MARKS)

### 1. Define the term “Sitemap” in the planning phase.
A Sitemap is a comprehensive visual or textual representation of 
a website's structure, detailing every page and its relationship 
to others. During the planning phase, it serves as the primary 
architectural blueprint that defines the hierarchy of content. 
By mapping out the sitemap early, developers ensure logical 
navigation and a smooth user flow, preventing the creation of 
orphaned pages that are difficult for users or search engines 
to find.

### 2. What is the purpose of the “Launch” phase?
The Launch phase is the critical stage where a website is moved 
from a local or staging environment to a live, public web server. 
The purpose is to make the site accessible to the global internet 
audience. This involves configuring domain names (DNS), 
setting up SSL certificates for data encryption, and performing 
final environment checks to ensure the live server handles 
the code exactly as the development server did.

### 3. Why is “Documentation” important?
Documentation is the formal record of a website's technical and 
functional logic. It is vital because it ensures that the system 
can be maintained and updated by different developers in the 
future. Without clear documentation, troubleshooting bugs or 
adding new features becomes a time-consuming and error-prone 
process. It serves as the "instruction manual" for the site's 
codebase, database structure, and third-party integrations.

---



## 🟡 GROUP B: LONG QUESTIONS (4 MARKS)


### 5. “Planning is the most critical phase of web development.” Discuss.

**I. Introduction**
Planning is the foundational stage of the Web Development Life Cycle (WDLC). 
It serves as the bridge between a client's abstract vision and the 
technical execution. Without a robust planning phase, a project lacks 
boundaries, objectives, and a roadmap, making it highly susceptible 
to failure, budget overruns, and missed deadlines.

**II. Strategic Pillars of the Planning Phase**
* **Goal Alignment:** Establishing exactly why the site is being built.
* **Resource Optimization:** Identifying the human and technical 
  resources required.
* **Scope Definition:** Creating a clear "start" and "end" point for 
  the development team.
* **Risk Mitigation:** Anticipating technical bottlenecks before 
  they cost money.



**III. Detailed Thematic Analysis**
1. **Defining Project Goals and Scope:**
   Planning begins by identifying the Key Performance Indicators (KPIs). 
   Is the goal to sell products (E-commerce) or provide information 
   (Educational)? Defining the "Scope" ensures that developers do not 
   waste time on features that the client does not actually need, 
   preventing "Scope Creep."

2. **Understanding Client Requirements and Audience:**
   A developer must play the role of a consultant. By gathering 
   information about the target audience (age, location, technical 
   literacy), the developer can choose the right design language 
   and functionality.

3. **Sitemap and Wireframe Construction:**
   Before coding, a sitemap acts as a skeletal structure. It 
   visualizes the relationship between pages. Wireframes, on the 
   other hand, define the UI layout. These documents act as a 
   contract between the client and developer.

4. **Tool and Tech Stack Selection:**
   Based on the goals, the team decides whether to use a CMS 
   (WordPress/Drupal) or custom frameworks (React/Node.js). 
   Planning ensures the chosen technology can handle the expected 
   user traffic.

**IV. Conclusion**
Planning is not merely a preliminary step; it is the blueprint of 
the entire project. A website built without planning is like a 
house built without an architect—it may look fine initially, 
but it will eventually collapse under the weight of its own 
inefficiencies.

---

### 6. Explain the iterative nature of the Maintenance phase.

**I. Introduction**
In the professional world, a website is never truly "finished." 
The moment a site is launched, it begins to age. The Maintenance 
phase is an ongoing, cyclical process designed to keep the website 
functional, secure, and competitive in a changing digital market.

**II. The Cycle of Maintenance**
* **Reactive Maintenance:** Fixing bugs reported by users after launch.
* **Preventative Maintenance:** Updating software to prevent hacks.
* **Evolutionary Maintenance:** Adding features to match competitors.
* **Adaptive Maintenance:** Changing the code to work with new browsers.



**III. Detailed Analysis of Why a Site is Never Finished**
1. **Evolving Security Threats:**
   Cybersecurity is a moving target. Hackers constantly find new 
   vulnerabilities in server software and plugins. Maintenance 
   requires regular security patches to protect sensitive user data.

2. **Content Stale-ness:**
   For a website to remain useful, it must have fresh data. For 
   example, a University site with 2023 schedules in 2026 is 
   useless. The iterative nature of maintenance involves 
   constantly auditing and refreshing content.

3. **Technological Advancements:**
   Web browsers (Chrome, Safari, Firefox) update their engines 
   constantly. A site that looks perfect today might "break" 
   tomorrow due to a browser update. Maintenance involves 
   continuous testing for cross-browser compatibility.

4. **Performance Optimization:**
   As databases grow, site speed may decrease. Maintenance 
   involves cleaning up databases, optimizing images, and 
   ensuring that the "Load Time" stays under the critical 
   3-second mark.

**IV. Conclusion**
Maintenance is the heartbeat of a website. It is an iterative 
loop of monitoring, fixing, and upgrading that transforms a 
static digital product into a living, evolving business asset.

---

### 7. Describe the process of Information Gathering.

**I. Introduction**
Information Gathering is the "Discovery Phase" of web 
development. It is the initial interaction where the developer 
acts as a researcher to extract the vital parameters of the 
business from the client.

**II. Core Steps in Information Gathering**
* **Stakeholder Interviews:** Meeting with the people who 
  fund and use the site.
* **Competitive Analysis:** Studying what the competition is 
  doing right and wrong.
* **Technical Constraints Audit:** Checking the existing 
  hosting or legacy systems.

**III. Detailed Process Breakdown**
1. **Client Interviews and Meetings:**
   This is more than a casual chat. It is a formal extraction 
   of the "Brand Voice." The developer asks: "What is the 
   one thing you want users to do on this page?"

2. **Understanding Business Goals:**
   The developer must understand the monetization model. If the 
   business goal is lead generation, the information gathering 
   must focus on contact forms and Call-to-Action (CTA) placement.

3. **Target Audience Importance:**
   Understanding the "End User" is the most critical part of 
   this phase. If the audience is elderly, the design needs 
   high contrast and large fonts. If the audience is Gen-Z, 
   the site needs to be extremely mobile-fast and visual. 

**IV. Conclusion**
Information gathering ensures that the developer isn't just 
building a "generic" website, but a specialized tool that 
solves a specific business problem.

---

## 🔴 GROUP C: SCENARIO-BASED QUESTIONS (5 MARKS)
> **Requirement:** Maximum length (4-6 Pages equivalent). 
> **Format:** Analysis, Impact, Risks, Corrective Action.

### 8. Client wants to skip the Testing phase. Explain the risks.

**I. Scenario Analysis**
A client, often motivated by budget or time constraints, may 
request to skip the testing phase to go "live" faster. This 
is one of the most dangerous decisions in the development cycle.

**II. Comprehensive Risk Assessment**
* **Security Vulnerabilities:**
  Untested code is a gateway for SQL injections and XSS 
  attacks. If a site is launched without a security audit, 
  sensitive user information (passwords, emails) is at high risk.
* **Functional Paralysis:**
  Critical features like "Add to Cart," "Payment Gateways," 
  or "Contact Forms" may fail under certain conditions. If a 
  user cannot pay, the business loses revenue immediately.
* **Device Fragmentation (Compatibility):**
  There are thousands of screen resolutions. Without testing, 
   the site might look perfect on the developer's 4K monitor 
  but be completely unreadable on a budget Android phone.

**III. The Impact of Skipping Testing**
1. **Reputational Damage:** First impressions are permanent. 
   A user who visits a buggy site will never return.
2. **Financial Loss:** The cost of fixing a bug *after* launch is often 10 times higher than fixing it *during* the testing phase.
3. **Legal Liability:** If a site skips testing and results 
   in a data breach, the client could face massive legal fines.

**IV. Conclusion**
Testing is not a "luxury"—it is a necessity. It ensures that 
the website is reliable, secure, and ready for the harsh 
environment of the public internet.

---


### 9. Developer starts coding without design or sitemap.

**I. The Problem: "Coding in the Dark"**
When a developer jumps straight into HTML/CSS/JS without a 
sitemap or wireframe, they are building a structure without a 
foundation. This leads to "Spaghetti Code" and constant rework.

**II. Analysis of the Failure Points**
* **Lack of Visual Direction:** Without a design, the 
  developer makes arbitrary aesthetic choices that the 
  client might hate, leading to hours of wasted coding.
* **Undefined User Journey:** Without a sitemap, the 
  navigation becomes a maze. Pages are linked randomly, 
  making it impossible for users to find information.
* **Scope Inflation:** Since there is no plan, the developer 
  might build features that aren't needed while forgetting 
  features that are essential.

**III. Corrective Professional Process**
1. **Requirement Elicitation:** Fully understand the needs.
2. **Sitemap Creation:** Map the page hierarchy.
3. **Wireframing/Prototyping:** Get visual approval.
4. **Development:** Only now should coding begin.

**IV. Conclusion**
Planning and Design phases exist to save time. Skipping them 
always results in a longer, more expensive, and more 
frustrating development process.

---


### 10. University website became outdated. Analysis.

**I. Diagnosis of the Issue**
If a University website features old exam schedules, broken 
links, and outdated faculty lists, the **Maintenance Phase** has been completely neglected.

**II. The Role of Maintenance in Institutional Sites**
University websites are dynamic. They are hubs of daily 
information. Neglecting maintenance results in:
* **Information Decay:** Users lose trust in the institution.
* **SEO Degradation:** Search engines penalize sites with 
  broken links and outdated content.
* **Operational Inefficiency:** Students call the office 
  constantly because they can't find the info online.

**III. Required Maintenance Activities**
1. **Content Refresh Cycle:** A designated admin must update 
   exam dates and news at least once a week.
2. **Technical Audits:** Regularly checking that the 
   "Student Portal" can handle the traffic during results.
3. **Security Monitoring:** University sites are high-value 
   targets for hackers; security must be updated monthly.

**IV. Conclusion**
A University website is a service. Without a dedicated 
maintenance plan, it ceases to be a useful tool and 
becomes a digital liability for the institution.