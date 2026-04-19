# AI at Work Agent & Adoption Package

This is part of a broader set of Copilot agent and learning materials. Check out my projects site to get an overview:
https://www.jaysons.dev

### Updates
10.04.2026
- Updated Solution package 1.1 with reworked Flows
  - Added new environment variables for custom nudge icons and button links for indivialization
  - Agent Flows have accordingly been reworked
- ! added update solution package "Nudge Updates solution v2.1" to be imported if initial solution package had already been imported / deployed
- ! after import of NudgeUpdate make sure to add new environment variables and Flows to existing solution, deactivate old flows


### Executive Summary
AI at Work Agent & Adoption Package is a declarative Copilot agent combined with an adoption framework to enable AI literacy across the entire organization. Users are reached directly in 1:1 Teams chat via proactive agent nudges, ensuring high visibility, relevance, and real acceptance of AI topics in daily work. Its evergreen design allows centrally planned nudges to continuously land monthly feature updates, new scenarios, and learning content directly with users, creating fast, additive value over time.

### Value
Direct 1:1 Teams nudging turns the agent into an active adoption channel rather than a passive knowledge base, maximizing attention and engagement. Centrally planned, evergreen nudges ensure that Copilot updates, new features, and best practices reach users quickly and consistently, without relying on traditional comms channels. This significantly reduces time to value while sustaining long‑term adoption with minimal operational effort.
### Setup
- find the complete instructions in "package overview and setup.pdf"
- import "complete solution.zip" in PowerApps Studio
- import Sharepoint List schemas either via Sharepoint Online GUI (csv) or via Powershell (xml)
- adjust envinroment variables in PowerApps Studio
- that's all --> now its only on you to plan and publish  

**Add these additional contents for maximum value**
- Safe AI with Copilot Chat Learning Path https://github.com/JaysonBucket/Copilot-Chat-Safe-AI-Learning-Path
- M365 Learning Pathways https://github.com/pnp/custom-learning-office-365
- Copilot Chat Success Kit https://adoption.microsoft.com/en-us/copilot-chat/success-kit/
- Copilot Success Kit https://adoption.microsoft.com/en-us/copilot/success-kit/
<br>

### Overall Overview
<img width="450" height="225" alt="image" src="https://github.com/user-attachments/assets/63280b71-eb91-464b-a5b3-1fa87c6a7cbf" />

### Agent Experience
<img width="457" height="418" alt="{C066FFD1-3E03-4C22-A637-7F7B6F821A40}" src="https://github.com/user-attachments/assets/b58d7cf6-8c36-4f3f-8ca2-4cf452a8331d" />

### Enduser Nudge Experience
<img width="400" height="260" alt="image" src="https://github.com/user-attachments/assets/061d7ae9-4847-46af-9e58-b05f98517d2f" />

### Enduser Prompt Tipps Experience
<img width="425" height="215" alt="image" src="https://github.com/user-attachments/assets/fde992c4-e9c6-40ac-adba-04b14ceae6cb" />

### NEW Teams App advanced Experience
<img width="440" height="242" alt="image" src="https://github.com/user-attachments/assets/99d478ac-7157-4200-9b3f-e0b56f991b56" />
<br>
<br>

### Goal
- Enable organization‑wide AI literacy around Microsoft 365 Copilot and AI at work
- Support users from Beginner to Expert/Developer based on role, persona, and maturity
- Establish a centralized, trusted “one‑stop shop” for AI learning, inspiration, and updates
- Drive ongoing adoption beyond one‑time trainings or campaigns
- Lower entry barriers by supporting even free Microsoft 365 Copilot Chat users

### Solution
- Declarative Copilot agent fully web‑grounded and free to use
- Curated content repository structured by persona, maturity, and category
- Flexible deployment options, from passive discovery to proactive nudging via Power Automate
- Centrally planned 1:1 Teams nudges for feature updates, scenarios, and learning content
- Clear content governance model separating public and optional internal resources

### Value Proposition:
- Deploy once, reuse indefinitely with full content flexibility
- Proactive 1:1 Teams communication ensures maximum visibility and acceptance
- No PAYG, no custom build, no operational overhead
- Relevant recommendations through lightweight bucketization and IDs
- Supports adoption, enablement, communications, champions, IT, and developers alike
- Easy extensibility by adding internal links without breaking the model

### Problem Statement:
- AI learning content is scattered across portals, links, and communities
- Users are overwhelmed by volume and unsure where to start
- Existing enablement efforts are often one‑off, role‑agnostic, or not scalable
- Copilot updates do not reliably reach users in their daily workflow
- Organizations lack a proactive, evergreen mechanism to land AI change continuously

## What's the deal
- template content
- all customizable
- links to internal resources can be added

HINT: when adding internal resources mind your audience!
- Adding it just as additional resources like the rest will work super smooth, take appropriate classification
- adding it as Knowldedge sources will also work fine, but as you with that add organizational data as source, PAYG will be needed for Copilot Chat users


## Content organization structure

The content, especially the links dropped, is organized in a way to make the agents suggestions as relevant as possible without putting too much effort in. 
This is achieved through three different bucketizations.

To save characters for declarative agents content, each bucket is organized with IDs which are then being used as short identifiers within the content list.

There is a clear pattern how the content list then is organized - referring to the bucket IDs for categorization:
Content Name;Category ID CID;Persona ID PID;Maturity ID MID;Content Link;Content Description

## Content categorization / bucketing

#### Categories
gives an idea about what kind of content is behind the link

Structure: Categories;CID
- Events and Webinars;1
- Self-Paced Learning;2
- Training;3
- HowTo;4
- examples;6
- news;7

#### Personas
indicates for which kind of user group this content is relevant

Structure: Personas;PID
- Enduser;1
- Developer;2
- Champions;3
- Business;4
- Comms;5
- IT;7
- everyone;8
- ACM Team;9

#### Maturity level
respects current users experience to sort out too low- or high-level content \

Structure: Maturity Level;MID
- beginner;1
- advanced;2
- expert;3
- any;4








