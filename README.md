# Automated-Trading-Platform-ATP---frontend-services

The ATP is an entry point to the FLEXGRID services. It is a web application written in meteor, which is able to show different views according to the role of each logged user. Besides, the application allow users to make different actions, depending on his/her role. We consider four main user roles (aggregator, ESP, FMO and DSO) corresponding to four main agents in electricity market.

On one hand, the application interacts with the services in FLEXGRID:
 * It calls to the APIs that envelope the different algorithms defined for FLEXGRID, that is, it is able to run remotely all the algorithms in FLEXGRID
 * It shows results of those executions and,
 * It maintains and historical of executions, so user can review the result of any of previous executions.

On the other hand, the application is able to activate a market clearing:
 * Users create FlexRequests and FlexOffers
 * Users can watch charts representing FlexRequest vs FlexOfers
 * Users can activate a market clearing

Finally, there was an special user role, the administrator. This administrator can configure external services and email addresses, in order to be notified when a market clearing activation is produced.

## Use of the ATP for demo pourpouses

For checking the ATP you can go to the [ATP GUI web site](https://atp-flexgrid.tec.etra-id.com/), and try with one of these users (the password is the same as the username):
  
| Role       | Username   |
|------------|------------|
| Aggregator | aggregator |
| DSO        | dso        |
| FMO        | fmo        |
| ESP        | esp        |
  
