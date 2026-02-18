# How to Request Changes

This guide explains how teachers can request changes to the Mergington High School Activities website without needing to modify code directly.

## Using Issue Templates

When you need to make a change to the activities system, you can create a new issue on GitHub. We have created easy-to-use forms for the most common requests.

### How to Create an Issue

1. Go to the [Issues page](https://github.com/andrefontourainvillia/skills-expand-your-team-with-copilot4/issues)
2. Click the green **"New issue"** button
3. You'll see a list of templates - choose the one that matches what you need
4. Fill out the form with the required information
5. Click **"Submit new issue"**

The system will automatically assign @copilot (our coding agent) to work on your request!

## Available Templates

### 1. Add New Activity
**When to use:** You want to add a new extracurricular activity to the system.

**What you'll need to provide:**
- Activity name (e.g., "Drama Club", "Robotics Team")
- Description of what students will do
- Schedule (which days and what times)
- Maximum number of participants
- Any additional information (teacher, location, equipment)

**Example:** Adding a new "Science Olympiad" activity that meets on Wednesdays from 3:30-5:00 PM.

---

### 2. Modify Existing Activity
**When to use:** You need to change details of an activity that already exists.

**What you'll need to provide:**
- Which activity to modify
- What needs to change (description, schedule, participant limit, etc.)
- Current information
- New information
- Reason for the change

**Example:** Changing Chess Club's schedule from Mondays/Fridays to Tuesdays/Thursdays due to room conflicts.

---

### 3. Remove Activity
**When to use:** An activity is no longer being offered and should be removed.

**What you'll need to provide:**
- Which activity to remove
- Reason for removal
- Whether students are currently enrolled
- Plan for notifying students (if applicable)

**Example:** Removing "Morning Fitness" because the teacher is no longer available.

---

### 4. Bug Report
**When to use:** Something isn't working correctly on the website.

**What you'll need to provide:**
- Description of the problem
- Steps to reproduce the issue
- What should happen instead
- How urgent the fix is

**Example:** Students cannot sign up for Basketball Team - they see an error message.

---

### 5. Feature Request
**When to use:** You have an idea for a new feature or improvement.

**What you'll need to provide:**
- Description of the feature
- What problem it solves
- How it should work
- Who would use it
- How important it is

**Example:** Add ability to export student rosters as CSV files for attendance tracking.

## Tips for Creating Good Issue Requests

### Be Specific
- Instead of: "Change the schedule"
- Better: "Change Chess Club schedule from Mondays/Fridays 3:15-4:45 PM to Tuesdays/Thursdays 3:30-5:00 PM"

### Provide Context
Explain why the change is needed. This helps ensure the solution addresses the root problem.

### Use Examples
If you're not sure how to describe something, use examples from existing activities.

### Check Existing Issues
Before creating a new issue, check if someone else has already requested the same thing.

## What Happens Next?

1. **Issue is Created:** Your request is submitted as a GitHub issue
2. **Automatic Assignment:** The @copilot coding agent is automatically assigned
3. **Work Begins:** Copilot will analyze your request and make the necessary changes
4. **Review:** You can monitor progress and provide feedback
5. **Completion:** Once done, you'll be notified and can verify the changes

## Time Format Reference

When specifying times, please use 24-hour format (also called "military time"):

| 12-hour | 24-hour |
|---------|---------|
| 6:30 AM | 06:30   |
| 7:00 AM | 07:00   |
| 3:15 PM | 15:15   |
| 3:30 PM | 15:30   |
| 5:00 PM | 17:00   |
| 5:30 PM | 17:30   |

**Tip:** To convert PM times, add 12 to the hour (3:30 PM → 15:30)

## Getting Help

If you're not sure which template to use or need help filling out a form:
- Review this guide
- Look at the [Development Guide](how-to-develop.md) for technical details
- Ask a colleague who has submitted an issue before
- Create a Feature Request issue describing what you need help with

## Privacy & Security Note

Please do not include:
- Student passwords or sensitive personal information
- Your own passwords or login credentials
- Any confidential school information

The issue templates are designed to collect only the information needed to make the requested changes.
