int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
02-06 17:19:13.596 D/hw_netstat( 4261): total/279/132,unknown:0/279/132
--------- beginning of system
02-06 17:19:13.903 W/ActivityManager( 4261): getRunningAppProcesses: caller 10046 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Ignored event (cmd=34) for foreign interface (ifindex 9 wdev 0x0)
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
02-06 17:19:14.521 D/wpa_supplicant( 4417): wlan0: nl80211: New scan results available
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Scan probed for SSID '\xe9\x92\xb1\xe5\xae\x9d\xe9\x82\x80\xe6\x82\xa8\xe5\x85\x8d\xe8\xb4\xb9\xe4\xb8\x8a\xe7\xbd\x91'
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Scan probed for SSID 'Acer\xe8\x9c\x82\xe9\xb8\x9f\xe5\x85\x8d\xe8\xb4\xb9Wifi'
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Scan probed for SSID 'KFC FREE WIFI'
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Scan probed for SSID '629041'
02-06 17:19:14.521 D/wpa_supplicant( 4417): nl80211: Scan probed for SSID ''
02-06 17:19:14.522 D/wpa_supplicant( 4417): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5745 5765 5785 5805 5825
02-06 17:19:14.522 D/wpa_supplicant( 4417): wlan0: Event SCAN_RESULTS (3) received
02-06 17:19:14.522 D/wpa_supplicant( 4417): wlan0: Scan completed in 2.413340 seconds
02-06 17:19:14.522 D/wpa_supplicant( 4417): nl80211: Associated on 2422 MHz
02-06 17:19:14.522 D/wpa_supplicant( 4417): nl80211: Associated with 84:82:f4:32:9c:f9
02-06 17:19:14.523 D/wpa_supplicant( 4417): nl80211: Received scan results (18 BSSes)
02-06 17:19:14.523 D/wpa_supplicant( 4417): nl80211: Scan results indicate BSS status with 84:82:f4:32:9c:f9 as associated
02-06 17:19:14.523 D/wpa_supplicant( 4417): WPS: AP vendor specific ies
02-06 17:19:14.523 D/wpa_supplicant( 4417): WPS: AP SSID=ChinaNet-kUaV, MAC=40:f4:20:ef:ea:92, manufacturer=, mode name=, model number=, device name=
02-06 17:19:14.523 D/wpa_supplicant( 4417): WPS: AP vendor specific ies
02-06 17:19:14.523 D/wpa_supplicant( 4417): WPS: AP SSID=ChinaNet-U3Ka, MAC=40:f4:20:f0:0b:2a, manufacturer=Broadcom, mode name=Broadcom, model number=123456, device name=BroadcomAP
02-06 17:19:14.523 D/wpa_supplicant( 4417): WPS: AP vendor specific ies
02-06 17:19:14.524 D/wpa_supplicant( 4417): WPS: AP SSID=ChinaNet-gKi7, MAC=40:f4:20:ef:e9:a2, manufacturer=Broadcom, mode name=Broadcom, model number=123456, device name=BroadcomAP
02-06 17:19:14.524 D/wpa_supplicant( 4417): WPS: AP vendor specific ies
02-06 17:19:14.524 D/wpa_supplicant( 4417): WPS: AP SSID=ChinaNet-wbpi, MAC=40:f4:20:93:1c:0a, manufacturer=Broadcom, mode name=Broadcom, model number=123456, device name=BroadcomAP
02-06 17:19:14.524 D/wpa_supplicant( 4417): wlan0: BSS: Start scan result update 496
02-06 17:19:14.524 D/wpa_supplicant( 4417): wlan0: BSS: Remove id 771 BSSID bc:46:99:90:19:9c SSID 'ALDJF-Guest' due to no match in scan
02-06 17:19:14.525 D/wpa_supplicant( 4417): wlan0: BSS: Remove id 775 BSSID 88:25:93:33:03:05 SSID 'broadwell1' due to no match in scan
02-06 17:19:14.525 D/wpa_supplicant( 4417): wlan0: BSS: Remove id 776 BSSID bc:46:99:cd:ae:76 SSID '18KKK' due to no match in scan
02-06 17:19:14.525 D/wpa_supplicant( 4417): BSS: last_scan_res_used=18/32
02-06 17:19:14.525 D/wpa_supplicant( 4417): wlan0: Scan-only results received
02-06 17:19:14.526 D/wpa_supplicant( 4417): wlan0: Radio work 'scan'@0xb7984cb8 done in 2.430030 seconds
02-06 17:19:14.533 D/wpa_supplicant( 4417): wlan0: Control interface command 'BSS RANGE=0- MASK=0x29d87'
02-06 17:19:14.542 D/wpa_supplicant( 4417): wlan0: Control interface command 'BSS RANGE=762- MASK=0x29d87'
02-06 17:19:14.551 D/wpa_supplicant( 4417): wlan0: Control interface command 'BSS RANGE=768- MASK=0x29d87'
02-06 17:19:14.560 D/wpa_supplicant( 4417): wlan0: Control interface command 'BSS RANGE=775- MASK=0x29d87'
02-06 17:19:14.579 I/SendBroadcastPermission( 4261): action:android.net.wifi.SCAN_RESULTS, mPermissionType:0
02-06 17:19:14.580 I/HwActivityManagerService( 4261): collectReceiverComponents, callerApp: ProcessRecord{6a63aed 0:0:system/1000}, flags: 400
02-06 17:19:14.580 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=android.net.wifi.SCAN_RESULTS flg=0x4000010 (has extras) }, receivers: [ResolveInfo{8577751 com.android.settings/.wifi.cmcc.ConnectSwitchReceiver m=0x108000 euid=0}]
02-06 17:19:14.592 E/WifiService( 4261): Permission denial: Need ACCESS_COARSE_LOCATION or ACCESS_FINE_LOCATION permission to get scan results
02-06 17:19:14.592 E/WifiService( 4261): Permission denial: Need ACCESS_COARSE_LOCATION or ACCESS_FINE_LOCATION permission to get scan results
02-06 17:19:14.601 I/ActivityManager( 4261): new Process app=ProcessRecord{d3eabb6 0:0:com.tencent.mtt/u0a101}, name: com.tencent.mtt, euid: 0
02-06 17:19:14.623 I/ActivityManager( 4261): Start proc 21310:com.tencent.mtt/u0a101 for content provider com.tencent.mtt/.base.stat.StatServer
02-06 17:19:14.624 V/ActivityManager_MU( 4261): Waiting to start provider ContentProviderRecord{c4c0b7 u0 euid:0 com.tencent.mtt/.base.stat.StatServer} launchingApp=ProcessRecord{d3eabb6 21310:0:com.tencent.mtt/u0a101} caller pid= 855
02-06 17:19:14.653 D/ActivityThread(21310): ActivityThread,attachApplication
02-06 17:19:14.653 D/ActivityManager( 4261): ActivityManagerService,attachApplication,callingPid = 21310
02-06 17:19:14.654 V/ActivityManager( 4261): New app record ProcessRecord{d3eabb6 21310:0:com.tencent.mtt/u0a101} thread=android.os.BinderProxy@b080024 pid=21310
02-06 17:19:14.663 I/[Gralloc]( 3709): alloc w[16] h[16] format[1] usage[256]
02-06 17:19:14.663 I/[Gralloc]( 3709): alloc succ handle[0xb77b69a8] stride[32]
02-06 17:19:14.664 E/linker  (21310): readlink('/proc/self/fd/21') failed: Permission denied [fd=21]
02-06 17:19:14.665 E/linker  (21310): warning: unable to get realpath for the library "/system/lib/hw/gralloc.hi3630.so". Will use given name.
02-06 17:19:14.667 E/linker  (21310): readlink('/proc/self/fd/21') failed: Permission denied [fd=21]
02-06 17:19:14.667 E/linker  (21310): warning: unable to get realpath for the library "libion.so". Will use given name.
02-06 17:19:14.669 E/HAL     (21310): load: id=gralloc != hmi->id=gralloc
02-06 17:19:14.671 I/MQoS    ( 4261): onSignal: mSubId=0,currDataSubID=0
02-06 17:19:14.672 I/MQoS    ( 4261): received cell-signal:5
02-06 17:19:14.672 D/cell strength( 6014): ===== cell singal strength changed : -46
02-06 17:19:14.672 I/SendBroadcastPermission( 4261): action:android.intent.action.SIG_STR, mPermissionType:0
02-06 17:19:14.673 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=android.intent.action.SIG_STR flg=0x20000010 (has extras) }, receivers: null
02-06 17:19:14.676 D/NetworkController.MobileSignalController(0)( 4891): mSimSubId:0 onSignalStrengthsChanged signalStrength=SignalStrength: -46 0 -89 255 -1 -1 -1 -1 -1 -1 0 0 0 -1 false gw|lte level=4
02-06 17:19:14.676 D/NetworkController.MobileSignalController(0)( 4891):  mDataNetType:17 indexOfkey:14 iconGroup.mName:TDS roaming:false
02-06 17:19:14.676 W/ActivityManager( 4261): getRunningAppProcesses: caller 10046 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:14.677 D/HwCust  (21310): Create obj success use class android.content.res.HwCustHwResourcesImpl
02-06 17:19:14.680 I/HwCustMobileSignalControllerImpl( 4891): subId:0 phoneType:1 networktype:17 targetClass:2 masterLevel:4 slaveLevel:4
02-06 17:19:14.683 D/NetworkController.MobileSignalController(0)( 4891): origin typeIcon:2130838280 icons.mName:TDS
02-06 17:19:14.813 V/ActivityManager( 4261): Provider ContentProviderRecord{c4c0b7 u0 euid:0 com.tencent.mtt/.base.stat.StatServer} is published
02-06 17:19:14.990 D/WifiHW  ( 4261): wifi_send_command: cmd:'IFNAME=wlan0 SIGNAL_POLL'
02-06 17:19:14.991 D/wpa_supplicant( 4417): wlan0: Control interface command 'SIGNAL_POLL'
02-06 17:19:15.000 E/WifiConfigStore( 4261): updateConfiguration freq=2422 BSSID=84:82:f4:32:9c:f9 RSSI=-43 "SZXX-1202"WPA_PSK
02-06 17:19:15.526 I/HwLauncher( 6100):  FPSMonitor [Launcher , dispatchTouchEvent begin, false, true] down event  x = 153 y = 153
02-06 17:19:15.526 I/HwLauncher( 6100): Launcher  while lockScreenOrientation,isRotationEnabled is false!
02-06 17:19:15.527 I/HwLauncher( 6100):  FPSMonitor [PagedView , onIntercept] down event  x = 153 y = 153
02-06 17:19:15.530 I/HwLauncher( 6100):  FPSMonitor [Launcher , dispatchTouchEvent end, false, true] down event  x = 153 y = 153
02-06 17:19:15.587 I/HwLauncher( 6100):  FPSMonitor [Launcher , dispatchTouchEvent begin, false, true] up event  x = 153 y = 153
02-06 17:19:15.587 I/HwLauncher( 6100):  FPSMonitor [PagedView , onIntercept] up event  x = 153 y = 153
02-06 17:19:15.588 I/HwLauncher( 6100): QuickActionView hide() animated = true, fromSticky = true
02-06 17:19:15.588 I/HwLauncher( 6100): QuickActionView hide() action view has already hidden, return.
02-06 17:19:15.588 I/HwLauncher( 6100): Launcher mUnlockScreenRunnbale  getOrientationEnabled false 
02-06 17:19:15.588 I/HwLauncher( 6100):  FPSMonitor [Launcher , dispatchTouchEvent end, false, true] up event  x = 153 y = 153
02-06 17:19:15.589 V/AudioManager( 6100): playSoundEffect   effectType: 0
02-06 17:19:15.589 V/AudioManager( 6100): querySoundEffectsEnabled...
02-06 17:19:15.589 W/ResourceType( 6100): No known package when getting name for resource number 0x9c040004
02-06 17:19:15.589 I/HwLauncher( 6100): Launcher onclick begin com.huawei.android.launcher.BubbleTextView{32a2e2d VFED..CL. ...P..ID 0,1280-264,1570 #9c040004}
02-06 17:19:15.589 I/HwLauncher( 6100): Launcher.Utilities  startActivitySafely useLaunchAnimation = true
02-06 17:19:15.589 I/HwLauncher( 6100): Launcher.Utilities  startActivitySafely begin startActivity() for current user
02-06 17:19:15.591 I/ActivityManager( 4261): startActivityMayWait, callerApp: ProcessRecord{d9cc27f 6100:0:com.huawei.android.launcher/u0a48}, intent: Intent { act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10200000 cmp=com.highlight.mjhb/.CCXGame bnds=[12,1250][276,1540] }
02-06 17:19:15.591 I/ActivityManager( 4261): resolve info: ResolveInfo{2d6fa90 com.highlight.mjhb/.CCXGame m=0x0 euid=0}, euid: 0
02-06 17:19:15.593 I/ActivityManager( 4261): START u0 {act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10200000 cmp=com.highlight.mjhb/.CCXGame bnds=[12,1250][276,1540]} from uid 10048 on display 0
02-06 17:19:15.593 I/HwUserBehaviourRecord( 4261): appEnterRecord---com.highlight.mjhb
02-06 17:19:15.597 I/ActivityManager( 4261): ActivityRecord info: ActivityInfo{140bf89 com.highlight.mjhb.CCXGame}, euid=0
02-06 17:19:15.599 W/FileUtils( 4261): Failed to chmod(/data/share): android.system.ErrnoException: chmod failed: EPERM (Operation not permitted)
02-06 17:19:15.600 I/K3V3CpuGovernorPolicy( 6044): set scene Hmp policy : 300 , 150
02-06 17:19:15.604 D/HwCust  ( 4261): Create obj success use class android.content.res.HwCustHwResourcesImpl
02-06 17:19:15.612 V/HwWindowManagerService( 4261): moveTaskToTop mTaskChanged:true
02-06 17:19:15.612 I/ActivityManager( 4261): create new task record, multiLaunchId: 0, intent = Intent { act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10200000 cmp=com.highlight.mjhb/.CCXGame }
02-06 17:19:15.613 V/HwWindowManagerService( 4261): moveTaskToTop mTaskChanged:true
02-06 17:19:15.615 D/HwCust  ( 4261): Create obj success use class android.app.HwCustHwWallpaperManagerImpl
02-06 17:19:15.621 V/HwWindowManagerService( 4261): moveTaskToTop mTaskChanged:true
02-06 17:19:15.623 I/HwWindowManagerService( 4261): setFocusedApp token: Token{1550faf ActivityRecord{fe37b8e u0 com.highlight.mjhb/.CCXGame t24013}} requestedOrientation: 0
02-06 17:19:15.627 V/HwWindowManagerService( 4261): setFocusedApp update app ops, mTaskChanged set to:false
02-06 17:19:15.627 I/HwLauncher( 6100): Launcher.Utilities  startActivitySafely end startActivity() for current user
02-06 17:19:15.627 I/HwLauncher( 6100): Launcher onclick end
02-06 17:19:15.632 I/HwLauncher( 6100): Launcher onPause()
02-06 17:19:15.637 I/HwLauncher( 6100): Launcher.MotionManager stopMotionAppsReco begin,flg = 402
02-06 17:19:15.637 D/MotionDetectionManager( 6100): stopMotionAppsReco motionApps: 402
02-06 17:19:15.637 D/MotionDetectionManager( 6100): stopMotionAppsReco not recognition motionApps 402
02-06 17:19:15.637 W/HwLauncher( 6100): Launcher.MotionManager stopMotionAppsReco service flg 402 is unavailable
02-06 17:19:15.638 I/HwLauncher( 6100): Launcher.MotionManager stopMotionAppsReco begin,flg = 403
02-06 17:19:15.638 D/MotionDetectionManager( 6100): stopMotionAppsReco motionApps: 403
02-06 17:19:15.638 D/MotionDetectionManager( 6100): stopMotionAppsReco not recognition motionApps 403
02-06 17:19:15.638 W/HwLauncher( 6100): Launcher.MotionManager stopMotionAppsReco service flg 403 is unavailable
02-06 17:19:15.670 I/ActivityManager( 4261): mService.startProcessLocked for activity: ActivityRecord{fe37b8e u0 com.highlight.mjhb/.CCXGame t24013}, appinfo euid: 0
02-06 17:19:15.670 I/ActivityManager( 4261): new Process app=ProcessRecord{da76e66 0:0:com.highlight.mjhb/u0a103}, name: com.highlight.mjhb, euid: 0
02-06 17:19:15.680 I/[Gralloc]( 3709): alloc w[1080] h[1812] format[1] usage[2355]
02-06 17:19:15.681 I/[Gralloc]( 3709): alloc succ handle[0xb7909fc0] stride[1120]
02-06 17:19:15.681 I/[Gralloc]( 3709): alloc w[1080] h[1920] format[1] usage[3]
02-06 17:19:15.689 I/[Gralloc]( 3709): alloc succ handle[0xb77ad438] stride[1120]
02-06 17:19:15.694 I/ActivityManager( 4261): Start proc 21353:com.highlight.mjhb/u0a103 for activity com.highlight.mjhb/.CCXGame
02-06 17:19:15.701 I/SendBroadcastPermission( 6100): action:com.huawei.android.action.WIDGET_FOCUS_CHANGE, mPermissionType:0
02-06 17:19:15.702 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=com.huawei.android.action.WIDGET_FOCUS_CHANGE flg=0x10 (has extras) }, receivers: null
02-06 17:19:15.731 D/ActivityThread(21353): ActivityThread,attachApplication
02-06 17:19:15.732 D/ActivityManager( 4261): ActivityManagerService,attachApplication,callingPid = 21353
02-06 17:19:15.733 V/ActivityManager( 4261): New app record ProcessRecord{da76e66 21353:0:com.highlight.mjhb/u0a103} thread=android.os.BinderProxy@cd145a7 pid=21353
02-06 17:19:15.742 I/[Gralloc]( 3709): alloc w[1080] h[1920] format[1] usage[2867]
02-06 17:19:15.742 I/[Gralloc]( 3709): alloc w[1080] h[1920] format[1] usage[3]
02-06 17:19:15.742 I/[Gralloc]( 3709): alloc succ handle[0xb77ad438] stride[1120]
02-06 17:19:15.750 I/[Gralloc]( 3709): alloc succ handle[0xb78c19f8] stride[1120]
02-06 17:19:15.750 W/[Gralloc-Warning]( 3709): int gralloc_register_buffer(const gralloc_module_t*, buffer_handle_t):66 Registering handle 0xb78ca418 coming from the same process: 3709.
02-06 17:19:15.763 E/Parcel  ( 3937): Reading a NULL string not supported here.
02-06 17:19:15.763 E/Parcel  ( 3937): Reading a NULL string not supported here.
02-06 17:19:15.768 D/SurfaceFlinger( 3709): disp:0 orientation:1, transformIndex:4
02-06 17:19:15.768 D/SurfaceFlinger( 3709): HWComposer setTransformChanged transformIndex is 4
02-06 17:19:15.769 I/ActivityManager( 4261): Config changes=480 {1.0 460mcc65535mnc zh_CN ldltr sw360dp w598dp h336dp 480dpi nrml land finger -keyb/v/h dpad/v suim:1 s.14}
02-06 17:19:15.786 I/InputReader( 4261): Reconfiguring input devices.  changes=0x00000004
02-06 17:19:15.786 I/InputReader( 4261): Device reconfigured: id=2, name='huawei,touchscreen', size 1080x1920, orientation 1, mode 1, display id 0
02-06 17:19:15.798 I/HwSystemManager( 8292): HsmPackageManager:onConfigureChanged: zh_CN
02-06 17:19:15.816 W/Settings( 6056): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
02-06 17:19:15.817 D/STK App ( 6056): isStkLauncherAvailable() slotId = 0, mUiccCardAvailableArray[slotId]false, isAirplaneModeOn = false
02-06 17:19:15.844 I/HwSystemManager( 5231): HsmPackageManager:onConfigureChanged: zh_CN
02-06 17:19:15.850 D/STK App ( 6056): slotId = 0, showMode = ALWAYS_SHOW, install
02-06 17:19:15.872 D/CubicBezierInterpolator( 4891): CubicBezierInterpolator  mControlPoint1x = 0.15, mControlPoint1y = 0.7, mControlPoint2x = 0.2, mControlPoint2y = 0.98
02-06 17:19:15.873 D/CubicBezierInterpolator( 4891): CubicBezierInterpolator  mControlPoint1x = 0.6, mControlPoint1y = 0.9, mControlPoint2x = 0.8, mControlPoint2y = 1.0
02-06 17:19:15.873 D/CubicBezierInterpolator( 4891): CubicBezierInterpolator  mControlPoint1x = 0.15, mControlPoint1y = 0.7, mControlPoint2x = 0.2, mControlPoint2y = 0.98
02-06 17:19:15.873 D/CubicBezierInterpolator( 4891): CubicBezierInterpolator  mControlPoint1x = 0.6, mControlPoint1y = 0.9, mControlPoint2x = 0.8, mControlPoint2y = 1.0
02-06 17:19:15.874 I/ActivityManager( 4261): launch r: ActivityRecord{fe37b8e u0 com.highlight.mjhb/.CCXGame t24013}, uid = 10103, r.info.applicationInfo.euid  = 0
02-06 17:19:15.875 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:15.875 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimProcessPackageResume: cost time 0 ms end.
02-06 17:19:15.879 D/Tethering( 4261): StateReceiver onReceive action:android.intent.action.CONFIGURATION_CHANGED
02-06 17:19:15.885 I/[Gralloc]( 3709): alloc w[16] h[16] format[1] usage[256]
02-06 17:19:15.885 D/Tethering( 4261): upstreamIfaceTypes.add:0
02-06 17:19:15.885 D/Tethering( 4261): upstreamIfaceTypes.add:1
02-06 17:19:15.885 D/Tethering( 4261): upstreamIfaceTypes.add:5
02-06 17:19:15.885 D/Tethering( 4261): upstreamIfaceTypes.add:7
02-06 17:19:15.885 D/Tethering( 4261): upstreamIfaceTypes.add:9
02-06 17:19:15.886 I/HwLauncher( 6100): Workspace onSizeChanged
02-06 17:19:15.889 I/[Gralloc]( 3709): alloc succ handle[0xb7815908] stride[32]
02-06 17:19:15.891 E/linker  (21353): readlink('/proc/self/fd/21') failed: Permission denied [fd=21]
02-06 17:19:15.892 E/linker  (21353): warning: unable to get realpath for the library "/system/lib/hw/gralloc.hi3630.so". Will use given name.
02-06 17:19:15.892 I/HwSystemManager( 5231): NotificationGuideService:handle MSG_ACTIVIY_FOREGROUND, uid:10103
02-06 17:19:15.897 W/PGApi_client( 6044): recv actoionId = 10000, action = com.huawei.pgmng.PGAction@b59e01b actionId =10000 pkg =com.highlight.mjhb extend1 =7054 extend2 = flag =3 type =1
02-06 17:19:15.897 W/PGMiddleWare( 6044): in handleAction method, action = 10000
02-06 17:19:15.897 W/PGMiddleWare( 6044): in handleAction, invoke client = com.huawei.pgmng.middleware.AudioEffectLowPowerImpl@ae149d3, action = com.huawei.pgmng.PGAction@b59e01b actionId =10000 pkg =com.highlight.mjhb extend1 =7054 extend2 = flag =3 type =1
02-06 17:19:15.897 V/AudioManager( 6044): isMusicActive...
02-06 17:19:15.898 E/linker  (21353): readlink('/proc/self/fd/21') failed: Permission denied [fd=21]
02-06 17:19:15.898 E/linker  (21353): warning: unable to get realpath for the library "libion.so". Will use given name.
02-06 17:19:15.900 D/        ( 4261): isSystemBootComplete =true
02-06 17:19:15.900 E/HAL     (21353): load: id=gralloc != hmi->id=gralloc
02-06 17:19:15.904 D/        ( 4261):  type:1 subId = 0
02-06 17:19:15.906 D/        ( 4261):  operator:46000
02-06 17:19:15.908 D/HwCust  (21353): Create obj success use class android.content.res.HwCustHwResourcesImpl
02-06 17:19:15.915 I/HwLauncher( 6100): FolderEditText inputMehtod changed lastSoftInputHight=948 r=Rect(0, 0 - 1794, 1080)
02-06 17:19:15.917 I/HwLauncher( 6100): FolderEditText inputMehtod changed lastSoftInputHight=948 r=Rect(0, 0 - 1794, 1080)
02-06 17:19:15.917 D/PhoneStatusBar/NavigationBarView( 4891): layoutId: 4, containsKey: true
02-06 17:19:15.919 D/BarTransitions.NavigationBarView( 4891): MODE_TRANSLUCENT -> MODE_TRANSLUCENT animate=false
02-06 17:19:15.919 D/BarTransitions.NavigationBarView( 4891): applyModeBackground MODE_TRANSLUCENT animate=false,mGradientBackground=true
02-06 17:19:15.919 D/PhoneStatusBar/NavigationBarView( 4891): setDisabledFlags home button, disableHome:false,disableSearch:false
02-06 17:19:15.920 D/PhoneStatusBar/NavigationBarView( 4891): setDisabledFlags home button, disableHome:false,disableSearch:false
02-06 17:19:15.920 D/TintManager( 4891): updateBarTint
02-06 17:19:15.965 D/PhoneStatusBar( 4891): mode=default, land=true, topMargin=726, leftMargin=78, height=621
02-06 17:19:15.966 D/PhoneStatusBar( 4891): mode=default, land=true, height=906
02-06 17:19:15.971 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:15.971 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimAddProcessRelation: cost 0 ms end.
02-06 17:19:15.976 D/ImageWallpaper( 4891): onSurfaceRedrawNeeded(holder:android.service.wallpaper.WallpaperService$Engine$1@d3a373e)
02-06 17:19:15.976 D/ImageWallpaper( 4891): Reloading bitmap: mBackground, bgw, bgh, dw, dh = null, 0, 0, 2160, 1920
02-06 17:19:15.982 D/main    (21353): ---JNI_OnLoad---
02-06 17:19:15.982 I/HwLauncher( 6100): Model  onReceive intent=Intent { act=android.intent.action.CONFIGURATION_CHANGED flg=0x70000010 }
02-06 17:19:15.983 I/HwLauncher( 6100): Model  onReceive user=UserHandle{0}
02-06 17:19:15.984 D/ImageWallpaper( 4891): onOffsetsChanged: xOffset=0.0, yOffset=0.0, xOffsetStep=0.0, yOffsetStep=0.0, xPixels=0, yPixels=0
02-06 17:19:15.985 I/HwLauncher( 6100): Launcher.Utilities updateOrientToPortrait original orientation = 2
02-06 17:19:15.985 I/HwLauncher( 6100): Launcher.Utilities updateOrientToPortrait: update configuration to portrait
02-06 17:19:15.986 I/HwLauncher( 6100): Launcher.Settings  updateIconTitleSize fontSize = 13.0
02-06 17:19:15.986 D/HwLauncher( 6100): Launcher.Settings  updateIconTitleSize before fontSize: 13.0
02-06 17:19:15.986 D/HwLauncher( 6100): Launcher.Settings  updateIconTitleSize after fontSize: 39.0
02-06 17:19:15.986 V/HwPolicyFactory(21353): : success to get AllImpl object and return....
02-06 17:19:15.989 I/PanelView( 4891): Configuration orientation changed
02-06 17:19:15.992 I/HwCust  (21353): Constructor found for class android.app.HwCustHwWallpaperManagerImpl
02-06 17:19:15.993 D/HwCust  (21353): Create obj success use class android.app.HwCustHwWallpaperManagerImpl
02-06 17:19:15.993 V/HwWidgetFactory(21353): : successes to get AllImpl object and return....
02-06 17:19:15.995 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:15.996 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimAddProcessRelation: cost 1 ms end.
02-06 17:19:16.005 D/ToolboxContentView( 4891): update ToolBox when the Configuration is changed.
02-06 17:19:16.008 I/SendBroadcastPermission( 5961): action:com.tencent.qqpinyin.exp_data_change, mPermissionType:0
02-06 17:19:16.065 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=com.tencent.qqpinyin.exp_data_change flg=0x10 }, receivers: null
02-06 17:19:16.068 V/ActivityThread(21353): ActivityThread,callActivityOnCreate
02-06 17:19:16.070 V/xgame   (21353): ### memory:643289088  -  613
02-06 17:19:16.071 V/xgame   (21353): ### isMemoryAvailable: true
02-06 17:19:16.094 D/ImageWallpaper( 4891): onVisibilityChanged: mVisible, visible=true, false
02-06 17:19:16.095 D/NetworkController.MobileSignalController(0)( 4891):  mDataNetType:17 indexOfkey:14 iconGroup.mName:TDS roaming:false
02-06 17:19:16.097 D/PhoneStatusBar( 4891): mSettingsPanelGravity = 55
02-06 17:19:16.102 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 0
02-06 17:19:16.109 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 1
02-06 17:19:16.111 D/HwCust  (  855): Create obj success use class android.app.HwCustNotificationImpl
02-06 17:19:16.118 D/PhoneStatusBar/NavigationBarView( 4891): layoutId: 4, containsKey: true
02-06 17:19:16.119 D/BarTransitions.NavigationBarView( 4891): MODE_TRANSLUCENT -> MODE_TRANSLUCENT animate=false
02-06 17:19:16.119 D/BarTransitions.NavigationBarView( 4891): applyModeBackground MODE_TRANSLUCENT animate=false,mGradientBackground=true
02-06 17:19:16.119 D/PhoneStatusBar/NavigationBarView( 4891): setDisabledFlags home button, disableHome:false,disableSearch:false
02-06 17:19:16.119 D/PhoneStatusBar/NavigationBarView( 4891): setDisabledFlags home button, disableHome:false,disableSearch:false
02-06 17:19:16.120 D/TintManager( 4891): updateBarTint
02-06 17:19:16.138 I/art     ( 4891): Background partial concurrent mark sweep GC freed 100503(5MB) AllocSpace objects, 80(4MB) LOS objects, 24% free, 48MB/64MB, paused 853us total 145.946ms
02-06 17:19:16.153 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{1bc54c2 855:0:com.tencent.mtt:service/u0a101} is not a cloned process
02-06 17:19:16.172 I/TimeManager( 4891): receiver action = android.intent.action.CONFIGURATION_CHANGED
02-06 17:19:16.173 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{1bc54c2 855:0:com.tencent.mtt:service/u0a101} is not a cloned process
02-06 17:19:16.177 D/HwWallpaperManager( 4891): Parse offsets:-1,-1,-1,-1
02-06 17:19:16.179 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:16.179 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimAddProcessRelation: cost 0 ms end.
02-06 17:19:16.197 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:16.197 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimAddProcessRelation: cost 1 ms end.
02-06 17:19:16.202 D/mali_winsys( 4891): new_window_surface returns 0x3000
02-06 17:19:16.203 D/PhoneStatusBar/NavigationBarView( 4891): layoutId: 4, containsKey: true
02-06 17:19:16.203 I/UsageStatsService( 4261): reportEvent Informing listeners of out-of-idle com.highlight.mjhb,previouslyIdle:true
02-06 17:19:16.204 D/BarTransitions.NavigationBarView( 4891): MODE_TRANSLUCENT -> MODE_VERTICAL animate=false
02-06 17:19:16.204 D/BarTransitions.NavigationBarView( 4891): applyModeBackground MODE_VERTICAL animate=false,mGradientBackground=true
02-06 17:19:16.204 D/BarTransitions.NavigationBarView( 4891): Show color layer
02-06 17:19:16.204 D/BarTransitions.NavigationBarView( 4891): applyModeBackground MODE_VERTICAL animate=false,mGradientBackground=true
02-06 17:19:16.204 D/PhoneStatusBar/NavigationBarView( 4891): setDisabledFlags home button, disableHome:false,disableSearch:false
02-06 17:19:16.204 D/PhoneStatusBar/NavigationBarView( 4891): setDisabledFlags home button, disableHome:false,disableSearch:false
02-06 17:19:16.205 D/TintManager( 4891): updateBarTint
02-06 17:19:16.213 I/[Gralloc]( 3709): alloc w[1080] h[126] format[1] usage[2816]
02-06 17:19:16.216 I/[Gralloc]( 3709): alloc succ handle[0xb7876740] stride[1120]
02-06 17:19:16.220 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:16.220 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimAddProcessRelation: cost 0 ms end.
02-06 17:19:16.230 V/SMCSAMSHelper( 4261): SMCSAMSHelper.addSTPEvent: cost 0 ms end.
02-06 17:19:16.230 V/SMCSAMSHelper( 4261): SMCSAMSHelper.smartTrimAddProcessRelation: cost 0 ms end.
02-06 17:19:16.254 D/mali_winsys( 4891): new_window_surface returns 0x3000
02-06 17:19:16.254 I/HwWallpaperService( 4261): setCurrOffsets:420,0,0,420
02-06 17:19:16.254 D/ImageWallpaper( 4891): not a rregular bitmap, get it from mWallpaperManager, size:(1920,1920)
02-06 17:19:16.257 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{1bc54c2 855:0:com.tencent.mtt:service/u0a101} is not a cloned process
02-06 17:19:16.257 I/HwWallpaperService( 4261): getCurrOffsets(0):420,0,0,420
02-06 17:19:16.258 D/ImageWallpaper( 4891): getCurrOffsets:420,0,0,420
02-06 17:19:16.258 D/ImageWallpaper( 4891): Surface != bitmap dimensions: surface w/h, bitmap w/h: 2160, 1920, 1920, 1920
02-06 17:19:16.261 W/View    ( 4891): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{4ddd600 V.E...... ......ID 0,0-270,72 #7f1000c3 app:id/notificationIcons} during layout: running second layout pass
02-06 17:19:16.273 I/art     ( 4261): Background partial concurrent mark sweep GC freed 136731(8MB) AllocSpace objects, 52(1488KB) LOS objects, 22% free, 53MB/69MB, paused 3.114ms total 276.628ms
02-06 17:19:16.281 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{1bc54c2 855:0:com.tencent.mtt:service/u0a101} is not a cloned process
02-06 17:19:16.283 V/NotificationService( 4261): notifications are disabled by AppOps for com.tencent.mtt
02-06 17:19:16.283 E/NotificationService( 4261): Suppressing notification from package com.tencent.mtt by user request.
02-06 17:19:16.285 I/HwWindowManagerService( 4261): setAppOrientation token: Token{1550faf ActivityRecord{fe37b8e u0 com.highlight.mjhb/.CCXGame t24013}} requestedOrientation: 6
02-06 17:19:16.286 D/HWExtDeviceManager( 4261): motion DeviceEventQueue mDeviceHandler: Handler (com.huawei.hwextdevice.HWExtDeviceManager$DeviceEventQueue$HWExtDeviceHandler) {aa35533}
02-06 17:19:16.286 D/        ( 4261): ALOGD: HWExtDeviceManager::enableDevice 1 ... 
02-06 17:19:16.286 D/        ( 4261): ALOGD: HWExtDeviceService::addActiveRecord add connection sucessed connSize: 2 
02-06 17:19:16.286 D/        ( 4261): MotionHubChannel startMotionReco: 7
02-06 17:19:16.286 D/        ( 4261): ALOGD: HWExtDeviceService::enableDevice add record: 2 
02-06 17:19:16.291 I/[Gralloc]( 3709): alloc w[72] h[1920] format[1] usage[2816]
02-06 17:19:16.293 I/[Gralloc]( 3709): alloc succ handle[0xb7709cd8] stride[96]
02-06 17:19:16.307 D/HWEMRP  ( 4261): onDeviceDataChanged  proposedRotation:-1
02-06 17:19:16.307 D/HWEMRP  ( 4261): onDeviceDataChanged  oldProposedRotation:0
02-06 17:19:16.350 V/AudioManager( 4891): getStreamVolume  treamType: 3
02-06 17:19:16.362 V/AudioManager( 4891): isStreamMute   streamType: 3
02-06 17:19:16.379 V/AudioManager( 4891): getStreamVolume  treamType: 2
02-06 17:19:16.381 V/AudioManager( 4891): isStreamMute   streamType: 2
02-06 17:19:16.383 D/HwImageWallpaper( 4891): resultMap.get(KEY_AVG_COLOR):2 resultMap.get(KEY_USE_COVER):1
02-06 17:19:16.384 V/AudioManager( 4891): getRingerMode...
02-06 17:19:16.384 V/AudioManager( 4891): getStreamVolume  treamType: 4
02-06 17:19:16.385 V/AudioManager( 4891): isStreamMute   streamType: 4
02-06 17:19:16.387 W/FileUtils( 4261): Failed to chmod(/data/share): android.system.ErrnoException: chmod failed: EPERM (Operation not permitted)
02-06 17:19:16.388 V/AudioManager( 4891): getStreamVolume  treamType: 0
02-06 17:19:16.389 V/AudioManager( 4891): isStreamMute   streamType: 0
02-06 17:19:16.399 D/HwCust  ( 4261): Create obj success use class android.content.res.HwCustHwResourcesImpl
02-06 17:19:16.403 D/HwImageWallpaper( 4891): getLayerBitmap
02-06 17:19:16.414 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.428 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.430 I/[Gralloc]( 3709): alloc w[1080] h[126] format[1] usage[2816]
02-06 17:19:16.434 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 0
02-06 17:19:16.435 I/[Gralloc]( 3709): alloc succ handle[0xb77ae2a8] stride[1120]
02-06 17:19:16.436 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.439 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.442 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 1
02-06 17:19:16.444 W/View    ( 4891): requestLayout() improperly called by com.android.systemui.statusbar.phone.IconMerger{4ddd600 V.E...... ........ 0,0-270,72 #7f1000c3 app:id/notificationIcons} during second layout pass: posting in next frame
02-06 17:19:16.445 I/[Gralloc]( 3709): alloc w[72] h[1920] format[1] usage[2816]
02-06 17:19:16.448 I/[Gralloc]( 3709): alloc succ handle[0xb77b6de8] stride[96]
02-06 17:19:16.450 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 0
02-06 17:19:16.452 D/mali_winsys( 4891): new_window_surface returns 0x3000
02-06 17:19:16.458 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 1
02-06 17:19:16.468 I/System.out(21353): [/system/bin/sh, -c, getprop ro.board.platform]
02-06 17:19:16.468 I/System.out(21353): null
02-06 17:19:16.468 I/System.out(21353): null
02-06 17:19:16.468 I/SendBroadcastPermission( 4891): action:com.android.systemui.ACTION_WALLPAPER_USE_MASK, mPermissionType:0
02-06 17:19:16.469 I/System.out(21353): Calling by::className:com.tencent.bugly.proguard.a  MethodName:a
02-06 17:19:16.469 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=com.android.systemui.ACTION_WALLPAPER_USE_MASK flg=0x10 pkg=com.huawei.android.launcher (has extras) }, receivers: null
02-06 17:19:16.493 I/CrashReport(21353): native library loaded
02-06 17:19:16.493 I/CrashReport(21353): backup java method success
02-06 17:19:16.493 I/CrashReport(21353): back up java classes success
02-06 17:19:16.505 I/CrashReport(21353): base = 0xbe021000
02-06 17:19:16.505 I/CrashReport(21353): stacksize = 8M
02-06 17:19:16.505 I/CrashReport(21353): guardsize = 0
02-06 17:19:16.508 I/CrashReport(21353): getted buglyline com/tencent/bugly/crashreport/
02-06 17:19:16.508 I/CrashReport(21353): it is default prefix
02-06 17:19:16.509 I/CrashReport(21353): register native log methods success
02-06 17:19:16.509 I/CrashReport(21353): register native key-value methods success
02-06 17:19:16.509 I/CrashReport(21353): register native methods success
02-06 17:19:16.509 I/CrashReport(21353): setLogMode 6 current 4
02-06 17:19:16.514 E/Thermal-daemon( 3725): [flash_led] temp_new :30  temp_old :29
02-06 17:19:16.514 E/Thermal-daemon( 3725): Report temperature: [flash_led] temp :30  report_threshold:1
02-06 17:19:16.519 I/[Gralloc]( 3709): alloc w[1920] h[2160] format[2] usage[2816]
02-06 17:19:16.530 D/ThermalStateManager( 6044): Thermal type: 3 cur_temperature:30
02-06 17:19:16.530 I/[Gralloc]( 3709): alloc succ handle[0xb78963f0] stride[1952]
02-06 17:19:16.543 D/ImageWallpaper( 4891): USE_COVER
02-06 17:19:16.544 D/TintManager( 4891): updateBarTint
02-06 17:19:16.546 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.554 D/mali_winsys( 4891): new_window_surface returns 0x3000
02-06 17:19:16.580 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{da76e66 21353:0:com.highlight.mjhb/u0a103} is not a cloned process
02-06 17:19:16.585 I/System.out(21353): [/system/bin/sh, -c, type su]
02-06 17:19:16.585 I/System.out(21353): null
02-06 17:19:16.585 I/System.out(21353): null
02-06 17:19:16.585 I/System.out(21353): Calling by::className:com.tencent.bugly.proguard.a  MethodName:a
02-06 17:19:16.599 I/[Gralloc]( 3709): alloc w[1920] h[2160] format[2] usage[2816]
02-06 17:19:16.611 I/SendBroadcastPermission(21353): action:com.tencent.mm.plugin.openapi.Intent.ACTION_HANDLE_APP_REGISTER, mPermissionType:0
02-06 17:19:16.612 I/HwActivityManagerService( 4261): collectReceiverComponents, callerApp: ProcessRecord{da76e66 21353:0:com.highlight.mjhb/u0a103}, flags: 400
02-06 17:19:16.612 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=com.tencent.mm.plugin.openapi.Intent.ACTION_HANDLE_APP_REGISTER flg=0x10 (has extras) }, receivers: [ResolveInfo{bb4118f com.tencent.mm/.plugin.base.stub.WXEntryActivity$EntryReceiver m=0x108000 euid=0}]
02-06 17:19:16.617 D/SensorHub( 4261): Channel activate-> handle: 4, enabled:1, err: 0
02-06 17:19:16.617 E/SensorHub( 4261): PS activate 1
02-06 17:19:16.617 D/SensorHub( 4261): Channel setDelay-> handle: 4, ns:200000000, err: 0
02-06 17:19:16.618 I/[Gralloc]( 3709): alloc succ handle[0xb785d890] stride[1952]
02-06 17:19:16.637 V/CCXGame (21353): [processLocation]clear data
02-06 17:19:16.638 V/CCXGame (21353): latitude=0.000000,longitude=0.000000
02-06 17:19:16.643 D/ImageWallpaper( 4891): Suppressed drawFrame since redraw is not needed and offsets have not changed. rotation new/old: 1/1, width new/old: 2160/2160, height new/old: 1920/1920, offsetChanged: false
02-06 17:19:16.643 D/ImageWallpaper( 4891): Suppressed drawFrame since redraw is not needed and offsets have not changed. rotation new/old: 1/1, width new/old: 2160/2160, height new/old: 1920/1920, offsetChanged: false
02-06 17:19:16.646 D/WifiManager(21353): Enter init, sThreadRefCount:0
02-06 17:19:16.646 D/WifiService( 4261): getWifiServiceMessenger, pid:21353, uid:10103
02-06 17:19:16.646 D/WifiManager(21353): Create WifiManager handlerthread
02-06 17:19:16.649 D/WifiService( 4261): New client listening to asynchronous messages
02-06 17:19:16.650 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.656 I/WindowBlurViewManager( 4891): allowChangeBlurBackground
02-06 17:19:16.657 I/WindowBlurViewManager( 4891): setBlurBackground()
02-06 17:19:16.662 D/HwCust  (23620): Create obj success use class android.content.res.HwCustHwResourcesImpl
02-06 17:19:16.667 I/[Gralloc]( 3709): alloc w[134] h[240] format[1] usage[819]
02-06 17:19:16.669 I/[Gralloc]( 3709): alloc succ handle[0xb78a5968] stride[160]
02-06 17:19:16.671 I/K3V3CpuGovernorPolicy( 6044): close previously scene Hmp policy : 300 , 150
02-06 17:19:16.673 D/HwSensorManager(21353): HwSensorManager version: 1.0.0
02-06 17:19:16.699 D/CubicBezierInterpolator(21353): CubicBezierInterpolator  mControlPoint1x = 0.15, mControlPoint1y = 0.7, mControlPoint2x = 0.2, mControlPoint2y = 0.98
02-06 17:19:16.700 D/CubicBezierInterpolator(21353): CubicBezierInterpolator  mControlPoint1x = 0.6, mControlPoint1y = 0.9, mControlPoint2x = 0.8, mControlPoint2y = 1.0
02-06 17:19:16.700 D/CubicBezierInterpolator(21353): CubicBezierInterpolator  mControlPoint1x = 0.15, mControlPoint1y = 0.7, mControlPoint2x = 0.2, mControlPoint2y = 0.98
02-06 17:19:16.701 D/CubicBezierInterpolator(21353): CubicBezierInterpolator  mControlPoint1x = 0.6, mControlPoint1y = 0.9, mControlPoint2x = 0.8, mControlPoint2y = 1.0
02-06 17:19:16.719 I/System  (21353): core_booster, getBoosterConfig = false
02-06 17:19:16.719 D/WindowBlur( 4891): similitudeRate = 1980
02-06 17:19:16.730 D/WindowBlur( 4891): notifyBlurResult bitmap = android.graphics.Bitmap@e6ef2ff
02-06 17:19:16.753 D/OpenGLRenderer(21353): Use EGL_SWAP_BEHAVIOR_PRESERVED: false
02-06 17:19:16.763 D/PhoneStatusBar( 4891): setSystemUiVisibility vis=c0000000 mask=ffffffff oldVal=c0000700 newVal=c0000000 diff=700
02-06 17:19:16.764 D/PhoneStatusBar( 4891): sbMode=-1, nbMode=-1mStatusBarMode=2, mNavigationBarMode=2
02-06 17:19:16.764 D/BarTransitions.PhoneStatusBarView( 4891): MODE_TRANSLUCENT -> MODE_TRANSLUCENT animate=false
02-06 17:19:16.764 D/BarTransitions.NavigationBarView( 4891): MODE_VERTICAL -> MODE_VERTICAL animate=false
02-06 17:19:16.764 D/TintManager( 4891): updateBarTint
02-06 17:19:16.768 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 0
02-06 17:19:16.774 I/HwWindowManagerService( 4261): setAppOrientation token: Token{1550faf ActivityRecord{fe37b8e u0 com.highlight.mjhb/.CCXGame t24013}} requestedOrientation: 0
02-06 17:19:16.775 D/        ( 4261): MotionHubChannel stopMotionReco: 7
02-06 17:19:16.777 V/MicroMsg.SDK.WXApiImplV10.ActivityLifecycleCb(21353): com.highlight.mjhb.CCXGame  onActivityResumed
02-06 17:19:16.778 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10103cmd = 1
02-06 17:19:16.779 V/xgame   (21353): -----message_activity#onResume:
02-06 17:19:16.784 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.784 V/HwPhoneWindowManager( 4261): updateSystemUiColorLw window=Window{b2cf2b4 u0 com.highlight.mjhb/com.highlight.mjhb.CCXGame},EmuiStyle=0,StatusBarColor=0xff000000,NavigationBarColor=0xff000000
02-06 17:19:16.784 D/HwPhoneWindowManager( 4261): Transact:setSystemUIColor to status bar service
02-06 17:19:16.785 D/CommandQueue( 4891): CommandQueue, onTransaction
02-06 17:19:16.785 D/CommandQueue( 4891): CommandQueue, setBarBackgroundColor
02-06 17:19:16.787 D/TintManager( 4891): isEmuiStyle=0, statusBarColor=ff000000, navigationColor=ff000000
02-06 17:19:16.787 D/TintManager( 4891): updateBarBgColor:emuiStyle=0,statusBarColor=#FF000000,navigationBarColor=#FF000000
02-06 17:19:16.787 D/BarTransitions.PhoneStatusBarView( 4891): setUseGradientBackground: true
02-06 17:19:16.787 D/BarTransitions.NavigationBarView( 4891): setUseGradientBackground: true
02-06 17:19:16.788 D/TintManager( 4891): statusBarIconTint=#FFFFFFFF,navigationBarIconTint=#FF000000
02-06 17:19:16.788 D/TintManager( 4891): updateBarTint
02-06 17:19:16.805 I/PhoneStateManager( 6044): camera pkg and front pkg not same,so don't think camera front: com.tencent.mm, com.highlight.mjhb
02-06 17:19:16.849 I/MID     (21353): read mid from InternalStorage
02-06 17:19:16.853 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{da76e66 21353:0:com.highlight.mjhb/u0a103} is not a cloned process
02-06 17:19:16.856 I/MID     (21353): read mid from InternalStorage:xjgD6zAYj0803BWH1ZxB6HaRKZR36Xm8SnAJpFaX3/5iIEVmiePXhrE0ST77HnIJQUN0x+dWSUxqE35OrA6HZwBZn61suZDBULT0ESXztup/pqJPdNEzVExioXIfQxB4IAZox+SCzb5dP145wU+AYWWkMUbu
02-06 17:19:16.865 E/HAL     (21353): load: id=gralloc != hmi->id=gralloc
02-06 17:19:16.865 I/OpenGLRenderer(21353): Initialized EGL, version 1.4
02-06 17:19:16.872 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{da76e66 21353:0:com.highlight.mjhb/u0a103} is not a cloned process
02-06 17:19:16.877 E/linker  (21353): readlink('/proc/self/fd/39') failed: Permission denied [fd=39]
02-06 17:19:16.877 E/linker  (21353): warning: unable to get realpath for the library "libhwaps.so". Will use given name.
02-06 17:19:16.904 E/linker  (21353): readlink('/proc/self/fd/45') failed: Permission denied [fd=45]
02-06 17:19:16.904 E/linker  (21353): warning: unable to get realpath for the library "/system/lib/libhwuibp.so". Will use given name.
02-06 17:19:16.917 D/OpenGLRenderer(21353): loaded so path=/system/lib/libhwuibp.so handle=0xb30dad04
02-06 17:19:16.922 D/mali_winsys(21353): new_window_surface returns 0x3000
02-06 17:19:16.922 I/[Gralloc]( 3709): alloc w[1048] h[422] format[1] usage[2816]
02-06 17:19:16.927 I/[Gralloc]( 3709): alloc succ handle[0xb78b0f38] stride[1056]
02-06 17:19:16.927 I/[Gralloc]( 3709): alloc w[1048] h[422] format[1] usage[2816]
02-06 17:19:16.930 I/[Gralloc]( 3709): alloc succ handle[0xb7843dd8] stride[1056]
02-06 17:19:16.931 I/[Gralloc]( 3709): alloc w[1048] h[422] format[1] usage[2816]
02-06 17:19:16.934 I/[Gralloc]( 3709): alloc succ handle[0xb77ae090] stride[1056]
02-06 17:19:16.962 D/SensorHub( 4261): -------------------------->SENSOR_TYPE_PROXIMITY data[0] = 5.000000
02-06 17:19:16.963 D/mali_winsys(21353): new_window_surface returns 0x3000
02-06 17:19:16.973 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.975 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.984 W/ActivityManager( 4261): getRunningAppProcesses: caller 10103 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:16.989 D/mali_winsys(21353): new_window_surface returns 0x3000
02-06 17:19:16.990 D/main    (21353): ---Java_org_cocos2dx_lib_Cocos2dxRenderer_nativeInit---w=1794,h=1080
02-06 17:19:16.993 D/cocos2d-x debug info(21353): dumpInfo(92)
02-06 17:19:16.993 D/cocos2d-x debug info(21353): <dict>
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	cocos2d.x.version: cocos2d-x 2.2.6
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	cocos2d.x.compiled_with_profiler: false
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	cocos2d.x.compiled_with_gl_state_cache: true
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.vendor: ARM
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.renderer: Mali-T624
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.version: OpenGL ES 3.1 v1.r8p0-01dev0.89305006046df295a29af63abd09cd0b
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.max_texture_size: 8192
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.max_texture_units: 96
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.supports_PVRTC: false
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.supports_NPOT: true
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.supports_BGRA8888: false
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.supports_discard_framebuffer: true
02-06 17:19:16.993 D/cocos2d-x debug info(21353): 	gl.supports_vertex_array_object: true
02-06 17:19:16.993 D/cocos2d-x debug info(21353): </dict>
02-06 17:19:17.009 D/mali_winsys(21353): new_window_surface returns 0x3000
02-06 17:19:17.009 I/System  (21353): core_booster, getBoosterConfig = false
02-06 17:19:17.010 I/[Gralloc]( 3709): alloc w[332] h[166] format[1] usage[2816]
02-06 17:19:17.011 I/[Gralloc]( 3709): alloc succ handle[0xb7880e90] stride[352]
02-06 17:19:17.011 I/[Gralloc]( 3709): alloc w[332] h[166] format[1] usage[2816]
02-06 17:19:17.013 I/[Gralloc]( 3709): alloc succ handle[0xb78cd900] stride[352]
02-06 17:19:17.013 I/[Gralloc]( 3709): alloc w[332] h[166] format[1] usage[2816]
02-06 17:19:17.014 I/[Gralloc]( 3709): alloc succ handle[0xb78ff8e8] stride[352]
02-06 17:19:17.032 I/[Gralloc]( 3709): alloc w[422] h[1048] format[1] usage[2816]
02-06 17:19:17.035 I/[Gralloc]( 3709): alloc succ handle[0xb78c5778] stride[480]
02-06 17:19:17.072 I/[Gralloc]( 3709): alloc w[1080] h[1794] format[1] usage[2816]
02-06 17:19:17.077 I/[Gralloc]( 3709): alloc succ handle[0xb78622a0] stride[1120]
02-06 17:19:17.086 I/[Gralloc]( 3709): alloc w[166] h[332] format[1] usage[2816]
02-06 17:19:17.088 I/[Gralloc]( 3709): alloc succ handle[0xb78bfe98] stride[224]
02-06 17:19:17.090 D/PhoneStatusBar( 4891): setSystemUiVisibility vis=0 mask=ffffffff oldVal=c0000000 newVal=0 diff=c0000000
02-06 17:19:17.090 D/PhoneStatusBar( 4891): sbMode=0, nbMode=0mStatusBarMode=2, mNavigationBarMode=2
02-06 17:19:17.090 D/BarTransitions.PhoneStatusBarView( 4891): MODE_TRANSLUCENT -> MODE_OPAQUE animate=false
02-06 17:19:17.090 D/BarTransitions.PhoneStatusBarView( 4891): applyModeBackground MODE_OPAQUE animate=false,mGradientBackground=true
02-06 17:19:17.090 D/BarTransitions.PhoneStatusBarView( 4891): setColor = ff000000
02-06 17:19:17.091 D/BarTransitions.PhoneStatusBarView( 4891): Show color layer
02-06 17:19:17.091 D/BarTransitions.NavigationBarView( 4891): MODE_VERTICAL -> MODE_OPAQUE animate=false
02-06 17:19:17.091 D/BarTransitions.NavigationBarView( 4891): applyModeBackground MODE_OPAQUE animate=false,mGradientBackground=true
02-06 17:19:17.091 D/TintManager( 4891): updateBarTint
02-06 17:19:17.097 I/ActivityManager( 4261): Displayed com.highlight.mjhb/.CCXGame: +1s427ms
02-06 17:19:17.114 I/SendBroadcastPermission( 4891): action:com.huawei.eassistant.action.NOTIFYCATION_BAR, mPermissionType:0
02-06 17:19:17.115 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=com.huawei.eassistant.action.NOTIFYCATION_BAR flg=0x10 (has extras) }, receivers: null
02-06 17:19:17.129 I/HwLauncher( 6100): Launcher mUnlockScreenRunnbale  getOrientationEnabled false 
02-06 17:19:17.130 I/HwLauncher( 6100): Launcher onStop()
02-06 17:19:17.133 I/HwMtmBroadcastResourceManager( 4261): removeReceiver mtm Broadcast
02-06 17:19:17.134 I/HwMtmBroadcastResourceManager( 4261): removeReceiver mtm Broadcast
02-06 17:19:17.135 I/HwMtmBroadcastResourceManager( 4261): removeReceiver mtm Broadcast
02-06 17:19:17.143 I/WindowManager( 4261): Screen frozen for +1s408ms due to Window{b2cf2b4 u0 com.highlight.mjhb/com.highlight.mjhb.CCXGame}
02-06 17:19:17.144 W/FileUtils( 4261): Failed to chmod(/data/share): android.system.ErrnoException: chmod failed: EPERM (Operation not permitted)
02-06 17:19:17.146 D/HwCust  ( 4261): Create obj success use class android.content.res.HwCustHwResourcesImpl
02-06 17:19:17.148 D/cocos2d-x debug info(21353): CGameGlobal(359)CGameGlobal() 111111
02-06 17:19:17.156 D/CubicBezierInterpolator( 4261): CubicBezierInterpolator  mControlPoint1x = 0.5, mControlPoint1y = 0.15, mControlPoint2x = 0.55, mControlPoint2y = 0.95
02-06 17:19:17.157 D/CubicBezierInterpolator( 4261): CubicBezierInterpolator  mControlPoint1x = 0.5, mControlPoint1y = 0.15, mControlPoint2x = 0.55, mControlPoint2y = 0.95
02-06 17:19:17.161 D/cocos2d-x debug info(21353): CGameGlobal(395)CGameGlobal() 111112
02-06 17:19:17.161 D/cocos2d-x debug info(21353): appLoadVersionFile(301)appSavVersionFile_path->/data/user/0/com.highlight.mjhb/files//game_ver.dat
02-06 17:19:17.255 D/SensorHub( 4261): -------------------------->SENSOR_TYPE_PROXIMITY data[0] = 5.000000
02-06 17:19:17.306 I/native_eup(20597): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler2 start
02-06 17:19:17.306 I/native_eup(20597): JARJNIVERSION:1
02-06 17:19:17.306 I/native_eup(20597): found native exception upload!
02-06 17:19:17.306 I/native_eup(20597): found native exception handler!
02-06 17:19:17.306 I/native_eup(20597): regist handler start procType 1 , level 23 , tombDir:/data/user/0/com.tencent.mobileqq/app_tombs
02-06 17:19:17.306 I/native_eup(20597): registSignal start
02-06 17:19:17.306 I/native_eup(20597): registSignal end
02-06 17:19:17.306 I/native_eup(20597): regist handler end
02-06 17:19:17.306 I/native_eup(20597): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler end
02-06 17:19:17.306 I/native_eup(20597): NativeRQDVersion:testbuildnum
02-06 17:19:17.306 I/native_eup(20597): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler2 start
02-06 17:19:17.306 I/native_eup(20597): JARJNIVERSION:0
02-06 17:19:17.306 I/native_eup(20597): found native exception upload!
02-06 17:19:17.306 I/native_eup(20597): found native exception handler!
02-06 17:19:17.306 I/native_eup(20597): regist handler start procType 1 , level 23 , tombDir:/data/user/0/com.tencent.mobileqq/app_tombs
02-06 17:19:17.306 I/native_eup(20597): registSignal start
02-06 17:19:17.306 I/native_eup(20597): registSignal end
02-06 17:19:17.306 I/native_eup(20597): regist handler end
02-06 17:19:17.306 I/native_eup(20597): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler end
02-06 17:19:17.306 I/native_eup(20597): NativeRQDVersion:testbuildnum
02-06 17:19:17.399 I/native_eup(20671): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler2 start
02-06 17:19:17.399 I/native_eup(20671): JARJNIVERSION:1
02-06 17:19:17.399 I/native_eup(20671): found native exception upload!
02-06 17:19:17.399 I/native_eup(20671): found native exception handler!
02-06 17:19:17.399 I/native_eup(20671): regist handler start procType 1 , level 23 , tombDir:/data/user/0/com.tencent.mobileqq/app_tombs
02-06 17:19:17.399 I/native_eup(20671): registSignal start
02-06 17:19:17.399 I/native_eup(20671): registSignal end
02-06 17:19:17.399 I/native_eup(20671): regist handler end
02-06 17:19:17.399 I/native_eup(20671): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler end
02-06 17:19:17.399 I/native_eup(20671): NativeRQDVersion:testbuildnum
02-06 17:19:17.399 I/native_eup(20671): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler2 start
02-06 17:19:17.399 I/native_eup(20671): JARJNIVERSION:0
02-06 17:19:17.399 I/native_eup(20671): found native exception upload!
02-06 17:19:17.399 I/native_eup(20671): found native exception handler!
02-06 17:19:17.399 I/native_eup(20671): regist handler start procType 1 , level 23 , tombDir:/data/user/0/com.tencent.mobileqq/app_tombs
02-06 17:19:17.399 I/native_eup(20671): registSignal start
02-06 17:19:17.399 I/native_eup(20671): registSignal end
02-06 17:19:17.399 I/native_eup(20671): regist handler end
02-06 17:19:17.399 I/native_eup(20671): Java_com_tencent_feedback_eup_jni_NativeExceptionUpload_registNativeExceptionHandler end
02-06 17:19:17.399 I/native_eup(20671): NativeRQDVersion:testbuildnum
02-06 17:19:17.405 D/cocos2d-x debug info(21353): startGameNetWork(659)CGameConnection::startGameNetWork new SocketThread
02-06 17:19:17.405 D/cocos2d-x debug info(21353): SocketThread(58)init mutext
02-06 17:19:17.405 D/cocos2d-x debug info(21353): isServerConfigTypeEnabled(382)isServerConfigTypeEnabled(382):0 return true
02-06 17:19:17.405 D/cocos2d-x debug info(21353): getCurrentServerIp(561)getCurrentServerIp(561):FOUND can use server for 0 115.159.48.163
02-06 17:19:17.405 D/cocos2d-x debug info(21353): getCurrentServerIp(581)getCurrentServerIp(581):switch ip.....to 0
02-06 17:19:17.405 D/cocos2d-x debug info(21353): startGameNetWork(670)CGameConnection::startGameNetWork s_pSocketThread start 115.159.48.163 
02-06 17:19:17.405 D/cocos2d-x debug info(21353): isServerConfigTypeEnabled(382)isServerConfigTypeEnabled(382):0 return true
02-06 17:19:17.405 D/cocos2d-x debug info(21353): getCurrentServerIp(561)getCurrentServerIp(561):FOUND can use server for 0 115.159.48.163
02-06 17:19:17.405 D/cocos2d-x debug info(21353): getCurrentServerIp(581)getCurrentServerIp(581):switch ip.....to 0
02-06 17:19:17.405 D/cocos2d-x debug info(21353): start(133)clear msg list at first
02-06 17:19:17.405 D/cocos2d-x debug info(21353): start(143)clear send msg list at first
02-06 17:19:17.405 D/cocos2d-x debug info(21353): start(157)start socket thread,ip=115.159.48.163, port=17768
02-06 17:19:17.405 D/Device Model(21353): SimpleAudioEngine() - deviceModel = H60-L01
02-06 17:19:17.406 D/cocos2d-x debug info(21353): start_thread(508)ipv4 thred->getServerIp(): 115.159.48.163
02-06 17:19:17.408 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10046cmd = 0
02-06 17:19:17.410 I/AudioFlinger( 3802): acquireWakeLock_l() AudioOut_6 mType: 0 status 0
02-06 17:19:17.410 I/AudioFlinger( 3802): updateWakeLockUids_l() AudioOut_6 mType: 0 status 0
02-06 17:19:17.413 I/MediaPlayer(21353): setDataSource(64, 15738836, 1444876)
02-06 17:19:17.415 I/MediaPlayerFactory( 3802): is mp3 file ret =  0
02-06 17:19:17.415 D/NuPlayer( 3802): hw fadein is disabled!
02-06 17:19:17.416 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10046cmd = 1
02-06 17:19:17.423 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10046cmd = 0
02-06 17:19:17.430 D/HwActivityManagerService( 4261): handleANRFilterFIFO,uid = 10046cmd = 1
02-06 17:19:17.431 V/MediaExtractor( 3802): Autodetected media content as 'audio/mpeg' with confidence 0.20
02-06 17:19:17.432 D/FileSource( 3802): [IsOnlineCache] fileSize:[21465768]
02-06 17:19:17.432 D/FileSource( 3802): [IsOnlineCache] isOnlineCache:[1]
02-06 17:19:17.432 W/MP3Extractor( 3802): [MP3Extractor.cpp:MP3Extractor:419]#, File is Online
02-06 17:19:17.432 D/HwExtendedExtractor( 3802): extended extractor not needed, return default
02-06 17:19:17.434 D/NuPlayerDriver( 3802): notifyListener_l(0xb73025a8), (1, 0, 0)
02-06 17:19:17.434 D/MediaPlayer(21353): Message: MEDIA_PREPARED(1), ext1=0, ext2=0x0
02-06 17:19:17.434 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1107] callback app listenerNotNull=1, send=1
02-06 17:19:17.435 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1111] callback application
02-06 17:19:17.435 D/MediaPlayer(21353): setSubtitleAnchor in MediaPlayer
02-06 17:19:17.435 D/MediaPlayer(21353): setSubtitleAnchor in MediaPlayer
02-06 17:19:17.439 I/System.out(20671): [/system/bin/sh, -c, getprop]
02-06 17:19:17.439 I/System.out(20671): null
02-06 17:19:17.439 I/System.out(20671): null
02-06 17:19:17.439 I/System.out(20671): Calling by::className:com.tencent.bugly.proguard.y  MethodName:a
02-06 17:19:17.443 I/MediaPlayer(21353): [HSM] stayAwake false uid: 10103, pid: 21353
02-06 17:19:17.444 E/HsmCoreServiceImpl( 4261): onTransact in code is: 102
02-06 17:19:17.444 I/MediaProcessHandler( 4261): processOp opType: 1, uid: 10103, pid: 21353
02-06 17:19:17.444 W/MediaProcessHandler( 4261): remove target not exist, maybe the UI process: uid: 10103, pid: 21353
02-06 17:19:17.444 D/NuPlayerDriver( 3802): stop(0xb73025a8)
02-06 17:19:17.444 D/MediaPlayer(21353): Action:stop, CurrentState:MEDIA_PLAYER_STOPPED
02-06 17:19:17.445 D/NuPlayerDriver( 3802): prepareAsync():just change to STATE_PREPARED
02-06 17:19:17.445 D/NuPlayerDriver( 3802): notifyListener_l(0xb73025a8), (1, 0, 0)
02-06 17:19:17.445 D/MediaPlayer(21353): Message: MEDIA_PREPARED(1), ext1=0, ext2=0x0
02-06 17:19:17.445 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1107] callback app listenerNotNull=1, send=1
02-06 17:19:17.445 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1111] callback application
02-06 17:19:17.446 D/NuPlayerDriver( 3802): seekTo(0xb73025a8) 0 ms
02-06 17:19:17.446 D/NuPlayerDriver( 3802): notifyListener_l(0xb73025a8), (7, 0, 0)
02-06 17:19:17.446 I/NuPlayerDriver( 3802): NuPlayerDriver,seekTimeUs: 0
02-06 17:19:17.446 I/NuPlayer( 3802): NuPlayer::canSeek,mSourceFlags = 15 
02-06 17:19:17.447 I/NuPlayer( 3802): NuPlayer::canSeek,mSourceFlags = 15 
02-06 17:19:17.447 D/MediaPlayer(21353): Message: Unknown MediaEventType(7), ext1=0, ext2=0x0
02-06 17:19:17.447 I/GenericSource( 3802): start
02-06 17:19:17.447 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1107] callback app listenerNotNull=1, send=1
02-06 17:19:17.447 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1111] callback application
02-06 17:19:17.447 I/MediaPlayer(21353): [HSM] stayAwake true uid: 10103, pid: 21353
02-06 17:19:17.447 E/HsmCoreServiceImpl( 4261): onTransact in code is: 102
02-06 17:19:17.448 I/MediaProcessHandler( 4261): processOp opType: 0, uid: 10103, pid: 21353
02-06 17:19:17.448 D/NuPlayerDriver( 3802): start(0xb73025a8), state is 4, eos is 0
02-06 17:19:17.448 D/MediaPlayer(21353): Action:start, CurrentState:MEDIA_PLAYER_STARTED
02-06 17:19:17.449 D/cocos2d-x debug info(21353): start_thread(520)connected
02-06 17:19:17.449 I/[Gralloc]( 3709): alloc w[1080] h[1794] format[1] usage[2816]
02-06 17:19:17.454 W/Utils   ( 3802): File is Online
02-06 17:19:17.455 D/NuPlayerDriver( 3802): notifyListener_l(0xb73025a8), (4, 0, 0)
02-06 17:19:17.456 D/MediaPlayer(21353): Message: MEDIA_SEEK_COMPLETE(4), ext1=0, ext2=0x0
02-06 17:19:17.456 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1107] callback app listenerNotNull=1, send=1
02-06 17:19:17.456 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1111] callback application
02-06 17:19:17.457 W/Utils   ( 3802): File is Online
02-06 17:19:17.458 I/NuPlayer( 3802): NuPlayer::canSeek,mSourceFlags = 15 
02-06 17:19:17.467 I/[Gralloc]( 3709): alloc succ handle[0xb77b69a8] stride[1120]
02-06 17:19:17.470 E/OMXNodeInstance( 3802): setConfig(5e:google.mp3.decoder, ConfigPriority(0x6f800002)) ERROR: Undefined(0x80001001)
02-06 17:19:17.470 I/ACodec  ( 3802): codec does not support config priority (err -2147483648)
02-06 17:19:17.471 I/MediaCodec( 3802): MediaCodec will operate in async mode
02-06 17:19:17.472 I/NuPlayer( 3802): performSeek before, mIsSeeking should to change to false
02-06 17:19:17.473 D/cocos2d-x debug info(21353): server_msg_process(693)server_msg_process(693):m_currentSvrIdx = 0
02-06 17:19:17.473 D/cocos2d-x debug info(21353): refreshServerConfigTypeEnabled(305)refreshServerConfigTypeEnabled(305):set tencent_bpg_fail_start_time 0_ture3
02-06 17:19:17.473 D/cocos2d-x debug info(21353): refreshServerConfigTypeEnabled(308)refreshServerConfigTypeEnabled(308):set tencent_bpg_fail_counter 0_ture4
02-06 17:19:17.473 I/[Gralloc]( 3709): alloc w[1080] h[1794] format[1] usage[2816]
02-06 17:19:17.498 I/APM::AudioPolicyManager( 3802): startOutput() output 6, stream 3, session 283
02-06 17:19:17.498 I/APM::AudioPolicyManager( 3802): getNewOutputDevice() selected device 2
02-06 17:19:17.498 I/APM::AudioPolicyManager( 3802): setOutputDevice() device 0x0002 delayMs 0
02-06 17:19:17.498 I/APM::AudioPolicyManager( 3802): setOutputDevice() prevDevice 0x0002
02-06 17:19:17.498 I/APM::AudioPolicyManager( 3802): setOutputDevice() changing to device 0x0002 , muteWaitMs 0
02-06 17:19:17.499 I/[Gralloc]( 3709): alloc succ handle[0xb77c5550] stride[1120]
02-06 17:19:17.502 I/dsp_hifi_ctl( 3802): DTS_ERR_keyValuePairs (0) srs_cfg:trumedia_enable=1
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 5 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 7 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 7 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 1 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 7 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 7 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 7 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 7 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 15 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 1 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 1 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 1 device 0x2
02-06 17:19:17.502 I/APM::AudioPolicyManager( 3802): checkAndSetVolume: index 1 device 0x2
02-06 17:19:17.504 D/NuPlayerDriver( 3802): notifyListener_l(0xb73025a8), (6, 0, 0)
02-06 17:19:17.505 D/MediaPlayer(21353): Message: Unknown MediaEventType(6), ext1=0, ext2=0x0
02-06 17:19:17.505 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1107] callback app listenerNotNull=1, send=1
02-06 17:19:17.505 D/MediaPlayer(21353): [virtual void android::MediaPlayer::notify(int, int, int, const android::Parcel *)] : [1111] callback application
02-06 17:19:17.506 I/[Gralloc]( 3709): alloc w[1080] h[1794] format[1] usage[2816]
02-06 17:19:17.512 I/AudioFlinger( 3802): updateWakeLockUids_l() AudioOut_6 mType: 0 status 0
02-06 17:19:17.512 V/SRS_ProcT( 3802): CFG for 0xb72c6f10
02-06 17:19:17.512 V/SRS_Routing( 3802): ResolveRoute 1: 2 2
02-06 17:19:17.512 V/SRS_Routing( 3802): ResolveRoute 2: 2 2
02-06 17:19:17.513 V/SRS_Routing( 3802): ResolveRoute 3: 2 2
02-06 17:19:17.513 V/SRS_ProcT( 3802): CFG HLimit: 1
02-06 17:19:17.513 D/PhoneStateManager( 6044): SESSION_ID_NEW, containsKey, pid: 3802, mValue: 283, 1013
02-06 17:19:17.514 I/audio_hw_primary( 3802): start_output_stream : mode=0, devices=2
02-06 17:19:17.534 I/[Gralloc]( 3709): alloc succ handle[0xb78ca418] stride[1120]
02-06 17:19:17.573 D/cocos2d-x debug info(21353): setIsVisitorLogin(306)#### NOTE:other no IOS plotform, CAN NOT SET VISITOR MODE
02-06 17:19:17.577 V/MicroMsg.SDK.WXApiImplV10.ActivityLifecycleCb(21353): WXStat trigger onForeground
02-06 17:19:17.585 I/HwActivityManagerService( 4261): ProcessRecord ProcessRecord{11217c5 20671:0:com.tencent.mobileqq/u0a46} is not a cloned process
02-06 17:19:17.588 I/System.out(20671): [/system/bin/sh, -c, type su]
02-06 17:19:17.588 I/System.out(20671): null
02-06 17:19:17.588 I/System.out(20671): null
02-06 17:19:17.588 I/System.out(20671): Calling by::className:com.tencent.bugly.proguard.y  MethodName:a
02-06 17:19:17.609 W/ActivityManager( 4261): getTasks: caller 10099 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:17.630 D/WifiManager(20671): Enter init, sThreadRefCount:0
02-06 17:19:17.630 D/WifiService( 4261): getWifiServiceMessenger, pid:20671, uid:10046
02-06 17:19:17.630 D/WifiManager(20671): Create WifiManager handlerthread
02-06 17:19:17.633 D/WifiService( 4261): New client listening to asynchronous messages
02-06 17:19:17.633 W/ActivityManager( 4261): getRunningAppProcesses: caller 10046 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:17.655 D/AudioFlinger( 3802): mixer(0xb727d740) throttle end: throttle time(69)
02-06 17:19:17.701 I/System  (20671): core_booster, getBoosterConfig = false
02-06 17:19:17.841 D/SensorHub( 4261): -------------------------->SENSOR_TYPE_PROXIMITY data[0] = 0.000000
02-06 17:19:18.007 D/WifiHW  ( 4261): wifi_send_command: cmd:'IFNAME=wlan0 SIGNAL_POLL'
02-06 17:19:18.007 D/wpa_supplicant( 4417): wlan0: Control interface command 'SIGNAL_POLL'
02-06 17:19:18.018 E/WifiConfigStore( 4261): updateConfiguration freq=2422 BSSID=84:82:f4:32:9c:f9 RSSI=-47 "SZXX-1202"WPA_PSK
02-06 17:19:18.032 I/[Gralloc]( 3709): alloc w[422] h[1048] format[1] usage[2816]
02-06 17:19:18.038 I/[Gralloc]( 3709): alloc succ handle[0xb7843dd8] stride[480]
02-06 17:19:18.047 I/[Gralloc]( 3709): alloc w[422] h[1048] format[1] usage[2816]
02-06 17:19:18.053 I/[Gralloc]( 3709): alloc succ handle[0xb78b0f38] stride[480]
02-06 17:19:18.413 D/HwArpVerifier( 4261): check_wifi_state_mode = 0 mCheckStateToken=26 token26
02-06 17:19:18.415 D/HwArpVerifier( 4261): 192.168.1.114    0x1         0x2         b8:98:f7:58:7c:bd     *        wlan0
02-06 17:19:18.415 D/HwArpVerifier( 4261): 192.168.1.1      0x1         0x6         c4:8f:07:14:48:eb     *        wlan0
02-06 17:19:18.415 D/HwArpVerifier( 4261): 192.168.1.115    0x1         0x2         a4:44:d1:ce:fe:33     *        wlan0
02-06 17:19:18.415 D/HwArpVerifier( 4261): 192.168.1.31     0x1         0x2         00:cf:e0:3c:ed:4e     *        wlan0
02-06 17:19:18.415 D/HwArpVerifier( 4261): 192.168.1.250    0x1         0x2         c0:1a:da:12:60:79     *        wlan0
02-06 17:19:18.416 D/HwArpVerifier( 4261): 192.168.1.124    0x1         0x0         00:00:00:00:00:00     *        wlan0
02-06 17:19:18.416 D/HwArpVerifier( 4261): 192.168.1.49     0x1         0x2         c0:9a:71:2d:0a:d1     *        wlan0
02-06 17:19:18.416 D/HwArpVerifier( 4261): 192.168.1.196    0x1         0x2         a4:44:d1:92:1e:2f     *        wlan0
02-06 17:19:18.416 D/wifiserviceimpl( 4261): netmask =16777215
02-06 17:19:18.417 D/HwArpVerifier( 4261): ARP wlan0,addr: /192.168.1.245
02-06 17:19:18.481 D/HWMultiGW( 4261): setGateWay 192.168.1.1
02-06 17:19:19.250 D/gpsd    ( 8103): WakeLock(Acquire,GPSD)
02-06 17:19:19.250 D/gpsd    ( 8103): WakeLock(Release,GPSD)
02-06 17:19:19.259 I/SendBroadcastPermission( 4261): action:android.intent.action.SIG_STR, mPermissionType:0
02-06 17:19:19.260 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=android.intent.action.SIG_STR flg=0x20000010 (has extras) }, receivers: null
02-06 17:19:19.260 D/cell strength( 6014): ===== cell singal strength changed : -46
02-06 17:19:19.260 I/MQoS    ( 4261): onSignal: mSubId=0,currDataSubID=0
02-06 17:19:19.261 I/MQoS    ( 4261): received cell-signal:5
02-06 17:19:19.261 D/NetworkController.MobileSignalController(0)( 4891): mSimSubId:0 onSignalStrengthsChanged signalStrength=SignalStrength: -46 0 -89 255 -1 -1 -1 -1 -1 -1 0 0 0 -1 false gw|lte level=4
02-06 17:19:19.261 D/NetworkController.MobileSignalController(0)( 4891):  mDataNetType:17 indexOfkey:14 iconGroup.mName:TDS roaming:false
02-06 17:19:19.265 W/ActivityManager( 4261): getRunningAppProcesses: caller 10046 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:19.270 I/HwCustMobileSignalControllerImpl( 4891): subId:0 phoneType:1 networktype:17 targetClass:2 masterLevel:4 slaveLevel:4
02-06 17:19:19.510 D/HwArpVerifier( 4261): There are 1 mac address for gateway 
02-06 17:19:19.510 D/HwArpVerifier( 4261): mac is static ARP: c4:8f:07:14:48:eb
02-06 17:19:19.510 D/HwArpVerifier( 4261): from HEART_CHECK transmit to state:HEART_CHECK
02-06 17:19:19.510 D/HwArpVerifier( 4261): msg what=124 arg1(token)=26 arg2(mode)=0 delay=30000
02-06 17:19:19.511 D/HwArpVerifier( 4261): performPollAndLog:
02-06 17:19:19.529 D/hw_netstat( 4261): total/3353/6937,com.highlight.mjhb/1926/4717,com.tencent.mobileqq/640/1783,unknown:0/735/385,com.tencent.mtt/52/52
02-06 17:19:20.636 V/AudioManager(21353): playSoundEffect   effectType: 0
02-06 17:19:20.636 V/AudioManager(21353): querySoundEffectsEnabled...
02-06 17:19:20.683 I/[Gralloc]( 3709): alloc w[1080] h[1794] format[1] usage[2816]
02-06 17:19:20.703 I/[Gralloc]( 3709): alloc succ handle[0xb78c5b28] stride[1120]
02-06 17:19:21.024 D/WifiHW  ( 4261): wifi_send_command: cmd:'IFNAME=wlan0 SIGNAL_POLL'
02-06 17:19:21.024 D/wpa_supplicant( 4417): wlan0: Control interface command 'SIGNAL_POLL'
02-06 17:19:21.036 E/WifiConfigStore( 4261): updateConfiguration freq=2422 BSSID=84:82:f4:32:9c:f9 RSSI=-46 "SZXX-1202"WPA_PSK
02-06 17:19:21.166 I/art     ( 4261): Starting a blocking GC Explicit
02-06 17:19:21.338 I/art     ( 4261): Explicit concurrent mark sweep GC freed 19493(1175KB) AllocSpace objects, 7(196KB) LOS objects, 23% free, 53MB/69MB, paused 1.747ms total 171.760ms
02-06 17:19:21.338 I/art     ( 4261): WaitForGcToComplete blocked for 63.159ms for cause HeapTrim
02-06 17:19:21.519 E/Thermal-daemon( 3725): [ap] temp_new :35  temp_old :33
02-06 17:19:21.519 E/Thermal-daemon( 3725): Report temperature: [ap] temp :35  report_threshold:1
02-06 17:19:21.566 D/ThermalStateManager( 6044): Thermal type: 0 cur_temperature:35
02-06 17:19:24.041 D/WifiHW  ( 4261): wifi_send_command: cmd:'IFNAME=wlan0 SIGNAL_POLL'
02-06 17:19:24.041 D/wpa_supplicant( 4417): wlan0: Control interface command 'SIGNAL_POLL'
02-06 17:19:24.048 E/WifiConfigStore( 4261): updateConfiguration freq=2422 BSSID=84:82:f4:32:9c:f9 RSSI=-44 "SZXX-1202"WPA_PSK
02-06 17:19:24.534 D/HwArpVerifier( 4261): performPollAndLog:
02-06 17:19:24.566 D/hw_netstat( 4261): total/913/210,unknown:0/747/80,com.highlight.mjhb/166/130
02-06 17:19:25.166 D/SensorHub( 4261): -------------------------->SENSOR_TYPE_PROXIMITY data[0] = 5.000000
02-06 17:19:25.267 I/MQoS    ( 4261): onSignal: mSubId=0,currDataSubID=0
02-06 17:19:25.267 I/MQoS    ( 4261): received cell-signal:5
02-06 17:19:25.268 D/NetworkController.MobileSignalController(0)( 4891): mSimSubId:0 onSignalStrengthsChanged signalStrength=SignalStrength: -49 0 -91 255 -1 -1 -1 -1 -1 -1 0 0 0 -1 false gw|lte level=4
02-06 17:19:25.269 D/NetworkController.MobileSignalController(0)( 4891):  mDataNetType:17 indexOfkey:14 iconGroup.mName:TDS roaming:false
02-06 17:19:25.273 D/cell strength( 6014): ===== cell singal strength changed : -49
02-06 17:19:25.281 I/SendBroadcastPermission( 4261): action:android.intent.action.SIG_STR, mPermissionType:0
02-06 17:19:25.281 I/ActivityManager( 4261): collectReceiverComponents for intent: Intent { act=android.intent.action.SIG_STR flg=0x20000010 (has extras) }, receivers: null
02-06 17:19:25.285 W/ActivityManager( 4261): getRunningAppProcesses: caller 10046 does not hold REAL_GET_TASKS; limiting output
02-06 17:19:25.289 I/HwCustMobileSignalControllerImpl( 4891): subId:0 phoneType:1 networktype:17 targetClass:2 masterLevel:4 slaveLevel:4
02-06 17:19:26.044 D/SensorHub( 4261): -------------------------->SENSOR_TYPE_PROXIMITY data[0] = 0.000000
02-06 17:19:27.054 D/WifiHW  ( 4261): wifi_send_command: cmd:'IFNAME=wlan0 SIGNAL_POLL'
02-06 17:19:27.054 D/wpa_supplicant( 4417): wlan0: Control interface command 'SIGNAL_POLL'
02-06 17:19:27.061 E/WifiConfigStore( 4261): updateConfiguration freq=2422 BSSID=84:82:f4:32:9c:f9 RSSI=-46 "SZXX-1202"WPA_PSK
