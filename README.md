# Databricks Dashboard – Visual View Guide

This repository contains a Databricks Lakeview dashboard exported as a JSON file.
GitHub cannot render Databricks dashboards visually. The dashboard must be imported
into a Databricks workspace to view it.

## Prerequisites

- Access to a Databricks workspace
- Permission to create or import dashboards
- Required tables/views referenced by the dashboard exist in the workspace

## File Location

```text
dashboards/Transaction Dashboard.lvdash.json
```
## View Dashboard via Databricks Repos (Recommended)

1. Open **Databricks Workspace**
2. Navigate to **Workspace → Repos**
3. Open this repository
4. Locate the dashboard file
5. Click the **three dots (⋮)** next to the file
6. Select **Import dashboard**

The dashboard will open in the Databricks **Lakeview UI**.

---

## View Dashboard via Dashboards UI

1. Open **Databricks Workspace**
2. Go to **Workspace → Dashboards**
3. Click **Create → Import dashboard**
4. Upload `Transaction Dashboard.lvdash.json`

The dashboard will be created and rendered visually.

---

## Notes

- `.lvdash.json` is a dashboard definition file
- The file must be **imported**, not executed
- GitHub displays the file as JSON by design
