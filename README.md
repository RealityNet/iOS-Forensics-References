# iOS-Forensics-References

<p>Last update: September 6th 2022</p>
<p><h1>DATA Partition (/private/var)</p></h1>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"db" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/db/biome/</b>
<ul>
<li><b>iOS 16 - Now You 'C' It, Now You Don't -- Breaking Down The Biomes Part 1</b></li>
https://blog.d204n6.com/2022/09/ios-16-now-you-c-it-now-you-dont.html
<li><b>iOS 16 Breaking Down the Biomes Part 2 - AppInstalls, AppLaunch, & AppIntents</b></li>
https://blog.d204n6.com/2022/09/ios-16-breaking-down-biomes-part-2.html
<li><b>iOS 16 - Breaking Down the Biomes (Part 3) - Keeping up with CarPlay</b></li>
https://blog.d204n6.com/2022/09/ios-16-breaking-down-biomes-part-3.html
<li><b>iOS 16 - Breaking Down the Biomes (Part 4) - Surfin' with Safari</b></li>
https://blog.d204n6.com/2022/09/ios-16-breaking-down-biomes-part-4.html
<li><b>iOS 16 - Breaking Down the Biomes Part 5 -- "Hey Siri, find me some more data..."</b></li>
https://blog.d204n6.com/2022/09/ios-16-breaking-down-biomes-part-5-hey.html
<li><b>iLEAPP Biome Plugins</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeAppinstall.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeBacklight.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeBattperc.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeBluetooth.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeCarplayisconnected.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeDevplugin.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeHardware.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeInfocus.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeIntents.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeLocationactivity.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeNotes.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeNotificationsPub.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeNowplaying.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeSafari.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeSync.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeTextinputses.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeUseractmeta.py
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/biomeWifi.py
</ul>
</li>
<li>
<b>/db/dhcpclient/</b>
<ul>
<li><b>MAC Apt Networking Plugin</b></li>
https://github.com/ydkhatri/mac_apt/wiki/NETWORKING
<li><b>Cellebrite CTF 2020: Juan Mortyme</b></li>
https://ciofecaforensics.com/2020/10/30/cellebrite-ctf-juan/
<li><b>Apple TV Forensics 03: Analysis</b></li>
https://blog.elcomsoft.com/2019/09/apple-tv-forensics-03-analysis/
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/db/diagnostics/</b>
<ul>
<li><b>Apple Unified Logging and Activity Tracing formats</b></li>
https://github.com/libyal/dtformats/blob/main/documentation/Apple%20Unified%20Logging%20and%20Activity%20Tracing%20formats.asciidoc
<li><b>Browsing the unified log in difficult circumstances</b></li>
https://eclecticlight.co/2017/09/25/browsing-the-unified-log-in-difficult-circumstances/
<li><b>Reviewing macOS Unified Logs</b></li>
https://www.mandiant.com/resources/blog/reviewing-macos-unified-logs
<li><b>Finding Waldo: Leveraging the Apple Unified Log for Incident Response</b></li>
https://www.crowdstrike.com/blog/how-to-leverage-apple-unified-log-for-incident-response/
https://objectivebythesea.org/v3/talks/OBTS_v3_jMusunuri_eMartin.pdf
<li><b>Unified Log Reader</b></li>
https://github.com/ydkhatri/UnifiedLogReader
<li><b>Upgrade From NULL—Detecting iOS Wipe Artifacts</b></li>
https://dfir.pubpub.org/pub/6i7d593n/release/1
<li><b>Logs Unite! - Forensic Analysis of Apple Unified Logs</b></li>
https://github.com/mac4n6/Presentations/blob/master/Logs%20Unite!%20-%20Forensic%20Analysis%20of%20Apple%20Unified%20Logs/LogsUnite.pdf
<li><b>Introducing 'Analysis of Apple Unified Logs: Quarantine Edition' [Entry 0]</b></li>
https://www.mac4n6.com/blog/2020/4/19/introducing-analysis-of-apple-unified-logs-quarantine-edition-entry-0
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"installd" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/installd/Library/Logs/MobileInstallation/mobile_installation.log.*</b>
<ul>
<li><b>CyberDefenders - Jailbreak CTF</b></li>
https://www.netscylla.com/blog/2022/06/09/Cyberdefenders-Jailbreak-CTF.html
<li><b>iOS Mobile Installation Logs</b></li>
https://dfir.pubpub.org/pub/e5xlbw88/release/2
<li><b>iOS Mobile Installation Logs</b></li>
https://dfrws.org/wp-content/uploads/2019/10/2019_review-ios_mobile_installation_logs.pdf
<li><b>iOS Mobile Installation Logs Parser</b></li>
https://abrignoni.blogspot.com/2019/01/ios-mobile-installation-logs-parser.html
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iLEAPP Mobile Installation Log Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/mobileInstall.py
</ul>
</li>
<li>
<b>/installd/Library/Logs/MobileInstallation/LastBuildInfo.plist</b>
<ul>
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 21-5551</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Cellebrite CTF 2020: Ruth Langmore</b></li>
https://ciofecaforensics.com/2020/11/02/cellebrite-ctf-ruth/
<li><b>iLEAPP Last Build Info Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/lastBuild.py
</ul>
</li>
</ul>
</div>
