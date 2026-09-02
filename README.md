# DB-Vul
A manually validated dataset of reproducible Docker environments for 211 publicly disclosed DBMS vulnerabilities across 17 database systems.

To define the scope of DBMS vulnerabilities, we follow the DBMS-oriented product classification used by the [DB-Engines Ranking](https://db-engines.com/en/ranking

Each sample is organized in a separate directory containing the triggering code, vulnerable source files or key code snippets, a Dockerized vulnerable environment, and a structured security write-up. The write-up documents the vulnerability mechanism, affected versions, environment configuration, vulnerable code location, patching strategy, reproduction procedure, code analysis, and supporting sources.

The detailed distribution is shown below.

| Database Category | Database | Count | Percentage |
|---|---|---:|---:|
| Relational / SQL | MariaDB | 50 | 23.7% |
| Relational / SQL | PostgreSQL | 39 | 18.5% |
| Relational / SQL | SQLite | 32 | 15.2% |
| Relational / SQL | MySQL | 7 | 3.3% |
| Relational / SQL | H2DB | 3 | 1.4% |
| Relational / SQL | CrateDB | 2 | 0.9% |
| Relational / SQL | DuckDB | 1 | 0.5% |
| Relational / SQL | TiDB | 1 | 0.5% |
| Key-value | Redis | 30 | 14.2% |
| Document | MongoDB | 10 | 4.7% |
| Document | CouchDB | 5 | 2.4% |
| Search Engine | Solr | 10 | 4.7% |
| Search Engine | Elasticsearch | 5 | 2.4% |
| Column-oriented | ClickHouse | 8 | 3.8% |
| Time-series | OpenTSDB | 5 | 2.4% |
| Time-series | InfluxDB | 2 | 0.9% |
| Graph | Neo4j | 1 | 0.5% |
| **Total** | **17 DBMSs** | **211** | **100.0%** |
