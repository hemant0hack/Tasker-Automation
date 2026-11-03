# Tasker-Automation

Ye repository personal + Tasker automation projects ke liye hai. Yaha main multiple Android Tasker projects store karunga — kuch public share karne ke liye, aur kuch secure/private use ke liye.

## Purpose
- Reusable Tasker workflows ko organize karna
- Public automation ideas share karna
- Sensitive automations ko safe rakhna

## Public vs Secure Content

### Public (share karne ke liye)
- Generic Tasker profiles/tasks
- Productivity automations
- Documentation and setup notes

### Secure (public repo me directly commit na karein)
- API keys / tokens
- Personal webhook URLs
- Device-specific IDs (MAC, IP, account info)
- Passwords, OTP flows, private endpoints

## Tasker Project Notes
- Tasker profiles/projects XML export/import support karte hain, isliye workflows ko version control me rakhna easy hota hai.
- Share karne se pehle XML files review karein aur hardcoded sensitive values remove karein.

## Recommended Repo Organization
- `public/` → safe-to-share Tasker projects
- `private-template/` → placeholders/examples without secrets

## Security Checklist (before push)
- [ ] Secrets scan run karo
- [ ] XML/JSON me hardcoded credentials check karo
- [ ] Device-specific values sanitize karo
- [ ] Public sharing ke liye only safe automation export karo

## References
- Android Authority: Tasker basics and automation concepts
- Tasker XML export/import community reference (Tasker-XML-Info)
