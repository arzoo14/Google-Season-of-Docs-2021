# GSoD 2021 Timeline & Deliverables

| SYMBOLS | MEANINGS |
|:-------:|:--------:|
| :heavy_check_mark: | Completed |
| :construction: | In Progress |
| :warning: | Needs review |
| :red_circle: | Not Yet Started |



| **DELIVERABLES**               | **STATUS**            |  **PR**  | **FEEDBACK**|
|:---------------------------------|:---------------------:|:------------:|:-----------------:|
|   **_WEEK 1 (May 31 - June 6)_** |    |     |        |
| Enable Google Analytics on readthedocs pages| :heavy_check_mark: | | |
| Add 'Quick Guides' section in readthedocs landing page | :heavy_check_mark: | [#1469](https://github.com/performancecopilot/pcp/pull/1469) | [Link](https://pcp.readthedocs.io/en/latest/QG/QuickGuides.html) |
| Make separate .rst files for each 'How To' tasks |:heavy_check_mark: | " | | 
| Adding separate .rst files for each 'Short Guides' | :heavy_check_mark:| " | |
|   **_WEEK 2 (June 7 - June 13)_** |    |     |        |
| Start with the 'How To' Guides |:heavy_check_mark: | | |
| How do I list the available performance metrics | :heavy_check_mark:| [#1473](https://github.com/performancecopilot/pcp/pull/1473) | [Link](https://pcp.readthedocs.io/en/latest/QG/ListAvailableMetrics.html#list-the-available-performance-metrics) |
| How do I add new metrics to the available set |:heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/AddNewMetrics.html) |
| How do I record metrics on my local system |:heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/RecordMetricsOnLocalSystem.html) |
|   **_WEEK 3 (June 14 - June 20)_** |    |     |        |
| Continue with the 'How To' Guides |:heavy_check_mark: | | |
| How do I record metrics from a remote system |:heavy_check_mark: | [#1473](https://github.com/performancecopilot/pcp/pull/1473) | [Link](https://pcp.readthedocs.io/en/latest/QG/RecordMetricsFromRemoteSystem.html)|
| How do I create a simple graph of a performance metrics | :heavy_check_mark:| " | [Link](https://pcp.readthedocs.io/en/latest/QG/GraphPerformanceMetric.html) |
| How do I automate performance problem detection |:warning: | [#1474](https://github.com/performancecopilot/pcp/pull/1474) | [Link](https://pcp.readthedocs.io/en/latest/QG/AutomateProblemDetection.html) |
|   **_WEEK 4 (June 21 - June 27)_** |    |     |        |
| Continue with the 'How To' Guides | :heavy_check_mark: | | |
| How do I setup automated rules to write to the system log |:heavy_check_mark: | [#1473](https://github.com/performancecopilot/pcp/pull/1473) | [Link](https://pcp.readthedocs.io/en/latest/QG/SetupAutomatedRules.html) |
| How do I record historical data for use with pcp-dstat(1) tool |:heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/RecordHistoricalValues.html) |
| How do I export metric values in a comma-separated formats | :heavy_check_mark:| " | [Link](https://pcp.readthedocs.io/en/latest/QG/ExportMetricValues.html) |
|   **_WEEK 5 (June 28 - July 4)_** |    |     |        |
| Blogging of the last four weeks	 | | | |
| Audit existing documentation for tutorial content | :heavy_check_mark: | | |
|   **_WEEK 6 (July 5 - July 11)_** |    |     |        |
| Start refactoring of Short Guides into 'How do I..." form | :heavy_check_mark: | | |
| How do I use charts |:heavy_check_mark: | [#1469](https://github.com/performancecopilot/pcp/pull/1469) | [Link](https://pcp.readthedocs.io/en/latest/QG/UseCharts.html)|
| How do I manage archive log |:heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/LoggingBasics.html) |
|   **_WEEK 7 (July 12 - July 18)_** |    |     |        |
| Continue refactoring of Short Guides into 'How do I..." form | :heavy_check_mark: | | |
| How do I automate reasoning with pmie | :heavy_check_mark: | [#1469](https://github.com/performancecopilot/pcp/pull/1469) | [Link](https://pcp.readthedocs.io/en/latest/QG/AutomatedReasoningBasics.html) |
| How do I site rules with pmieconf | :heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/ConfigureAutomatedReasoning.html) |
|   **_WEEK 8 (July 19 - July 25)_** |    |     |        |
| Continue refactoring of Short Guides into 'How do I..." form | :heavy_check_mark: | | |
| How do I analyze Linux containers | :heavy_check_mark:| [#1469](https://github.com/performancecopilot/pcp/pull/1469) | [Link](https://pcp.readthedocs.io/en/latest/QG/AnalyzeLinuxContainers.html) |
| How do I establish secure connections | :heavy_check_mark:| " | [Link](https://pcp.readthedocs.io/en/latest/QG/SecureConnections.html) |
|   **_WEEK 9 (July 26 - August 1)_** |    |     |        |
| Blogging of the last four weeks	 | | | |
| Continue refactoring of Short Guides into 'How do I..." form | :heavy_check_mark: | | |
| How do I establish secure client connections | :heavy_check_mark: | [#1469](https://github.com/performancecopilot/pcp/pull/1469) | [Link](https://pcp.readthedocs.io/en/latest/QG/SecureClientConnections.html) |
| How do I setup authenticated connections | :heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/AuthenticatedConnections.html) |
|   **_WEEK 10 (August 2 - August 8)_** |    |     |        |
| Continue refactoring of Short Guides into 'How do I..." form | :heavy_check_mark: | | |
| How do I import data and create PCP archives |:heavy_check_mark: | [#1469](https://github.com/performancecopilot/pcp/pull/1469) | [Link](https://pcp.readthedocs.io/en/latest/QG/ImportData.html) |
| How do I visualize performance with pmview |:heavy_check_mark: | " | [Link](https://pcp.readthedocs.io/en/latest/QG/Use3DViews.html)|
|   **_WEEK 11 (August 9 - August 15)_** |    |     |        |
| Provide feedback to developers about potential areas of improvements | | | |
|   **_WEEK 12 (August 16 - August 22)_** |    |     |        |
| Introduce consistency into all Tutorials and Guides across the project | :heavy_check_mark: | | |
| Work on feedbacks from mentors, developers and end-users | :heavy_check_mark: | | |
| Checking (changing) of the codebase as per coding standards	|:heavy_check_mark: | | |
| Work on Bugs/Issues (if any) | :heavy_check_mark:| | |
| Blogging of the last four weeks	 | | | |
|   **_WEEK 13 (August 23 - August 31)_** |    |     |        |
| Canvas the community for additional topics | | | |
| Complete the leftovers (in any) | | | |
| Work with the organization to provide information needed for the final evaluation and case study | | | |
| Blogging of The Last Week| | | |









