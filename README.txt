MOONVEIL TAROT — V15 FRONT-END PROTOTYPE — UI FIX PASS

START HERE
1. Extract the ZIP on Android.
2. Keep all files in the same folder.
3. Open index.html in a browser.
4. Tap “Book My Session”.

BOOKING FLOW IN THIS PROTOTYPE
- AI Astrologer: no date/time slot; ₹3/minute; minimum 10 minutes (₹30); wallet demo.
- Human Astrologer: select sample astrologer -> choose date -> choose consecutive 15-minute slots -> choose private text chat or video call -> enter email/name -> payment demo. Example profile prices vary (₹150/₹200/₹250 per 15-minute slot). In the live version each approved astrologer can set a custom slot price.
- Your Booking: shows bookings saved in the same browser; cancel action is a demo, reschedule requires live availability integration.
- Birth Details: form for up to two people (name, age, sex, birth time and birth place).
- Astrologer application shows ₹2,499 joining fee and 24% Moonveil commission per completed session; it includes a custom 15-minute slot price field. Example: on ₹150, commission ₹36 and astrologer share ₹114 before applicable taxes/other charges. These are demo terms, not payment-enforced in this static prototype.
- User and astrologer login pages remain separate; public admin login is not shown.
- Chat/video selection is present in the booking flow, but real chat/video calls are not connected.

IMPORTANT: NOT PRODUCTION READY
This is a static HTML prototype. It does NOT include real authentication, secure customer accounts, actual email delivery, server-side wallet balances, live AI API responses, payment gateway verification, confirmed slot locking, secure rescheduling/cancellation, automated 15-minute login credential delivery, or private astrologer-only birth-detail access. Demo wallet/booking data is stored in browser localStorage and may be lost or altered. Do not accept real payments or collect real sensitive customer information until a secure backend and payment/email providers are implemented. Never put API keys or admin secrets in HTML. Sample astrologers are placeholders.


V15 UI FIX PASS
- Removed customer booking CTA from login screens so the astrologer/customer login pages stay focused on sign-in.
- Kept the V14 embedded homepage hero artwork (no separate image file required for the main hero).
- Added a small overflow-safety rule to login screens for narrow mobile displays.
- This is still a static front-end prototype: payment, authentication, email, wallet, slot locking, and secure rescheduling/cancellation need a real backend before launch.


V16 UI refinement: added a subtle lavender/silver glow and rounded border to login navigation links only. Other page content and artwork are retained from V15. This remains a static frontend prototype; backend authentication, payments, and wallet are not implemented.
