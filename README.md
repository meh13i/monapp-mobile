Noor+ — Complete project ready for Codemagic (AAB) and Play Store
===============================================================

Package name: com.noorplus.app

Subscriptions (product IDs to create in Play Console):
- Monthly product id: noorplus_monthly  -> suggested price: 1.99 EUR / month
- Yearly product id : noorplus_yearly   -> suggested price: 10.99 EUR / year

AdMob:
- This build uses Google test App ID and Banner ID (replace with your own in production)
  - App ID: ca-app-pub-3940256099942544~3347511713
  - Banner ID: ca-app-pub-3940256099942544/6300978111

Included:
- Flutter project (lib/)
- codemagic.yaml configured to build an AAB
- Cloud Function (cloud_functions/index.js) for subscription verification
- README with next steps and checklist

Before building on Codemagic:
1. Create the subscriptions in Google Play Console with the EXACT product IDs: 'noorplus_monthly' and 'noorplus_yearly'.
2. Replace test AdMob IDs with your real ones before production.
3. Deploy the cloud function to Firebase and configure service account credentials for Google Play Developer API.
4. Add google-services.json if using Firebase features.
5. Configure keystore for signing (Codemagic can manage automatically).
6. Upload the produced AAB to Play Console and fill store listing (title, descriptions, screenshots).

Need help?
- I can walk you step-by-step to Codemagic (I can produce screenshots).
- I can replace test AdMob IDs with real ones and repackage.
- I can deploy the cloud function commands for you to run.

