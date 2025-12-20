# Community Tools 🚀

A collection of Python tools designed to help open source communities and developer teams work more efficiently.

## 🎯 Tools Included

### 1. **PR Summarizer** ⭐
Automatically generates TL;DR summaries of Pull Requests with:
- Multi-platform support (GitHub, GitLab, Bitbucket)
- Beginner-friendly/educational mode
- PR categorization (bug fix, feature, docs, etc.)
- Contribution suggestions
- Docker support

### 2. **Meeting Action Extractor** 📋
Extracts action items from meeting notes with:
- Discord & Slack integration
- Multiple extraction methods (LLM, regex)
- Formatted output for community platforms
- Group by assignee

### 3. **Dead Link Checker** 🔗
Monitors and reports broken links:
- Recursive crawling
- GitHub Actions integration
- CSV/JSON export
- Auto-issue creation

### 4. **GitHub Star Notifier** ⭐
Get notified when someone stars your repository:
- Web dashboard
- Slack/Discord notifications
- User analytics
- Follower filtering

### 5. **API Rate Limit Monitor** 📊
Monitor API rate limits and get alerts:
- Multi-API support
- Slack/Discord alerts
- Configurable thresholds

### 6. **Domain Expiration Monitor** 🌐
Never lose a domain again:
- WHOIS checking
- Multiple alert thresholds
- Slack notifications

### 7. **Invoice Reminder Bot** 💰
Automated follow-up for unpaid invoices:
- Stripe integration
- Email reminders
- Configurable schedules

### 8. **Post-Mortem Generator** 📝
Generate structured incident post-mortems:
- Interactive CLI
- Template system
- Action item tracking

## 🚀 Quick Start

### PR Summarizer
```bash
cd pr-summarizer
pip install -r requirements.txt
python enhanced_summarizer.py owner/repo 123 --beginner-friendly
```

### Meeting Action Extractor
```bash
cd meeting-action-extractor
pip install -r requirements.txt
python enhanced_extractor.py -i notes.txt -o actions.json --discord
```

### GitHub Star Notifier Dashboard
```bash
cd github-star-notifier
pip install -r requirements.txt
export GITHUB_TOKEN=your_token
export GITHUB_REPO=owner/repo
python dashboard.py
# Open http://localhost:5003
```

## 📚 Documentation

- [Community Tools Analysis](./COMMUNITY_TOOLS_ANALYSIS.md) - Comprehensive analysis
- [Quick Reference](./COMMUNITY_TOOLS_QUICK_REFERENCE.md) - Quick start guide
- [Build Summary](./BUILD_SUMMARY.md) - What's been built
- [PR Summarizer Enhancements](./PR_SUMMARIZER_COMMUNITY_ENHANCEMENTS.md) - Detailed enhancement plan

## 🐳 Docker Support

All tools include Docker support:
```bash
docker build -t pr-summarizer pr-summarizer/
docker run --rm -e GITHUB_TOKEN=xxx pr-summarizer owner/repo 123
```

## 🤝 Contributing

Contributions welcome! These tools are designed for communities, by communities.

## 📄 License

MIT

## 🙏 Acknowledgments

Built with ❤️ for open source communities worldwide.

