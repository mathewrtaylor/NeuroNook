# Full Leads/Admin Manual (Markdown)

## Introduction

This guide is intended for NN Leads and Admins responsible for managing access, permissions, repositories, and organizational collaboration.

Experience with GitHub is not assumed.

This guide focuses on practical administration tasks while avoiding unnecessary technical complexity.

---

## Recommended Permission Structure

| Role | Permission Level |
|---|---|
| Moderators | Read Only |
| Leads | Maintain |
| Admins | Admin |

### Why This Structure Helps

This structure keeps permissions organized and reduces the chance of accidental changes.

Users should only receive the minimum access needed for their role.

---

## Understanding Roles

### Moderators (Read Only)

Moderators can:

- View repositories
- Open Issues
- Participate in Discussions

Moderators cannot:

- Change repository settings
- Delete files
- Modify permissions

---

### Leads (Maintain)

Leads can:

- Manage Issues
- Manage Discussions
- Organize repositories
- Help coordinate collaboration

Leads should avoid making major organization-wide security changes unless necessary.

---

### Admins (Admin)

Admins can:

- Manage permissions
- Add/remove members
- Configure organization security
- Manage repository settings

Admin access should be limited to trusted individuals.

---

## Adding Members to the Organization

### Step-by-Step

1. Open the NN organization
2. Select **People**
3. Select **Invite Member**
4. Enter the user’s GitHub username or email
5. Assign the appropriate role
6. Send the invitation

[SCREENSHOT PLACEHOLDER: Invite Member Screen]

---

## Important Security Warning

Only invite people whose identity has been verified.

Adding a user may grant access to internal resources, discussions, and moderation materials.

Always double-check usernames before sending invitations.

---

## Managing Teams

Teams help organize permissions and responsibilities.

### Example Teams

- Moderators
- Leads
- Documentation Team
- Resource Team

---

## Creating a Team

1. Open the organization
2. Select **Teams**
3. Select **New Team**
4. Enter a team name
5. Add members
6. Assign repository access

[SCREENSHOT PLACEHOLDER: Create Team Page]

---

## Assigning Repository Access

### To Assign Permissions

1. Open the repository
2. Select **Settings**
3. Select **Manage Access**
4. Add the user or team
5. Select the appropriate permission level

---

## Repository Visibility

Repositories may be:

- Public
- Private

### Recommendation

Internal moderation and operational repositories should remain private.

---

## Requiring Two-Factor Authentication (2FA)

### Why It Matters

2FA reduces the risk of unauthorized access.

This is especially important for moderation and administrative roles.

---

## Enabling Required 2FA

1. Open organization settings
2. Select **Security**
3. Require 2FA for all members

[SCREENSHOT PLACEHOLDER: Organization Security Settings]

---

## Managing Issues

Leads and Admins should regularly review Issues.

### Good Practices

- Respond respectfully
- Close resolved Issues
- Label Issues clearly
- Redirect conversations when necessary

---

## Discussions Best Practices

Discussions should remain:

- Respectful
- Organized
- On-topic

Leads and Admins may lock discussions if necessary.

---

## Repository Organization Suggestions

### Helpful Practices

- Use clear repository names
- Keep folder structures simple
- Avoid duplicate files
- Archive unused repositories

---

## Privacy & Safety Guidelines

Never upload:

- Member data
- Sensitive moderator information
- Passwords
- Recovery codes

Be cautious with screenshots that may expose usernames or private discussions.

---

## Reviewing Permissions

Permissions should be reviewed periodically.

### Recommended Review Frequency

- Quarterly
- After leadership changes
- After moderator departures

---

## Troubleshooting

### User Cannot Access Repository

- Verify they accepted the invite
- Verify permissions
- Verify 2FA is enabled

### Incorrect Permissions

- Review team membership
- Review repository access settings

---

## Final Recommendations

- Keep processes simple
- Document important decisions
- Use Issues for transparency
- Limit Admin access
- Prioritize security and accessibility