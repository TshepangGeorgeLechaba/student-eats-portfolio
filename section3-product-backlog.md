# Section 3: Product Backlog

---

## 1. Evidence of Learning

> **Definition:** A product backlog is a single, prioritized list of all required features, technical enhancements, bug fixes, and infrastructure tasks needed for a product. It is owned by the product team and continuously evolves as customer needs and technical constraints change.

### Visual Evidence: Trello Product Backlog Board

![Trello Product Backlog Board](./assets/product-backlog-trello.png)
*Figure 3.1: Complete Product Backlog organized on Trello (October 2026).*

---

### Student Eats Prioritized Product Backlog

The table below reflects our core Product Backlog, managed on Trello using MoSCoW prioritization (Must have, Should have, Could have, Won't have) and ordered by business value for CPUT student buyers and residence vendors:

| Priority | Item ID | Feature / Module | User Story & Acceptance Summary | Target Sprint | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Must Have** | PB-01 | User Registration & Role-Based Auth | University email validation (`@mycput.ac.za`), bcrypt password encryption, role flag (`buyer`/`vendor`). | Sprint 4 & 5 | In Progress |
| **Must Have** | PB-02 | Cart & Residence Checkout | Shopping cart state, pickup location selection (e.g., Freedom Square), dynamic total calculation. | Sprint 7 | In Progress |
| **Must Have** | PB-03 | Seller Dashboard | Residence vendor interface to create/edit menu listings, manage inventory, and toggle stock availability. | Sprint 8 | Completed |
| **Should Have** | PB-04 | Marketplace Search & Filtering | Interactive meal cards filtered by residence venue, price range, and dietary tags. | Sprint 6 | Completed |
| **Should Have** | PB-05 | Real-Time Order Tracking | Order state pipeline (`Placed` $\rightarrow$ `Preparing` $\rightarrow$ `Ready for Pickup`). | Sprint 7 | In Progress |
| **Could Have** | PB-06 | System Documentation & Testing | Functional testing, UI testing, and final project documentation/presentation. | Sprint 9 & 10 | In Progress |

---

## 2. Structured Reflection

### Reflecting on Backlog Prioritization and Scope Management

Managing the *Student Eats* product backlog required balancing user-facing business requirements with technical infrastructure tasks and strict academic deadlines. Early in the project, our backlog included non-essential ideas such as integrated online payment gateways and complex automated chat systems.

#### Key Takeaways & Impact on Execution:
1. **Focusing on Minimum Viable Product (MVP):** Applying Agile prioritization allowed us to filter out low-priority items and focus on core value streams—specifically secure university authentication and seamless order checkout.
2. **Managing Technical Debt:** Maintaining a formal product backlog made technical maintenance tasks (such as MySQL schema migrations and Express CORS middleware configuration) visible alongside user stories. This prevented hidden technical bottlenecks during full-stack integration.
3. **Evolution of Learning:** Backlog refinement taught me that a product backlog is a living document, not a rigid plan. Re-evaluating sprint velocity and re-ordering backlog items ensured our team maintained steady progress toward our final deliverable.
