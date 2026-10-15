# Chezs' Home on the Web

The personal website of Cheryl ("Chezs", also "Buttons"), built in 2000–2001.
It was originally hosted at `chezs.faithweb.com`. Her earlier versions lived on
Angelfire (`angelfire.com/tv/chezs`) and Topcities (`chezs.topcities.com`).

## Where it lives

| What | Where |
| --- | --- |
| Live site (GitHub Pages) | https://bradg.github.io/chezs/ |
| Source on GitHub | https://github.com/bradg/chezs (branch `main`, which Pages serves from the root) |
| Source on Bitbucket (backup copy) | https://bitbucket.org/bradg76/chezs (branch `main`) |
| Private copy on claude.ai | https://claude.ai/artifact/WEkMRQvBeo5BbmjnEtZu7B |

GitHub and Bitbucket hold the same history. To update both:

```sh
git push github cleanup:main
git push origin cleanup:main
```

## Branches

- **`master`**: the original files, untouched. They were saved straight from
  the live site, so they still include the host's ads, counters and leftover folders.
- **`cleanup`** (published as **`main`**): the cleaned-up site that is deployed.

## What's in it

- **Main site (faithweb, 2000–2001):** the files in the root folder.
  `index.html` is the entrance page.
- **`Guestbook.html`:** rebuilt from Internet Archive snapshots of her Bravenet
  guestbook. It has 42 entries; spam, ads and invitations were left out.
- **Poems** (`truefriend`, `recipe4love`, `sunsetsunrise`, `myfriend`,
  `dontloseit`): these were originally hosted on Angelfire and homepage.com.
- **`angelfire/`:** her first site (2000).
- **`topcities/`:** her 2001 redesign. It includes the memorial she wrote for
  the dogs Freckles and Baxter, and her Paint Shop Pro class homework.
- `chezs-home.html` is the entrance page as published to the claude.ai copy. It isn't used by the live site.

## What was changed

- Removed the host ads, pop-ups, Site Meter counters and the host's own folders.
- Removed the music (MIDI) embeds, because none of the music files survived.
- Removed images whose files are missing. Pages whose background tile was lost
  got a background colour that keeps the text readable.
- Pages and images were recovered from the
  [Internet Archive](https://web.archive.org/) wherever copies existed.
  Roughly 260 images were never archived and are lost.
- Links to pages that are gone were removed. Links to other people's sites
  point to their Internet Archive copies.

Everything is plain static HTML. There is no build step: open `index.html`
in a browser to view it locally.
