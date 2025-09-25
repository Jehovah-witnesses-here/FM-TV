# 📺 M3U Stream Status Report

**Generated on:** 2025-09-25 12:57:42 UTC
**GitHub Actions Runner Location:** GitHub's infrastructure (global)

## 📊 Summary

| Metric | Count | Percentage |
|--------|-------|------------|
| **Total Streams** | 1301 | 100% |
| **✅ Working Streams** | 1269 | 97.5% |
| **❌ Failed Streams** | 32 | 2.5% |

## 📁 Files Processed

- `vod playlist.m3u`: 495 streams
- `channel playlist.m3u`: 806 streams

## 📋 Failure Analysis (32 total failures)

### 🚫 Access Denied (13 streams)
*Likely geo-blocked or requires authentication*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| BLAZE | UNITED KINGDOM | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TG 4 | UNITED KINGDOM | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TV WAREHOUSE | UNITED KINGDOM | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| AL MASHHAD | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| ALARABIYA | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC 1 | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC 4 | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC 5 | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC BOLLYWOOD | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC DRAMA | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC PERSIA | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| SPACETOON ARABIC | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| WANASAH | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |

### ⏱️ Connection Timeouts (2 streams)
*Server too slow to respond or overloaded*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| TG 4+1 | UNITED KINGDOM | channel playlist.m3u | Connection timeout | N/A |
| CARTOON NETWORK | USA | channel playlist.m3u | Connection timeout | N/A |

### ❓ Not Found (404) (14 streams)
*Stream URL no longer exists*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| ITV 3 | UNITED KINGDOM | channel playlist.m3u | Stream not found | 404 |
| AXS TV | USA | channel playlist.m3u | Stream not found | 404 |
| CMT | USA | channel playlist.m3u | Stream not found | 404 |
| FOX SOUL | USA | channel playlist.m3u | Stream not found | 404 |
| FREE FORM | USA | channel playlist.m3u | Stream not found | 404 |
| FYI | USA | channel playlist.m3u | Stream not found | 404 |
| HALLMARK MOVIES & MYSTERY | USA | channel playlist.m3u | Stream not found | 404 |
| QVC | USA | channel playlist.m3u | Stream not found | 404 |
| SHOWTIME NEXT | USA | channel playlist.m3u | Stream not found | 404 |
| SMITHSONIAN CHANNEL | USA | channel playlist.m3u | Stream not found | 404 |
| SNY | USA | channel playlist.m3u | Stream not found | 404 |
| START TV | USA | channel playlist.m3u | Stream not found | 404 |
| STARZ ENCORE CLASSIC | USA | channel playlist.m3u | Stream not found | 404 |
| TENNIS CHANNEL | USA | channel playlist.m3u | Stream not found | 404 |

### 🌍 Other HTTP Errors (3 streams)
*Various HTTP status codes*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| AMERICAN HEROES CHANNEL (AHC) | USA | channel playlist.m3u | HTTP 410 | 410 |
| C SPAN 2 | USA | channel playlist.m3u | HTTP 410 | 410 |
| CRIME+INVESTIGATION | USA | channel playlist.m3u | HTTP 410 | 410 |


## 📈 Geographic Notes

- Tests run from **GitHub Actions infrastructure** (multiple global locations)
- "Access Denied" errors may indicate geo-restrictions
- Some streams may work from different geographic locations
- DNS errors suggest the streaming service may be down entirely
- Timeout errors often indicate server overload or slow response

## 📝 Technical Details

- **User-Agent:** Modern browser simulation for better compatibility
- **Timeout:** 15 seconds per stream
- **Method:** HEAD request first, then GET with stream verification
- **Retry Logic:** Single attempt per stream to avoid rate limiting
- **Headers:** Include Accept-Language and Referer for better success rates

---
*Last updated: 2025-09-25 12:57:42 UTC*
*Report generated automatically by GitHub Actions*
