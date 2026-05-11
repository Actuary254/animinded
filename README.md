# AniMinded

AniMinded is a Vue + Vite frontend application that helps users discover anime, save titles to a Plan to Watch list, move completed titles into a Watched list, and rate/review them locally in the browser.

## Live Links

- GitHub Repository: https://github.com/Actuary254/animinded
- Live Application: https://animinded-9r5x.vercel.app/

## Implemented MVP Features

- Genre-based smart anime generator using a local curated dataset
- Bookmark system for a persistent Plan to Watch list
- Watched list with movement from bookmarks to completed titles
- Interactive 1–10 rating system
- Search and genre filtering on the Bookmarks page
- Search and rating filtering on the Watched page
- Personal review notes for watched anime
- localStorage persistence across browser sessions
- Responsive dark anime-inspired interface

## Usage Instructions for Testing

1. Open the live app.
2. Go to **Generator**.
3. Select a genre and click **Generate**.
4. Click **Bookmark This** to save the title.
5. Go to **Bookmarks** and confirm that the title appears.
6. Use the search box or genre filter to test filtering.
7. Click **Mark as Watched**.
8. Go to **Watched**, rate the anime from 1–10, and add a short review note.
9. Refresh the page to confirm the data remains saved in localStorage.

No login or dummy account is required because AniMinded stores user data locally in the browser.

## Future Scope

Future improvements could include backend authentication, a cloud database, anime poster images, API integration, advanced recommendation logic, and account-based syncing across devices.

## Local Development

```bash
npm install
npm run dev
npm run build
```
