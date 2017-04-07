GoCD example repository for pipeline as code

For the YAML plugin:

Install [GoCD YAML configuration plugin](https://github.com/tomzo/gocd-yaml-config-plugin) and add this to your XML config:
```xml
<config-repos>
  <config-repo plugin="yaml.config.plugin">
    <git url="git@git.thoughtworks.net:techops/gocd-config-repo-example.git" />
  </config-repo>
</config-repos>
```
