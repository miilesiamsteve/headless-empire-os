# Security

## Private by default

Headless Empire OS is often used as a **private** repository containing sensitive business context. The public GitHub template must stay free of real operator data.

## Rules

1. **Never commit** API keys, tokens, passwords, private keys, or session cookies. Use `.env` (gitignored).  
2. **Never publish** personal data, financials, unreleased strategy, or customer PII in public forks or Network feeds.  
3. Treat agent tools as untrusted for exfiltration risk: do not paste secrets into prompts that leave your machine.  
4. Public-safe “Now” updates and marketing drafts require human review before external posting.  
5. If you accidentally commit a secret, rotate the credential immediately and purge history if the repo was ever public.

## Reporting

If you find a security issue in the **public starter** (e.g. docs that encourage unsafe patterns), open a private report to the Headless Empire maintainers via the org contact on [headlessempire.com](https://headlessempire.com).
