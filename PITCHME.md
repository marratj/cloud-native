# Cloud Native

### What does Cloud Native mean and what does it consist of?

Based on the blog series by Joe Beda

---

## Cloud Native Definition
 
There is no hard definition; mostly comprised of

 - Structuring teams, culture and technology
 - Efficient resource usage
 - Automation
 - Microservices
 - Observability



---
## Structuring teams, culture and technology

 - Work together and not seperated
 - Ops needs basic understanding of Dev and vice versa
 - Know what is the goal of the project
 - There is no space for assigning blame, work as a Team!   


--- 
## Efficient resource usage

 - Works hand in hand with Automation
 - Think about what you are doing
 - Be Lazy
 - Use tools as much as possible


---

## Automation

---

### Reduce

 - Error-prone manual tasks
 - Downtimes & callouts
 - Documentation effort

---

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

## Microservices

 - Set of loosely coupled application components
 - Shift away from big monolothic application blocks
 - Services talk to each other via APIs
 - Sort of Unix philisophy: "One tool for each task"

Note:
Aufmalen einer Microservices-Uebersicht
--- 

## Observability

Don't trust your systems will 'just run', gain insight to as much components as possible

---

### Do

 - Monitoring of components (cluster resources, application endpoints)
 - Consolidate and analyze logging centrally
 - Build proper rulesets for both monitoring and logging
 - Make them visible in a dashboard
 - Proactively step in before the shit hits the fan
 - And most importantly: Automate the above

---

### Don't

 - Wait for monitoring alerts to react to
 - Wait for callouts at night
 - Manually scan through logs on single servers
 - Just throw a problem over the wall to another team
 - Wait until someone takes a problem to you


---

## Thank you
