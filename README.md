# Follow along 🎶

Ideally you would need a tenant with multiple active users and at least one Entra ID P2 license and at least one user with an Exchange Online mailbox... And you will to send the tenant's audit logs and signin logs (interactive and non interactive) to a Log Analytics workspace. 🔗 [Configure Microsoft Entra diagnostic settings for activity logs](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-configure-diagnostic-settings)   

**Step 1**    
Take an account with ot without a mailbox and add the MFA method TOTP with the Authenticator App. Click here during registration: <img width="539" alt="image" src="https://github.com/user-attachments/assets/ba5f91fc-e8a8-4a14-aa98-81899e7770d1" />    
At the end of that process, you should see the following in the MFA methods of your account:    
<img width="202" alt="image" src="https://github.com/user-attachments/assets/13bedbc9-b02a-466e-80fd-c4377d9926da" />    

**Step 2**
Then you pick another account that you like very much (meaning you already have used in the past, and this time with a mailbox) on which you already have set MFA, and you connect with it using a TOR client (or with a TOR browser extension on).

> ⚠️ Don't use a corporate device for this.

Once you have sign-in, within the same session add a new MFA method on the account (of any type) within the next 5 to 10 minutes.

Once you have added this method, add an email redirection rule on the account.

🎉 That's it for now, it should give us enough telemetry to play around... 
