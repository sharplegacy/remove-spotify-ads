# remove-spotify-ads
No more stupid Ads @Spotify


# This method works as long you can access the device's hosts file.

1. Access the hosts file.

Windows = C:\Windows\System32\drivers\etc\hosts
Mac = /private/etc/hosts

2. Open hosts file as admin. If you can't open the hosts file as administrator on Windows, I recommend you use notepad++.
3. Copy the following addresses to your hosts file.

# Windows:
0.0.0.0 adclick.g.doublecklick.net
0.0.0.0 adeventtracker.spotify.com
0.0.0.0 ads-fa.spotify.com
0.0.0.0 analytics.spotify.com
0.0.0.0 audio2.spotify.com
0.0.0.0 b.scorecardresearch.com
0.0.0.0 bounceexchange.com
0.0.0.0 bs.serving-sys.com
0.0.0.0 content.bitsontherun.com
0.0.0.0 core.insightexpressai.com
0.0.0.0 crashdump.spotify.com
0.0.0.0 d2gi7ultltnc2u.cloudfront.net
0.0.0.0 d3rt1990lpmkn.cloudfront.net
0.0.0.0 desktop.spotify.com
0.0.0.0 doubleclick.net
0.0.0.0 ds.serving-sys.com
0.0.0.0 googleadservices.com
0.0.0.0 googleads.g.doubleclick.net
0.0.0.0 gtssl2-ocsp.geotrust.com
0.0.0.0 js.moatads.com
0.0.0.0 log.spotify.com
0.0.0.0 media-match.com
0.0.0.0 omaze.com
0.0.0.0 open.spotify.com
0.0.0.0 pagead46.l.doubleclick.net
0.0.0.0 pagead2.googlesyndication.com
0.0.0.0 partner.googleadservices.com
0.0.0.0 pubads.g.doubleclick.net
0.0.0.0 redirector.gvt1.com
0.0.0.0 s0.2mdn.net
0.0.0.0 securepubads.g.doubleclick.net
0.0.0.0 spclient.wg.spotify.com
0.0.0.0 tpc.googlesyndication.com
0.0.0.0 v.jwpcdn.com
0.0.0.0 video-ad-stats.googlesyndication.com
0.0.0.0 weblb-wg.gslb.spotify.com
0.0.0.0 www.googleadservices.com
0.0.0.0 www.googletagservices.com
0.0.0.0 www.omaze.com
0.0.0.0 pagead2.googlesyndication.com
0.0.0.0 tpc.googlesyndication.com
0.0.0.0 video-ad-stats.googlesyndication.com

=========================================================================

# Mac:
# As for Mac just change "0.0.0.0" to "127.0.0.1"

127.0.0.1 adclick.g.doublecklick.net
127.0.0.1 adeventtracker.spotify.com
127.0.0.1 ads-fa.spotify.com
127.0.0.1 analytics.spotify.com
127.0.0.1 audio2.spotify.com
127.0.0.1 b.scorecardresearch.com
127.0.0.1 bounceexchange.com
127.0.0.1 bs.serving-sys.com
127.0.0.1 content.bitsontherun.com
127.0.0.1 core.insightexpressai.com
127.0.0.1 crashdump.spotify.com
127.0.0.1 d2gi7ultltnc2u.cloudfront.net
127.0.0.1 d3rt1990lpmkn.cloudfront.net
127.0.0.1 desktop.spotify.com
127.0.0.1 doubleclick.net
127.0.0.1 ds.serving-sys.com
127.0.0.1 googleadservices.com
127.0.0.1 googleads.g.doubleclick.net
127.0.0.1 gtssl2-ocsp.geotrust.com
127.0.0.1 js.moatads.com
127.0.0.1 log.spotify.com
127.0.0.1 media-match.com
127.0.0.1 omaze.com
127.0.0.1 open.spotify.com
127.0.0.1 pagead46.l.doubleclick.net
127.0.0.1 pagead2.googlesyndication.com
127.0.0.1 partner.googleadservices.com
127.0.0.1 pubads.g.doubleclick.net
127.0.0.1 redirector.gvt1.com
127.0.0.1 s0.2mdn.net
127.0.0.1 securepubads.g.doubleclick.net
127.0.0.1 spclient.wg.spotify.com
127.0.0.1 tpc.googlesyndication.com
127.0.0.1 v.jwpcdn.com
127.0.0.1 video-ad-stats.googlesyndication.com
127.0.0.1 weblb-wg.gslb.spotify.com
127.0.0.1 www.googleadservices.com
127.0.0.1 www.googletagservices.com
127.0.0.1 www.omaze.com
127.0.0.1 pagead2.googlesyndication.com
127.0.0.1 tpc.googlesyndication.com

=========================================================================

4. Save it (Ctrl + S). Remember not to save it as ".txt",".ics", or other extension, it won't work.

Additional Step for Mac: Close spotify, right click it, select 'Open Package Contents', then navigate to 'Contents/Resources/Apps' and delete 'ad.spa'
