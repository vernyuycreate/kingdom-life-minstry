# Kingdom Life International Ministries (KLIM) - Demo Website
Built by Vernyuy Services - WhatsApp: +237 652 311 022

## How to run
Open `index.html` in any browser. Internet is needed for GSAP and Google Fonts (loaded from CDNs).
Pages are reached through the menu (`#home`, `#sermons`, `#events`, `#give`, `#admin` ...).
Admin demo: `index.html#admin`, password `demo`. This is NOT real security; data is kept in localStorage.

## Images to add
Put every file below in `assets/images/`. Use exactly these names (.jpg).
Until a file exists, the site shows a coloured placeholder; once it exists, it appears automatically.

| File name | Used for | Suggested size |
|---|---|---|
| hero-worship.jpg | Homepage hero background (worship or congregation, dark and wide) | 2000x1200 |
| welcome-congregation.jpg | "Welcome" section arch image (portrait) | 1200x1500 |
| pastor-portrait.jpg | Senior pastor portrait (home and Our Pastor page) | 1200x1500 |
| dept-worship.jpg | Worship ministry card | 900x1100 |
| dept-prayer.jpg | Prayer ministry card | 900x1100 |
| dept-evangelism.jpg | Evangelism & Outreach card | 900x1100 |
| dept-youth.jpg | Youth ministry card | 900x1100 |
| dept-children.jpg | Children's ministry card | 900x1100 |
| dept-media.jpg | Media & Communications card | 900x1100 |
| dept-ushering.jpg | Ushering department card | 900x1100 |
| dept-welfare.jpg | Welfare & Hospitality card | 900x1100 |
| sermon-1.jpg | Thumbnail: The Weight of Glory | 1280x800 |
| sermon-2.jpg | Thumbnail: Praying Without Ceasing | 1280x800 |
| sermon-3.jpg | Thumbnail: Raised to Walk | 1280x800 |
| sermon-4.jpg | Thumbnail: A Table in the Wilderness | 1280x800 |
| sermon-5.jpg | Thumbnail: Worship as Warfare | 1280x800 |
| sermon-6.jpg | Thumbnail: Kingdom Families | 1280x800 |
| map.jpg | Contact page map image (screenshot of the church location) | 1280x800 |

Total: 18 images. Keep each under about 300 KB (compress with squoosh.app) for fast mobile loading.
Use photos you own or have a licence for.

## Not images, but needed for a live version
- Real sermon video/audio files (`assets/videos`, `assets/audio`) and a live-stream embed. The players are demo only.
- A backend for forms, payments and the admin. Everything here is saved in the visitor's browser only.

## Changing the WhatsApp call-to-action
All button links open WhatsApp. To change the number or message, edit the `WA` constant in `index.html`.
"# kingdom-life-minstry" 
