# Telecom Capital Budgeting
This document serves to summarize the project scope and output from our engagement with a leading telecom company as part of the Opex Forecasting efforts.






## Project Scope
We were engaged by a leading telecom company to develop a solution that could forecast the cash and Opex impact of projects within the cell-site network over the next 3 years at the site-level of granularity.  During our project, we built a proof of concept solution to:

- **Guide operational decision-making and proactively address potential budget risks by providing target financial performance metrics**
  - Prior to this, the budget was managed centrally (national team), and targets did not exist at the market (local) levels, so local decision makers had a lack of accountability around operational decisions and their financial trade-offs

- **Compare current project plan with alternative scenarios to identify savings opportunities**
  - Varied build / decommission schedule
  -	Different tower configurations
  -	Vendor selection (for lease and backhaul)

- **Define business requirements and UX Design for full-scale solution**
  - Solution needs to store 2 years of historical costs including ~10 cost areas within the network
  - Target budget needs to exist at the market level of granularity and must extend for 3 years
  - Users need the ability to incorporate “What-if” (scenario) analysis based on common parameters (individual & bulk entry)
  - API integration with existing systems must be available


## Collaboration & Personnel Involved
We collaborated across various groups within the client’s organization to complete this project, including:

- Met with personnel from lease, backhaul, utilities, roaming, and R&M teams to gather data and to align on forecasting methodology
- Worked with Client’s Analytics team to understand SQL database for relevant datasets (planned projects within the network)
- Teamed with finance personnel to determine appropriate target setting methodology for regions and markets
- Interviewed market and regional directors (future end users) to socialize the proof of concept, refine use cases, and to define the functional requirements for the full solution
- Communicated weekly with client core team to track progress, escalate issues, and to discuss potential off the shelf solutions for full-scale implementation


## Project Highlights 
Throughout the project, I accomplished the following:

- Created ~25 alteryx workflows to perform full end to end cleaning, joining, and forecasting of data across 5 primary cost items (lease, backhaul, utilities, repair & maintenance, and roaming) 
- Built Power BI Dashboard to visualize baseline spend, financial targets, and forecasts for multiple scenarios 
- Led interviews with Market and regional directors to understand desired functionality within the solution and use cases within the organization


### Alteryx Workflow Diagram

![image](https://user-images.githubusercontent.com/71853253/195449208-978418f0-8806-4024-8ea9-548c2e14b442.png)

### Alteryx Workflow Example
![image](https://user-images.githubusercontent.com/71853253/195454231-38ae8ff5-b222-45a7-83e1-20b8d56ce574.png)

### Power BI Dasboard - Forecast and Target
![image](https://user-images.githubusercontent.com/71853253/195454283-7bdd0b07-61ba-45c9-a7a1-27bcb7c7f02a.png)

### User Personas and Use Cases
![image](https://user-images.githubusercontent.com/71853253/195454329-59b5e827-1fe2-40af-86f0-f3a25422ceb8.png)

### Market Research Findings (Off the Shelf Solution)
![image](https://user-images.githubusercontent.com/71853253/195454386-32431e5e-b4b6-4e8f-8bee-49d7a33c8b6f.png)






