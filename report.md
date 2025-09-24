# 📺 M3U Stream Status Report

**Generated on:** 2025-09-24 18:36:58 UTC
**GitHub Actions Runner Location:** GitHub's infrastructure (global)

## 📊 Summary

| Metric | Count | Percentage |
|--------|-------|------------|
| **Total Streams** | 1231 | 100% |
| **✅ Working Streams** | 1216 | 98.8% |
| **❌ Failed Streams** | 15 | 1.2% |

## 📁 Files Processed

- `vod playlist.m3u`: 495 streams
- `channel playlist.m3u`: 736 streams

## 📋 Failure Analysis (15 total failures)

### 🚫 Access Denied (13 streams)
*Likely geo-blocked or requires authentication*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
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
| BLAZE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TG 4 | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TV WAREHOUSE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |

### ⏱️ Connection Timeouts (2 streams)
*Server too slow to respond or overloaded*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| TG 4+1 | UK | channel playlist.m3u | Connection timeout | N/A |
| TNT SPORTS 2 | UK | channel playlist.m3u | Connection timeout | N/A |


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
*Last updated: 2025-09-24 18:36:58 UTC*
*Report generated automatically by GitHub Actions*
