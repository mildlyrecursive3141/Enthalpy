## Enthalpy is laboratory management software built around one idea: a lab is only as reliable as its records. It gives every lab member a single place to log observations, track equipment and calibration schedules, manage consumables and inventory, and keep a complete, tamper-evident audit trail, all without forcing the lab into a rigid, one-size-fits-all workflow. It runs on your own server, so your data stays under your control, and it is open to any lab, from a single research bench to a multi-team facility.



# Primary Functional
1. Dashboard: KPIs, alerts, activity
2. Experiments: Protocols, observations, results
3. Equipment: Assets, calibration, maintenance
4. Scheduling: People, rooms, instruments
5. Data & Reports: Tables, files, exports
6. Personnel: Roles, permissions, teams
7. Inventory (EXPENDABLES, DIFFERENT FROM EQUIPMENT): Consumables, batches, stock
8. Administration: Audit, settings, compliance


## Tech stack
Desktop: [Rust](https://rust-lang.org/) & [Tauri 2](https://v2.tauri.app/) \
Frontend: [React](https://react.dev/) & [TypeScript](https://www.typescriptlang.org/) \
Application core: Tauri Commands & Rust Services \
Database: [PostgreSQL](https://www.postgresql.org/) (2 main modes: local personal usage & collaborative multi-user experience)
