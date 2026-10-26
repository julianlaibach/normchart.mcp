# normchart

Build business charts in IBCS notation (International Business Communication
Standards) from a conversation: column, bar, line and waterfall charts with
variance analysis, for reporting and management presentations.

## What it contains

- **The normchart connector** (`https://www.normchart.com/mcp`): ten tools to
  browse the IBCS template catalogue, read and save the charts in your
  normchart account, check a chart before saving it, and show the finished
  chart.
- **The normchart skill**: the workflow the assistant follows — read the
  authoring guide first, start from the closest template, check every
  configuration before saving, and show the finished chart once, at the end.

## Use it

Install the plugin, then connect the normchart connector and sign in with your
normchart account (create one free at [www.normchart.com](https://www.normchart.com)).
Then ask, for example:

- "Use normchart to make an IBCS column chart of our monthly net sales: Jan 120, Feb 135, Mar 128."
- "Which IBCS templates does normchart offer?"
- "Change the title of my normchart chart *Net sales* to *Net sales 2026*."

Charts are saved to your normchart account and can be refined in the
normchart editor.

## Data

The plugin sends the data and instructions you give for a chart to your
normchart account through `www.normchart.com`, which stores the charts you
save there. Signing in uses OAuth; you can revoke access at any time from your
profile on www.normchart.com. The plugin has no access to other accounts and
sends nothing to any other service.

- Privacy policy: <https://www.normchart.com/privacy>
- Support: <https://www.normchart.com/feedback>
