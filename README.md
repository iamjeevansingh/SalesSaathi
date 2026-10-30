# Sales Saathi (Android)

A free AI sales assistant: save leads, get a daily follow-up reminder notification,
write WhatsApp messages with AI, and find new customer types for your city.

## Get the APK (free, using GitHub)
1. Upload this whole folder to a new GitHub repository (keep the `.github` folder).
2. Open the repository's **Actions** tab. The "Build APK" workflow runs on every push
   (or tap **Run workflow**).
3. When it finishes (about 3-5 minutes), open the run and download **SalesSaathi-apk**
   under Artifacts. Unzip it to get `app-debug.apk`.
4. Copy it to your phone and install it (allow "Install unknown apps" when asked).

## Turn on the AI (free)
1. Go to https://aistudio.google.com/app/apikey, sign in with Google, create an API key.
2. In the app open **Settings**, paste the key, tap **Test AI**, then **Save settings**.

The model name defaults to `gemini-2.5-flash`. If Google retires it, enter a newer model
name in Settings.

## Notes
- Leads are stored only on the phone. Uninstalling the app deletes them.
- The daily reminder time is set in Settings (default 10:00).
