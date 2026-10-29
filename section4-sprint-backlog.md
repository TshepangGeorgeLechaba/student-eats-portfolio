# Section 4: Sprint Backlog

---

## 1. Evidence of Learning

> **Definition:** A Sprint Backlog is a real-time, actionable plan created by and for developers outlining the specific Product Backlog items selected for a sprint, along with the granular tasks required to achieve the Sprint Goal.

### Visual Evidence: Active Sprint Kanban Board

![Active Sprint Kanban Board](./assets/sprint-backlog-kanban.png)
*Figure 4.1: Active Sprint Kanban board showing To Do, In Progress, Testing, and Done lists (October 2026).*

---

### Active Sprint Task Board & Goal Alignments (Student Eats)

Below is an overview of our team's active Sprint Backlogs across critical development phases, managed on Trello using Kanban columns (*To Do*, *In Progress*, *Testing*, *Done*):

#### Sprint 4 & 5 Focus: User Authentication & Database Persistence
- **Sprint Goal:** Enable secure CPUT student and vendor registration, credential hashing, and role-based login.
- **Sprint Backlog Tasks:**
  - [x] Design React registration interface with real-time field validation.
  - [x] Configure MySQL `users` table schema with `role` flags (`buyer` vs. `vendor`).
  - [x] Implement Express backend API endpoint `/api/auth/register`.
  - [x] Implement Express backend API endpoint `/api/auth/login`.
  - [ ] Implement JWT session persistence and bcrypt password encryption.

#### Sprint 7 Focus: Shopping Cart & Residence Order Checkout
- **Sprint Goal:** Allow student buyers to add items to a persistent cart, select a residence pickup location, and finalize order checkout.
- **Sprint Backlog Tasks:**
  - [x] Build React Context provider for stateful cart management (add, remove, update quantities).
  - [x] Design checkout interface with residence pickup location dropdown.
  - [x] Implement dynamic subtotal and total calculations.
  - [x] Build order confirmation preview screen.
  - [ ] Connect checkout form submission to Express POST `/api/orders` backend route.

---

## 2. Structured Reflection

### Reflecting on Sprint Execution and Daily Task Alignment

Working with dedicated Sprint Backlogs provided our development team with structure and daily clarity throughout the *Student Eats* project lifecycle. While the Product Backlog represented our high-level vision, breaking work into two-week sprint goals kept daily execution focused and realistic.

#### Key Takeaways & Impact on Execution:
1. **Maintaining Sprint Goal Focus:** Defining clear sprint goals prevented feature creep during active sprint cycles. When secondary feature ideas arose, having an established sprint backlog allowed us to protect our current sprint velocity and defer extra tasks to future sprints.
2. **Real-time Progress Transparency:** Visualizing our task pipeline on Trello allowed all team members—from frontend developers to QA testers—to identify work status and spot bottlenecks instantly.
3. **Evolution of Learning:** As a full-stack developer, I learned that a sprint backlog requires continuous active management. Breaking down complex full-stack features into smaller sub-tasks (under 4 hours of effort) significantly improved our task completion rate and made daily stand-up reporting much more actionable.
