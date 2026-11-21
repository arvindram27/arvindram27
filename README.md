![Arvind Ramachandran. Data Engineering and Applied AI. Python, SQL, PySpark, Delta Lake, DuckDB, PostgreSQL, LangGraph and FastAPI.](assets/3-profile-hero-revised.png)

<div>
<samp>

<p><strong>+-- 01 / ABOUT</strong></p>

<p>Hi, I'm Arvind.<br>
Mechanical engineer transitioning into data engineering and applied AI.<br>
Chennai, India.</p>

<p>I build data pipelines and AI agent workflows. I'm looking for roles in data engineering and AI engineering.</p>

<p>My focus is reliability. I work on data quality and traceable results with clear limits on what an AI agent can do.</p>

<p>&gt; <a href="https://arvindramachandran.tech/">Portfolio</a></p>

<p><strong>+-- 02 / SELECTED WORK</strong></p>

<p><strong>[01] <a href="https://github.com/arvindram27/CartProof">CartProof</a> (Meta Global AI Developer Hackathon 2026 submission)</strong></p>
<p>A shopping agent can say "done" even when an item is missing from your cart or the quantity is wrong. Its success message is not proof that the cart is correct.</p>
<p>CartProof compares the actual cart with its starting state and the requested change. It checks the items and quantities as well as whether the rest of the cart stayed unchanged. The controlled demo attempts one correction for a missing item and checks the cart again before reporting success.</p>
<p>Python / Meta API / Shopify Storefront API<br>
Scope: controlled synthetic-cart demo with one deliberately dropped action. No checkout or orders. Not a general shopping service.</p>

<p><strong>[02] <a href="https://github.com/arvindram27/multi-agent-market-intelligence">MAMI / Multi-Agent Market Intelligence</a></strong></p>
<p>Market research needs sources that can be checked and results that can be reviewed. MAMI turns news excerpts into structured analysis with source evidence. A person reviews the results before they are saved to Postgres.</p>
<p>I'm also building an agent harness around this workflow to control token budgets and data access. It checks writes against the approved target and records decisions and outcomes.</p>
<p>LangGraph / PostgreSQL / SQLite<br>
Scope: harness controls are tested offline and are not enabled in the default app. The full live harness is not finished.</p>

<p><strong>[03] <a href="https://github.com/arvindram27/market-efficiency-detector">Market Efficiency Detector</a></strong></p>
<p>How long does a price take to adjust after news? MED explores that question through a synthetic Price Adjustment Latency demo and a separate candle-based timing study that keeps missing data visible.</p>
<p>Python / Spark / SQLite<br>
Scope: research prototype. Not a validated market efficiency detector or trading system.</p>

<p><strong>[04] <a href="https://github.com/arvindram27/retail-feed-standardizer">Retail Feed Standardizer</a></strong></p>
<p>Sales feeds from shops and online stores use different formats. Bad records can get lost during processing and leave gaps in the totals. This pipeline puts accepted rows into a standard Delta table and keeps rejected rows in quarantine with a reason. It checks that row counts and amounts add up.</p>
<p>PySpark / Delta Lake<br>
Scope: small-scale learning project using synthetic feeds. Re-run safety is not yet implemented.</p>

<p><strong>[05] <a href="https://github.com/arvindram27/ai-cost-margin-pipeline">AI Cost &amp; Margin Pipeline</a></strong></p>
<p>AI usage counts alone do not show what each customer costs to serve. This pipeline turns usage events into estimated costs and simulated customer margins. Usage that cannot be priced stays visible rather than being counted as free.</p>
<p>Python / DuckDB<br>
Scope: synthetic usage and prices only. Revenue and margins are simulated.</p>

<p><strong>+-- 03 / IN PROGRESS</strong></p>

<p><strong><a href="https://github.com/arvindram27/servicedesk-copilot">ServiceDesk Copilot</a></strong></p>
<p>A local-only IT support prototype exploring checks on model providers and token budgets before a request runs. It also explores permission checks before writes.</p>
<p>Python / FastAPI / SQLite<br>
Scope: synthetic data. The ticket workflow and agent loop are not complete.</p>

<p><strong>+-- 04 / TOOLBOX</strong></p>

<p>Python / SQL / PySpark / Delta Lake<br>
DuckDB / PostgreSQL / LangGraph / FastAPI</p>

<p>+-- end</p>

</samp>
</div>
