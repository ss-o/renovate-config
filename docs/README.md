# Shareable Configuration Presets

## [Default preset](https://github.com/ss-o/renovate-config/blob/main/default.json)


```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>ss-o/renovate-config"]
}
```

Store the configuration preset as above in one of these locations:

```verilog
renovate.json
renovate.json5
.github/renovate.json
.github/renovate.json5
.gitlab/renovate.json
.gitlab/renovate.
.renovaterc
.renovaterc.json
package.json (within a "renovate" section)
```
