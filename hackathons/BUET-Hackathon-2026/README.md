# BUET CSE FEST Hackathon 2026

Problem sets for the BUET CSE FEST Hackathon 2026. These problem statements are hosted in their original author's GitHub repositories — linked and summarized below with credit, rather than copied here directly.

If you have PDF/image versions of these (or any other round's) problem sets that you're free to redistribute, drop them into [`problems/`](problems/) following the [contribution guide](../../CONTRIBUTING.md).

## Rounds

### Mock / Practice Round — Contact Information Parser

A warm-up problem to get familiar with the hackathon's workflow, tooling, and evaluation process before the main challenge.

- **Task:** Build a REST API that extracts structured contact info (name, email, phone) from natural language text using an LLM, then validates the extracted contact against a provided PostgreSQL database.
- **Endpoints:** `POST /parse`, `GET /health`
- **Stack:** Any backend + an LLM (Gemini or GPT) + PostgreSQL (via Docker or local)
- **Source:** [suhashines/bcf-2026-hackathon-mock](https://github.com/suhashines/bcf-2026-hackathon-mock)

### Preliminary Round — ConversationalDB: Natural Language Query Engine

**AI / API track.** Build a backend that turns plain-English business questions into verified SQL answers.

- **Task:** Accept a natural language question, use a specified LLM to generate SQL, execute it against a provided PostgreSQL database (HR, Sales, Finance, Payroll schema), and return the result in a standardized JSON response format that automated checkers can verify.
- **Endpoints:** `POST /query`, `GET /health`
- **Key constraint:** The solution must be database-agnostic — the schema may differ (different table/column names) during hidden evaluation, so hardcoded queries or table/column mappings are disallowed.
- **Extras:** A subset of questions require integrating external APIs (currency conversion, geolocation) either standalone or combined with database results.
- **Includes:** 31 official test questions (scalar/record/table results), an OpenAPI spec for external APIs, and an official Python checker script.
- **Source:** [suhashines/bcf-2026-hackathon-preliminary](https://github.com/suhashines/bcf-2026-hackathon-preliminary) — see [`problem-statement/problem-statement.md`](https://github.com/suhashines/bcf-2026-hackathon-preliminary/blob/main/problem-statement/problem-statement.md)

---

*Credit: both problem sets above were authored by [@suhashines](https://github.com/suhashines). Please refer to the source repositories for the full, up-to-date problem statement, starter files, and checker scripts.*
