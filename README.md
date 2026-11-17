# Reviewflowz for Cursor

Ask Cursor about the customer reviews in your [Reviewflowz](https://www.reviewflowz.com) account. Reviewflowz collects reviews from 200+ platforms, including Google, Trustpilot, G2, Capterra, the App Store and Tripadvisor.

This plugin adds:

- **The Reviewflowz MCP server** (`https://app.reviewflowz.com/mcp/tools`), with 18 tools to read, analyze and organize your reviews.
- **A `reviewflowz` skill** that tells the agent which tool to use for each kind of question.

## Requirements

A Reviewflowz account. [Start a free trial](https://www.reviewflowz.com) if you don't have one.

## Setup

1. Install the plugin from the Cursor Marketplace.
2. The first time the agent calls a Reviewflowz tool, Cursor opens a Reviewflowz sign-in page in your browser.
3. Log in, choose the Reviewflowz account to connect, and select **Authorize**.

There is no API key to configure. Access uses OAuth and can be revoked from Reviewflowz at any time.

## Example prompts

- What's my average rating and reply rate over the last 12 months, by month?
- Show me my 1 to 3 star reviews from the last 30 days.
- Which topics are driving my negative reviews this quarter?
- Compare my locations on review volume and average rating this year.
- Draft a reply to my most recent 1 star review.
- Tag my most recent 1 star review as needs follow-up.

## Tools

| Tool | What it does | Changes data |
|---|---|---|
| `list_review_profiles` | List review profiles (locations, products, apps) | No |
| `get_reviews` | Read reviews, filtered by platform, rating, date or keyword | No |
| `get_stats` | Rating, volume and reply-rate statistics and time series | No |
| `analyze_sentiment` | Topics and sentiment behind reviews | No |
| `compare_profiles` | Compare several profiles side by side | No |
| `draft_reply` | Suggest a reply to one review (never posts it) | No |
| `describe_report_options` | List the dimensions and metrics a custom report can use | No |
| `list_custom_reports` | List saved custom reports | No |
| `run_report` | Run a custom report | No |
| `create_custom_report` | Save a custom report | Yes |
| `list_tags` | List review tags | No |
| `tag_review` / `untag_review` | Add or remove tags on a review | Yes |
| `list_review_owners` | List teammates reviews can be assigned to | No |
| `assign_review_owner` / `unassign_review_owner` | Assign or remove teammates on a review | Yes |
| `resolve_owner_suggestion` | Confirm or reject a suggested teammate | Yes |
| `report_connector_feedback` | Tell the Reviewflowz team what was missing | Yes |

The plugin never posts replies to review platforms, deletes reviews, or changes account settings, billing or users.

## Support

hello@reviewflowz.com · [Privacy policy](https://www.reviewflowz.com/privacy-policy) · [Terms](https://www.reviewflowz.com/terms-of-service)
