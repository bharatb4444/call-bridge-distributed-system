# Publication review / outstanding checks

- Automated text scan of archived sources showed no embedded GitHub tokens, cloud access keys, private-key blocks, or customer email addresses. Docker passwords are passed via environment variables or generated at runtime. This is not a full security audit.
- The included data are **local validation results**, not the underlying GCP evidence for the 88 checks in the manuscript.
- Original proprietary Java production code is not included. Historical work was performed at an employer; confirm that this separate reconstruction does not reproduce any restricted employer IP before sharing publicly.
- The original self-extracting GCP shell runner was deliberately omitted from this public-review snapshot to favor plainly inspectable source files. The operational entry point is `code/run.sh`.
- Check all dependency and third-party license obligations before choosing an open-source license.
- Review every file before public publication; automated screening cannot certify absence of secrets or proprietary information.
