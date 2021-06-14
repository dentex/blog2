# YouTube Downloader for Android
### an Android app to download YouTube videos (and extract/convert audio to mp3). 
#### Compatible with Android Lollipop (5.0 - API21) and up

This will be a stripped-down and lightweight version of the old blog.   
It will be used to provide the latest apk for the **YTD** app.

Get it here:

# [DOWNLOAD LATEST BUILD](/files/apk/dentex.youtube.downloader_v7.2.apk)

versionName: `7.2`

versionCode: `155`

SHA1 checksum: `11f3f4be16c8e7c710b6cb0a247af08a875382d8`

[End User License Agreement (EULA)](/docs/eula.html)

### Installation
- The app supports Android versions starting from Lollipop (5.0);
- Remember to enable **Unknown Sources** from your device's **Security** settings, to allow installations of non market apps (safely ignore the subsequent dialog). Please note: in newer versions of Android, this kind of permission is not system-wide, but has to be given to single apps;
- If the "install" button is not working, temporary disable apps as Halo, Screenfilter, Twilight, LastPass password manager or anything similar (apps that do "draw on other apps");
- To install the app, click on your notification bar message for the completed download (if using the system downloads app, otherwise this may vary: i.e. if you have a file manager installed, you can browse to your downloads folder and install YTD's apk directly, clicking on the apk file).

### Usage
- Search for video and music within the app itself, OR
- Select the "share" button in the YouTube App while watching a video (or share any YouTube plain text link via any App) and choose "YouTube downloader";
- You'll see all the video codecs and qualities available for the video you're on.
then:
- Press an item to download the video locally (on the device) or to send the download via SSH to a remote PC. Destination machine requirements: Bash and Wget (and FFmpeg for muxing 480p and 1080p videos). More SSH info available in the app's tutorials;
- Long-press an item and choose between copy to clipboard or share link as text. Note: such a link (differently from when you send it via SSH) can be only used from the same device where it has been created OR from the same LAN, if you share it to another PC;
- Use the Dashboard to interact with downloaded video (audio extraction/conversion/mux and file management);
- On Lollipop or above, you can copy/move/rename/delete files on external sdcard.

### Features
- Search for YouTube videos within the app;
- Download on your device;
- Remote download on another PC via SSH;
- Multi-threaded downloads: maximizes bandwidth available and minimizes YouTube's speed throttling;
- Support for almost any format/quality available from YouTube;
- Audio extraction to aac/ogg or conversion to mp3 (menu available via single-click on items in the Dashboard tab);
- Mp3's ID3 tags edit;
- Mux Audio-Only and Video-Only streams into a complete video (to enjoy HD resolutions available as separated streams only);
- File management (menu available via long-click on items in the Dashboard tab);
- Handle download link: copy and/or pass it to other apps;
- Video list filters by format, quality etc via (left) sliding menu;
- Many preferences to customize usage.

### Known issues
- Some very long running downloads may be forced to PAUSE state if the app is not kept to the front for a certain amount of time. In this cases a manual resume is needed;
- On KitKat and above, is possible to use the external (removable) sdcard as download destination folder, but that's one caveat: only the app's private folder will be available. IMPORTANT note: this folder will be deleted by the system (together with all your downloads) if you uninstall the app. For the moment it's not possible to choose a different directory on the external/removable sdcard;
- The stream traditionally used by the app for the video preview if often missing nowadays, so a low resolution video-only stream is being used in such cases;
- age-restricted videos requiring log-in might not work.

### Anti-features

Are not supported for download all videos that:

- implement encrypted streams (some complete movies);
- are not available in your country;
- are live events.

### Support
- email (guess it);
- [xda-developers forum](https://forum.xda-developers.com/t/app-free-android-5-0-youtube-downloader-v7-0.2335450/).

### Credits

For the translators list, see [HERE](/docs/translators.html).
    
    Credits for the custom download manager to Hiroshi Matsunaga (matsuhiro): 
    https://github.com/matsuhiro/AndroidDownloadManger (released "unlicensed"). 
    
    The FFmpeg binary (http://www.ffmpeg.org/index.html), 
    used for the audio extraction feature, is released under the LGPL-3.0.
    (FFmpeg version 2.1.3 Copyright (c) 2000-2014 the FFmpeg developers)
    
    The Android-filechooser library is released under the MIT license.
    (Android-filechooser Copyright (c) 2012 Hai Bison)
    Updated version at https://code.google.com/p/an-huu/
    
    Launcher and notification icons by Sam Plane: 
    http://samplane123.deviantart.com/, released under the CC BY-NC-ND 
    (http://creativecommons.org/licenses/by-nc-nd/3.0)
    
    Search and results saving adapted from the project at 
    https://github.com/falikk/MediaSearch by Yaroslav Maslov
    (released "unlicensed").
    
    The SlidingMenu library is released under the Apache License:
    https://github.com/jfeinstein10/SlidingMenu
    (Copyright (c) 2012 Jeremy Feinstein)
    
    The liblame library, used to compile FFmpeg, is released under the LGPL.
    A GitHub project, https://github.com/intervigilium/liblame, 
    has been used to compile the lame libraries for Android.
    (liblame Copyright (c) 2010 Ethan Chen)
    (LAME Copyright (c) 1999-2007 The LAME Project,
    Copyright (c) 1999-2001 Mark Taylor,
    Copyright (c) 1998 Micheal Cheng)
    (mpglib Copyright (c) 1995-1997 Michael Hipp)
    
    Audio tags editing library: Jaudiotagger by Paul Taylor, released under the LGPL.
    http://www.jthink.net/jaudiotagger/index.jsp 
    Copyright (c) 2004-2007 JThink Ltd
    
    Picasso: Image downloading and caching library;
    OkHttp: An HTTP and SPDY client for Android and Java applications;
    Okio: A modern I/O API for Java;
    Copyright 2013 Square, Inc. 
    https://square.github.io/picasso/
    https://github.com/square/okhttp/
    https://github.com/square/okio/
    
    Crouton library: Copyright (c) 2012-2013 Benjamin Weiss and 
    Copyright (c) 2012 Neofonie Mobile GmbH, as modified by Prashant Adesara 
    https://github.com/prashantadesara/CroutonExample 
    released under the Apache License
    
    Gold Medal icon by Andy, from http://psdblast.com/
    
    PagerSlidingTabStrip layout: https://github.com/astuetz/PagerSlidingTabStrip
    Copyright (c) 2013 Andreas Stuetz, released under the Apache License.
    
### Code excerpts Licenses
    
    Stack Overflow (http://stackoverflow.com): 
    a question and answer site for programmers where all the content is CC BY-SA 3.0 licensed 
    (see http://creativecommons.org/licenses/by-sa/3.0)
    
    Utils.getCpuInfo(): 
    http://www.roman10.net/how-to-get-cpu-information-on-android/
    by Liu Feipeng
    
    Utils.scanMedia(): 
    http://www.grokkingandroid.com/adding-files-to-androids-media-library-using-the-mediascanner/
    by Wolfram Rittmeyer
    
    DashboardAdapter.java and DashboardListItem.java: code adapted from 
    https://github.com/survivingwithandroid/Surviving-with-android/ 
    by Francesco Azzola (JFrankie)
    
    Rhino.jar: open-source implementation of JavaScript written entirely in Java; 
    https://developer.mozilla.org/en-US/docs/Rhino 
    license: http://www.mozilla.org/MPL/2.0/

    QueueThread.java reference: 
    http://mindtherobot.com/blog/159/android-guts-intro-to-loopers-and-handlers/
    by Ivan Memruk

    CustomAsyncTask.java "priority" patch by http://stackoverflow.com/users/3153792/corsair992
    
    SHA1 file checksum method: http://www.rgagnon.com/javadetails/java-0416.html
    CC BY-NC-SA 2.5 CA licensed (see http://creativecommons.org/licenses/by-nc-sa/2.5/ca/)

### Changelog

     v7.2 - Jun 14 2021
    -----------------------------------
    [x] also use the 1080p 60fps video-only stream for the mp4 1080p mux
    [x] fix for age restricted videos (7)

     v7.1 - Dec 16 2020
    -----------------------------------
    [x] fix for age restricted videos (6)

     v7.0 - Dec 05 2020
    -----------------------------------
    [x] fix formats parsing
    [x] new video search (but limited to 20 results)
    [x] revised themes
    [x] other minor fixes and clean-up

     v6.9 - Jul 28 2020
    -----------------------------------
    [x] encrypted signature patch (24)
    [x] fix dashboard media import for some devices
    [x] fix file send from dashboard

     v6.8.9 - Jun 30 2020
    -----------------------------------
    [x] fix title retrieving

     v6.8.8 - Jun 13 2020
    -----------------------------------
    [x] fix regression for mp3 encoding in queue

     v6.8.7 - Jun 09 2020
    -----------------------------------
    [x] support videos with only one stream available

     v6.8.6 - Jun 01 2020
    -----------------------------------
    [x] fix regression not showing some formats (thanks @Nikhowolf)

     v6.8.5 - May 31 2020
    -----------------------------------
    [x] fix regression for API below Lollipop

     v6.8.4 - May 29 2020
    -----------------------------------
    [x] encrypted signature patch (23)

     v6.8.3 - Apr 09 2020
    -----------------------------------
    [x] encrypted signature patch (22)
    [x] add support for two new formats

     v6.8.2 - Mar 20 2020
    -----------------------------------
    [x] remove Fabric/Crashlytics
    [x] permanently enable secondary streams
    [x] add support for a few new formats
    [x] fix for age restricted videos (5)
    [x] many updated translations (thanks guys @crowdin)

     v6.8.1 - Jan 24 2020
    -----------------------------------
    [x] encrypted signature patch (21)
    [x] small layout fix

     v6.8 - Dic 15 2019
    -----------------------------------
    [x] fix for age restricted videos (4)
    [x] amoled-black and terminal-green app themes
    [x] reverse default dashboard entries order (new on top)
    [x] completed translations for Kurdish, Thai, Chinese, etc. 
        (thanks Cibranî, starwalking2017, candysweetplayzmc 
        and all contributors @Crowdin)
    [x] support for vnd.youtube links
    [x] fix live events detection (thanks @openeco)

     v6.7.3 - Sep 14 2019
    -----------------------------------
    [x] fix language switching for all translations
    [x] added Swedish translation (thanks @Granberg)
    [x] translations clean-up

     v6.7.1 - Jun 21 2019
    -----------------------------------
    [x] encrypted signature patch (20)

     v6.7 - Jun 15 2019
    -----------------------------------
    [x] fix downloads for age restricted videos
    [x] encrypted signature patch (19)
    [x] add the "Music" standard download location
    [x] get rid of any reference to 3GP (removed from YouTube)
    [x] fix copy/move/import files for external sdcard in Pie
    [x] fix download on extSdCard in JellyBean (thanks @User_99)
    [x] do not trigger auto-extraction with opus (thanks @Philz7)
    [x] increase max downloads threads to 8

     v6.6.2 - Gen 19 2019
    -----------------------------------
    [x] encrypted signature patch (18)
    [x] some updated translations

     v6.6.1 - Dic 12 2018
    -----------------------------------
    [x] fix for encrypted signature handling
    [x] other minor changes

     v6.6 - Nov 28 2018
    -----------------------------------
    [x] improved encrypted signature handling
    [x] improved free storage space detection
    [x] fix downloads in Android Pie
    [x] revised update routines, including:
        - fix apk downloads below Lollipop
        - fix apk installations above Oreo
    [x] do not scan intermediate m4a files
    [x] fix duplicated mp3 image tags
    [x] add the 320k mp3 encoding option
    [x] fix notification settings in API above Marshmallow
    [x] updated translations (thanks guys @GetLocalization!)

     v6.5.1 - Nov 09 2018
    -----------------------------------
    [x] fix Settings crashing in android version below Lollipop
    [x] a few other updated translations

     v6.5 - Nov 08 2018
    -----------------------------------
    [x] encrypted signature patch (17)
    [x] fix copy/move/import files for external sdcard for API 26+
    [x] add private external sdcard dir for download
        (WARNING: this folder will be deleted upon app's uninstall)
    [x] do not send logcat if not on the latest version
    [x] some updated translations

     v6.3 - Sep 08 2018
    -----------------------------------
    [x] encrypted signature patch (16)

     v6.2 - Sep 04 2018
    -----------------------------------
    [x] fix for some random network errors
    [x] updated translations (thanks NightOwlEyes and protheusdk)

     v6.1 - May 03 2018
    -----------------------------------
    [x] fix https connections for API below Lollipop

     v6.0 - Apr 18 2018
    -----------------------------------
    [x] support for age restricted videos
    [x] support for HDR videos
    [x] get rid of underscores in filenames
    [x] don't show advertising links in search
    [x] fix notifications for android O+
    [x] adaptive icon for android O+
    [x] language change now works also for android N+
    [x] drop support for android ICS (API 14/15)
    [x] many translations updated (thanks XDA folks!)
    [x] Telegram channel link into Social menu
    [x] can change also album art when editing ID3 tags
    [x] various maintenance fixes
    [x] libraries updated

     v5.4.1 - Feb 22 2018
    -----------------------------------
    [x] properly remember dashboard sort preference
    [x] properly recognize downloads' sizes
    [x] fix for videos with only a single format available

     v5.3 - Feb 16 2018
    -----------------------------------
    [x] encrypted signature patch (15)
    [x] dashboard sorting dialog (into the sliding menu)
    [x] option to clear the search history
    [x] fix search button in soft-keyboard (Search Tab)
    [x] fix mp3 auto-extraction bug with opus files (thank DomsDoms @XDA)
    [x] cryptocurrencies donation menu

     v5.2.5 - Oct 19 2017
    -----------------------------------
    [x] fix crash after FFmpeg operations under Nougat

     v5.2.4 - Jul 21 2017
    -----------------------------------
    [x] maintenance release
    [x] fix for the FC opening the dashboard tab.

     v5.2.3 - Jul 13 2017
    -----------------------------------
    [x] fix FC when sharing a video from YouTube

     v5.2.2 - Jul 9 2017
    -----------------------------------
    [x] fix for the wrong "purchase required" warning
    [x] added Bitcoin donation option

     v5.2.1 - Feb 12 2017
    -----------------------------------
    [x] recognize more 5.1 m4a audio-only formats
    [x] permit mux with webm also for ogg-wrapped opus streams
    [x] various translations updated

     v5.2 - Feb 01 2017
    -----------------------------------
    [x] encrypted signature patch (14) (thanks mad_ady and nixxo)
    [x] wrap .opus audio files into .ogg container for better support (thanks Georgi P.)
    [x] small bug fix in dashboard json file
    [x] drop support for FLV videos, no more available

     v5.1.1 - Sep 24 2016
    -----------------------------------
    [x] fixed another bug on dashboard restore

     v5.1 - Sep 21 2016
    -----------------------------------
    [x] fixed dashboard restore bug (sizes showed as 0B)
    [x] fixed a few minor bugs


     v5.0 - Sep 18 2016
    -----------------------------------
    [x] multi-threaded downloads
    [x] redundant "clear Dashboard" button in action bar
    [x] fix some app's crashes in Android N
    [x] better preview thumbnail in Formats tab
    [x] fix for the "shared?ci=" link type
    [x] fix for the progress bar during FFmpeg operations
    [x] use correct file extension for opus formats
    [x] support for ogg 4.0 ch. and m4a 5.1 ch. new audio-only formats
    [x] do not block age-restricted videos anymore 
        (please note: only some of them will be available for download)
    [x] better Search tab's results sorting dialog
    [x] prevent app's log from becoming too big 

     v4.8.6 - Jan 28 2016
    -----------------------------------
    [x] fix for the custom download location file-chooser

     v4.8.5 - Jan 26 2016
    -----------------------------------
    [x] fix for moving files to extSdCard

     v4.8.4 - Jan 24 2016
    -----------------------------------
    [x] if device/ROM doesn't support direct writing to extSdCard, 
        disable custom download location
    [x] support for file copy/move/rename/delete on extSdCard (Lollipop and above)

     v4.8.3 - Dic 20 2015
    -----------------------------------
    [x] encrypted signature patch (13) (thanks gantt)
    [x] better error handling if signature detection fails

     v4.8.2 - Nov 22 2015
    -----------------------------------
    [x] support for 2160p/2304p MP4 VO streams
    [x] do again broken mp3 conversions using the pause/resume menu item (thanks William K.)
    [x] formats list bug fix for secondary streams (thanks dhuvy @XDA)

     v4.8.1 - Nov 10 2015
    -----------------------------------
    [x] encrypted signature patch (12) (thanks gantt)

     v4.8 - Nov 6 2015
    -----------------------------------
    [x] always use system file-chooser, on Lollipop or above, 
        with extSdCard not present or not (directly) writeable
    [x] fixed a bug introduced in previous version, 
        causing custom download folder to change into private app's data folder 

     v4.7 - Nov 1 2015
    -----------------------------------
    [x] new FFmpeg builds (from v2.8) extending support to 64bit CPUs
    [x] force FFmpeg's version check when the ROM has been updated
    [x] ask the permission to write on the sdcard (on M devices)
    [x] fixed file-chooser checkbox issue for multiple selection
    [x] option to use wi-fi connection only

     v4.6 - Sep 24 2015
    -----------------------------------
    [x] material design for android versions > Lollipop
    [x] remove option to embed video preview (now fullscreen only)
    [x] better detection of free space on memory storage for some devices
    [x] handle the MP4 720p downloads for some very long videos, 
        when file length can't be retrieved
    [x] add option for MP3 "download" quality
    [x] show correct file size for 480p and 1080p

     v4.5.1 - Jun 19 2015
    -----------------------------------
    [x] do not fail muxing when 1080p and 480p downloads coexist into the Dashboard
        (thanks scandiun @XDA)
    [x] do again broken mux operations using the pause/resume menu item
    [x] support JuiceSSH to send remote downloads
    [x] proper check to manually mux only .mp4 with .m4a and .webm with .ogg streams

     v4.5 - Jun 09 2015
    -----------------------------------
    [x] new and working integrated search (with filters menu)
    [x] Bengali (India), Bulgarian, Romanian and Serbian translations added (as WIP);
        many others updated
    [x] do not try to download purchasable videos
    [x] wrap extracted aac audio-only into an m4a container
    [x] many libraries updated (OkHttp added for networking)
    [x] better error handling during update check
    [x] showing time left for downloads based on network speed
    [x] asks to overwrite when downloading files already stored
    [x] many small bugs fixed (themes, languages selection, etc.)
    [x] added support for Opus audio-only formats and a few others

     v4.4.2 - Feb 15 2015
    -----------------------------------
    [x] fix downloads count in notification
    [x] many languages updated

     v4.4.1 - Jan 28 2015
    -----------------------------------
    [x] YouTube site change hotfix
    [x] FFmpeg binary update fix

     v4.4 - Jan 03 2015
    -----------------------------------
    [x] configurable downloads queue
    [x] option to invert dashboard's entries click menus
    [x] auto-resume downloads paused due to network failure
    [x] new FFmpeg build targeting non-NEON CPUs (i.e. Tegra devices)
    [x] option to send logcat to the developer via email
    [x] added Croatian, Indonesian (WIP) and Norwegian (WIP) translations
    [x] fixed dashboard rename with existing filename (thanks m0d)
    [x] back-button going through all tabs now as optional
    [x] new FFmpeg builds supporting Android L
    [x] keep screen on if something is "in progress"

     v4.3.3 - Nov 15 2014
    -----------------------------------
    [x] encrypted signature patch (11) (thanks gantt)
    [x] support for 60fps VO streams

     v4.3.2 - Jul 24 2014
    -----------------------------------
    [x] encrypted signature patch (10) (thanks gantt)

     v4.3.1 - Jul 16 2014
    -----------------------------------
    [x] encrypted signature patch (9)
    [x] setting to download beta updates

     v4.3 - Jun 20 2014
    -----------------------------------
    [x] encrypted signature patch (8) (thanks gantt @userscripts.org)
    [x] search results sorting dialog (into the sliding menu)
    [x] search field history suggestions
    [x] new progress bars
    [x] better light theme
    [x] app reload upon language or theme change fix
    [x] file-chooser theme fix
    [x] send via SSH re-enabled for videos with encrypted signatures
    [x] support for 2160P and 1440p WebM VO streams
    [x] clear dashboard brute-force (delete also files paused/in progress)

     v4.2 - May 14 2014
    -----------------------------------
    [x] more downloads requiring mux now get actually queued
    [x] long running audio-extractions in background don't crash (may pause only) 
    [x] formats list reorganized and other optimizations
    [x] correct XDA thread link into About menu (thanks pandahunter)
    [x] Khmer translation (as WIP)

     v4.1.2 - May 04 2014
    -----------------------------------
    [x] update fix 
    [x] another tab selection fix

     v4.1.1 - May 03 2014
    -----------------------------------
    [x] correct width for search and Dashboard-filter text fields
    [x] correct tab selection when sharing links from other apps to YTD
    [x] many updated and completed translations:
        (Chinese, Czech, Dutch, German, Greek languages, Italian, 
         Portuguese-Brazil, Russian, Slovak, Vietnamese) (thanks guys!)

     v4.1 - Apr 29 2014
    -----------------------------------
    [x] light theme fixed / theme-chooser restored
    [x] default ID3 tags for direct-mp3 downloads (mrdoug's idea)
    [x] edit mp3's ID3 tags option into Dashboard

     v4.0 - Apr 27 2014
    -----------------------------------
    [x] new UI
    [x] integrated search
    [x] direct 1080p, 480p and mp3 downloads
    [x] grab direct-mp3's quality from the Auto-extract audio setting (dafnis' idea)
    [x] improved/fixed scraping
    [x] Thai and Japanese translation (as WIP)

     v3.7.2 - Mar 21 2014
    -----------------------------------
    [x] maintenance update

     v3.7.1 - Mar 06 2014
    -----------------------------------
    [x] small bug fix

     v3.7 - Mar 05 2014
    -----------------------------------
    [x] moved to new servers (with revised update process)
    [x] fixed a bug on removing audio or video files after extraction/conversion
    [x] new FFmpeg builds from latest v2.1.3
    [x] YouTube preview thumb as mp3 album art (Barry Williams' idea)
    
     v3.6.4 - Jan 27 2014 
    ----------------------------------- 
    [x] bug fix for Dashboard restore and file import 
     
     v3.6.3 - Jan 25 2014 
    ----------------------------------- 
    [x] bug fix 
     
     v3.6.2 - Jan 24 2014 
    ----------------------------------- 
    [x] support for "youtu.be" shortened links in stock browser 
    [x] no more GPL licensed 
     
     v3.6.1 - Jan 21 2014 
    ----------------------------------- 
    [x] bug fixes 
    [x] updated translations 
     
     v3.6 - Jan 15 2014 
    ----------------------------------- 
    [x] new FFmpeg builds from latest v2.1.1: 
     - new build for x86 CPU 
     - fix for many arm devices 
    [x] menu/preferences reorganization 
    [x] fix and improvements for encrypted signatures 
    [x] high quality AO streams hack (thanks gantt@userscripts.org) 
     
     v3.5.4 - Dic 17 2013 
    ----------------------------------- 
    [x] possibility to import into Dashboard multiple files at once 
    [x] Dashboard bottom status bar 
     
     v3.5.3 - Dic 12 2013 
    ----------------------------------- 
    [x] auto-update bug fix 
     
     v3.5.2 - Dic 11 2013 
    ----------------------------------- 
    [x] fixed missing progress bars during mux 
    [x] Dashboard backup file can be renamed 
    [x] indicator for Dashboard background jobs 
     
     v3.5.1 - Dic 09 2013 
    ----------------------------------- 
    [x] fixed two small bugs 
     
     v3.5 - Dic 09 2013 
    ----------------------------------- 
    [x] Dashboard option to mux video-only and audio-only streams 
    [x] new FFmpeg builds from latest v2.1 (with NEON support) available for download 
    [x] option to choose between Settings or Dashboard as app entry-point-activity 
    [x] "Send" option into Dashboard items long-click menu 
    [x] all "in-progress" operations visible from Dashboard 
    [x] fixed Dark and Light themes appearance 
    [x] Android 4.4 target and many other optimizations 
    [x] Czech translation 
     
     v3.4.1 - Nov 19 2013 
    ----------------------------------- 
    [x] encrypted signature patch (7) 
    [x] layout fix for Samsung GT-P5110 and GT-N8000 devices 
     
     v3.4 - Nov 18 2013 
    ----------------------------------- 
    [x] video list filters via sliding menu 
    [x] encrypted signature patch (6) 
    [x] option to clear Dashboard into its menu (with checkbox to delete also data) 
    [x] removed support for MP4 1080p and FLV 480p "hidden" streams (not working anymore) 
     
     v3.3.1 - Nov 06 2013 
    ----------------------------------- 
    [x] fix for storage free space check 
     
     v3.3 - Nov 04 2013 
    ----------------------------------- 
    [x] MP4 1080p and FLV 480p "hidden" streams support 
    [x] again, better support for "secondary" YouTube streams 
    [x] fixed important bugs on resumed downloads and storage free space 
        (thanks Christophelaures from XDA) 
     
     v3.2 - Oct 30 2013 
    ----------------------------------- 
    [x] better support for "secondary" YouTube streams 
    [x] support for audio files import into Dashboard 
    [x] other optimizations 
     
     v3.1 - Oct 26 2013 
    ----------------------------------- 
    [x] option to auto-enqueue FFmpeg tasks on downloads completion 
    [x] support for FLV video import into Dashboard 
    [x] support for video-only and audio-only "secondary" streams from YouTube
    [x] various bug fixes 
     
     v3.0.2 - Oct 11 2013 
    ----------------------------------- 
    [x] small fix 
     
     v3.0.1 - Oct 10 2013 
    ----------------------------------- 
    [x] layout fix for API 14,15,16 
    [x] other bug fixes 
     
     v3.0 - Oct 08 2013 
    ----------------------------------- 
    [x] Dashboard for interaction with downloaded video: 
     - show status/progress/speed 
     - click to: 
      ^ open video/audio file 
      ^ audio extraction/conversion 
     - long-click to manage files: 
      ^ copy 
      ^ move 
      ^ rename 
      ^ re-download 
      ^ remove 
      ^ delete 
      ^ pause/resume 
    [x] Custom download manager supporting: 
     - pause/resume 
     - YouTube link validation on resume through different networks and/or expire time 
    [x] new translations: 
     - Slovak 
     - Slovenian 
     - Vietnamese 
     - Finnish 
     
     v2.7 - Aug 20 2013 
    ----------------------------------- 
    [x] auto-patch experimental signature changes 
    [x] Android 4.3 target 
     
     v2.6.2 - Aug 08 2013 
    ----------------------------------- 
    [x] encrypted signature patch (5) 
     
     v2.6.1 - Jul 26 2013 
    ----------------------------------- 
    [x] option to show resolutions into the video list 
    [x] encrypted signature patch (4) 
     
     v2.6 - Jul 17 2013 
    ----------------------------------- 
    [x] fix for exp. signature parsing 
    [x] new translations: 
     - Arabic 
     - Danish 
     - Greek 
     
     v2.5.2 - Jul 14 2013 
    ----------------------------------- 
    [x] auto-fetch gantt's script to parse experimental signatures 
     
     v2.5.1 - Jul 12 2013 
    ----------------------------------- 
    [x] encrypted signature patch (3) 
     
     v2.5 - Jul 11 2013 
    ----------------------------------- 
    [x] encrypted signature patch (2) 
    [x] other small bugs fixed 
     
     v2.4 - Jul 02 2013 
    ----------------------------------- 
    [x] new launcher and notification icons by Sam Plane 
     
     v2.3.2 - Jun 28 2013 
    ----------------------------------- 
    [x] small bugs fixed 
     
     v2.3.1 - Jun 27 2013 
    ----------------------------------- 
    [x] encrypted signature patch 
     
     v2.3 - Jun 25 2013 
    ----------------------------------- 
    [x] encrypted signature support (thanks gantt@userscripts.org) 
    [x] other bug/stability fixes 
     
     v2.2 - May 12 2013 
    ----------------------------------- 
    [x] fixed a bunch of BUUUUUGS !!! 
    [x] handles direct link clicks 
     
     v2.1 - May 11 2013 
    ----------------------------------- 
    [x] code optimizations 
    [x] mediaScanner bug fix (thanks Wolfram!) 
    [x] new translations: 
     - Chinese (China) 
     - Chinese (Hong Kong) 
     
     v2.0.6 - May 09 2013 
    ----------------------------------- 
    [x] dialog/toast when Downloads system app is not found 
    [x] Chinese (Taiwan) translation 
     
     v2.0.5 - May 09 2013 
    ----------------------------------- 
    [x] bug fix (FC when Downloads system app is not found)(3) 
     
     v2.0.4 - May 08 2013 
    ----------------------------------- 
    [x] bug fix (FC when Downloads system app is not found)(2) 
    [x] Hungarian translation 
     
     v2.0.3 - May 08 2013 
    ----------------------------------- 
    [x] bug fix (FC when Downloads system app is not found) 
     
     v2.0.2 - May 07 2013 
    ----------------------------------- 
    [x] bug fix 
     
     v2.0.1 - May 06 2013 
    ----------------------------------- 
    [x] bug fix 
     
     v2.0 - May 06 2013 
    ----------------------------------- 
    [x] audio extraction from downloaded video with optional conversion to mp3 (with FFmpeg) 
    [x] PayPal donation menu 
    [x] BugSense integration 
    [x] on the fly language switch 
    [x] fixed locale change to default 
    [x] 3 new option on SSH: 
     - use other ConnectBot forks 
     - use link inside same LAN 
     - SSH-send to long-press menu 
    [x] up-navigation for activities 
    [x] nice translators list 
    [x] new translations: 
     - German 
     - Hebrew 
     - Polish (Poland) 
     - Portuguese (Brazil) 
     - Russian 
     - Spanish 
     - Western Farsi (Iran) 
     
     v1.9 - Mar 23 2013 
    ----------------------------------- 
    [x] YT web page parsing improved 
    [x] fixed notification error when remove downloads not yet started 
    [x] 4K and 3D video support 
    [x] re-organized menus 
    [x] on the fly theme switch 
    [x] progress bar for video list 
    [x] option to enable logging 
    [x] Korean translation 
     
     v1.8.2 - Mar 15 2013 
    ----------------------------------- 
    [x] dark/light theme switcher 
    [x] option to show all the file sizes into the video list 
    [x] French translation 
     
     v1.8.1 - Mar 14 2013 
    ----------------------------------- 
    [x] notification bug fix 
     
     v1.8 - Mar 12 2013 
    ----------------------------------- 
    [x] extSdCard support 
    [x] long-press on video list item: menu to copy/share link 
    [x] auto update-check once a day 
    [x] new notification icon 
    [x] landscape orientation support 
    [x] YT video thumbnail preview 
    [x] entire row in v.list click-able 
    [x] Turkish translation 
    [x] Dutch translation 
     
     v1.7 - Mar 03 2012 
    ----------------------------------- 
    [x] translations: 
     - Italian 
     - Portuguese (Portugal) 
    [x] option to force the locale 
     
     v1.6 - Mar 01 2013 
    ----------------------------------- 
    [x] own YTD notification bar 
    [x] options for own and sys notification
    [x] added some credits 
     
     v1.5.2 - Feb 25 2013 
    ----------------------------------- 
    [x] better fix on bad video list 
    [x] remove stop download on click 
    [x] open DM on notification bar click (still not working in CM ROM) 
     
     v1.5.1 - Feb 24 2013 
    ----------------------------------- 
    [x] fixed crash if no net is available 
    [x] fixed crash on bad video list 
     
     v1.5 - Feb 22 2013 
    ----------------------------------- 
    [x] on-line update check 
    [x] option to fetch file-sizes 
    [x] stop download on click (maybe not working in CM 10.1) 
    [x] DownloadManager quick links 
    [x] settings and DM overflow menu 
    [x] reordered preferences 
    [x] small fixes 
     
     v1.4 - Jan 29 2013 
    ----------------------------------- 
    [x] licenses and code links 
    [x] Share this App option 
     
     v1.3.1 - Jan 19 2013 
    ----------------------------------- 
    [x] handle again http|https links (thanks Reiner!) 
     
     v1.3 - Jan 18 2013 
    ----------------------------------- 
    [x] share via mobile links support 
     
     v1.2 - Dec 25 2012 
    ----------------------------------- 
    [x] fix for YouTube web-page changes 
     
     v1.1.1 - Dec 16 2012 
    ----------------------------------- 
    [x] preferences fix 
     
     v1.1 - Dec 13 2012 
    ----------------------------------- 
    [x] all text strings exported 
    [x] preferences modification 
    [x] quick start tutorial 
     
     v1.0.1 - Dec 11 2012 
    ----------------------------------- 
    [x] bad typo fixed 
    [x] file-chooser new folder icons 
     
     v1.0 - Dec 11 2012 
    ----------------------------------- 
    [x] FIRST PUBLIC RELEASE 
    [x] send download via SSH 
    [x] SSH send how-to dialog 
    [x] standard download locations 
    [x] file-chooser for download destination
    [x] add quality suffix options 
    [x] file renaming options 
    -----------------------------------    

_Copyright (C) 2012-2020 Samuele Rini_
