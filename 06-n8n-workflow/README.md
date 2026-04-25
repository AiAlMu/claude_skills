# n8n Workflow Designer

Designs a complete n8n automation workflow from a plain-English description of a business process. Lists every node, the data flow, and beginner tips.

## Install

Copy `n8n-workflow.md` to your `.claude/commands/` folder.

## Usage

```
/n8n-workflow [describe the business process to automate]
```

## Example

```
/n8n-workflow When a new row is added to a Google Sheet with a customer email, send them a welcome email via Gmail, then add them to a Notion database
```

Claude will output a step-by-step node list you can follow in n8n.
