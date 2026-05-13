# Kalinga Kitchen Website

Public customer website for Kalinga Kitchen & Bar.

## What this repo does

- Shows restaurant information, menu, location, and contact details.
- Lets customers submit table booking requests.
- Sends bookings to the separate backend/admin website.

## Deployment

Deploy this repo as a static site on Vercel.

The booking form currently sends production requests to:

```text
https://kalinga-backend.vercel.app/api/bookings
```

If your backend Vercel URL is different, update `PRODUCTION_API_BASE_URL` near the bottom of `index.html`.

## Local Testing

Run the backend repo locally first:

```bash
npm install
npm start
```

Then open this website locally. When the hostname is `localhost` or `127.0.0.1`, the form sends requests to:

```text
http://localhost:3000/api/bookings
```
