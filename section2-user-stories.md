# Section 2: User Stories and Tasks

---

## 1. Evidence of Learning

> **Definition:** A user story in Agile describes a software feature from the perspective of the person using it (*As a... I want... So that...*). Breaking these stories into daily sub-tasks gives developers, designers, and testers a clear roadmap of what needs to be built and tested.

### Visual Evidence: Trello User Story Cards

![Trello User Stories and Acceptance Criteria](./assets/user-stories-trello.png)
*Figure 2.1: Trello cards showing user stories, acceptance criteria, and sub-task checklists.*

---

### Core User Stories & Task Breakdowns (Student Eats)

#### Story 1: Student Registration & Role Selection
- **User Story:** *As a CPUT student, I want to create an account using my university email address so that I can log in safely and order food or list my homemade meals.*
- **Acceptance Criteria:**
  - Email input must validate `@mycput.ac.za` or `@cput.ac.za` domain strings.
  - Passwords must be hashed securely before saving to the MySQL database.
  - Role selection flags must distinguish between `buyer` and `vendor` accounts.
- **Team Task Breakdown:**
  1. [Designer - Lisakhanya] Wireframe and layout the React registration screen UI[cite: 8].
  2. [Developer - Luthando / Tshepang] Create Express POST endpoint `/api/auth/register`[cite: 8, 9].
  3. [Developer - Junior / Tshepang] Configure MySQL `users` table schema with role flags[cite: 8, 9].
  4. [Tester - Junior] Test email domain validation and password length edge cases[cite: 9].

![Registration Page Interface](./assets/registration-page-screenshot.png)
*Figure 2.2: User Registration screen with CPUT email validation.*

---

#### Story 2: Marketplace Search & Residence Filtering
- **User Story:** *As a hungry student living in residence, I want to browse available homemade meals and filter by my building so I can quickly find food nearby.*
- **Acceptance Criteria:**
  - Render interactive meal cards displaying meal price, vendor name, and residence pickup location.
  - Filter listings dynamically based on residence dropdown selection (e.g., Freedom Square, Catsville).
- **Team Task Breakdown:**
  1. [Designer - Lisakhanya] Build responsive meal grid components and visual tags in React[cite: 8].
  2. [Developer - Luthando] Build Express GET endpoint `/api/products` with filter parameters[cite: 9].
  3. [Developer - Tshepang] Connect backend API responses to React state management[cite: 8, 9].

![Marketplace Search and Filter Screenshot](./assets/marketplace-filter-screenshot.png)
*Figure 2.3: Student Eats marketplace meal discovery grid.*

---

#### Story 3: Cart Management & Pickup Checkout
- **User Story:** *As a buyer, I want to add meals to a shopping cart and pick my residence spot so I can confirm my order for pickup.*
- **Acceptance Criteria:**
  - Dynamic subtotal and total calculations when adding or removing items.
  - Checkout confirmation screen showing order summary, vendor details, and estimated pickup time.
- **Team Task Breakdown:**
  1. [Product Owner / Developer - Bradley] Design cart state logic and residence pickup selection[cite: 9].
  2. [Developer - Tshepang] Create Express POST endpoint `/api/orders` to persist order history[cite: 8, 9].
  3. [Tester - Junior] Run end-to-end checkout flow checks to verify order data accuracy[cite: 9].

![Cart and Checkout Screenshot](./assets/checkout-page-screenshot.png)
*Figure 2.4: Shopping Cart and Checkout preview screen.*

---

## 2. Structured Reflection

### Reflecting on End-User Perspective and Feature Prioritization

Focusing on user stories completely changed how our team worked together. At first, we were jumping straight into database tables and writing Express endpoints. Framing features around user needs kept us focused on what actually mattered to CPUT students sitting in residence.

#### What I Personally Learned:
1. **Building for Real Constraints:** Writing user stories forced us to think about safety and convenience early on. Requiring `@mycput.ac.za` email addresses meant buyers and sellers knew they were dealing with real campus peers[cite: 8].
2. **Clear Task Distribution:** Breaking big user stories into specific developer, designer, and testing tasks prevented us from stepping on each other's toes[cite: 8, 9]. Lisakhanya could focus on UI design while Junior set up test cases and the backend team worked on API integration[cite: 8, 9].
3. **Growth as a Developer:** Defining acceptance criteria before writing code made QA testing straightforward[cite: 9, 11]. We didn't consider a story "done" until it satisfied the exact criteria our Product Owner (Bradley) signed off on[cite: 9, 11].
