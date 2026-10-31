<div align="center">

<h1>Quant Research Desk</h1>

<p><strong>Independent quantitative research · Systematic trading · Research software</strong></p>

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=19&duration=3700&pause=1200&color=2997A7&center=true&vCenter=true&width=850&height=48&lines=Investigating+signals%2C+not+just+backtests.;Testing+what+survives+outside+the+sample.;Building+tools+that+make+research+repeatable." alt="Animated introduction to Quant Research Desk" />

<p>
<a href="https://quantresearchdesk.com">Website</a> &nbsp;·&nbsp;
<a href="https://quantresearchdesk.com/research">Research library</a> &nbsp;·&nbsp;
<a href="mailto:contact@quantresearchdesk.com">Contact</a>
</p>

</div>

---

## What we're working on

Quant Research Desk (QRD) is an independent research collaboration between **Roberto Coccaro** and **Amin Hydar Ali**. We study financial markets through quantitative models, historical data and software built to test ideas systematically.

A trading idea can sound convincing for a perfectly reasonable reason: prices trend, assets sometimes reverse after large moves, liquidity changes throughout the day, and investors respond differently to information. The difficult part is working out whether any of those observations leads to a repeatable result *after* accounting for the choices made during research and the costs of trading it.

That's the problem much of our work revolves around. We investigate proposed sources of return, compare models against simpler alternatives, test where results become unstable, and document what the evidence does and does not support. Alongside that research, we build the data and software infrastructure needed to run those experiments reliably.

Our work spans both research and engineering. We publish papers and technical notes, and we intend to release selected tools that others can inspect, run and challenge. Not every experiment finds an opportunity. We think documenting the ones that fail is part of doing the work properly.

## Research and engineering

<table>
<tr>
<td width="50%" valign="top">
<h3>Systematic strategies</h3>
<p>We investigate momentum, trend following, mean reversion, contrarian effects and cross-sectional relationships. The focus is not only whether a signal appears in a backtest, but when it emerges, what might explain it and how sensitive it is to the test design.</p>
</td>
<td width="50%" valign="top">
<h3>Portfolio construction and risk</h3>
<p>A promising signal is only one part of a portfolio. We study allocation, diversification, covariance estimation, volatility targeting, drawdowns, turnover and the trade-offs that appear when different strategies are combined.</p>
</td>
</tr>
<tr>
<td valign="top">
<h3>Research methodology</h3>
<p>Historical data offers many ways to find attractive patterns by accident. We examine sample selection, look-ahead bias, parameter sensitivity, multiple testing, out-of-sample evaluation and the consequences of changing market conditions.</p>
</td>
<td valign="top">
<h3>Market microstructure</h3>
<p>We explore order-book depth, trades, spreads, liquidity and short-horizon market behavior. We also pay attention to what a data feed actually measures: local processing delays and API round trips, for example, are not the same as exchange or execution latency.</p>
</td>
</tr>
<tr>
<td valign="top">
<h3>Research software</h3>
<p>We work on the practical tools behind repeatable analysis: market-data collection, cleaning, simulation, backtesting, experiment configuration, testing and result storage. Good research software should make assumptions visible and failures diagnosable.</p>
</td>
<td valign="top">
<h3>Research publication</h3>
<p>We turn investigations into papers, short explanations and technical documentation. Where possible, we describe the setup, limitations and interpretation clearly enough for another researcher to question the result rather than simply accept it.</p>
</td>
</tr>
</table>

## How we approach a research question

There is no single procedure that makes a quantitative result trustworthy. We use a set of checks suited to the question, the available data and the intended use of the result.

