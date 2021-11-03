---
title: Best Practices for Implementing Automation Projects 
tags: Talk, Automation, Ansible
description: This is intended as a slidedeck to collaborate over Automation best practices
---

## Best Practices for Automation Projects
<!-- Put the link to this slide here so people can follow -->
slide: https://hackmd.io/@kvegh/automation_best_practices/

---

### TL;DR: the intention here is to collect key strategies to focus on during automation projects

---

<!-- .slide: style="font-size: 18px;" -->

#### #1 Minimize the number of automation frameworks
***
As far as possible, if you can, then to one single tool. The more different teams speak the same markup language, the better the collaboration. **Maximize collaboration**. 

/* It's easy to get distracted to highly focused tools for specific usecases, however complexity doesn't pay off, and different tools grow the maintenance effort of the automation framework exponentially. */ 

IOW: Aim for joining automation efforts **across teams**, in all IT Stack Layers. 

---

<!-- .slide: style="font-size: 18px;" -->

#### #2 Aim for [Infrastructure as Code](https://https://www.redhat.com/en/topics/automation/what-is-infrastructure-as-code-iac)
***
Describing your infrastructure with versionable code allows you to: 
* Document and review changes in the Deployment code (also, retrospectively)
* Version Infrastructure definition releases
* Rebuild Infrastructure any time (allowing Just-in-time-DR and multicloud migrations)
* Regularly validate running configuration 

---

<!-- .slide: style="font-size: 18px;" -->

#### #3 Aim for lowest requirements on the managed node side
***
Deploying agents can be both undesired (updates, security) and/or even not possible (hypervisors, cloud instances, network elements, application instances...) 

Use standard connections, APIs instead. 

---

<!-- .slide: style="font-size: 18px;" -->

#### #4 Research the Vendor support for technologies to be automated
***
No need to build everything from scratch. 

In order to efficiently automate different usecases, ensure that the technology vendor itself is involved in creating the automation content or best practices for their own solutions. 

---

<!-- .slide: style="font-size: 18px;" -->

#### #5 Define and DOCUMENT [the usecases to be automated](https://http://people.redhat.com/kvegh/slidedecks/Finding%20the%20right%20automation%20usecases%20to%20start%20with%20-%20German+English.pdf) VERY CLEARLY 
***
Automation projects stand and fall with the usecase definitions - and the focus being kept on them. Prioritize, and plan the timeline of rolling them out. 

---

<!-- .slide: style="font-size: 18px;" -->

#### #6 Automated usecases shall be consumable in a self-service manner
***
Have interfaces defined where users/customers with the right roles can trigger automated jobs, preferably without human intervention. 

---

<!-- .slide: style="font-size: 18px;" -->

#### #7 Auditability
***
The outcome of all triggered automation jobs shall be centrally collected for review and/or autditing purposes. Consider implementing an auditor/reviewer role. 

---

<!-- .slide: style="font-size: 18px;" -->

#### #8 Automated usecases shall be consumable in a self-service manner
***
Have interfaces defined where users/customers with the right roles can trigger automated jobs, preferably without human intervention. 


---

<!-- .slide: style="font-size: 18px;" -->

#### #X Automated usecases shall be consumable in a self-service manner
***
Have interfaces defined where users/customers with the right roles can trigger automated jobs, preferably without human intervention. 

