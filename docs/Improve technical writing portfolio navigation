# How to Resolve Claim Validation Errors

## Overview

This guide explains how to identify and resolve validation errors in the fictional Healthcare Claims Processing Platform (HCPP).

A validation error occurs when submitted claim information is missing, invalid, or does not meet configured processing requirements.

## Prerequisites

Before resolving a validation error, confirm that you have:

- Access to HCPP
- Permission to view and edit claims
- The affected claim ID
- The displayed error message or error code

## Locate the Claim

1. Sign in to HCPP.
2. Select **Claims** from the dashboard.
3. Enter the claim ID in the search field.
4. Select **Search**.
5. Open the affected claim.

The claim status should display **Action Required** when a validation issue requires correction.

## Review the Validation Error

Locate the validation message associated with the claim.

Record the following information before making changes:

- Error code
- Error message
- Affected field
- Current field value

For example:

```text
Error Code: HCPP-400
Message: Missing required field
Field: procedureCode
```

## Correct the Claim

1. Select **Edit Claim**.
2. Locate the field identified in the validation message.
3. Review the current value.
4. Enter the required or corrected information.
5. Review the remaining claim information for accuracy.
6. Select **Save**.

> **Important:** Correct only information that you are authorized to modify.

## Resubmit the Claim

After correcting the validation issue:

1. Review the updated claim.
2. Select **Submit Claim**.
3. Confirm that HCPP accepts the submission.
4. Record the updated claim status.

A successful submission should move the claim from **Action Required** to **Processing**.

## Verify the Resolution

Confirm that:

- The original validation error no longer appears.
- The corrected information is displayed.
- The claim status has changed to **Processing**.
- No additional validation errors are present.

If another validation error appears, repeat the correction process for the newly identified issue.

## Example

### Before Correction

```json
{
  "claimId": "CLM-10482",
  "procedureCode": "",
  "status": "Action Required"
}
```

### After Correction

```json
{
  "claimId": "CLM-10482",
  "procedureCode": "99213",
  "status": "Processing"
}
```

## Troubleshooting

If the claim remains in **Action Required** after correction:

1. Confirm that all required fields contain valid information.
2. Review the displayed error message for additional validation issues.
3. Verify that your account has permission to modify the affected field.
4. Confirm that the claim was successfully resubmitted.
5. Record the error message and steps already performed.

If the issue remains unresolved, follow the escalation process in the [Troubleshooting Guide](./troubleshooting-guide.md).

## Related Documentation

- [Quick Start Guide](./quick-start-guide.md)
- [Troubleshooting Guide](./troubleshooting-guide.md)
- [Configuration Reference](./configuration-reference.md)
- [Claims Processing Workflow](./claims-processing-workflow.md)
