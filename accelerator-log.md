# Accelerator Log

## Options
```json
{
  "projectName" : "backstage-demo",
  "includeTap" : false,
  "includeTas" : true
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[0].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug server.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug vms/tas/DEPLOYING.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug vms/tas/tas-config.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[0].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [package.json, kubernetes/**, vms/**, catalog/**, README.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug server.js didn't match [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug vms/tas/DEPLOYING.md matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┗ ┗ Debug vms/tas/tas-config.yaml matched [package.json, kubernetes/**, vms/**, catalog/**, README.md] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [package.json]
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json matched [package.json] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug server.js didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug vms/tas/DEPLOYING.md didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug vms/tas/tas-config.yaml didn't match [package.json] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [node-express->backstage-demo]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeTas) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [vms/tas/tas-config.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug server.js didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug vms/tas/DEPLOYING.md didn't match [vms/tas/tas-config.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug vms/tas/tas-config.yaml matched [vms/tas/tas-config.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [node-express->backstage-demo]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[3].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'vms/tas/tas-config.yaml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yaml, folder=vms/tas/, filename=tas-config.yaml, g0=vms/tas/tas-config.yaml, g1=vms/tas/, g2=tas-config.yaml, g3=tas-config.yaml, g4=.yaml} and was rewritten to 'manifest.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ README (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ README.delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ README.delegate.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug server.js didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug vms/tas/DEPLOYING.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug vms/tas/tas-config.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[0].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [node-express->backstage-demo]
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeTap) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeTas) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ README.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [vms/tas/DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/DEPLOYING.md didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug kubernetes/tap/workload.yaml didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug server.js didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug vms/tas/DEPLOYING.md matched [vms/tas/DEPLOYING.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug vms/tas/tas-config.yaml didn't match [vms/tas/DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [node-express->backstage-demo]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[0].sources[2].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'vms/tas/DEPLOYING.md' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.md, folder=vms/tas/, filename=DEPLOYING.md, g0=vms/tas/DEPLOYING.md, g1=vms/tas/, g2=DEPLOYING.md, g3=DEPLOYING.md, g4=.md} and was rewritten to 'README.md'
┃ ┃ ┃ ┃ ┃ ┏ README.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┗ ┗ ┗ Debug Multiple representations for path 'README.md', will concatenate them together
┃ ┗ ┗ ╺ engine.transformations[0].validated.delegate.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
