# Cloud Native

### What does Cloud Native mean and what does it consist of?

Based on the blog series by Joe Beda

---

## Cloud Native Definition
 
There is no hard definition; mostly comprised of

 - Structuring teams, culture and technology
 - Automation
 - Observability
 - Microservices
 - Efficient resource usage


Note:
Speaker notes go here

---

## Microservices

 - Set of loosely coupled application components
 - Shift away from big monolothic application blocks
 - Services talk to each other via APIs
 - Sort of Unix philisophy: "One tool for each task"

Note:
Aufmalen einer Microservices-Uebersicht

--- 

## Automation

### Reduce

 - Error-prone manual tasks
 - Downtimes & callouts
 - Documentation effort


### Gain 

 - Faster deployments
 - Better disaster recovery
 - Sleep at night

---

## Containers and Clusters

---

### Containers 

 - Automate packaging
 - Make applications portable through environments (dev/test/prod)
 - Make deployments atomic (as opposed to traditional CM)
 - Enhance resource utilization (no more a full VM per application)

---

### Clusters (K8s)

 - Automate on which resource to run applications
 - Reduce the need for manual bookkeeping (which app runs on which server?)
 - Provide a consistent and quick way for deployments

 --- 

## Observability

Don't trust your systems will 'just run', gain insight to as much components as possible

 - Monitoring of components (cluster resources, application endpoints)
 - Consolidate and analyze logging centrally
 - Build proper rulesets for both monitoring and logging
 - Make them visible in a dashboard
 - And most importantly: Automate the above
