# Integrations

## Connect your tools

GitBook integrates with popular development tools to streamline your workflow.

### Git providers

Sync your documentation with:

- **GitHub** - Sync with GitHub repositories
- **GitLab** - Sync with GitLab projects

### Communication

- **Slack** - Get notifications in Slack channels
- **Discord** - Community notifications

### Analytics

- **Google Analytics** - Track page views and user behavior
- **Plausible** - Privacy-friendly analytics

### Search

- **Algolia** - Enhanced search capabilities

### Setting up integrations

1. Go to your Space **Settings**
2. Click on **Integrations**
3. Select the integration you want to enable
4. Follow the authorization steps

### API access

You can also access GitBook programmatically:

```javascript
const response = await fetch('https://api.gitbook.com/v1/spaces', {
  headers: {
    'Authorization': 'Bearer YOUR_API_TOKEN'
  }
});
```
