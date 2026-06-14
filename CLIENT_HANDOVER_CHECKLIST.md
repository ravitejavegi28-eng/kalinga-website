# Client Handover Checklist

Use this checklist before giving the restaurant website to a client.

## 1. Client Details

- Restaurant name is correct.
- Phone and WhatsApp number are correct.
- Address is correct.
- Opening hours are correct.
- Google Maps link opens the correct location.
- Instagram/Facebook links open correctly.

## 2. Customer Website

- Home page loads properly on phone and laptop.
- Menu items and prices are checked by the client.
- Photos are approved by the client.
- Reviews section uses real public review sources.
- Call button works.
- WhatsApp button works.
- Directions button works.
- Booking form submits successfully.
- Booking success message shows clearly.

## 3. Staff/Admin Website

- Staff login password is known only to the client/staff.
- New bookings appear in the dashboard.
- Today/Tomorrow/Yesterday/All filters work.
- Search works by name, phone, or booking ID.
- Confirmed and Cancelled status updates work.
- WhatsApp message opens after Confirmed/Cancelled.
- Delete asks for confirmation before removing a booking.
- Export CSV downloads booking data.
- Mobile admin view is easy to use.

## 4. Database And Security

- Supabase table is connected.
- Service role key is only in Vercel backend environment variables.
- Service role key is not inside customer website code.
- Public/anon key is not used for admin-only actions.
- Old test bookings are deleted before client handover if needed.

## 5. Deployment

- Customer site URL is final.
- Staff/admin site URL is final.
- Both sites are deployed from GitHub/Vercel.
- Latest changes are pushed to GitHub.
- Test with Ctrl + F5 after deployment.
- Custom domain is connected if client bought one.

## 6. Client Training

- Show client how to open staff dashboard.
- Show how to confirm a booking.
- Show how to cancel a booking.
- Show how to delete wrong/test bookings.
- Show how to export CSV.
- Explain that WhatsApp messages need staff to press send.

## 7. Final Delivery Message

Send this to the client:

```
Your restaurant website and staff booking dashboard are ready.

Customer website:
<CUSTOMER_WEBSITE_URL>

Staff dashboard:
<STAFF_DASHBOARD_URL>

Please test booking, call, WhatsApp, directions, and admin login once.
After your confirmation, we can connect your custom domain.
```
