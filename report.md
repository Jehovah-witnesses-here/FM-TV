# 📺 M3U Stream Status Report

**Generated on:** 2025-09-25 22:30:32 UTC
**GitHub Actions Runner Location:** GitHub's infrastructure (global)

## 📊 Summary

| Metric | Count | Percentage |
|--------|-------|------------|
| **Total Streams** | 1236 | 100% |
| **✅ Working Streams** | 1189 | 96.2% |
| **❌ Failed Streams** | 47 | 3.8% |

## 📁 Files Processed

- `channel playlist.m3u`: 1236 streams

## 📋 Failure Analysis (47 total failures)

### 🚫 Access Denied (14 streams)
*Likely geo-blocked or requires authentication*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| BLAZE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TV WAREHOUSE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| INSIDE CRIME | UK FAST | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TG 4 | IE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
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

### ❓ Not Found (404) (32 streams)
*Stream URL no longer exists*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| AXS TV | USA | channel playlist.m3u | Stream not found | 404 |
| MLB 1 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| MLB 2 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| MLB 3 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 1 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 11 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 13 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 2 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 3 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 4 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NBA 9 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NFL 15 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 1 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 10 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 11 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 13 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 2 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 3 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 4 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 5 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 6 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 7 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 8 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| NHL 9 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| PPV 1 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| PPV 2 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| PPV 3 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| PPV 4 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| PPV 5 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| PPV 6 | USA EVENTS | channel playlist.m3u | Stream not found | 404 |
| CTB PERTH | AUS | channel playlist.m3u | Stream not found | 404 |
| CANAL 4 SAN JUAN | AR | channel playlist.m3u | Stream not found | 404 |

### 💥 Server Errors (5xx) (1 streams)
*Server-side issues*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| Fubo sports 1 | CA | channel playlist.m3u | Server error | 502 |


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
*Last updated: 2025-09-25 22:30:32 UTC*
*Report generated automatically by GitHub Actions*
