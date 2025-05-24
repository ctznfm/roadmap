## FLOW: `@ctznfun` Campaign Lifecycle

1. **User tags `@ctznfun` on X (Twitter)**

> Example: “Hey @ctznfun, help me promote my new token!”

2. **ctznfun bot auto-replies**

> “Hi! Can you describe the type of campaign you want to launch?”

3. **Client explains their project and objective**

   * Project name, link, goal (awareness / followers / traffic / holders)

4. **ctznfun AI follows up to understand the context**

   * Asks deeper questions: target market? chain? tone? competitors?

5. **Set marketing budget:**

   * ✅ If the user **sets a max budget** → AI calculates best content plan within that budget
   * ❌ If the user **does not set a budget** → AI recommends a budget based on project needs

6. **If agreed, ctznfun sends a payment link**

   * Multichain support (OKX Wallet API: USDT, USDC, BNB, ETH, SOL, BTC)
   * Includes: contributor reward + platform fee + buffer + AI cost
   * Multichain support (OKX Wallet API)

7. **Once payment is confirmed**, backend will:

   * Generate campaign ID + content plan (via AI)
   * Store all campaign content in the dashboard

8. **ctznfun sends the dashboard link to the user**

   * User must log in via X OAuth + ctzn.fun create a new wallet

9. **Inside the dashboard, user can customize:**

   * Post via: `@ctznfun` or user’s own account
   * Set post schedule (date + time)
   * Upload image/video cover
   * Edit caption and hashtags
   * Add partner/KOL tags

10. **User clicks “Start Campaign”** on the dashboard or replies “Start Campaign” on X

11. **ctznfun starts tracking engagement & validating contributors:**

* Check contributor followers (`min 50–100`)
* Verify account age (not newly created)
* Detect quote tweets with meaningful captions (at least 3 non-spam words)
* Detect relevant, original comments (no copy-paste)
* Exclude spam retweets (mass RT behavior from bots)

12. **Point system is automatically activated:**

* Like = 1 pt, RT = 2 pts, Quote = 3 pts, Comment = 2 pts
* 500 pts = \$5 reward (default)
* Calculated every 24 hours

13. **If a contributor’s wallet reaches 500 pts (minimum threshold):**

* Reward is converted to USDT/USDC (via OKX API)
* User can withdraw funds anytime if balance > \$5
