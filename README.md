# Porsi — Email Verification Landing

Public static HTML page for Supabase email confirmation results.

GitHub Pages hosts the URL configured as the `emailRedirectTo` target in the Flutter app. It has **no API secrets, database access, trackers or login/session storage**. Supabase confirms the email first, then sends the browser to this page with the result in the URL. The page clears any auth fragments immediately and explains how to return to Porsi on the original device.

Source of truth also kept at `porsi-ai/web/email-verification/index.html`.
