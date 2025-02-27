# Decision Log Entries

### Example Entry - Suggested to always put latest DL at top.
| Decision Number | Decision Date | Decision | Description | Made By | Decision Record or Additional Details|
|-----------------|---------------|----------|-------------|---------|--------------------------------------|
|2| 2025-02-22 | Use github actions for CI/CD Pipeline for MMI | GitHub actions are simpler to start with, but can be become quite advanced over time, making adoption quicker and easier. GitHub actions are also deployment target agnostic. Being agnostic has its pros and cons as well, so it is suggested that future RFCs cover the preferred target environments, such as stating "any managed container service" can be used as a deployment target. | Dev team |  [RFC supporting decision](https://github.com/daxiom/mmi/discussions/2) |
|1| 2025-02-20 | Decision to use a decision log | Allows for historical context and details for decisions | Dev team | [0001](0001-Use-decision-logging.md) |
