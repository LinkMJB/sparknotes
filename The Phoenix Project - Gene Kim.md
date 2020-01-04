* Character introductions
  * Bill - Main character, forcefully promoted to VP of IT, from Midrange Tech Manager
  * Steve - CEO
  * Wes - Distributed/Modern System Lead
  * Sarah - Tech Lead on Pheonix Project
  * Chris - Lead Developer on Phoenix Project
  * Patty - NOC and Service Desk lead -- the face of helpdesk
  * John - Security Team Lead

* Background:
  * Internal efficiency warring
  * Ineffective Change Authorization Board (CAB)
  * Security regularly breaking systems during patching
  * Unexplained, unplanned outages to storage and network systems
  * Phoenix Project held as the highest priority project, delays considered to be unacceptable
  * P62 - SOX audit finds several critical security issues
  * P66 - Recent security patch that caused outage found to be ineffective/unrelated to SOX improvement that was noted as the reason for the patch
  * P66 - Former CIO kept accepting risks of audit findings, instead of fixing them. Recent audit found 169 pages of findings, 16 critical findings
  * P70 - Piling backlog of technical debt preventing effective work
    * Every task is considered urgent
    * No complete list of projects or commitments
    * Lacking project management
    * Heroics and heroes responsible for all work
    * People going directly to IT resources for help, breaking visibility of work and priorities
* Audit current tasking, be clear about intent
  * Internal audit reveals many projects spanning multiple years
  * Tasking works out to nearly a 1:1 level, 1 project per person/employee
  * Phoenix Project and Audit Remediation projects consuming the most resources

* P82 - Trying something new, even if less efficient, can win holdouts to existing processes. Process managers/owners will get upset/emotional over their solution/tradition being replaced or circumvented, but their expertise is also critical in order to be successful.
* P89 - Work in Process (WIP) is crippling, especially when viewed as physical inventory
  * "The Goal" - Theory of Constraints
  * Lean Production
  * Toyota Production System
  * Total Quality Management
  * Working the most urgent issue is no efficient (FIFO)
  * Tradition is the enemy of efficiency
  * Theory of Constraints
    * Improvement anywhere in the system other than the bottleneck is an illusion/waste
  * "The 3 Ways"
    * 1: Fast flow of work from Dev to IT
    * 2: Shorten and amplify feedback loops
    * 3: Culture that fosters experiments, learning from failure, understanding repetition as a pre-requisite to mastery
* P92 - 4 types of work
  * 1: Business Project Work
  * 2: Internal Projects
  * 3: Changes
  * 4: Unplanned Work (firefighting, anti-work)
* P97
  * Despite proving resource utilization, competing task priorities, and need for more staffing, Steve (CEO) tells Bill (VP of IT) he can only use what he already has, and that IT is already the most expensive part of the company.
* P116-P117
  * Force documentation even if it takes using a proxy to the keyboard (pair programming)
* P127
  * Code changing so fast that releases are coming before even getting the prior release through smoke tests. No release has successfully gotten through the smoke tests, and new pieces keep getting broken with each release.
* P130-138
  * Phoenix Project gets shoved out the door despite warnings and urges by leadership to Steve (CEO) that it is a colossal failure and to delay. Reasons range from poor performance, to memory leaks, to exposing customer credit card data. Steve explodes in anger, and tells each employee he needs to meet with them.
* P148
  * When Steve meets with Bill, he threatens to outsource IT in 90 days
* P161
  * 1: Visualize your work (Kanban)
  * 2: Identify source of unplanned work
* P162
  * Theory of Constraints
    * 1: Identify your current constraint/bottleneck
    * 2: Exploit the constraint
      * Never waste its time
      * Ensure it is always busy
      * It should always be working on the highest priority
    *   3: Subordinate the constraint
      * "Drum-Barrel-Rope"
      * Match pace to meet capacity of the constraint, even if it means slowing down
* P164
  * Feature development is prioritized over stability, security, security, scalability, manageability, operability, and continuity. Operations is reacting to retrofit performance to match the resulting problems caused by lack of planning and design.
  * Non-functional requirements
* P165
  * Constraint is unable to attend design and planning meetings due to unplanned work and firefighting
  * Work/todo/planning must match business objectives. Taking needless work out of the system is MORE IMPORTANT than putting new work into the system
* P172
  * Steve (CEO) begins micromanaging and blames Bill for IT mismanagement. Bill quits after getting blamed for all of the problems.
* P180
  * Steve apologizes at Erik's behest, Bill comes back after taking some personal time to reflect and enjoy his family
* P184 - 5 Dysfunctions of a Team - Patrick Lencioni
* P185 - Steve commits to making IT a core competency of the company, and to establish trust
* P195
  * Steve hosts an emotional vulnerability exercise to build trust among the team
  * Bill explains how they have no process to define or manage how work gets taken on, or approved for work. Erik explains that this is technical debt, that carries "interest" that develops into unplanned work and firefighting when it is not managed. Worsened by a lack of capacity planning.
* P197
  * When we fall into reactive patterns, work gets prioritized based on who yells the loudest, the most often, sweetens the pot, or gets the ear of a high ranking executive.
* P200
  * 1: When WIP goes down, completed tasking goes up
  * 2: Due date performance goes up, because WIP went down
  * 3: Accepting new work increases WIP
  * 4: As WIP increases, due date performance goes down
  * Bill refocuses on priorities by freezing all incoming work, to eliminate multitasking
* P210
  * Work Center = Machine, Man, or Method
* P212
  * Accepting/scheduling new work should require a "bill of resources" to establish capacity and demand
  * Total Productivity Maintenance (TPM) is the most important type of work
  * Improving daily work is even more important than daily work itself
  * Resilience Engineering dictates that routinely injecting faults into the system makes us handle them frequently, and makes it less painful each time
  * Mike Rother: Improvement Kata
    * Repetition creates habits, habits enable mastery
