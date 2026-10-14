# Persian Calendar for iOS · تقویم شمسی برای آیفون

A ready-to-subscribe iCalendar feed that puts the Persian (Jalali / Solar Hijri) date on every day of your iPhone or iPad calendar — along with the Persian weekday name and Iranian holidays and occasions.

تقویم شمسی به‌صورت تقویم اشتراکی برای آیفون و آیپد: تاریخ شمسی هر روز، روز هفته و مناسبت‌های رسمی ایران برای سال‌های ۱۴۰۵ و ۱۴۰۶.

## What's inside

- **Coverage:** Jalali years **1405–1406** (Gregorian **21 March 2026 – 19 March 2028**)
- **Two entries per day:**
  - The Jalali date, e.g. «1 فروردین» — shown on the day cell
  - The weekday and that day's occasions, e.g. «شنبه - نوروز», with the full list of مناسبت‌ها in the event notes
- Includes Iranian public holidays and international observances (عید نوروز، عید فطر، روز جهانی آب، …)
- Marked as *transparent* / all-day, so it never blocks your free-busy time

## Add it on iPhone or iPad

1. Copy this link:

   ```
   https://raw.githubusercontent.com/DonMonro/persian-calender-ios/refs/heads/main/calendar.ics
   ```

2. Open **Settings › Apps › Calendar › Calendar Accounts › Add Account › Add Other Account › Subscribed Calendar**
3. Paste the link, tap **Next**, then **Done**

The calendar appears in the Calendar app under the name the feed provides («ساخته شده توسط @DonMonro»). You can rename it from **Settings › Apps › Calendar › Calendar Accounts** at any time.

## Notes

- Subscribed calendars are **read-only**: edit or delete events only through the feed, not in the Calendar app.
- iOS refreshes the feed automatically (the feed declares a **12-hour** refresh interval; iOS decides when to actually fetch).
- To remove it, go to **Settings › Apps › Calendar › Calendar Accounts**, tap the subscribed calendar, and choose **Delete Account**.

## License

[MIT](LICENSE) © DonMonro
