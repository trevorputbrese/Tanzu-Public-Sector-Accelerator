# Accelerator Log

## Options
```json
{
  "branch" : "main",
  "description" : "The really amazing STIG'ed starter we have",
  "icon" : "https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/Greater_coat_of_arms_of_the_United_States.svg/160px-Greater_coat_of_arms_of_the_United_States.svg.png",
  "name" : "stiged-java-web-app",
  "projectName" : "STIG'ed Java Web App Starter",
  "url" : "https://github.com/alexbarbato/Tanzu-Public-Sector-Accelerator"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","icon":"https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/Greater_coat_of_arms_of_the_United_States.svg/160px-Greater_coat_of_arms_of_the_United_States.svg.png","name":"stiged-java-web-app","description":"The really amazing STIG'ed starter we have","artifactId":"STIG'ed_Java_Web_App_Starter","projectName":"STIG'ed Java Web App Starter","branch":"main","url":"https://github.com/alexbarbato/Tanzu-Public-Sector-Accelerator"}
┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input8479810979711274845, --data-values-file, /tmp/accelerator-options106541744203616131.json, --output-files, /tmp/ytt-output6051805386779147393]
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┗ ┗ Debug new-accelerator.yaml didn't match [README.md] -> excluded
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
