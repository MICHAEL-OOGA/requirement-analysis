
# 📘 Requirement Analysis

---

## ❓ What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, and refining the **needs and expectations** of users and stakeholders for a software system. It’s one of the **most critical phases** of the Software Development Life Cycle (SDLC).

🔍 It ensures the development team understands **what the system should do**, **how it should behave**, and **what constraints must be considered** before writing any code.

---

## 💡 Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in building successful software solutions. Here’s why it matters:

- ✅ **Prevents Miscommunication**  
  Ensures that developers and stakeholders share a common understanding of project goals.

- 🚫 **Reduces Costly Mistakes**  
  Identifies potential issues early, avoiding expensive rework in later phases.

- 🧭 **Provides Clear Direction**  
  Serves as a roadmap for design, development, and testing teams to follow.

---

## 🛠️ Key Activities in Requirement Analysis

1. **📥 Requirement Gathering**  
   Collecting raw requirements from stakeholders through interviews, questionnaires, or observation.

2. **🗣️ Requirement Elicitation**  
   Engaging with users to clarify, interpret, and explore deeper needs and constraints.

3. **📝 Requirement Documentation**  
   Writing clear, organized requirement specifications that can be shared with the team.

4. **🔍 Requirement Analysis and Modeling**  
   Structuring and prioritizing requirements using diagrams or models (e.g., Use Case Diagrams, Flowcharts).

5. **✅ Requirement Validation**  
   Verifying that all documented requirements accurately represent stakeholder expectations.

---

## 🧾 Types of Requirements

### ✅ Functional Requirements

Functional requirements describe **what the system should do** — its core features and behavior.

**Examples in Booking Management System:**
- 🔐 Users can register and log in securely.
- 🔍 Guests can search for available properties by date and location.
- 🛏️ Hosts can list new properties.
- 📅 Guests can book properties and view booking history.
- 🧾 Admins can approve or delete listings.

---

### ⚙️ Non-functional Requirements

These define **how** the system performs — its quality, reliability, and constraints.

**Examples:**
- 🚀 The system must load within 2 seconds.
- 🔒 All user data must be encrypted.
- 📱 The site must work on mobile and desktop devices.
- 🌐 The platform must handle at least 10,000 users simultaneously.

---

## 🧩 Use Case Diagrams

### 🧠 What is a Use Case Diagram?

A Use Case Diagram is a **visual representation of system functionality** from the user's perspective. It highlights the interactions between **actors** (users or systems) and **use cases** (functions the system performs).

---

### 🎯 Benefits

- 🔍 Identifies user roles and how they interact with the system
- 🧭 Provides a high-level overview of system functionality
- 💬 Improves communication between technical and non-technical stakeholders

---

### 🖼️ Use Case Diagram – Booking System

Actors:
- 👤 Guest
- 🏠 Host
- 🧑‍💼 Admin

Use Cases:
- Register/Login
- Search Properties
- Book Property
- View Booking History
- List Property
- Manage Listings
- Approve/Remove Listings
- View Reports

📌 Diagram:

![Use Case Diagram](./alx-booking-uc.png)

---

## 🎯 Acceptance Criteria

### 📌 What is Acceptance Criteria?

Acceptance Criteria are the **conditions that a feature must meet to be considered complete and functional**. They ensure developers build what users expect.

---

### 🚀 Why it Matters

- ✅ Defines done
- 🔍 Makes testing easier
- 💬 Aligns expectations between devs and stakeholders

---

### 🧾 Example: Checkout Feature

**Feature:** Guest checks out from a booked property

**Acceptance Criteria:**
- ✅ User must be logged in
- ✅ Booking must exist and be valid
- ✅ Checkout is only available on or after the scheduled date
- ✅ System marks booking as "Completed" after checkout
- ✅ Confirmation and invoice are emailed to the guest


