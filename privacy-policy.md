# Datenschutzerklärung für TraceIt

Stand: 13. Juli 2026

Diese Datenschutzerklärung beschreibt, wie die iOS-App **TraceIt** personenbezogene Daten verarbeitet. TraceIt ist eine Ernährungs- und Fortschritts-Tracking-App für iPhone.

## Verantwortlicher und Kontakt

Oliver Heidebroek  
E-Mail: [TraceItSupport@icloud.com](mailto:TraceItSupport@icloud.com)

## Kurzfassung

Private Profil-, Ernährungs-, Tagebuch-, Aktivitäts-, Gewichts-, Wasser-, Rezept- und Einstellungsdaten werden in der aktuellen TestFlight-/App-Store-Version lokal auf deinem iPhone gespeichert. Sie werden weder an Supabase noch an eine private CloudKit-Datenbank übertragen. Nur wenn du die Community-Funktion bewusst nutzt, werden die nachfolgend beschriebenen Community- und Kontodaten an Supabase übertragen. TraceIt verwendet keine Werbe- oder Tracking-SDKs, betreibt kein geräteübergreifendes Tracking und verkauft keine personenbezogenen Daten.

## Welche Daten verarbeitet TraceIt?

Je nach Nutzung kann TraceIt folgende Daten auf deinem Gerät verarbeiten:

- Profildaten wie Anzeigename, Geschlecht, Alter, Größe, Gewicht, Zielgewicht, Aktivitätslevel, Ernährungsziel und Einheitensystem;
- Ernährungs- und Tagebuchdaten wie Mahlzeiten, Lebensmittel, Portionsgrößen, Nährwerte, Barcodes, Favoriten und eigene Lebensmittel;
- Trackingdaten wie Gewicht, Wasser, Aktivitäten, Schritte, aktive Kalorien, Notizen und Tagesfortschritt;
- Rezepte, Zutaten, Zubereitungsschritte, Portionen und optionale Bilder;
- Kamera- und Fotoeingaben für Barcodes, Nährwerttabellen sowie Lebensmittel- oder Rezeptbilder;
- Spracheingaben für den In-App-Assistenten, wenn du Mikrofon und Spracherkennung erlaubst;
- App-Einstellungen und Onboarding-Status.

Diese privaten Trackingdaten bleiben in der aktuellen Release-Version lokal auf deinem Gerät, sofern du sie nicht selbst exportierst oder teilst.

## Community-Konto und Community-Inhalte

Der öffentliche Community-Katalog kann ohne Community-Konto gelesen werden. Wenn du ein Lebensmittel einreichen möchtest, meldest du dich über **Mit Apple anmelden** an. Dabei verarbeitet Supabase Auth eine technische Benutzer-ID und – abhängig von deiner Apple-Auswahl – deine E-Mail-Adresse. Apple kann eine Relay-Adresse bereitstellen.

Bei einer bewussten Einreichung werden ausschließlich die für die Katalogprüfung erforderlichen Lebensmitteldaten an Supabase übertragen: Name, Marke, Kategorie, Barcode, Portionsangaben, sieben Nährwertwerte pro 100 g sowie technische Einreichungs- und Moderationsdaten. Private Profil-, Tagebuch-, Gewichts-, Wasser-, Aktivitäts-, Rezept- oder HealthKit-Daten werden nicht an Supabase übertragen.

Einreichungen sind zunächst nicht öffentlich und werden moderiert. Freigegebene Einträge erscheinen als **TraceIt Community** im öffentlichen Katalog. Problematische Inhalte können aus der App per E-Mail gemeldet und anschließend entfernt werden. Missbräuchliche Konten können gesperrt werden.

## Kontolöschung

Ein angemeldetes Community-Konto kann direkt unter **Einstellungen → Datenschutz & Daten → Community-Konto löschen** gelöscht werden. Dabei werden das Supabase-Auth-Konto und nicht veröffentlichte Einreichungen gelöscht. Bereits freigegebene Katalogeinträge können aus Gründen der Katalogkonsistenz ohne Verknüpfung zum gelöschten Konto erhalten bleiben. Moderations- und Sicherheitsnachweise können soweit erforderlich in anonymisierter Form fortbestehen.

Lokale Trackingdaten sind unabhängig vom Community-Konto. Du kannst sie in der App löschen oder durch Entfernen der App und ihrer Daten vom Gerät beseitigen.

## Supabase

