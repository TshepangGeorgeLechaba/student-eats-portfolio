# Section 4: Sprint Backlog

---

## 1. Evidence of Learning

> **Definition:** A Sprint Backlog is a real-time, actionable plan created by and for developers outlining the specific Product Backlog items selected for a sprint, along with the granular tasks required to achieve the Sprint Goal[cite: 20].

### Active Sprint Task Board & Goal Alignments (Student Eats)

Below is an overview of our team's active Sprint Backlogs across critical development phases, managed on Trello using Kanban columns (*To Do*, *In Progress*, *Testing*, *Done*)[cite: 16, 20]:

#### Sprint 4 & 5 Focus: User Authentication & Database Persistence
- **Sprint Goal:** Enable secure CPUT student and vendor registration, credential hashing, and role-based login[cite: 16].
- **Sprint Backlog Tasks:**
  - [x] Design React registration interface with real-time field validation[cite: 16].
  - [x] Configure MySQL `users` table schema with `role` flags (`buyer` vs. `vendor`)[cite: 16].
  - [x] Implement Express backend API endpoint `/api/auth/register`[cite: 16].
  - [x] Implement Express backend API endpoint `/api/auth/login`[cite: 16].
  - [ ] Implement JWT session persistence and bcrypt password encryption[cite: 16].

#### Sprint 7 Focus: Shopping Cart & Residence Order Checkout
- **Sprint Goal:** Allow student buyers to add items to a persistent cart, select a residence pickup location, and finalize order checkout[cite: 16].
- **Sprint Backlog Tasks:**
  - [x] Build React Context provider for stateful cart management (add, remove, update quantities)[cite: 16].
  - [x] Design checkout interface with residence pickup location dropdown[cite: 16].
  - [x] Implement dynamic subtotal and total calculations[cite: 16].
  - [x] Build order confirmation preview screen[cite: 16].
  - [ ] Connect checkout form submission to Express POST `/api/orders` backend route[cite: 16].

---

## 2. Structured Reflection

### Reflecting on Sprint Execution and Daily Task Alignment

Working with dedicated Sprint Backlogs provided our development team with structure and daily clarity throughout the *Student Eats* project lifecycle[cite: 20]. While the Product Backlog represented our high-level vision, breaking work into two-week sprint goals kept daily execution focused and realistic[cite: 16, 20].

#### Key Takeaways & Impact on Execution:
1. **Maintaining Sprint Goal Focus:** Defining clear sprint goals prevented feature creep during active sprint cycles[cite: 20]. When secondary feature ideas arose, having an established sprint backlog allowed us to protect our current sprint velocity and defer extra tasks to future sprints[cite: 20].
2. **Real-time Progress Transparency:** Visualizing our task pipeline on Trello allowed all team members—from frontend developers to QA testers—to identify work status and spot bottlenecks instantly[cite: 16, 20].
3. **Evolution of Learning:** As a full-stack developer, I learned that a sprint backlog requires continuous active management[cite: 20]. Breaking down complex full-stack features into smaller sub-tasks (under 4 hours of effort) significantly improved our task completion rate and made daily stand-up reporting much more actionable[cite: 20].
