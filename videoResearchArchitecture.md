20170802

Video information source research is currently an ad hoc system with the following limitations:
* "System" exists entirely within Richard Wheeler's user account stack
* "System" is limited to YouTube
* "System" is undocumented

System workflow:
1. In YouTube (https://www.youtube.com/), User \[currently rruuww\] initiates search using keyword searches
2. When User discovers possible review candidates, User adds video to "research" playlist \[currently "research: surveillance"\]
3. Contents of "research" playlist (like all YouTube playlists) are automatically exposed as RSS feeds, although these feeds are not W3C compliant (https://validator.w3.org/feed/)
4. Using Feed43 (http://feed43.com/), the non-compliant "research" playlist RSS feed is converted into a compliant RSS feed
5. Using IFTTT (https://ifttt.com/), the compliant "research" playlist RSS feed monitored, and for each new item in the feed the following are created:
* An email alert \[currently to rruuww\]
* A new issue in GitHub in the repo https://github.com/ificouldseewhatyousee/ificouldsee/
6. User watches video and uses "Image and Video Processing instructions" (https://github.com/ificouldseewhatyousee/ificouldsee/wiki/Image-and-Video-Processing) to process video 
