# Instagram MCP Server

[![MCP Compatible](https://img.shields.io/badge/MCP-Compatible-blue)](https://insightfulpipe.com/mcp-servers/instagram)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Connect Instagram Business accounts to AI assistants for analytics and content management.**

The Instagram MCP server enables Claude, ChatGPT, Cursor, and other AI assistants to analyze your Instagram performance. Monitor engagement, track follower growth, publish content, and get AI-powered content recommendations.

![Instagram MCP Server](https://insightfulpipe.com/images/instagram.svg)

## MCP Server URL

```
https://instagram.insightfulmcp.com/
```

## What is Instagram MCP?

Instagram MCP is a **remote Model Context Protocol server** that connects your Instagram Business or Creator account to AI assistants. This integration allows you to:

- Query Instagram analytics using natural language
- Analyze post, Story, and Reels performance
- Track follower growth and audience demographics
- Publish posts and manage comments
- Discover other business accounts

## Installation

### Claude

1. Copy the MCP Server URL: `https://instagram.insightfulmcp.com/`
2. Open [Claude Connectors Settings](https://claude.ai/settings/connectors)
3. Scroll to the bottom and click **Add custom connector**
4. Paste the URL and click **Add**
5. Click **Connect** on the connector to start authorization
6. Click **Authorize access** in the browser to complete the connection

### ChatGPT

1. Copy the MCP Server URL: `https://instagram.insightfulmcp.com/`
2. Open ChatGPT Settings → **Connections**
3. Click **Add Connection** and paste the URL
4. Authorize with your InsightfulPipe account

### Claude Code

```bash
claude mcp add instagram https://instagram.insightfulmcp.com/
```

### Cursor

1. Open Cursor Settings → **MCP Servers**
2. Add new server with URL: `https://instagram.insightfulmcp.com/`
3. Authorize the connection

## Available Actions

### Read Actions

| Action | Description |
|--------|-------------|
| `get_profile` | Get Instagram business profile information |
| `get_media` | List recent media posts for the Instagram account |
| `get_media_by_id` | Get details for a specific media post |
| `get_media_insights` | Get insights for a specific media post |
| `get_account_insights` | Get account-level insights and analytics |
| `get_stories` | List current stories for the Instagram account |
| `get_media_comments` | Get comments on an Instagram media post |
| `get_comment_by_id` | Get details for a specific comment by ID |
| `get_comment_replies` | Get replies to a specific comment |
| `get_business_discovery` | Get profile info and media metrics for another Instagram Business or Creator account by username |

### Write Actions

| Action | Description |
|--------|-------------|
| `create_comment` | Create a new comment on an Instagram media post |
| `reply_to_comment` | Reply to a comment on Instagram media |
| `hide_comment` | Hide or unhide a comment on Instagram media |
| `delete_comment` | Delete a comment from Instagram media |
| `toggle_media_comments` | Enable or disable comments on Instagram media |
| `publish_post` | Publish an image or video post to Instagram (combines container creation, status check, and publishing) |

## Usage Examples

### Profile Performance

```
"How is my Instagram performing this week?"
```

### Content Analysis

```
"Which of my Instagram posts got the most engagement this month?"
```

### Audience Insights

```
"What are my Instagram audience demographics?"
```

### Best Posting Times

```
"When are my followers most active on Instagram?"
```

### Competitor Research

```
"Show me the profile and recent posts from @competitor_brand"
```

### Publish Content

```
"Publish this image to Instagram with the caption 'New product launch!'"
```

## Supported Instagram Features

- **Feed Posts** - Photo and carousel analytics
- **Instagram Reels** - Short-form video performance
- **Instagram Stories** - 24-hour content insights
- **Profile Analytics** - Account-level metrics
- **Audience Insights** - Follower demographics
- **Business Discovery** - Research other accounts

## Supported Metrics

| Metric | Description |
|--------|-------------|
| Followers | Total follower count |
| Reach | Unique accounts reached |
| Impressions | Total content views |
| Engagement Rate | Interactions / reach |
| Profile Visits | Profile page views |
| Website Clicks | Link taps |
| Saves | Content bookmarks |
| Shares | Content shares |

## Why Instagram MCP?

### For Content Creators
- **Understand your audience** - Deep demographic insights
- **Optimize content** - Data-driven posting strategy
- **Track growth** - Monitor follower milestones

### For Brands
- **Brand awareness** - Track reach and impressions
- **Engagement monitoring** - Measure audience connection
- **Competitive insights** - Benchmark performance

### For Social Media Managers
- **Content management** - Publish and moderate from AI
- **Automated reporting** - Generate performance reports
- **Client communication** - Easy-to-explain insights

## Security & Privacy

- **Meta Official API** - Instagram Graph API
- **OAuth 2.0** - Secure authentication
- **Granular permissions** - Control read vs write access
- **Business/Creator only** - Personal accounts not supported

## Related MCP Servers

- [Facebook Pages MCP](https://insightfulpipe.com/mcp-servers/facebook-pages) - Facebook analytics
- [Facebook Ads MCP](https://insightfulpipe.com/mcp-servers/facebook-ads) - Meta advertising
- [TikTok Ads MCP](https://insightfulpipe.com/mcp-servers/tiktok-ads) - TikTok marketing

## Resources

- [Documentation](https://insightfulpipe.com/docs/instagram)
- [Video Tutorial](https://www.youtube.com/playlist?list=PLJNzvjxzI5Xwe__BJJLAelSF0ewO3mEFk)
- [InsightfulPipe Blog](https://insightfulpipe.com/blogs)

## Support

- **Documentation**: [insightfulpipe.com/docs](https://insightfulpipe.com/docs)
- **Email**: support@insightfulpipe.com

## License

MIT License - see [LICENSE](LICENSE) for details.
