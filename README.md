# npm-locked-transitive-dependency-removed
test case for removing a transitive dependency on upgrade

```
SECURITY_ADVISORIES='[{"dependency-name":"@dependabot-fixtures/npm-transitive-dependency","affected-versions":["<1.0.1"]}]' bin/dry-run.rb npm_and_yarn dependabot-fixtures/npm-locked-transitive-dependency-removed --security-updates-only --dep @dependabot-fixtures/npm-transitive-dependency
```