* P213
  * Wait time for a resource is the percentage of time that the resource is busy, divided by the time the resource is idle
  * Wait times must be visible/visualized
* P218
  * GAIT Principles
    * Material weakness
      * Linkage
      * Significance
      * Controls reliance
* P221
  * You win when you protect the organization without putting meaningless/inconsequential work into the IT system
  * You win even more when you take meaningless work OUT of the IT system
  * Scoping errors are expensive
    * Example: "QA manager writes millions of new tests for a legacy/dead product and files bug reports for features that no longer exist"
* P226
  * Kanban - Makes demand and WIP visible upstream AND downstream
    * Ready
    * Doing
    * Done
  * Kanban WIP limits on "doing" can increase throughput
  * ALL work must ultimately go through the kanban board. Not email, not IM, not phone, etc…
* P227
  * Once using Kanban, ETA/ETC can be calculated using aggregated historical metrics. Enables exposing these metrics, and making use
  * Using checklists associated with Kanban instead of longer documentation drives completion times down
* P228
  * 2-week improvement cycles (Kata)
    * Plan -> Do -> Check -> Act
* P229
  * Indicate card/issue priorities w/ color-code or labels instead of separate columns
  * Blocked issues should be reviewed more frequently than other work
* P230
  * Internal non-urgent work (not customer facing) should be prioritized this way:
    * 1: Work that improves the current bottleneck performance should be most important
    * 2: Work that doesn't utilize the current bottleneck is next
    * 3: LAST: Work that requires using the current bottleneck (negatively impacts customers)
* P251
  * Each department needs to align their values to support the company's goals/targets. Much more than catch phrases, mottos, and ideals. PRACTICAL AND SPECIFIC.
* P252 - 3 Internal Control Objectives (audits)
  * 1: Gain assurance for reliability of financial reporting
  * 2: Compliance with laws and regulations
  * 3: Efficiency and effectiveness of operations
* P253 - COSO cube
* P254 - Maintenance schedules as KPI for predicting behavior
* P271 - Properly scoping security work against systems related to the control and process/dates needing protection/security
* P275 - "The Bates Motel"/"Hotel California" of work
* P276 - Repetition involving teamwork, creates trust and transparency
* P286 - Keep work flowing one direction. Work should never move backward in the queue/be reworked. Consider pulling late resources in early, to define non-functional requirements.
* P294 - "Allspaw" supercharging and optimizing the entire process flow
  * "takt time" - cycle time necessary to keep up with demand. If this time is exceeded by any component or series of components, customer demand cannot be met
* P295 - Feedback loops are necessary to get late stage inputs/retrospect influencing design and planning
* P296 - In Toyota LEAN examples, large batching for bottleneck resources compounded the problem. Solve why a large batch is necessary, and fix/optimize those reasons since they are the real bottlenecks
  * Decrease "changeover" time
  * Enable faster deployment cycles
  * Flickr - John Allspaw, Paul Hammond - Velocity Conference
* P297
  * Jez Humble, Dave Farley - Continuous Delivery
  * Eric Reis - Lean Startup
  * Version Control everything
  * Automate deployment actions
  *   Codify human/tribal knowledge
* P303
  * Value stream mapping of processes written out into a workflow
  * Tracking time
  * Identifying steps that typically wait/queue
* P304
  * Dev, QA< and production all commonly deployed via the same scripts, and no manual processes
  * Blue/green and/or A/B testing deployments
* P321 - Feature flags for quickly turning features on and off -- fix production with a single commit/change
* P328 - Improvement Kata's
* P329 - Chaos Monkey and Evil Chaos Monkey
* P331 - Bill gets offered the CIO position with unanimous support. Strong profits and share prices in response to his last few quarters of performance
* P332 - Steve wants Bill to rotate around the company improving each department instead of taking the CIO position. Ultimately pathing up to COO. Steve's reasoning is that the best COO's come from IT background.
* P333 - Business needs to be married to IT to be profitable in today's modern world
* P335 - Proposed hedge-fund to reward companies that embrace IT as a core competency
* P337 - The DevOps Cookbook
* P342 - Risk Adjusted Value Management
  * Paul Proctor, and Michael Smith - Gartner
  * KPI to IT translation
  * Audit internal control objectives
    * GAIT
    * Institute of Internal Auditors

* Resource Guide
  * P348 - Why do DevOps?
  * P354 - Where DevOps came from
  * P356 - The 3 ways explained
    * 1: Left to right flow optimization, CI/CD
    * 2: Feedback loops, process improvements
    * 3: Create culture of innovation and risk taking, prioritizing non-functional requirements, high-trust, celebrate improvements
  * P358 - Top DevOps Myths
    * 1: DevOps replaces Agile
    * 2: DevOps replaces ITIL
    * 3: DevOps means NoOps
    * 4: DevOps is only for open source
    * 5: DevOps is just Infrastructure as Code or automation
    * 6: DevOps is only for startups and unicorns
  * P362 - The 4 types of work
    * 1: Business Projects
    * 2: Internal IT Projects
    * 3: Changes
    * 4: Unplanned Work/Firefighting
  * P367 - Further reading
    * 1: The Goal
    * 2: It's not luck
    * 3: Beyond the Goal
    * 4: The logical thinking process
    * 5: The 5 dysfunctions of a team
    * 6: Toyota Kata
    * 7: Continuous Delivery
    * 8: Release IT!
    * 9: Visible Ops
    * 10: ITIL V3
    * 11: Purposeful Kanban
    * 12: Kanban - David J. Anderson