<table>
<tr><th align="left">Stage</th><th align="left">What we try to establish</th></tr>
<tr><td><strong>01 · Formulate the idea</strong></td><td>What behavior are we trying to explain? Is there an economic, behavioral or market-structure rationale, or are we starting from an observed statistical pattern?</td></tr>
<tr><td><strong>02 · Examine the data</strong></td><td>Where did it come from? What is missing? Are timestamps, corporate actions, survivorship and data availability handled correctly?</td></tr>
<tr><td><strong>03 · Establish a baseline</strong></td><td>Does the idea improve on a simple benchmark? How many choices and parameters have been introduced?</td></tr>
<tr><td><strong>04 · Challenge the result</strong></td><td>What happens across periods, assets, parameter values and genuinely unseen samples? Could multiple testing explain the apparent success?</td></tr>
<tr><td><strong>05 · Account for implementation</strong></td><td>What do turnover, spreads, fees, slippage, liquidity and execution constraints do to the result?</td></tr>
<tr><td><strong>06 · Report what remains</strong></td><td>What survives, what fails, what remains uncertain, and what would someone need to reproduce or extend the work?</td></tr>
</table>

A historical backtest is evidence about a particular model, dataset and testing procedure. It is **not** proof that a strategy will make money in live trading. We distinguish simulated results from live results and consider negative or inconclusive findings worth reporting.

## Published work

Our [research library](https://quantresearchdesk.com/research) contains papers, historical investigations and downloadable reports. Topics explored include:

- **Alpha research frameworks.** Comparing different families of systematic signals, their possible mechanisms, validation requirements and common failure modes.
- **Mean reversion and contrarian behavior.** Investigating whether short- and longer-horizon return patterns remain meaningful outside the periods in which they were identified.
- **Portfolio research.** Examining how signal combinations, allocation rules and risk constraints change portfolio behavior.
- **Market anomaly audits.** Revisiting proposed effects, including results that do not provide convincing evidence of a tradable opportunity.

**[Browse the QRD research library](https://quantresearchdesk.com/research)**

The library is the source of record for available papers, authorship, dates and the status of individual investigations. We do not present research ideas or historical simulations here as verified live investment performance.

## Open-source work

We want this organization to become a useful home for selected research code, not just a link to our website. Our initial areas of interest include a **Python order-book simulator**, **market-data utilities** and **reproducible research examples**.

These are areas of planned or ongoing development, **not promises that the corresponding repositories are already released**. When a public project is ready, we aim to provide enough documentation for someone unfamiliar with our environment to install it, run a basic example, understand its assumptions and reproduce its tests.

Some work will remain private, particularly proprietary strategies, credentials, licensed datasets and infrastructure details that should not be exposed. Public releases will be separated from that material and reviewed before publication.

## Working with our research

If you're reading one of our papers or exploring a future repository, we welcome substantive questions. Useful discussion often starts with something specific: an assumption that may not hold, a data issue, a different benchmark, an alternative explanation, or a result that fails to replicate.

We are particularly interested in discussions about systematic strategy design, robust backtesting, market-data quality, portfolio risk and dependable research engineering. If you find a reproducibility issue in a released project, please use that repository's issue tracker when available. For general enquiries or collaboration proposals, contact us directly.

## People and contact

QRD is developed by **Roberto Coccaro** and **Amin Hydar Ali**. We work across quantitative research, software engineering and the publication of systematic market studies.

<table>
<tr><td><strong>Website</strong></td><td><a href="https://quantresearchdesk.com">quantresearchdesk.com</a></td></tr>
<tr><td><strong>Research papers</strong></td><td><a href="https://quantresearchdesk.com/research">Research library</a></td></tr>
<tr><td><strong>General contact</strong></td><td><a href="mailto:contact@quantresearchdesk.com">contact@quantresearchdesk.com</a></td></tr>
<tr><td><strong>Roberto</strong></td><td><a href="mailto:roberto@quantresearchdesk.com">roberto@quantresearchdesk.com</a></td></tr>
<tr><td><strong>Amin</strong></td><td><a href="mailto:amin@quantresearchdesk.com">amin@quantresearchdesk.com</a></td></tr>
</table>

---

<div align="center">
<sub>Quant Research Desk · Research, code and publications at <a href="https://quantresearchdesk.com">quantresearchdesk.com</a></sub>
</div>
