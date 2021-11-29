---
description: Learn what's possible in SIEM Rules
---

# Rule Management

## Rules

### Overview <a href="#automatic-extractions" id="automatic-extractions"></a>

SIEM Rules allows you to create and modify rules in the open-source Sigma format.

You can read more about Sigma rules and how they are constructed in the Sigma repository on GitHub:

{% embed url="https://github.com/SigmaHQ/sigma" %}

We have also created a short series of posts you might find useful if you are new to the Sigma format:

{% embed url="https://www.signalscorps.com/blog/2021/sigma-rules-101-yaml" %}

Once you've created a Rule in Sigma format in the SIEM Rules user interface, it can be converted to another backend schema.

![SIEM Rules Backend Conversions](../.gitbook/assets/siemrules-backend-conversion.png)

You can view the available backend schemas for conversion in the SIEM Rules.

Note: due to the way Rules can be constructed, not all Rules can be converted to every backend type. If this is the case, you will see this message returned: `This format is not supported for this rule.`\