Für Community-Authentifizierung, Einreichungen, Moderation und den öffentlichen Katalog nutzt TraceIt **Supabase**. Das eingesetzte Projekt wird in der Region Frankfurt (`eu-central-1`) betrieben. Supabase verarbeitet die genannten Daten als technischer Dienstleister nach seinen Datenschutz- und Sicherheitsbedingungen. Weitere Informationen: [supabase.com/privacy](https://supabase.com/privacy).

## Apple HealthKit

Mit deiner Erlaubnis kann TraceIt Schritte, aktive Kalorien und Körpergewicht aus Apple Health lesen und Gewichtseinträge in Apple Health schreiben. HealthKit-Daten werden ausschließlich für Aktivitäts-, Fortschritts- und Gewichtsfunktionen verwendet. Sie werden nicht an Supabase übertragen und nicht für Werbung, Marketing oder Tracking genutzt. Berechtigungen kannst du jederzeit in den iOS-Einstellungen oder in der Health-App ändern.

## Kamera, Fotos, Mikrofon und Spracherkennung

TraceIt fragt Berechtigungen erst an, wenn du die jeweilige Funktion nutzt. Kamera und Fotos dienen Barcode-Scans, Nährwerttabellen-Scans und optionalen Lebensmittel- oder Rezeptbildern. Mikrofon und Apple-Spracherkennung dienen Spracheingaben für den Assistenten. Apple kann Spracheingaben nach seinen Bedingungen verarbeiten. Wenn du eine Berechtigung ablehnst, bleiben die übrigen App-Bereiche nutzbar.

## Inhaltsmeldungen und Support

Wenn du einen Community-Eintrag meldest oder den Support kontaktierst, öffnet TraceIt deine E-Mail-App mit einer vorbereiteten Nachricht. Erst wenn du die Nachricht selbst absendest, werden Absenderadresse, Nachrichtentext, die technische Katalog-ID und gegebenenfalls von dir ergänzte Angaben über deinen E-Mail-Anbieter an [TraceItSupport@icloud.com](mailto:TraceItSupport@icloud.com) übertragen.

## Weitere Empfänger

Abhängig von den von dir genutzten Funktionen können Daten durch folgende Anbieter verarbeitet werden:

- Apple für Mit Apple anmelden, HealthKit, Speech/Spracherkennung, iCloud Mail sowie TestFlight und App Store Connect;
- Supabase für Community-Konto, Einreichungen, Moderation und öffentlichen Katalog;
- dein E-Mail-Anbieter, wenn du eine Meldung oder Supportnachricht absendest.

Private Trackingdaten werden in der aktuellen Release-Version nicht über iCloud/CloudKit synchronisiert.

## Rechtsgrundlagen

Soweit die DSGVO anwendbar ist, erfolgt die Verarbeitung insbesondere zur Bereitstellung gewünschter App- und Community-Funktionen (Art. 6 Abs. 1 lit. b DSGVO), aufgrund deiner Einwilligung bei optionalen Berechtigungen (Art. 6 Abs. 1 lit. a DSGVO), aufgrund berechtigter Interessen an Sicherheit, Moderation, Missbrauchsverhinderung und zuverlässigem Betrieb (Art. 6 Abs. 1 lit. f DSGVO) sowie zur Erfüllung gesetzlicher Pflichten (Art. 6 Abs. 1 lit. c DSGVO).

## Speicherdauer

Lokale Daten bleiben gespeichert, bis du sie in der App löschst, die App zurücksetzt oder App und Daten vom Gerät entfernst. Community-Kontodaten und nicht veröffentlichte Einreichungen werden bei der In-App-Kontolöschung gelöscht. Freigegebene, vom Konto getrennte Katalogdaten bleiben bis zur Entfernung oder Moderation verfügbar. Support-E-Mails und notwendige Moderationsnachweise werden nur so lange gespeichert, wie sie für Bearbeitung, Sicherheit oder gesetzliche Pflichten erforderlich sind.

## Deine Rechte

Soweit anwendbar, hast du insbesondere Rechte auf Auskunft, Berichtigung, Löschung, Einschränkung, Datenübertragbarkeit, Widerspruch, Widerruf einer Einwilligung für die Zukunft und Beschwerde bei einer Datenschutzaufsichtsbehörde. Kontaktiere dafür [TraceItSupport@icloud.com](mailto:TraceItSupport@icloud.com).

## Kinder

TraceIt richtet sich nicht gezielt an Kinder. Wenn du glaubst, dass ein Kind ohne erforderliche Zustimmung personenbezogene Daten bereitgestellt hat, kontaktiere uns bitte.

## Änderungen

Diese Datenschutzerklärung kann bei Änderungen der App, der Datenverarbeitung oder rechtlicher Anforderungen aktualisiert werden. Die aktuelle Version wird unter dieser URL veröffentlicht.

---

# Privacy Policy for TraceIt

Last updated: July 13, 2026

This Privacy Policy explains how the iOS app **TraceIt** processes personal data. TraceIt is a nutrition and progress tracking app for iPhone.

## Controller and Contact

Oliver Heidebroek  
Email: [TraceItSupport@icloud.com](mailto:TraceItSupport@icloud.com)

## Summary

In the current TestFlight/App Store release, private profile, nutrition, diary, activity, weight, water, recipe, and settings data is stored locally on your iPhone. It is not uploaded to Supabase or to a private CloudKit database. Only when you intentionally use Community features is the Community and account data described below transferred to Supabase. TraceIt does not use advertising or tracking SDKs, does not track users across apps or websites, and does not sell personal data.

## Data Processed on Your Device

Depending on your use, TraceIt may process profile data, nutrition and diary data, tracking entries, recipes, optional images, camera input, speech input, app settings, and onboarding status on your device. This private tracking data remains local in the current release unless you choose to export or share it yourself.

## Community Account and Content

You may read the public Community catalog without a Community account. To submit a food, you sign in with **Sign in with Apple**. Supabase Auth then processes a technical user identifier and, depending on your Apple choice, your email address. Apple may provide a private relay address.

An intentional submission sends only the food data needed for catalog review to Supabase: name, brand, category, barcode, serving information, seven nutrition values per 100 g, and technical submission and moderation metadata. Private profile, diary, weight, water, activity, recipe, or HealthKit data is not sent to Supabase.

Submissions are not public until moderated. Approved items appear as **TraceIt Community** in the public catalog. Users can report problematic content by email from the app, moderators can remove content, and abusive accounts can be blocked.

## Account Deletion

A signed-in Community account can be deleted directly under **Settings → Privacy & Data → Delete Community Account**. This deletes the Supabase Auth account and unpublished submissions. Approved catalog entries may remain without any link to the deleted account to preserve catalog integrity. Moderation and security records may remain in anonymized form where necessary.

Local tracking data is independent of the Community account. You can delete it in the app or by removing the app and its data from your device.

## Supabase

TraceIt uses **Supabase** for Community authentication, submissions, moderation, and the public catalog. The project is hosted in the Frankfurt (`eu-central-1`) region. Supabase processes the described data as a technical service provider under its privacy and security terms. See [supabase.com/privacy](https://supabase.com/privacy).

## Apple HealthKit

With your permission, TraceIt may read steps, active calories, and body weight from Apple Health and may write body-weight entries to Apple Health. HealthKit data is used only for activity, progress, and weight features. It is not sent to Supabase and is not used for advertising, marketing, or tracking. You can change permissions at any time in iOS Settings or the Health app.

## Camera, Photos, Microphone, and Speech Recognition

TraceIt asks for permissions only when you use the related feature. Camera and photos support barcode scans, nutrition-label scans, and optional food or recipe images. Microphone and Apple Speech Recognition support voice input for the assistant. Apple may process speech input under its terms. Denying a permission does not prevent use of unrelated app features.

## Content Reports and Support

When you report a Community item or contact support, TraceIt opens your email app with a prepared message. Only if you send it yourself are your sender address, message, technical catalog ID, and any information you add transmitted through your email provider to [TraceItSupport@icloud.com](mailto:TraceItSupport@icloud.com).

## Other Recipients

Depending on the features you use, data may be processed by Apple for Sign in with Apple, HealthKit, Speech Recognition, iCloud Mail, TestFlight, and App Store Connect; by Supabase for the Community account, submissions, moderation, and public catalog; and by your email provider when you send a report or support message. Private tracking data is not synchronized through iCloud/CloudKit in the current release.

## Legal Bases

Where the GDPR applies, processing may be based on providing requested app and Community functions (Art. 6(1)(b)), consent for optional permissions (Art. 6(1)(a)), legitimate interests in security, moderation, abuse prevention, and reliable operation (Art. 6(1)(f)), and compliance with legal obligations (Art. 6(1)(c)).

## Retention

Local data remains until you delete it in the app, reset the app, or remove the app and its data. Community account data and unpublished submissions are deleted through in-app account deletion. Approved, de-linked catalog data remains available until removed or moderated. Support emails and necessary moderation records are retained only as long as needed for handling, security, or legal obligations.

## Your Rights

Where applicable, you may have rights to access, correct, delete, restrict, transfer, or object to processing, withdraw consent for the future, and lodge a complaint with a data protection authority. Contact [TraceItSupport@icloud.com](mailto:TraceItSupport@icloud.com).

## Children

TraceIt is not directed specifically at children. If you believe a child provided personal data without required consent, please contact us.

## Changes

This Privacy Policy may be updated when app functionality, processing, or legal requirements change. The current version is published at this URL.
