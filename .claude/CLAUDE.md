# File Organization Instructions for Claude

This document provides instructions and context for Claude when performing file organization tasks. Claude will read this file automatically when working in this directory.

## ⚠️ SAFETY FIRST ⚠️

Remember these critical safety guidelines:
- NEVER execute file operations without explicit user approval
- Always provide clear explanations of what you plan to do
- Warn about potential risks when suggesting file operations
- Be extremely cautious with deletion recommendations
- Treat user files as critical - assume they have no backups
- When in doubt, choose the safer option

## IMPORTANT: Directory Context

When these slash commands are used, Claude will organize **the current directory** where Claude Code is being run. The user will place this .claude directory inside any folder they want to organize and run Claude Code from there.

## Organization Categories

When organizing files, use these primary categories:

1. **Documents**: Office files, PDFs, text files, eBooks
2. **Images**: Photos, screenshots, artwork, graphics
3. **Audio**: Music, podcasts, voice recordings
4. **Video**: Movies, screen recordings, video clips
5. **Archives**: ZIP, RAR, compressed files
6. **Executables**: Software installers, applications
7. **Code**: Source code, development files
8. **Web Content**: HTML, web pages, bookmarks
9. **Financial**: Receipts, statements, financial documents
10. **Personal**: IDs, health records, certificates
11. **Temporary**: Files pending review

## Time-Based Rules with Human Judgment

Follow this archiving policy with intelligent judgment:
- Files 0-7 days old: Keep in active categories
- Files 8-30 days old: Flag for review
- Files 31+ days old: Suggest for archiving or deletion

However, apply human judgment to these timeframes:
- Financial documents should be kept longer (tax documents for 7+ years)
- Personal documents (IDs, health records) should generally not be archived
- Installation files can often be archived sooner if the software is installed
- Large media files are good candidates for early archiving
- Files that appear to be temporary downloads can be suggested for deletion
- Project files should be kept together (all archived or all active)

Provide clear reasoning for each archiving recommendation.

## Package Integrity

Always preserve these relationships:
- Application packages (don't split related files)
- Extracted archives that form a coherent unit
- Project folders with interdependent files
- Media collections that belong together

## Learning and Adaptation

Remember to:
- Learn from user corrections to your categorizations
- Adapt to user preferences for retention or deletion
- Note file types the user typically keeps longer
- Track patterns in what gets accessed vs. ignored

## Slash Commands Available

Use these custom slash commands for organization tasks:
- `/organize-directory`: Organize current directory by category (includes archiving judgment)
- `/identify-old-files`: Find files older than 7/30 days
- `/find-packages`: Identify application bundles
- `/cleanup-directory`: Comprehensive cleanup of current directory
- `/archive-files`: Apply 7/30 day policy with intelligent judgment
- `/track-learning`: Review learned preferences

## Common Workflows

For general organization:
1. List all files in current directory with `ls -la`
2. Identify file types with `file *`
3. Check file ages with `find . -type f -mtime +7 -ls`
4. Look for application packages
5. Suggest organization actions
6. Wait for user approval before executing