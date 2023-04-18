# NTLM Authenticated Services

Password Spraying

As account lockout is commonly configured in AD environments, conducting a full brute-force attack may not be feasible. Thus, we resort to password spraying attack where a single password is used to authenticate with all the acquired usernames to avoid triggering the account lockout mechanism that may arise from multiple password attempts.&#x20;

:warning: These attacks may trigger detection measures due to the significant number of failed authentication attempts generated.
