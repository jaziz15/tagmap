# TagMap Privacy Policy 

**Last updated:** 29 September 2026
**Publisher:** Joe Aziz
**Contact:** joeaziz77@gmail.com

## What TagMap is

TagMap is a Chrome extension for analysts and product managers. It shows which analytics
events a website fires as you use it, and lets you save sequences of those events as named
"funnels" for later reference.

## Where TagMap runs

TagMap does not run on any website until you explicitly enable it for that site.

On installation, TagMap holds no access to any website. When you open the side panel and
choose **Enable TagMap on this site**, Chrome asks you to grant access to that one site.
Only then does TagMap load its code into pages on that site. TagMap does not run on, read,
or observe any site you have not enabled.

You can withdraw access at any time, either from the **Disable** control in the side panel
or from Chrome's own extension settings. Withdrawing access immediately stops TagMap
running on that site.

## What TagMap collects

**Stored in your TagMap account (only if you sign in):**

- **Your Google account email address and a user identifier.** Collected only when you
  choose to sign in with Google, which is only required to save funnels. Used solely to
  authenticate you and to associate your saved funnels with your account.
- **Funnels you create** — the funnel name, its optional description, and the ordered list
  of event names and event types you added to it, plus any property keys and values you
  explicitly selected as distinguishing properties for a step. These event names and
  property values come from the analytics calls of websites you enabled, so a saved funnel
  contains website content that you chose to keep.

This data is stored on TagMap's backend, hosted on Supabase, and is protected by
row-level security: each record is readable and writable only by the account that created
it.

**Held only on your own device, and never transmitted:**

- **Observed analytics events** — the event name, event type (`track` / `page` /
  `identify`), and the property keys, types and values of analytics calls firing on sites
  you have enabled. These are held in a local in-browser buffer (the most recent 100
  events) so that the side panel can show them, and they are discarded when your browser
  session ends or when you click **Clear session**.
- Observed events are **not** sent to TagMap's backend or to any other server. The only
  data that leaves your device is the funnel content you explicitly choose to save, and
  your account identity when you sign in.

## What TagMap does not do

- It does **not** persist observed property values to any database. Property values appear
  transiently in the side panel and are never written to the backend.
- It does **not** collect your browsing history, page content, form input, keystrokes, or
  any personal data beyond the account email you use to sign in.
- It does **not** collect data from sites you have not explicitly enabled.
- It does **not** sell or transfer your data to third parties, use it for advertising,
  profiling, or credit assessment, or use it for any purpose unrelated to TagMap's single
  purpose of showing you analytics events and letting you save funnels.

## Third parties

- **Supabase** provides TagMap's database and authentication. Account
  identity and saved funnels are stored there on Joe Aziz's behalf.
- **Google** provides sign-in. When you sign in, Google returns an identity token that
  confirms your email address; TagMap requests the `email`, `profile` and `openid` scopes
  and nothing else.

No other third party receives any TagMap data.

## Retention and deletion

Saved funnels are retained until you delete them or ask for your account to be deleted.
Deleting a funnel in the side panel removes it and its steps from the backend. Signing out
clears the local session on that device; your saved funnels remain in your account and
reappear when you sign in again.

To request deletion of your account and all associated data, contact
joeaziz77@gmail.com.

## Your rights

Depending on where you live, you may have the right to access, correct, export or delete
the personal data TagMap holds about you (your account email and your saved funnels).
Contact joeaziz77@gmail.com to exercise any of these rights.

## Changes

If this policy changes materially, the updated version will be published at this URL with
a new "Last updated" date, and the Chrome Web Store listing will be updated to match.

## Contact

joeaziz77@gmail.com
Joe Aziz
