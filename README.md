# Anikurd Search - Kurdish Anime Finder

A professional anime discovery platform for Kurdish users. Search for anime, get metadata in Kurdish, and find verified sources from Kurdish anime providers.

## Features

- 🎯 **Anime Discovery**: Search and identify anime with accurate metadata
- 🇰🇺 **Kurdish First**: Full Kurdish Sorani interface with Kurdish genres and synopses
- 🔗 **Provider Integration**: Aggregates anime from multiple verified Kurdish providers
- ✅ **Real Sources Only**: No fake URLs or placeholder content - only verified external links
- 📱 **Responsive Design**: Works seamlessly on mobile, tablet, and desktop
- 🎬 **Cinema Design**: Modern black & white interface inspired by anime culture
- 🌐 **Multi-Provider**: Searches all enabled providers concurrently
- ⚡ **Fast Search**: Returns results even if some providers are offline

## Tech Stack

- **Frontend**: Next.js 15 + React 19 + TypeScript + Tailwind CSS
- **Database**: PostgreSQL + Prisma ORM
- **APIs**: AniList for anime metadata
- **Styling**: Black & white cinema design

## Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL 13+

### Installation

```bash
# Clone the repository
git clone https://github.com/anikurdsearch/Anikurd-search.git
cd Anikurd-search

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your database and API keys

# Set up database
npx prisma generate
npx prisma migrate dev

# Start development server
npm run dev
```

The application will be available at `http://localhost:3000`

## Providers

Supported anime providers:

- **KurdSubtitle**: https://kurdsubtitle.net
- **KurdSubtitle TV**: https://tv.kurdsubtitle.net
- **KurdPrime**: https://kurdprime.com
- **Beenar**: https://beenar.net
- **Beenama**: https://beenama.com
- **Awena Film**: https://awenafilm.com
- **ShaFilm**: https://shafilm.vip

---

Built with ❤️ for the Kurdish anime community
