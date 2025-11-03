# Issue Templates for Teachers

Welcome! This guide explains how to use GitHub issue templates to request changes to the school activity system.

## Why Use Issue Templates?

Issue templates help you provide all the necessary information for changes to be implemented quickly and accurately by GitHub Copilot. Each template is designed for a specific type of request and will guide you through providing the right details.

## Available Templates

### 🐛 Bug Report
**Use this when:** Something isn't working correctly

**Examples:**
- Colors don't match school colors
- Students can't register for an activity
- Buttons aren't clickable
- Information displays incorrectly

**What you'll need to provide:**
- Description of what's wrong
- What you expected to happen
- Steps to reproduce the problem
- Which part of the system is affected

---

### ✨ Feature Request
**Use this when:** You want to add new functionality

**Examples:**
- Add difficulty levels for activities
- Create a calendar view
- Add a search feature
- Group activities by type

**What you'll need to provide:**
- Clear description of the new feature
- Why it's needed and who benefits
- Acceptance criteria (how to know when it's complete)
- Suggested implementation ideas (optional)

---

### 🎨 UI/Styling Change
**Use this when:** You want to change how things look

**Examples:**
- Change website colors or theme
- Add dark mode
- Update fonts or layout
- Add animations or visual effects
- Update logos or images

**What you'll need to provide:**
- Description of the visual change
- Current appearance
- Desired appearance (be specific with colors, sizes, etc.)
- Design specifications (hex codes, dimensions, etc.)

---

### 📝 Documentation Update
**Use this when:** Documentation needs to be updated or corrected

**Examples:**
- README file is outdated
- Instructions are missing or incorrect
- Help text needs updating
- Code comments need clarification

**What you'll need to provide:**
- Location of the documentation
- What's wrong with it currently
- What it should say instead
- Any additional sections needed

---

### 📊 Data/Content Update
**Use this when:** Activity information or content needs updating

**Examples:**
- Change activity schedules
- Update activity descriptions
- Fix incorrect categorizations
- Update teacher/coach information

**What you'll need to provide:**
- Type of content to update
- Current content
- What it should be changed to
- Urgency level

---

## How to Create an Issue

1. Go to the [Issues tab](../../issues) in GitHub
2. Click the green **"New Issue"** button
3. Choose the template that best fits your request
4. Fill out all required fields (marked with asterisks)
5. Provide as much detail as possible
6. Click **"Submit new issue"**

## Tips for Writing Good Issues

### Be Specific
❌ Bad: "Make it look better"
✅ Good: "Change the primary color to lime green (#00ff00) with dark background (#1a1a1a) for contrast, and add the Octocat mascot from octodex.github.com"

### Include Examples
❌ Bad: "The schedule is wrong"
✅ Good: "Chess Club currently shows Tuesday at 3pm, but it should be Thursday at 4pm"

### Define Success
❌ Bad: "Add difficulty levels"
✅ Good: "Add Beginner, Intermediate, and Advanced difficulty levels that students can filter by. Activities without a level should work as before."

### Provide Context
Include screenshots, error messages, or links to examples when helpful!

## What Happens Next?

Once you submit an issue:
1. **@copilot** (GitHub Copilot agent) will be automatically assigned
2. Copilot will analyze your request and implement the changes
3. Copilot will create a pull request with the proposed changes
4. You (or another reviewer) can review and approve the changes
5. Once approved, the changes will be merged into the system

## Need Help?

If you're not sure which template to use or have questions:
- Start a [Discussion](../../discussions) instead of creating an issue
- Consult the [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- Ask a colleague who has used the system before

## Template Structure

Each template follows this recommended structure for AI-assisted development:

✅ **Clear problem description** - What needs to change and why
✅ **Clear acceptance criteria** - How to know when it's done
✅ **Hints and suggestions** - Ideas for implementation (when relevant)
✅ **Context and limitations** - Any constraints or related information

This ensures GitHub Copilot has all the information needed to implement your request successfully!

---

*Happy requesting! 🎉*
