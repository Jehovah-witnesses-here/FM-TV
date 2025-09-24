# 📺 M3U Stream Status Report

**Generated on:** 2025-09-24 06:39:47 UTC
**GitHub Actions Runner Location:** GitHub's infrastructure (global)

## 📊 Summary

| Metric | Count | Percentage |
|--------|-------|------------|
| **Total Streams** | 1083 | 100% |
| **✅ Working Streams** | 1063 | 98.2% |
| **❌ Failed Streams** | 20 | 1.8% |

## 📁 Files Processed

- `vod playlist.m3u`: 495 streams
- `channel playlist.m3u`: 588 streams

## 📋 Failure Analysis (20 total failures)

### 🚫 Access Denied (12 streams)
*Likely geo-blocked or requires authentication*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| BLAZE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TV WAREHOUSE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TG 4 | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| ALARABIYA | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC 1 | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC 4 | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC 5 | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC BOLLYWOOD | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC DRAMA | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| MBC PERSIA | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| SPACETOON ARABIC | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| WANASAH | AE | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |

### ⏱️ Connection Timeouts (1 streams)
*Server too slow to respond or overloaded*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| TG 4+1 | UK | channel playlist.m3u | Connection timeout | N/A |

### ❓ Not Found (404) (6 streams)
*Stream URL no longer exists*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| FS2 | US | channel playlist.m3u | Stream not found | 404 |
| FOX NEWS CHANNEL | US | channel playlist.m3u | Stream not found | 404 |
| HBO SIGNATURE | US | channel playlist.m3u | Stream not found | 404 |
| NICK JR. | US | channel playlist.m3u | Stream not found | 404 |
| MTV LIVE | US | channel playlist.m3u | Stream not found | 404 |
| CANAL 4 SAN JUAN | AR | channel playlist.m3u | Stream not found | 404 |

### 🔗 Connection Errors (1 streams)
*Network connectivity issues*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| CTV | CA | channel playlist.m3u | Connection error | N/A |


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
*Last updated: 2025-09-24 06:39:47 UTC*
*Report generated automatically by GitHub Actions*
