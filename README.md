# Calculate Client Security Hash

This project is conducted within ACME Systems Inc. , Finance and Accounting Department. The Objective of this process automation is intented to

- Deliver fast processing
- Reduce redundant activities
- Improve overall performance and reliability

## Process Description

- Step.1 Open ACME System 1 Web Application
- Step.2 Log into application with required username and password
- Step.3 Access the work items menu in the dashboard
- Step.4 For each activity of type WI5 perform the following steps
- Step.5 Open the details page and retrieve the Client Information Details
- Step.6 Open SHA 1 Online webpage
- Step.7 Enter ClientID-ClientName-ClientCountry details
- Step.8 Retrieve Client Security Hash value
- Step.9 Go back to Client Information Details and update with hash value as comment and set status value to "Completed"
- Step.10 Continue with next activity with type WI5

## Note

- Orchestrator Asset is used to store Credentials
- Robotic Enterprise Framework is used(REFramework)
