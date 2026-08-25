# Screenshot replacement guide

The App Store page references these files:

1. `screenshots/01_connection_dashboard.png` — Wrike connection form/dashboard with status and stat buttons.
2. `screenshots/02_project_task_sync.png` — Odoo project or task form showing the Wrike Sync panel.
3. `screenshots/03_sync_queue.png` — Sync Jobs list/form with states, retry information, and logs.
4. `screenshots/04_webhook_events.png` — Webhook Events list/form and connection webhook configuration.
5. `screenshots/05_workspace_data.png` — Imported Wrike task/folder records and their Odoo bindings.

The package currently contains polished interface previews based on the module's XML views and Python behavior. Replace each file with a real screenshot using the exact same filename before publishing when production data is available.

Recommended capture settings:

- Browser viewport: 1440 × 900 or larger.
- Hide confidential client IDs, secrets, tokens, email addresses, and real customer names.
- Use one consistent demo database and connection name.
- Keep browser chrome outside the crop.
- Export PNG at full resolution; do not compress text until it becomes blurry.
- Preserve an aspect ratio close to 1400 × 850 so the page layout remains stable.
