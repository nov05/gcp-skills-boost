# 🟢 GSP647 Configuring IAM Permissions with gcloud

https://www.skills.google/games/7223/labs/44685

### Run the following Commands in CloudShell

SSH to the VM instance.

```bash
gcloud compute ssh centos-clean --zone=$(gcloud compute project-info describe --format="value(commonInstanceMetadata.items[google-compute-default-zone])") --quiet
```

Inside the SSH session, run the following commands.

```bash
curl -LO https://raw.githubusercontent.com/Itsabhishek7py/GoogleCloudSkillsboost/refs/heads/main/Configuring%20IAM%20Permissions%20with%20gcloud/abhishek.sh
sudo chmod +x abhishek.sh
./abhishek.sh
```
