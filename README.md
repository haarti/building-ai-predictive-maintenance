# Automotive predictive maintenance

Final project for the Building AI course

## Summary

Project is about developing predictive maintenance functionality for automotives and related industry utilising gathered vehicle sensorial telemetry data and related service records, with the help of developed machine learning models. So in a nutshell, provide insights on the esimated time of failure for various vehicle components, and alert for maintenance before things will actually break.


## Background

When a vehicle breaks down & rendering itself useless, it typically creates an unpredicted & urgent issue on how now to get to the place one was going, how to get the potential cargo delivered to destination, how to get the vehicle to some service station, potentially with the help of some towing. So the day, and depending the situation, potentially several days are ruined. Also depending of the case, a failure in some inexpensive part may lead to a bigger & costly failure, potentially a hazarduous one.

Predictive maitenance with ai would actively monitor the health of the various components via the telementry data & models teached from the gatered historical data from other incidents as service records. By utilising this solution, the system would predict & alert on components that would need service in near future, and hereby potentially preventing more profound unpredicted incidents from happening.


## How is it used?

The solution would be operational in (near) real-time manner. The data gathering & intake would be periodic & configurable. Some of the processing could be done already at the vehicle (at edge), e.g. utilising some anomaly detection algorithms for selected sensorial data. Other data gathering would involve pushing the data to back-end (preferable some cloud environments) for further processing and more heavy-lifting processes & analytical/machine learning workloads.

The system would allow alerting user on selected events based on data & predictive models. Also the system would allow some visual back-end solution to explore vehicle status and mantenance predictions based on gathered data.

Solution could be also integrated to service operations, which would allow easy or even automatic reservation for nearest or preferred service point for needed maintenance.


## Data sources and AI methods
* Sensorial telementry data from vehicles
* Vehicle manufacturer's databases of historical data & service records

Potential algorithms to be tried out first:
* XgBoost for predictive models
* Random forest -type of algorithm for anomaly detection



## Challenges
Data availability for development might be challenging. Domain knowledge is also essential.

