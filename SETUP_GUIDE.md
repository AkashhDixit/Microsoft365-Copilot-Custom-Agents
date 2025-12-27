# Setup Guide - Microsoft 365 Copilot Custom Agents

This guide provides step-by-step instructions to deploy the custom agents in your Microsoft 365 environment.

## Prerequisites

- Microsoft 365 subscription (Business Standard or higher recommended)
- Access to Microsoft 365 admin center
- Copilot Studio access (Copilot Pro or higher)
- Modern web browser (Chrome, Edge, Safari)
- Admin or appropriate permissions to create/manage agents

## Part 1: Accessing Copilot Studio

### Method 1: Via Microsoft 365 Admin Center

1. Go to [Microsoft 365 Admin Center](https://admin.microsoft.com)
2. Sign in with your Microsoft 365 admin account
3. Navigate to **Settings** > **Org settings** > **Copilot Studio**
4. Click **Create new agent** or **Go to Copilot Studio**
5. You'll be redirected to the Copilot Studio dashboard

### Method 2: Direct Access

1. Visit [Copilot Studio](https://copilot.cloud.microsoft/)
2. Sign in with your Microsoft 365 credentials
3. Click **+ New agent** in the left sidebar

---

## Part 2: Creating the Email Assistant Agent

### Step 1: Create a New Agent

1. In Copilot Studio, click **+ New agent**
2. Name the agent: **Email Assistant (Professional Business English)**
3. Select **Prompt-based agent** as the agent type
4. Click **Create**

### Step 2: Configure the Agent Instructions

1. In the **Instructions** field, paste the complete content from `Email_Assistant_Ak_2.1.txt`
   - Copy all text from the file (from "# Email Assistant Agent (v2.1)" to "--- END OF INSTRUCTIONS ---")
   - Paste into the Instructions field

### Step 3: Configure Agent Settings

**Basic Settings:**
- **Agent Name**: Email Assistant (v2.1)
- **Description**: Professional email rewriting agent for Indian MNC standards
- **Icon**: Select a communication/email icon

**Advanced Settings (Optional):**
- **Language**: English (or English, Hindi for bilingual support)
- **Greeting Message**: "Hello! I'm your Email Assistant. I help rewrite and improve your emails for professional business communication aligned with Indian MNC standards."

### Step 4: Test the Agent

1. Click **Test** in the bottom-right corner
2. Try a sample message:
   ```
   Please rewrite this: "hi can u send me the files asap? we need them now"
   ```
3. Verify the output is professional and grammatically correct

### Step 5: Publish

1. Click **Publish** in the top-right
2. Choose deployment channels:
   - **Microsoft Teams**: Enable for Teams conversations
   - **Outlook**: Enable for email integration
   - **Web**: Enable for web access
3. Click **Publish**

---

## Part 3: Creating the SQL Developer Agent

### Step 1: Create a New Agent

1. In Copilot Studio, click **+ New agent**
2. Name the agent: **SQL Developer Assistant**
3. Select **Prompt-based agent**
4. Click **Create**

### Step 2: Configure the Agent Instructions

1. In the **Instructions** field, paste the complete content from `Universal_SQL_Developer_Agent.txt`
   - Copy all text from the file (from "# Universal SQL Developer Agent" to "--- END OF INSTRUCTIONS ---")
   - Paste into the Instructions field

### Step 3: Configure Agent Settings

**Basic Settings:**
- **Agent Name**: SQL Developer Assistant
- **Description**: Cross-platform SQL query analyzer and optimizer
- **Icon**: Select a database/code icon

**Advanced Settings (Optional):**
- **Language**: English
- **Greeting Message**: "Hello! I'm your SQL Developer Assistant. I help analyze, debug, and optimize SQL queries across Oracle, SQL Server, MySQL, PostgreSQL, and SQLite."

### Step 4: Test the Agent

1. Click **Test** in the bottom-right corner
2. Try a sample query:
   ```
   SELECT * FROM users WHERE active = 1 ORDER BY created_at DESC LIMIT 10
   
   This is for PostgreSQL. Can you optimize this?
   ```
3. Verify it detects the SQL dialect and provides optimization suggestions

### Step 5: Publish

1. Click **Publish** in the top-right
2. Choose deployment channels:
   - **Microsoft Teams**: For team collaboration
   - **Web**: For standalone access
3. Click **Publish**

---

## Part 4: Integration with Microsoft 365 Applications

### Microsoft Teams Integration

1. Once published, open Microsoft Teams
2. Search for your agent by name
3. Click **Add** to add the agent to your Teams workspace
4. Use the agent in:
   - Team channels
   - Direct messages
   - Group chats

### Outlook Integration

1. Open Outlook (Web or Desktop)
2. Compose a new email
3. Look for the Copilot icon or agent indicator
4. Select **Email Assistant** from the available tools
5. Enter your draft email and get suggestions

### Web Access

1. Share the agent URL from Copilot Studio
2. Users can access via the web link
3. No additional software required

---

## Part 5: Customization & Advanced Configuration

### Adding Knowledge Base (Optional)

1. In agent settings, go to **Knowledge** section
2. Upload relevant documents:
   - Company communication guidelines
   - SQL best practices documentation
   - Custom query patterns
3. The agent will reference these in responses

### Setting Up Actions (Optional)

1. Go to **Actions** section
2. Connect to:
   - **Microsoft Lists**: For storing query optimization history
   - **Power Automate**: For automated workflows
   - **Custom APIs**: For enterprise integrations

### Configuring Monitoring

1. Go to **Analytics** tab
2. Monitor:
   - Usage patterns
   - User satisfaction
   - Common queries/requests
   - Agent performance metrics

---

## Part 6: Managing & Updating Agents

### Version Updates

1. When you want to update the instructions:
   - Click **Edit** on the agent
   - Modify the Instructions field
   - Save and publish
   - Version history is automatically maintained

### User Management

1. Go to **Settings** > **Permissions**
2. Add team members who can:
   - View agent analytics
   - Suggest improvements
   - Test new versions

### Monitoring Performance

1. Regular checks (weekly recommended):
   - Review **Analytics** for usage patterns
   - Check **Feedback** for user suggestions
   - Monitor **Error logs** for failures

---

## Troubleshooting

### Issue: Agent not responding correctly

**Solution:**
1. Verify the full instruction set was copied
2. Ensure no formatting was lost during paste
3. Check if the agent was re-published after edits
4. Test with simpler, clearer prompts first

### Issue: Integration not working with Teams

**Solution:**
1. Confirm the agent is published to Teams
2. Refresh Teams or log out/log in
3. Check if your admin has enabled Copilot Studio integration
4. Verify user has Copilot Pro license

### Issue: SQL queries returning unexpected results

**Solution:**
1. Specify the SQL dialect explicitly ("This is Oracle SQL")
2. Provide more context about the data structure
3. Show the complete query, not just fragments
4. Include error messages if available

### Issue: Email suggestions not meeting requirements

**Solution:**
1. Clarify the audience and tone needed
2. Provide examples of desired style
3. Mention any specific standards to follow
4. Include context about the situation

---

## Best Practices

### For Email Assistant Agent

✅ **Do:**
- Provide complete context about who you're emailing
- Mention the tone you want (formal, friendly, assertive)
- Include any specific requirements or standards
- Ask for clarifications if suggestions seem unclear

❌ **Don't:**
- Send sensitive information (passwords, financial data)
- Expect the agent to replace human review for critical communications
- Use without proofreading final emails
- Assume all suggestions are grammatically perfect

### For SQL Developer Agent

✅ **Do:**
- Specify the database platform/version
- Provide schema context if the agent needs it
- Ask for specific optimization types (performance, readability)
- Request explanations for complex changes

❌ **Don't:**
- Use without testing queries in your environment first
- Assume all suggestions are optimal for your specific data
- Deploy without validating the optimized query
- Skip understanding the suggested changes

---

## Support & Feedback

### Getting Help

1. **Microsoft Support**: Visit [Microsoft Support](https://support.microsoft.com/)
2. **Copilot Studio Docs**: Check [official documentation](https://learn.microsoft.com/en-us/microsoft-cloud/copilot/)
3. **Community Forums**: Join Microsoft 365 community discussions

### Providing Feedback

1. In Copilot Studio, click the **Feedback** icon
2. Share:
   - What worked well
   - Areas for improvement
   - Feature requests
   - Bug reports

---

## Security & Compliance

### Data Handling

- **Email Content**: Only processed within your Microsoft 365 tenant
- **SQL Queries**: Analyzed without storing execution results
- **No External Sharing**: All data remains within your organization

### Compliance

- Agents comply with Microsoft 365 security standards
- Data is encrypted in transit and at rest
- Regular security audits recommended
- Document usage for compliance reporting if needed

---

## Next Steps

1. ✅ Set up both agents in your Copilot Studio
2. ✅ Test thoroughly with your team
3. ✅ Deploy to Teams and other channels
4. ✅ Train users on best practices
5. ✅ Monitor analytics and gather feedback
6. ✅ Iterate and improve based on usage patterns

---

**Last Updated**: December 2025
**Maintained By**: Akash Dixit
**Questions?** Contact or open an issue in the repository
