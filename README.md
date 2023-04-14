# iOS Forensics References

<p>Last update: April 14th 2023</p>
<p><h1>DATA Partition (/private/var)</p></h1>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/db/" folder</span></b></h2></p>
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
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/installd/" folder</span></b></h2></p>
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
c<ul>
<li>
<b>/mobile/Library/Accounts/Accounts3.sqlite</b>
<ul>
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 21-5551</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS - Tracking Device Migration</b></li>
https://blog.d204n6.com/2021/06/ios-tracking-device-migration.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>Cellebrite CTF 2022 - Beth's iPhone</b></li>
https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-beths-iphone.html
<li><b>Magnet Forensics Virtual Summit 2023 CTF – iOS</b></li>
https://www.forgottennook.com/blog/magnet-ios-2023
<li><b>iLEAPP Accounts Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/accs.py
<li><b>Accounts3.sqlite query</b></li>
https://github.com/kacos2000/Queries/blob/master/Accounts3_sqlite.sql
<li><b>Case Study: Forensic Analysis of TikTok on iOS</b></li>
https://dfir.pubpub.org/pub/h6vyh33u/release/1
</ul>
</li>
<li>
<b>/mobile/Library/AddressBook/AddressBook.sqlitedb</b>
<ul>
<li><b>Getting Started with iOS Forensics</b></li>
https://www.systoolsgroup.com/forensics/sqlite/ios.html
<li><b>Identification and analysis of email and contacts artefacts on iOS and OS X</b></li>
https://researchonline.gcu.ac.uk/ws/portalfiles/portal/24600592/K.Ovens_PID4325955.pdf
<li><b>TIME IS NOT ON OUR SIDE WHEN IT COMES TO MESSAGES IN IOS 11</b></li>
https://smarterforensics.com/2017/09/time-is-not-on-our-side-when-it-comes-to-messages-in-ios-11/
<li><b>How To Identify When an IPhone or iPad was Factory Reset</b></li>
https://athenaforensics.co.uk/how-to-identify-when-an-iphone-or-ipad-was-factory-reset/
<li><b>A Digital Forensic Analysis on the iCloud® and its Synchronization to Apple® Devices</b></li>
https://www.marshall.edu/forensics/files/FRIEDMANRACHEL-Research-Paper-08242012.pdf
<li><b>Upgrade From NULL—Detecting iOS Wipe Artifacts</b></li>
https://dfir.pubpub.org/pub/6i7d593n/release/1
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 21-5551</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>AddressBook.sqlitedb query</b></li>
https://github.com/kacos2000/Queries/blob/master/AddressBook_sqlite.sql
<li><b>iPhone Artifacts - Champlain College</b></li>
https://www.champlain.edu/Documents/LCDI/iPhone%20Artifacts.pdf
</ul>
</li>
<li>
<b>/mobile/Library/AddressBook/AddressBookImages.sqlitedb</b>
<ul>
<li><b>Identification and analysis of email and contacts artefacts on iOS and OS X</b></li>
https://researchonline.gcu.ac.uk/ws/portalfiles/portal/24600592/K.Ovens_PID4325955.pdf
<li><b>IOS 13 – SUMMARY FOR THOSE OF YOU WHO ENJOY THE CLIFFSNOTES</b></li>
https://smarterforensics.com/2019/09/ios-13-summary-for-those-of-you-who-enjoy-the-cliffsnotes/
<li><b>AddressBookImages.sqlitedb query</b></li>
https://github.com/kacos2000/Queries/blob/master/AddressBookImages_sqlite.sql
</ul>
</li>
<li>
<b>/mobile/Library/AggregatedDictionary/ADDataStore.sqlitedb</b>
<ul>
<li><b>Pincodes, Passcodes, & TouchID on iOS - An Introduction to the Aggregate Dictionary Database (ADDataStore.sqlite)</b></li>
https://www.mac4n6.com/blog/2017/3/12/introduction-to-the-aggregate-dictionary-database-addatastoresqlite
<li><b>On the Fifth Day of APOLLO, My True Love Gave to Me – A Stocking Full of Random Junk, Some of Which Might be Useful!</b></li>
https://www.mac4n6.com/blog/2018/12/18/on-the-fifth-day-of-apollo-my-true-love-gave-to-me-a-stocking-full-of-random-junk-some-of-which-might-be-useful
<li><b>APOLLO ADDataStore Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/aggregate_dictionary_scalars.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/aggregate_dictionary_distributed_keys.txt
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>Forensics Tools: Stop Miscalculating iOS Usage Analytics!</b></li>
https://www.zdziarski.com/blog/?p=2686
</ul>
</li>
<li>
<b>/mobile/Library/AppConduit/AvailableApps.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/AppConduit/AvailableCompanionApps.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/Application Support/com.apple.remotemanagmentd/RMAdminStore-Cloud.sqlite</b>
<br>
<b>/mobile/Library/Application Support/com.apple.remotemanagmentd/RMAdminStore-Local.sqlite</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>ScreenTimeController</b></li>
https://github.com/Evian-Zhang/ScreenTimeController/blob/master/README.md
<li><b>MAC Apt SceenTime Plugin</b></li>
https://github.com/ydkhatri/mac_apt/blob/master/plugins/screentime.py
<li><b>APOLLO ScreenTime Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/screentime_timed_items.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/screentime_counted_items.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/screentime_by_hour.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/screentime_by_category.txt
<li><b>Plaso iOS SceenTime Parser</b></li>
https://plaso.readthedocs.io/en/latest/_modules/plaso/parsers/sqlite_plugins/ios_screentime.html
<li><b>A Look Into Apple’s Screen Time Feature and What Insights It Lends To Forensics</b></li>
https://www.goldencelle.com/post/a-look-into-apple-s-screen-time-feature-and-what-insights-it-lends-to-forensics
<li><b>Cellebrite CTF 2020: Ruth Langmore</b></li>
https://ciofecaforensics.com/2020/11/02/cellebrite-ctf-ruth/
<li><b>Magnet Forensics Virtual Summit 2023 CTF – iOS</b></li>
https://www.forgottennook.com/blog/magnet-ios-2023
</ul>
</li>
<li>
<b>/mobile/Library/ApplicationSync/AssetSortOrder.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/BulletinBoard/ClearedSections.plist</b>
<ul>
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
</ul>
</li>
<li>
<b>/mobile/Library/Caches/com.apple.Pasteboard/*</b>
</li>
<li>
<b>/mobile/Library/Caches/com.apple.routined/Cache.sqlite</b>
<ul>
<li><b>Locations, Locations, Locations</b></li>
https://doubleblak.com/blogPosts.php?id=14
https://doubleblak.com/BlogArticles/14/PDF2.pdf
<li><b>On the Tenth Day of APOLLO, My True Love Gave to Me – An Oddly Detailed Map of My Recent Travels – iOS Location Analysis</b></li>
http://www.mac4n6.com/blog/2018/12/23/on-the-tenth-day-of-apollo-my-true-love-gave-to-me-an-oddly-detailed-map-of-my-recent-travels-ios-location-analysis
<li><b>APOLLO iOS Routined Cache Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cache_zrtcllocationmo.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cache_zrthintmo.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cache_zrvisitmo.txt
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>iOS Location Artifacts Explained</b></li>
https://cellebrite.com/en/ios-location-artifacts-explained/
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>iPhone Device Speeds via Cache.sqlite > ZRTCLLOCATIONMO table</b></li>
https://theforensicscooter.com/2021/09/22/iphone-device-speeds-in-cache-sqlite-zrtcllocationmo/
<li><b>Cache.sqlite query</b></li>
https://github.com/ScottKjr3347/iOS_Cache.sqlite_Queries
<li><b>Apple Probably Knows What You Did Last Summer</b></li>
https://blog.elcomsoft.com/2018/06/apple-probably-knows-what-you-did-last-summer/
<li><b>UAV Forensics: DJI Mini 2 Case Study</b></li>
https://www.researchgate.net/publication/352058134_UAV_Forensics_DJI_Mini_2_Case_Study
</ul>
</li>
<li>
<b>/mobile/Library/Caches/com.apple.routined/Cloud.sqlite</b>
<b>/mobile/Library/Caches/com.apple.routined/Cloud-V2.sqlite</b>
<ul>
<li><b>Locations, Locations, Locations</b></li>
https://doubleblak.com/blogPosts.php?id=14
https://doubleblak.com/BlogArticles/14/PDF2.pdf
<li><b>On the Tenth Day of APOLLO, My True Love Gave to Me – An Oddly Detailed Map of My Recent Travels – iOS Location Analysis</b></li>
http://www.mac4n6.com/blog/2018/12/23/on-the-tenth-day-of-apollo-my-true-love-gave-to-me-an-oddly-detailed-map-of-my-recent-travels-ios-location-analysis
<li><b>APOLLO iOS Routined Cloud Modules</b></li>  
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_visit_entry.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_visit_exit.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_visit_inbound_start.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_visit_inbound_stop.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_visit_outbound_start.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_visit_outbound_stop.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_address.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_cloud_mapitem.txt
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>iOS Location Artifacts Explained</b></li>
https://cellebrite.com/en/ios-location-artifacts-explained/
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
<li><b>Cellebrite CTF 2021 - Beth's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-beths-iphone.html
<li><b>Apple Probably Knows What You Did Last Summer</b></li>
https://blog.elcomsoft.com/2018/06/apple-probably-knows-what-you-did-last-summer/
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
</ul>
</li>
<li>
<b>/mobile/Library/Caches/com.apple.routined/Local.sqlite</b>
<ul>
<li><b>Locations, Locations, Locations</b></li>
https://doubleblak.com/blogPosts.php?id=14
https://doubleblak.com/BlogArticles/14/PDF2.pdf
<li><b>On the Tenth Day of APOLLO, My True Love Gave to Me – An Oddly Detailed Map of My Recent Travels – iOS Location Analysis</b></li>
http://www.mac4n6.com/blog/2018/12/23/on-the-tenth-day-of-apollo-my-true-love-gave-to-me-an-oddly-detailed-map-of-my-recent-travels-ios-location-analysis
<li><b>APOLLO iOS Routined Local Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_local_learned_location_of_interest_entry.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_local_learned_location_of_interest_exit.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_local_learned_location_of_interest_transition_start.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_local_learned_location_of_interest_transition_stop.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_local_vehicle_parked.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/routined_local_vehicle_parked_history.txt
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>iOS Location Artifacts Explained</b></li>
https://cellebrite.com/en/ios-location-artifacts-explained/
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
<li><b>Cellebrite CTF 2022 - Beth's iPhone</b></li>
https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-beths-iphone.html
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/addaily.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.accountsettings.plist</b>
<ul>
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.ActivitySharing.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.AdLib.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.aggregated.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.AppStore.plist</b>
<ul>
<li><b>Hacking and Securing iOS Applications by Jonathan Zdziarski, Chapter 4</b></li>
https://www.oreilly.com/library/view/hacking-and-securing/9781449325213/ch04.html
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.assistant.backedup.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
<li><b>Local Photo Library Photos.sqlite Query Documentation & Notable Artifacts</b></li>
https://theforensicscooter.com/2022/05/02/photos-sqlite-query-documentation-notable-artifacts/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.BatteryCenter.BatteryWidget.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.camera.plist</b>
<ul>
<li><b>Local Photo Library Photos.sqlite Query Documentation & Notable Artifacts</b></li>
https://theforensicscooter.com/2022/05/02/photos-sqlite-query-documentation-notable-artifacts/
<li><b>Do you have a Full-Sized Asset…or just a Thumbnail? Did Optimized iPhone Storage process occur?</b></li>
https://theforensicscooter.com/2022/12/05/do-you-have-a-full-sized-assetor-just-a-thumbnail-did-optimized-iphone-storage-process-occur/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.carplay.plist</b>
<ul>
<li><b>Ridin’ With Apple CarPlay</b></li>
https://thebinaryhick.blog/2019/05/08/ridin-with-apple-carplay/
<li><b>They See Us Rollin’; They Hatin’: Forensics of iOS CarPlay and Android Auto</b></li>
https://papers.put.as/papers/ios/2019/summit_archive_1564072550.pdf
<li><b>iOS 16 - Breaking Down the Biomes (Part 3) - Keeping up with CarPlay</b></li>
https://blog.d204n6.com/2022/09/ios-16-breaking-down-biomes-part-3.html
<li><b>Digital Forensic Case Studies for In-Vehicle Infotainment Systems Using Android Auto and Apple CarPlay</b></li>
https://www.mdpi.com/1424-8220/22/19/7196/pdf
<li><b>Cellebrite CTF 2021 Writeup</b></li>
https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708
<li><b>Cellebrite CTF 2021 - Marsha's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-marshas-iphone.html
<li><b>Auto-Parser: Android Auto and Apple CarPlay Forensics</b></li>
https://link.springer.com/chapter/10.1007/978-3-031-06365-7_4
https://github.com/BiTLab-BaggiliTruthLab/Auto-Parser-Android-Auto-Apple-CarPlay
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.celestial.plist</b>
<ul>
<li><b>Ridin’ With Apple CarPlay</b></li>
https://thebinaryhick.blog/2019/05/08/ridin-with-apple-carplay/
<li><b>Auto-Parser: Android Auto and Apple CarPlay Forensics</b></li>
https://link.springer.com/chapter/10.1007/978-3-031-06365-7_4
https://github.com/BiTLab-BaggiliTruthLab/Auto-Parser-Android-Auto-Apple-CarPlay
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.cloud.quota.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.cloudphotod.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.cmfsyncagent.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>The Meaning of Messages</b></li>
https://www.magnetforensics.com/blog/the-meaning-of-messages/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.commcenter.shared.plist</b>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.conference.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.contacts.donation-agent.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.contextstored.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.CoreDuet.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.CoreDuet.QueuedDenials.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.coreduetd.batterysaver.state.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.coreduetd.plist</b>
<ul>
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.corerecents.recentsd.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.corespotlightui.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.FeedbackAssistant.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.homesharing.plist</b>
<ul>
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.icloud.findmydeviced.FMIPAccounts.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.identityservices.idstatuscache.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Making the most of Property Lists</b></li>
https://forensicskween.com/research/making-the-most-of-property-lists/
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.imservice*.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.locationd.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Location Services and System Services are they ON or OFF</b></li>
https://dfir.pubpub.org/pub/4sv4kxyh/release/2
<li><b>iOS Location Services and System Services ON or OFF?</b></li>
https://theforensicscooter.com/2021/09/20/ios-location-services-and-system-services-on-or-off/
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.madrid.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>The Meaning of Messages</b></li>
https://www.magnetforensics.com/blog/the-meaning-of-messages/
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.mmcs.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.mobile.ldbackup.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Local Photo Library Photos.sqlite Query Documentation & Notable Artifacts</b></li>
https://theforensicscooter.com/2022/05/02/photos-sqlite-query-documentation-notable-artifacts/
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.mobilegestalt.plist</b>
<ul>
<li><b>WHO IS THE OWNER OF THE MOBILE DEVICE?</b></li>
https://www.digitalforensics.com/blog/articles/who-is-the-owner-of-the-mobile-device/
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.mobilephone.plist</b>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.mobileslideshow.plist</b>
<ul>
<li><b>How to find iOS Hidden Assets</b></li>
https://theforensicscooter.com/2022/07/29/how-to-find-ios-hidden-assets/
<li><b>Do you have a Full-Sized Asset…or just a Thumbnail? Did Optimized iPhone Storage process occur?</b></li>
https://theforensicscooter.com/2022/12/05/do-you-have-a-full-sized-assetor-just-a-thumbnail-did-optimized-iphone-storage-process-occur/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.MobileSMS.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
What is the likelihood of recovering deleted iPhone messages?
https://improsec.com/tech-blog/what-is-the-likelihood-of-recovering-deleted-iphone-messages
Missing Pieces: Tips and Tricks on how to ensure your acquisitions aren’t missing critical data
https://static1.squarespace.com/static/62ab5b933d903d4c55e5d716/t/62fa28d8fd3a89429f8a9a80/1660561630138/MissingPieces_Hyde_Quezada_Final.pdf
<li><b>The Meaning of Messages</b></li>
https://www.magnetforensics.com/blog/the-meaning-of-messages/
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.mt.lastLaunch.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.nano.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.nanoregistry.plist</b>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.preferences.datetime.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.preferences.network.plist</b>
<ul>
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>Wireless Network Preferences – iOS</b></li>
https://bitsplease4n6.wordpress.com/2020/12/17/wireless-network-preferences-ios/
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.Preferences.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.purplebuddy.plist</b>
<ul>
<li><b>iOS - Tracking Device Migration</b></li>
https://blog.d204n6.com/2021/06/ios-tracking-device-migration.html
<li><b>Putting a User Behind an iOS Device</b></li>
https://dfrws.org/wp-content/uploads/2020/06/2020_USA_pres-putting_a_user_behind_an_ios_device.pdf
<li><b>How was an iPhone set up?</b></li>
https://dfir.pubpub.org/pub/2q177smo/release/5
<li><b>Upgrade From NULL—Detecting iOS Wipe Artifacts</b></li>
https://dfir.pubpub.org/pub/6i7d593n/release/1
<li><b>How was an iPhone set up?</b></li>
https://smarterforensics.com/2019/01/how-was-an-iphone-setup/
<li><b>How To Identify When an IPhone or iPad was Factory Reset</b></li>
https://athenaforensics.co.uk/how-to-identify-when-an-iphone-or-ipad-was-factory-reset/
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Local Photo Library Photos.sqlite Query Documentation & Notable Artifacts</b></li>
https://theforensicscooter.com/2022/05/02/photos-sqlite-query-documentation-notable-artifacts/
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.sharingd.plist</b>
<ul>
<li><b>Analysis of Apple Unified Logs: Quarantine Edition [Entry 11] – AirDropping Some Knowledge</b></li>
http://www.mac4n6.com/blog/2020/6/5/analysis-of-apple-unified-logs-quarantine-edition-entry-11-airdropping-some-knowledge
<li><b>EXTRACTING FORENSIC ARTIFACTS FROM APPLE CONTINUITY</b></li>
https://smarterforensics.com/wp-content/uploads/2014/06/The-Cider-Press-DFIR_Summit2017.pdf
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.springboard.plist</b>
<ul>
<li><b>Recover your iPhone Screen Time or restrictions passcode (supports iOS 14)</b></li>
https://www.iphonebackupextractor.com/guides/recover-screen-time-parental-restrictions-passcode/
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>Auto-Parser: Android Auto and Apple CarPlay Forensics</b></li>
https://link.springer.com/chapter/10.1007/978-3-031-06365-7_4
https://github.com/BiTLab-BaggiliTruthLab/Auto-Parser-Android-Auto-Apple-CarPlay
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.timed.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/com.apple.weather.plist</b>
</li>
<li>
<b>/mobile/Library/Recents/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/Bookmarks.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/BrowserState.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/CloudTabs.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/History.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SMS/Attachments/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SMS/Drafts/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SMS/sms.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SMS/sms-temp.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/HomeBackground.cpbitmap</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/SpringBoard/HomeBackgroundThumbnail.jpg </b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/IconState.plist</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/LockBackgroundThumbnail.jpg</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/SpringBoard/LockBackgroundThumbnaildark.jpg</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/PushStore/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Suggestions/query_predictions.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/TCC/TCC.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/UserConfigurationProfiles/PublicEffectiveUserSettings.plist</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/UserConfigurationProfiles/UserSettings.plist</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/UserNotifications/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Voicemail/voicemail.db</b>
<ul>
<li><b>
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/installd/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>
</ul>
</li>
  
</ul>
</div>
