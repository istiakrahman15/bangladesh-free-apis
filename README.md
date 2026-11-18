# Bangladesh Free APIs

Free and legal APIs for Bangladeshi developers - weather, prayer times, cricket, football, currency, news, geography, education and more. No key needed for many, free tier for the rest.

[![License: MIT](https://img.shields.io/github/license/istiakrahman15/bangladesh-free-apis?style=flat-square&color=yellow)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/istiakrahman15/bangladesh-free-apis?style=flat-square&logo=github)](https://github.com/istiakrahman15/bangladesh-free-apis/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/istiakrahman15/bangladesh-free-apis?style=flat-square&logo=github)](https://github.com/istiakrahman15/bangladesh-free-apis/network/members)
[![APIs](https://img.shields.io/badge/APIs-104-blue?style=flat-square)](apis.json)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)
[![Last Commit](https://img.shields.io/github/last-commit/istiakrahman15/bangladesh-free-apis?style=flat-square)](https://github.com/istiakrahman15/bangladesh-free-apis/commits/main)
[![Support Me](https://img.shields.io/badge/Support-Me-FF6B35?style=flat-square&logo=heart&logoColor=white)](https://www.supportkori.com/istiakrahman15)

A curated list of free APIs that Bangladeshi developers actually need. Every entry is free to start, legal to use, and links to its official docs. No scraped APIs, no leaked keys, no paid only services.

**Why this list is different:** other lists mix free and paid APIs, or include private and unofficial APIs. This list is free only, legal only, and Bangladesh first. If an API has no free tier, it is not here.

> If this list saved you even one hour, please consider supporting it. This list is free for everyone, forever, and your support keeps it alive. See [Support this project](#support-this-project).

## Table of Contents

- [Bangladesh First](#1-bangladesh-first)
- [Weather](#2-weather)
- [Prayer Times and Islamic](#3-prayer-times-and-islamic)
- [Sports: Cricket and Football](#4-sports-cricket-and-football)
- [Currency and Finance](#5-currency-and-finance)
- [News](#6-news)
- [Geography and Countries](#7-geography-and-countries)
- [Learning and Books](#8-learning-and-books)
- [Development and Testing](#9-development-and-testing)
- [Images and Media](#10-images-and-media)
- [AI and Machine Learning](#11-ai-and-machine-learning)
- [Jobs and Education](#12-jobs-and-education)
- [Authentication and Authorization](#13-authentication-and-authorization)
- [Email](#14-email)
- [File Storage and Sharing](#15-file-storage-and-sharing)
- [URL Shorteners and QR Codes](#16-url-shorteners-and-qr-codes)
- [IP, Geolocation and Time](#17-ip-geolocation-and-time)
- [Translation and Documents](#18-translation-and-documents)
- [Maps](#19-maps)
- [Anime, Games and Music](#20-anime-games-and-music)
- [Space, Science and Health](#21-space-science-and-health)
- [Blockchain and Package Registries](#22-blockchain-and-package-registries)
- [Search, Transport and Food](#23-search-transport-and-food)
- [Government Open Data and Entertainment](#24-government-open-data-and-entertainment)
- [How to use in 1 minute](#how-to-use-in-1-minute)
- [What is NOT in this list](#what-is-not-in-this-list)
- [Support this project](#support-this-project)
- [Contribute](#contribute)
- [Search keywords](#search-keywords)

**How to read the tables**

- **Auth:** `No` means no key needed. `apiKey` means a free key after signup. `OAuth` means OAuth login.
- **HTTPS:** `Yes` means the API works over HTTPS.
- **CORS:** `Yes` means you can call it from browser JavaScript. `Unknown` means it was not confirmed, so test it or call it from your server.
- **Free tier:** the free limit as published by the provider. Limits change, so always check the official docs before you ship.

## 1. Bangladesh First

Start here if you are building for Bangladesh. These APIs give you divisions, districts, upazilas, banks, universities, tax rules, dengue data, flood levels, power generation, and Bangladesh Bank rates.

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [BDAPIs](https://bdapis.com) | 8 divisions, 64 districts, upazilas, thanas and post codes, in English and Bangla (address dropdowns) | No | Yes | Unknown | Free, 100 requests per 15 minutes per IP |
| [Desh API](https://deshapi.riadul.com) | Geo, banks and branches, universities, income tax, gold price, Bangla tools, prayer times, metro and railway (one API for everyday Bangladesh data) | No | Yes | Unknown | Free, no signup, no key |
| [BD Open API](https://bdopenapi.vercel.app) | Divisions, districts, upazilas and unions, in English and Bangla (delivery and address forms) | No | Yes | Unknown | Free, no key, personal and commercial use |
| [data.gov.bd](https://www.data.gov.bd) | Bangladesh government open data portal, datasets on education, health, economy and more (open data apps) | No | Yes | Unknown | Free, open government data |
| [BD Open Data](https://www.bdopendata.com) | Bangladesh economic data from 29 sources, BBS, Bangladesh Bank, NBR and more, CC BY 4.0 (research and dashboards) | No | Yes | Unknown | Free, no registration, no key |
| [mcp-bangladesh](https://mcp.shohag.one) | 8 live government datasets in one free endpoint: DGHS dengue, river flood levels, BPDB power, district weather, AQI, Bangladesh Bank forex and inflation (AI apps and dashboards) | No | Yes | Unknown | Free, zero auth |
| [Bangladesh Bank and BBS data](https://www.data.gov.bd) | Bangladesh Bank forex rates and Bangladesh Bureau of Statistics data, published through the open data portal and BD Open Data, not as a separate key API (BDT rates and stats) | No | Yes | Unknown | Free, open data |

## 2. Weather

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Open-Meteo](https://open-meteo.com/en/docs) | Current weather and 16 day forecast by latitude and longitude, no key (Dhaka weather app) | No | Yes | Yes | Free for non-commercial use, 10,000 calls per day |
| [OpenWeatherMap](https://openweathermap.org/api) | Current weather, 5 day forecast and air quality worldwide (weather dashboard) | apiKey | Yes | Unknown | Free tier, 60 calls per minute |
| [wttr.in](https://wttr.in/:help) | Weather in your terminal and as JSON, no signup (quick weather check) | No | Yes | Yes | Free |
| [NASA POWER](https://power.larc.nasa.gov/docs/) | Global solar and weather data for energy and agriculture (solar and farming apps in Bangladesh) | No | Yes | Yes | Free |

## 3. Prayer Times and Islamic

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Aladhan](https://aladhan.com/prayer-times-api) | Prayer times by city or coordinates, Hijri calendar and Qibla, many calculation methods (Dhaka prayer time app) | No | Yes | Yes | Free |
| [islamic.app](https://api.islamic.app) | Prayer times, Quran verses with translations and tafsir, Qibla and Hijri dates, no auth (Islamic app) | No | Yes | Unknown | Free, 600 requests per minute per IP |
| [Quran Cloud](https://alquran.cloud/api) | Quran text, audio, translations and editions by ayah, surah or juz (Quran reader app) | No | Yes | Yes | Free |
| [Quran API](https://quran.api-docs.io/) | RESTful Quran API with multiple languages (Quran study app) | No | Yes | Yes | Free |
| [Quran-api](https://github.com/fawazahmed0/quran-api#readme) | Free Quran API with 90 plus languages and 400 plus translations (Bangla translation app) | No | Yes | Yes | Free |
| [Bayan](https://bayan.alwa7i.com/api) | Arabic Islamic encyclopedia: hadith with grades, Quran with tafsir and narrators (Islamic study app) | No | Yes | Yes | Free |

## 4. Sports: Cricket and Football

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [football-data.org](https://www.football-data.org) | Football fixtures, results, standings and scorers for 12 top competitions, including Premier League and Champions League (Messi and Barcelona scores) | apiKey | Yes | Unknown | Free, 10 requests per minute, delayed scores, current season only |
| [API-Football](https://www.api-football.com) | Football fixtures, live scores, leagues, standings, teams and players for 1,200 plus leagues (live score app) | apiKey | Yes | Unknown | Free, 100 requests per day, recent seasons only |
| [TheSportsDB](https://www.thesportsdb.com) | Crowdsourced sports database: teams, leagues, events and artwork, free v1 with public test key (sports app) | apiKey | Yes | Unknown | Free v1 with test key, 30 requests per minute, v2 is paid only |
| [CricAPI](https://www.cricapi.com) | Live cricket scores, fixtures, scorecards and player stats (Bangladesh cricket score app) | apiKey | Yes | Unknown | Free, 100 requests per day, fantasy endpoints are paid |

## 5. Currency and Finance

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Frankfurter](https://frankfurter.dev) | Exchange rates for 219 currencies from 112 central banks and official sources, daily reference rates (USD to BDT converter) | No | Yes | Unknown | Free, no quotas, abuse rate limiting only |
| [ExchangeRate-API](https://www.exchangerate-api.com) | Free currency conversion rates (BDT converter) | apiKey | Yes | Yes | Free tier after signup |
| [CoinGecko](https://www.coingecko.com/api) | Cryptocurrency prices, market data and developer data (crypto price tracker) | No | Yes | Yes | Free, 10 to 30 calls per minute |
| [World Bank](https://datahelpdesk.worldbank.org/knowledgebase/topics/125589) | World development indicators: GDP, population, health and education for 200 plus countries, including Bangladesh (economy dashboard) | No | Yes | No | Free, no key |
| [Monitly](https://monit.ly/api-docs) | Official statistics from Eurostat, World Bank, OECD, IMF and WHO for 150 plus countries (stats dashboard) | apiKey | Yes | Yes | Free tier after signup |
| [Statistics of the World](https://statisticsoftheworld.com/api-docs) | Economic data for 218 countries, GDP, population, inflation and 440 plus indicators from IMF and World Bank (country comparison) | No | Yes | Yes | Free |
| [Fixer](https://fixer.io) | Current and historical foreign exchange rates (forex rates app) | apiKey | Yes | Unknown | Free tier after signup, paid plans for more |

## 6. News

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [NewsAPI](https://newsapi.org/) | Headlines and articles from thousands of news sources and blogs (Bangladesh news app) | apiKey | Yes | Unknown | Free, 100 requests per day, developer use only |
| [GNews](https://gnews.io) | Real time news search and top headlines from 80,000 plus sources in 41 languages (news search) | apiKey | Yes | Unknown | Free, 100 requests per day, 12 hour delay, non-commercial only |
| [GDELT](https://www.gdeltproject.org) | Global news, events, language and tone database, document search with no auth (news trends and research) | No | Yes | Unknown | Free, no auth, 1 request per 5 seconds per IP |
| [Hacker News API](https://github.com/HackerNews/API) | Official Hacker News stories, comments and users via Firebase (tech news app) | No | Yes | Yes | Free, no key |
| [TheNews API](https://www.thenewsapi.com/) | Aggregated headlines, top stories and live news as JSON (news aggregator) | apiKey | Yes | Yes | Free tier after signup |
| [Spaceflight News](https://spaceflightnewsapi.net) | Spaceflight related news (space news app) | No | Yes | Yes | Free |

## 7. Geography and Countries

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [REST Countries](https://restcountries.com) | Country data: name, capital, population, currency, language, flag and more (country picker, Bangladesh info) | apiKey | Yes | Unknown | Free key, v5 needs a free API key, older no key versions are shut down |
| [Nager.Date](https://date.nager.at) | Public holidays for more than 90 countries, including Bangladesh (Bangladesh holiday calendar) | No | Yes | No | Free |
| [Nominatim](https://nominatim.openstreetmap.org) | OpenStreetMap geocoding: address to coordinates and back, 1 request per second, User-Agent required (map search) | No | Yes | No | Free, 1 request per second, no bulk geocoding |
| [Zippopotam.us](http://www.zippopotam.us) | Place info by postal code: country, city and state (postcode lookup) | No | No | Unknown | Free |
| [OpenStreetMap](http://wiki.openstreetmap.org/wiki/API) | Navigation, geolocation and geographical data from OpenStreetMap (map apps) | OAuth | No | Unknown | Free, editing API, read use should use Nominatim or Overpass |
| [Open-Meteo Geocoding](https://open-meteo.com/en/docs) | City name to latitude and longitude, no key (turn Dhaka into coordinates for weather) | No | Yes | Yes | Free for non-commercial use |

## 8. Learning and Books

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Open Library](https://openlibrary.org/developers/api) | Books, covers, authors and ISBN data from the Internet Archive (book search app) | No | Yes | No | Free |
| [Gutendex](https://gutendex.com/) | Project Gutenberg books catalogue, 70,000 plus free public domain books (free ebook app) | No | Yes | Unknown | Free |
| [Free Dictionary](https://dictionaryapi.dev/) | English definitions, phonetics, examples and synonyms (dictionary app) | No | Yes | Unknown | Free |
| [Wiktionary](https://en.wiktionary.org/w/api.php) | Collaborative dictionary data from Wiktionary (dictionary and language app) | No | Yes | Yes | Free |
| [Open Trivia](https://opentdb.com/api_config.php) | Trivia questions for quizzes and games (quiz app) | No | Yes | Unknown | Free |
| [SlashYear](https://slashyear.com/api) | Dated historical events as JSON, each quoted from a cited Wikipedia revision (history app) | No | Yes | Yes | Free |

## 9. Development and Testing

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [JSONPlaceholder](https://jsonplaceholder.typicode.com) | Fake REST API for testing and prototyping: posts, comments, todos and users (frontend practice) | No | Yes | Yes | Free |
| [GitHub REST API](https://docs.github.com/en/rest) | Repos, users, issues and commits, public data without auth (GitHub profile app) | No | Yes | Unknown | Free, 60 calls per hour without auth, more with auth |
| [Httpbin](https://httpbin.org/) | Simple HTTP request and response service for testing (API testing) | No | Yes | Yes | Free |
| [ReqRes](https://reqres.in/) | Hosted REST API ready to respond to AJAX requests (frontend testing) | No | Yes | Unknown | Free |
| [DummyJSON](https://dummyjson.com) | Fake REST API with products, users, posts, comments and todos (app prototyping) | No | Yes | Yes | Free |
| [APIs.guru](https://apis.guru/api-doc/) | Wikipedia for web APIs, OpenAPI specs for public APIs (find API specs) | No | Yes | Unknown | Free |
| [Cat Facts](https://catfact.ninja/) | Random cat facts as JSON (fun test data) | No | Yes | Yes | Free |

## 10. Images and Media

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Unsplash](https://unsplash.com/developers) | Free stock photography (website images) | OAuth | Yes | Unknown | Free tier after signup |
| [Pexels](https://www.pexels.com/api/) | Free stock photos and videos (website images and video) | apiKey | Yes | Yes | Free tier after signup |
| [NASA Open API](https://api.nasa.gov) | NASA data including imagery, astronomy picture of the day and more (space app) | apiKey | Yes | No | Free tier after signup, demo key available |
| [Lorem Picsum](https://picsum.photos/) | Placeholder images from Unsplash (design mockups) | No | Yes | Unknown | Free |
| [PokeAPI](https://pokeapi.co) | Pokemon species, moves and stats (fun game app) | No | Yes | Unknown | Free, fair use, cache responses |

## 11. AI and Machine Learning

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Hugging Face](https://huggingface.co) | AI model hub with inference API for text, vision and audio (AI features in your app) | apiKey | Yes | Yes | Free tier after signup |
| [Groq](https://console.groq.com) | Fast LLM inference with an OpenAI compatible API (chatbot and AI app) | apiKey | Yes | Unknown | Free plan, per model rate limits, no card to start |
| [OpenRouter](https://openrouter.ai/docs/quick-start) | Unified API for 300 plus LLMs, with a free tier for some models (try many AI models in one place) | apiKey | Yes | Yes | Free tier for free models |
| [Google Gemini](https://ai.google.dev/gemini-api/docs) | Multimodal generative AI for text, vision and code (AI app) | apiKey | Yes | Unknown | Free tier after signup |

## 12. Jobs and Education

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Universities List](https://github.com/Hipo/university-domains-list) | University names, countries and domains for 9,000 plus universities, including Bangladesh (university picker) | No | Yes | Unknown | Free |
| [The Muse](https://www.themuse.com/developers/api/v2) | Job board and company profiles (job search app) | apiKey | Yes | Unknown | Free tier after signup |
| [Arbeitnow](https://documenter.getpostman.com/view/18545278/UVJbJdKh) | Job board aggregator for Europe and remote jobs (remote job search) | No | Yes | Yes | Free |
| [Wikipedia](https://www.mediawiki.org/wiki/API:Main_page) | MediaWiki encyclopedia API, articles and search (learning app) | No | Yes | Unknown | Free |

## 13. Authentication and Authorization

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Supabase Auth](https://supabase.com/docs/guides/auth) | Email, social and phone login for your app, built on Postgres (login for SaaS and SMM panels) | apiKey | Yes | Unknown | Free: 50,000 monthly active users, 500 MB database, 1 GB storage |
| [Auth0](https://auth0.com) | Login, signup and social login with MFA and user management (auth for web apps) | OAuth | Yes | Unknown | Free: up to 25,000 monthly active users |
| [Clerk](https://clerk.com/pricing) | Drop in signup, login and user management with social login (auth for Next.js apps) | apiKey | Yes | Unknown | Free Hobby: 50,000 monthly retained users per app, no card |
| [Firebase Auth](https://firebase.google.com/pricing) | Google sign in, email and social login, part of Firebase (login for mobile and web apps) | apiKey | Yes | Unknown | Free Spark plan: 50,000 monthly active users for email, social and anonymous sign in |

## 14. Email

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Resend](https://resend.com/pricing) | Simple email API for transactional and marketing email (welcome and OTP emails) | apiKey | Yes | Unknown | Free: 3,000 emails per month, 100 per day, 3 domains |
| [Mailgun](https://www.mailgun.com/pricing/) | Email sending, tracking and validation API (order and notification emails) | apiKey | Yes | Unknown | Free: 100 emails per day, 1 sending domain |

## 15. File Storage and Sharing

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Cloudinary](https://cloudinary.com/pricing) | Image and video upload, storage, resize and delivery (product and profile images) | apiKey | Yes | Unknown | Free forever: 25 monthly credits, 1 credit is 1,000 transformations or 1 GB storage or 1 GB bandwidth |
| [Uploadcare](https://uploadcare.com/pricing/) | File upload widget and CDN with image processing (file upload forms) | apiKey | Yes | Unknown | Free: 1,000 operations per month, 5 GB traffic, 1 GB storage |

## 16. URL Shorteners and QR Codes

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [is.gd](https://is.gd/developers.php) | Free URL shortener API with statistics, no key (short links for posts) | No | Yes | Yes | Free, no key, 200 new links per hour and 4,800 per day per IP |
| [CleanURI](https://cleanuri.com/docs) | Free URL shortener API, no key (short links for sharing) | No | Yes | Unknown | Free, no key, fair use, about 2 requests per second per IP |
| [QR Server (goQR.me)](https://api.qrserver.com/v1/create-qr-code/) | Free QR code image API, no key, including commercial use (QR codes for payments and menus) | No | Yes | Yes | Free, no key, no published hard limit |

## 17. IP, Geolocation and Time

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [ip-api.com](http://ip-api.com/) | IP geolocation: country, city, timezone and ISP, no key (detect visitor location) | No | No | Yes | Free: 45 requests per minute, non-commercial only, HTTPS is paid only |
| [ipinfo.io](https://ipinfo.io/json) | IP address details: location, ASN and company, free token (visitor info) | apiKey | Yes | Yes | Free Lite: unlimited country and ASN lookups with a free token |
| [ipapi.co](https://ipapi.co/) | IP geolocation API with location and currency data (visitor country and currency) | No | Yes | Yes | Free trial: 1,000 requests per 24 hours, 30,000 per month |
| [TimezoneDB](https://timezonedb.com/api) | Timezone and time conversion by zone or coordinates (event times in Dhaka time) | apiKey | Yes | Unknown | Free for personal and non-commercial use, 1 request per second |

## 18. Translation and Documents

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [MyMemory](https://mymemory.translated.net/doc/) | Translation memory API for English, Bangla and many languages (translate app text) | No | Yes | Yes | Free anonymous: 5,000 characters per day, 50,000 per day with an email |
| [APITemplate.io](https://apitemplate.io/) | Generate PDF and image documents from templates with JSON data (invoices and certificates) | apiKey | Yes | Unknown | Free: 50 images or PDFs per month, 3 templates, no card |

## 19. Maps

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Mapbox](https://www.mapbox.com/pricing) | Maps, geocoding, directions and place search (map in your app) | apiKey | Yes | Unknown | Free: 50,000 web map loads per month, 100,000 geocoding and directions requests |
| [OpenRouteService](https://openrouteservice.org/) | Directions, routing, isochrones and geocoding on OpenStreetMap data (delivery routes) | apiKey | Yes | Yes | Free Standard plan: 2,000 directions requests per day, 40 per minute |
| [TomTom](https://developer.tomtom.com/pricing) | Maps, routing, traffic and search APIs (map and delivery apps) | apiKey | Yes | Unknown | Free Freemium: 50,000 tile requests plus 2,500 non-tile requests per day, no card |

## 20. Anime, Games and Music

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [AniList](https://docs.anilist.co/guide/graphql/) | Anime and manga data: titles, scores, schedules and lists, GraphQL (anime tracker app) | OAuth | Yes | Unknown | Free, public data needs no key, OAuth only for user lists |
| [RAWG](https://rawg.io/apidocs) | Video game database: games, genres, platforms and ratings (game discovery app) | apiKey | Yes | Unknown | Free tier after signup, 20,000 requests per month, non-commercial |
| [Chess.com](https://www.chess.com/news/view/published-data-api) | Chess player profiles, games, ratings and clubs, read only (chess stats app) | No | Yes | Unknown | Free, read only, no key |
| [FreeToGame](https://www.freetogame.com/api-doc) | Free to play games database with details and links (free games list) | No | Yes | Yes | Free, no key, under 10 requests per second |
| [MusicBrainz](https://musicbrainz.org/doc/Development/XML_Web_Service/Version_2) | Open music encyclopedia: artists, releases and recordings (music app) | No | Yes | Unknown | Free, no key, 1 request per second, User-Agent header required |
| [Deezer](https://developers.deezer.com/api) | Music catalog: tracks, albums, artists and playlists (music player app) | OAuth | Yes | Unknown | Free, public catalog reads need no key, OAuth only for user data |

## 21. Space, Science and Health

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Launch Library 2](https://ll.thespacedevs.com/2.3.0/) | Rocket launches, missions and spaceflight events (space launch tracker) | No | Yes | Unknown | Free, no key, 15 requests per hour |
| [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/fdsnws/event/1/) | Real time and historical earthquake data worldwide (earthquake alerts) | No | Yes | Unknown | Free, no key, 20,000 results per query maximum |
| [OpenFDA](https://open.fda.gov) | US FDA data on drugs, devices and food recalls (health research app) | apiKey | Yes | Unknown | Free, no key: 1,000 requests per day, free key: 120,000 per day |

## 22. Blockchain and Package Registries

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Etherscan](https://docs.etherscan.io/) | Ethereum blockchain data: balances, transactions and contracts (crypto wallet app) | apiKey | Yes | Yes | Free tier after signup, 3 calls per second, 100,000 calls per day |
| [CoinPaprika](https://docs.coinpaprika.com) | Cryptocurrency prices, market data and coin info, no key (crypto price app) | No | Yes | Unknown | Free, no key, 20,000 calls per month, personal use |
| [npm Registry API](https://registry.npmjs.org) | npm package metadata, versions and download info (package search tool) | No | Yes | Unknown | Free, no key for public package reads |
| [PyPI JSON API](https://pypi.org/pypi) | Python package metadata and release info (Python package tool) | No | Yes | Yes | Free, no key for public package reads |

## 23. Search, Transport and Food

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [OpenSky Network](https://opensky-network.org/apidoc/index.html) | Live flight tracking and flight data, non-commercial (flight tracker app) | OAuth | Yes | No | Free, non-commercial only, 400 credits per day anonymous, 4,000 registered |
| [TheMealDB](https://www.themealdb.com/api.php) | Meal recipes, ingredients and food categories (recipe app) | apiKey | Yes | Yes | Free test key 1 for development and education |
| [Open Food Facts](https://openfoodfacts.github.io/openfoodfacts-server/api/) | Open food product database with nutrition and ingredients (food scanner app) | No | Yes | Yes | Free, no key, 15 product reads per minute, 10 searches per minute per IP |

## 24. Government Open Data and Entertainment

| API | Description | Auth | HTTPS | CORS | Free tier |
| --- | --- | --- | --- | --- | --- |
| [Data.gov](https://api.data.gov/) | US government open data: datasets from many federal agencies (open data dashboards) | apiKey | Yes | Unknown | Free tier after signup, personal key: 1,000 requests per hour |
| [TVmaze](https://www.tvmaze.com/api) | TV show, episode and schedule data with images (TV tracker app) | No | Yes | Yes | Free, no key, 20 requests per 10 seconds per IP |

## How to use in 1 minute

### Dhaka weather with Open-Meteo, no key

Dhaka is at latitude 23.8103, longitude 90.4125.

```javascript
const res = await fetch(
  "https://api.open-meteo.com/v1/forecast?latitude=23.8103&longitude=90.4125&current=temperature_2m,relative_humidity_2m,wind_speed_10m&timezone=Asia%2FDhaka"
);
const data = await res.json();
console.log(data.current.temperature_2m, "C in Dhaka");
```

### Bangladesh divisions with BDAPIs, no key

```javascript
const res = await fetch("https://bdapis.com/api/v1.2/divisions");
const data = await res.json();
console.log(data.data.map((d) => d.division));
// Barishal, Chattogram, Dhaka, Khulna, Mymensingh, Rajshahi, Rangpur, Sylhet
```

Note: BDAPIs CORS support is not confirmed in every check. If the browser blocks the call, call it from your server or a small proxy instead.

## What is NOT in this list

- **bKash and Nagad:** there is no official public API for bKash or Nagad payments for developers to list here. Do not add an unofficial bKash or Nagad API. The Desh API entry above only lists MFS tariffs and USSD codes as public info, it is not a payment API.
- **Facebook, YouTube or other scraped APIs:** if it is not an official API, it is not here.
- **Paid only APIs:** if there is no free tier, it is not here.
- **Dead links:** if the official docs are gone, the entry should be removed.

## Support this project

Hi, I am Istiak Rahman, a 19 year old student and developer from Bangladesh. I built this list for you, and I keep it free for everyone.

I do not have a PC. I build everything on my Android phone, late at night after study, checking every API one by one so you do not have to waste your time or money on a paid only service. This list took many nights to make, and I will keep updating it, but I cannot do it alone.

If this list helped you build your app, finish your project, or learn something new, please support me. Even a small support means a lot to me. It helps me keep building free tools for Bangladeshi developers, and one day, buy a PC so I can build even better things for you.

**Support me here: [supportkori.com/istiakrahman15](https://www.supportkori.com/istiakrahman15)**

No money? No problem. You can still help me a lot, for free:

- Star this repo, it helps other BD developers find it on GitHub search.
- Share it with a friend who is learning to code.
- Add 1 API you use, so the next developer finds it here too.

Thank you for using this list, and thank you for believing in a developer from Bangladesh who is building with just a phone and a dream.

## Contribute

This list grows when Bangladeshi developers add what they use. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

- Star the repo, it helps other BD developers find it on GitHub search.
- Add 1 API: copy one table row, fill in the official link, auth, HTTPS, CORS and free tier. One API per pull request is best.
- Fix a dead link: if an API moved or shut down, open a pull request to fix or remove it.
- Open an issue: use the Add API template if you know an API but do not want to write the pull request yourself.

## Search keywords

bangladesh, bangla, free api, public api, bd developer, bangladeshi developers, dhaka weather, prayer time bangladesh, cricket api, football api, bdt currency, currency exchange, open data, bangladesh open data, developer tools, api list, awesome list, rest api, json api, free apis, divisions districts upazilas, bangladesh geography, islamic api, quran api, news api bangladesh, jobs api, education api, auth api, supabase auth, firebase auth, email api, resend, file storage api, cloudinary, url shortener, qr code api, ip api, timezone api, translation api, mapbox, openrouteservice, anime api, game api, music api, space api, earthquake api, etherscan, npm api, pypi api, flight tracker api, recipe api, open food facts, tv api

## License

MIT License. See [LICENSE](LICENSE) for details.

Built for Bangladeshi developers, by [Istiak Rahman](https://github.com/istiakrahman15).
