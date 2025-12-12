# UML Diagrams (Assignment 4) – images folder

This folder contains the UML diagrams for the **HomeService App (All Service Company)**.  
These images are part of our GitHub documentation and they represent the **system design blueprint** created in **Assignment 4**.  [oai_citation:1‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

We use these diagrams to describe:
- **System interactions** (Use Case + Sequence)
- **System structure** (Class)
- **System behavior over time** (State)
- **Logical architecture** (Component)
- **Physical deployment** (Deployment)  [oai_citation:2‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)


## Team roles (who did what)

- **Omar Emad**: Use Case Diagram + Sequence Diagrams  [oai_citation:3‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)  
- **Abdulla Beston**: Class Diagram  [oai_citation:4‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)  
- **Dldar Bahri**: State Diagram  [oai_citation:5‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)  
- **Mahmud Kosrat**: Component Diagram  [oai_citation:6‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)  
- **Rekar Mhamad**: Deployment Diagram  [oai_citation:7‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)  


## Diagram list (current filenames)

> Note: The filenames are currently generic (Picture1..).  
> We kept them as-is to avoid broken links. Renaming is optional.

### 1) Use Case Diagram — (Omar Emad)
**File:** `Picture1.jpg`  
This diagram shows interactions between the actors (Customer, Service Provider, Admin) and the system.  
It summarizes key functions such as booking, payments, messaging, listing management, and admin controls.  [oai_citation:8‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

![Use Case Diagram](Picture1.jpg)


### 2) Class Diagram — (Abdulla Beston)
**File:** `Picture2.jpg`  
This diagram describes the structural model of the system.  
It includes user hierarchy, service listings, bookings, payments, reviews, notifications, and availability models, with relationships and attributes.  [oai_citation:9‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

![Class Diagram](Picture2.jpg)


### 3) Sequence Diagram 1 – Book a Service — (Omar Emad)
**File:** `Picture3.png`  
This sequence explains the booking process.  
It shows how the customer interacts with the Web App and how the app communicates with Booking Service, Service Provider, Notification Service, and Payment Gateway.  [oai_citation:10‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

![Sequence Diagram – Book a Service](Picture3.png)


### 4) State Diagram – Booking Lifecycle — (Dldar Bahri)
**File:** `Picture4.png`  
This state diagram models the booking lifecycle from **Pending → Confirmed → InProgress → Completed / Cancelled** to control correct transitions.  [oai_citation:11‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

![State Diagram – Booking Lifecycle](Picture4.png)


### 5) Component Diagram — (Mahmud Kosrat)
**File:** `Picture5.jpg`  
This diagram presents the logical architecture of the system.  
It separates the client layer, backend components, database, and external services such as payment and messaging gateways.  [oai_citation:12‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

![Component Diagram](Picture5.jpg)


### 6) Deployment Diagram — (Rekar Mhamad)
**File:** `Picture6.jpg`  
This diagram shows the physical deployment environment.  
User devices access the Web Server, which communicates with the Application Server and Database Server, with external integrations.  [oai_citation:13‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)

![Deployment Diagram](Picture6.jpg)


### 7) Extra image (if needed)
**File:** `Picture7.jpg`  
This image is currently kept as an extra diagram/screenshot used during design.  
(If we decide it is a duplicate, we will remove it later to keep the folder clean.)

![Extra](Picture7.jpg)


## Why these UML diagrams were chosen
We selected these UML diagrams because together they provide a complete system design:
- Use Case + Sequence diagrams explain **what happens and how users interact**.
- Class diagram explains **what entities exist and how they relate**.
- State diagram controls **how booking status changes**.
- Component diagram clarifies **software modules and dependencies**.
- Deployment diagram clarifies **where the system runs physically**.  [oai_citation:14‡G10-Assignm4[1].docx](sediment://file_0000000026e471fdb809098ffd1db1a8)
