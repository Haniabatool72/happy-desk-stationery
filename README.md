# 🖍️ Happy Desk Stationery

Online store and shop counter system for **Happy Desk**, a stationery, school supplies, art & craft and toys shop in Pakistan.

Creativity • Joy • Organisation

## ✨ Features

**Online store**
- Stationery and toys catalog with categories, search and product pages
- Cart and checkout with Cash on Delivery
- Order tracking page
- Photo gallery
- Mobile friendly, SEO ready (sitemap and robots.txt)

**Counter and billing (for the shop)**
- Pick products, add customer name and phone, discount (% or Rs.) and delivery charges
- Confirm the bill, then send it to the customer on WhatsApp in one tap
- Print or download the invoice
- Stock is updated automatically when a bill is made

**Admin dashboard**
- Add and edit products, prices, sale prices, stock and photos
- Online orders and shop bills
- Inventory adjustments with reasons
- Gallery, customers/staff roles, delivery and offers settings

**Database**
- Supabase (products, orders, counter sales, stock, users)
- Works with thousands of products

## 📁 Files

| File | What it does |
|---|---|
| `index.html` | The whole website, counter and admin |
| `_redirects` | Page routing for Netlify |
| `vercel.json` | Page routing for Vercel |
| `robots.txt` | Search engine rules |
| `generate-sitemap.mjs` | Builds `sitemap.xml` from your live products |

## 🚀 Deploy

1. Upload all files to a GitHub repo.
2. Connect the repo to **Vercel** or **Netlify**. No build step is needed.
3. Put your Supabase `url` and `anonKey` inside `index.html`.

## 🗺️ Make the sitemap

After adding products (needs Node 18 or newer):

```bash
node generate-sitemap.mjs https://your-site.com
```

Upload the new `sitemap.xml` and `robots.txt` next to `index.html`.

## 🔐 Pages

| Page | Who can use it |
|---|---|
| `/` , `/stationery`, `/toys`, `/gallery` | Everyone |
| `/cart`, `/checkout`, `/track` | Customers |
| `/counter` | Staff |
| `/admin` | Admin only |

## ⚠️ Security

- The Supabase `anonKey` is public and is fine inside `index.html`.
- **Never** put the `service_role` key in this repo.
- Keep the repo **Private** if you do not want others to see your code.

## 📞 Contact

Happy Desk Stationery
Instagram: [@happy.deskk](https://www.instagram.com/happy.deskk)
Facebook: [Happy Desk](https://www.facebook.com/share/19G3y15yir/)
WhatsApp: +92 334 8881214
