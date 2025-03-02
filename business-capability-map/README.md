# Business Capability Map

## 1. Introduction
The **Business Capability Map (BCM)** is an enterprise architecture methodology that systematically represents the capabilities required for an organization to function. Instead of illustrating business processes or organizational units, BCM focuses on the fundamental abilities a company needs, facilitating alignment between IT and business strategy.

---
## 2. When Would You Use Business Capability Maps?
Business capability maps help organizations understand their organization’s infrastructure (systems, resources, processes, and structures) and market position, especially during key events like **mergers**, **digital transformations**, **leadership changes**, or before **major investments**. They identify overlapping, redundant, or unique capabilities, enabling better resource allocation and decision-making. Mapping capabilities provides leadership with clearer insights, supporting tasks like application rationalization and Standard Operating Procedure (SOP) revisions, which improves efficiency, continuity, and success. However, while the map itself may not provide immediate insights, it can highlight areas worth further investigation, revealing strengths or weaknesses.

## 3. Definition of Business Capability
A **Business Capability** is a specific ability an organization possesses to achieve a business objective. Capabilities are:
- **Stable**: They do not change frequently with shifts in the business environment.
- **Implementation-independent**: They are not tied to specific processes or technologies.
- **Hierarchical**: High-level capabilities can be further broken down into sub-capabilities.

---
## 4. Structure of a Business Capability Map
A Business Capability Map is a **hierarchical model** that organizes capabilities into three levels:

### **Level 1: Strategic Capabilities**
These define the core operational areas of the organization, such as:
- **Product & Service Management**
- **Customer Relationship Management**
- **Financial Management**
- **Risk Management**

### **Level 2: Core Business Capabilities**
These break down strategic capabilities into functional business areas, such as:
- **Lending Capability**
  - Credit Assessment
  - Collateral Management
  - Contract Management

- **Financial Management Capability**
  - Account Management
  - Transaction Processing
  - Risk Analysis

### **Level 3: Detailed Capabilities**
Sub-capabilities cover specific business functions, for example:
- **Collateral Management**
  - Collateral Registration
  - Collateral Valuation
  - Collateral Monitoring
  - Collateral Enforcement

---
## 5. Business Capability Map Example (Banking Lending)
The following table presents an example of a **Business Capability Map** for the banking lending sector:

| **Strategic Capability** | **Core Business Capability** | **Sub-Capabilities** |
|--------------------------|----------------------------|----------------------|
| Lending | Credit Assessment | Risk Analysis, Rating |
|  | Collateral Management | Registration, Valuation, Monitoring, Enforcement |
|  | Contract Management | Loan Agreement Handling, Modifications |
| Financial Management | Account Management | Account Opening, Freezing, Closure |
|  | Transaction Processing | Payments, Withdrawals, Refunds |

---
## 6. Business Capability vs. Business Process
It is important to distinguish between **Business Capability** and **Business Process**:

| **Business Capability** | **Business Process** |
|------------------------|--------------------|
| *What an organization can do* | *How an operation is performed* |
| Stable, changes rarely | Dynamic, changes frequently |
| Descriptive in nature | Execution-oriented |
| Independent of technology | Implementation-dependent |

---
## 7. Business Capability and IT
The Business Capability Map is not only crucial for business alignment but also for IT strategy. Key connections between BCM and IT include:
- **Service Domain Mapping**: IT services are mapped to Business Capabilities.
- **DDD (Domain-Driven Design) Alignment**: Business Capabilities help define Bounded Contexts in the DDD model.
- **Microservices Design**: Business Capabilities guide the structuring of microservices.

---
## 8. Summary
The **Business Capability Map** is an essential tool for aligning business and IT strategies. It helps organizations understand **what** they need to achieve without focusing on **how** to implement it. Its hierarchical structure ensures that business and IT developments are well-organized and scalable.
