# DANBI site templates

Templates are incomplete and must not be published directly. The Pages workflow is manual only and refuses to build without approved text, a date, officer name, legal approval and a manual publication confirmation. Values must be entered by the owner in repository Actions secrets. The generated site intentionally publishes the officer name; secrets are not committed or printed. Checks validate structure, not legal compliance.

Required secrets: `PRIVACY_OFFICER`, `EFFECTIVE_DATE` (YYYY-MM-DD), `DISCLOSURE_KO`, `DISCLOSURE_EN`, and `POLICY_APPROVED` (set to `YES` only after legal review). Select GitHub Actions as the Pages source. Run the workflow manually with `publish_confirmed` set to `YES` only after all prerequisites and publication approval. The remaining international-processing disclosure texts must be completed with verified facts before secrets are set; placeholder values are rejected.
