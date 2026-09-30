# DALTEX public lead form — TEST (template-driven)

Test copy of the public registration form (Form Builder Phase 2). Fields are drawn from the
campaign's **pinned template version** (`crm_form_assignments` → `crm_form_templates`).

- Submits to the edge function `public-lead-intake-test`, which maps answers server-side and stores
  them in **`crm_form_test_submissions`** — never `crm_leads`, never the live rate-limit log.
- The live form (`daltex-lead-form`, `daltex-lead-form-dev`) and `public-lead-intake` are untouched.
- Open: `https://daloshq.com/daltex-lead-form-test/?c=<campaign public_token>`
