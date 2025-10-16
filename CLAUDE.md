# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a documentation and content repository for curating coding tools, updates, and news. It is NOT a software project with code to build or test.

## Content Organization

When adding new content about coding tools, consider organizing them in the following structure:

```
/tools/
  /languages/        # Tools organized by programming language
  /categories/       # Tools organized by purpose (IDE, linting, testing, etc.)
  /updates/          # Latest tool updates and releases
/guides/             # How-to guides for specific tools
/news/              # Industry news and announcements
```

## Common Tasks

### Adding New Tool Documentation
1. Create appropriate directory structure if not exists
2. Use consistent markdown formatting for tool entries
3. Include: tool name, purpose, latest version, key features, and links

### Updating Tool Information
1. Check existing documentation in relevant directory
2. Update version information and changelog
3. Maintain consistent formatting with existing entries

## Content Guidelines

- Each tool entry should include: name, description, latest version, official website, and key features
- Use markdown for all documentation
- Include practical examples where applicable
- Maintain alphabetical ordering within categories
- Add relevant tags/labels for easier discovery

## Repository Maintenance

Since this is a content repository:
- No build/test commands needed
- Focus on content quality and organization
- Keep information current and accurate
- Ensure all links are working

## Updating README.md with Latest Tools

When asked to update the list with new tools/information:

1. **Research Sources**
   - Use WebSearch to find latest Stack Overflow Developer Survey results
   - Search for official tool changelogs and release notes
   - Look for "[tool name] 2025 new features" or "[tool name] updates [current year]"
   - Check Model Context Protocol ecosystem for new MCP servers
   - Review official blogs: VS Code, GitHub, Google I/O, AWS announcements

2. **Key Sections to Update**
   - **Quick Stats** - Update with latest survey data (developer counts, percentages)
   - **What's Hot** - Reflect current trends and emerging technologies
   - **Most Reliable AI Tools** - Add new tools, update existing tool features
   - **Latest Updates** - Add new section or update existing with version-specific features
   - **MCP Servers** - Add newly released servers with dates and capabilities
   - **Last Updated** - Always update the footer with current month/year

3. **Format Guidelines**
   - Use **bold** for tool names and version numbers
   - Include dates in parentheses for major releases (e.g., "May 2025")
   - Use bullet points with dashes for features
   - Keep descriptions concise (1-2 lines per feature)
   - Add links using markdown format: [text](url)
   - Maintain consistent emoji usage (📊, 🔥, 🏆, 🆕, 🔌, 📅)

4. **Data Attribution**
   - Always cite sources (Stack Overflow Survey year, official changelogs)
   - Include survey sample size when available
   - Reference specific version numbers for tools
   - Note when features are in preview/beta vs generally available (GA)

5. **Content Freshness Indicators**
   - Mark preview/beta features appropriately
   - Use "(coming soon)" for announced but unreleased features
   - Include "New in [year]" subsections for clarity
   - Update the "Last Updated" section at the bottom

## Common Update Patterns

### When Adding New AI Tools
```markdown
**[Tool Name]** - Key differentiator, main feature, pricing model
```

### When Adding Version Updates
```markdown
### [Tool Name] v[Version] ([Month Year])
- **Feature Name** - Brief description of what it does
- **Another Feature** - Brief description
```

### When Adding MCP Servers
```markdown
**[Server Name] ([Month Year])**
- **Component 1** - What it does
- **Component 2** - What it does
- Overall capability description
```

## Git Commit Messages for Updates

Follow this pattern for documentation updates:
```
Update coding tools documentation with [year] [topic]

Major updates:
- [Specific change 1]
- [Specific change 2]
- [Specific change 3]
```

## Quality Checklist

Before committing updates, verify:
- [ ] All statistics have sources cited
- [ ] Version numbers are accurate
- [ ] Dates are included for major releases
- [ ] Links are properly formatted
- [ ] Consistent markdown formatting
- [ ] "Last Updated" section reflects current update
- [ ] No typos or grammatical errors
- [ ] Emoji usage is consistent with existing style