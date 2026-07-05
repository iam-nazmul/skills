 **A complete ERPNext skill package. It follows the standard progressive-disclosure structure: a compact SKILL.md that's always loaded when triggered, plus five reference files Claude reads only when the task needs them.**


**The SKILL.md covers the core concepts that unlock everything else in ERPNext — DocTypes, docstatus lifecycle, child tables, link fields, permissions — plus a routing table and ground rules (like never mutating GL/Stock Ledger entries directly). The references cover:**

- rest-api.md — token auth, CRUD with filters, submit/cancel via frappe.client, file uploads, webhooks, and a table of common errors and their real causes

- frappe-development.md — bench commands, custom app structure, DocType controllers, the ORM, hooks.py (doc_events, scheduler, fixtures), whitelisted methods, background jobs, patches, and testing

- low-code-customization.md — server/client scripts, custom fields, workflows, notifications, and data import for hosted instances where you can't deploy code
reports.md — Query Reports vs Script Reports with working templates for both, plus how to run reports over REST

- business-workflows.md — the selling/buying/stock/accounting document chains, statuses, and integration patterns like idempotent order intake


**You can save it by clicking the file above, or unzip it if you want to review or tweak the contents first. If you'd like, I can also run a few test prompts against the skill (e.g., "create a submitted sales invoice via API") to sanity-check it, or split it into multiple narrower skills if your use case is more specific — like API integration only.**