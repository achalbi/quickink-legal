---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for QuickInk

**Effective date:** 1 October 2026
**Last updated:** 6 October 2026

This Privacy Policy explains how the QuickInk mobile application ("QuickInk", "the app", "we", "our") handles your information. QuickInk is operated by **thoughtbasics**, Bengaluru, Karnataka, India — the "Data Fiduciary" under India's Digital Personal Data Protection Act, 2023 ("DPDP Act").

Questions, requests, or grievances: **admin@thoughtbasics.com**.

---

## 1. Summary

- Your notes, scans, photos, and related content are stored **on your device** and, when you are signed in, **synced to QuickInk's cloud** so they are backed up and available across your devices.
- Document scanning, text extraction (OCR) and, in the apps, building the search index run **on your device** (so did face detection, in earlier versions of the app); voice-note transcription does too where your phone supports it (Section 2.7). We never use your content to train AI models, ours or anyone else's, and never for advertising. Some features send content to our infrastructure: **naming** sends the **text of a new scan or voice note** to generate its title and one-line description (Section 4b); **online transcription** sends the **images of the pages of scans you make or open** (Section 4b); **Ask** sends **your question and the relevant pages of your documents** (Section 4a); the **web app** sends text to build its search index (Section 4a); and **face grouping**, in the web app and earlier versions of the app, stores face templates **in your account** (Section 2.6). Your phone's own location and speech services, from Apple or Google, may also process locations and voice input (Sections 2.4 and 2.7).
- We use a small set of infrastructure providers (Apple, Google, Supabase, Cloudflare, PowerSync) to operate the service — listed in Section 6.
- We collect limited, first-party **usage analytics**, linked to your account (event counts, platform and app version, sync-error reports — not the contents of your documents). There are **no advertising SDKs and no third-party trackers** in the app.
- Content you deliberately **publish or share by link** is accessible to anyone who has the link (Section 7).
- You can request a copy of your data or deletion of your account and data at any time (Sections 9–10).

## 2. Information we collect

### 2.1 Account information
When you sign in with Google, we receive your basic Google profile: name, email address, and profile picture. We use it to create and authenticate your QuickInk account. We never receive your Google password.

On iPhone and iPad you can sign in with Apple instead. We receive the name you choose to share, the first time only, and an email address: your own, or a private relay address if you choose **Hide My Email**, in which case we never see your real one. We never receive your Apple Account password. You can add Apple and Google to the same QuickInk account under **Settings → Account → Sign-in methods**, so both open the same library. Deleting your QuickInk account also ends QuickInk's access to your Apple account.

### 2.2 Profile details you add
Display name, optional phone number, profile photo, and similar profile fields you choose to fill in.

### 2.3 Content you create ("your content")
Document scans and imported files, photos and videos, notes and journals, voice notes and their transcriptions, text extracted from your documents by on-device OCR (used to make your content searchable), the text online transcription returns for your scanned pages (Section 4b), documents, folders, tags (including labels the app suggests), places, albums, stories, chat messages and the media you send in them (from earlier versions of the app and from the web app), Ask conversations, tasks, people and contacts you link (2.5), face data from earlier versions of the app and the web app (2.6), and trip records from earlier versions of the app. Your content is stored on your device and synced to QuickInk's cloud storage when you are signed in.

On iPhone, if you turn on **Also add to Reminders** when you set a reminder from a scan, QuickInk asks for access to Apple Reminders and adds that reminder there. It then keeps that one reminder in step with the task: changing the time moves it, ticking the task off completes it, and removing the reminder or deleting the task deletes it. It does not read or change your other reminders, and nothing from Reminders is sent to us.

