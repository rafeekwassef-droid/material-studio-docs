# Material Studio merchant documentation

Public site: https://rafeekwassef-droid.github.io/material-studio-docs/

Version 0.2.0 is a QA build, not a released Theme Store product. Theme metadata points to `/docs/` and `/support/`. A custom domain is optional.

## Support delivery gate

Recipient: rafeekwassef@yahoo.com (also used for the Shopify login).

The form posts normally to FormSubmit with CAPTCHA enabled, image attachment support and an acknowledgement template. Before marking support ready:

1. Submit an activation request and confirm FormSubmit's email in the recipient inbox.
2. Replace the email-form endpoint with the opaque endpoint supplied by FormSubmit, if available.
3. Send an authorized test with a small screenshot; verify recipient delivery, attachment and sender acknowledgement.
4. Remove the pending-activation callout only after delivery is verified. Preserve direct email as a fallback.

The response target is two business days. Do not publish a claim that support is operational until the above test passes. No credentials are stored in this site.
