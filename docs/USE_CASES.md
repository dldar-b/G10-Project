# 🧩 Use Case Modelling

## Role 3 – Use Case Modeller (Omar Emad)

### Actors:
- **Customer** – Requests home services.  
- **Service Provider** – Offers services like cleaning, plumbing, or electrical work.  
- **Administrator** – Manages system data and users.

### Main Use Cases:
1. Register a New Account  
2. Book a Service  
3. Chat with Service Provider  
4. Rate and Review a Provider  

---

## Example Use Case – *Book a Service*

**Goal:**  
Allow the customer to request and schedule a service.  

**Preconditions:**  
- The customer must be logged in.  
- The provider must have available slots.  

**Main Flow:**  
1. Customer searches for a provider.  
2. Selects a service and date.  
3. Confirms the booking.  
4. System stores the booking in the database.  

**Postconditions:**  
- Booking is saved successfully.  
- Provider receives a booking notification.  

**Alternative Flow:**  
- If the provider is unavailable, the system suggests another provider.  

---

📎 *Use Case Diagram:*  
(Pthe diagram image in the folder `docs/assets/` and the name its `use_case_diagram.jpg`)

Example reference:  
`![Use Case Diagram](assets/use_case_diagram.jpg)`
