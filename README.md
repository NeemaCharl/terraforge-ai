# Terraforge.ai

AI-assisted Terraform generator for junior devs & small teams.

Write a simple YAML file describing what you need → Terraforge spits out production-ready Terraform + IAM policies + cost estimate in seconds.

### Why
- Juniors waste hours on boilerplate & IAM policies
- Small startups can’t afford senior DevOps
- Existing tools are either too simple or enterprise-bloated

### MVP Features (Week 6 target)
- CLI: `terraforge generate my-app.yaml`
- Supports EC2, S3, Lambda, IAM roles/policies
- Built-in AWS Pricing API cost estimate
- Optional local/Groq LLM to refine your YAML → perfect HCL
- Slack/email alerts on apply success/failure

Freemium → free for basic templates, €9–19/mo for AI + team features.

Currently in private beta → join the waitlist: hello@terraforge.ai
