# 🏗️ Oracle 19c Performance Monitoring and Tuning Scripts

This repository contains a comprehensive collection of **Oracle Database 19c** SQL scripts, designed to diagnose and tune database performance at both **session** and **system** levels — with full support for **Multitenant (CDB/PDB)** environments.

---

## 📚 Contents

| Category | Description |
|-----------|--------------|
| **Session-Level Tuning** | Diagnose active sessions, SQL IDs, and blocking locks. |
| **System-Level Tuning** | Review wait events, I/O stats, and memory usage. |
| **AWR/ASH Reports** | Analyze performance trends and real-time workload activity. |
| **SQL Plan & Execution** | View and tune SQL execution plans. |
| **PDB Resource Monitoring** | Monitor resource utilization across PDBs. |
| **Locking & Contention** | Identify blocking sessions and enqueue waits. |

---

## 🧩 Key Scripts Summary

| Script | Purpose |
|--------|----------|
| `sess_top.sql` | Lists top sessions by CPU, I/O, or wait time. |
| `awr_top_sqls.sql` | Extracts high-load SQLs from AWR. |
| `ash_active_sessions.sql` | Shows real-time activity using ASH. |
| `wait_event_summary.sql` | Summarizes system-wide wait events. |
| `tablespace_usage.sql` | Monitors tablespace and datafile usage. |
| `io_stats.sql` | Displays file-level I/O statistics. |
| `sql_plan_details.sql` | Shows execution plan and tuning hints. |
| `pdb_resource_usage.sql` | Reports CPU/memory/I/O usage per PDB. |
| `system_stats_snapshot.sql` | Captures system stats for baseline comparison. |
| `locking_issues.sql` | Detects blocking and waiting sessions. |

---

## ⚙️ Usage

### 1️⃣ Connect to SQL*Plus
```bash
sqlplus / as sysdba
