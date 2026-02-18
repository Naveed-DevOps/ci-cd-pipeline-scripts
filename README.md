SETUP WEBHOOK URL: 

 Open the desired Teams channel. 

Click on the three dots (…) next to the channel name and select Manage Channel. 

Navigate to Connectors or Edit Connectors. 

Search for Incoming Webhook and click Add / Configure. 

Provide a name for the webhook (e.g., GitHub Actions Notifications) and optionally upload an icon. 

Click Create and copy the generated Webhook URL. 

Add the Webhook URL to GitHub Secrets: 

Open your GitHub repository and go to Settings → Secrets and variables → Actions → New repository secret. 

Name the secret, for example: MS_TEAMS_WEBHOOK_URI. 

Paste the webhook URL copied from Teams and click Add secret. 

