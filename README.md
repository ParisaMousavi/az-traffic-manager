# Push changes in Azure DevOps Repo & GitHub
```
git remote add origin https://p-moosavinezhad@dev.azure.com/p-moosavinezhad/az-iac/_git/az-traffic-manager

git remote set-url --add --push origin https://p-moosavinezhad@dev.azure.com/p-moosavinezhad/az-iac/_git/az-traffic-manager

git remote set-url --add --push origin https://github.com/ParisaMousavi/az-traffic-manager.git
```

# Create a new tag
```
git tag -a <year.month.day> -m "description"

git push origin <year.month.day>

```
- git tag -a 2022.11.30 -m "aks operation scaling video"; git push origin 2022.11.30;