# Tests

Notebooks for verifying a Wikibase instance. All use Python stdlib only — no extra packages required.  
Set the target instance in **cell 2** of each notebook, or via `../.env`.

| Notebook | What it tests |
|----------|---------------|
| [00_sparql_health_check.ipynb](00_sparql_health_check.ipynb) | SPARQL endpoint reachability, triple count, and labelled items |
| [00_wikibase_bot_test.ipynb](00_wikibase_bot_test.ipynb) | Bot account login and read access to Q1 (requires credentials) |
| [01_wikibase_diagnostics.ipynb](01_wikibase_diagnostics.ipynb) | API, extensions, namespaces, statistics, entities, search, and SPARQL |
