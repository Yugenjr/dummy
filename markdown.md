# QuickClaim - Income Insurance, Simplified 😌!!

## Inspiration

Gig workers power India’s on-demand economy, yet their income is fragile.  
**A single disruption like heavy rain, extreme heat, or local shutdowns can wipe out a week’s earnings.**
We started with a simple question:
> *“How are gig workers handling this today?”*

During our research, we spoke with several gig workers, but in particular, one from Haryana who we connected with through an open-source program. His responses reshaped our thinking.

1. **“We do get incentives sometimes, but not when we actually need them.”**  
   Payouts are often delayed or misaligned with the real moment of income loss.
2. **“Fake claims happen in many ways.. how will you prevent that?”**  
   Fraud isn’t rare! it’s expected.
   The third question hit harder than everything else.
3. **“What is ML?”**  
   That was the turning point. we understood that they need not have known that much technology .
> The solution shouldn’t expect users to understand technology — it should just work.

That’s how **QuickClaim** evolved.. built for real users, not assumptions.
---

##  How We Built It

### Worker App
- **React + Vite + Capacitor**
- Mobile PWA with:
  - Real-time **geolocation tracking**
  - **Offline support** (Service Workers)
  - **JWT authentication**
### Admin Dashboard  
- **React + Vite**
- Operations UI for:
  - User management
  - Claim monitoring
  - **Fraud detection dashboard**
### Backend API
- **Node.js + Express**
- **PostgreSQL** (RDS/Cloud SQL) + Redis cache
- Core features:
  - REST API + JWT auth
  - **AI risk scoring engine**
  - GPS/IP correlation
  - Real-time **fraud flags**
  - Parametric trigger system
---
## Challenges we ran into:

### Fraud simulation is harder than expected
GPS spoofing and fake inactivity patterns required **layered validation mechanisms**, not just basic checks.
### Balancing simplicity vs accuracy
Gig workers need **fast, frictionless onboarding**, while insurance models demand **rich and reliable data**.
### Parametric trigger design
Designing **fair and accurate thresholds** without overpaying or underpaying was more complex than expected.
### Real-time decision making
Ensuring **low-latency trigger evaluation** while maintaining accuracy was a key challenge.

---

## What We're Proud of
- Thought of Empathy before Innovating 😌
- Fully functional onboarding + claim system
- Weekly pricing matched to gig earnings
- Auto-triggered claims (no manual filing)
- Fraud-aware architecture beyond demo UI
- Mobile-first UX for real gig workers

---

## What we learned

- Simplicity is harder than complexity
  (especially when users don’t have patience for forms and sometimes to understand tech as well.. )
- “AI powered” means nothing without clean data inputs
- Fraud is not an edge case... it’s the default scenario
- Parametric insurance works only if:
                Trigger Accuracy≈Real Income Loss

## What’s next for QuickClaim

- Integrating with platforms like Zomato / Swiggy  
  So we can work with real data instead of assumptions
- Making fraud detection stronger  
  Looking into behavioral patterns and route consistency to catch anomalies
- Moving towards personalized premiums  
  Pricing based on how each user actually works
- Building a more advanced admin dashboard  
  To track users, risks, and claims in real time

And Yeah that's our phase 1 Journey in a nutshell ! a few things to convey from our side:

A complete single readme might feel vague to read..so under the readme file , navigations are given appropriately .
Regarding the market clash... (hope we escape it 😄).. we have added a dedicated readme for it named Adversarial_Defense_and_Anti_Spoofing_Strategy.md 
and for which navigation is given in readme too.. 


**Team Detroit - We argue , we debug , we deliver !! **
  
  Improving performance, reliability, and overall efficiency of the system at production levels.. 
  
---

