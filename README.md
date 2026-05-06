# eStump
### A Hyperlocal Stump Removal Marketplace

> The most niche marketplace you've ever seen. I have since learned more about stumps than any one person should.

---

## Overview

eStump is a hyperlocal three sided marketplace that connects homeowners with vetted stump removal contractors in their area. The idea came from the client himself, a stump removal contractor who saw a gap in the market and came to me to build the solution.

What looked like a simple booking tool on the surface turned out to be a deceptively complex marketplace with three distinct user types, a distance based contractor matching system, a traveling contractor fallback, and a full admin approval workflow.

eStump is currently in final stages and launching mid May 2026.

---

## The Problem

- Homeowners needed a simple, no account required way to request stump removal in their area
- Contractors needed a way to manage and accept jobs within their preferred travel radius
- If no local contractor was available, the job needed to fall through to a traveling contractor
- The eStump team needed a way to vet, approve, and manage contractors before they ever touched the platform
- The client is also a contractor himself and needed his own separate business account on the platform

---

## My Role

**Founder & Full Stack Engineer, Alors Creative**

I was the sole engineer and technical decision maker on this project, responsible for the full stack architecture, backend engineering, frontend development, and ongoing maintenance.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js |
| Backend | Node.js / Express |
| Database | PostgreSQL |
| ORM | None, raw queries for lean and purposeful data access |

---

## Architecture & Technical Highlights

### Three Sided Marketplace
eStump is built around three distinct user types, each with their own experience and access level:

- **Homeowners** — No account required. Submit a job request, receive email updates throughout the process, pay the 20% platform fee upfront, and settle directly with the contractor on completion.
- **Contractors** — Create an account, set their travel radius, and manage incoming jobs through a dedicated dashboard. Go through a vetting and approval process before being activated on the platform.
- **Admin (eStump team)** — Manage contractor approvals and denials through a dedicated admin dashboard. The client also has a separate contractor account for his own stump removal business.

### Distance Based Contractor Matching
When a homeowner submits a job request, the platform matches them with vetted contractors within their area based on each contractor's preferred travel radius. Contractors can set their radius at signup: 5, 10, 15, or 25 miles.

### Traveling Contractor Fallback
If no contractor is available within the homeowner's area, the job opens up to traveling contractors who have opted in to taking jobs beyond the standard radius. This ensures no job goes unfulfilled regardless of location.

### Contractor Approval Workflow
Before a contractor can accept jobs on the platform, they must go through a vetting process managed through the admin dashboard. The eStump team reviews compliance documentation and approves or denies each application before the contractor is activated.

### No Account Required for Homeowners
To reduce friction on the customer side, homeowners never have to create an account. They submit a request, receive email updates at each stage of the job, and complete payment directly with the contractor on site.

---

## Key Features

- Homeowner job request flow with no account required
- Email based job status updates for homeowners
- Contractor dashboard for managing and accepting jobs
- Distance based contractor matching with 5, 10, 15, and 25 mile radius options
- Traveling contractor fallback for jobs outside local coverage areas
- Admin dashboard for contractor vetting, approval, and platform management
- Separate contractor account for the client's own stump removal business
- 20% platform fee collected upfront from homeowners

---

## Outcome

eStump is currently in final stages of development and launching mid May 2026. What started as a simple booking tool evolved into a fully featured three sided marketplace with a sophisticated matching system, admin workflows, and a thoughtful no friction experience for homeowners.

---

## Live Site

*[Visit eStump](https://estump.com/)*

---

*Built by Lindsey Dortch, Alors Creative*
*[lindseydortch.dev](https://lindseydortch.dev) · [linkedin.com/in/lindseydortch](https://linkedin.com/in/lindseydortch) · [github.com/lindseydortch](https://github.com/lindseydortch)*
