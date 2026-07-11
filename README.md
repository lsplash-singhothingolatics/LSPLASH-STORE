# LSPLASH store

Node.js store with server-verified Razorpay payments. Zero npm dependencies.

## Run locally
    RAZORPAY_KEY_ID=rzp_test_xxx RAZORPAY_KEY_SECRET=yyy node lsplash-store.js
Then open http://localhost:3000

## Deploy on Render
- Build Command:  (leave blank)
- Start Command:  node lsplash-store.js
- Environment variables:  RAZORPAY_KEY_ID, RAZORPAY_KEY_SECRET, SESSION_SECRET
