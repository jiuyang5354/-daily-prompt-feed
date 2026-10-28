[中文](README.md) | **English**

# Daily Prompt feed

Daily Prompt videos that pass validation are published here as releases named `dp-YYYY-MM-DD`. Each release contains `final.mp4`, `cover.jpg`, and `manifest.json`, for the Windows `dp-publisher` to download and publish to Douyin.

Only the most recent 14 editions are retained. The `drop` branch is force-replaced each day and contains only that day's files; pushing it triggers GitHub Actions to create the release.
