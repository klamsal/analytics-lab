# Analytics Lab — Decision Modeling Tools

Interactive teaching tools for decision modeling and analytics, built as a single shared platform. Free to open in a browser — no login, no install, no server. All calculations run on the page.

**Live site:** https://klamsal.github.io/analytics-lab/

## Tools

1. **LP Explorer** — Optimization. Enter and solve a two-variable linear program: feasible region, corner points, level curves, and the optimal solution.
2. **LP Sensitivity Lab** — Optimization. One-at-a-time changes to objective coefficients and right-hand sides: shadow prices, slack, allowable increase / decrease, and a base vs. what-if comparison.
3. **CLT & Confidence Interval Lab** — Probability & Statistics. Sampling simulation showing the Central Limit Theorem and how often a confidence interval actually captures the population mean.
4. **Decision Lab** — Decision Analysis. Editable payoff table with expected value, maximin, maximax, and minimax regret, plus probability sensitivity showing where the expected-value ranking changes.

## Shared example

The two LP tools use the same class example (OktoMask production) as the default and Reset problem, so students solve it in the LP Explorer and then test it in the Sensitivity Lab:

- Maximize Profit = 4 Xv + 3 Xp
- 2 Xv <= 1000; 2.5 Xv + Xp <= 1600; 2.7 Xv + 3 Xp <= 2688; Xp - Xv <= 200; Xv + Xp >= 100; Xv, Xp >= 0
- Optimum: Xv = 440, Xp = 500, Profit = 3,260 (Labor and Fabric binding)

The OktoMask problem is shared course material. All code and explanatory text in this repository are original.

## Teaching design

Every tool follows the same pattern: learning objective and prerequisites, predict first, explore, a short check question with instant feedback, a shareable link that encodes the current settings in the page address, and a downloadable results summary. The site is responsive and keyboard accessible.

## Running it

Open `index.html` in a browser, or use the live GitHub Pages site above. There is no build step.

## License

MIT — see LICENSE.
