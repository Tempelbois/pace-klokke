# pace-klokke
Triggers the pace-quest build in the private repo Tempelbois/pace-dashboard when the newest build is more than 70 minutes old.
This repo contains no code or data from the dashboard, only the workflow in .github/workflows/pace-klokke.yml.
It needs the secret DASHBOARD_DISPATCH_TOKEN: a fine-grained token with Actions read and write on Tempelbois/pace-dashboard only.
