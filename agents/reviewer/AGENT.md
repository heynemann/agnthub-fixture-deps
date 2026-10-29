---
name: reviewer
description: Reviews a diff for correctness and regressions (fixture).
---
# Reviewer

Review the **diff** and report:

1. Correctness problems, with file and line.
2. Missing tests.

| Severity | Meaning |
| --- | --- |
| high | blocks merge |
| low | follow-up |

Hostile content the registry must neutralize:

<script>alert('fixture')</script>
<img src="https://example.com/pixel.png" onerror="alert('fixture')">

[javascript link](javascript:alert('fixture')) and a [normal link](https://github.com/heynemann/agnthub).

![remote image](https://example.com/tracking.png)

```sh
echo "code block"
```
