## Automated-Trading-Platform-ATP---frontend-services

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

For checking the ATP you can go to the [ATP GUI web site](https://atp-flexgrid.tec.etra-id.com/), and try with one of these users:
  
| Role       | Username   |
|------------|------------|
| Aggregator | aggregator |
| DSO        | dso        |
| FMO        | fmo        |
| ESP        | esp        |
  
The <b>password</b> is the same as the username.

As it has been commented, depending on the role of the choosen user, you will be able to view one section or others. This table is defined in deliverable D6.2, section 3.3.

## ATP services

Each service or algorithm is accesible independently of the ATP GUI. You can call the services that run each algorithm following the following instructions.

### FMCT - UCS 1.1, UCS 1.2 and UCS 1.3

1. GO to [General FLEXGRID SWAGGER API](https://api.demo.etra-id.com/)
2. Fill the upper input next to button 'Explore' with 'https://resources.demo.etra-id.com/SWAGGER/flexgrid/UCS1.X.yaml'
3. Test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.

### FST - UCS 2.1

1. GO to [General FLEXGRID SWAGGER API](https://api.demo.etra-id.com/)
2. Fill the upper input next to button 'Explore' with 'https://resources.demo.etra-id.com/SWAGGER/flexgrid/UCS2.1.yaml'
3. Test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.


### FST - UCS 2.2

1. GO to [General FLEXGRID SWAGGER API](https://api.demo.etra-id.com/)
2. Fill the upper input next to button 'Explore' with 'https://resources.demo.etra-id.com/SWAGGER/flexgrid/UCS2.2.yaml'
3. Test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.


### FST - UCS 2.3

1. GO to [ICSS Stacked revenues SWAGGER API](https://stacked-revenues-api.flexgrid-project.eu/swagger/)
2. Identify with credentials given by ICSS (please contact to them):
    1. Click on button 'Autorize'
    2. When a window appears, fill inputs with data given by ICCS    
    3. Click on 'Autorize' in the window.
3. For both sites, test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.

### AFAT - UCS 4.1

1. GO to [General FLEXGRID SWAGGER API](https://api.demo.etra-id.com/)
2. Fill the upper input next to button 'Explore' with 'https://resources.demo.etra-id.com/SWAGGER/flexgrid/UCS4.1.yaml'
3. Test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.


### AFAT - UCS 4.2

1. GO to [ICCS Pricing SWAGGER API](https://pricing-api.flexgrid-project.eu/swagger/). You can use data returned by services in [ICCS Database services swagger](https://db.flexgrid-project.eu/swagger/).
2. Identify with credentials given by ICSS (please contact to them):
    1. Click on button 'Autorize'
    2. When a window appears, fill inputs with data given by ICCS    
    3. Click on 'Autorize' in the window.
3. For both sites, test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.


### AFAT - UCS 4.3

1. GO to [ICSS Flex Ofer SWAGGER API](https://flex-offers-api.flexgrid-project.eu/swagger/)
2. Identify with credentials given by ICSS (please contact to them):
    1. Click on button 'Autorize'
    2. When a window appears, fill inputs with data given by ICCS    
    3. Click on 'Autorize' in the window.
3. For both sites, test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.


### AFAT - UCS 4.4 PV Forecasting

1. GO to [General FLEXGRID SWAGGER API](https://api.demo.etra-id.com/)
2. Fill the upper input next to button 'Explore' with 'https://resources.demo.etra-id.com/SWAGGER/flexgrid/UCS4.4_PV_production.yaml'
3. Test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.


### AFAT - UCS 4.4 Market prices forecasting

1. GO to [General FLEXGRID SWAGGER API](https://api.demo.etra-id.com/)
2. Fill the upper input next to button 'Explore' with 'https://resources.demo.etra-id.com/SWAGGER/flexgrid/UCS4.4_PricesForecasting.yaml'
3. Test each service by expanding it (icon v):
     1. Click on button 'Try it out'. The different required inputs will become enabled
     2. Fill data. Correct format is described in each input.
     3. Click on "Execute"
     4. The response will be shown below
     5. Be patient, some services are slow, due the size of inputs or auxiliar data loaded.
