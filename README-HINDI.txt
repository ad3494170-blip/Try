AKASH WP BOT — RENDER HOSTING GUIDE (Hindi)

Is ZIP mein ek bahut simple website hai. Yeh WhatsApp bot nahi hai; sirf website ka starter project hai.

FILES:
- server.js          Website server
- package.json       Dependencies aur start command
- public/index.html  Website ka design
- README-HINDI.txt   Yeh guide

ANDROID MOBILE SE RENDER PAR DEPLOY:

1. ZIP ko extract karo.
2. GitHub par login karo aur "New repository" banao.
3. Repository ka naam: akash-wp-bot
4. Extract ki hui files GitHub repository mein upload karo.
   Dhyan rahe: package.json, server.js aur public folder repository ke root mein hone chahiye.
5. Render.com kholo aur GitHub se sign in karo.
6. New + par tap karke "Web Service" chuno.
7. Apni akash-wp-bot repository connect karo.
8. Settings:
   - Runtime: Node
   - Build Command: npm install
   - Start Command: npm start
   - Instance type: Free (agar account mein available ho)
9. "Create Web Service" dabao aur deploy complete hone do.
10. Render jo URL dega, use kholo. Akash WP Bot website dikhni chahiye.

TEST:
Aapki website URL ke aakhir mein /health lagakar kholo.
Example: https://YOUR-SITE.onrender.com/health
JSON mein status "ok" aaye to server sahi chal raha hai.

NOTE:
- Is project mein WhatsApp pairing, bot commands ya message automation nahi hai.
- Render free service inactive rehne par sleep ho sakti hai aur dobara khulne mein thoda samay lag sakta hai.
- Kisi bhi secret/API key ko public GitHub repository mein upload mat karna.
