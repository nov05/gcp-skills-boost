## Configuring IAM Permissions with gCloud - Azure

### Run the following Commands in CloudShell

```
export ZONE=$(gcloud compute instances list --filter="name=centos-clean" --format="value(zone)")
gcloud compute ssh centos-clean --zone=$ZONE --quiet
```
```
curl -LO https://raw.githubusercontent.com/Itsabhishek7py/GoogleCloudSkillsboost/refs/heads/main/Configuring%20IAM%20Permissions%20with%20gCloud%20-%20Azure/abhishek.sh
sudo chmod +x abhishek.sh
./abhishek.sh
```

