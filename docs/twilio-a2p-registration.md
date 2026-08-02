# Twilio A2P 10DLC Registration

## Brand Information

**Brand Name:** Redline Data Lab

## Opt-in Method

**Method:** Web Form

## Public URLs

**Direct Opt-in URL:** https://redline-data.xyz/request-info (UNVERIFIED - awaiting deployment)

**Privacy Policy URL:** https://redline-data.xyz/privacy.html (UNVERIFIED - awaiting deployment)

**Terms and Conditions URL:** https://redline-data.xyz/tos.html (UNVERIFIED - awaiting deployment)

## Message Flow Description

End users opt in at https://redline-data.xyz/request-info by completing a request-information form. The mobile-number field is optional. To consent to SMS, the user must voluntarily check a separate checkbox that is unchecked by default. The disclosure explains the types of messages, that message frequency varies, that message and data rates may apply, that users may reply STOP to opt out or HELP for help, and that consent is not a condition of purchase. The form can be submitted without providing a mobile number or consenting to SMS. Redline Data Lab records the consent timestamp, source URL, disclosure version, and exact disclosure text.

## Consent Disclosure Version

**Version:** sms-consent-v1.0

## Exact Disclosure Text

"Yes, I agree to receive recurring SMS messages from Redline Data Lab about requested service information, appointment reminders, onboarding and account updates, and customer support. Message frequency varies. Message and data rates may apply. Reply STOP to opt out or HELP for help. Consent is not a condition of purchase. View our Terms and Privacy Policy."

## Consent Recording

For every submission, Redline Data Lab records:
- Submission ID
- Full name
- Business name
- Work email
- Mobile phone (when provided)
- SMS consent: true or false
- Consent timestamp in UTC
- Source URL
- Consent-copy version (sms-consent-v1.0)
- Exact disclosure shown
- Privacy Policy URL
- Terms and Conditions URL
- Submission status
- CRM integration result
- Created timestamp

## Support Contact

**Email:** hello@redline-data.xyz

## Important Notes

- No SMS messages are sent until Twilio registration and production activation are complete
- Consented contacts are marked as pending SMS eligibility until production approval
- Mobile numbers are never added to SMS audiences without explicit consent
- Consent is never inferred from phone number entry, form submission, or purchase
- All consent evidence is stored server-side through the existing Netlify Forms integration
- No credentials or secrets are exposed in client-side code
