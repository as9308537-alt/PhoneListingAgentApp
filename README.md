# Listing Agent — Android starter

This is a real Android AccessibilityService starter for a teach-once/replay phone agent.

## Mobile build path
1. Create a GitHub repository and upload this folder.
2. Open **Actions → Build APK → Run workflow**.
3. Download **ListingAgent-debug-apk** from the workflow run.
4. Install the APK on Android.
5. Open the app → enable Accessibility → Start Training → perform the workflow in the target app → Stop & Save.
6. Later use Voice Command or Run Saved Workflow.

## Important
- This starter records semantic accessibility events, not passwords/OTP.
- Security screens, CAPTCHA, OTP and identity checks should be completed by the account owner.
- Amazon/Flipkart API integration and AI image generation are the next modules; this starter does not claim to bypass marketplace controls.
- The replay engine is intentionally conservative and should be tested with a small workflow before any bulk operation.
