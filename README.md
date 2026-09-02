# DB-Vul-Set

> [!NOTE]
> This repository is currently being updated. The complete DB-Vul dataset has not yet been uploaded, and additional vulnerability samples and related materials will be added progressively.

A manually validated dataset of reproducible Docker environments for **211** publicly disclosed DBMS vulnerabilities across **17** database systems.

To define the scope of DBMS vulnerabilities, we follow the DBMS-oriented product classification used by the [DB-Engines Ranking](https://db-engines.com/en/ranking)

Each sample is organized in a separate directory containing the triggering code, vulnerable source files or key code snippets, a Dockerized vulnerable environment, and a structured security write-up. The write-up documents the vulnerability mechanism, affected versions, environment configuration, vulnerable code location, patching strategy, reproduction procedure, code analysis, and supporting sources.

The detailed distribution is shown below.

<table>
<tr>
<th>Database Category</th>
<th>Database</th>
<th>Count</th>
<th>Percentage</th>
</tr>
<tr>
<td rowspan="8">Relational / SQL</td>
<td>MariaDB</td>
<td>50</td>
<td>23.7%</td>
</tr>
<tr>
<td>PostgreSQL</td>
<td>39</td>
<td>18.5%</td>
</tr>
<tr>
<td>SQLite</td>
<td>32</td>
<td>15.2%</td>
</tr>
<tr>
<td>MySQL</td>
<td>7</td>
<td>3.3%</td>
</tr>
<tr>
<td>H2DB</td>
<td>3</td>
<td>1.4%</td>
</tr>
<tr>
<td>CrateDB</td>
<td>2</td>
<td>0.9%</td>
</tr>
<tr>
<td>DuckDB</td>
<td>1</td>
<td>0.5%</td>
</tr>
<tr>
<td>TiDB</td>
<td>1</td>
<td>0.5%</td>
</tr>
<tr>
<td>Key-value</td>
<td>Redis</td>
<td>30</td>
<td>14.2%</td>
</tr>
<tr>
<td rowspan="2">Document</td>
<td>MongoDB</td>
<td>10</td>
<td>4.7%</td>
</tr>
<tr>
<td>CouchDB</td>
<td>5</td>
<td>2.4%</td>
</tr>
<tr>
<td rowspan="2">Search Engine</td>
<td>Solr</td>
<td>10</td>
<td>4.7%</td>
</tr>
<tr>
<td>Elasticsearch</td>
<td>5</td>
<td>2.4%</td>
</tr>
<tr>
<td>Column-oriented</td>
<td>ClickHouse</td>
<td>8</td>
<td>3.8%</td>
</tr>
<tr>
<td rowspan="2">Time-series</td>
<td>OpenTSDB</td>
<td>5</td>
<td>2.4%</td>
</tr>
<tr>
<td>InfluxDB</td>
<td>2</td>
<td>0.9%</td>
</tr>
<tr>
<td>Graph</td>
<td>Neo4j</td>
<td>1</td>
<td>0.5%</td>
</tr>
<tr>
<td><b>Total</b></td>
<td><b>17 DBMSs</b></td>
<td><b>211</b></td>
<td><b>100.0%</b></td>
</tr>
</table>
