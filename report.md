# 📺 M3U Stream Status Report

**Generated on:** 2025-09-22 00:49:53 UTC
**GitHub Actions Runner Location:** GitHub's infrastructure (global)

## 📊 Summary

| Metric | Count | Percentage |
|--------|-------|------------|
| **Total Streams** | 635 | 100% |
| **✅ Working Streams** | 633 | 99.7% |
| **❌ Failed Streams** | 2 | 0.3% |

## 📁 Files Processed

- `vod playlist.m3u`: 495 streams
- `channel playlist.m3u`: 140 streams

## 📋 Failure Analysis (2 total failures)

### 🚫 Access Denied (2 streams)
*Likely geo-blocked or requires authentication*

| Channel Name | Group | File | Error Details | Code |
|-------------|-------|------|---------------|------|
| BLAZE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |
| TV WAREHOUSE | UK | channel playlist.m3u | Access denied (possibly geo-blocked) | 403 |


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
*Last updated: 2025-09-22 00:49:53 UTC*
*Report generated automatically by GitHub Actions*
