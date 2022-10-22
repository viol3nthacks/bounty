# Bug Rankings

P1 - Critical
Vulnerabilities that cause a privilege escalation from unprivileged to admin or allow for remote execution, financial theft, etc.

> • Remote Code Execution
> • Vertical Authentication Bypass
> • XML External Entities Injection with significant impact
> • SQL Injection with significant impact

P2 - High
Vulnerabilities that affect the security of the platform including the processes it supports

> • Lateral authentication bypass
> • Stored XXS with significant impact
> • CSRF with significant impact
> • Direct object reference with significant impact
> • Internal SSRF


P3 - Medium
Vulnerabilities that affect multiple users and require little or no user interaction to trigger

> • Reflective XXS with impact
> • Direct object reference
> • URL redirect
> • CSRF with impact

P4 - Lows
Vulnerabilities that affect singular users and require interaction or significant prerequisites to trigger (MitM) to trigger

> • SSL misconfigurations with little impact
> • SPF configuration problems
> • XSS with limited impact
> • CSRF with limited impact

P5 - Acceptable Risk
Non-exploitable vulnerabilities in functionality. Vulnerabilities that are by design or are deemed acceptable business risk to the customer

> • Debug information
> • Use of CAPTCHAs
> • Code obfuscation
> • Rate limiting, etc.