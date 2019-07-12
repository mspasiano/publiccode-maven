# publiccode-maven
To update the version and date in publiccode.yml with maven plugin

```bash
mvn release:clean release:prepare --batch-mode --errors --fail-at-end --show-version
```
