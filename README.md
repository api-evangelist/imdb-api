# IMDb-API (imdb-api)

Community web service (operated under the **IMDb-API / TV-API** brand) for
receiving movie, TV series and cast information in JSON. Aggregates IMDb,
TheMovieDb, Wikipedia, Rotten Tomatoes, Metacritic, TheTVDB, FilmAffinity and
YouTube into a single REST API. Originally hosted at
[imdb-api.com](https://imdb-api.com/) and migrated to
[tv-api.com](https://tv-api.com/).

> **Not an official IMDb / Amazon product.** IMDb itself has no public REST API.
> This profile covers the community service maintained by the
> [IMDb-API](https://github.com/IMDb-API) GitHub user. Adjacent community options
> include [OMDb API](https://www.omdbapi.com/), [TMDB](https://www.themoviedb.org/),
> [imdbapi.dev](https://imdbapi.dev/), and the
> [IMDb API on Apify](https://apify.com/api/imdb-api).

**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** company
- **x-tier:** 2 (enriched with real OpenAPI + pricing)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Video

## API
- **IMDb-API** — [Documentation](https://tv-api.com/api) · [OpenAPI](openapi/imdb-api-openapi.yml)

### Endpoint Categories
- **Search** — Search, SearchMovie, SearchSeries, SearchName, SearchEpisode, SearchCompany, AdvancedSearch
- **Title** — Title, FullCast, Posters, Images, Trailer, YouTubeTrailer, Ratings, UserRatings, SeasonEpisodes
- **Name** — Name, NameAwards
- **Lists** — Top250Movies, Top250TVs, MostPopularMovies, MostPopularTVs, InTheaters, ComingSoon, BoxOffice, BoxOfficeAllTime, IMDbList
- **External** — Wikipedia, ExternalSites, Reviews, MetacriticReviews, FAQ, Company, Keyword
- **Tools** — Usage, ResizeImage, ResizePoster

## Artifacts

| Type | Path |
|---|---|
| OpenAPI | [openapi/imdb-api-openapi.yml](openapi/imdb-api-openapi.yml) |
| JSON Schema | [json-schema/](json-schema/) (Title, Rating, Name, SearchResult, Usage) |
| JSON Structure | [json-structure/](json-structure/) (Title, Rating, Name) |
| JSON-LD context | [json-ld/imdb-api-context.jsonld](json-ld/imdb-api-context.jsonld) |
| Examples | [examples/](examples/) (search, title, ratings, fullcast, top250movies, usage) |
| Spectral rules | [rules/imdb-api-rules.yml](rules/imdb-api-rules.yml) |
| Vocabulary | [vocabulary/imdb-api-vocabulary.yml](vocabulary/imdb-api-vocabulary.yml) |
| Naftiko capabilities | [capabilities/](capabilities/) — title-enrichment, trending-discovery, person-profile + shared bundle |
| Plans & pricing | [plans/imdb-api-plans-pricing.yml](plans/imdb-api-plans-pricing.yml) |
| Rate limits | [rate-limits/imdb-api-rate-limits.yml](rate-limits/imdb-api-rate-limits.yml) |
| FinOps | [finops/imdb-api-finops.yml](finops/imdb-api-finops.yml) |

## Pricing (summary)

| Plan | Price | Daily quota |
|---|---|---|
| Free | $0 | 100 req/day |
| Standard | from $11.24/mo | 5,000 req/day |
| Plus | from $22.49/mo | 10,000 req/day |
| Premium | from $44.97/mo | 30,000 – 999,999 req/day |

All paid plans use non-recurring monthly billing. 15% discount on cryptocurrency payment. Quota is observable via the `/API/Usage/{apiKey}` endpoint.

## SDK & Tools
- **IMDbApiLib** — C# / NuGet wrapper: <https://github.com/IMDb-API/IMDbApiLib>
- **IMDbApiClient** — Free Windows desktop client: <https://github.com/IMDb-API/IMDbApiClient>

No MCP servers or Claude Code skills are published by this provider as of the last enrichment pass.

## Tags
Video, Movies, TV, Entertainment, Metadata, Ratings, Public APIs

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## Maintainers
- **Kin Lane** — kin@apievangelist.com
