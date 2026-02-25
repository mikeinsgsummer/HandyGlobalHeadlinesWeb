# Handy Global Headlines

**Latest Version:** v2.5 (2026-02-25)

## Recent Changes
- **Ultimate Resilience:** Added sequential fallback to fetching engine (automatically tries proxies one-by-one if racing fails).
- **Safe Storage:** Implemented `safeParse` to prevent app-wide crashes from corrupted `localStorage` data.
- **Robust Polyfills:** Enhanced legacy browser support with bulletproof polyfills for `flatMap`, `flat`, `Promise.any`, and `AggregateError`.
- **Hybrid Fetching:** Added AllOrigins JSON fallback for higher CORS compatibility on restricted networks.
- **Smart Error UI:** Enhanced diagnostics with stack trace capture and a "Restart App" option.
- **Fixed:** Critical interest filtering logic bug that caused app crashes.