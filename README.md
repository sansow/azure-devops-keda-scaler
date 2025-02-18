# azure-devops-keda-scaler

echo "# azure-devops-keda-scaler" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sansow/azure-devops-keda-scaler.git
git push -u origin main

Referecen code to build https://github.com/kevchu3/azure-buildagent-container.git

oc new-project azure-build \n
oc new-project ado-openshift
create a secret called azuredevops for Scaled Joba nd Trigger Aith with AZP_URL, AZP_TOKEN and AZP_POOL