When you keep an action from a scan, such as a reminder to pay a bill or what you are owed from a split, it becomes a task, and the task's notes can include the **amount** and the name of the biller (for example "Bill to pay: ₹2,340 · due 22 Sep"). Tasks are part of your content, so that amount is stored in your account and synced like any other task. When you mark a bill as paid or log an expense, that record is kept **only on the phone** where you made it and is not sent to us. QuickInk does not store card, bank or UPI account details: **Pay** hands a payment link to the UPI app you choose, and QuickInk knows you paid only if you answer that you did. **Add event** and **Add contact** open your phone's own calendar and contacts editors; QuickInk does not read your calendar.

### 2.4 Location
If you allow location access, QuickInk records where your photos are taken, and where your scans are taken while **Attach location to scans** is on, to organise them by place. Photos and files you import keep the location already saved in them. The coordinates and the place name are stored with the item and synced to your account. To turn coordinates into a place name, your phone sends them to Apple's or Google's location service; Ask does the same with addresses it finds in your documents. In the web app, Ask sends such an address to Google's geocoding service, and the map of a saved location is loaded by your browser from Google Maps, which receives that location's coordinates. Trip records from earlier versions of the app may include the route of trips you recorded. You can decline or revoke the location permission at any time; new photos and scans then carry no location of their own.

### 2.5 Contacts
Contacts you link to a document or note, or ask Ask to save, are stored in your account: their name, organisation, phone numbers and email addresses. If you allow access to your address book, the invite and share pickers match names against it **on your device**; only the email address of someone you choose to invite is sent. We do not upload your address book.

### 2.6 Face grouping
Face grouping is not part of this version of the app. It runs in the web app and in earlier versions of the app; in those app versions, face detection ran **on your device**. The mathematical face templates it creates (a list of numbers, not an image) are stored **in your account**, so the people you named follow you across devices. Nothing on our servers reads or analyses these templates; they are used only by your own devices and the web app. Your photos are not sent for this. Templates synced by the web app or an earlier version stay in your account until you delete the account (see Section 10), or until you ask us to remove them by writing to **admin@thoughtbasics.com**; this version of the app has no "Delete all face data" control and no longer keeps a local copy. Where face grouping runs, giving a person a name **automatically links that person to photos you add later in which it recognises them** — you are not asked to confirm each one. Those links are part of your content, so they sync to your other devices, and you can remove a person from any photo at any time.

