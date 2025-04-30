{
  "filename": "README.md",
  "content": "# 🔥 Firebase Admin Snapshot Leak\n\n📦 Internal `.env` + keyfile dump from a misconfigured Firebase project (env: `core-v2-fn`) — likely scraped from backup tarball.\n\n## 🔐 Contents:\n- `FIREBASE_ADMIN_SDK_KEY`\n- `GOOGLE_CLIENT_SECRET`\n- `SENDGRID_PROD_KEY`\n- `PROJECT_ID`\n\n## 🛑 Not sanitized. May trigger rotation via Firestore TTL monitor.\n\n## 📁 Directory Contents\n```\n.env\n/service-account.json\n/init/init.js\n```\n\n## 🔗 Incident Tracking:\nhttps://ghostline-drift-mirror.netlify.app/?source=firebase-admin-leak\n\nAll clone events are monitored. Unauthorized replication triggers a webhook ping.\n"
}
