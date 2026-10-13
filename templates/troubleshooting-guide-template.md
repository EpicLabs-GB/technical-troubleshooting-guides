# Troubleshooting: [Problem or symptom]

> **Status:** Draft 
> **Last validated:** YYYY-MM-DD 
> **Applies to:** [Product, service, or version]

## Overview

Explain the problem and what this guide will help the reader investigate or resolve.

## Symptoms

- [Symptom one]
- [Symptom two]
- [Relevant error message]

## Scope

Explain what the guide covers and what it does not cover.

## Prerequisites

Before starting, confirm that you have:

- [Required role or permission]
- [Required tool]
- [Required module or software version]
- [Backup or rollback plan, if applicable]

## Safety and impact

> **Warning:** Explain whether any step changes configuration, restarts a service, removes data, interrupts users, or has another production impact.

## Diagnostic workflow

### Step 1: Confirm the symptom

Explain what the reader should check.

```powershell
# Add a diagnostic command here
```

**Expected result:**

```text
Add an example of the expected sanitized output here.
```

**If the result is different:**

Explain what the different result may mean.

### Step 2: Collect diagnostic information

Explain the next diagnostic step.

```powershell
# Add another diagnostic command here
```

### Step 3: Isolate the affected component

Explain how to distinguish between possible causes.

| Observation | Possible cause | Next step |
|---|---|---|
| [Observation] | [Possible cause] | [Action] |

## Root-cause indicators

Describe the evidence that confirms each possible root cause.

## Resolution

Explain the proposed change before showing the command.

```powershell
# Add a remediation command here
```

**Impact:** [Describe the impact.]

**Expected result:** [Describe the successful result.]

## Validation

After making the change:

1. Repeat the original failing action.
2. Confirm that the expected result is returned.
3. Review the relevant logs or monitoring data.
4. Check that no unrelated service was affected.

## Rollback

Explain how to reverse the change safely.

```powershell
# Add a rollback command here
```

## Escalation data

If the problem remains unresolved, collect:

- Reproduction time, including the time zone
- Sanitized correlation or request ID
- Relevant logs
- Product and module versions
- Commands already run
- Results of the diagnostic steps

Do not include passwords, tokens, private keys, customer data, or confidential information.

## Related guides

- [Add a related guide]

## References

- [Add an official reference]

## Change history

| Date | Change | Author |
|---|---|---|
| YYYY-MM-DD | Initial publication | Michael Nell |
