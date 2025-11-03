# GitHub Copilot Coding Agent Guide

This guide answers common questions about using GitHub Copilot coding agent and clarifies the different workflows available.

## How to Use GitHub Copilot Coding Agent

GitHub Copilot coding agent can be accessed through **two primary workflows**:

### 1. GitHub Web Interface (GitHub GUI)

**This is the recommended approach for most users**, especially those who are not developers or prefer not to work in a code editor.

#### Workflow:
1. Navigate to your repository on GitHub.com
2. Go to the **Issues** tab
3. Create a new issue or select an existing one
4. In the issue's **Assignees** section, select **@copilot**
5. Copilot will automatically:
   - Create a new branch
   - Create a pull request
   - Begin working on the issue
   - Provide updates in the PR conversation

#### Advantages:
- ✅ No local development environment needed
- ✅ No code editor or extensions required
- ✅ Works entirely in your browser
- ✅ Perfect for non-technical staff
- ✅ Accessible from any device with internet

#### When to use:
- You're a teacher, manager, or non-developer requesting changes
- You want a quick way to delegate work
- You don't need to see the code changes locally before they're submitted
- You prefer the GitHub web interface

---

### 2. VS Code with GitHub Pull Request Extension

This workflow is **optional** and designed for developers who want more control and local interaction with Copilot's work.

#### Requirements:
- Visual Studio Code (VS Code) installed
- GitHub Pull Request & Issues extension installed
- GitHub Copilot extension installed (for other Copilot features)

#### Workflow:
1. Install the [GitHub Pull Request & Issues extension](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
2. Open your repository in VS Code
3. Use the GitHub extension to:
   - View issues
   - Assign issues to @copilot
   - Monitor pull requests created by Copilot
   - Review and comment on Copilot's changes
   - Approve and merge PRs

#### Advantages:
- ✅ Full integration with your development environment
- ✅ View and test Copilot's changes locally
- ✅ Use other VS Code features alongside Copilot
- ✅ Faster review and iteration cycles

#### When to use:
- You're a developer working on the repository
- You want to test changes locally before merging
- You prefer working in VS Code over the web interface
- You need to make additional changes alongside Copilot's work

---

## Do You Need the GitHub Pull Request Extension?

### Short Answer: **No, it's optional**

The GitHub Pull Request extension is **not required** to use GitHub Copilot coding agent. However, it enhances the experience if you're working in VS Code.

### Detailed Explanation:

| Scenario | Extension Needed? | Explanation |
|----------|------------------|-------------|
| Using GitHub web interface only | ❌ No | Copilot works entirely through GitHub.com |
| Assigning issues to Copilot | ❌ No | Assignment happens on GitHub.com |
| Reviewing Copilot's pull requests | ❌ No | Can be done entirely on GitHub.com |
| Working in VS Code | ⚠️ Optional but recommended | Extension provides better integration |
| Local testing of changes | ⚠️ Optional but recommended | Makes it easier to pull and test branches |

### What the Extension Provides:

If you choose to install the GitHub Pull Request extension in VS Code, you get:

1. **Issue Management**: View and manage issues directly in VS Code
2. **PR Review**: Review pull requests without leaving your editor
3. **Branch Management**: Easily checkout branches created by Copilot
4. **Inline Comments**: Add review comments directly in the code
5. **Approval Workflow**: Approve or request changes from VS Code

### Installation (Optional):

If you want to use the extension:

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
3. Search for "GitHub Pull Requests"
4. Click Install on "GitHub Pull Requests and Issues"
5. Sign in to your GitHub account when prompted

---

## Recommended Workflow for Different Users

### For Teachers and Non-Technical Staff

**Use the GitHub web interface exclusively:**

1. Go to your repository on GitHub.com
2. Create an issue describing what you need
3. Assign the issue to @copilot
4. Wait for Copilot to create a pull request
5. Review the PR on GitHub.com
6. Approve and merge when satisfied

**No extensions or code editors needed!**

---

### For Developers

**Hybrid approach (recommended):**

1. **Assign issues**: Use GitHub.com or VS Code with the PR extension
2. **Monitor progress**: Check GitHub.com or VS Code
3. **Review changes**: 
   - For simple changes: Review on GitHub.com
   - For complex changes: Use VS Code with PR extension to test locally
4. **Merge**: Approve and merge from either interface

**Extensions recommended but not required.**

---

## Frequently Asked Questions

### Q: Can I assign Copilot to an issue from my phone?
**A:** Yes! The GitHub mobile app allows you to assign issues to @copilot, though the experience is optimized for desktop browsers.

### Q: Does Copilot need access to my local machine?
**A:** No. Copilot runs entirely in GitHub Actions and doesn't access your local machine.

### Q: Can multiple people work with Copilot on different issues?
**A:** Yes. Each issue assignment creates a separate branch and pull request, so multiple Copilot tasks can run in parallel.

### Q: What if I don't have VS Code installed?
**A:** That's perfectly fine! You can use GitHub Copilot coding agent entirely through the GitHub web interface without ever installing VS Code.

### Q: Is the GitHub Pull Request extension free?
**A:** Yes, the extension is free and open source.

### Q: Can I use other code editors like PyCharm or Sublime?
**A:** While other editors don't have the same GitHub PR extension, you can still use GitHub Copilot coding agent through the GitHub web interface. The code changes Copilot makes can be reviewed in any editor once you pull the branch.

---

## Getting Started Checklist

- [ ] Enable Copilot coding agent for your repository (Settings → Copilot → Coding agent)
- [ ] Verify you have write access to the repository
- [ ] Decide on your preferred workflow (GitHub GUI vs VS Code)
- [ ] (Optional) Install GitHub Pull Request extension if using VS Code
- [ ] Create or select an issue to assign to Copilot
- [ ] Assign the issue to @copilot
- [ ] Monitor the automatically created pull request
- [ ] Review, provide feedback, or approve the changes

---

## Additional Resources

- [GitHub Copilot Coding Agent Documentation](https://docs.github.com/en/copilot/using-github-copilot/using-github-copilot-coding-agent)
- [GitHub Pull Request Extension](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- [Development Guide](./how-to-develop.md) - For local development setup
- [Copilot Instructions](../.github/copilot-instructions.md) - Repository-specific guidance for Copilot

---

## Summary

- ✅ GitHub Copilot coding agent works through GitHub.com - **no extensions required**
- ✅ VS Code with GitHub Pull Request extension is **optional** for enhanced workflow
- ✅ Choose the workflow that best fits your role and comfort level
- ✅ Non-technical users can effectively use Copilot without any code editor
- ✅ Developers get extra benefits from using VS Code with the extension

**The key takeaway**: You can start using GitHub Copilot coding agent right now through GitHub.com without installing anything!
