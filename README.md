# Skill grouping demo 3

A third copy of the Skill Sync fixtures. Every skill has a new name, so you can import it next
to `skill-grouping-demo` and `skill-grouping-demo-2` with no name clash. Each skill folder has
the new name too, except `broken-skill` and `ignore-instructions`.

The fixtures and their expected verdicts are the same as in demo 2. Read the README of
`skill-grouping-demo` for each case, and use the table below to find the new name.

`ignore-instructions` still has the same name as `log-triage`, to test a duplicate name.

## Branches

| Branch | Content |
|---|---|
| `main` | Rounds 1 to 4: grouping, the security check verdicts and the warning skills. |
| `long-changes` | `main` plus long rewrites of twelve skills. Each update should pass. |
| `mix-updates` | `main` plus a mix of passed, warning and blocked updates, a deleted skill and a new skill. |
| `broken-manifest` | `main` plus `plugins/writing/.claude-plugin/plugin.json`, which is not valid JSON. |

## Test the review of updates

1. Connect `https://github.com/RobTF9/skill-grouping-demo-3` and import skills.
2. Move `main` to one of the update branches, for example
   `git push --force origin mix-updates:main`.
3. Click Check now.

## Names

| Name in demo 1 and 2 | Name in demo 3 |
|---|---|
| api-design | endpoint-planner |
| blog-post | article-drafter |
| brand-voice | house-style |
| chat-transcript | chat-log-cleaner |
| ci-status | pipeline-status |
| code-review | diff-inspector |
| csv-cleanup | spreadsheet-tidy |
| dashboard-review | chart-audit |
| db-migrations | schema-change-guide |
| debug-logs | log-triage |
| deploy-helper | staging-rollout |
| docs-search | manual-lookup |
| editorial | copy-editor |
| email-reply | inbox-responder |
| emoji-guide | emoji-picker |
| faq-writer | help-center-faq |
| file-namer | document-namer |
| hidden-unicode | text-translator |
| incident-review | outage-retro |
| kpi-definitions | metric-definitions |
| legacy | old-cursor-skill |
| linkedin-post | social-update |
| long-description | wordy-summary |
| meeting-notes | minutes-taker |
| metric-glossary | kpi-explainer |
| onboarding-checklist | first-week-plan |
| override-tone | shouty-rewriter |
| oversized-notes | bulky-notes |
| phishing-awareness | scam-email-training |
| pr-description | change-summary |
| refactor-plan | cleanup-plan |
| release-checklist | ship-checklist |
| release-notes | changelog-writer |
| send-report | weekly-uploader |
| sql-helper | query-writer |
| standalone-helper | lone-helper |
| status-badge | reply-badge |
| support-macro | ticket-macro |
| thread-scheduler | post-scheduler |
| tweet-thread | microblog-thread |
| write-tests | unit-test-writer |
| press-release-for-a-product-launch-… (over 128 characters) | launch-announcement-with-founder-quotes-… (over 128 characters) |
