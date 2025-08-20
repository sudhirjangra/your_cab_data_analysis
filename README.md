# YourCab Dataset Description

## Context
The dataset comes from **YourCab**, a Bangalore-based city-specific cab company that operated around **2013**—before app-based services like Uber or Ola were popular.  
Customers booked cabs through:
- Desktop website  
- Mobile website  
- Call center  

> Note: There was **no mobile app** for this service.

---

## Business Problem
Cancellations due to **car unavailability** caused penalties for the company.  
- The **later** a cancellation occurred, the **higher the penalty** paid to the customer.  
- These cancellations resulted in both **financial loss** and **reputation damage**.  

**Objective**:  
Build a **predictive model** that identifies bookings at high risk of cancellation (due to car unavailability) **before confirmation**, so the company can avoid accepting them.

---

## Scope of Data
- Focuses only on **cancellations due to company-side issues** (car unavailability).  
- Does **not** include customer-driven cancellations.  
- Covers different **travel types**:  
  - Hourly rentals  
  - Point-to-point trips  
  - Long-distance trips  

---
