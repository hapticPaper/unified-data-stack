# unified-data-stack

## Components
* Load Balancing
* Authentication and Authorization 
* Session caching
* Internal vs External and Service APIs
* Standard communication objects for services
* SDK to perform use the api and perform <i>loop</i> queries
* Standard request and response implementation across services
* Request management, queue, queue management, error msg creation (like `429`)
* Delivery System - all data returned will be centrally governed (allows things like bypassing the entire level of <i>processing</i> APIs instead returning the last cached response)
* Abstracted delivery system allowing additional/different delivery mechanisms.
* Connector foundation (supporting the addition of n data sources or consumers)
* 4 Sample request and delivery methods:<br>
  - Database Queries<br>
  - Local `/` files <br>
  - In-memory cached<br>
  - Externally persisted (`s3:`)
* Sample Consumers
  - Direct User API call to data source
  - Web Application
  - SDK packaged requests including rate limiting







Template full-stack data service - Load Balancing -> Canonical Data Usage
