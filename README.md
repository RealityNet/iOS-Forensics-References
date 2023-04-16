# iOS Forensics References

<p>Last update: April 14th 2023</p>
<p><h1>DATA Partition (/private/var)</p></h1>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/.fseventsd/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/.fseventsd</b>
<ul>
<li><b>Understanding MacOS File System Events with FSEventsParser</b></li>
http://www.osdfcon.org/presentations/2017/Ibrahim-Understanding-MacOS-File-Ststem-Events-with-FSEvents-Parser.pdf
<li><b>Mac OS X and iOS Forensics - Looking into the past with FSEvents</b></li>
https://papers.put.as/papers/macosx/2017/summit_archive_1498158287.pdf
<li><b>FSEvents Parser</b></li>
https://github.com/dlcowen/FSEventsParser
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/containers/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/containers/Shared/SystemGroup/"GUID"/Library/BatteryLife/CurrentPowerlog.PLSQL</b>
<ul>
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>On the Third Day of APOLLO, My True Love Gave to Me – Application Usage to Determine Who Has Been Naughty or Nice</b></li>
http://www.mac4n6.com/blog/2018/12/16/on-the-third-day-of-apollo-my-true-love-gave-to-me-application-usage-to-determine-who-has-been-naughty-or-nice
<li><b>On the Fourth Day of APOLLO, My True Love Gave to Me – Media Analysis to Prove You Listened to “All I Want for Christmas is You” Over and Over Since Before Thanksgiving</b></li>
http://www.mac4n6.com/blog/2018/12/17/on-the-fourth-day-of-apollo-my-true-love-gave-to-me-media-analysis-to-prove-you-listened-to-all-i-want-for-christmas-is-you-over-and-over-since-before-thanksgiving
<li><b>On the Sixth Day of APOLLO, My True Love Gave to Me – Blinky Things with Buttons – Device Status Analysis</b></li>
http://www.mac4n6.com/blog/2018/12/19/on-the-sixth-day-of-apollo-my-true-love-gave-to-me-blinky-things-with-buttons-device-status-analysis
<li><b>On the Seventh Day of APOLLO, My True Love Gave to Me – A Good Conversation – Analysis of Communications and Data Usage</b></li>
http://www.mac4n6.com/blog/2018/12/20/on-the-seventh-day-of-apollo-my-true-love-gave-to-me-a-good-conversation-analysis-of-communications-and-data-usage
<li><b>On the Eighth Day of APOLLO, My True Love Gave to Me – A Glorious Lightshow – Analysis of Device Connections</b></li>
http://www.mac4n6.com/blog/2018/12/21/on-the-eighth-day-of-apollo-my-true-love-gave-to-me-a-glorious-lightshow-analysis-of-device-connections
<li><b>On the Tenth Day of APOLLO, My True Love Gave to Me – An Oddly Detailed Map of My Recent Travels – iOS Location Analysis</b></li>
http://www.mac4n6.com/blog/2018/12/23/on-the-tenth-day-of-apollo-my-true-love-gave-to-me-an-oddly-detailed-map-of-my-recent-travels-ios-location-analysis
<li><b>APOLLO CurrentPowerLog Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_accessory_connection.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_airdrop.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_app_audio.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_app_deletion.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_app_info.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_app_nowplaying.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_app_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_app_usage_by_hour.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_assertion.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_audio_routing.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_awdl_states.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_backcamera_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_backlight_brightness.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_battery_level.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_battery_level_ui.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_bluetooth_device_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_button_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_camera_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_coalition_interval.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_device_lock_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_device_screen_autolock.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_device_telephony_activity.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_device_telephony_registration.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_device_volume.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_display.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_display_brightness.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_frontcamera_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_ids_messages.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_incallservice.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_kernel_task_monitor.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_lightning_connector_status.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_lightnining_connector_status.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_location_client_status.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_location_tech_status.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_mobilebackup.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_network_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_paired_device_config.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_power_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_powernap.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_process_data_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_process_id.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_process_monitor_dynamic.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_push_message_received.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_rapport_received_message.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_springboard_aggregate_bulletins.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_springboard_aggregate_notifications.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_timezone.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_torch_state.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_video.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_video_cmfile.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_video_cmhls.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_video_vtsession.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_wallet_card.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_wallet_transaction.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/powerlog_wifi_properties.txt
<li><b>Time Well Spent: Precision Timing, Monotonic Clocks, and the PowerLogs Database for iOS</b></li>
https://www.forensicfocus.com/webinars/time-well-spent-precision-timing-monotonic-clocks-and-the-powerlogs-database-for-ios/
<li><b>Oh no! I have a wiped iPhone, now what?</b></li>
https://blog.digital-forensics.it/2021/05/oh-no-i-have-wiped-iphone-now-what.html
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/containers/Shared/SystemGroup/"GUID"/Library/Database/com.apple.MobileBluetooth.ledevices.other.db</b>
<ul>
<li><b>Bluetooth – iOS</b></li>
https://bitsplease4n6.wordpress.com/2020/12/17/bluetooth-ios/
<li><b>How to Use iOS Bluetooth Connections to Solve Crimes Faster</b></li>
https://dfir.pubpub.org/pub/frknihlg/release/1
<li><b>How to Use iOS Bluetooth Connections to Solve Crimes Faster</b></li>
https://cellebrite.com/en/how-to-use-ios-bluetooth-connections-to-solve-crimes-faster/
<li><b>iLEAPP Bluetooth Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/bluetooth.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/containers/Shared/SystemGroup/"GUID"/Library/Database/com.apple.MobileBluetooth.ledevices.paired.db</b>
<ul>
<li><b>Bluetooth – iOS</b></li>
https://bitsplease4n6.wordpress.com/2020/12/17/bluetooth-ios/
<li><b>How to Use iOS Bluetooth Connections to Solve Crimes Faster</b></li>
https://dfir.pubpub.org/pub/frknihlg/release/1
<li><b>How to Use iOS Bluetooth Connections to Solve Crimes Faster</b></li>
https://cellebrite.com/en/how-to-use-ios-bluetooth-connections-to-solve-crimes-faster/
<li><b>iLEAPP Bluetooth Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/bluetooth.py
<li><b>EXTRACTING FORENSIC ARTIFACTS FROM APPLE CONTINUITY</b></li>
https://smarterforensics.com/wp-content/uploads/2014/06/The-Cider-Press-DFIR_Summit2017.pdf
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/containers/Shared/SystemGroup/"GUID"/Library/Preferences/com.apple.MobileBluetooth.devices.plist</b>
<ul>
<li><b>Bluetooth – iOS</b></li>
https://bitsplease4n6.wordpress.com/2020/12/17/bluetooth-ios/
<li><b>How to Use iOS Bluetooth Connections to Solve Crimes Faster</b></li>
https://dfir.pubpub.org/pub/frknihlg/release/1
<li><b>How to Use iOS Bluetooth Connections to Solve Crimes Faster</b></li>
https://cellebrite.com/en/how-to-use-ios-bluetooth-connections-to-solve-crimes-faster/
<li><b>Cellebrite CTF 2021 - Beth's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-beths-iphone.html
<li><b>Cellebrite CTF 2020: Juan Mortyme</b></li>
https://ciofecaforensics.com/2020/10/30/cellebrite-ctf-juan/
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>iLEAPP Bluetooth Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/bluetooth.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
</ul>
</div>
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
<b>/db/dhcpd_leases*</b>
<ul>
<li><b>iLEAPP DHCP Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/dhcphp.py
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
<li><b>iLEAPP DHCP Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/dhcpl.py
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
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
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
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/logs/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/logs/lockdownd.log</b>
<ul>
<li><b>So Long Lockdown!</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=9
<li><b>KnowledgeC (and Friends)</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=2
<li><b>Cellebrite CTF 2021 - Beth's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-beths-iphone.html
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/logs/usermanagerd.log.*</b>
</li>
<li>
<b>/logs/wifimanager.log</b>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/mobile/Containers/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/mobile/Containers/Data/Application/"Apple Safari GUID"/Library/Caches/com.apple.mobilesafari/Cache.db</b>
<ul>
<li><b>Getting Started with iOS Forensics</b></li>
https://www.systoolsgroup.com/forensics/sqlite/ios.html
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/<Apple Safari GUID>/Library/Caches/com.apple.WebAppCache/ApplicationCache.db</b>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/<Apple Safari GUID>/Library/Cookies/Cookies.binarycookies</b>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Safari GUID"/Library/ImageCache/Favicons/Favicon.db</b>
<ul>
<li><b>Favicons</b></li>
https://www.doubleblak.com/m/blogPosts.php?id=13
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Safari GUID"/Library/Preferences/com.apple.mobilesafari.plist</b>
<ul>
<li><b>iOS 14 - First Thoughts and Analysis</b></li>
https://blog.d204n6.com/2020/09/ios-14-first-thoughts-and-analysis.html
<li><b>iLEAPP Recent Web Searches Safari Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/safariRecentWebSearches.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Safari GUID"/Library/Safari/Downloads/Downloads.plist</b>
<ul>
<li><b>iOS / macOS - Tracking Downloads from Safari Without Downloads</b></li>
https://blog.d204n6.com/2021/05/ios-macos-tracking-downloads-from.html
<li><b>Safari and iPhone Internet History Parser</b></li>
http://az4n6.blogspot.com/2014/07/safari-and-iphone-internet-history.html
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Safari GUID"/Library/Safari/Thumbnails/</b>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Safari GUID"/Library/WebKit/WebsiteData/LocalStorage/</b>
<ul>
<li><b>Mobile Cyber Forensic Investigations of Web3 Wallets on Android and iOS</b></li>
https://www.mdpi.com/2076-3417/12/21/11180
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Maps GUID"/Library/Maps/GeoHistory.mapsdata</b>
<ul>
<li><b>Just Call Me Buffy the Proto Slayer – An Initial Look into Protobuf Data in Mac and iOS Forensics</b></li>
http://www.mac4n6.com/blog/2019/9/27/just-call-me-buffy-the-proto-slayer-an-initial-look-into-protobuf-data-in-mac-and-ios-forensics
<li><b>ROTTEN TO THE CORE? NAH, IOS14 IS MOSTLY SWEET</b></li>
https://smarterforensics.com/2020/09/rotten-to-the-core-nah-ios14-is-mostly-sweet/
<li><b>HOW THE GRINCH STOLE APPLE MAPS ARTIFACTS… OR DID HE JUST HIDE THEM?</b></li>
https://smarterforensics.com/2016/12/how-the-grinch-stole-apple-maps-artifacts-or-did-he-just-hide-them/
<li><b>FIRST THE GRINCH AND NOW THE EASTER BUNNY! WHERE IS APPLE MAPS HIDING?</b></li>
https://smarterforensics.com/2018/03/first-the-grinch-and-now-the-easter-bunny-where-is-apple-maps-hiding/
<li><b>…WON’T YOU BACK THAT THING UP: A GLIMPSE OF IOS 13 ARTIFACTS</b></li>
https://smarterforensics.com/2019/09/wont-you-back-that-thing-up-a-glimpse-of-ios-13-artifacts/
<li><b>Find Me If You Can: Mobile GPS Mapping Applications Forensic Analysis & SNAVP the Open Source, Modular, Extensible Parser Analysis & SNAVP the Open Source, Modular, Extensible Parser</b></li>
https://commons.erau.edu/cgi/viewcontent.cgi?article=1414&context=jdfsl
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Containers/Data/Application/"Apple Maps GUID"/Library/Preferences/com.apple.Maps.plist</b>
<ul>
<li><b>HOW THE GRINCH STOLE APPLE MAPS ARTIFACTS… OR DID HE JUST HIDE THEM?</b></li>
https://smarterforensics.com/2016/12/how-the-grinch-stole-apple-maps-artifacts-or-did-he-just-hide-them/
<li><b>FIRST THE GRINCH AND NOW THE EASTER BUNNY! WHERE IS APPLE MAPS HIDING?</b></li>
https://smarterforensics.com/2018/03/first-the-grinch-and-now-the-easter-bunny-where-is-apple-maps-hiding/
<li><b>…WON’T YOU BACK THAT THING UP: A GLIMPSE OF IOS 13 ARTIFACTS</b></li>
https://smarterforensics.com/2019/09/wont-you-back-that-thing-up-a-glimpse-of-ios-13-artifacts/
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
</ul>
</li>
<li>
<b>/mobile/Containers/Shared/AppGroup/"Apple Maps GUID"/Maps/MapsSync_0.0.1</b>
<ul>
<li><b>What Apple Maps Activity Can be Found Using a Logical Extraction</b></li>
https://lordtemplar1.wordpress.com/2022/05/08/what-apple-maps-activity-can-be-found-using-a-logical-extraction/
<li><b>iOS14 Maps History BLOB Script</b></li>
http://cheeky4n6monkey.blogspot.com/2020/11/ios14-maps-history-blob-script.html
https://github.com/cheeky4n6monkey/4n6-scripts/blob/master/iOS/ios14_maps_history.py
<li><b>ROTTEN TO THE CORE? NAH, IOS14 IS MOSTLY SWEET</b></li>
https://smarterforensics.com/2020/09/rotten-to-the-core-nah-ios14-is-mostly-sweet/
<li><b>iLEAPP Maps Sync Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/mapsSync.py
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/mobile/Library/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/mobile/Library/Accounts/Accounts3.sqlite</b>
<ul>
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
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
<li><b>Case Study: Forensic Analysis of TikTok on iOS</b></li>
https://dfir.pubpub.org/pub/h6vyh33u/release/1
<li><b>iLEAPP Accounts Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/accs.py
<li><b>Accounts3.sqlite query</b></li>
https://github.com/kacos2000/Queries/blob/master/Accounts3_sqlite.sql
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
<li><b>…WON’T YOU BACK THAT THING UP: A GLIMPSE OF IOS 13 ARTIFACTS</b></li>
https://smarterforensics.com/2019/09/wont-you-back-that-thing-up-a-glimpse-of-ios-13-artifacts/
<li><b>ROTTEN TO THE CORE? NAH, IOS14 IS MOSTLY SWEET</b></li>
https://smarterforensics.com/2020/09/rotten-to-the-core-nah-ios14-is-mostly-sweet/
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
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>AddressBook.sqlitedb query</b></li>
https://github.com/kacos2000/Queries/blob/master/AddressBook_sqlite.sql
<li><b>iPhone Artifacts - Champlain College</b></li>
https://www.champlain.edu/Documents/LCDI/iPhone%20Artifacts.pdf
<li><b>iLEAPP Address Book Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/addressBook.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
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
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
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
<li><b>Data Quality and Quantity – How to Get the Best of Both Worlds, Part 2 – Examining Screen Time Artifacts</b></li>
https://cellebrite.com/en/data-quality-and-quantity-how-to-get-the-best-of-both-worlds-part-2-examining-screen-time-artifacts/
<li><b>A Look Into Apple’s Screen Time Feature and What Insights It Lends To Digital Intelligence</b></li>
https://cellebrite.com/en/a-look-into-apples-screen-time-feature-and-what-insights-it-lends-to-digital-intelligence/
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
<b>/mobile/Library/Biome/</b>
<ul>
<li><b>Analyzing iOS Biome AppIntent Files</b></li>
https://bluecrewforensics.com/2022/03/07/ios-app-intents/
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
<li><b>An Alternate Location for Deleted SMS/iMessage Data in Apple Devices</b></li>
https://dfir.pubpub.org/pub/yp6efc8q/release/1
https://sqlmcgee.wordpress.com/2022/03/28/an-alternate-location-for-deleted-sms-imessage-data-in-apple-devices-2/
<li><b>Lagging for the Win: Querying for Negative Evidence in the sms.db</b></li>
https://belkasoft.com/lagging-for-win
<li><b>The Meaning of Messages</b></li>
https://www.magnetforensics.com/blog/the-meaning-of-messages/
<li><b>Magnet Forensics Virtual Summit 2023 CTF – iOS</b></li>
https://www.forgottennook.com/blog/magnet-ios-2023
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
/mobile/Library/Caches/com.apple.findmy.fmipcore/
<ul>
<li><b>Stored AirTag (and Other) Aritfacts</b></li>
https://blog.d204n6.com/2022/04/airtag-youre-it.html
<li><b>AirTags within iOS File Systems</b></li>
https://medium.com/@Appalachian4n6/airtags-within-ios-file-systems-279dc783b69f
<li><b>iLEAPP AirTags Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/airtags.py
</ul>
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
<li><b>Location Data on iOS and Android Devices</b></li>
https://cellebrite.com/en/episode-15-ibeg-to-dfir-location-data-on-ios-and-android-devices/
<li><b>Apple Probably Knows What You Did Last Summer</b></li>
https://blog.elcomsoft.com/2018/06/apple-probably-knows-what-you-did-last-summer/
<li><b>UAV Forensics: DJI Mini 2 Case Study</b></li>
https://www.researchgate.net/publication/352058134_UAV_Forensics_DJI_Mini_2_Case_Study
<li><b>Magnet User Summit 2022 CTF - iPhone</b></li>
https://www.stark4n6.com/2022/06/magnet-user-summit-2022-ctf-iphone.html
<li><b>Building a Pattern of Life - Leveraging Location and Health Data</b></li>
https://www.youtube.com/watch?v=eU7THDwFkiM
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>iPhone Device Speeds via Cache.sqlite > ZRTCLLOCATIONMO table</b></li>
https://theforensicscooter.com/2021/09/22/iphone-device-speeds-in-cache-sqlite-zrtcllocationmo/
<li><b>Vehicle and iPhone Speed Comparison</b></li>
https://theforensicscooter.com/2022/07/01/vehicle-and-iphone-speed-comparison/
<li><b>Cache.sqlite query</b></li>
https://github.com/ScottKjr3347/iOS_Cache.sqlite_Queries
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Caches/com.apple.routined/Cloud.sqlite</b>
<br>
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
<li><b>Location Data on iOS and Android Devices</b></li>
https://cellebrite.com/en/episode-15-ibeg-to-dfir-location-data-on-ios-and-android-devices/
<li><b>Cellebrite CTF 2021 - Beth's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-beths-iphone.html
<li><b>Apple Probably Knows What You Did Last Summer</b></li>
https://blog.elcomsoft.com/2018/06/apple-probably-knows-what-you-did-last-summer/
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
<li><b>Building a Pattern of Life - Leveraging Location and Health Data</b></li>
https://www.youtube.com/watch?v=eU7THDwFkiM
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
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
<li><b>Location Data on iOS and Android Devices</b></li>
https://cellebrite.com/en/episode-15-ibeg-to-dfir-location-data-on-ios-and-android-devices/
<li><b>Building a Pattern of Life - Leveraging Location and Health Data</b></li>
https://www.youtube.com/watch?v=eU7THDwFkiM
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>Cellebrite CTF 2022 - Beth's iPhone</b></li>
https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-beths-iphone.html
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Calendar/Calendar.sqlitedb</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>Magnet User Summit 2022 CTF - iPhone</b></li>
https://www.stark4n6.com/2022/06/magnet-user-summit-2022-ctf-iphone.html
<li><b>Calendar.sqlitedb query</b></li>
https://github.com/kacos2000/queries/blob/master/calendar_sqlitedb.sql
<li><b>iLEAPP Calendar Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/calendarAll.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/CallHistoryDB/CallHistory.storedata</b>
<ul>
<li><b>Missing SQLite Records Analysis</b></li>
https://dfir.pubpub.org/pub/33vkc2ul/release/1
<li><b>A GLIMPSE OF IOS 10 FROM A SMARTPHONE FORENSIC PERSPECTIVE</b></li>
https://smarterforensics.com/2016/09/a-glimpse-of-ios-10-from-a-smartphone-forensic-perspective/
<li><b>TIME IS NOT ON OUR SIDE WHEN IT COMES TO MESSAGES IN IOS 11</b></li>
https://smarterforensics.com/2017/09/time-is-not-on-our-side-when-it-comes-to-messages-in-ios-11/
<li><b>…WON’T YOU BACK THAT THING UP: A GLIMPSE OF IOS 13 ARTIFACTS</b></li>
https://smarterforensics.com/2019/09/wont-you-back-that-thing-up-a-glimpse-of-ios-13-artifacts/
<li><b>IOS 13 – SUMMARY FOR THOSE OF YOU WHO ENJOY THE CLIFFSNOTES</b></li>
https://smarterforensics.com/2019/09/ios-13-summary-for-those-of-you-who-enjoy-the-cliffsnotes/
<li><b>ROTTEN TO THE CORE? NAH, IOS14 IS MOSTLY SWEET</b></li>
https://smarterforensics.com/2020/09/rotten-to-the-core-nah-ios14-is-mostly-sweet/
<li><b>How To Identify When an IPhone or iPad was Factory Reset</b></li>
https://athenaforensics.co.uk/how-to-identify-when-an-iphone-or-ipad-was-factory-reset/
<li><b>iOS 14 - First Thoughts and Analysis</b></li>
https://blog.d204n6.com/2020/09/ios-14-first-thoughts-and-analysis.html
<li><b>Cellebrite CTF 2022 - Marsha's iPhone</b></li>
https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-marshas-iphone.html
<li><b>Mo’ SIMs, Mo’ Problems. Examining Phones with Dual SIMs.</b></li>
https://thebinaryhick.blog/2022/12/06/mo-sims-mo-problems-examining-phones-with-dual-sims/
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>CallHistory Query</b></li>
https://github.com/kacos2000/queries/blob/master/callhistory_storedata.sql
<li><b>APOLLO CallHistory Module</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/call_history.txt 
<li><b>iLEAPP CallHistory Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/callHistory.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/CallHistoryDB/CallHistoryTemp.storedata</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>…WON’T YOU BACK THAT THING UP: A GLIMPSE OF IOS 13 ARTIFACTS</b></li>
https://smarterforensics.com/2019/09/wont-you-back-that-thing-up-a-glimpse-of-ios-13-artifacts/
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/CallHistoryTransactions/</b>
</li>
<li>
<b>/mobile/Library/com.apple.itunesstored/itunesstored2.sqlitedb</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
</ul>
</li>
<li>
<b>/mobile/Library/com.apple.itunesstored/kvs.sqlitedb</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/mobile/Library/CoreDuet/Knowledge/knowledgeC.db</b>
<ul>
<li><b>Knowledge is Power! Using the macOS/iOS knowledgeC.db Database to Determine Precise User and Application Usage</b></li>
http://www.mac4n6.com/blog/2018/8/5/knowledge-is-power-using-the-knowledgecdb-database-on-macos-and-ios-to-determine-precise-user-and-application-usage
<li><b>Knowledge is Power II – A Day in the Life of My iPhone using knowledgeC.db</b></li>
https://www.mac4n6.com/blog/2018/9/12/knowledge-is-power-ii-a-day-in-the-life-of-my-iphone-using-knowledgecdb
<li><b>Extensive knowledgeC APOLLO Updates!</b></li>
https://www.mac4n6.com/blog/2020/6/17/extensive-knowledgec-apollo-updates
<li><b>Socially Distant but Still Interacting! New and Improved Updates to macOS/iOS CoreDuet interactionC.db APOLLO Modules</b></li>
https://www.mac4n6.com/blog/2020/6/21/socially-distant-but-still-interacting-new-and-improved-updates-to-macosios-coreduet-interactioncdb-apollo-modules
<li><b>Providing Context to iOS App Usage with knowledgeC.db and APOLLO</b></li>
https://www.mac4n6.com/blog/2020/1/13/apollo-into-the-details-with-application-activities
<li><b>On the Third Day of APOLLO, My True Love Gave to Me – Application Usage to Determine Who Has Been Naughty or Nice</b></li>
https://www.mac4n6.com/blog/2018/12/16/on-the-third-day-of-apollo-my-true-love-gave-to-me-application-usage-to-determine-who-has-been-naughty-or-nice
<li><b>On the Fourth Day of APOLLO, My True Love Gave to Me – Media Analysis to Prove You Listened to “All I Want for Christmas is You” Over and Over Since Before Thanksgiving</b></li>
https://www.mac4n6.com/blog/2018/12/17/on-the-fourth-day-of-apollo-my-true-love-gave-to-me-media-analysis-to-prove-you-listened-to-all-i-want-for-christmas-is-you-over-and-over-since-before-thanksgiving
<li><b>On the Sixth Day of APOLLO, My True Love Gave to Me – Blinky Things with Buttons – Device Status Analysis</b></li>
https://www.mac4n6.com/blog/2018/12/19/on-the-sixth-day-of-apollo-my-true-love-gave-to-me-blinky-things-with-buttons-device-status-analysis
<li><b>On the Eighth Day of APOLLO, My True Love Gave to Me – A Glorious Lightshow – Analysis of Device Connections</b></li>
http://www.mac4n6.com/blog/2018/12/21/on-the-eighth-day-of-apollo-my-true-love-gave-to-me-a-glorious-lightshow-analysis-of-device-connections
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
<li><b>Apple TV Forensics 03: Analysis</b></li>
https://blog.elcomsoft.com/2019/09/apple-tv-forensics-03-analysis/
<li><b>iOS KnowledgeC.db Notifications</b></li>
https://theforensicscooter.com/2021/10/03/ios-knowledgec-db-notifications/
<li><b>iOS KnowledgeC.db Notifications</b></li>
https://dfir.pubpub.org/pub/g2v1z97i/release/1
<li><b>KnowledgeC: Now Playing entries</b></li>
https://www.forensicmike1.com/2019/10/07/knowledgec-now-playing-entries/
<li><b>USING PHOTOS.SQLITE TO SHOW THE RELATIONSHIPS BETWEEN PHOTOS AND THE APPLICATION THEY WERE CREATED WITH? BY SCOTT KOENIG</b></li>
https://smarterforensics.com/2020/08/does-photos-sqlite-have-relations-with-cameramessagesapp-by-scott-koenig/
<li><b>KnowledgeC (and Friends)</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=2
<li><b>Building a Pattern of Life - Leveraging Location and Health Data</b></li>
https://www.youtube.com/watch?v=eU7THDwFkiM
<li><b>iOS 16 - Now You 'C' It, Now You Don't -- Breaking Down The Biomes Part 1</b></li>
https://blog.d204n6.com/2022/09/ios-16-now-you-c-it-now-you-dont.html
<li><b>iOS - Tracking Traces of Deleted Applications</b></li>
https://blog.d204n6.com/2019/09/ios-tracking-traces-of-deleted.html
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>Magnet User Summit 2022 CTF - iPhone</b></li>
https://www.stark4n6.com/2022/06/magnet-user-summit-2022-ctf-iphone.html
<li><b>KwnoledgeC queries</b></li>
https://github.com/ScottKjr3347/iOS_KnowledgeC.db_Queries
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>APOLLO KnowledgeC Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_activity_level.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_activity_level_feedback.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_airplay_prediction.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_calendar.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_clock.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_mail.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_maps.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_notes.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_passbook.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_photos.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_safari.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_activity_weather.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_inFocus.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_install.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_intents.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_location_activity.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_media_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_relevantshortcuts.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_app_webusage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_audio_bluetooth_connected.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_audio_input_route.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_audio_media_nowplaying.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_audio_output_route.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_calendar_event_title.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_charging_smart_topoff_checkpoint.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_dasd_activity_profile.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_dasd_battery_temperature.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_dasd_control_effort.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_battery_saver.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_batterylevel.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_carplay_connected.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_inferred_motion.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_is_backlit.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_keybag_locked.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_locked.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_locked_imputed.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_low_power_mode.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_orientation.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_pluggedin.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_device_watch_nearby.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_discoverability_signals.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_discoverability_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_disk_subsystem_access.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_event_tombstone.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_family_prediction.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_inferred_microlocation_visit.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_knowledge_sync_addition_window.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_notification_usage.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_paired_device_nearby.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_deletes_all.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_deletes_recent.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_edit_all.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_engagement.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_favorites_other.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_share_airdrop.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_share_all.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_photos_share_extension.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_portrait_entity.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_portrait_topic.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_safari_browsing.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_segment_monitor.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_settings_doNotDisturb.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_sharesheet_feedback.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_siri.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_siri_activites.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_siri_flow_activity.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_siri_service.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_spotlight_viewer_event.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_standby_timer.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_sync_addition_window.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_sync_deletion_bookmark.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_system_airplane_mode.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_system_tlc.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_system_userwakingevent.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_user_first_backlight_after_wakeup.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_user_interaction_app_directory.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_widget_refresh.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_widget_view.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_widgets_viewed.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/knowledge_wifi_connection.txt
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/CoreDuet/People/interactionC.db</b>
<ul>
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>KnowledgeC (and Friends)</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=2
<li><b>Socially Distant but Still Interacting! New and Improved Updates to macOS/iOS CoreDuet interactionC.db APOLLO Modules</b></li>
http://www.mac4n6.com/blog/2020/6/21/socially-distant-but-still-interacting-new-and-improved-updates-to-macosios-coreduet-interactioncdb-apollo-modules
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>APOLLO interactionC Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/interaction_contact_interactions.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/interaction_contact_interactions_keywords.txt
<li><b>iLEAPP interactionC Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/interactionCcontacts.py
<li><b>Local Photo Library Photos.sqlite Query Variations & WHERE statements</b></li>
https://theforensicscooter.com/2022/02/21/photos-sqlite-update/
<li><b>Comparison of iOS backups: Encrypted vs Unencrypted</b></li>
https://www.arcpointforensics.com/news/comparison-of-ios-backups
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/DataAccess/</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>A Digital Forensic Analysis on the iCloud® and its Synchronization to Apple® Devices</b></li>
https://www.marshall.edu/forensics/files/FRIEDMANRACHEL-Research-Paper-08242012.pdf
</ul>
</li>
<li>
<b>/mobile/Library/DeviceRegistry.state/activeStateMachine.plist</b>
<ul>
<li><b>Apple Watch Forensics 02: Analysis</b></li>
https://blog.elcomsoft.com/2019/06/apple-watch-forensics-02-analysis/
<li><b>APPLE WATCH FORENSICS: IS IT EVER POSSIBLE, AND WHAT IS THE PROFIT?</b></li>
https://dfrws.org/wp-content/uploads/2019/06/2019_EU_pres-apple_watch_forensics_is_it_ever_possible_and_what_is_the_profit.pdf
<li><b>Data Extraction and Forensic Analysis for Smartphone Paired Wearables and IoT Devices</b></li>
https://www.researchgate.net/publication/339022164_Data_Extraction_and_Forensic_Analysis_for_Smartphone_Paired_Wearables_and_IoT_Devices
</ul>
</li>
<li>
<b>/mobile/Library/DeviceRegistry.state/historySecureProperties.plist</b>
<ul>
<li><b>Apple Watch Forensics 02: Analysis</b></li>
https://blog.elcomsoft.com/2019/06/apple-watch-forensics-02-analysis/
<li><b>APPLE WATCH FORENSICS: IS IT EVER POSSIBLE, AND WHAT IS THE PROFIT?</b></li>
https://dfrws.org/wp-content/uploads/2019/06/2019_EU_pres-apple_watch_forensics_is_it_ever_possible_and_what_is_the_profit.pdf
<li><b>Data Extraction and Forensic Analysis for Smartphone Paired Wearables and IoT Devices</b></li>
https://www.researchgate.net/publication/339022164_Data_Extraction_and_Forensic_Analysis_for_Smartphone_Paired_Wearables_and_IoT_Devices
</ul>
</li>
<li>
<b>/mobile/Library/DoNotDisturb/DB/Settings.sqlite</b>
</li>
<li>
<b>/mobile/Library/DuetExpertCenter/streams/userNotificationEvent/local</b>
<ul>
<li><b>Peeking at User Notification Events in iOS 15</b></li>
https://gforce4n6.blogspot.com/2022/05/peeking-at-user-notification-events-in.html
<li><b>Peeking at User Notification Events in iOS 15</b></li>
https://dfrws.org/presentation/dfir-review-showcase-peeking-at-user-notification-events-in-ios-15/
<li><b>iOS 16 - "Paul unsent a message." ... OR DID HE?!</b></li>
https://blog.d204n6.com/2022/09/ios-16-paul-unsent-message-or-did-he.html
<li><b>iLEAPP User Notifications Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/notificationsDuet.py
</ul>
</li>
<li>
<b>/mobile/Library/FrontBoard/applicationState.db</b>
<ul>
<li><b>Identifying installed and uninstalled apps in iOS</b></li>
https://abrignoni.blogspot.com/2018/12/identifying-installed-and-uninstalled.html
<li><b>iOS - Tracking Traces of Deleted Applications</b></li>
https://blog.d204n6.com/2019/09/ios-tracking-traces-of-deleted.html
<li><b>iOS Application Groups & Shared data</b></li>
http://www.swiftforensics.com/2021/01/ios-application-groups-shared-data.html
<li><b>iOS - Tracking Bundle IDs for Containers, Shared Containers, and Plugins</b></li>
https://blog.d204n6.com/2020/09/ios-tracking-bundle-ids-for-containers.html
<li><b>iOS – Tracking Bundle IDs for Containers, Shared Containers, and Plugins</b></li>
https://www.magnetforensics.com/blog/ios-tracking-bundle-ids-for-containers-shared-containers-and-plugins/
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Magnet Virtual Summit 2020 CTF (iOS)</b></li>
https://www.stark4n6.com/2020/06/magnet-virtual-summit-2020-ctf-ios.html
<li><b>iLEAPP Application State Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/applicationstate.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Health/ActivitySharing/contacts.dat</b>
<ul>
<li><b>#DFIRFIT or Bust - A forensic exploration of iOS Health Data</b></li>
https://papers.put.as/papers/ios/2018/summit_archive_1528385073.pdf
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
</ul>
</li>
<li>
<b>/mobile/Library/Health/healthdb.sqlite</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Health/healthdb_secure.sqlite</b>
<ul>
<li><b>#DFIRFIT or Bust - A forensic exploration of iOS Health Data</b></li>
https://papers.put.as/papers/ios/2018/summit_archive_1528385073.pdf
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
<li><b>Audio and App Usage in Apple Health</b></li>
https://www.stark4n6.com/2022/08/audio-and-app-usage-in-apple-health.html
<li><b>Enriching Investigations with Apple Watch Data Through the healthdb_secure.sqlite Database</b></li>
https://dfir.pubpub.org/pub/xqvcn3hj/release/1
<li><b>Building a Pattern of Life - Leveraging Location and Health Data</b></li>
https://www.youtube.com/watch?v=eU7THDwFkiM
</ul>
</li>
<li>
<b>/mobile/Library/homed/datastore.sqlite</b>
<ul>
<li><b>A journey into IoT Forensics - Episode 5 - Analysis of the Apple HomePod and the Apple Home Kit Environment (aka thanks RN Team!)</b></li>
https://blog.digital-forensics.it/2021/01/a-journey-into-iot-forensics-episode-5.html
<li><b>Forensic Analysis of Apple HomePod & Apple HomeKit Environment w/ Mattia Epifani - SANS DFIR Summit</b></li>
https://www.youtube.com/watch?v=D8AOXCBkaTY
</ul>
</li>
<li>
<b>/mobile/Library/Keyboard/<language>-dynamic.lm/dynamic-lexicon.dat</b>
<ul>
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>iLEAPP Keyboard Lexicon</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/keyboardLexicon.py
</ul>
</li>
<li>
<b>/mobile/Library/Keyboard/app_usage_database.plist</b>
<ul>
<li><b>iLEAPP App Usage Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/keyboardAppUsage.py
</ul>
</li>
<li>
<b>/mobile/Library/Keyboard/langlikelihood.dat</b>
<ul>
<li><b>Cellebrite CTF 2021 Writeup</b></li>
https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708
</ul>
</li>
<li>
<b>/mobile/Library/Keyboard/UserDictionary.sqlite</b>
<ul>
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
</ul>
</li>
<li>
<b>/mobile/Library/Logs/AppConduit/</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Using Apple “Bug Reporting” for forensic purposes</b></li>
https://for585.com/sysdiagnose
<li><b>iOS Sysdiagnose AppConduit script</b></li>
https://github.com/cheeky4n6monkey/iOS_sysdiagnose_forensic_scripts/blob/master/sysdiagnose-appconduit.py
<li><b>iLEAPP AppConduit Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/appConduit.py
</ul>
</li>
<li>
<b>/mobile/Library/Logs/mobile_installation_helper.log*</b>
</li>
<li>
<b>/mobile/Library/Logs/mobileactivationd/</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Cellebrite CTF 2021 - Beth's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-beths-iphone.html
<li><b>Apple TV Forensics 03: Analysis</b></li>
https://blog.elcomsoft.com/2019/09/apple-tv-forensics-03-analysis/
<li><b>iLEAPP Mobile Activation Logs Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/mobileActivationLogs.py
</ul>
</li>
<li>
<b>/mobile/Library/Mail/</b>
<ul>
<li><b>iOS Mail</b></li>
https://www.doubleblak.com/m/blogPosts.php?id=10
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/MedicalID/MedicalIDData.Archive</b>
<ul>
<li><b>Magnet Virtual Summit 2020 CTF (iOS)</b></li>
https://www.stark4n6.com/2020/06/magnet-virtual-summit-2020-ctf-ios.html
<li><b>iLEAPP MedicalID Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/medicalID.py
</ul>
</li>
<li>
<b>/mobile/Library/NanoBackup/</b>
</li>
<li>
<b>/mobile/Library/NanoMusicSync/</b>
</li>
<li>
<b>/mobile/Library/NanoPreferencesSync/</b>
<ul>
<li><b>Apple Watch Forensics 02: Analysis</b></li>
https://blog.elcomsoft.com/2019/06/apple-watch-forensics-02-analysis/
</ul>
</li>
<li>
<b>/mobile/Library/NanoTimeKit/</b>
</li>
<li>
<b>/mobile/Library/PersonalizationPortrait/PPSQLDatabase.db</b>
<ul>
<li><b>Guest Post by @bizzybarney! A Peek Inside the PPSQLDatabase.db Personalization Portrait Database</b></li>
http://www.mac4n6.com/blog/2020/6/2/guest-post-by-bizzybarney-a-peek-inside-the-ppsqldatabasedb-personalization-portrait-database
<li><b>Lucky (iOS) #13: Time to Press Your Bets w/ Jared Barnhart - SANS DFIR Summit 2020</b></li>
https://www.youtube.com/watch?v=8Fy83iQ4f8Q
</ul>
</li>
<li>
<b>/mobile/Library/Preferences/.GlobalPreferences.plist</b>
<ul>
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
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
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
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
<li><b>How iOS Properties Files Can Confirm a Suspect’s Contacts Even If Deleted</b></li>
https://cellebrite.com/en/how-ios-properties-files-can-confirm-a-suspects-contacts-even-if-data-deleted/
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
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
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
<b>/mobile/Library/Recents/Recents</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Library/Safari/Bookmarks.db</b>
<ul>
<li><b>iOS 14 - First Thoughts and Analysis</b></li>
https://blog.d204n6.com/2020/09/ios-14-first-thoughts-and-analysis.html
<li><b>Getting Started with iOS Forensics</b></li>
https://www.systoolsgroup.com/forensics/sqlite/ios.html
<li><b>iLEAPP Safari Bookmarks Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/safariBookmarks.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Safari/BrowserState.db</b>
<ul>
<li><b>Examining mobile devices: identiffying private internet browking activity in Mobile Safari</b></li>
https://www.opentext.com/file_source/OpenText/en_US/PDF/Examining-mobiledevices-&-private-internet-browsing-activity-whitepaper-en.pdf
<li><b>iOS 14 - First Thoughts and Analysis</b></li>
https://blog.d204n6.com/2020/09/ios-14-first-thoughts-and-analysis.html
<li><b>iLEAPP Safari Tabs Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/safariTabs.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Safari/CloudTabs.db</b>
<ul>
<li><b>iLEAPP Safari Tabs Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/safariTabs.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Safari/History.db</b>
<ul>
<li><b>Missing SQLite Records Analysis</b></li>
https://dfir.pubpub.org/pub/33vkc2ul/release/1
<li><b>KnowledgeC (and Friends)</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=2
<li><b>Magnet User Summit 2022 CTF - iPhone</b></li>
https://www.stark4n6.com/2022/06/magnet-user-summit-2022-ctf-iphone.html
<li><b>APOLLO Safari History Module</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/iconsScreen.py
<li><b>iLEAPP Safari History Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/safariHistory.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/Safari/SafariTabs.db</b>
<ul>
<li><b>iOS 16 - Breaking Down the Biomes (Part 4) - Surfin' with Safari</b></li>
https://blog.d204n6.com/2022/09/ios-16-breaking-down-biomes-part-4.html
<li><b>iOS 16: What Digital Investigators Need to Know</b></li>
https://www.magnetforensics.com/blog/ios-16-what-digital-investigators-need-to-know/
<li><b>Checking in on iOS 16 in Magnet AXIOM 6.8</b></li>
https://www.magnetforensics.com/blog/checking-in-on-ios-16-in-magnet-axiom-6-8/
</ul>
</li>
<li>
<b>/mobile/Library/SMS/Attachments/</b>
<ul>
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/SMS/Drafts/</b>
<ul>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/draftmessage.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/SMS/sms.db</b>
<ul>
<li><b>iOS16 iMessages</b></li>
https://doubleblak.com/blogPosts.php?id=27
<li><b>iOS 16 - "Paul unsent a message." ... OR DID HE?!</b></li>
https://blog.d204n6.com/2022/09/ios-16-paul-unsent-message-or-did-he.html
<li><b>Message Reactions</b></li>
https://doubleblak.com/blogPosts.php?id=24
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iLEAPP SMS Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/sms.py
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/SMS/sms-temp.db</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/HomeBackgroundThumbnail.jpg</b>
</li>
<li>
<b>/mobile/Library/SpringBoard/IconState.plist</b>
<ul>
<li><b>Today, Widgets, & Ignored Apps in iOS</b></li>
https://thebinaryhick.blog/2021/07/25/today-widgets-ignored-apps-in-ios/
<li><b>Recover iOS App Screen Layouts with the New iOS Home Screen Items Artifact</b></li>
https://www.magnetforensics.com/blog/recover-ios-app-screen-layouts-with-the-new-ios-home-screen-items-artifact/
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iLEAPP Icon State Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/iconsScreen.py
<li><b>A Few Interesting iOS Forensic Artefacts</b></li>
https://salt4n6.com/2018/05/15/a-few-interesting-ios-forensic-artefacts/
<li><b>iOS - Tracking Traces of Deleted Applications</b></li>
https://blog.d204n6.com/2019/09/ios-tracking-traces-of-deleted.html
<li><b>Auto-Parser: Android Auto and Apple CarPlay Forensics</b></li>
https://link.springer.com/chapter/10.1007/978-3-031-06365-7_4
https://github.com/BiTLab-BaggiliTruthLab/Auto-Parser-Android-Auto-Apple-CarPlay
<li><b>They See Us Rollin’; They Hatin’: Forensics of iOS CarPlay and Android Auto</b></li>
https://papers.put.as/papers/ios/2019/summit_archive_1564072550.pdf
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/LockBackgroundThumbnail.jpg</b>
</li>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/LockBackgroundThumbnaildark.jpg</b>
</li>
<ul>
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/mobile/Library/SpringBoard/PushStore/</b>
<ul>
<li><b>pushstore_parser</b></li>
https://github.com/jakev/pushstore-parser
<li><b>iLEAPP PushStore Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/notificationsXI.py
</ul>
</li>
<li>
<b>/mobile/Library/Suggestions/query_predictions.db</b>
<ul>
<li><b>iLEAPP Query Predictions Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/queryPredictions.py
</ul>
</li>
<li>
<b>/mobile/Library/TCC/TCC.db</b>
<ul>
<li><b>iLEAPP TCC Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/tcc.py
</ul>
</li>
<li>
<b>/mobile/Library/UserConfigurationProfiles/PublicEffectiveUserSettings.plist</b>
<ul>
<li><b>iOS Settings Display Auto-Lock & Require Passcode</b></li>
https://theforensicscooter.com/2021/09/05/ios-settings-display-auto-lock-require-passcode/
<li><b>iOS Settings Display Auto-Lock & Require Passcode</b></li>
https://dfir.pubpub.org/pub/khnqi0ff/release/1
<li><b>Cellebrite CTF 2021 - Beth's iPhone</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-beths-iphone.html
<li><b>Cellebrite CTF 2021 Writeup</b></li>
https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708
</ul>
</li>
<li>
<b>/mobile/Library/UserConfigurationProfiles/UserSettings.plist</b>
</li>
<li>
<b>/mobile/Library/UserNotifications/</b>
<ul>
<li><b>Magnet User Summit 2022 CTF - iPhone</b></li>
https://www.stark4n6.com/2022/06/magnet-user-summit-2022-ctf-iphone.html
<li><b>iLEAPP User Notifications Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/notificationsXII.py
<li><b>Mobile Cyber Forensic Investigations of Web3 Wallets on Android and iOS</b></li>
https://www.mdpi.com/2076-3417/12/21/11180
</ul>
</li>
<li>
<b>/mobile/Library/Voicemail/voicemail.db</b>
<ul>
<li><b>iOS Voicemail Transcripts</b></li>
https://www.linkedin.com/pulse/ios-voicemail-transcripts-charlie-rubisoff/
<li><b>Dude, Where's My Banana? Retrieving data from an iPhone voicemail database</b></li>
http://cheeky4n6monkey.blogspot.com/2013/01/dude-wheres-my-banana-retrieving-data.html
<li><b>Dude, Where's My Data?</b></li>
http://az4n6.blogspot.com/2012/12/dude-wheres-my-data.html
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf

