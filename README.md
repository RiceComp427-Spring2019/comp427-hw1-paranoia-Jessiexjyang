# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Xuejuan Yang

_Student NetID_: xy25

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: As head of the TSA, you set the rules for screening passengers at airport checkpoints.
- Assumptions:

  The main purpose of TSA is to make sure the security of people and the airport.   The import way is to use the screening  machine to check whether the belongings are safe.
- Assets:

  The screening machine is at the central power of the checkpoint. We need to make sure it's performing as expected, providing useful and accurate information and covering various types of items to be scanned:
  - The screening machine should be able to detect any types of items, covered by any non-metal materials of filled-into any regular items. The screening machine should also be ruled to stop and make signals to the item in case it can't make the decision.
  - The screening machine may be serving for a long time and can't recognize new items or defend new attacks.
  - The screening machine usually runs for a long period of time. Some functionality may not be 100% accuracy after a long-time run.
- Threats:

  As the screening machine is of the central power, attackers can come up with various ways to bypass/fool the machine. Another threat may come from the outdated functionality and detection ability:
  - Attackers may use think, reflective or special non-metal materials to cover dangerous items.
  - Attackers can also put/fill non-metal but prohibited items into normal items.
  - Items produced by new techniques may not be identified and detected by old (or even not old) screening machines.
- Countermeasures:

  It is very important to check its functionality overtimes, making sure the expected and unexpected behaviors given various items:

  - An up-to-date list of items should be predefined and hard-coded into the machine: laptop, camera, smartphones, tablets, etc. 
  - In case the list can't cover some newly produced items, a set of general rules should be specified try to cover any unknown or unexpected goods.
  
  The above ideas should be useful and cost-effective. Even it's not cost-effective, we still need to pay for the cost to gain the safety gain.
  Pressure test and extreme test are also of great necessity: 
  - Periodically make the machine running for consecutive hours (24 hours as an example) to make sure it can still perform well with the same high precision. 
  - Put a huge number of items on the luggage moving belt. Super-heavy items, heavily covered suitcases, tiny and light items are also good for testing.

  In case of an outage,
  - back-up machines are important and should be ready to serve the checkpoint at any time.     
  - Backup security staffs and workers should be scheduled by human resources as well. 

  The above methods should be useful and cost-effective. Regular maintenance, routine check, and backup plans should be the industry standard in any area. Extra cost might come from the backup security staff since they don’t have much work to do if there is no outage.


## Problem 2
- Scenario: As head of IT for an international law firm, you are responsible for a document management system; some documents stored there are about sensitive legal, financial, or political matters.
- Assumptions:

  This document management has various types of documents. Some of them are available for all people, while some are private.  There will be a reading history for each reader. 
- Assets:

  The most important feature for a document management system is providing the requested content correctly and timely:
  - The full document should be retrieved and present to the reader. Documents need to be well indexed for search purpose. We don't expect missing or partial document being served. 
  - Documents also need to be well maintained for time-sensitive requests. Retrieving a document shouldn't take a long and unexpected time.
  
  Storage safety is similar to the aforementioned availability in some aspects, while it has additional requirements. Before requesting and reading documents, we need to properly keep and store the documents:
  - Storage should be well-maintained and capable to store future documents (in terms of document size)
  - Duplication and backups are needed in case one of the storage units is not working
  - Storage system should be guarded against theft or damage.



- Threats:

  The following can be the list of threats which may impact the document management system in terms of availability. Note that not all of them are intentional or from an "attacker". Some threats can occur by poor management or purely by nature:
  - There can be a large number of documents belonging to the same category. When retrieved by category, some documents may be missing due to the lack of index or improper index.
  - Due to the bulk volume of documents, retrieving a relative old document may take a long time. Sometimes the waiting time can't serve for the requirement, thus no information is served for the request. For example, newly produced documents may be stored in "hot" storage while old or non-popular documents are kept in "cold" storage.
  - The system itself may be suspending or stop serving documents due to durability or just system bugs.
  
  Similar to other assets, storage safety is also under threats, either intentional or just by nature:
  - The storage space is always limited and pre-set. We can't expect to have unlimited space. An incoming batch of documents with a relatively large size may not be able to put into the system.
  - A storage system may be broken or dead. It can from the power breakdown, the temperature, the hardware durability, etc.
  - The storage unit can be damaged intentionally by attackers, while can also suffering from natural disasters (storm, earthquake, etc.). It can also be stolen by competitors under some cases.
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

## Problem 3
- Scenario: Your choice (give a brief explanation)
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph 
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

