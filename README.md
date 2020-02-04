# CarRepairTrackerCapStone

Car Repair Tracker Application - Analogous to a pizza ordering and tracking app. 

For our final capstone, we were tasked with creating an app that could communicate the status of a car dropped off at the shop to be repaired. The customer could create their own account, attach a car to their profile and create a repair request for the car. The mechanic would then see the order, and fill in the repair details with line items that included cost, and estimated time to repair. The customer would then see the line items for the repair request and accept or decline each item to get an ETA and estimated total cost. The mechanic would then perform the repairs that were OK'd by the customer and update the repair order as complete once all repairs were finished.

We started the project by planning the UI flow for the app and for each account role (customer, employee(mechanic) and administrator) and then started working on the project in vertical slices. I designed the ERD table for the app and then worked on the Data Access Layer in MVC as that's where I felt my strongest talents lied. As the team worked through the app, I pitched in on various facets of the project. I did some front-end features as needed, refactored the code after it was discovered the database tables needed to be reworked and refactored some of the associated code.

Our instructor was the product owner and we consulted him as needed for clarification on the app. We also practiced the agility methodology with daily stand up meetings in the morning detailing our individual progress in the percentage of app feature completed, any roadblocks stopping us and what we wanted to accomplish that day. The team also had weekly retrospectives to review the overall project together

WorkFlow:
1) Customers can create an account, then enter vehicle description and then problem description. 
2) Employee (Mechanic) can then check the vehicle in, add line items to vehicle issue, along with estimated cost and time to completion.
3) Customers can then accept or decline each individual line item and get updated cost and completion date.
4) The employee can update the vehicle as line items are completed and mark as complete with a date for pickup for the user to see when work finished is finished and paid for. (Payment assumed to be handled through a separate system.)

MS SQL DB for backend, MVC for Business Logic and Data Manipulation, JS Vue Front End Presentation

MS SQL Back end for user roles, user accounts, vehicles, incident and incident items.

C# MVC used for middleware, BI.

Vue frontend for user presentation with responsive design. Mobile View for the customer, standard desktop view for employee/admin per Product Owner.
