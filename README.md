# Material Studio merchant documentation

Public site: https://rafeekwassef-droid.github.io/material-studio-docs/

Version 0.2.0 is a QA build, not a released Theme Store product. Theme metadata points to `/docs/` and `/support/`. A custom domain is optional.

## Support delivery

Recipient: rafeekwassef@yahoo.com (also used for the Shopify login).

The owner confirmed inbox activation and test receipt on 2026-10-12. Attachment delivery and sender acknowledgement still need an explicit check.

The form posts normally to FormSubmit with CAPTCHA enabled, image attachment support and an acknowledgement template. Operational checks:

1. Inbox activation and test receipt: confirmed by the owner on 2026-10-12.
2. Replace the email-form endpoint with the opaque endpoint supplied by FormSubmit, if available.
3. Send an authorized test with a small screenshot; verify recipient delivery, attachment and sender acknowledgement.
4. Pending-activation callout removed after owner confirmation. Direct email remains available.

The response target is two business days. Do not publish a claim that support is operational until the above test passes. No credentials are stored in this site.
