# 01 – Foundations & Culture  
**What DevOps Really Means + Key Frameworks**

This module starts with mindset: DevOps is cultural and organizational before it's technical. Tools come later. We'll draw from two excellent books to define it clearly:

- *Learning DevOps (Second Edition)* by Mikael Krief  
- *Cloud Native DevOps with Kubernetes* by John Arundel & Justin Domingus

### What DevOps Really Means

DevOps emerged around 2007–2009, coined by Patrick Debois, Gene Kim, and John Willis. It combines **Development (Dev)** and **Operations (Ops)** to break down silos and create multidisciplinary teams that deliver business value faster and more reliably.

From *Learning DevOps (Second Edition)*:  
> The term DevOps [...] represents the combination of Development (Dev) and Operations (Ops). It has given rise to a movement that advocates bringing developers and operations together within teams. This delivers added business value to users more quickly, which makes it more competitive in the market. DevOps culture is a set of practices that reduce the barriers between developers, who want to innovate and deliver faster, and operations, who want to guarantee the stability of production systems and the quality of the system changes they make.

It extends **agile methodologies** (Scrum, XP, etc.) by including Ops in the loop — enabling more frequent, higher-quality deployments, better end-to-end visibility, and cost savings through reduced rework and outages.

Key enablers include:
- Frequent deployments via **CI/CD** (Continuous Integration / Continuous Delivery)
- Automated testing (TDD/BDD focus)
- User feedback loops
- Monitoring of apps and infrastructure

From *Cloud Native DevOps with Kubernetes*:  
> Nobody Understands DevOps [...] There is also widespread misunderstanding about what DevOps actually is: A job title? A team? A methodology? A skill set?

The book emphasizes that DevOps is **primarily an organizational, human issue**, not a technical one (quoting Jerry Weinberg: "No matter how it looks at first, it’s always a people problem").  

It debunks myths like "NoOps" (outsourcing all ops to cloud providers eliminates the need for DevOps) — in reality, DevOps shifts traditional ops work earlier in the pipeline: automated tests, security scans, monitoring, logging, and policy checks happen **before** code reaches production.

Business value:  
> DevOps is “improving the quality of your software by speeding up release cycles with cloud automation and practices, with the added benefit of software that actually stays up in production” [...] companies that adopt DevOps principles release better software faster, react better and faster to failures and problems, are more agile in the marketplace, and dramatically improve the quality of their products.

In 2026, with AI accelerating code and cloud-native defaults, DevOps remains essential: slow, unstable delivery kills competitiveness.

### Key Frameworks

These frameworks capture the essence from both books and the broader movement.

#### 1. CAMS / CALMS (from John Willis & others)  
Popularized by John Willis (with Damon Edwards), later extended to CALMS by Jez Humble. This is one of the most cited breakdowns of DevOps pillars.

| Pillar     | Meaning                                                                 | Explanation from Sources                                |
|------------|-------------------------------------------------------------------------|---------------------------------------------------------|
| **C**ulture| Collaboration, trust, breaking silos, shared responsibility             | Core of both books: multidisciplinary teams, no "throw over the wall" |
| **A**utomation| Automate builds, tests, deploys, infra (IaC)                            | Essential for speed + reliability; tools must be shared across Dev/Ops |
| **M**easurement| Track meaningful metrics (speed, stability, quality)                    | Prove progress with data; aligns with monitoring/feedback loops |
| **S**haring / **L**ean (CALMS) | Knowledge sharing + eliminate waste, focus on value flow                | Learning from failures; iterative, agile-inspired processes |

CAMS stresses that tools alone fail without culture; CALMS adds Lean for waste reduction.

#### 2. DevOps Trinity (from Brian Dawson / CloudBees)  
Another clean lens from *Cloud Native DevOps with Kubernetes* sources: alignment across three planes.

- **People and Culture** — Collaboration, trust, shared goals (the human foundation)  
- **Process and Practice** — Agile/iterative workflows, CI/CD, feedback loops, monitoring  
- **Tools and Technology** — Shared, integrated tooling (IaC, monitoring, automation) that everyone can use


#### 3. The Three Axes from *Learning DevOps*  
Explicitly called out as the movement's foundation:

- **Culture of collaboration** — Multidisciplinary teams with one objective: fast value delivery  
- **Processes** — Agile-inspired, iterative: Planning → Development → CI/CD → Continuous Deployment → Continuous Monitoring (cyclical)  
- **Tools** — Unified across teams (Dev uses monitoring/security; Ops automates infra via IaC with Dev input)

These axes match CALMS/Trinity but emphasize the full lifecycle phases.

### Why This Matters for Your Journey
DevOps isn't "install Docker and call it done". It's cultural transformation starting at the top, propagating down. Success shows in faster releases, fewer outages, happier teams, and better business outcomes.



Methodologies, Agile, WaterFall

**Recommended reading for this module**:
- Chapters on "Getting started with DevOps" from *Learning DevOps (Second Edition)*
- "The Dawn of DevOps" / "Nobody Understands DevOps" from *Cloud Native DevOps with Kubernetes*
