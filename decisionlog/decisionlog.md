# Decision Log Entries

| Decision Number |  Decision Date | Decision | Approved/Rejected | Description | Made By | Decision Record |
|--|---------------|----------|-------------------------|-----------|---------|---------------|
|1| 2025-02-27 | Decision to use a decision log |  |  | Dev team | [0001](0001-Use-decision-logging.md) |
|2| 2025-02-22 | Use github actions for CI/CD Pipeline for MMI | Tekton, Argocd | GitHub actions are simpler to start with, but can be become quite advanced over time, making adoption quicker and easier. GitHub actions are also deployment target agnostic. Being agnostic has its pros and cons as well, so it is suggested that future RFCs cover the preferred target environments, such as stating "any managed container service" can be used as a deployment target. | Dev team | [0002](0002-Use-github-actions.md) [RFC supporting decision](https://github.com/daxiom/mmi/discussions/2) |
