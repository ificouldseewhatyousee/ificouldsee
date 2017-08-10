20170810

Video information source research is currently an ad hoc system with the following limitations:
* "System" is limited to YouTube

System workflow:
1. In YouTube (https://www.youtube.com/), User initiates search using keyword searches
2. In YouTube, when User discovers possible review candidates, User adds video to "research" playlist \[any member of ificouldseewhatyoucouldsee YouTube user (https://www.youtube.com/channel/UCa4T96vEIH4dHy8mLoS20yw) playlist "research: new videos to review" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqfqWW5kF59v-otubvz_NLXo)\]
3. Contents of "research: new videos to review" playlist (like all YouTube playlists) are automatically exposed as RSS feeds, although these feeds are not W3C compliant (https://validator.w3.org/feed/)
4. Using Feed43 (http://feed43.com/), the non-compliant "research: new videos to review" playlist RSS feed is converted into a compliant RSS feed
5. Using IFTTT (https://ifttt.com/), the compliant "research: new videos to review" playlist RSS feed monitored, and for each new item in the feed the following are created:
* A new issue in GitHub in the repo https://github.com/ificouldseewhatyousee/ificouldsee/
6. In YouTube, User \[any member of ificouldseewhatyoucouldsee YouTube user (https://www.youtube.com/channel/UCa4T96vEIH4dHy8mLoS20yw) playlists "research: new videos to review" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqfqWW5kF59v-otubvz_NLXo), "research: videos to download" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqedOIiwptHY03ZCyLevSq4N), and "research: pass" (https://www.youtube.com/watch?v=f_JLCG5IKZg&list=PLpC3nKmQXcqfDfg0UT1qHg9gzm8OfPDKQ)\] watches videos in playlist "research: new videos to review" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqfqWW5kF59v-otubvz_NLXo) and triages to the appropriate playlist based on User's judgment of whether the video truly is relevant to the project.
7. In YouTube, User \[any user\] uses a browser plugin that enables video downloading—such as Video Downloadhelper for Firefox or Chrome (https://addons.mozilla.org/en-US/firefox/addon/video-downloadhelper/)—to download the video to their desktop.
8. In YouTube, User \[any member of ificouldseewhatyoucouldsee YouTube user (https://www.youtube.com/channel/UCa4T96vEIH4dHy8mLoS20yw) playlists "research: videos to download" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqedOIiwptHY03ZCyLevSq4N) and "research: downloaded videos to clip" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqeaKiE7_ozFWNWQF4CvdE8U)\] moves videos from "research: videos to download" to "research: downloaded videos to clip".
9. On desktop, User \[any user\] uses available video editing tools to clip videos for processing.
10. In YouTube, User \[any member of ificouldseewhatyoucouldsee YouTube user (https://www.youtube.com/channel/UCa4T96vEIH4dHy8mLoS20yw) playlists "research: downloaded videos to clip" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqeaKiE7_ozFWNWQF4CvdE8U) and "research: downloaded and clipped videos" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqc0kjOR5bxStUsab5uHb2iq)\] moves videos that have been clipped from "research: downloaded videos to clip" to "research: downloaded and clipped videos".
11. In YouTube, User \[any _owner_ of ificouldseewhatyoucouldsee YouTube user (https://www.youtube.com/channel/UCa4T96vEIH4dHy8mLoS20yw) playlist "research: clips to review" (https://www.youtube.com/playlist?list=PLpC3nKmQXcqd0KRgg1v9PWAaC-HqqBQWX)\] uploads clips to playlist.
12. In YouTube, User \[any user\] uses _If I Could See What You See_ "Processing: Image and Video Processing" instructions (https://github.com/ificouldseewhatyousee/ificouldsee/wiki/Processing:-Image-and-Video-Processing) to process video clips.