<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/mobile/Media/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/mobile/Media/DCIM/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/iTunes_Control/iTunes/MediaLibrary.sqlitedb</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/iTunesControl/iTunes/iTunesPrefs</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/MediaAnalysis/mediaanalysis.db</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/PhotoData/AlbumsMetadata/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/PhotoData/Caches/GraphService/CLSPublicEventCache.sqlite</b>
</li>
<li>
<b>/mobile/Media/PhotoData/CPL/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/PhotoData/Photos.sqlite</b>
<ul>
<li><b>iLEAPP Photos Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/photosMetadata.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/mobile/Media/PhotoData/Thumbnails/</b>
<ul>
<li><b>
</ul>
</li>
<li>
<b>/mobile/Media/Recordings/</b>
<ul>
<li><b>
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/mobile/MobileSoftwareUpdate/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/mobile/MobileSoftwareUpdate/restore.log</b>
<ul>
<li><b>Restore Log - Tracking iOS Update History
https://www.stark4n6.com/2021/10/restore-log-tracking-ios-update-history.html
<li><b>Cellebrite CTF 2021 Writeup</b></li>
https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708
<li><b>iLEAPP restore.log Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/restoreLog.py
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/networkd/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/networkd/netusage.sqlite</b>
<ul>
<li><b>Network and Application Usage using netusage.sqlite & DataUsage.sqlite iOS Databases</b></li>
http://www.mac4n6.com/blog/2019/1/6/network-and-application-usage-using-netusagesqlite-amp-datausagesqlite-ios-databases
<li><b>iOS - Tracking Traces of Deleted Applications</b></li>
https://blog.d204n6.com/2019/09/ios-tracking-traces-of-deleted.html
<li><b>iLEAPP Net Usage Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/netusage.py
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/preferences/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/preferences/com.apple.networkextension.plist</b>
</li>
<li>
<b>/preferences/com.apple.wifi.known-networks.plist</b>
<ul>
<li><b>Apple Private Wi-Fi Addresses</b></li>
https://ciofecaforensics.com/2020/10/24/apple-private-addresses/
<li><b>Sysdiagnose in iOS 16: a first look from a Digital Forensics perspective</b></li>
https://blog.digital-forensics.it/2022/11/sysdiagnose-in-ios-16-first-look-from.html
<li><b>mac_apt WiFi Plugin</b></li>
https://github.com/ydkhatri/mac_apt/blob/master/plugins/ios_wifi.py
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/com.apple.accounts.exists.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iLEAPP Conf Accounts Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/confaccts.py
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/com.apple.networkidentification.plist</b>
<ul>
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>Everything You Always Wanted to Know About iTunes and iCloud Backups But Were Afraid to Ask</b></li>
https://blog.elcomsoft.com/2014/03/itunes-icloud-backups/
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/com.apple.radios.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/com.apple.wifi.plist</b>
<ul>
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 19-5551 Summary Report</b></li>
https://cts-forensics.com/reports/19-5551_Web.pdf
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/com.apple.wifi-private-mac-networks.plist</b>
<ul>
<li><b>Apple Private Wi-Fi Addresses</b></li>
https://ciofecaforensics.com/2020/10/24/apple-private-addresses/
<li><b>iLEAPP WiFi Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/appleWifiPlist.py
<li><b>mac_apt WiFi Plugin</b></li>
https://github.com/ydkhatri/mac_apt/blob/master/plugins/ios_wifi.py
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/NetworkInterfaces.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Sysdiagnose Network Interfaces script</b></li>
https://github.com/cheeky4n6monkey/iOS_sysdiagnose_forensic_scripts/blob/master/sysdiagnose-networkinterfaces.py
<li><b>Using Apple “Bug Reporting” for forensic purposes</b></li>
https://for585.com/sysdiagnose
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/preferences/SystemConfiguration/preferences.plist</b>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/root/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/root/.obliterated</b>
<ul>
<li><b>Upgrade From NULL—Detecting iOS Wipe Artifacts</b></li>
https://dfir.pubpub.org/pub/6i7d593n/release/1
<li><b>How To Identify When an IPhone or iPad was Factory Reset</b></li>
https://athenaforensics.co.uk/how-to-identify-when-an-iphone-or-ipad-was-factory-reset/
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
</ul>
</li>
<li>
<b>/root/Library/Application Support/com.apple.wifianalyticsd/DeviceAnalyticsModel.sqlite</b>
</li>
<li>
<b>/root/Library/Application Support/com.apple.wifianalyticsd/WiFiNetworkStoreModel.sqlite</b>
<ul>
<li><b>iLEAPP WifiNetworkStoreModel Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/wifiNetworkStoreModel.py
</ul>
</li>
<li>
<b>/root/Library/Caches/com.apple.wifid/ThreeBars.sqlite</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Locations, Locations, Locations</b></li>
https://doubleblak.com/blogPosts.php?id=14
</ul>
</li>
<li>
<b>/root/Library/Caches/locationd/Cache.sqlite</b>
</li>
<li>
<b>/root/Library/Caches/locationd/cache_encryptedA.db</b>
<ul>
<li><b>New Script – iOS Locations Scraper</b></li>
http://www.mac4n6.com/blog/2016/6/6/new-script-ios-locations-scraper
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
<li><b>Getting Started with iOS Forensics</b></li>
https://www.systoolsgroup.com/forensics/sqlite/ios.html
<li><b>APOLLO cache_ecnryptedA/B Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedAB_cdmacelllocation.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedAB_celllocation.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedAB_celllocationlocal.txt
</ul>
</li>
<li>
<b>/root/Library/Caches/locationd/cache_encryptedB.db</b>
<ul>
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>New Script – iOS Locations Scraper</b></li>
http://www.mac4n6.com/blog/2016/6/6/new-script-ios-locations-scraper
<li><b>Smartphone Privacy: How Your Smartphone Tracks Your Entire Life</b></li>
https://conference.hitb.org/hitbsecconf2018pek/materials/D2T2%20-%20How%20Your%20Smartphone%20Tracks%20Your%20Entire%20Life%20-%20Vladimir%20Katalov.pdf
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>APOLLO cache_ecnryptedA/B Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedAB_cdmacelllocation.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedAB_celllocation.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedAB_celllocationlocal.txt
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/root/Library/Caches/locationd/cache_encryptedC.db</b>
<ul>
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>SANS 2022 DFIR Summit Queries</b></li>
https://for585.com/dfirsummit22
<li><b>APOLLO cache_ecnryptedC Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedC_motionstatehistory.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedC_stepcounthistory.txt
https://github.com/mac4n6/APOLLO/blob/master/modules/locationd_cacheencryptedC_nataliehistory.txt
<li><b>The phone reveals your motion: Digital traces of walking, driving and other movements on iPhones</b></li>
https://www.sciencedirect.com/science/article/abs/pii/S2666281721000780
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/root/Library/Caches/locationd/clients.plist</b>
<ul>
<li><b>iOS Location Services and System Services ON or OFF?</b></li>
https://theforensicscooter.com/2021/09/20/ios-location-services-and-system-services-on-or-off/
<li><b>iOS Location Services and System Services are they ON or OFF</b></li>
https://dfir.pubpub.org/pub/4sv4kxyh/release/2
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/root/Library/Caches/locationd/consolidated.db</b>
<ul>
<li><b>iOS GeoFences</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=22
<li><b>BELKASOFT CTF JULY 2022: WRITE-UP</b></li>
https://belkasoft.com/belkactf-jul2022-writeup
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/root/Library/Lockdown/data_ark.plist</b>
<ul>
<li><b>Putting a User Behind an iOS Device</b></li>
https://dfrws.org/wp-content/uploads/2020/06/2020_USA_pres-putting_a_user_behind_an_ios_device.pdf
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Oh no! I have a wiped iPhone, now what?</b></li>
https://blog.digital-forensics.it/2021/05/oh-no-i-have-wiped-iphone-now-what.html
<li><b>KnowledgeC (and Friends)</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=2
<li><b>Magnet Virtual Summit 2020 CTF (iOS)</b></li>
https://www.stark4n6.com/2020/06/magnet-virtual-summit-2020-ctf-ios.html
<li><b>iOS - Tracking Device Migration</b></li>
https://blog.d204n6.com/2021/06/ios-tracking-device-migration.html
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
</ul>
</li>
<li>
<b>/root/Library/Lockdown/escrow_records/</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Understanding usbmux and the iOS lockdown service</b></li>
https://jon-gabilondo-angulo-7635.medium.com/understanding-usbmux-and-the-ios-lockdown-service-7f2a1dfd07ae
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/root/Library/Lockdown/pair_records/</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Understanding usbmux and the iOS lockdown service</b></li>
https://jon-gabilondo-angulo-7635.medium.com/understanding-usbmux-and-the-ios-lockdown-service-7f2a1dfd07ae
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/root/Library/Logs/MobileContainerManager</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>How To Identify When an IPhone or iPad was Factory Reset</b></li>
https://athenaforensics.co.uk/how-to-identify-when-an-iphone-or-ipad-was-factory-reset/
<li><b>So Long Lockdown!</b></li>
http://www.doubleblak.com/m/blogPosts.php?id=9
<li><b>Upgrade From NULL—Detecting iOS Wipe Artifacts</b></li>
https://dfir.pubpub.org/pub/6i7d593n/release/1
<li><b>Using Apple “Bug Reporting” for forensic purposes</b></li>
https://for585.com/sysdiagnose
<li><b>Apple Watch Forensics 02: Analysis</b></li>
https://blog.elcomsoft.com/2019/06/apple-watch-forensics-02-analysis/
<li><b>Apple TV Forensics 03: Analysis</b></li>
https://blog.elcomsoft.com/2019/09/apple-tv-forensics-03-analysis/
<li><b>iLEAPP Mobile Container Manager Logs Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/mobileContainerManager.py
</ul>
</li>
<li>
<b>/root/Library/MobileContainerManager/containers.sqlite3</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Application Groups & Shared data</b></li>
http://www.swiftforensics.com/2021/01/ios-application-groups-shared-data.html
</ul>
</li>
<li>
<b>/root/Library/Preferences/com.apple.MobileBackup.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>Using Apple “Bug Reporting” for forensic purposes</b></li>
https://for585.com/sysdiagnose
<li><b>Sysdiagnose in iOS 16: a first look from a Digital Forensics perspective</b></li>
https://blog.digital-forensics.it/2022/11/sysdiagnose-in-ios-16-first-look-from.html
<li><b>iOS Sysdiagnose Mobile Backup script</b></li>
https://github.com/cheeky4n6monkey/iOS_sysdiagnose_forensic_scripts/blob/master/sysdiagnose-mobilebackup.py
<li><b>Local Photo Library Photos.sqlite Query Documentation & Notable Artifacts</b></li>
https://theforensicscooter.com/2022/05/02/photos-sqlite-query-documentation-notable-artifacts/
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/root/Library/Preferences/com.apple.preferences.network.plist</b>
<ul>
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>Wireless Network Preferences – iOS</b></li>
https://bitsplease4n6.wordpress.com/2020/12/17/wireless-network-preferences-ios/
</ul>
</li>
</ul>
</div>
<p><h2 style="text-align: left;"><b><span style="font-size: medium;">"/wireless/" folder</span></b></h2></p>
<div>
<ul>
<li>
<b>/wireless/Library/Databases/CellularUsage.db</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>A Few Interesting iOS Forensic Artefacts</b></li>
https://salt4n6.com/2018/05/15/a-few-interesting-ios-forensic-artefacts/
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>Cellebrite CTF 2021 - Marsha's Backup</b></li>
https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-marshas-backup.html
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
</ul>
</li>
<li>
<b>/wireless/Library/Databases/DataUsage.sqlite</b>
<ul>
<li><b>Network and Application Usage using netusage.sqlite & DataUsage.sqlite iOS Databases</b></li>
http://www.mac4n6.com/blog/2019/1/6/network-and-application-usage-using-netusagesqlite-amp-datausagesqlite-ios-databases
<li><b>FROM APPLE SEEDS TO APPLE PIE</b></li>
https://objectivebythesea.org/v1/talks/OBTS_v1_Edwards.pdf
<li><b>iOS - Tracking Traces of Deleted Applications</b></li>
https://blog.d204n6.com/2019/09/ios-tracking-traces-of-deleted.html
<li><b>iOS Analysis Test No. 20-5551 Summary Report</b></li>
https://cts-forensics.com/reports/20-5551_Web.pdf
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>iOS Forensics: HFS+ file system, partitions and relevant evidences</b></li>
https://andreafortuna.org/2020/08/31/ios-forensics-hfs-file-system-partitions-and-relevant-evidences/
<li><b>APOLLO DataUsage Modules</b></li>
https://github.com/mac4n6/APOLLO/blob/master/modules/datausage_zliveusage.txt 
https://github.com/mac4n6/APOLLO/blob/master/modules/netusage_zprocess.txt
<li><b>iLEAPP DataUsage Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/netusage.py
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
<li>
<b>/wireless/Library/preferences/com.apple.commcenter.callservices.plist</b>
</li>
<li>
<b>/wireless/Library/Preferences/com.apple.commcenter.counts.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/wireless/Library/Preferences/com.apple.commcenter.data.plist</b>
<ul>
<li><b>Mo’ SIMs, Mo’ Problems. Examining Phones with Dual SIMs.</b></li>
https://thebinaryhick.blog/2022/12/06/mo-sims-mo-problems-examining-phones-with-dual-sims/
<li><b>iLEAPP SimInfo Plugin</b></li>
https://github.com/abrignoni/iLEAPP/blob/main/scripts/artifacts/simInfo.py  
</ul>
</li>
<li>
<b>/wireless/Library/Preferences/com.apple.commcenter.device_specific_nobackup.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
</ul>
</li>
<li>
<b>/wireless/Library/Preferences/com.apple.commcenter.plist</b>
<ul>
<li><b>Checkra1n Era - Ep 4 - Analyzing extractions "Before First Unlock"</b></li>
https://blog.digital-forensics.it/2019/12/checkra1n-era-ep-4-analyzing.html
<li><b>iOS Forensics: BFU (Before First Unlock) acquisition, using checkra1n</b></li>
https://andreafortuna.org/2020/01/10/ios-forensics-bfu-before-first-unlock-acquisition-using-checkra1n/
<li><b>Artifacts of an IOS device</b></li>
https://infosecaddicts.com/artifacts-ios-device/
<li><b>Mobile Digital Evidence - iOS Analysis Test No. 18-5551</b></li>
https://cts-forensics.com/reports/38551_Web.pdf
<li><b>iOS Analysis Test No. 21-5551 Summary Report</b></li>
https://cts-forensics.com/reports/21-5551_Web.pdf
<li><b>iOS Analysis Test No. 22-5551 Summary Report</b></li>
https://cts-forensics.com/reports/22-5551_Web.pdf
<li><b>Practical Mobile Forensics - Fourth Edition</b></li>
https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520
<li><b>iOS Forensics for Investigators</b></li>
https://www.packtpub.com/product/ios-forensics-for-investigators/9781803234083
</ul>
</li>
</ul>
</div>
