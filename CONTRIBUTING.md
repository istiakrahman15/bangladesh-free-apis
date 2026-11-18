# Contributing to Bangladesh Free APIs

Thank you for helping Bangladeshi developers. This repo grows one API at a time, and a small pull request is the best way to help.

## English

### Rules

1. **Free only.** The API must have a free tier or be fully free. If it is paid only, do not add it.
2. **Legal only.** Only official APIs from the provider. No scraped APIs, no unofficial Facebook, YouTube, bKash or Nagad APIs.
3. **Official link only.** Link to the official docs or homepage. Do not link to a blog post or a copied list.
4. **One API per pull request.** It is easier to review and easier to fix.
5. **Check the link first.** Open the link yourself and make sure the docs page loads and the free tier is real.

### How to add 1 API

1. Fork this repo and clone your fork.
2. Find the right section in `README.md`. If no section fits, use the closest one and say so in your pull request.
3. Add one row to that section table, in this exact format:

```
| [API Name](https://official-docs-link) | Short description in English, with a Bangla use case in brackets if it helps (Dhaka weather app) | No | Yes | Yes | Free, your free tier note here |
```

Fill in the columns like this:

- **API:** name linked to the official docs or homepage.
- **Description:** one short sentence in English. Add a Bangla use case in brackets where it helps, for example `(Dhaka weather app)`.
- **Auth:** `No` if no key is needed, `apiKey` if a free key is needed after signup, `OAuth` if OAuth is needed.
- **HTTPS:** `Yes` or `No`.
- **CORS:** `Yes` if the API works from browser JavaScript, `No` if it does not, `Unknown` if you did not test it.
- **Free tier:** the free limit from the official docs, for example `Free, 100 requests per day`. Do not guess a limit. If you are not sure, write `Free tier, check official docs`.

4. Add the same API to `apis.json` in the same category, with the same name, url, description, auth, https, cors, category, free_tier and bangladesh_relevant values.
5. Keep the table sorted by name inside the section if you can, but a correct new row matters more than perfect sorting.
6. Open a pull request and fill in the pull request template.

### How to fix a dead link

1. Open the link and confirm it is really dead or moved.
2. If it moved, update the link to the new official docs page.
3. If it shut down or has no free tier any more, remove the row from `README.md` and from `apis.json`, and say why in your pull request.

### How to suggest an API without a pull request

Open an issue with the **Add API** template and fill in the name, official link, and free tier. Someone else can turn it into a pull request.

## Bangla

### Niyom

1. **Sudhu free API.** Free tier na thakle add korben na.
2. **Sudhu legal API.** Sudhu official API add korben. Scraping kora API, unofficial Facebook, YouTube, bKash ba Nagad API add korben na.
3. **Sudhu official link.** Official docs ba homepage er link diben.
4. **Ek pull request e ekta API.** Review korte sohoj hoy.
5. **Link ta age nije khule dekhben.** Docs page khule kina, ar free tier sotti ache kina, check korben.

### 1 ta API kivabe add korben

1. Repo ta fork kore clone korben.
2. `README.md` e sothik section khujben. Kono section na mille kachakachi section e diben, ar pull request e likhben.
3. Section er table e ekta row add korben, ei format e:

```
| [API Name](https://official-docs-link) | Short description in English, with a Bangla use case in brackets if it helps (Dhaka weather app) | No | Yes | Yes | Free, your free tier note here |
```

Column gula evabe puron korben:

- **API:** official docs ba homepage er link soho naam.
- **Description:** English e ekta choto line. Dorkar hole Bangla use case bracket e likhben, jemon `(Dhaka weather app)`.
- **Auth:** key na lagle `No`, free signup er por key lagle `apiKey`, OAuth lagle `OAuth`.
- **HTTPS:** `Yes` ba `No`.
- **CORS:** browser JavaScript theke kaj korle `Yes`, na korle `No`, test na korle `Unknown`.
- **Free tier:** official docs theke free limit likhben, jemon `Free, 100 requests per day`. Andaz e limit likhben na.

4. `apis.json` e o eki API add korben, eki category te, eki naam, url, description, auth, https, cors, category, free_tier ar bangladesh_relevant diye.
5. Pull request khulben ar pull request template ta puron korben.

### Dead link thik korben kivabe

Link ta sotti dead kina age check korben. Notun jaygay move korle link update korben. API bondho hoye gele ba free tier na thakle row ta `README.md` ar `apis.json`, duita thekei soraben, ar pull request e karon likhben.

Dhonnobad.
