```
 ██████╗ ███████╗ ██████╗██╗      █████╗ ██╗███╗   ███╗██████╗ 
 ██╔══██╗██╔════╝██╔════╝██║     ██╔══██╗██║████╗ ████║██╔══██╗
 ██████╔╝█████╗  ██║     ██║     ███████║██║██╔████╔██║██████╔╝
 ██╔══██╗██╔══╝  ██║     ██║     ██╔══██║██║██║╚██╔╝██║██╔══██╗
 ██║  ██║███████╗╚██████╗███████╗██║  ██║██║██║ ╚═╝ ██║██║  ██║
 ╚═╝  ╚═╝╚══════╝ ╚═════╝╚══════╝╚═╝  ╚═╝╚═╝╚═╝     ╚═╝╚═╝  ╚═╝
                                                              
 The Intelligent File Organization Assistant for Claude Code
```

# Reclaimr

## ⚠️ IMPORTANT WARNING ⚠️

**THIS IS EXPERIMENTAL SOFTWARE. USE AT YOUR OWN RISK.**

- **ALWAYS make a backup of your files before using these commands**
- **AI is non-deterministic - results may vary between runs**
- **Never use on critical directories without testing first**
- **Review ALL recommendations before approving any actions**
- **No liability is accepted for any data loss or unexpected results**

## Overview

This project provides a portable set of Claude Code slash commands that can be dropped into any directory you want to organize. Simply place the `.claude` directory in your target folder, run Claude Code there, and use the slash commands to organize that directory.

## 💭 Why I Built This

I built Reclaimr to inspire others to explore the creative possibilities of Claude Code beyond just coding assistance. On the max plan, there are times when we're sleeping or away - why not let Claude Code handle some maintenance tasks for us?

File organization is just the beginning. Imagine what else Claude Code could do while you're away:
- Monitor logs and summarize issues
- Organize research notes
- Analyze data and prepare reports
- Sanitize datasets
- Generate documentation

**What will you build with Claude Code?** I'd love to see your ideas and extensions to this project. Together, we can expand what's possible with AI assistants working alongside us.

## Key Features

- **Portable Organization**: Drop the `.claude` directory into any folder you want to organize
- **Intelligent Categorization**: Claude sorts files into logical categories based on file type and content
- **Time-Based Archiving**: Implements a 7-day active period and 30-day review policy
- **Learning System**: Claude remembers your preferences and corrections over time
- **Package Preservation**: Identifies related files that should be kept together

## How It Works

1. Copy the `.claude` directory to the folder you want to organize
2. Navigate to that folder in your terminal
3. Run `claude` to launch Claude Code
4. Use slash commands like `/organize-directory` or `/identify-old-files`
5. Claude will analyze and organize the current directory

## Documentation

The detailed documentation is now stored in the `.claude` directory:

- `.claude/CLAUDE.md`: Complete instructions for Claude's file organization
- `.claude/commands/`: Slash commands for common file organization tasks
- `.claude/claude_assistant.md`: Detailed guide on how Claude operates as an assistant

## Available Commands

The following slash commands are available:

- `/organize-directory`: Categorize all files in the current directory
- `/identify-old-files`: Find files older than 7/30 days for review or deletion
- `/find-packages`: Identify application bundles that should stay together
- `/cleanup-directory`: Comprehensive cleanup with categorization and age detection
- `/archive-files`: Apply 7/30 day policy with intelligent human judgment
- `/track-learning`: Review what Claude has learned about your preferences

## Installation

```bash
# Clone or download this repository
git clone https://github.com/vanzan01/claude-code-reclaimr.git

# Copy the .claude directory to any folder you want to organize
cp -r claude-code-reclaimr/.claude ~/Downloads/

# Navigate to that directory
cd ~/Downloads

# Run Claude Code (requires installation via npm)
claude
```

## Benefits

This approach offers several advantages:

- **Portability**: Organize any directory by simply copying the .claude folder there
- **Consistency**: The same organization rules applied everywhere
- **Tracking**: Store your organization preferences in git
- **Learning**: Claude remembers your preferences between sessions
- **Customization**: Edit the command files to change organization behavior

## Safe Usage Guidelines

To use this tool safely:

1. **Start small**: Test on a directory with just a few files first
2. **Make backups**: Always create a backup copy before organizing important files
3. **Review carefully**: Check all suggestions before approving any actions
4. **Dry runs**: Ask Claude to explain what it would do before taking action
5. **Test restoration**: Ensure you can restore from your backups if needed

Remember that Claude will never execute file operations without your explicit approval. Always review the suggested changes before giving permission to proceed.

## 🌟 Join the Community

I'd love to hear how you're using Reclaimr and what other Claude Code tools you're creating! Here's how to get involved:

- ⭐ **Star this repo** if you find it useful
- 🔀 **Fork and enhance** with your own ideas
- 🐛 **Open issues** for bugs or suggestions
- 🔄 **Submit PRs** – *Fun fact: I'll be using Claude Code itself to handle issues and PRs!*
- 📝 **Share your experience** in discussions
- 🔗 **Connect with me** to collaborate on more Claude Code projects

Let's push the boundaries of what's possible with AI assistants in our workflows. From automating routine tasks to creating intelligent systems that work while we sleep, the possibilities are endless!

## 🙏 Acknowledgements

This project was inspired by the incredible capabilities of Claude Code and Anthropic's vision for AI assistants. Special thanks to the entire Anthropic team for making this tool available to developers.

*Built with ❤️ and Claude Code*

## 🤖 Meta: The Claude Code Experience

In the spirit of transparency: this entire project—from concept to code to documentation—was developed with Claude Code as my partner. The slash commands, organization logic, and even this README were all created through natural language conversations with Claude.

It's a real testament to how AI assistants can help bring ideas to life quickly. My favorite part? I'm running Claude Code to maintain this repository too—so when you submit issues or PRs, they'll be reviewed by Claude Code first! It's Claude Code all the way down. 😄