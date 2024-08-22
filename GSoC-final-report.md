
### A short description of the goals of the project:<br>

SkyWalking BanyanDB is an observability database designed to ingest, analyze, and store metrics, tracing, and logging data. 
The goal of this project is to implement a built-in monitoring feature for the SkyWalking BanyanDB cluster. This built-in monitoring functionality can be set optionally through feature flags. 

For each node, show the following information: 
- Node ID or name
- Uptime
- CPU usage (percentage)
- Memory usage (percentage)
- Disk usage (percentage)
- Ports (gRPC and HTTP)
<br>

### What you did:<br>
I completed the built-in monitoring feature with the following steps: 
- Meet with my mentor twice a week and created design tech design for self-observability 
- Developed database functionalities (Internal group) to extract and store cluster metrics 
- Created UI mocks in Figma and confirmed UI/UX designed with mentor 
- Created an overview page in the BanyanDB Web App to display the nodes status 
- Implemented unit test and integration test for the built-in monitoring feature
- Created documentation to explain the bulit-in monitoring feature
<br>

### The current state:<br>
Completed<br>
<br>

### What's left to do:<br>
All works related to this project have been done, and if there are more requests in the future from the Apache SkyWalking community, I will also actively make contributions.<br>
<br>

### What code got merged upstream:<br>
#### Before GSoC starts:
- [UI] Default Time Range for Querying Data to Last 15 Minutes:
https://github.com/apache/skywalking-banyandb/pull/397

- [UI] Use BanyanDB Browser' Icon and Remove Unused Buttons:
https://github.com/apache/skywalking-banyandb/pull/402

- [UI] Fix default port in vite.config.js:
https://github.com/apache/skywalking-banyandb/pull/410

- Add Measure IndexRule and IndexRuleBinding to Measure Page:
https://github.com/apache/skywalking-banyandb/pull/418

- Add Top N Aggregation to web app:
https://github.com/apache/skywalking-banyandb/pull/430

#### During the GSoC coding period:
- [GsoC][BanyanDB] Self-Observability: Create Internal Group:
https://github.com/apache/skywalking-banyandb/pull/446

- [GsoC][BanyanDB] Self-Observability: Run Time Modes:
https://github.com/apache/skywalking-banyandb/pull/453

- [GsoC][BanyanDB] Self Observability: Fix Metrics Creation:
https://github.com/apache/skywalking-banyandb/pull/460

- [GsoC][BanyanDB] Self-Observability: Create Measure Schema:
https://github.com/apache/skywalking-banyandb/pull/462

- [UI] Fix yaml code mirror to http read request:
https://github.com/apache/skywalking-banyandb/pull/463

- [GsoC][BanyanDB] Self-Observability: Write Metric Data to Measure In Standalone Mode:
https://github.com/apache/skywalking-banyandb/pull/467

- [GsoC][BanyanDB] Self-Observability: Write Metric Data to Measure In Liaison and Data mod:
https://github.com/apache/skywalking-banyandb/pull/475

- [UI] Fix offset update issues:
https://github.com/apache/skywalking-banyandb/pull/477

- [GsoC][BanyanDB] Self-Observability: Add Metrics - Uptime, Disk:
https://github.com/apache/skywalking-banyandb/pull/481

- [UI] Vendor update July 2024:
https://github.com/apache/skywalking-banyandb/pull/484

- [GSOC] [Self-Observability] Suppress Error When Getting Path Stat:
https://github.com/apache/skywalking-banyandb/pull/490

- [GSoC] [UI] Dashboard Page:
https://github.com/apache/skywalking-banyandb/pull/496

- [GSoc] [Self-Observability] Fix dashboard disk N/A in standalone mode:
https://github.com/apache/skywalking-banyandb/pull/497

- [GSoC][UI] Fix and show message when group is not exist and native is turned off:
https://github.com/apache/skywalking-banyandb/pull/515
<br>

### Any challenges or important things you learned during the project.<br>
One significant challenge I faced during this project was that it required full-stack development, whereas my prior experience was primarily focused on front-end work before GSoC. Given that BanyanDB is a complex database, understanding the codebase initially felt overwhelming. However, I learned the importance of breaking down a complex project into smaller, manageable steps. By meeting with my mentor twice a week and completing small tasks incrementally, I gradually gained a better understanding of the codebase. After a few weeks, I had a clearer picture of the project and was eventually able to complete this challenging task successfully.
