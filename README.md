# **T3A2-A - Full Stack App (Part A): Customer Credit Application**  
**Name:** Wade Doolan  
**Student number:** 12678  

---  

## **R1: Application description**   

### Purpose  
The purpose of this application is to provide a secure platform for a retail store to facilitate a customer credit system. A retail store might use a customer credit system to:  

- Rewards its customers for buying a certain number of goods, spending a particular amount in the store over a set time, winning a competition or buying a particular item or category of item the store is trying to clear.
- Track its customers spending habits to gain useful insights

Importantly, the application allows a retail store to track it's overall outstanding store credit and associated liabilities. 


### Functionality/features  

Essentially, the application allows a retail worker/store owner to add or remove customer credit for individual customers. For example, if a customer purchases a particular item the retailer can choose to add credit to their name, so the customer can use it at a later stage (like an incentive to came back into the store again).  Also, the retail worker/store owner can create credit categories (e.g. credit towards shirts only or shoes only or general store credit). A dollar value can be placed on the different categories of credit. The main features/functionality include:  

- An admin dashboard through which a retail worker/store owner:  
    - Is able to configure the categories of store credit and the dollar value of the store credit.
    - Can see metrics for outstanding credit, number of customers with credit, outstanding amount of credit in dollar value.
    - Can view, add, delete and update customer details, including their current store credit and credit categories.
    - Can add or remove customer credit.
    - Can update their own information
        
### Target audience   

The application is targeted towards retail store owners, interested in tracking customer credit. The application can be used in any retail environment. It can also be used in a hospitality environment where customer credit is used for purchases. For example, caf&#233;s.


### Tech stack

The application will be built using a M.E.R.N stack. Specifically:
- M: MongoDB database tier - a NoSQL document database.
- E: Express.js server tier - a web framework the works on a Node.js server.
- R: React.js top tier (frontend)- a JavaScript framework used to build client side, dynamic applications.
- N: Node.js server tier - a high-end JavaScript web server.  

(MongoDB, 2022) 

--- 

## **R2: Dataflow diagram** 


![dataflow diagram](./docs/Dataflow%20diagram%20-%20customer%20credit%20%20app.png)



--- 

## **R3: Application architecture diagram**  

![application architecture diagram](./docs/Application%20architecture%20diagram.png)

(Digikull.com, 2022)  



--- 

## **R4: User stories**  

- As a retail store manager, I want my staff to be able to log into a secure environment, so that we can track and update store credit for our customers.  
- As a retail store manager, I want to be able to set up my own categories of credit, so I can incentivise customers to purchase particular items.  
- As a retail store manager, I want to be able to see the total outstanding credit for my store, so I can calculate my current liabilities.  
- As a retail store manager, I want to be able to add a dollar value per credit point for each category, so I can ultimately see outstanding credit by category.   
- As a retail worker, I want to be able to add a new customer to the system, so I can add or remove credit for them.  
- As a retail worker, I want to be able to see the current credit balance for a customer, so I can inform the customer how much credit is available for a particular category.  
- As a retail worker, I want to be able to add additional credit points for a customer for a particular category, so I can reward the customer for spending a certain amount.  
- As a retail worker, I want to be able to remove credit points for a customer for a particular category, so I can record when a customer has used credit towards a purchase.  
- As a retail worker, I want to be able to see a list of all store customers, to help me find a customer.  
- As a retail worker, I want to be able to take a profile picture of my customer and add it to their account, so I can identify my customers.  
- As a retail worker, I want to be able to search for a particular customer using their email address or phone number, so I can easily find a customer in the system.  


--- 

## **R5: Wireframes**  

### Mobile design

![mobile design](./docs/Mobile%20design.png)

### Tablet design

![tablet design](./docs/Tablet%20design.png)

### Desktop design

![desktop design](./docs/Desktop%20design.png)
--- 

## **R6: Project management** 

Trello has been used to plan the development of the application. The kanban board shown in the Trello page below will be used throughout the development phase (Part-B). The Backlog has already been populated for first part of the development phase (the frontend). The backlog for the backend development phase will be populated towards the end of the frontend development phase.

![trello](./docs/Trello%20screenshot.png)


My Trello board can be tracked via the link below. 

https://trello.com/invite/b/iSEVu7Nc/ATTI532665fb54871f4f08a9a9b8efcd2c6e6DCDE062/full-stack-application-customer-credit-app

---

## References 

Reference list Digikull.com. (2022). Digikull - Top 10 Skills to Become a MERN Full-Stack Developer in 2022 Blog. [online] Available at: https://digikull.com/top-10-skills-to-become-a-mern-full-stack-developer-in-2022-blog.html [Accessed 10 Feb. 2023].

MongoDB. (2022). What Is The MERN Stack? Introduction & Examples. [online] Available at: https://www.mongodb.com/mern-stack [Accessed 11 Feb. 2023].