### 2.7 Voice
Voice notes you record are stored as content (2.3). Their transcription runs on your device where your phone supports the language; on iOS, when it doesn't, Apple's speech recognition may process the audio under Apple's privacy policy. When you speak into the microphone to search on Android, your phone's speech service (usually Google's) may process the audio off the device. QuickInk does not send audio to its AI provider.

### 2.8 Usage analytics and diagnostics
We collect first-party analytics on our own servers, linked to your account (your account ID, email address, name and profile picture): your platform (iOS or Android), app version, product events (for example, "a document was scanned", its page count, whether OCR ran and how many characters it read) and sync-error reports (the kind of item, the error code and the item's ID) — **never** the text or images of your content. We do not use third-party analytics or advertising SDKs. Device logs stay on your device unless you send them to us.

### 2.9 Push notifications
This version of the app registers no push token, sends you no push notifications and contains no Firebase Cloud Messaging and no Firebase installation ID; its reminders are scheduled on your phone and never pass through our servers. When someone shares a document with you, you learn about it inside the app the next time it syncs. Earlier versions of the app, if you allowed notifications, registered a push token (from Firebase Cloud Messaging, which delivers through Apple's push service on iPhone), an install ID and your platform, so notifications reached your device. The first time this version runs, it removes that registration for the device it is on; registrations from other devices you have not updated stay until you delete your account. A notification to an earlier version can include a preview of what it is about — for example, the sender and the start of a chat message — and that preview passes through Google's or Apple's push service on its way to you.

## 3. Purposes and legal basis

We process the above solely to: (a) provide the service — sync, backup, search, sharing, notifications; (b) secure it — authentication, abuse prevention, incident response; (c) improve it — aggregate usage analytics; (d) communicate with you about the service; and (e) meet legal obligations (including India's CERT-In directions and the DPDP Act). Under the DPDP Act we process your personal data on the basis of your **consent**, given when you sign up and when you enable specific features (location, contacts, notifications, face grouping). The features that send your content to our AI provider — online transcription of scanned pages, naming of new scans and voice notes, and Ask (Sections 4a and 4b) — run only after you allow them: the app asks once after you sign in, names the provider and what is sent, and sends nothing until you say yes; **Settings → Privacy → Online AI** turns it on or off afterwards. Some other features are on when you start, are described here, and are ones you consent to by using the app; each has a Settings switch that turns it off. You may withdraw consent at any time as easily as you gave it — via the corresponding Settings toggle or OS permission, or by writing to us; withdrawal stops future processing but doesn't affect processing already done.

## 4. What we do NOT do

We do not sell or rent your personal data. We do not show ads or share data with advertisers. **We do not use your content to train AI models**, and Cloudflare, the AI provider QuickInk uses (Section 6), is contractually barred from training on it. We do not track you across other apps or websites. Nobody at QuickInk browses your content as a matter of course; staff access is limited to what is needed to operate, secure and support the service.

## 4a. Automated processing of your content

To power search and the AI features, your content is processed **automatically, by machines**: text you type, text recognised from scans and photos, and transcripts of voice notes are turned into a search index — including numerical representations ("embeddings") used to find things by meaning rather than exact words. In the apps, the index is built **on your device** and stored in your account. For items you add and searches you make in the QuickInk web app, the text is sent to Cloudflare's AI service (Section 6) to build the index. When you use **Ask** — which works only once you have allowed online AI (Section 4b) — your question and the relevant pages of your documents are sent to Cloudflare's AI service with your account ID, and the answer may be kept for up to 30 days. All of this is used to answer *your* searches and questions, and for nothing else. It is not used to train models, ours or anyone's.

If you use the import features, we access only what you choose. When you import from **Google Drive**, QuickInk shows the names of your Drive files so you can choose, and downloads only the files you select. On Android you can also import from **Google Photos** through Google's photo picker.

When you tap **Add to Wallet** on a scanned ticket, QuickInk sends the ticket's title, its date and time, its booking reference and what its barcode says to our server, which makes a pass for Apple Wallet or Google Wallet and hands it back. The page image, the page text and the scan itself are not sent, and the server keeps nothing. Nothing is sent until you tap.

## 4b. Transcription and naming — new scans and voice notes

**Nothing in this section happens until you allow online AI.** QuickInk asks once after you sign in, saying that the AI models are run by Cloudflare (Workers AI) and what is sent to them. If you say "Not now", nothing is sent, and the app asks again only when you tap something that would send — a "Transcribe online" button, generating a title, or a question in Ask. **Settings → Privacy → Online AI** shows your answer and changes it at any time; turning it off stops online transcription, naming and Ask on that phone. The answer is kept on the phone, per account, so a new phone asks again.

Once online AI is allowed, **Settings → Privacy → Transcription & titles** has two modes: **Online** (the default) and **On device**.

In Online mode, two things happen automatically when you capture:

- **Naming.** As soon as the first page of a new scan is read — or a new voice note's transcription finishes — the **text** your device recognised is sent to our AI provider (Section 6) — unless it looks like an identity document or a prescription (below) — which returns a short title and a one-line description. Only recognised text is sent on this path — never the page image, and never the audio. (How the transcript itself is produced is described in Section 2.7: on-device, except that iOS system speech recognition may involve Apple for some languages. The naming call sends only the finished transcript's text, to our provider.)
- **Transcription.** QuickInk sends **the image of each page of a new scan** — except pages that look like an identity document or a prescription (below) — to our transcription provider, which returns the text it reads — phones are poor at handwriting, and the online reading is substantially better. If you turn on **Auto-scan camera photos**, a scan it makes from one of your photos is a new scan too, and its page is sent **as soon as the scan is made** — which can be while QuickInk is in the background, because that is when Auto-scan looks at your new photos. If that send fails (you were offline, for example), QuickInk tries again, a few times at most, while the scan is still waiting in your Inbox and the app is open. QuickInk also sends the pages of a scan that your phone alone has read so far **when you open that scan**, or **when you combine it into a document** with Combine pages — so an older scan is sent only when you open it or choose it for a document, one document at a time. No background process ever goes back through your existing scans. Your device also reads every page itself, and that on-device text is what you keep when a page can't be sent — offline, past the daily limit, or with the mode set to On device.

Online is the default because most phones cannot read handwriting reliably on their own, and because a title made from misread text is close to useless.

Switching to **On device** stops both immediately — nothing about a new scan or voice note leaves your phone automatically. You can still transcribe an individual page or a whole document yourself from its details screen, and generate a title and description from there; doing so sends only what that action needs.

The transcription path sends a **picture of your document** rather than text taken from it. Before it sends a page on its own, QuickInk looks at what your phone read on that page, and at any QR code on it, for signs of an **Aadhaar, PAN or voter ID card, a driving licence, a cheque, a passport or a prescription**. A page that looks like one of those is not sent automatically, and neither is its text for naming. An identity card, driving licence, cheque or passport is sent only if you transcribe it yourself from its details screen; a prescription shows a button that asks you before it is sent. The scan itself is still stored and synced to your account like any other (Section 2.3). This check is a guess and **can miss a page** — one your phone could not read, for example — and it does not look for other financial records or health information, so with Online set those pages are sent like any other, as are the pages of an older scan that you open while it still has pages only your phone has read. Switch to On device before scanning anything you'd rather keep entirely on your phone. Images and text sent on these paths are used only to produce the transcription, title and description, and are not used to train models.

The transcribed text of a page is stored **with the scan in your account** and syncs to your other devices, like the rest of your content. It does not replace what your device originally read. Any document you export that contains transcribed text says so on the page. The generated title and description are stored with the scan like a title you typed yourself, and sync across your devices; you can edit or clear them at any time. There are daily limits on how many pages can be transcribed and how many titles can be generated this way.

## 5. Where your data is stored

Your content and account data are stored with the infrastructure providers in Section 6. Supabase (database and sign-in) and PowerSync (sync) run in Mumbai, India (AWS ap-south-1). The web app runs in Google Cloud in Mumbai (asia-south1) and is reached through Cloudflare's global network. Media files are stored in Cloudflare R2 in its Asia-Pacific location. The analytics service runs in Google Cloud in the United States (us-central1). Some providers operate global networks, so data may transit or be processed in other jurisdictions; transfers comply with the DPDP Act's cross-border provisions.

## 6. Service providers (data processors)

| Provider | Role | Data involved |
|---|---|---|
| Google (Sign-In, Maps, Play services; Firebase Cloud Messaging for earlier versions) | Authentication; push delivery to earlier versions (2.9); on Android, maps, place names, voice input and Google Photos import; in the web app, the map of a saved location and placing addresses Ask saves as map pins | Google profile basics; push tokens and notification previews (2.9); on Android, locations shown on a map or turned into place names (2.4), voice input audio (2.7), and the photos you pick from Google Photos; in the web app, the addresses Ask saves as places and the coordinates of saved locations you open (2.4) |
| Apple (Sign in with Apple, Push Notification service for earlier versions, MapKit, speech recognition) | On iPhone: authentication when you sign in with Apple, push delivery to earlier versions (2.9), maps and place names, and speech recognition where on-device recognition isn't available | Notification previews (2.9); locations shown on a map, turned into place names or searched for (2.4); voice audio when on-device recognition isn't available (2.7) |
| Supabase | Database, authentication, APIs | Account data, content metadata, synced content records |
| Cloudflare (R2, CDN, Workers) | Media file storage and delivery; share pages | Your media/document files; shared-content delivery |
| Cloudflare (Workers AI) | AI features — answering your Ask questions (4a); naming new scans and voice notes (a generated title and one-line description from their text, 4b); transcribing the pages you scan (4b); building the web app's search index (4a) | Your Ask questions with the relevant pages of your documents (answers kept up to 30 days); text of new scans and voice notes; images of scanned pages sent for transcription; text and search queries from the web app |
| Google Drive | Optional file import, when you choose it | The names of your Drive files while you choose; the files you select |
| PowerSync (JourneyApps) | Synchronization between your device and our database | Synced content records |
| Google Cloud | Hosting for our analytics service and web app | Analytics linked to your account (2.8); content you use in the web app |

Each processes data only to provide its service to us, under its own security and privacy commitments. We will keep this subprocessor list current on this page.

## 7. Sharing features — what becomes visible to others

- **Invites:** if you invite someone by email to a document or album, they see that content and your display name, email address and profile photo. In a chat, the other members see your name, email address, profile photo and when you were last active.
- **Share links:** **anyone with a link** can view what it shares. Treat links like the documents themselves. Document links can also have a password, an expiry date, or require viewers to enter their email address, which you then see. An album link shows a preview of the album (its title, your name, how many items it holds and a few thumbnails) and lets people ask to join. You can reset or turn off either kind of link at any time; already-downloaded copies remain with recipients.
- **Publishing:** a **public** story is readable by anyone with its link and may appear in Discover. A **protected** story is visible only to people you invite; others can ask you for access by giving their name and email address. After you unpublish a story, its media can remain in our content delivery network's cache for up to 4 hours.
- **Join requests:** if you ask to join a shared album, its owner and admins see your account name and email address.

## 8. Security

TLS encryption for all transfers; time-limited, signed URLs for private media (media in a published story is served publicly, Section 7); access controls that isolate each account's private files; sign-in tokens stored in the platform secure store (iOS Keychain / Android encrypted storage); encryption at rest on our storage providers. No system is 100% secure — see Section 12 for how we handle incidents.

## 9. Your rights (DPDP Act)

You have the right to: **access** a summary of your personal data and processing; **correction and completion**; **erasure** (Section 10); **grievance redressal**; and to **nominate** a person to exercise your rights if you are incapacitated or deceased. To exercise any right, email **admin@thoughtbasics.com** from your registered email. We acknowledge grievances within **48 hours** and aim to resolve them within **15 days**. If unsatisfied, you may approach the **Data Protection Board of India**.

## 10. Data retention and deletion

- Your data is retained while your account is active. Items you move to Trash can be restored for 30 days; after that the app deletes them permanently.
- **Account deletion:** see [Delete your account](/delete-account/). Deletion removes your account record, synced content, media files, analytics data (your analytics identity and usage events) and cached answers to your Ask questions from our systems, subject to short backup-rotation windows and log-retention obligations under Indian law (CERT-In directions require certain security logs to be retained for 180 days).
- Content you shared or published may remain with people who already downloaded it.
- Dormant accounts may be deleted after prolonged inactivity following advance notice to your registered email.

## 11. Children

QuickInk is intended for users **18 years and older**. We do not knowingly process the personal data of anyone under 18. If you believe a minor is using QuickInk, contact us and we will delete the account and its data.

## 12. Data breaches

If a personal-data breach affects you, we will notify you without undue delay with a description of the breach, likely consequences, and the steps we are taking, and we will notify the Data Protection Board of India and CERT-In as required by law.

## 13. Changes to this policy

We may update this policy; the "Last updated" date reflects the latest revision. Material changes will be notified by email to your registered address. A copy of this notice is available in other languages listed in the Eighth Schedule to the Constitution of India on request.

## 14. Contact / Grievance Officer

**thoughtbasics** — Bengaluru, Karnataka, India
Grievance contact: **admin@thoughtbasics.com** [name an individual on publication]
