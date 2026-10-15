# Vardies OSY — Privacy Policy

Prepared for publication: 16 October 2026.

## Who operates the app

Vardies OSY (ΒΑΡΔΙΕΣ ΟΣΥ) is an independently developed Android application operated by Charris Eliopoulos. It helps drivers manage their own work schedules. It is not an official OSY application and is not affiliated with Yahoo or Microsoft.

For privacy questions and requests, contact **arxiaellis@yahoo.com**.

## Scope and optional features

This notice describes the app and its subscription-check service. Features differ between releases. Outlook/Hotmail support is a test integration. Yahoo email access is planned, requires Yahoo approval, and is not yet available. The Yahoo description below explains its intended limited use, not an already operating connection.

## Information used and why

- **Employee number and access expiry:** to identify the subscription record and check whether imports are permitted. The current test app requires an administrator-managed expiry for both trials and paid subscriptions; it does not grant an automatic local trial.
- **Schedule PDFs and extracted details:** to import, display, search and summarize the user's shifts. A schedule may contain identifying information, duty dates, working hours, route or duty details, and absence entries. PDFs are parsed on the Android device.
- **Calendar information:** to let the user choose a calendar, read relevant existing entries and create or update schedule entries with permission.
- **Email account and authorization information:** for an optional connection that finds relevant schedule emails and retrieves matching PDF attachments.
- **Settings, import history and backups:** to remember app choices, avoid duplicate imports and provide the app's backup and restore functions.

The app does not request the user's email password. Local OAuth credentials used by the email integration are encrypted using Android Keystore-backed storage. The app does not sell or license mailbox contents or work schedules, and does not use them for advertising or profiling. Paid access, where offered, pays for app functionality rather than the sale of user data.

## Email access

Email connection is optional. A user can select a PDF manually instead, subject to access eligibility. Relevant messages are located using schedule sender, subject and attachment information; an employee-number check is applied before import. Optional background checks look for new schedules and avoid downloading the same item repeatedly.

The planned Yahoo integration requests read-only IMAP access for schedule messages from **osycompass@osy.gr** and PDF attachments matching the employee number. It will not request Yahoo Contacts or Calendar access, send messages, or modify or delete mailbox messages. Downloaded attachments are intended to be processed on the device, not uploaded to the developer's subscription service.

Users can disconnect an email account in the app and revoke authorization through the email provider's account settings. Removing locally stored credentials does not, by itself, revoke authorization at the provider or remove previously imported calendar entries.

## Data leaving the device

**Subscription service:** the entered employee number is sent to a Google Apps Script service that checks a privately managed Google spreadsheet. It holds employee numbers and access-expiry dates. Unknown employee numbers can be logged with first and latest check times, check counts and notification status. An administrative email alert may be sent to the operator's designated mailbox. A typed employee number is not proof of identity. Yahoo email contents and PDF attachments are not sent to this service.

**Calendar provider:** imported shifts are written to the calendar selected by the user. If that calendar syncs to Google or another provider, the entries can be transferred to that provider and other devices, or shared according to the user's calendar settings. The provider's own privacy terms apply to that processing.

**Email provider:** optional connections communicate directly with the selected provider for authorization and permitted mailbox access. Yahoo access remains subject to approval and implementation.

**GitHub and backups:** update checks and downloads contact GitHub. User-selected exports or backups are saved to the destination chosen by the user, which may be cloud storage. Android system backup or device-transfer behavior also depends on the device and account settings. Email authorization credentials are excluded from the app's configured Android backup rules.

Network services receive ordinary connection metadata, such as IP addresses, in providing their services. Google, Microsoft, Yahoo, GitHub and any selected storage provider process information under their respective terms and may process it in different countries. The developer does not promise that provider-managed logs or backups are erased when a live spreadsheet row is deleted.

## Retention and deletion

- **Subscription registry:** employee numbers and expiry dates are kept while access is active and for six calendar months after expiry. The hourly cleanup removes older expired rows from the live registry. Blank or invalid expiry dates require administrative correction rather than guessed automatic deletion.
- **Unknown-number logs:** live rows are removed by hourly cleanup at or after 30 days from their first check. Repeated checks do not extend that period. A later check after deletion can create a new record.
- **Administrative notification emails:** the operator must remove these separately within the same 30-day period. The spreadsheet cleanup cannot automatically delete messages from the recipient's mailbox, sent folders, forwards or exported copies.
- **On-device information:** files, settings and import history remain until removed through available app or Android controls. Uninstalling does not automatically remove calendar events, exports, cloud copies or server-side subscription records.
- **Provider history and backups:** live cleanup does not guarantee deletion from Google spreadsheet version history, provider backups or independently retained copies. These require separate handling through the relevant account or provider controls.

The retention rules describe the updated subscription service. Older app releases can behave differently, including retaining legacy trial behavior until their next online check. Installing the latest release is recommended. A previously verified future access expiry can remain usable offline until that date.

## Your choices and privacy requests

You can choose not to connect email, turn off automatic checks, disconnect accounts and manage permissions in Android or the relevant provider's settings. Disabling a permission can prevent the related feature from working. An employee number and valid access expiry are required for new imports; they are not optional if you want to use that functionality.

For records maintained by the operator, email **arxiaellis@yahoo.com** to request access, correction or deletion, or to raise a concern. Where applicable law provides them, you may also request restriction or portability, object to processing or withdraw consent for optional processing. These rights depend on the circumstances; withdrawing optional email access does not automatically delete records required for another purpose. You may complain to the competent data protection authority.

The operator may need proportionate verification before disclosing or changing a subscription record. Do not send email passwords, OAuth credentials or unnecessary full schedule PDFs. Requests about data held independently by a calendar, email or storage provider may also require action through that provider.

## Changes

This notice will be updated if the app's data practices change, including before a materially different Yahoo integration is released. A privacy notice describes practices; it is not a claim of Yahoo approval, a security-audit certificate or a certification of legal compliance.
