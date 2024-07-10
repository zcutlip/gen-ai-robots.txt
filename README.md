# Generative AI Robots.txt

A robots.txt to tell generative AI scrapers they're unwelcome

## Summary

This is an example `robots.txt` containing entries to tell generative AI scrapers to move along. Please take what entries you like to add to your own website. Maybe some scrapers/gen AI services you feel okay about, so you can leave those out!

The whole point here is freedom. Your content is yours and you should be free to protect as well as share it in whatever ways are right for you.

## Pull Requests

Please submit entries as pull requests.

PR requirements:
- Please, on PR per company/organization
  - E.g., please don't add Google and Facebook crawlers in the same PR
  - However, if Google has several crawlers, grouping them together in a PR is fine
  - This allows each PR to more clearly document what company's crawlers are being blocked
- A comment explaining scraper this entry blocks
  - e.g., `# Perplexity AI`
- At least one comment citing a source explaining this crawler and how it's related to generative AI
  - Please don't editorialize. Save the opinions for the cited source
  - More than one is even better, don't go overboard though
- A well formed `robots.txt` entry, including (someone should be able to copy this to the root of their website, unmodified):
  - The user agent to match
  - a `Disallow: /` directive

Here's an example of a desirable entry:

```
# Perplexity AI
# https://archive.is/22gCl (wired.com)
# https://rknight.me/blog/perplexity-ai-is-lying-about-its-user-agent/
User-Agent: PerplexityBot
Disallow: /
```