# Task Management Tracker (Excel)

A lightweight **task management tracker built in Microsoft Excel** — designed for ops teams who want *clarity* without heavyweight tools.

This template combines:
- a structured **task table** (with drop-downs + conditional formatting),
- an **Overdue** risk flag,
- and a **Dashboard** with quick charts (by **Owner** and **Team**).

> ✅ Works best in **Excel Desktop** (Windows/Mac). Most features also work in Excel Online, but drop-downs/formatting may vary.

---

## Preview

Add screenshots here after you upload the repo:

![Image Alt](https://github.com/Ritika-port/Task-Management-Tracker/blob/main/task%20management%20dashboard%20ss.png?raw=true)
![Image Alt](https://github.com/Ritika-port/Task-Management-Tracker/blob/main/Task%20management%20table%20ss.png?raw=true)


---

## What’s inside

- **Dashboard sheet**
  - Bar chart: **# of Tasks by Owner**
  - Bar chart: **# of Tasks by Team**
  - Scan-friendly table with status coloring

- **Support Sheet**
  - Rollups using `COUNTIF`:
    - Tasks by **Status**
    - Tasks by **Owner**
    - Tasks by **Team**
    - Total **Overdue** tasks

---

## Columns (data dictionary)

| Column | Type | What it’s for |
|---|---|---|
| Task ID | Text | Unique ID (e.g., `T001`) |
| Task Name | Text | Short, action-oriented task title |
| Team | Text (drop-down) | Team/category (e.g., Finance/HR/Strategy) |
| Task Owner | Text (drop-down) | Person responsible |
| Start Date | Date | Task start date |
| Due Date | Date | Task deadline |
| Task Duration | Calculated | `Due Date - Start Date` |
| Status | Text (drop-down) | `Not Started` / `In Progress` / `Completed` |
| Overdue? | Calculated (TRUE/FALSE) | Flags tasks past due date and not completed |
| Comments | Text | Context, blockers, next step |

