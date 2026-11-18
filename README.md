# Bangladesh Free APIs

Free and legal APIs for Bangladeshi developers - weather, prayer times, cricket, football, currency, news, geography, education and more. No key needed for many, free tier for the rest.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![GitHub stars](https://img.shields.io/github/stars/istiakrahman15/bangladesh-free-apis)](https://github.com/istiakrahman15/bangladesh-free-apis/stargazers)

A curated list of free APIs that Bangladeshi developers actually need. Every entry is free to start, legal to use, and links to its official docs. No scraped APIs, no leaked keys, no paid only services.

**Why this list is different:** other lists mix free and paid APIs, or include private and unofficial APIs. This list is free only, legal only, and Bangladesh first. If an API has no free tier, it is not here.

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
- [How to use in 1 minute](#how-to-use-in-1-minute)
- [What is NOT in this list](#what-is-not-in-this-list)
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
| [DummyJSON](https://dummyjson.com/) | Fake REST API with products, users, posts, comments and todos (app prototyping) | No | Yes | Yes | Free |
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

## Contribute

This list grows when Bangladeshi developers add what they use. See [CONTRIBUTING.md](CONTRIBUTING.md) for the full guide.

- Star the repo, it helps other BD developers find it on GitHub search.
- Add 1 API: copy one table row, fill in the official link, auth, HTTPS, CORS and free tier. One API per pull request is best.
- Fix a dead link: if an API moved or shut down, open a pull request to fix or remove it.
- Open an issue: use the Add API template if you know an API but do not want to write the pull request yourself.

## Search keywords

bangladesh, bangla, free api, public api, bd developer, bangladeshi developers, dhaka weather, prayer time bangladesh, cricket api, football api, bdt currency, currency exchange, open data, bangladesh open data, developer tools, api list, awesome list, rest api, json api, free apis, divisions districts upazilas, bangladesh geography, islamic api, quran api, news api bangladesh, jobs api, education api

## License

MIT License. See [LICENSE](LICENSE) for details.

Built for Bangladeshi developers, by [Istiak Rahman](https://github.com/istiakrahman15).
