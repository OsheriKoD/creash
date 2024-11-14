# creash
crash app
11-14 20:30:38.479  2017  6171 I ActivityTaskManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.LAUNCHER] flg=0x10200000 cmp=com.osherdahan.EzScan/.MainActivity bnds=[439,666][640,963]} from uid 10089
11-14 20:30:38.482  1777  5133 W audio_hw_generic: Not supplying enough data to HAL, expected position 2106614 , only wrote 2106607
11-14 20:30:38.492  2017  2017 W ActivityManager: Unable to start service Intent { act=android.service.appprediction.AppPredictionService cmp=com.google.android.as/com.google.android.apps.miphone.aiai.app.AiAiPredictionService } U=0: not found
11-14 20:30:38.492  2017  2017 W RemoteAppPredictionService: could not bind to Intent { act=android.service.appprediction.AppPredictionService cmp=com.google.android.as/com.google.android.apps.miphone.aiai.app.AiAiPredictionService } using flags 67108865
11-14 20:30:38.496  1771  1771 D Zygote  : Forked child process 7926
11-14 20:30:38.506  2017  2047 I ActivityManager: Start proc 7926:com.osherdahan.EzScan/u0a137 for activity {com.osherdahan.EzScan/com.osherdahan.EzScan.MainActivity}
11-14 20:30:38.509  7926  7926 W herdahan.EzSca: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:38.514  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:38.522  7926  7926 E herdahan.EzSca: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:38.553  2017  2909 W InputReader: Device has associated, but no associated display id.
11-14 20:30:38.553  2017  2909 I chatty  : uid=1000(system) Binder:2017_11 identical 8 lines
11-14 20:30:38.553  2017  2909 W InputReader: Device has associated, but no associated display id.
11-14 20:30:38.572  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:38.590  7568  7568 I cjrg    : onPause
11-14 20:30:38.614  7926  7926 W SoLoader: Initializing SoLoader: 0
11-14 20:30:38.614  7926  7926 W SoLoader: Recording new base apk path: /data/app/com.osherdahan.EzScan-09o4YQ7s6IMqfqX7cyOG5A==/base.apk
11-14 20:30:38.614  7926  7926 W SoLoader: Previously recorded 0 base apk paths.
11-14 20:30:38.615  7926  7926 I SoLoader: Preparing SO source: DirectorySoSource[root = /system/lib flags = 2]
11-14 20:30:38.615  7926  7926 I SoLoader: Preparing SO source: DirectorySoSource[root = /vendor/lib flags = 2]
11-14 20:30:38.615  7926  7926 I SoLoader: Preparing SO source: DirectApkSoSource[root = [/data/app/com.osherdahan.EzScan-09o4YQ7s6IMqfqX7cyOG5A==/base.apk!/lib/x86]]
11-14 20:30:38.621  7926  7926 I SoLoader: Preparing SO source: ApplicationSoSource[DirectorySoSource[root = /data/app/com.osherdahan.EzScan-09o4YQ7s6IMqfqX7cyOG5A==/lib/x86 flags = 0]]
11-14 20:30:38.621  7926  7926 I SoLoader: init finish: 4 SO sources prepared
11-14 20:30:38.621  7926  7926 W SoLoader: SoLoader initialized: 8
11-14 20:30:38.629  1811  2454 E SurfaceFlinger: ro.sf.lcd_density must be defined as a build property
11-14 20:30:38.629  1811  2454 E SurfaceFlinger: ro.sf.lcd_density must be defined as a build property
11-14 20:30:38.629  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.632  7926  7949 D libEGL  : Emulator has host GPU support, qemu.gles is set to 1.
11-14 20:30:38.638  7926  7926 D AppCompatDelegate: Checking for metadata for AppLocalesMetadataHolderService : Service not found
11-14 20:30:38.640  7926  7926 W RenderThread: type=1400 audit(0.0:45): avc: denied { write } for name="property_service" dev="tmpfs" ino=6933 scontext=u:r:untrusted_app:s0:c137,c256,c512,c768 tcontext=u:object_r:property_socket:s0 tclass=sock_file permissive=0
11-14 20:30:38.641  7926  7949 W libc    : Unable to set property "qemu.gles" to "1": connection failed; errno=13 (Permission denied)
11-14 20:30:38.651  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.663  7926  7949 D libEGL  : loaded /vendor/lib/egl/libEGL_emulation.so
11-14 20:30:38.664  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.670  7926  7949 D libEGL  : loaded /vendor/lib/egl/libGLESv1_CM_emulation.so
11-14 20:30:38.674  7926  7949 D libEGL  : loaded /vendor/lib/egl/libGLESv2_emulation.so
11-14 20:30:38.675  7926  7926 W SoLoader: SoLoader already initialized
11-14 20:30:38.683  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Entering merged library JNI_OnLoad.
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing 12 pre-merged libs (including stub)
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libfabricjni_so.  onload_func: 0xbccc9360
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libmapbufferjni_so.  onload_func: 0xbcd1e820
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libreact_devsupportjni_so.  onload_func: 0xbcda6360
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libreact_featureflagsjni_so.  onload_func: 0xbcdae110
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libreact_newarchdefaults_so.  onload_func: 0xbcdd6e30
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libreactnativeblob_so.  onload_func: 0xbce76070
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libreactnativejni_so.  onload_func: 0xbce96b10
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register librninstance_so.  onload_func: 0xbceb49a0
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libturbomodulejsijni_so.  onload_func: 0xbcf25ad0
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libuimanagerjni_so.  onload_func: 0xbcf2e290
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libyoga_so.  onload_func: 0xbcf348c0
11-14 20:30:38.695  7926  7926 D jni_lib_merge: About to register 11 actual methods.
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Entering merged library JNI_OnLoad.
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing 4 pre-merged libs (including stub)
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libhermes_executor_so.  onload_func: 0xbdcd6b00
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libhermesinstancejni_so.  onload_func: 0xbdcde500
11-14 20:30:38.695  7926  7926 D jni_lib_merge: Preparing to register libjsijniprofiler_so.  onload_func: 0xbdcded00
11-14 20:30:38.695  7926  7926 D jni_lib_merge: About to register 3 actual methods.
11-14 20:30:38.696  7926  7926 W SoLoader: SoLoader already initialized
11-14 20:30:38.702  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.713  7926  7926 W herdahan.EzSca: Accessing hidden method Landroid/view/WindowInsets$Type;->ime()I (blacklist, linking, denied)
11-14 20:30:38.719  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.721  7926  7947 D HostConnection: HostConnection::get() New Host Connection established 0xd2ebecb0, tid 7947
11-14 20:30:38.723  7926  7947 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:38.725  7926  7947 W OpenGLRenderer: Failed to choose config with EGL_SWAP_BEHAVIOR_PRESERVED, retrying without...
11-14 20:30:38.736  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.736  7926  7947 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 0 0
11-14 20:30:38.736  7926  7947 D EGL_emulation: eglCreateContext: 0xe9654a60: maj 2 min 0 rcv 2
11-14 20:30:38.753  7926  7947 D EGL_emulation: eglMakeCurrent: 0xe9654a60: ver 2 0 (tinfo 0xde4e8d10)
11-14 20:30:38.755  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.758  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:38.770  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.779  1675  1675 I hwservicemanager: getTransport: Cannot find entry android.hardware.graphics.mapper@3.0::IMapper/default in either framework or device manifest.
11-14 20:30:38.779  7926  7947 W Gralloc3: mapper 3.x is not supported
11-14 20:30:38.788  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.790  7926  7947 D HostConnection: createUnique: call
11-14 20:30:38.790  7926  7947 D HostConnection: HostConnection::get() New Host Connection established 0xd2ebedf0, tid 7947
11-14 20:30:38.791  7926  7947 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:38.791  7926  7947 D eglCodecCommon: allocate: Ask for block of size 0x1000
11-14 20:30:38.791  7926  7947 D eglCodecCommon: allocate: ioctl allocate returned offset 0x3ffff6000 size 0x2000
11-14 20:30:38.792  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:38.799  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:38.805  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.806  7926  7947 D EGL_emulation: eglMakeCurrent: 0xe9654a60: ver 2 0 (tinfo 0xde4e8d10)
11-14 20:30:38.809  7926  7947 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 1 0
11-14 20:30:38.823  1791  1791 W EmuHWC2 : validate: layer 74 CompositionType 1, fallback
11-14 20:30:38.829  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.833  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.841  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.842  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onFinishInput():3086
11-14 20:30:38.845  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 0, locked = false
11-14 20:30:38.845  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onStartInput():1899 onStartInput(EditorInfo{EditorInfo{packageName=com.osherdahan.EzScan, inputType=0, inputTypeString=NULL, enableLearning=false, autoCorrection=false, autoComplete=false, imeOptions=0, privateImeOptions=null, actionName=UNSPECIFIED, actionLabel=null, initialSelStart=-1, initialSelEnd=-1, initialCapsMode=0, label=null, fieldId=-1, fieldName=null, extras=null, hintText=null, hintLocales=[]}}, false)
11-14 20:30:38.845  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.845  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 1, locked = false
11-14 20:30:38.846  2478  2478 I AndroidIME: InputBundleManager.loadActiveInputBundleId():450 loadActiveInputBundleId: und-Latn-x-password, password
11-14 20:30:38.851  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.856  2017  2045 I ActivityTaskManager: Displayed com.osherdahan.EzScan/.MainActivity: +357ms
11-14 20:30:38.859  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.865  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.868  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.877  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.880  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.883  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.893  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.896  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.899  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.911  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.914  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.919  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.928  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.933  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.937  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.947  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.948  7926  7950 I ExpoModulesCore: ✅ AppContext was initialized
11-14 20:30:38.952  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:38.964  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.981  1791  1791 W EmuHWC2 : validate: layer 75 CompositionType 1, fallback
11-14 20:30:38.986  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.drawer.ReactDrawerLayoutManager
11-14 20:30:38.988  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.uimanager.LayoutShadowNode
11-14 20:30:38.989  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.scroll.ReactHorizontalScrollViewManager
11-14 20:30:38.990  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.scroll.ReactHorizontalScrollContainerViewManager
11-14 20:30:38.991  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.ReactProgressBarViewManager
11-14 20:30:38.991  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.progressbar.ProgressBarShadowNode
11-14 20:30:38.993  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.scroll.ReactScrollViewManager
11-14 20:30:38.994  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.switchview.ReactSwitchManager
11-14 20:30:38.995  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.switchview.ReactSwitchManager$ReactSwitchShadowNode
11-14 20:30:38.996  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.safeareaview.ReactSafeAreaViewManager
11-14 20:30:38.996  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.safeareaview.ReactSafeAreaViewShadowNode
11-14 20:30:38.996  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.swiperefresh.SwipeRefreshLayoutManager
11-14 20:30:38.998  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.FrescoBasedReactTextInlineImageViewManager
11-14 20:30:38.998  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.frescosupport.FrescoBasedReactTextInlineImageShadowNode
11-14 20:30:39.009  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.image.ReactImageManager
11-14 20:30:39.010  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.modal.ReactModalHostManager
11-14 20:30:39.010  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.ReactRawTextManager
11-14 20:30:39.010  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.ReactRawTextShadowNode
11-14 20:30:39.011  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.ReactTextInputManager
11-14 20:30:39.013  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.textinput.ReactTextInputShadowNode
11-14 20:30:39.014  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.ReactTextViewManager
11-14 20:30:39.014  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.ReactTextShadowNode
11-14 20:30:39.014  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.view.ReactViewManager
11-14 20:30:39.015  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.ReactVirtualTextViewManager
11-14 20:30:39.015  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.text.ReactVirtualTextShadowNode
11-14 20:30:39.015  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.facebook.react.views.unimplementedview.ReactUnimplementedViewManager
11-14 20:30:39.015  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.reactnativecommunity.picker.ReactDialogPickerManager
11-14 20:30:39.016  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.reactnativecommunity.picker.ReactPickerShadowNode
11-14 20:30:39.016  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.reactnativecommunity.picker.ReactDropdownPickerManager
11-14 20:30:39.017  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class expo.modules.kotlin.views.GroupViewManagerWrapper
11-14 20:30:39.018  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenContainerViewManager
11-14 20:30:39.019  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenViewManager
11-14 20:30:39.020  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ModalScreenViewManager
11-14 20:30:39.020  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenStackViewManager
11-14 20:30:39.020  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenStackHeaderConfigViewManager
11-14 20:30:39.021  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenStackHeaderSubviewManager
11-14 20:30:39.021  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.SearchBarManager
11-14 20:30:39.023  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenFooterManager
11-14 20:30:39.026  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenContentWrapperManager
11-14 20:30:39.045  1811  1811 E Layer   : [Surface(name=AppWindowToken{a1518e6 token=Token{6db9b41 ActivityRecord{8999228 u0 com.osherdahan.EzScan/.MainActivity t14}}})/@0x52ef04 - animation-leash#0] No local sync point found
11-14 20:30:39.045  1811  1811 E Layer   : [Surface(name=AppWindowToken{a1518e6 token=Token{6db9b41 ActivityRecord{8999228 u0 com.osherdahan.EzScan/.MainActivity t14}}})/@0x52ef04 - animation-leash#0] No local sync point found
11-14 20:30:39.045  1811  1811 E Layer   : [Surface(name=AppWindowToken{b7063cc token=Token{1d749ff ActivityRecord{29bed1e u0 com.google.android.apps.nexuslauncher/.NexusLauncherActivity t2}}})/@0x599a6bc - animation-leash#0] No local sync point found
11-14 20:30:39.045  1811  1811 E Layer   : [Surface(name=AppWindowToken{b7063cc token=Token{1d749ff ActivityRecord{29bed1e u0 com.google.android.apps.nexuslauncher/.NexusLauncherActivity t2}}})/@0x599a6bc - animation-leash#0] No local sync point found
11-14 20:30:39.059  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:39.068  2017  2909 I ActivityManager: Killing 4600:com.google.android.permissioncontroller/u0a60 (adj 975): empty #17
11-14 20:30:39.069  7568  7603 D EGL_emulation: eglMakeCurrent: 0xde4909c0: ver 2 0 (tinfo 0xb05a5b40)
11-14 20:30:39.087  7568  7568 I cjrg    : onStop
11-14 20:30:39.112  1771  1771 I Zygote  : Process 4600 exited due to signal 9 (Killed)
11-14 20:30:39.127  7926  7957 D NetworkSecurityConfig: No Network Security Config specified, using platform default
11-14 20:30:39.151  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10060 pid 4600 in 82ms
11-14 20:30:39.177  7926  7956 I ExpoModulesCore: ✅ JSI interop was installed
11-14 20:30:39.178  7926  7956 W ExpoModulesCore: ⚠️ JSI interop was already installed
11-14 20:30:39.178  7926  7956 I ExpoModulesCore: ✅ Constants were exported
11-14 20:30:39.213  2562  3039 I FontLog : (REDACTED) Received query %s, URI %s
11-14 20:30:39.213  2562  3039 I FontLog : (REDACTED) Query [%s] resolved to %s
11-14 20:30:39.214  2562  3039 I FontLog : (REDACTED) Fetch %s end status %s
11-14 20:30:39.215  2562  3039 I FontLog : (REDACTED) Pulling font file for id = %d, cache size = %d
11-14 20:30:39.217  2562  3039 I FontLog : (REDACTED) Pulling font file for id = %d, cache size = %d
11-14 20:30:39.234  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:39.234  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:39.275  7926  7956 I ReactNativeJS: Running "main"
11-14 20:30:39.299  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreenStackHeaderConfigShadowNode
11-14 20:30:39.299  7926  7957 W unknown:ViewManagerPropertyUpdater: Could not find generated setter for class com.swmansion.rnscreens.ScreensShadowNode
11-14 20:30:39.300  7926  7957 E AndroidRuntime: FATAL EXCEPTION: mqt_native_modules
11-14 20:30:39.300  7926  7957 E AndroidRuntime: Process: com.osherdahan.EzScan, PID: 7926
11-14 20:30:39.300  7926  7957 E AndroidRuntime: com.facebook.react.uimanager.IllegalViewOperationException: No ViewManager found for class RNCSafeAreaProvider
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.uimanager.ViewManagerRegistry.get(ViewManagerRegistry.java:85)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.uimanager.UIImplementation.createShadowNode(UIImplementation.java:108)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.uimanager.UIImplementation.createView(UIImplementation.java:249)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.uimanager.UIManagerModule.createView(UIManagerModule.java:438)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at java.lang.reflect.Method.invoke(Native Method)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.bridge.JavaMethodWrapper.invoke(JavaMethodWrapper.java:372)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.bridge.JavaModuleWrapper.invoke(JavaModuleWrapper.java:146)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.jni.NativeRunnable.run(Native Method)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at android.os.Handler.handleCallback(Handler.java:883)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at android.os.Handler.dispatchMessage(Handler.java:100)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.bridge.queue.MessageQueueThreadHandler.dispatchMessage(MessageQueueThreadHandler.java:27)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at android.os.Looper.loop(Looper.java:214)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.bridge.queue.MessageQueueThreadImpl.lambda$startNewBackgroundThread$2(MessageQueueThreadImpl.java:217)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at com.facebook.react.bridge.queue.MessageQueueThreadImpl$$ExternalSyntheticLambda1.run(D8$$SyntheticClass:0)
11-14 20:30:39.300  7926  7957 E AndroidRuntime:        at java.lang.Thread.run(Thread.java:919)
11-14 20:30:39.301  2017  5449 W ActivityTaskManager:   Force finishing activity com.osherdahan.EzScan/.MainActivity
11-14 20:30:39.301  2017  7965 I DropBoxManagerService: add tag=data_app_crash isTagEnabled=true flags=0x2
11-14 20:30:39.304  2017  2456 W InputReader: Device has associated, but no associated display id.
11-14 20:30:39.305  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
11-14 20:30:39.304  2017  2456 I chatty  : uid=1000(system) Binder:2017_9 identical 8 lines
11-14 20:30:39.304  2017  2456 W InputReader: Device has associated, but no associated display id.
11-14 20:30:39.305  7926  7957 I Process : Sending signal. PID: 7926 SIG: 9
11-14 20:30:39.316  2017  2017 W ActivityManager: Unable to start service Intent { act=android.service.appprediction.AppPredictionService cmp=com.google.android.as/com.google.android.apps.miphone.aiai.app.AiAiPredictionService } U=0: not found
11-14 20:30:39.316  2017  2017 W RemoteAppPredictionService: could not bind to Intent { act=android.service.appprediction.AppPredictionService cmp=com.google.android.as/com.google.android.apps.miphone.aiai.app.AiAiPredictionService } using flags 67108865
11-14 20:30:39.318  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:39.344  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:39.363  7568  7603 D EGL_emulation: eglMakeCurrent: 0xde4909c0: ver 2 0 (tinfo 0xb05a5b40)
11-14 20:30:39.368  2017  2116 W InputDispatcher: channel 'b9e5a0f com.osherdahan.EzScan/com.osherdahan.EzScan.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-14 20:30:39.368  2017  2116 E InputDispatcher: channel 'b9e5a0f com.osherdahan.EzScan/com.osherdahan.EzScan.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
11-14 20:30:39.368  1771  1771 I Zygote  : Process 7926 exited due to signal 9 (Killed)
11-14 20:30:39.369  2017  6467 I ActivityManager: Process com.osherdahan.EzScan (pid 7926) has died: vis+99 TOP
11-14 20:30:39.369  2017  3342 I WindowManager: WIN DEATH: Window{b9e5a0f u0 com.osherdahan.EzScan/com.osherdahan.EzScan.MainActivity}
11-14 20:30:39.369  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10137 pid 7926 in 0ms
11-14 20:30:39.369  2017  3342 W InputDispatcher: Attempted to unregister already unregistered input channel 'b9e5a0f com.osherdahan.EzScan/com.osherdahan.EzScan.MainActivity (server)'
11-14 20:30:39.370  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:39.399  2017  2038 W ActivityManager: setHasOverlayUi called on unknown pid: 7926
11-14 20:30:39.420  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:39.421  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:39.422  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:39.423  7568  7568 I cjrg    : onStart
11-14 20:30:39.428  7568  7568 I cjrg    : onResume
11-14 20:30:39.435  2017  2045 E memtrack: Couldn't load memtrack module
11-14 20:30:39.435  2017  2045 W android.os.Debug: failed to get memory consumption info: -1
11-14 20:30:39.442  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:39.453  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onFinishInput():3086
11-14 20:30:39.458  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 0, locked = false
11-14 20:30:39.458  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onStartInput():1899 onStartInput(EditorInfo{EditorInfo{packageName=com.google.android.apps.nexuslauncher, inputType=0, inputTypeString=NULL, enableLearning=false, autoCorrection=false, autoComplete=false, imeOptions=0, privateImeOptions=null, actionName=UNSPECIFIED, actionLabel=null, initialSelStart=-1, initialSelEnd=-1, initialCapsMode=0, label=null, fieldId=-1, fieldName=null, extras=null, hintText=null, hintLocales=[]}}, false)
11-14 20:30:39.458  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 1, locked = false
11-14 20:30:39.458  2478  2478 I AndroidIME: InputBundleManager.loadActiveInputBundleId():450 loadActiveInputBundleId: und-Latn-x-password, password
11-14 20:30:39.493  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:39.583  2163  2477 I chatty  : uid=10101(com.android.systemui) RenderThread identical 11 lines
11-14 20:30:39.597  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:40.234  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:40.234  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:40.713  2562  7461 E memtrack: Couldn't load memtrack module
11-14 20:30:40.713  2562  7461 W android.os.Debug: failed to get memory consumption info: -1
11-14 20:30:40.776  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 98304
11-14 20:30:40.803  2420  2932 E BufferQueueProducer: [unnamed-2420-1] setMaxDequeuedBufferCount: 2 dequeued buffers would exceed the maxBufferCount (2) (maxAcquired 1 async 0 mDequeuedBufferCannotBlock 0)
11-14 20:30:40.803  2420  2932 E Surface : IGraphicBufferProducer::setBufferCount(3) returned Invalid argument
11-14 20:30:40.811  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:40.812  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 98304
11-14 20:30:40.815  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:40.824  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:41.235  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:41.235  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:41.631  1777  1855 W audio_hw_generic: Not supplying enough data to HAL, expected position 2382471 , only wrote 2245417
11-14 20:30:41.830  2017  6467 I ActivityTaskManager: START u0 {act=android.settings.APPLICATION_DETAILS_SETTINGS dat=package:com.osherdahan.EzScan flg=0x10008000 cmp=com.android.settings/.applications.InstalledAppDetails bnds=[462,526][1067,680]} from uid 10089
11-14 20:30:41.833  1777  5133 W audio_hw_generic: Not supplying enough data to HAL, expected position 2245434 , only wrote 2245417
11-14 20:30:41.909  2017  2039 E system_server: Invalid ID 0x00000000.
11-14 20:30:41.910  2017  6467 W InputReader: Device has associated, but no associated display id.
11-14 20:30:41.910  2017  6467 I chatty  : uid=1000(system) Binder:2017_20 identical 8 lines
11-14 20:30:41.910  2017  6467 W InputReader: Device has associated, but no associated display id.
11-14 20:30:41.917  1771  1771 D Zygote  : Forked child process 7972
11-14 20:30:41.921  7972  7972 W ndroid.setting: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:41.924  2017  2047 I ActivityManager: Start proc 7972:com.android.settings/1000 for activity {com.android.settings/com.android.settings.applications.InstalledAppDetails}
11-14 20:30:41.926  7972  7972 E ndroid.setting: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:41.932  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:41.943  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:41.947  2017  6171 I chatty  : uid=1000(system) Binder:2017_1E identical 28 lines
11-14 20:30:41.947  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:41.951  7972  7972 I ndroid.setting: The ClassLoaderContext is a special shared library.
11-14 20:30:41.956  7972  7972 I ndroid.setting: The ClassLoaderContext is a special shared library.
11-14 20:30:41.983  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:41.983  2017  2039 I chatty  : uid=1000(system) android.anim identical 8 lines
11-14 20:30:41.983  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:41.991  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:42.010  7568  7568 I cjrg    : onPause
11-14 20:30:42.029  1811  2160 E SurfaceFlinger: ro.sf.lcd_density must be defined as a build property
11-14 20:30:42.030  1811  2160 E SurfaceFlinger: ro.sf.lcd_density must be defined as a build property
11-14 20:30:42.039  7972  7994 D libEGL  : Emulator has host GPU support, qemu.gles is set to 1.
11-14 20:30:42.047  7972  7994 W libc    : Unable to set property "qemu.gles" to "1": error code: 0x18
11-14 20:30:42.064  7972  7994 D libEGL  : loaded /vendor/lib/egl/libEGL_emulation.so
11-14 20:30:42.065  7972  7994 D libEGL  : loaded /vendor/lib/egl/libGLESv1_CM_emulation.so
11-14 20:30:42.065  7972  7994 D libEGL  : loaded /vendor/lib/egl/libGLESv2_emulation.so
11-14 20:30:42.079  7972  7972 D SettingsActivity: Starting onCreate
11-14 20:30:42.096  7972  7972 D SettingsActivity: Starting to set activity title
11-14 20:30:42.096  7972  7972 D SettingsActivity: Done setting title
11-14 20:30:42.096  7972  7972 D SettingsActivity: Switching to fragment com.android.settings.applications.appinfo.AppInfoDashboardFragment
11-14 20:30:42.115  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppNotificationPreferenceController
11-14 20:30:42.120  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppPermissionPreferenceController
11-14 20:30:42.120  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppStoragePreferenceController
11-14 20:30:42.121  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.InstantAppDomainsPreferenceController
11-14 20:30:42.121  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppDataUsagePreferenceController
11-14 20:30:42.121  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.TimeSpentInAppPreferenceController
11-14 20:30:42.121  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppOpenByDefaultPreferenceController
11-14 20:30:42.122  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AdvancedAppInfoPreferenceCategoryController
11-14 20:30:42.122  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.DrawOverlayDetailPreferenceController
11-14 20:30:42.122  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.WriteSystemSettingsPreferenceController
11-14 20:30:42.123  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.specialaccess.pictureinpicture.PictureInPictureDetailPreferenceController
11-14 20:30:42.123  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.ExternalSourceDetailPreferenceController
11-14 20:30:42.123  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppInstallerPreferenceCategoryController
11-14 20:30:42.123  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppInstallerInfoPreferenceController
11-14 20:30:42.123  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppSettingPreferenceController
11-14 20:30:42.124  7972  7972 D PrefCtrlListHelper: Could not find Context-only controller for pref: com.android.settings.applications.appinfo.AppVersionPreferenceController
11-14 20:30:42.125  7972  7972 W Settings: Unable to find info for package: null
11-14 20:30:42.134  7972  7972 W InstrumentedPrefFrag: Screen title missing for fragment com.android.settings.applications.appinfo.AppInfoDashboardFragment
11-14 20:30:42.140  7972  7972 W TileUtils: Found com.android.settings.Settings$DataUsageSummaryActivity for intent Intent { act=com.android.settings.action.SETTINGS pkg=com.android.settings } missing metadata com.android.settings.category
11-14 20:30:42.147  7972  7972 D AppInfoDashboard: NO dashboard tiles for AppInfoDashboard
11-14 20:30:42.147  7972  7972 D AppInfoDashboard: All preferences added, reporting fully drawn
11-14 20:30:42.147  2017  2045 I ActivityTaskManager: Fully drawn com.android.settings/.applications.InstalledAppDetails: +318ms
11-14 20:30:42.149  7972  7972 D SettingsActivity: Executed frag manager pendingTransactions
11-14 20:30:42.159  7972  7997 W TileUtils: Found com.android.settings.Settings$DataUsageSummaryActivity for intent Intent { act=com.android.settings.action.SETTINGS pkg=com.android.settings } missing metadata com.android.settings.category
11-14 20:30:42.163  7972  7972 W AppButtonsPrefCtl: App is not explicitly stopped
11-14 20:30:42.166  2017  2051 E BluetoothAdapter: Bluetooth binder is null
11-14 20:30:42.170  2017  2051 E KernelCpuUidUserSysTimeReader: Negative user/sys time delta for UID=10121
11-14 20:30:42.170  2017  2051 E KernelCpuUidUserSysTimeReader: Prev times: u=637 s=723 Curr times: u=565 s=497
11-14 20:30:42.180  7972  8000 D SettingsActivity: No enabled state changed, skipping updateCategory call
11-14 20:30:42.221  1770  1996 I netd    : trafficSwapActiveStatsMap() <46.35ms>
11-14 20:30:42.222  1770  1996 I netd    : tetherGetStats() <0.36ms>
11-14 20:30:42.233  7972  7972 D AppUtils: Have 0 number of activities in preferred list
11-14 20:30:42.235  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:42.235  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:42.260  1770  1770 I netd    : trafficSwapActiveStatsMap() <38.82ms>
11-14 20:30:42.261  1770  1770 I netd    : tetherGetStats() <0.54ms>
11-14 20:30:42.294  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:42.310  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:42.325  7568  7603 D EGL_emulation: eglMakeCurrent: 0xde4909c0: ver 2 0 (tinfo 0xb05a5b40)
11-14 20:30:42.341  1770  1770 I netd    : trafficSwapActiveStatsMap() <45.51ms>
11-14 20:30:42.342  1770  1770 I netd    : tetherGetStats() <0.50ms>
11-14 20:30:42.400  1770  1770 I netd    : trafficSwapActiveStatsMap() <48.36ms>
11-14 20:30:42.401  1770  1770 I netd    : tetherGetStats() <0.56ms>
11-14 20:30:42.460  1770  1770 I netd    : trafficSwapActiveStatsMap() <48.93ms>
11-14 20:30:42.461  1770  1770 I netd    : tetherGetStats() <0.55ms>
11-14 20:30:42.510  1770  1770 I netd    : trafficSwapActiveStatsMap() <41.09ms>
11-14 20:30:42.511  1770  1770 I netd    : tetherGetStats() <0.41ms>
11-14 20:30:42.550  1770  1770 I netd    : trafficSwapActiveStatsMap() <31.56ms>
11-14 20:30:42.551  1770  1770 I netd    : tetherGetStats() <0.66ms>
11-14 20:30:42.611  1770  1770 I netd    : trafficSwapActiveStatsMap() <50.75ms>
11-14 20:30:42.611  1770  1770 I netd    : tetherGetStats() <0.32ms>
11-14 20:30:42.660  1770  1770 I netd    : trafficSwapActiveStatsMap() <44.09ms>
11-14 20:30:42.661  1770  1770 I netd    : tetherGetStats() <0.54ms>
11-14 20:30:42.720  1770  1770 I netd    : trafficSwapActiveStatsMap() <52.28ms>
11-14 20:30:42.727  7972  7972 D AppUtils: Have 0 number of activities in preferred list
11-14 20:30:42.727  1770  1770 I netd    : tetherGetStats() <2.40ms>
11-14 20:30:42.817  7972  7972 W AppButtonsPrefCtl: App is not explicitly stopped
11-14 20:30:42.831  1771  1771 D Zygote  : Forked child process 8001
11-14 20:30:42.833  8001  8001 W ssioncontrolle: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:42.836  8001  8001 E ssioncontrolle: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:42.838  2017  2047 I ActivityManager: Start proc 8001:com.google.android.permissioncontroller/u0a60 for service {com.google.android.permissioncontroller/com.android.packageinstaller.role.service.RoleControllerServiceImpl}
11-14 20:30:42.859  8001  8001 I ssioncontrolle: The ClassLoaderContext is a special shared library.
11-14 20:30:42.991  7972  7972 V BatteryUtils: package: com.google.uid.shared:10098
11-14 20:30:42.991  7972  7972 V BatteryUtils: type: 0 time(us): 14129000
11-14 20:30:42.991  7972  7972 V BatteryUtils: foreground time(us): 14129000
11-14 20:30:43.023  7972  7992 D HostConnection: HostConnection::get() New Host Connection established 0xd644c190, tid 7992
11-14 20:30:43.026  7972  7992 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:43.029  7972  7992 W OpenGLRenderer: Failed to choose config with EGL_SWAP_BEHAVIOR_PRESERVED, retrying without...
11-14 20:30:43.039  7972  7992 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 0 0
11-14 20:30:43.039  7972  7992 D EGL_emulation: eglCreateContext: 0xd641a240: maj 2 min 0 rcv 2
11-14 20:30:43.055  7972  7992 D EGL_emulation: eglMakeCurrent: 0xd641a240: ver 2 0 (tinfo 0xb011d380)
11-14 20:30:43.062  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:43.092  1675  1675 I hwservicemanager: getTransport: Cannot find entry android.hardware.graphics.mapper@3.0::IMapper/default in either framework or device manifest.
11-14 20:30:43.093  7972  7992 W Gralloc3: mapper 3.x is not supported
11-14 20:30:43.105  7972  7992 D HostConnection: createUnique: call
11-14 20:30:43.106  7972  7992 D HostConnection: HostConnection::get() New Host Connection established 0xb0074440, tid 7992
11-14 20:30:43.107  7972  7992 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:43.107  7972  7992 D eglCodecCommon: allocate: Ask for block of size 0x1000
11-14 20:30:43.107  7972  7992 D eglCodecCommon: allocate: ioctl allocate returned offset 0x3ffff6000 size 0x2000
11-14 20:30:43.108  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:43.116  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:43.124  7972  7992 D EGL_emulation: eglMakeCurrent: 0xd641a240: ver 2 0 (tinfo 0xb011d380)
11-14 20:30:43.135  7972  7992 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 1 0
11-14 20:30:43.162  8001  8019 W Role    : com.osherdahan.EzScan not qualified for android.app.role.HOME due to missing RequiredComponent{mIntentFilterData=IntentFilterData{mAction='android.intent.action.MAIN', mCategories='[android.intent.category.HOME]', mDataScheme='null', mDataType='null'}, mPermission='null', mMetaData=[]}
11-14 20:30:43.164  8001  8019 W Role    : com.osherdahan.EzScan not qualified for android.app.role.DIALER due to missing RequiredComponent{mIntentFilterData=IntentFilterData{mAction='android.intent.action.DIAL', mCategories='[]', mDataScheme='null', mDataType='null'}, mPermission='null', mMetaData=[]}
11-14 20:30:43.167  8001  8019 W Role    : com.osherdahan.EzScan not qualified for android.app.role.SMS due to missing RequiredComponent{mIntentFilterData=IntentFilterData{mAction='android.provider.Telephony.SMS_DELIVER', mCategories='[]', mDataScheme='null', mDataType='null'}, mPermission='android.permission.BROADCAST_SMS', mMetaData=[]}
11-14 20:30:43.170  2017  2045 I ActivityTaskManager: Displayed com.android.settings/.applications.InstalledAppDetails: +1s327ms
11-14 20:30:43.187  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onFinishInput():3086
11-14 20:30:43.189  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 0, locked = false
11-14 20:30:43.189  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onStartInput():1899 onStartInput(EditorInfo{EditorInfo{packageName=com.android.settings, inputType=0, inputTypeString=NULL, enableLearning=false, autoCorrection=false, autoComplete=false, imeOptions=0, privateImeOptions=null, actionName=UNSPECIFIED, actionLabel=null, initialSelStart=-1, initialSelEnd=-1, initialCapsMode=0, label=null, fieldId=2131362628, fieldName=null, extras=null, hintText=null, hintLocales=[]}}, false)
11-14 20:30:43.189  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 1, locked = false
11-14 20:30:43.189  2478  2478 I AndroidIME: InputBundleManager.loadActiveInputBundleId():450 loadActiveInputBundleId: und-Latn-x-password, password
11-14 20:30:43.236  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:43.236  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:43.256  7972  7972 D AppInfoDashboard: Package change irrelevant, skipping
11-14 20:30:43.256  7568  7568 I cjrg    : onStop
11-14 20:30:43.261  7972  7972 D AppInfoDashboard: Package change irrelevant, skipping
11-14 20:30:43.319  7972  7972 I chatty  : uid=1000(system) com.android.settings identical 41 lines
11-14 20:30:43.322  7972  7972 D AppInfoDashboard: Package change irrelevant, skipping
11-14 20:30:43.333  7972  7972 D AppUtils: Have 0 number of activities in preferred list
11-14 20:30:43.343  7972  7972 W AppButtonsPrefCtl: App is not explicitly stopped
11-14 20:30:43.344  7972  7972 D AppInfoDashboard: Package change irrelevant, skipping
11-14 20:30:44.205  2017  2034 E UserRestrictionsUtils: Unknown restriction queried by uid 1000 (com.android.dynsystem et al): com.osherdahan.EzScan
11-14 20:30:43.647  7972  7972 I chatty  : uid=1000(system) com.android.settings identical 116 lines
11-14 20:30:43.647  7972  7972 D AppInfoDashboard: Package change irrelevant, skipping
11-14 20:30:44.207  7972  7972 W SettingsMetricsFeature: action(Pair<Integer, Object>... taggedData) is deprecated, Use action(int, int, int, String, int) instead.
11-14 20:30:44.207  2017  3342 I ActivityTaskManager: START u0 {act=android.intent.action.UNINSTALL_PACKAGE dat=package:com.osherdahan.EzScan cmp=com.google.android.packageinstaller/com.android.packageinstaller.UninstallerActivity (has extras)} from uid 1000
11-14 20:30:44.211  2017  2034 W InputReader: Device has associated, but no associated display id.
11-14 20:30:44.234  2017  2046 I DropBoxManagerService: add tag=system_server_wtf isTagEnabled=true flags=0x2
11-14 20:30:44.211  2017  2034 I chatty  : uid=1000(system) Binder:2017_2 identical 8 lines
11-14 20:30:44.211  2017  2034 W InputReader: Device has associated, but no associated display id.
11-14 20:30:44.237  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:44.237  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:44.239  1771  1771 D Zygote  : Forked child process 8025
11-14 20:30:44.241  8025  8025 W ackageinstalle: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:44.244  2017  2047 I ActivityManager: Start proc 8025:com.google.android.packageinstaller/u0a59 for activity {com.google.android.packageinstaller/com.android.packageinstaller.UninstallerActivity}
11-14 20:30:44.246  8025  8025 E ackageinstalle: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:44.257  2017  6467 W InputReader: Device has associated, but no associated display id.
11-14 20:30:44.258  2017  6467 I chatty  : uid=1000(system) Binder:2017_20 identical 28 lines
11-14 20:30:44.258  2017  6467 W InputReader: Device has associated, but no associated display id.
11-14 20:30:44.264  8025  8025 I ackageinstalle: The ClassLoaderContext is a special shared library.
11-14 20:30:44.278  1811  2454 E SurfaceFlinger: ro.sf.lcd_density must be defined as a build property
11-14 20:30:44.278  1811  2454 E SurfaceFlinger: ro.sf.lcd_density must be defined as a build property
11-14 20:30:44.280  8025  8025 W RenderThread: type=1400 audit(0.0:46): avc: denied { write } for name="property_service" dev="tmpfs" ino=6933 scontext=u:r:priv_app:s0:c512,c768 tcontext=u:object_r:property_socket:s0 tclass=sock_file permissive=0
11-14 20:30:44.280  8025  8047 D libEGL  : Emulator has host GPU support, qemu.gles is set to 1.
11-14 20:30:44.280  8025  8047 W libc    : Unable to set property "qemu.gles" to "1": connection failed; errno=13 (Permission denied)
11-14 20:30:44.300  8025  8047 D libEGL  : loaded /vendor/lib/egl/libEGL_emulation.so
11-14 20:30:44.301  8025  8047 D libEGL  : loaded /vendor/lib/egl/libGLESv1_CM_emulation.so
11-14 20:30:44.301  8025  8047 D libEGL  : loaded /vendor/lib/egl/libGLESv2_emulation.so
11-14 20:30:44.332  8025  8045 D HostConnection: HostConnection::get() New Host Connection established 0xd644c190, tid 8045
11-14 20:30:44.334  8025  8045 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:44.335  8025  8045 W OpenGLRenderer: Failed to choose config with EGL_SWAP_BEHAVIOR_PRESERVED, retrying without...
11-14 20:30:44.351  8025  8045 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 0 0
11-14 20:30:44.351  8025  8045 D EGL_emulation: eglCreateContext: 0xd641a480: maj 2 min 0 rcv 2
11-14 20:30:44.370  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:44.374  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 3342336
11-14 20:30:44.397  1675  1675 I hwservicemanager: getTransport: Cannot find entry android.hardware.graphics.mapper@3.0::IMapper/default in either framework or device manifest.
11-14 20:30:44.399  8025  8045 W Gralloc3: mapper 3.x is not supported
11-14 20:30:44.400  8025  8045 D HostConnection: createUnique: call
11-14 20:30:44.400  8025  8045 D HostConnection: HostConnection::get() New Host Connection established 0xd644c2d0, tid 8045
11-14 20:30:44.402  8025  8045 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:44.402  8025  8045 D eglCodecCommon: allocate: Ask for block of size 0x1000
11-14 20:30:44.402  8025  8045 D eglCodecCommon: allocate: ioctl allocate returned offset 0x3ff688000 size 0x2000
11-14 20:30:44.402  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 3342336
11-14 20:30:44.408  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 3342336
11-14 20:30:44.408  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:44.410  8025  8045 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 1 0
11-14 20:30:44.451  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 1269760
11-14 20:30:44.460  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 1269760
11-14 20:30:44.464  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:44.464  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 1269760
11-14 20:30:44.476  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:44.476  2017  2039 I chatty  : uid=1000(system) android.anim identical 8 lines
11-14 20:30:44.476  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:44.478  2017  2045 I ActivityTaskManager: Displayed com.google.android.packageinstaller/com.android.packageinstaller.UninstallerActivity: +268ms
11-14 20:30:44.479  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:44.520  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.214  2017  3342 I ActivityTaskManager: START u0 {flg=0x2000000 cmp=com.google.android.packageinstaller/com.android.packageinstaller.UninstallUninstalling (has extras)} from uid 10059
11-14 20:30:44.635  2163  2477 I chatty  : uid=10101(com.android.systemui) RenderThread identical 14 lines
11-14 20:30:44.651  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.237  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:45.237  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:45.249  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:45.249  8025  8045 D OpenGLRenderer: endAllActiveAnimators on 0xbec06400 (RippleDrawable) with handle 0xbec30150
11-14 20:30:45.255  2017  3342 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.256  2017  3342 I chatty  : uid=1000(system) Binder:2017_1A identical 38 lines
11-14 20:30:45.256  2017  3342 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.257  2017  6467 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.257  2017  6467 I chatty  : uid=1000(system) Binder:2017_20 identical 8 lines
11-14 20:30:45.257  2017  6467 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.258  8025  8025 W ActivityThread: handleWindowVisibility: no activity for token android.os.BinderProxy@443e27
11-14 20:30:45.276  2017  2046 I ActivityManager: Force stopping com.osherdahan.EzScan appid=10137 user=0: deletePackageX
11-14 20:30:45.332  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 2031616
11-14 20:30:45.336  2017  2058 I PackageManager: Removing old permission tree: com.osherdahan.EzScan.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION from package com.osherdahan.EzScan
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_DOCUMENTS from package com.google.android.youtube (protectionLevel=262146 flags=0x20dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.INTERACT_ACROSS_PROFILES from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_SOUND_TRIGGER from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.CAPTURE_AUDIO_OUTPUT from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_USB from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.CONTROL_INCALL_EXPERIENCE from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.WRITE_APN_SETTINGS from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.SUBSTITUTE_SHARE_TARGET_APP_NAME_AND_ICON from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.CAPTURE_MEDIA_OUTPUT from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.MODIFY_AUDIO_ROUTING from package com.google.android.googlequicksearchbox (protectionLevel=18 flags=0x28dbbec5)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission com.google.android.googleapps.permission.GOOGLE_AUTH from package com.android.providers.calendar (protectionLevel=2 flags=0x30883e45)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission com.google.android.googleapps.permission.GOOGLE_AUTH.cl from package com.android.providers.calendar (protectionLevel=2 flags=0x30883e45)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.WRITE_SECURE_SETTINGS from package com.google.android.apps.enterprise.dmagent (protectionLevel=50 flags=0x30083e05)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.CONNECTIVITY_INTERNAL from package com.google.android.apps.enterprise.dmagent (protectionLevel=18 flags=0x30083e05)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_USB from package com.google.android.apps.enterprise.dmagent (protectionLevel=18 flags=0x30083e05)
11-14 20:30:45.338  2017  2058 I PackageManager: Un-granting permission android.permission.CHANGE_COMPONENT_ENABLED_STATE from package com.google.android.apps.enterprise.dmagent (protectionLevel=18 flags=0x30083e05)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_CA_CERTIFICATES from package com.google.android.apps.enterprise.dmagent (protectionLevel=18 flags=0x30083e05)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_USERS from package com.google.android.apps.enterprise.dmagent (protectionLevel=18 flags=0x30083e05)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.READ_PRIVILEGED_PHONE_STATE from package com.google.android.apps.messaging (protectionLevel=18 flags=0x28cbbec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.MODIFY_PHONE_STATE from package com.google.android.apps.messaging (protectionLevel=18 flags=0x28cbbec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.READ_PRECISE_PHONE_STATE from package com.google.android.apps.messaging (protectionLevel=18 flags=0x28cbbec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.CONNECTIVITY_USE_RESTRICTED_NETWORKS from package com.google.android.apps.messaging (protectionLevel=18 flags=0x28cbbec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission com.google.android.setupwizard.READ_DEVICE_ORIGIN from package com.google.android.apps.messaging (protectionLevel=18 flags=0x28cbbec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.HIDE_NON_SYSTEM_OVERLAY_WINDOWS from package com.android.vending (protectionLevel=258 flags=0x28cabec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.SEND_DOWNLOAD_COMPLETED_INTENTS from package com.android.vending (protectionLevel=2 flags=0x28cabec5)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.SYSTEM_ALERT_WINDOW from package com.smartinvoices (protectionLevel=1250 flags=0x28c83e46)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.BIND_WALLPAPER from package com.android.camera2 (protectionLevel=18 flags=0x20d8bc45)
11-14 20:30:45.339  2017  2058 I PackageManager: Un-granting permission android.permission.SYSTEM_ALERT_WINDOW from package com.receiptapp (protectionLevel=1250 flags=0x28c83e46)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.INTERACT_ACROSS_PROFILES from package com.google.android.deskclock (protectionLevel=18 flags=0x30cbbec5)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.REQUEST_INSTALL_PACKAGES from package com.google.android.gm (protectionLevel=66 flags=0x28dbbec5)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.STATUS_BAR from package com.google.android.apps.tachyon (protectionLevel=18 flags=0x30c9bec5)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.STOP_APP_SWITCHES from package com.google.android.apps.tachyon (protectionLevel=18 flags=0x30c9bec5)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.CONNECTIVITY_USE_RESTRICTED_NETWORKS from package com.google.android.captiveportallogin (protectionLevel=18 flags=0x38c8be45)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.NETWORK_BYPASS_PRIVATE_DNS from package com.google.android.captiveportallogin (protectionLevel=2 flags=0x38c8be45)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.REQUEST_INSTALL_PACKAGES from package com.google.android.apps.docs (protectionLevel=66 flags=0x28cbbec5)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.SYSTEM_ALERT_WINDOW from package host.exp.exponent (protectionLevel=1250 flags=0x2898be44)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_DOCUMENTS from package host.exp.exponent (protectionLevel=262146 flags=0x2898be44)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.WRITE_SETTINGS from package host.exp.exponent (protectionLevel=1218 flags=0x2898be44)
11-14 20:30:45.340  2017  2058 I PackageManager: Un-granting permission android.permission.INTERACT_ACROSS_USERS from package com.google.android.syncadapters.contacts (protectionLevel=50 flags=0x20883e45)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.REQUEST_INSTALL_PACKAGES from package com.android.chrome (protectionLevel=66 flags=0xa0cbbec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.WRITE_EMBEDDED_SUBSCRIPTIONS from package com.google.android.gms (protectionLevel=50 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.CAPTURE_VIDEO_OUTPUT from package com.google.android.gms (protectionLevel=2 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.FORCE_STOP_PACKAGES from package com.google.android.gms (protectionLevel=18 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.MODIFY_DEFAULT_AUDIO_EFFECTS from package com.google.android.gms (protectionLevel=18 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_DEVICE_ADMINS from package com.google.android.gms (protectionLevel=2 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_ACTIVITY_STACKS from package com.google.android.gms (protectionLevel=2 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.CAPTURE_SECURE_VIDEO_OUTPUT from package com.google.android.gms (protectionLevel=2 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.MANAGE_ROLLBACKS from package com.google.android.gms (protectionLevel=514 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.MEDIA_CONTENT_CONTROL from package com.google.android.gms (protectionLevel=18 flags=0xa0cabec5)
11-14 20:30:45.341  2017  2058 I PackageManager: Un-granting permission android.permission.HIDE_NON_SYSTEM_OVERLAY_WINDOWS from package com.google.android.gms (protectionLevel=258 flags=0xa0cabec5)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission android.permission.UPDATE_APP_OPS_STATS from package com.google.android.tts (protectionLevel=274 flags=0x34cbbec5)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission android.permission.START_ACTIVITIES_FROM_BACKGROUND from package com.google.android.tts (protectionLevel=49682 flags=0x34cbbec5)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission com.google.android.googleapps.permission.GOOGLE_AUTH from package com.google.android.videos (protectionLevel=2 flags=0x30dbbec5)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission android.permission.SYSTEM_ALERT_WINDOW from package com.receiptapp1 (protectionLevel=1250 flags=0x28c83e46)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission android.permission.REQUEST_INSTALL_PACKAGES from package com.topjohnwu.magisk (protectionLevel=66 flags=0xb0c83e44)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission android.permission.WRITE_MEDIA_STORAGE from package com.google.android.apps.photos (protectionLevel=18 flags=0x38dbbec5)
11-14 20:30:45.357  2017  2058 I PackageManager: Un-granting permission android.permission.INTERACT_ACROSS_PROFILES from package com.google.android.calendar (protectionLevel=18 flags=0x30cbbec5)
11-14 20:30:45.358  2017  2058 I PackageManager: Un-granting permission android.permission.SET_WALLPAPER_COMPONENT from package com.google.android.apps.wallpaper (protectionLevel=18 flags=0x20cbbec5)
11-14 20:30:45.358  2017  2058 I PackageManager: Un-granting permission android.permission.BIND_WALLPAPER from package com.google.android.apps.wallpaper (protectionLevel=18 flags=0x20cbbec5)
11-14 20:30:45.358  2017  2058 I PackageManager: Un-granting permission android.permission.CHANGE_OVERLAY_PACKAGES from package com.google.android.apps.wallpaper (protectionLevel=18 flags=0x20cbbec5)
11-14 20:30:45.358  2017  2058 I PackageManager: Un-granting permission android.permission.WRITE_SECURE_SETTINGS from package com.google.android.apps.wallpaper (protectionLevel=50 flags=0x20cbbec5)
11-14 20:30:45.356  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 2031616
11-14 20:30:45.360  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:45.360  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 2031616
11-14 20:30:45.365  2017  2058 I PackageManager: Un-granting permission android.permission.INTERACT_ACROSS_PROFILES from package com.google.android.inputmethod.latin (protectionLevel=18 flags=0x20cabec5)
11-14 20:30:45.407  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 1863680
11-14 20:30:45.413  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 1863680
11-14 20:30:45.417  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 1863680
11-14 20:30:45.417  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:45.428  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.428  2017  2039 I chatty  : uid=1000(system) android.anim identical 18 lines
11-14 20:30:45.428  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.429  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:45.445  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.451  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:45.454  1834  1834 I keystore: clear_uid 10137
11-14 20:30:45.462  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.466  2017  2058 E PermissionMonitor: unknown permission type: -1for uid: 10137
11-14 20:30:45.467  1770  1770 E TrafficController: Failed to clean up the permission for 10137: No such file or directory
11-14 20:30:45.467  1770  1770 I netd    : trafficSetNetPermForUids(-1, [10137]) <0.11ms>
11-14 20:30:45.467  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.517  2163  2477 I chatty  : uid=10101(com.android.systemui) RenderThread identical 6 lines
11-14 20:30:45.520  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.529  2017  2058 I system_server: Explicit concurrent copying GC freed 84982(4228KB) AllocSpace objects, 7(512KB) LOS objects, 28% free, 15MB/21MB, paused 577us total 48.539ms
11-14 20:30:45.534  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.538  2017  2058 I ActivityManager: Force stopping com.osherdahan.EzScan appid=10137 user=0: pkg removed
11-14 20:30:45.537  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.539  2017  5449 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.539  2017  5449 I chatty  : uid=1000(system) Binder:2017_1C identical 8 lines
11-14 20:30:45.539  2017  5449 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.541  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.544  2017  6171 I chatty  : uid=1000(system) Binder:2017_1E identical 38 lines
11-14 20:30:45.544  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl: Exception when retrieving package:com.osherdahan.EzScan
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl: android.content.pm.PackageManager$NameNotFoundException: com.osherdahan.EzScan
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.ApplicationPackageManager.getPackageInfoAsUser(ApplicationPackageManager.java:190)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:159)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.settings.applications.appinfo.AppButtonsPreferenceController.retrieveAppEntry(AppButtonsPreferenceController.java:353)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.settings.applications.appinfo.AppButtonsPreferenceController.refreshUi(AppButtonsPreferenceController.java:633)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.settings.applications.appinfo.AppButtonsPreferenceController.refreshAndFinishIfPossible(AppButtonsPreferenceController.java:480)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.settings.applications.appinfo.AppButtonsPreferenceController.handleActivityResult(AppButtonsPreferenceController.java:281)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.settings.applications.appinfo.AppInfoDashboardFragment.onActivityResult(AppInfoDashboardFragment.java:393)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at androidx.fragment.app.FragmentActivity.onActivityResult(FragmentActivity.java:170)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.settings.SettingsActivity.onActivityResult(SettingsActivity.java:343)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.Activity.dispatchActivityResult(Activity.java:8110)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.ActivityThread.deliverResults(ActivityThread.java:4838)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.ActivityThread.handleSendResult(ActivityThread.java:4886)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.servertransaction.ActivityResultItem.execute(ActivityResultItem.java:51)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.ActivityThread$H.handleMessage(ActivityThread.java:2016)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.os.Handler.dispatchMessage(Handler.java:107)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.os.Looper.loop(Looper.java:214)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at android.app.ActivityThread.main(ActivityThread.java:7356)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at java.lang.reflect.Method.invoke(Native Method)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:492)
11-14 20:30:45.550  7972  7972 E AppButtonsPrefCtl:     at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:930)
11-14 20:30:45.551  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.553  2017  2058 E HistoricalRegistry: Interaction before persistence initialized
11-14 20:30:45.551  2017  6171 I chatty  : uid=1000(system) Binder:2017_1E identical 8 lines
11-14 20:30:45.551  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.556  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.567  2017  2017 I RoleManagerService: Granting default permissions...
11-14 20:30:45.574  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.android.musicfx/.Compatibility$Receiver
11-14 20:30:45.574  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.android.vending/com.google.android.finsky.packagemonitor.impl.PackageMonitorReceiverImpl$RegisteredReceiver
11-14 20:30:45.576  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.android.vending/com.google.android.finsky.packagemonitor.backgroundimpl.BackgroundPackageMonitorReceiverImpl$RegisteredReceiver
11-14 20:30:45.576  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.android.vending/com.google.android.finsky.instantapps.appmanagement.InstantAppRemoveMonitor
11-14 20:30:45.576  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.libraries.social.peoplekit.thirdparty.viewcontrollers.ThirdPartyReceiver
11-14 20:30:45.576  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.google.android.apps.photos/com.google.android.libraries.social.peoplekit.thirdparty.viewcontrollers.ThirdPartyReceiver
11-14 20:30:45.577  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.google.android.gms/.chimera.GmsIntentOperationService$PersistentTrustedReceiver
11-14 20:30:45.577  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
11-14 20:30:45.577  2017  2046 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.osherdahan.EzScan flg=0x4000010 (has extras) } to com.google.android.videos/com.google.android.libraries.social.peoplekit.thirdparty.viewcontrollers.ThirdPartyReceiver
11-14 20:30:45.568  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.578  2922  2922 I eyvr    : (REDACTED) O received %s
11-14 20:30:45.587  8025  8045 D EGL_emulation: eglMakeCurrent: 0xd641a480: ver 2 0 (tinfo 0xd640f320)
11-14 20:30:45.594  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.597  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.597  2017  6171 I chatty  : uid=1000(system) Binder:2017_1E identical 8 lines
11-14 20:30:45.597  2017  6171 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.599  4084  4099 W ding:backgroun: Reducing the number of considered missed Gc histogram windows from 106 to 100
11-14 20:30:45.603  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.606  2017  6171 W ActivityTaskManager: Finishing task with all activities already finished
11-14 20:30:45.607  2017  6171 W ActivityTaskManager: Duplicate finish request for ActivityRecord{c41372c u0 com.android.settings/.applications.InstalledAppDetails t15 f}
11-14 20:30:45.608  2017  2046 I ActivityManager: Killing 6893:com.android.mtp/u0a45 (adj 975): empty #17
11-14 20:30:45.615  2017  2035 E PackageManager: failed to find package com.osherdahan.EzScan
11-14 20:30:45.615  2017  2035 E OverlayManager: Failed to change enabled overlays for com.osherdahan.EzScan user 0
11-14 20:30:45.615  2163  2477 I chatty  : uid=10101(com.android.systemui) RenderThread identical 2 lines
11-14 20:30:45.618  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.626  2420  2443 W s.nexuslaunche: Reducing the number of considered missed Gc histogram windows from 112 to 100
11-14 20:30:45.632  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:45.644  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:45.651  1771  1771 D Zygote  : Forked child process 8059
11-14 20:30:45.659  8059  8059 W ndroid.keychai: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:45.669  2017  2047 I ActivityManager: Start proc 8059:com.android.keychain/1000 for service {com.android.keychain/com.android.keychain.KeyChainService}
11-14 20:30:45.674  1771  1771 I Zygote  : Process 6893 exited due to signal 9 (Killed)
11-14 20:30:45.685  8059  8059 E ndroid.keychai: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:45.692  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.698  7214  7226 W d.process.acor: Reducing the number of considered missed Gc histogram windows from 122 to 100
11-14 20:30:45.711  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10045 pid 6893 in 81ms
11-14 20:30:45.731  2744  2757 I gle.android.gm: Background concurrent copying GC freed 24110(1440KB) AllocSpace objects, 2(40KB) LOS objects, 27% free, 15MB/21MB, paused 527us total 185.873ms
11-14 20:30:45.739  7568  7603 D EGL_emulation: eglMakeCurrent: 0xde4909c0: ver 2 0 (tinfo 0xb05a5b40)
11-14 20:30:45.740  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:45.745  2017  2117 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-14 20:30:45.746  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:45.751  2420  2932 D EGL_emulation: eglMakeCurrent: 0xe96530e0: ver 2 0 (tinfo 0xde4d58c0)
11-14 20:30:45.755  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.771  2332  2332 D CarrierSvcBindHelper: No carrier app for: 0
11-14 20:30:45.773  1788  4765 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:45.774  1788  1788 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 9850880
11-14 20:30:45.779  2017  2017 W Looper  : Slow dispatch took 154ms main h=android.app.ActivityThread$H c=android.app.-$$Lambda$LoadedApk$ReceiverDispatcher$Args$_BumDX2UKsnxLVrE6UJsJZkotuA@ffc2157 m=0
11-14 20:30:45.779  2017  2017 W Looper  : Slow delivery took 222ms main h=android.app.ActivityThread$H c=android.app.-$$Lambda$LoadedApk$ReceiverDispatcher$Args$_BumDX2UKsnxLVrE6UJsJZkotuA@cce444 m=0
11-14 20:30:45.781  1770  1770 I netd    : trafficSwapActiveStatsMap() <37.67ms>
11-14 20:30:45.782  7568  7568 I cjrg    : onStart
11-14 20:30:45.783  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.785  2017  2039 I chatty  : uid=1000(system) android.anim identical 8 lines
11-14 20:30:45.785  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.785  7568  7568 I cjrg    : onResume
11-14 20:30:45.785  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onFinishInput():3086
11-14 20:30:45.785  1770  1770 I netd    : tetherGetStats() <3.78ms>
11-14 20:30:45.788  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 0, locked = false
11-14 20:30:45.789  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.onStartInput():1899 onStartInput(EditorInfo{EditorInfo{packageName=com.google.android.apps.nexuslauncher, inputType=0, inputTypeString=NULL, enableLearning=false, autoCorrection=false, autoComplete=false, imeOptions=0, privateImeOptions=null, actionName=UNSPECIFIED, actionLabel=null, initialSelStart=-1, initialSelEnd=-1, initialCapsMode=0, label=null, fieldId=-1, fieldName=null, extras=null, hintText=null, hintLocales=[]}}, false)
11-14 20:30:45.789  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.789  2017  2039 I chatty  : uid=1000(system) android.anim identical 8 lines
11-14 20:30:45.789  2017  2039 W InputReader: Device has associated, but no associated display id.
11-14 20:30:45.790  2478  2478 I GoogleInputMethodService: GoogleInputMethodService.updateDeviceLockedStatus():2155 repeatCheckTimes = 1, locked = false
11-14 20:30:45.793  2478  2478 I AndroidIME: InputBundleManager.loadActiveInputBundleId():450 loadActiveInputBundleId: und-Latn-x-password, password
11-14 20:30:45.793  1788  1823 D gralloc_ranchu: gralloc_alloc: Creating ashmem region of size 6307840
11-14 20:30:45.798  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.836  8001  8021 I SystemConfig: Adding association: com.google.android.as <- com.android.providers.contacts
11-14 20:30:45.836  8001  8021 I SystemConfig: Adding association: com.google.android.as <- com.android.providers.media
11-14 20:30:45.836  8001  8021 I SystemConfig: Adding association: com.google.android.as <- com.android.providers.telephony
11-14 20:30:45.836  8001  8021 I SystemConfig: Adding association: com.google.android.as <- com.android.systemui
11-14 20:30:45.836  8001  8021 I SystemConfig: Adding association: com.google.android.as <- com.google.android.gms
11-14 20:30:45.836  8001  8021 I SystemConfig: Adding association: com.google.android.as <- com.google.android.gsf
11-14 20:30:45.853  2017  2036 W Looper  : Slow dispatch took 115ms android.ui h=com.android.server.am.ActivityManagerService$UiHandler c=null m=53
11-14 20:30:45.857  8001  8021 W SystemConfig: No directory /product_services/etc/sysconfig, skipping
11-14 20:30:45.857  8001  8021 W SystemConfig: No directory /product_services/etc/permissions, skipping
11-14 20:30:45.821  2163  2477 I chatty  : uid=10101(com.android.systemui) RenderThread identical 1 line
11-14 20:30:45.825  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:30:45.865  1771  1771 D Zygote  : Forked child process 8085
11-14 20:30:45.870  8059  8059 I ndroid.keychai: The ClassLoaderContext is a special shared library.
11-14 20:30:45.870  7568  7632 E algt    : Stopping hotword detector since user is hotword OPA ineligible
11-14 20:30:45.873  7568  7632 I acql    : (REDACTED) Updating hotword opa ineligibility to %b
11-14 20:30:45.875  2017  2047 I ActivityManager: Start proc 8085:com.android.documentsui/u0a49 for broadcast {com.android.documentsui/com.android.documentsui.PackageReceiver}
11-14 20:30:45.876  2017  2017 W ActivityManager: Unable to start service Intent { act=android.service.appprediction.AppPredictionService cmp=com.google.android.as/com.google.android.apps.miphone.aiai.app.AiAiPredictionService } U=0: not found
11-14 20:30:45.876  2017  2017 W RemoteAppPredictionService: could not bind to Intent { act=android.service.appprediction.AppPredictionService cmp=com.google.android.as/com.google.android.apps.miphone.aiai.app.AiAiPredictionService } using flags 67108865
11-14 20:30:45.882  2017  2125 D WifiConfigManager: Remove all networks for app ApplicationInfo{8eb3aed com.osherdahan.EzScan}
11-14 20:30:45.888  2744  8056 I Blockstore: (REDACTED) [DataStoreImpl] Clearing all the restore credential for %s packages
11-14 20:30:45.889  2744  8056 W Blockstore: [DataStoreImpl] Does not contain gms package key space. [CONTEXT service_id=258 ]
11-14 20:30:45.890  2744  8056 I Blockstore: (REDACTED) [PackageIntentOperation] Deleted restore credential for package %s is successful: %s
11-14 20:30:45.897  2562  8082 I Fitness : (REDACTED) FitCleanupIntentOperation received Intent %s
11-14 20:30:45.898  2017  2017 I ConditionProviders: Disallowing condition provider com.osherdahan.EzScan
11-14 20:30:45.899  2922  2922 I fmpg    : (REDACTED) Created gRPC endpoint for service %s
11-14 20:30:45.899  2744  8056 I Blockstore: (REDACTED) [DataStoreImpl] Setting IsLastInstallationDataPerPackage bit to %s for package %s
11-14 20:30:45.904  7568  7632 I agyx    : getLocaleToModelSpecsMap
11-14 20:30:45.904  7568  7632 I agyx    : Fetching latest config from MDD...
11-14 20:30:45.905  7568  7632 I agyx    : (REDACTED) Found map of size: %d
11-14 20:30:45.905  8085  8085 W oid.documentsu: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:45.906  1807  1807 D AF::TrackHandle: OpPlayAudio: track:55 usage:13 not muted
11-14 20:30:45.910  2017  2017 W Looper  : Drained
11-14 20:30:45.914  1807  1807 I chatty  : uid=1041(audioserver) /system/bin/audioserver identical 14 lines
11-14 20:30:45.914  1807  1807 D AF::TrackHandle: OpPlayAudio: track:55 usage:13 not muted
11-14 20:30:45.915  7568  7632 I algt    : (REDACTED) Initializing MicroDataManager InitializeType-%d, isForced-%b, isActivePhoneEnrollment-%b isActiveGoogleHomeEnrollment-%b
11-14 20:30:45.917  2922  3277 I eera    : (REDACTED) Starting to notify all %d listeners.
11-14 20:30:45.917  2922  3277 I eera    : Finished notifying all listeners.
11-14 20:30:45.918  2922  3274 I ecrx    : (REDACTED) [%s] On new data value: %s.
11-14 20:30:45.918  7568  7632 I agyx    : getLocaleToModelSpecsMap
11-14 20:30:45.918  7568  7632 I agyx    : Fetching latest config from MDD...
11-14 20:30:45.918  7568  7632 I agyx    : (REDACTED) Found map of size: %d
11-14 20:30:45.918  7568  7632 I ahba    : (REDACTED) Location for model with model type: %s and locale: %s, is : %s
11-14 20:30:45.918  2922  3224 I ygs     : (REDACTED) On new legacy external hotword consumer configuration: %s.
11-14 20:30:45.919  2922  3224 I ygs     : (REDACTED) Updating Bisto HotwordInformation: %s
11-14 20:30:45.919  2922  3224 I ygs     : Fetching HotwordInformation
11-14 20:30:45.919  2922  3224 I ergl    : get hotword information from Legacy
11-14 20:30:45.919  2922  3277 I ergh    : Account not changed, ignore update.
11-14 20:30:45.919  2922  3277 I ergb    : #getHotwordInformation
11-14 20:30:45.927  2922  2922 I ergb    : (REDACTED) Connected to HotwordService. ComponentName %s, service %s
11-14 20:30:45.928  8085  8085 E oid.documentsu: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:45.928  2922  3277 I ergb    : #getHotwordInformation bindService
11-14 20:30:45.931  2922  8113 I ergb    : Handing HotwordService connection in executor.
11-14 20:30:45.932  2420  2445 W System  : A resource failed to call release.
11-14 20:30:45.933  2420  2445 W System  : A resource failed to call release.
11-14 20:30:45.933  7568  7632 E algt    : Stopping hotword detector since user is hotword OPA ineligible
11-14 20:30:45.934  7568  7632 I acql    : (REDACTED) #takeChangeMicroDetectorMode [mIsBargeInEnabled: %b, mCurrentDetectionMode: %s]
11-14 20:30:45.934  7568  7632 I acql    : (REDACTED) Should stop hotword detection immediately - %b
11-14 20:30:45.935  2922  3277 I eera    : (REDACTED) Starting to notify all %d listeners.
11-14 20:30:45.936  2922  3277 I eera    : Finished notifying all listeners.
11-14 20:30:45.936  2922  3277 I ecrx    : (REDACTED) [%s] On new data value: %s.
11-14 20:30:45.937  7568  8077 I agyx    : getLocaleToModelSpecsMap
11-14 20:30:45.937  7568  8077 I agyx    : Fetching latest config from MDD...
11-14 20:30:45.937  7568  8077 I agyx    : (REDACTED) Found map of size: %d
11-14 20:30:45.938  7568  8077 I agyx    : getLocaleToModelSpecsMap
11-14 20:30:45.938  7568  8077 I agyx    : Fetching latest config from MDD...
11-14 20:30:45.938  7568  8077 I agyx    : (REDACTED) Found map of size: %d
11-14 20:30:45.938  7568  8077 I ahal    : (REDACTED) hasHotwordEverywhere-%b
11-14 20:30:45.939  7568  7632 E algt    : Stopping hotword detector since user is hotword OPA ineligible
11-14 20:30:45.940  7568  7632 I acql    : (REDACTED) #takeChangeMicroDetectorMode [mIsBargeInEnabled: %b, mCurrentDetectionMode: %s]
11-14 20:30:45.940  7568  7632 I acql    : (REDACTED) Should stop hotword detection immediately - %b
11-14 20:30:45.940  7568  7632 I agyx    : getLocaleToModelSpecsMap
11-14 20:30:45.940  7568  7632 I agyx    : Fetching latest config from MDD...
11-14 20:30:45.940  7568  7632 I agyx    : (REDACTED) Found map of size: %d
11-14 20:30:45.942  2922  3274 I eera    : (REDACTED) Starting to notify all %d listeners.
11-14 20:30:45.942  2922  3274 I eera    : Finished notifying all listeners.
11-14 20:30:45.942  2922  3274 I ecrx    : (REDACTED) [%s] On new data value: %s.
11-14 20:30:45.955  8085  8085 D ApplicationLoaders: Returning zygote-cached class loader: /system/framework/android.hidl.base-V1.0-java.jar
11-14 20:30:45.955  8085  8085 D ApplicationLoaders: Returning zygote-cached class loader: /system/framework/android.hidl.manager-V1.0-java.jar
11-14 20:30:45.955  8085  8085 D ApplicationLoaders: Returning zygote-cached class loader: /system/framework/android.hidl.base-V1.0-java.jar
11-14 20:30:45.956  2744  4589 I Icing   : doRemovePackageData com.osherdahan.EzScan
11-14 20:30:45.966  8085  8085 I oid.documentsu: The ClassLoaderContext is a special shared library.
11-14 20:30:45.968  7568  8077 I ahbh    : (REDACTED) #getHotwordModelFromMobstore [mobstoreUri: %s]
11-14 20:30:45.979  2017  2125 D WifiConfigStore: Writing to stores completed in 80 ms.
11-14 20:30:45.985  2017  2125 E PasspointManager: No app ops listener found for com.osherdahan.EzScan
11-14 20:30:45.988  2017  2125 I DropBoxManagerService: add tag=system_server_wtf isTagEnabled=true flags=0x2
11-14 20:30:46.022  2744  4581 I Icing   : IndexChimeraService.getServiceInterface callingPackage=com.google.android.gms componentName=AppsCorpus serviceId=36
11-14 20:30:46.027  2163  2191 I ndroid.systemu: NativeAlloc concurrent copying GC freed 204041(5336KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 5919KB/11MB, paused 2.219ms total 145.797ms
11-14 20:30:46.030  7568  8077 I HotwordService: (REDACTED) Model ID: %s
11-14 20:30:46.036  2744  2744 D BoundBrokerSvc: onBind: Intent { act=com.google.android.gms.feedback.internal.IFeedbackService dat=chimera-action: cmp=com.google.android.gms/.chimera.GmsBoundBrokerService }
11-14 20:30:46.036  2744  2744 D BoundBrokerSvc: Loading bound service for intent: Intent { act=com.google.android.gms.feedback.internal.IFeedbackService dat=chimera-action: cmp=com.google.android.gms/.chimera.GmsBoundBrokerService }
11-14 20:30:46.040  7568  8077 I HotwordService: (REDACTED) hotwordModelLocation is null %b, locale is %s, re-mapped Chinese locale %s
11-14 20:30:46.046  7568  8077 I HotwordService: (REDACTED) isOpaEligibleAndUserEnabled: %b
11-14 20:30:46.048  2922  8113 I ergb    : HotwordInformation fetch will try to save hotword model.
11-14 20:30:46.049  7568  7632 W acgw    : (REDACTED) Client : %s has no associated SessionController
11-14 20:30:46.049  2922  8113 I ergb    : onSuccess getHotwordInformation
11-14 20:30:46.051  7568  7632 W acgd    : Abort, client detached.
11-14 20:30:46.053  2922  3277 I ergb    : Save the hotword model in the HotwordInformation.
11-14 20:30:46.054  2922  3278 I bbma    : (REDACTED) setHotwordVoiceLocale: prev: %s, new: %s
11-14 20:30:46.054  2922  3278 I bbma    : (REDACTED) setting VM enrollment allowed: %b
11-14 20:30:46.054  2922  3278 I bbma    : (REDACTED) setting speaker ID model presence: %b
11-14 20:30:46.054  2922  3278 I bbma    : (REDACTED) setting hotword model of size: %d bytes
11-14 20:30:46.054  2922  3278 I bbma    : (REDACTED) setting speaker id present: %b
11-14 20:30:46.054  2922  3278 I bbma    : (REDACTED) setting speaker ID model presence: %b
11-14 20:30:46.055  2922  3278 I bbma    : (REDACTED) setting VM enrollment status: %b
11-14 20:30:46.055  2922  3278 I bbma    : (REDACTED) setting phone hotword opt-in: %s
11-14 20:30:46.055  2922  3278 I ygs     : (REDACTED) On new legacy external hotword consumer configuration: %s.
11-14 20:30:46.055  2922  3278 I ygs     : (REDACTED) Updating Bisto HotwordInformation: %s
11-14 20:30:46.055  2922  3278 I ygs     : Fetching HotwordInformation
11-14 20:30:46.055  2922  3274 I ergh    : Account not changed, ignore update.
11-14 20:30:46.056  2922  3278 I ergl    : get hotword information from Legacy
11-14 20:30:46.056  2922  3274 I ergb    : #getHotwordInformation
11-14 20:30:46.058  2922  3274 I ergb    : #getHotwordInformation bindService
11-14 20:30:46.059  2922  2922 I ergb    : (REDACTED) Connected to HotwordService. ComponentName %s, service %s
11-14 20:30:46.059  2922  8113 I ergb    : Handing HotwordService connection in executor.
11-14 20:30:46.061  7568  7733 I agyx    : getLocaleToModelSpecsMap
11-14 20:30:46.061  7568  7733 I agyx    : Fetching latest config from MDD...
11-14 20:30:46.062  7568  7733 I agyx    : (REDACTED) Found map of size: %d
11-14 20:30:46.062  8085  8085 D DocumentsApplication: OverlayManager.setEnabled() result: true
11-14 20:30:46.065  7568  7733 I ahal    : (REDACTED) hasHotwordEverywhere-%b
11-14 20:30:46.071  1771  1771 D Zygote  : Forked child process 8139
11-14 20:30:46.073  8139  8139 W d.process.medi: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:46.078  2017  2047 I ActivityManager: Start proc 8139:android.process.media/u0a45 for broadcast {com.android.providers.media/com.android.providers.media.MediaReceiver}
11-14 20:30:46.084  8139  8139 E d.process.medi: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:46.094  2744  2794 I Icing   : IndexChimeraService.getServiceInterface callingPackage=com.google.android.gms componentName=null serviceId=30
11-14 20:30:46.103  7568  7733 I ahbh    : (REDACTED) #getHotwordModelFromMobstore [mobstoreUri: %s]
11-14 20:30:46.111  8139  8139 I d.process.medi: The ClassLoaderContext is a special shared library.
11-14 20:30:46.113  2744  4589 I Icing   : Usage reports ok 2, Failed Usage reports 0, indexed 0, rejected 0
11-14 20:30:46.114  1771  1771 D Zygote  : Forked child process 8159
11-14 20:30:46.116  8159  8159 W droid.apps.doc: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:46.117  2017  2047 I ActivityManager: Start proc 8159:com.google.android.apps.docs/u0a133 for content provider {com.google.android.apps.docs/com.google.android.apps.docs.common.storagebackend.StorageBackendContentProvider}
11-14 20:30:46.122  8159  8159 E droid.apps.doc: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:46.127  7568  7733 I HotwordService: (REDACTED) Model ID: %s
11-14 20:30:46.127  7568  7733 I HotwordService: (REDACTED) hotwordModelLocation is null %b, locale is %s, re-mapped Chinese locale %s
11-14 20:30:46.133  7568  7733 I HotwordService: (REDACTED) isOpaEligibleAndUserEnabled: %b
11-14 20:30:46.134  2922  8113 I ergb    : HotwordInformation fetch will try to save hotword model.
11-14 20:30:46.135  7568  7632 W acgw    : (REDACTED) Client : %s has no associated SessionController
11-14 20:30:46.135  7568  7632 W acgd    : Abort, client detached.
11-14 20:30:46.136  2922  8113 I ergb    : onSuccess getHotwordInformation
11-14 20:30:46.145  2922  3274 I ergb    : Save the hotword model in the HotwordInformation.
11-14 20:30:46.146  2922  3279 I bbma    : (REDACTED) setHotwordVoiceLocale: prev: %s, new: %s
11-14 20:30:46.146  2922  3279 I bbma    : (REDACTED) setting VM enrollment allowed: %b
11-14 20:30:46.146  2922  3279 I bbma    : (REDACTED) setting speaker ID model presence: %b
11-14 20:30:46.146  2922  3279 I bbma    : (REDACTED) setting hotword model of size: %d bytes
11-14 20:30:46.146  2922  3279 I bbma    : (REDACTED) setting speaker id present: %b
11-14 20:30:46.147  2922  3279 I bbma    : (REDACTED) setting speaker ID model presence: %b
11-14 20:30:46.147  2922  3279 I bbma    : (REDACTED) setting VM enrollment status: %b
11-14 20:30:46.147  2922  3279 I bbma    : (REDACTED) setting phone hotword opt-in: %s
11-14 20:30:46.152  2744  4589 I Icing   : Usage reports ok 0, Failed Usage reports 0, indexed 0, rejected 0
11-14 20:30:46.166  2017  2911 I ActivityManager: Killing 3367:com.google.android.apps.messaging/u0a122 (adj 985): empty #17
11-14 20:30:46.167  2744  4589 I Icing   : Indexing com.google.android.gms-apps from com.google.android.gms
11-14 20:30:46.176  8159  8159 I droid.apps.doc: The ClassLoaderContext is a special shared library.
11-14 20:30:46.179  8139  8139 I d.process.medi: The ClassLoaderContext is a special shared library.
11-14 20:30:46.180  2017  2033 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10122] ], android.os.BinderProxy@9f0d090)
11-14 20:30:46.180  2017  3342 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ LISTEN id=36, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10122] ], android.os.BinderProxy@38418e)
11-14 20:30:46.180  2017  2867 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10122] ], android.os.BinderProxy@a74dd89)
11-14 20:30:46.181  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10122] ] (release request)
11-14 20:30:46.181  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10122] ] (release request)
11-14 20:30:46.192  2744  4589 I Icing   : Indexing done com.google.android.gms-apps
11-14 20:30:46.202  8159  8159 W droid.apps.doc: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.202  8159  8159 I chatty  : uid=10133(com.google.android.apps.docs) identical 1 line
11-14 20:30:46.202  8159  8159 W droid.apps.doc: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.210  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10122 pid 3367 in 44ms
11-14 20:30:46.210  1771  1771 I Zygote  : Process 3367 exited due to signal 9 (Killed)
11-14 20:30:46.213  8139  8179 I MediaProvider: Begin Intent { act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.osherdahan.EzScan flg=0x5000010 cmp=com.android.providers.media/.MediaService (has extras) }
11-14 20:30:46.229  8139  8179 I MediaProvider: End Intent { act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.osherdahan.EzScan flg=0x5000010 cmp=com.android.providers.media/.MediaService (has extras) }
11-14 20:30:46.230  2017  2867 I ActivityManager: Killing 5569:com.google.android.youtube/u0a131 (adj 985): empty #17
11-14 20:30:46.231  1771  1771 D Zygote  : Forked child process 8182
11-14 20:30:46.233  7568  8120 I dmsd    : (REDACTED) soft deleting data for %s
11-14 20:30:46.233  8182  8182 W android.vendin: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:46.236  8182  8182 E android.vendin: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:46.236  2017  2047 I ActivityManager: Start proc 8182:com.android.vending/u0a95 for broadcast {com.android.vending/com.google.android.finsky.packagemonitor.impl.PackageMonitorReceiverImpl$RegisteredReceiver}
11-14 20:30:46.237  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:46.237  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:46.246  7568  8120 I aklz    : refreshDeviceAppInfoForAccount done.
11-14 20:30:46.246  7568  7597 I dmru    : Scheduling deletion propagation for Geller data.
11-14 20:30:46.246  7568  8120 I dmru    : Performing deletion propagation for Geller data.
11-14 20:30:46.262  7568  7600 W aklz    : missing version info.
11-14 20:30:46.271  1771  1771 I Zygote  : Process 5569 exited due to signal 9 (Killed)
11-14 20:30:46.275  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10131 pid 5569 in 44ms
11-14 20:30:46.295  8182  8182 I android.vendin: The ClassLoaderContext is a special shared library.
11-14 20:30:46.302  2017  6176 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ], android.os.BinderProxy@96db4c1)
11-14 20:30:46.302  2017  2891 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=65, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ], android.os.BinderProxy@f0ef466)
11-14 20:30:46.302  2017  2033 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ LISTEN id=66, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&FOREGROUND Uid: 10131] ], android.os.BinderProxy@4b953a7)
11-14 20:30:46.303  2017  6176 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ], android.os.BinderProxy@48fb054)
11-14 20:30:46.303  2017  2891 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=64, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ], android.os.BinderProxy@ddfdbfd)
11-14 20:30:46.303  2017  2033 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ TRACK_DEFAULT id=70, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ], android.os.BinderProxy@5f0f2)
11-14 20:30:46.303  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ] (release request)
11-14 20:30:46.304  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=65, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ] (release request)
11-14 20:30:46.306  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ] (release request)
11-14 20:30:46.306  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=64, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ] (release request)
11-14 20:30:46.306  2017  2128 D ConnectivityService: releasing NetworkRequest [ TRACK_DEFAULT id=70, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10131] ] (release request)
11-14 20:30:46.329  7972  7992 D EGL_emulation: eglMakeCurrent: 0xd641a240: ver 2 0 (tinfo 0xb011d380)
11-14 20:30:46.345  8182  8182 W android.vendin: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.345  8182  8182 W android.vendin: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.392  8182  8182 I Finsky  : [2] mie.j(82): Process created at version: 43.5.26-29 [0] [PR] 693462648
11-14 20:30:46.442  8182  8214 I Finsky  : [606] acli.bt(192): Finished reading experiment flags from file [0tGUNCGIkbk4o6-fQ335kUYSKwVj4lusnHT-A5Dsy08] numFlags=1843.
11-14 20:30:46.445  8182  8214 I Finsky  : [606] acli.bt(192): Finished reading experiment flags from file [Se-xCc4LzNyh3UrKMIU2sUf-PUKz4oQEbpKZDMuaFno] numFlags=2222.
11-14 20:30:46.481  8182  8216 I Finsky  : [608] acli.bt(192): Finished reading experiment flags from file [v2WimGWEF5YO7-7ZCbCd0nV3tRQnqxdw8w06p5W_tmQ] numFlags=2232.
11-14 20:30:46.490  8182  8215 W Finsky  : [607] agql.j(99): Failed to get the task info for cold start.
11-14 20:30:46.490  8182  8215 I Finsky  : [607] agql.j(133): Process started for unknown session.
11-14 20:30:46.495  8159  8238 W CacheStorage: cache doesn't exist
11-14 20:30:46.500  8182  8182 I Finsky  : [2] mgl.ag(342): Profiling: Starting up (1)
11-14 20:30:46.532  2017  2898 D ConnectivityService: requestNetwork for uid/pid:10133/8159 NetworkRequest [ TRACK_DEFAULT id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ]
11-14 20:30:46.532  8159  8239 E DocsApplication: from onCreate Completable for sending summary about blocked SyncRequests
11-14 20:30:46.532  8159  8239 E DocsApplication: java.lang.IllegalStateException
11-14 20:30:46.532  8159  8239 E DocsApplication:       at grg.i(PG:64)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at gem.lambda$onCreate$2$com-google-android-apps-docs-DocsApplication(PG:279)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at fvc$1.run(PG:87)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at woo.jg(PG:13)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at wly.d(PG:3)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at wow$a.run(PG:3)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at wmj$a.run(PG:10)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at wsy.run(PG:14)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at wsy.call(PG:1)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at java.util.concurrent.FutureTask.run(FutureTask.java:266)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:46.532  8159  8239 E DocsApplication:       at java.lang.Thread.run(Thread.java:919)
11-14 20:30:46.533  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ] with score 60 and serial -1
11-14 20:30:46.533  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ] with score 60 and serial -1
11-14 20:30:46.533  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ] with score 60 and serial -1
11-14 20:30:46.543  8159  8239 E DocsApplication: from onCreate Completable for sending summary about blocked SyncRequests
11-14 20:30:46.543  8159  8239 E DocsApplication: java.lang.IllegalStateException
11-14 20:30:46.543  8159  8239 E DocsApplication:       at grg.i(PG:64)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at gem.lambda$onCreate$2$com-google-android-apps-docs-DocsApplication(PG:279)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at fvc$1.run(PG:87)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at woo.jg(PG:13)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at wly.d(PG:3)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at wow$a.run(PG:3)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at wmj$a.run(PG:10)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at wsy.run(PG:14)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at wsy.call(PG:1)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at java.util.concurrent.FutureTask.run(FutureTask.java:266)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:46.543  8159  8239 E DocsApplication:       at java.lang.Thread.run(Thread.java:919)
11-14 20:30:46.556  8182  8214 I Finsky  : [606] aahl.<init>(75): aaho - Registering in memory receiver for android.intent.action.PACKAGE_ADDED and android.intent.action.PACKAGE_REMOVED
11-14 20:30:46.567  8182  8182 I Finsky  : [2] mie.j(968): AsyncInit: Mandatory tasks are executed!
11-14 20:30:46.571  8182  8182 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-14 20:30:46.576  8182  8182 I Finsky  : [2] zol.k(28): SettingNotFoundException, fall through to G.downloadBytesOverMobileMaximum
11-14 20:30:46.577  8182  8182 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-14 20:30:46.578  8182  8182 I Finsky  : [2] zol.j(31): SettingNotFoundException, fall through to G.downloadBytesOverMobileRecommended
11-14 20:30:46.586  8159  8242 D NetworkSecurityConfig: Using Network Security Config from resource network_security_config debugBuild: false
11-14 20:30:46.596  8182  8213 I Finsky  : [605] oto.f(42): Subscription detail: DataSubscriptionInfo{groupIdLevel1=null, serviceProviderName=[Zr1R7g28S8p7iucp_gnNJJtsRl-pgO3Y6eIkCh24Iy0], simCarrierId=1}
11-14 20:30:46.598  2017  2898 D ConnectivityService: requestNetwork for uid/pid:10133/8159 NetworkRequest [ TRACK_DEFAULT id=97, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ]
11-14 20:30:46.598  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=97, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ] with score 60 and serial -1
11-14 20:30:46.598  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=97, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ] with score 60 and serial -1
11-14 20:30:46.598  8182  8214 I cr_CronetLibraryLoader: Cronet version: 131.0.6738.0, arch: i686
11-14 20:30:46.599  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=97, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10133] ] with score 60 and serial -1
11-14 20:30:46.600  8182  8215 I Finsky  : [607] ohd.d(126): playLoggingServerUrl: https://play.googleapis.com/play/log
11-14 20:30:46.603  8182  8215 I Finsky  : [607] ohd.d(145): playLoggingServerTimestampUrl: https://play.googleapis.com/play/log/timestamp
11-14 20:30:46.609  2017  3342 D ConnectivityService: requestNetwork for uid/pid:10095/8182 NetworkRequest [ TRACK_DEFAULT id=98, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ]
11-14 20:30:46.610  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=98, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ] with score 60 and serial -1
11-14 20:30:46.610  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=98, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ] with score 60 and serial -1
11-14 20:30:46.610  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=98, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ] with score 60 and serial -1
11-14 20:30:46.630  8182  8182 I Finsky  : [2] lno.l(307): This process start was not selected for Play memory metrics collection.
11-14 20:30:46.631  8182  8217 I Finsky  : [609] anuj.<init>(4): VerifyApps: Setup app restrictions monitor
11-14 20:30:46.633  8182  8217 I Finsky  : [609] aocf.a(32): VerifyApps: Device wide unknown source restriction updated
11-14 20:30:46.641  1770  8273 E ResolverController: No valid NAT64 prefix (101, <unspecified>/0)
11-14 20:30:46.646  8182  8213 I Finsky  : [605] qix.d(1): registerListener
11-14 20:30:46.647  8182  8213 I Finsky  : [605] qdg.h(46): DFS: Listener added for oty@f5dc21
11-14 20:30:46.647  8182  8213 I Finsky  : [605] qix.d(1): registerListener
11-14 20:30:46.647  8182  8217 I Finsky  : [609] wti.s(77): Enqueuing libraries load for -499346026
11-14 20:30:46.647  8182  8259 I Finsky  : [623] wti.t(14): Starting libraries load for -499346026
11-14 20:30:46.671  2562  3543 I FontLog : (REDACTED) Received query %s, URI %s
11-14 20:30:46.671  2562  3543 I FontLog : (REDACTED) Query [%s] resolved to %s
11-14 20:30:46.672  2562  3543 I FontLog : (REDACTED) Fetch %s end status %s
11-14 20:30:46.676  2562  3543 I FontLog : (REDACTED) Pulling font file for id = %d, cache size = %d
11-14 20:30:46.678  2562  3543 I FontLog : (REDACTED) Pulling font file for id = %d, cache size = %d
11-14 20:30:46.699  8182  8182 I Finsky  : [2] aaho.i(1): aaho - Received: android.intent.action.PACKAGE_FULLY_REMOVED, [dq7PwrqB-A39QOTIxStVbHI0W-z4Bi__UiiG1dytTUw]
11-14 20:30:46.701  2744  2744 D BoundBrokerSvc: onBind: Intent { act=com.google.android.gms.safetynet.service.START pkg=com.google.android.gms }
11-14 20:30:46.701  2744  2744 D BoundBrokerSvc: Loading bound service for intent: Intent { act=com.google.android.gms.safetynet.service.START pkg=com.google.android.gms }
11-14 20:30:46.710  8182  8182 I Finsky  : [2] aaip.C(84): Package no longer installed: com.osherdahan.EzScan
11-14 20:30:46.713  2562  2562 W SystemServiceRegistry: No service published for: persistent_data_block
11-14 20:30:46.722  8182  8182 I Finsky  : [2] mbe.f(9): AIM: AppInfoCacheUpdater -> invalidating apps: [com.osherdahan.EzScan]
11-14 20:30:46.722  8182  8182 I Finsky  : [2] mbt.a(26): AIM: AppInfoManager-Perf > Creating AppInfoManager ...
11-14 20:30:46.732  8182  8182 I Finsky  : [2] mbr.c(21): AIM: AppInfoManager-Perf > getApps > called for 1 apps
11-14 20:30:46.741  2017  5261 D HostConnection: HostConnection::get() New Host Connection established 0xb875f480, tid 5261
11-14 20:30:46.743  2017  5261 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:46.744  2017  5261 W OpenGLRenderer: Failed to choose config with EGL_SWAP_BEHAVIOR_PRESERVED, retrying without...
11-14 20:30:46.749  8182  8310 I Finsky  : [652] sdr.run(305): Frosting DB delete succeeded: true
11-14 20:30:46.749  8182  8267 I Finsky  : [626] mcz.a(58): AIM: AppInfoManager-Perf > OnDeviceAppInfo > cacheHitCount=0, cacheMissCount=1. Missed  in cache (limit 10) : [com.osherdahan.EzScan]
11-14 20:30:46.757  2017  5261 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 0 0
11-14 20:30:46.757  2017  5261 D EGL_emulation: eglCreateContext: 0xad8003c0: maj 2 min 0 rcv 2
11-14 20:30:46.765  2017  2045 I RoleUserState: Wrote roles.xml successfully
11-14 20:30:46.771  8182  8259 I Finsky  : [623] wti.t(286): Loaded library for account: [RkxLjGxzyc5OhtKbDLjNXMs7gpU6Q5aw58-8xqCOATQ]
11-14 20:30:46.771  8182  8259 I Finsky  : [623] wti.t(355): Finished loading 1 libraries.
11-14 20:30:46.777  2017  5261 D EGL_emulation: eglMakeCurrent: 0xad8003c0: ver 2 0 (tinfo 0xb6de3710)
11-14 20:30:46.782  2017  5261 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 1 0
11-14 20:30:46.801  8182  8317 I Finsky  : [656] pvz.j(27): ApplicationRestrictions: {}
11-14 20:30:46.809  8182  8182 I Finsky  : [2] aooq.c(44): Do not start WearSupportService due to Wear service optimization
11-14 20:30:46.810  8182  8182 I Finsky  : [2] afdf.<init>(47): Resetting scheduler db
11-14 20:30:46.811  8182  8217 I Finsky  : [609] agiu.<init>(26): Initializing pausers from value store.
11-14 20:30:46.811  8182  8217 I Finsky  : [609] aoop.i(43): setup::RES: Callers (Pausers) in PauseUpdatesCallersValueStore: []
11-14 20:30:46.812  8182  8267 I Finsky  : [626] lis.apply(1126): AIM: Got app ownership map. App counts: . Unique apps: 0
11-14 20:30:46.812  8182  8267 E Finsky  : [626] aoop.M(49): [Counters] attempted to use a non-positive increment for: 4752
11-14 20:30:46.816  8182  8182 I Finsky  : [2] aaip.C(84): Package no longer installed: com.osherdahan.EzScan
11-14 20:30:46.816  8182  8182 I Finsky  : [2] agob.f(9): Clearing split related stale data.
11-14 20:30:46.830  8182  8310 I Finsky  : [652] sdr.run(305): Frosting DB delete succeeded: false
11-14 20:30:46.831  8159  8289 I Cello   : [8289:NonCelloThread] cello.cc:594:operator() got notified of network change to online
11-14 20:30:46.835  8159  8289 I Cello   : [8289:NonCelloThread] cello.cc:594:operator() got notified of network change to online
11-14 20:30:46.837  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 1-1337, CT: 1731614883300, Constraints: [{ L: 30211796, D: 73411796, C: CHARGING_NONE, I: IDLE_NONE, N: NET_ANY }]
11-14 20:30:46.838  8182  8331 I Finsky  : [669] az.a(21): Asset module storage cleared for package com.osherdahan.EzScan.
11-14 20:30:46.840  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1210, CT: 1731614879576, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:46.869  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1211, CT: 1731614879576, Constraints: [{ L: 0, D: 86400000, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:46.869  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1212, CT: 1731614879576, Constraints: [{ L: 17520424, D: 28320424, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:46.869  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1213, CT: 1731614879576, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:46.869  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1214, CT: 1731614879576, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_NONE, N: NET_UNMETERED }]
11-14 20:30:46.869  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 10-79, CT: 1731614882886, Constraints: [{ L: 0, D: 86400000, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_ANY }]
11-14 20:30:46.870  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 20-23232323, CT: 1731598083057, Constraints: [{ L: 0, D: 82800000, C: CHARGING_REQUIRED, I: IDLE_NONE, N: NET_UNMETERED }]
11-14 20:30:46.871  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 24-77777777, CT: 1731598083269, Constraints: [{ L: 1, D: 82800000, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_NONE }]
11-14 20:30:46.871  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 26-1414141414, CT: 1731598083313, Constraints: [{ L: 42408610, D: 43308610, C: CHARGING_NONE, I: IDLE_NONE, N: NET_NONE }]
11-14 20:30:46.871  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 44-1027, CT: 1731598082636, Constraints: [{ L: 0, D: 86400000, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_NONE }]
11-14 20:30:46.888  2017  2909 I ActivityManager: Killing 7661:com.google.android.apps.wallpaper/u0a96 (adj 985): empty #17
11-14 20:30:46.890  8182  8267 I Finsky  : [626] mgb.apply(152): SCH: Scheduling 0 system job(s)
11-14 20:30:46.891  1771  1771 D Zygote  : Forked child process 8339
11-14 20:30:46.892  8182  8182 W Finsky  : [2] agrg.b(132): STU: Failed to get storage stats for package 'com.osherdahan.EzScan' (1601: Error getting stats: android.content.pm.PackageManager.NameNotFoundException)
11-14 20:30:46.895  8182  8182 I Finsky  : [2] otn.onSubscriptionsChanged(6): onSubscriptionsChanged
11-14 20:30:46.897  8182  8267 I Finsky  : [626] mcu.a(229): AIM: AppInfoManager-Perf > ItemModel > CacheSize=25, cacheHitCount=0, cacheMissCount=0, total appsWithNoServerDataCount=0. Missed  in cache (limit 10) : []
11-14 20:30:46.898  2017  2047 I ActivityManager: Start proc 8339:com.google.android.apps.maps/u0a114 for broadcast {com.google.android.apps.maps/com.google.android.libraries.social.peoplekit.thirdparty.viewcontrollers.ThirdPartyReceiver}
11-14 20:30:46.899  8339  8339 E droid.apps.map: Unknown bits set in runtime_flags: 0x8000
11-14 20:30:46.899  8339  8339 W droid.apps.map: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:46.900  8339  8339 E droid.apps.map: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:46.903  8182  8217 D NetworkSecurityConfig: No Network Security Config specified, using platform default
11-14 20:30:46.906  8182  8345 I Finsky  : [670] qix.d(1): registerListener
11-14 20:30:46.907  8182  8345 I Finsky  : [670] qdg.h(46): DFS: Listener added for adri@28ff105
11-14 20:30:46.909  8182  8259 I Finsky  : [623] lcf.accept(132): AIM: AppInfoManager-Perf > getApps > data collection finished
11-14 20:30:46.909  8182  8259 I Finsky  : [623] lkj.run(543): AIM: AppInfoManager-Perf > maybeDestroyAppInfoManager is called. actives = 0
11-14 20:30:46.911  8159  8289 I Cello   : [8289:NonCelloThread] token_bucket.cc:223:Create TokenBucket initialized with max_bucket_size of 300, with each request requiring 10 tokens
11-14 20:30:46.911  8159  8289 I chatty  : uid=10133(com.google.android.apps.docs) CelloTaskRunner identical 1 line
11-14 20:30:46.911  8159  8289 I Cello   : [8289:NonCelloThread] token_bucket.cc:223:Create TokenBucket initialized with max_bucket_size of 300, with each request requiring 10 tokens
11-14 20:30:46.924  8159  8289 I Cello   : [8289:NonCelloThread] init_helper.cc:549:MaybeResyncLocalState Detected no change in default fields or default team drive fields
11-14 20:30:46.927  8339  8339 I droid.apps.map: The ClassLoaderContext is a special shared library.
11-14 20:30:46.928  8159  8289 I Cello   : [8289:NonCelloThread] sync_engine.cc:2408:MaybeStartRepeatingPushTaskTimer Starting repeating push task timer with interval 30000ms
11-14 20:30:46.931  8182  8345 I Finsky  : [670] uei.a(614): IV2: found recoverable installs: []
11-14 20:30:46.940  1771  1771 I Zygote  : Process 7661 exited due to signal 9 (Killed)
11-14 20:30:46.950  2017  2452 D ConnectivityService: requestNetwork for uid/pid:10095/8182 NetworkRequest [ TRACK_DEFAULT id=100, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ]
11-14 20:30:46.951  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=100, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ] with score 60 and serial -1
11-14 20:30:46.951  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=100, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ] with score 60 and serial -1
11-14 20:30:46.951  8339  8339 W droid.apps.map: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.951  8339  8339 W droid.apps.map: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.951  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=100, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10095] ] with score 60 and serial -1
11-14 20:30:46.951  8339  8339 W droid.apps.map: JIT profile information will not be recorded: profile file does not exits.
11-14 20:30:46.952  8182  8269 I Finsky  : [628] ukf.Z(21): IQ: start evaluating install requests.
11-14 20:30:46.952  8182  8269 I Finsky  : [628] ukf.Z(54): IQ: no jobs active. Skipping
11-14 20:30:46.967  8182  8365 I Finsky  : [674] ujw.call(101): IQ: Pruning inactive install requests
11-14 20:30:46.969  8182  8269 I Finsky  : [628] ukf.Z(494): IQ: 0 scheduled install statuses found to proceed.
11-14 20:30:46.969  8182  8182 I Finsky  : [2] agnz.a(9): Connecting InstallListener to SplitInstallService broadcaster...
11-14 20:30:46.972  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10096 pid 7661 in 84ms
11-14 20:30:46.978  8182  8323 I Finsky  : [662] mgb.apply(48): SCH: Canceling job 3-1210
11-14 20:30:46.980  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1213, CT: 1731614879576, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:46.985  8182  8267 I Finsky  : [626] mgb.apply(152): SCH: Scheduling 1 system job(s)
11-14 20:30:46.985  8182  8267 I Finsky  : [626] afcv.b(261): SCH: Scheduling system job Id: 9965, L: 0, D: 85032591, C: true, I: true, N: 2
11-14 20:30:46.993  8182  8323 I Finsky  : [662] mgb.apply(48): SCH: Canceling job 3-1211
11-14 20:30:46.994  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1212, CT: 1731614879576, Constraints: [{ L: 17520424, D: 28320424, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:46.995  8159  8289 I Cello   : [8289:NonCelloThread] fetch_task.cc:671:RunInternal Largest local change id for My Drive at startup: 34295
11-14 20:30:46.996  8182  8269 I Finsky  : [628] mgb.apply(152): SCH: Scheduling 1 system job(s)
11-14 20:30:46.996  8182  8269 I Finsky  : [628] afcv.b(261): SCH: Scheduling system job Id: 9966, L: 16153004, D: 26953004, C: false, I: true, N: 2
11-14 20:30:47.001  8182  8323 I Finsky  : [662] mgb.apply(48): SCH: Canceling job 3-1212
11-14 20:30:47.002  8182  8244 I Finsky  : [618] afct.a(15): SCH: no pending jobs to schedule.
11-14 20:30:47.007  8182  8323 I Finsky  : [662] mgb.apply(48): SCH: Canceling job 3-1213
11-14 20:30:47.007  8182  8267 I Finsky  : [626] afct.a(15): SCH: no pending jobs to schedule.
11-14 20:30:47.010  8182  8323 I Finsky  : [662] mgb.apply(48): SCH: Canceling job 3-1214
11-14 20:30:47.011  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 20-23232323, CT: 1731598083057, Constraints: [{ L: 0, D: 82800000, C: CHARGING_REQUIRED, I: IDLE_NONE, N: NET_UNMETERED }]
11-14 20:30:47.013  8182  8244 I Finsky  : [618] mgb.apply(152): SCH: Scheduling 1 system job(s)
11-14 20:30:47.013  8182  8244 I Finsky  : [618] afcv.b(261): SCH: Scheduling system job Id: 9967, L: 0, D: 64636044, C: true, I: false, N: 2
11-14 20:30:47.018  8182  8365 I Finsky  : [674] uja.apply(1101): IQ: Creating job 1215, for (REQ_CHARGING, REQ_DEVICE_IDLE, REQ_GEARHEAD_PROJECTION_OFF, NETWORK=UNMETERED, PROVISIONING_STATE=PROVISIONED, BACKUP_MANAGER_STATE=BACKUP_READY, AUTHENTICATION_REQUIRED, PROCESS_IMPORTANCE_THRESHOLD=125)
11-14 20:30:47.018  8182  8365 I Finsky  : [674] uja.apply(1101): IQ: Creating job 1216, for (REQ_DEVICE_IDLE, REQ_GEARHEAD_PROJECTION_OFF, MIN_BATTERY=20, SHOULD_APPLY_BUDGET=true, NETWORK=UNMETERED, PROVISIONING_STATE=PROVISIONED, BACKUP_MANAGER_STATE=BACKUP_READY, AUTHENTICATION_REQUIRED)
11-14 20:30:47.019  8182  8365 I Finsky  : [674] uja.apply(1101): IQ: Creating job 1217, for (REQ_DEVICE_IDLE, REQ_GEARHEAD_PROJECTION_OFF, MIN_BATTERY=20, SHOULD_APPLY_BUDGET=true, NETWORK=UNMETERED, PROVISIONING_STATE=PROVISIONED, BACKUP_MANAGER_STATE=BACKUP_READY, TIME=[2024-11-15T01:00:00Z-2024-11-15T04:00:00Z], AUTHENTICATION_REQUIRED)
11-14 20:30:47.019  8182  8365 I Finsky  : [674] uja.apply(1101): IQ: Creating job 1218, for (REQ_CHARGING, REQ_DEVICE_IDLE, REQ_GEARHEAD_PROJECTION_OFF, NETWORK=UNMETERED, PROVISIONING_STATE=PROVISIONED, BACKUP_MANAGER_STATE=BACKUP_READY, AUTHENTICATION_REQUIRED)
11-14 20:30:47.019  8182  8365 I Finsky  : [674] uja.apply(1101): IQ: Creating job 1219, for (REQ_CHARGING, REQ_GEARHEAD_PROJECTION_OFF, NETWORK=UNMETERED, PROVISIONING_STATE=PROVISIONED, BACKUP_MANAGER_STATE=BACKUP_READY, AUTHENTICATION_REQUIRED, PROCESS_IMPORTANCE_THRESHOLD=125)
11-14 20:30:47.020  8182  8365 I Finsky  : [674] ukf.I(311): IQ: Bulk scheduling created jobs
11-14 20:30:47.025  8182  8269 I Finsky  : [628] agqb.c(17): SSM: Start staged session task with 0 tracked staged sessions
11-14 20:30:47.041  8182  8259 I Finsky  : [623] qsn.accept(59): SCH: Scheduling phonesky job Id: 12-1, CT: 1731616246895, Constraints: [{ L: 15000, D: 86400000, C: CHARGING_NONE, I: IDLE_NONE, N: NET_ANY }]
11-14 20:30:47.042  8182  8269 I Finsky  : [628] mgb.apply(152): SCH: Scheduling 1 system job(s)
11-14 20:30:47.042  8182  8269 I Finsky  : [628] afcv.b(261): SCH: Scheduling system job Id: 9953, L: 14853, D: 72048054, C: false, I: false, N: 1
11-14 20:30:47.046  8182  8228 I Finsky  : [613] nzl.ko(86): [ContentSync] finished, scheduled=true
11-14 20:30:47.051  8182  8259 I Finsky  : [623] adpa.run(164): RemoteSetup: Set {com.android.vending/com.google.android.finsky.remotesetup.PlayRemoteSetupActivity} enabled state to 1
11-14 20:30:47.051  8182  8267 I Finsky  : [626] adpa.run(45): SysUA: Set SystemUpdateActivity enabled state to 1
11-14 20:30:47.052  8182  8244 I Finsky  : [618] adpa.run(121): Set UnhibernateActivity enabled state to 1
11-14 20:30:47.052  8182  8269 I Finsky  : [628] adpa.run(84): SysCUA: Set {com.android.vending/com.google.android.finsky.systemcomponentupdateui.common.SystemComponentUpdateActivity} enabled state to 0
11-14 20:30:47.091  8182  8264 I cr_CronetUrlRequestContext: destroyNativeStreamLocked org.chromium.net.impl.CronetBidirectionalStream@f92d520
11-14 20:30:47.111  8339  8387 D libEGL  : Emulator has host GPU support, qemu.gles is set to 1.
11-14 20:30:47.111  8339  8387 W libc    : Unable to set property "qemu.gles" to "1": connection failed; errno=13 (Permission denied)
11-14 20:30:47.111  8182  8267 I Finsky  : [626] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1215, CT: 1731616247020, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:47.112  8182  8267 I Finsky  : [626] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1216, CT: 1731616247020, Constraints: [{ L: 0, D: 86400000, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:47.112  8182  8267 I Finsky  : [626] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1217, CT: 1731616247020, Constraints: [{ L: 16152981, D: 26952981, C: CHARGING_NONE, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:47.112  8182  8267 I Finsky  : [626] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1218, CT: 1731616247020, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_REQUIRED, N: NET_UNMETERED }]
11-14 20:30:47.112  8182  8267 I Finsky  : [626] qsn.accept(59): SCH: Scheduling phonesky job Id: 3-1219, CT: 1731616247020, Constraints: [{ L: 0, D: 86400000, C: CHARGING_REQUIRED, I: IDLE_NONE, N: NET_UNMETERED }]
11-14 20:30:47.114  2562  2562 D BoundBrokerSvc: onRebind: Intent { act=com.google.android.gms.clearcut.bootcount.service.START pkg=com.google.android.gms }
11-14 20:30:47.110  8339  8339 W Background_6: type=1400 audit(0.0:47): avc: denied { write } for name="property_service" dev="tmpfs" ino=6933 scontext=u:r:untrusted_app:s0:c114,c256,c512,c768 tcontext=u:object_r:property_socket:s0 tclass=sock_file permissive=0
11-14 20:30:47.119  8182  8269 I Finsky  : [628] mgb.apply(152): SCH: Scheduling 1 system job(s)
11-14 20:30:47.119  8182  8269 I Finsky  : [628] afcv.b(261): SCH: Scheduling system job Id: 9966, L: 0, D: 26952881, C: false, I: true, N: 2
11-14 20:30:47.151  2017  2452 D ConnectivityService: requestNetwork for uid/pid:10114/8339 NetworkRequest [ TRACK_DEFAULT id=101, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10114] ]
11-14 20:30:47.152  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=101, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10114] ] with score 60 and serial -1
11-14 20:30:47.153  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=101, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10114] ] with score 60 and serial -1
11-14 20:30:47.153  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=101, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10114] ] with score 60 and serial -1
11-14 20:30:47.181  2017  2898 W ActivityManager: Unable to start service Intent { cmp=com.google.android.projection.gearhead/com.google.android.apps.auto.carservice.service.impl.GearheadCarStartupService } U=0: not found
11-14 20:30:47.181  2017  2898 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@a2c3804
11-14 20:30:47.189  8339  8387 D libEGL  : loaded /vendor/lib/egl/libEGL_emulation.so
11-14 20:30:47.192  8339  8387 D libEGL  : loaded /vendor/lib/egl/libGLESv1_CM_emulation.so
11-14 20:30:47.194  8339  8387 D libEGL  : loaded /vendor/lib/egl/libGLESv2_emulation.so
11-14 20:30:47.194  2017  2898 I ActivityManager: Killing 7214:android.process.acore/u0a41 (adj 985): empty #17
11-14 20:30:47.199  8339  8387 D HostConnection: HostConnection::get() New Host Connection established 0xd2ebe0d0, tid 8387
11-14 20:30:47.200  8339  8387 D HostConnection: HostComposition ext ANDROID_EMU_CHECKSUM_HELPER_v1 ANDROID_EMU_native_sync_v2 ANDROID_EMU_native_sync_v3 ANDROID_EMU_native_sync_v4 ANDROID_EMU_dma_v1 ANDROID_EMU_direct_mem ANDROID_EMU_host_composition_v1 ANDROID_EMU_host_composition_v2 ANDROID_EMU_vulkan ANDROID_EMU_deferred_vulkan_commands ANDROID_EMU_vulkan_null_optional_strings ANDROID_EMU_vulkan_create_resources_with_requirements ANDROID_EMU_YUV420_888_to_NV21 ANDROID_EMU_YUV_Cache ANDROID_EMU_vulkan_free_memory_sync ANDROID_EMU_vulkan_shader_float16_int8 ANDROID_EMU_vulkan_async_queue_submit ANDROID_EMU_sync_buffer_data ANDROID_EMU_vulkan_async_qsri GL_OES_vertex_array_object GL_KHR_texture_compression_astc_ldr ANDROID_EMU_host_side_tracing ANDROID_EMU_gles_max_version_2
11-14 20:30:47.213  1771  1771 D Zygote  : Forked child process 8405
11-14 20:30:47.215  8405  8405 W .android.video: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:47.217  2744  2744 D BoundBrokerSvc: onBind: Intent { act=com.google.android.gms.common.BIND_SHARED_PREFS pkg=com.google.android.gms }
11-14 20:30:47.217  2744  2744 D BoundBrokerSvc: Loading bound service for intent: Intent { act=com.google.android.gms.common.BIND_SHARED_PREFS pkg=com.google.android.gms }
11-14 20:30:47.218  8405  8405 E .android.video: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:47.221  2017  2047 I ActivityManager: Start proc 8405:com.google.android.videos/u0a121 for broadcast {com.google.android.videos/com.google.android.libraries.social.peoplekit.thirdparty.viewcontrollers.ThirdPartyReceiver}
11-14 20:30:47.236  8405  8405 I .android.video: The ClassLoaderContext is a special shared library.
11-14 20:30:47.238  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:47.238  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:47.239  8339  8387 D eglCodecCommon: setVertexArrayObject: set vao to 0 (0) 0 0
11-14 20:30:47.239  8339  8387 D EGL_emulation: eglCreateContext: 0xde499400: maj 2 min 0 rcv 2
11-14 20:30:47.240  1771  1771 I Zygote  : Process 7214 exited due to signal 9 (Killed)
11-14 20:30:47.240  2017  2034 D CountryDetector: No listener is left
11-14 20:30:47.240  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10041 pid 7214 in 45ms
11-14 20:30:47.257  8339  8387 D EGL_emulation: eglMakeCurrent: 0xde499400: ver 2 0 (tinfo 0xde57bb60)
11-14 20:30:47.270  2562  2562 D WearableService: Creating wearable service asynchronously.
11-14 20:30:47.283  2562  3357 D WearableService: onGetService: waiting for onCreate to be completed.
11-14 20:30:47.314  2562  4429 I Wear_Controller: Wearable module requires a companion app to be installed.
11-14 20:30:47.314  2562  4429 I WearableService: onCreate: Wearable Services not starting. Wear is not available on this device.
11-14 20:30:47.322  2562  3357 W WearableService: onGetService: Wear is not available on this device.
11-14 20:30:47.331  2562  4640 W WearableService: onGetService: Wear is not available on this device.
11-14 20:30:47.342  8405  8439 W PlayMovies: mxg.run:22 User config found
11-14 20:30:47.342  8405  8439 W PlayMovies:
11-14 20:30:47.343  8405  8439 W PlayMovies: mxg.run:33 Loading user config
11-14 20:30:47.343  8405  8439 W PlayMovies:
11-14 20:30:47.372  2562  8424 I SemanticLocation: No subscriptions found [CONTEXT service_id=173 ]
11-14 20:30:47.394  2017  2456 D ConnectivityService: requestNetwork for uid/pid:10121/8405 NetworkRequest [ TRACK_DEFAULT id=102, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ]
11-14 20:30:47.395  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=102, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ] with score 60 and serial -1
11-14 20:30:47.395  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=102, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ] with score 60 and serial -1
11-14 20:30:47.395  2017  2456 D ConnectivityService: requestNetwork for uid/pid:10121/8405 NetworkRequest [ TRACK_DEFAULT id=103, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ]
11-14 20:30:47.395  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=102, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ] with score 60 and serial -1
11-14 20:30:47.395  2017  2125 D UntrustedWifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=103, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ] with score 60 and serial -1
11-14 20:30:47.395  2017  2125 D WifiNetworkFactory: got request NetworkRequest [ TRACK_DEFAULT id=103, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ] with score 60 and serial -1
11-14 20:30:47.396  2332  2332 D PhoneSwitcherNetworkRequstListener: got request NetworkRequest [ TRACK_DEFAULT id=103, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED Uid: 10121] ] with score 60 and serial -1
11-14 20:30:47.396  8405  8454 E SQLiteLog: (5) statement aborts at 1: [PRAGMA journal_mode=TRUNCATE] database is locked
11-14 20:30:47.396  8405  8454 W SQLiteConnection: Could not change the database journal mode of '/data/user/0/com.google.android.videos/databases/purchase_store.db' from 'wal' to 'TRUNCATE' because the database is locked.  This usually means that there are other open connections to the database which prevents the database from enabling or disabling write-ahead logging mode.  Proceeding without changing the journal mode.
11-14 20:30:47.402  8405  8439 W PlayMovies: igd.invokeSuspend:290 Observing cache file clear_cache_file_name.tmp
11-14 20:30:47.402  8405  8439 W PlayMovies:
11-14 20:30:47.454  8405  8405 W PlayMovies: lor.onCreate:520 Installer Package: com.android.vending
11-14 20:30:47.454  8405  8405 W PlayMovies:
11-14 20:30:47.459  8405  8405 W MediaSessionCompat: Couldn't find a unique registered media button receiver in the given context.
11-14 20:30:47.478  8405  8405 V MediaRouter: Selecting route: RouteInfo{ name=Phone, description=null, status=null, category=RouteCategory{ name=System types=ROUTE_TYPE_LIVE_AUDIO ROUTE_TYPE_LIVE_VIDEO  groupable=false }, supportedTypes=ROUTE_TYPE_LIVE_AUDIO ROUTE_TYPE_LIVE_VIDEO , presentationDisplay=null }
11-14 20:30:47.489  8405  8405 E BluetoothAdapter: Bluetooth binder is null
11-14 20:30:47.499  8405  8405 V MediaRouter: Selecting route: RouteInfo{ name=Phone, description=null, status=null, category=RouteCategory{ name=System types=ROUTE_TYPE_LIVE_AUDIO ROUTE_TYPE_LIVE_VIDEO  groupable=false }, supportedTypes=ROUTE_TYPE_LIVE_AUDIO ROUTE_TYPE_LIVE_VIDEO , presentationDisplay=null }
11-14 20:30:47.501  1771  1771 D Zygote  : Forked child process 8473
11-14 20:30:47.506  8473  8473 W opjohnwu.magis: Unexpected CPU variant for X86 using defaults: x86
11-14 20:30:47.509  2017  2047 I ActivityManager: Start proc 8473:com.topjohnwu.magisk/u0a134 for broadcast {com.topjohnwu.magisk/com.topjohnwu.magisk.core.Receiver}
11-14 20:30:47.532  8473  8473 E opjohnwu.magis: Not starting debugger since process cannot load the jdwp agent.
11-14 20:30:47.534  2017  6171 I ActivityManager: Killing 5928:com.android.dialer/u0a93 (adj 975): empty #17
11-14 20:30:47.537  2332  2332 D CarrierSvcBindHelper: No carrier app for: 0
11-14 20:30:47.551  2017  2045 E system_server: No package ID 7f found for ID 0x7f080363.
11-14 20:30:47.551  2017  2045 E system_server: No package ID 7f found for ID 0x7f140713.
11-14 20:30:47.551  2017  2045 E system_server: No package ID 7f found for ID 0x7f140713.
11-14 20:30:47.552  2017  2045 E system_server: No package ID 7f found for ID 0x7f08035f.
11-14 20:30:47.552  2017  2045 E system_server: No package ID 7f found for ID 0x7f140711.
11-14 20:30:47.552  2017  2045 E system_server: No package ID 7f found for ID 0x7f140711.
11-14 20:30:47.552  2017  2045 E system_server: No package ID 7f found for ID 0x7f080361.
11-14 20:30:47.552  2017  2045 E system_server: No package ID 7f found for ID 0x7f140712.
11-14 20:30:47.552  2017  2045 E system_server: No package ID 7f found for ID 0x7f140712.
11-14 20:30:47.552  2017  2045 W ShortcutService: Invalid tag 'capability' found at depth 2
11-14 20:30:47.553  2017  2045 E ShortcutService: Ignoring excessive intent tag.
11-14 20:30:47.553  2017  2045 W ShortcutService: Invalid tag 'parameter' found at depth 4
11-14 20:30:47.553  2017  2045 W ShortcutService: Invalid tag 'capability' found at depth 2
11-14 20:30:47.553  2017  2045 W ShortcutService: Invalid tag 'slice' found at depth 3
11-14 20:30:47.553  2017  2045 W ShortcutService: Invalid tag 'url-template' found at depth 4
11-14 20:30:47.556  2562  5084 W cpgw    : Phenotype API error. Event: # fdtf@57278391, EventCode: COMMIT_CONFIG [CONTEXT service_id=51 ]
11-14 20:30:47.556  2562  5084 W cpgw    : cpfe: 29537: Stale snapshot for com.google.android.libraries.mediahome.providers.video#com.google.android.videos(new configuration available)
11-14 20:30:47.556  2562  5084 W cpgw    :      at cphb.c(:com.google.android.gms@244433016@24.44.33 (100700-694629214):484)
11-14 20:30:47.556  2562  5084 W cpgw    :      at cphb.b(:com.google.android.gms@244433016@24.44.33 (100700-694629214):67)
11-14 20:30:47.556  2562  5084 W cpgw    :      at cpha.i(:com.google.android.gms@244433016@24.44.33 (100700-694629214):3)
11-14 20:30:47.556  2562  5084 W cpgw    :      at cpgw.h(:com.google.android.gms@244433016@24.44.33 (100700-694629214):18)
11-14 20:30:47.556  2562  5084 W cpgw    :      at cpgw.f(:com.google.android.gms@244433016@24.44.33 (100700-694629214):11)
11-14 20:30:47.556  2562  5084 W cpgw    :      at brlw.fl(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:47.556  2562  5084 W cpgw    :      at brmi.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):66)
11-14 20:30:47.556  2562  5084 W cpgw    :      at ecof.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):21)
11-14 20:30:47.556  2562  5084 W cpgw    :      at aogo.c(:com.google.android.gms@244433016@24.44.33 (100700-694629214):50)
11-14 20:30:47.556  2562  5084 W cpgw    :      at aogo.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):76)
11-14 20:30:47.556  2562  5084 W cpgw    :      at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:47.556  2562  5084 W cpgw    :      at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:47.556  2562  5084 W cpgw    :      at aolz.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):8)
11-14 20:30:47.556  2562  5084 W cpgw    :      at java.lang.Thread.run(Thread.java:919)
11-14 20:30:47.558  2562  5084 W AsyncOperation: operation=CommitToConfigurationOperationCall, opStatusCode=29537 [CONTEXT service_id=51 ]
11-14 20:30:47.558  2562  5084 W AsyncOperation: OperationException[Status{statusCode=Stale snapshot for com.google.android.libraries.mediahome.providers.video#com.google.android.videos(new configuration available), resolution=null}]
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at cpgw.h(:com.google.android.gms@244433016@24.44.33 (100700-694629214):48)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at cpgw.f(:com.google.android.gms@244433016@24.44.33 (100700-694629214):11)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at brlw.fl(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at brmi.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):66)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at ecof.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):21)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at aogo.c(:com.google.android.gms@244433016@24.44.33 (100700-694629214):50)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at aogo.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):76)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at aolz.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):8)
11-14 20:30:47.558  2562  5084 W AsyncOperation:        at java.lang.Thread.run(Thread.java:919)
11-14 20:30:47.558  8405  8442 W MobStoreFlagStore: Failed to commit due to stale snapshot for com.google.android.libraries.mediahome.providers.video#com.google.android.videos. Experiments may be delayed til next app start. Error code: 29501
11-14 20:30:47.558  8405  8466 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
11-14 20:30:47.566  2017  2117 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-14 20:30:47.580  1771  1771 I Zygote  : Process 5928 exited due to signal 9 (Killed)
11-14 20:30:47.584  8473  8496 D ProfileInstaller: Skipping profile installation for com.topjohnwu.magisk
11-14 20:30:47.590  2017  3336 W BroadcastQueue: Background execution not allowed: receiving Intent { act=android.intent.action.DROPBOX_ENTRY_ADDED flg=0x10 (has extras) } to com.google.android.gms/.stats.service.DropBoxEntryAddedReceiver
11-14 20:30:47.591  2017  3336 I ActivityManager: Killing 7771:com.google.android.projection.gearhead:shared/u0a100 (adj 975): empty #17
11-14 20:30:47.608  2017  2017 I Telecom : DefaultDialerCache: Refreshing default dialer for user 0: now com.android.dialer: DDC.oR@AJI
11-14 20:30:47.609  8405  8441 E PlayMovies: mvq.a:85 No worker key associated with this task with tags: [google_tv_widget_tag, com.google.android.apps.googletv.app.services.workmanager.WorkerWrapper]
11-14 20:30:47.609  8405  8441 E PlayMovies:
11-14 20:30:47.620  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10093 pid 5928 in 84ms
11-14 20:30:47.640  1771  1771 I Zygote  : Process 7771 exited due to signal 9 (Killed)
11-14 20:30:47.660  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10100 pid 7771 in 39ms
11-14 20:30:48.132  8159  8173 W System  : A resource failed to call close.
11-14 20:30:48.238  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:48.238  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:48.353  1777  1855 W audio_hw_generic: Not supplying enough data to HAL, expected position 2818843 , only wrote 2532952
11-14 20:30:49.239  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:49.239  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:49.525  8159  8224 W DynamiteModule: Local module descriptor class for com.google.android.gms.providerinstaller.dynamite not found.
11-14 20:30:49.529  2562  2580 W ProviderHelper: Unknown dynamite feature providerinstaller.dynamite
11-14 20:30:49.529  8159  8224 W ProviderInstaller: Failed to load providerinstaller module: No acceptable module com.google.android.gms.providerinstaller.dynamite found. Local version is 0 and remote version is 0.
11-14 20:30:49.533  8159  8224 I droid.apps.doc: The ClassLoaderContext is a special shared library.
11-14 20:30:49.535  8159  8224 I droid.apps.doc: The ClassLoaderContext is a special shared library.
11-14 20:30:49.560  8159  8224 V NativeCrypto: Registering com/google/android/gms/org/conscrypt/NativeCrypto's 305 native methods...
11-14 20:30:49.571  8159  8529 E GoogleApiManager: Failed to get service from broker.
11-14 20:30:49.571  8159  8529 E GoogleApiManager: java.lang.SecurityException: Unknown calling package name 'com.google.android.gms'.
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.Parcel.createException(Parcel.java:2071)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.Parcel.readException(Parcel.java:2039)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.Parcel.readException(Parcel.java:1987)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at anpu.a(:com.google.android.gms@244433016@24.44.33 (100700-694629214):36)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at anob.z(:com.google.android.gms@244433016@24.44.33 (100700-694629214):150)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at amvl.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):54)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.Handler.handleCallback(Handler.java:883)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.Handler.dispatchMessage(Handler.java:100)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at bsoa.lO(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at bsoa.dispatchMessage(:com.google.android.gms@244433016@24.44.33 (100700-694629214):5)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.Looper.loop(Looper.java:214)
11-14 20:30:49.571  8159  8529 E GoogleApiManager:      at android.os.HandlerThread.run(HandlerThread.java:67)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar: Failed to register com.google.android.gms.providerinstaller#com.google.android.gms
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar: drhl: 17: 17: API: Phenotype.API is not available on this device. Connection failed with: ConnectionResult{statusCode=DEVELOPER_ERROR, resolution=null, message=null}
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at drhn.a(:com.google.android.gms@244433016@24.44.33 (100700-694629214):13)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejvu.d(:com.google.android.gms@244433016@24.44.33 (100700-694629214):3)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejvw.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):130)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejxp.execute(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejvx.h(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejvx.l(:com.google.android.gms@244433016@24.44.33 (100700-694629214):101)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejvx.p(:com.google.android.gms@244433016@24.44.33 (100700-694629214):19)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at djpr.hl(:com.google.android.gms@244433016@24.44.33 (100700-694629214):35)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at dazh.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):14)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at ejxp.execute(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at dazi.b(:com.google.android.gms@244433016@24.44.33 (100700-694629214):18)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at dazx.b(:com.google.android.gms@244433016@24.44.33 (100700-694629214):36)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at dazz.c(:com.google.android.gms@244433016@24.44.33 (100700-694629214):26)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amst.c(:com.google.android.gms@244433016@24.44.33 (100700-694629214):9)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amvj.q(:com.google.android.gms@244433016@24.44.33 (100700-694629214):48)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amvj.d(:com.google.android.gms@244433016@24.44.33 (100700-694629214):10)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amvj.g(:com.google.android.gms@244433016@24.44.33 (100700-694629214):211)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amvj.onConnectionFailed(:com.google.android.gms@244433016@24.44.33 (100700-694629214):2)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amvl.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):82)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at android.os.Handler.handleCallback(Handler.java:883)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at android.os.Handler.dispatchMessage(Handler.java:100)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at bsoa.lO(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at bsoa.dispatchMessage(:com.google.android.gms@244433016@24.44.33 (100700-694629214):5)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at android.os.Looper.loop(Looper.java:214)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at android.os.HandlerThread.run(HandlerThread.java:67)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar: Caused by: amrl: 17: API: Phenotype.API is not available on this device. Connection failed with: ConnectionResult{statusCode=DEVELOPER_ERROR, resolution=null, message=null}
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at annn.a(:com.google.android.gms@244433016@24.44.33 (100700-694629214):15)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amsw.a(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     at amst.c(:com.google.android.gms@244433016@24.44.33 (100700-694629214):5)
11-14 20:30:49.573  8159  8528 W CondFlagRegistrar:     ... 11 more
11-14 20:30:49.583  8159  8530 I drha.a  : Unable to retrieve flag snapshot for com.google.android.gms.providerinstaller#com.google.android.gms, using defaults.
11-14 20:30:49.586  8159  8224 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-14 20:30:50.240  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:50.240  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:50.631  1959  1959 E netmgr  : Failed to open QEMU pipe 'qemud:network': Invalid argument
11-14 20:30:50.875  1961  1961 E wifi_forwarder: RemoteConnection failed to initialize: RemoteConnection failed to open pipe
11-14 20:30:51.240  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:51.240  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:52.241  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:52.241  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:52.305  7353  7365 W e.process.gapp: Reducing the number of considered missed Gc histogram windows from 115 to 100
11-14 20:30:53.241  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:53.241  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:54.242  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:54.242  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:55.242  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:55.242  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:56.243  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:56.243  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:56.611  8182  8267 W Finsky  : [626] acnt.a(64): PreloadClasses: Unable to load [kotlinx.coroutines.scheduling.ExperimentalCoroutineDispatcher, kotlinx.coroutines.scheduling.LimitingDispatcher, kotlinx.coroutines.internal.OpDescriptor, androidx.compose.runtime.ActualAndroid_androidKt$DefaultMonotonicFrameClock$2, androidx.compose.runtime.SnapshotThreadLocal, androidx.compose.ui.node.DepthSortedSet$DepthComparator$1, androidx.compose.runtime.snapshots.GlobalSnapshot$takeNestedMutableSnapshot$1, androidx.compose.ui.platform.AndroidCompositionLocals_androidKt$LocalLifecycleOwner$1, androidx.compose.ui.ComposedModifierKt$materialize$1, androidx.compose.ui.ComposedModifierKt$materialize$result$1, androidx.compose.runtime.CompositionImpl$RememberEventDispatcher, androidx.compose.runtime.snapshots.SnapshotIdSetKt, androidx.compose.animation.core.ComplexDoubleKt, androidx.compose.animation.core.ComplexDouble, androidx.compose.foundation.gestures.ScrollDraggableState, androidx.compose.foundation.gestures.DraggableKt$draggable$5, androidx.compose.ui.text.intl.AndroidLocale, androidx.compose.foundation.gestures.DraggableKt$awaitDownAndSlop$1, com.google.android.finsky.composenav.impl.NavHostUiKt$buildGraph$1$destinationBuilder$1, com.google.android.finsky.composenav.impl.MyModule_ProvideNavGraphBuilderFactory, com.google.android.finsky.composenav.impl.MyModule$provideNavGraphBuilder$1, com.google.android.finsky.composenav.compose.NoTransitionNavHostKt$NoTransitionNavHost$lambda$11$lambda$6$lambda$5$$inlined$map$1, com.google.android.finsky.composenav.compose.NoTransitionNavGraphBuilderExtKt$noTransitionComposable$content$1, com.google.android.finsky.composenav.compose.NavHostKt$NavHost$11$visibleEntries$2$1, com.google.android.finsky.composenav.impl.NavHostUiKt$buildGraph$1$destinationBuilder$1]
11-14 20:30:56.631  8182  8259 I Finsky  : [623] kwv.run(906): Initializing the instant apps module.
11-14 20:30:56.635  8182  8216 I Finsky  : [608] aati.h(14): Triggered update for experiment package com.google.android.finsky.stable.
11-14 20:30:56.643  8182  8308 I PhClient: Unable to retrieve flag snapshot for com.google.android.gms.phenotype, using defaults.
11-14 20:30:56.650  8182  8260 W RegistrationCommon: Failed to create storageInfo for com.google.android.finsky.stable.
11-14 20:30:56.650  8182  8260 W RegistrationCommon: com.google.android.gms.phenotype.core.common.PhenotypeException: 29514: Storage info not created for Play Store.
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at aqod.b(PG:1087)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at aqnz.b(PG:97)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at atkj.call(PG:225)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at axlm.a(PG:3)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at axks.run(PG:19)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at axln.run(PG:5)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at aygp.run(PG:59)
11-14 20:30:56.650  8182  8260 W RegistrationCommon:    at java.lang.Thread.run(Thread.java:919)
11-14 20:30:56.682  8182  8216 I Finsky  : [608] aati.h(68): Already at the latest configurations for experiment package com.google.android.finsky.stable.
11-14 20:30:56.682  8182  8216 I Finsky  : [608] aati.h(14): Triggered update for experiment package com.google.android.finsky.regular.
11-14 20:30:56.691  8182  8259 I Finsky  : [623] kwv.run(456): Component class com.google.android.finsky.wearsupport.WearSupportService disabled via PackageManager.
11-14 20:30:56.691  8182  8259 I Finsky  : [623] kwv.run(456): Component class com.google.android.finsky.wearsupport.WearChangeListenerService disabled via PackageManager.
11-14 20:30:56.695  8182  8310 I Finsky  : [652] qdk.accept(79): Wrote row to frosting DB: 1515
11-14 20:30:56.702  8182  8260 W RegistrationCommon: Failed to create storageInfo for com.google.android.finsky.regular.
11-14 20:30:56.702  8182  8260 W RegistrationCommon: com.google.android.gms.phenotype.core.common.PhenotypeException: 29514: Storage info not created for Play Store.
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at aqod.b(PG:1087)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at aqnz.b(PG:97)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at atkj.call(PG:225)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at axlm.a(PG:3)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at axks.run(PG:19)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at axln.run(PG:5)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at aygp.run(PG:59)
11-14 20:30:56.702  8182  8260 W RegistrationCommon:    at java.lang.Thread.run(Thread.java:919)
11-14 20:30:56.745  8182  8216 I Finsky  : [608] aati.h(68): Already at the latest configurations for experiment package com.google.android.finsky.regular.
11-14 20:30:56.745  8182  8216 I Finsky  : [608] aati.h(14): Triggered update for experiment package com.google.android.finsky.regular.
11-14 20:30:56.748  8182  8260 W RegistrationCommon: Failed to create storageInfo for com.google.android.finsky.regular.
11-14 20:30:56.748  8182  8260 W RegistrationCommon: com.google.android.gms.phenotype.core.common.PhenotypeException: 29514: Storage info not created for Play Store.
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at aqod.b(PG:1087)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at aqnz.b(PG:97)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at atkj.call(PG:225)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at axlm.a(PG:3)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at axks.run(PG:19)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at axln.run(PG:5)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at aygp.run(PG:59)
11-14 20:30:56.748  8182  8260 W RegistrationCommon:    at java.lang.Thread.run(Thread.java:919)
11-14 20:30:56.759  8182  8216 I Finsky  : [608] aati.h(68): Already at the latest configurations for experiment package com.google.android.finsky.regular.
11-14 20:30:56.967  8182  8182 I Finsky  : [2] agfz.run(312): Detected restoreservicev2://recovery not needed, will not run
11-14 20:30:57.008  8182  8331 I Finsky  : [669] qix.d(1): registerListener
11-14 20:30:57.008  8182  8331 I Finsky  : [669] ayif.m(6): getDownloads()
11-14 20:30:57.017  8182  8331 I Finsky  : [669] rl.run(51): Initialized AssetModuleDownloader.
11-14 20:30:57.017  4084  4084 I Endpoint: Created gRPC endpoint for service class com.google.frameworks.client.data.android.server.play.BackgroundProcessEndpointService
11-14 20:30:57.023  4084  4258 I Finsky:background: [257] qfh.j(6): DS: getDownloads()
11-14 20:30:57.243  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:57.243  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:58.243  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:58.243  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:58.391  2922  3279 I bbma    : (REDACTED) getHotwordActive::active query: %s, watch: %s, devices connected: %s
11-14 20:30:59.244  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:30:59.244  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:30:59.626  8159  8529 E GoogleApiManager: Failed to get service from broker.
11-14 20:30:59.626  8159  8529 E GoogleApiManager: java.lang.SecurityException: Unknown calling package name 'com.google.android.gms'.
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.Parcel.createException(Parcel.java:2071)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.Parcel.readException(Parcel.java:2039)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.Parcel.readException(Parcel.java:1987)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at anpu.a(:com.google.android.gms@244433016@24.44.33 (100700-694629214):36)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at anob.z(:com.google.android.gms@244433016@24.44.33 (100700-694629214):150)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at amvl.run(:com.google.android.gms@244433016@24.44.33 (100700-694629214):54)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.Handler.handleCallback(Handler.java:883)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.Handler.dispatchMessage(Handler.java:100)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at bsoa.lO(:com.google.android.gms@244433016@24.44.33 (100700-694629214):1)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at bsoa.dispatchMessage(:com.google.android.gms@244433016@24.44.33 (100700-694629214):5)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.Looper.loop(Looper.java:214)
11-14 20:30:59.626  8159  8529 E GoogleApiManager:      at android.os.HandlerThread.run(HandlerThread.java:67)
11-14 20:31:00.034  2163  2477 D EGL_emulation: eglMakeCurrent: 0xd641a900: ver 2 0 (tinfo 0xd640f310)
11-14 20:31:00.244  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:31:00.244  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:31:01.120  2744  2744 D BoundBrokerSvc: onUnbind: Intent { act=com.google.android.gms.feedback.internal.IFeedbackService dat=chimera-action: cmp=com.google.android.gms/.chimera.GmsBoundBrokerService }
11-14 20:31:01.244  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: a: input svInfo.flags is 8
11-14 20:31:01.244  1787  2290 E GnssHAL_GnssInterface: gnssSvStatusCb: b: input svInfo.flags is 8
11-14 20:31:01.527  2017  2326 I ActivityManager: Killing 7832:com.google.android.configupdater/u0a103 (adj 985): empty #17
11-14 20:31:01.560  1771  1771 I Zygote  : Process 7832 exited due to signal 9 (Killed)
11-14 20:31:01.570  2017  2048 I libprocessgroup: Successfully killed process cgroup uid 10103 pid 7832 in 42ms
11-14 20:31:01.909  8182  8182 I Finsky  : [2] afep.onStartJob(128): SCH: job service start with id 9953.
11-14 20:31:01.913  8182  8323 I Finsky  : [662] mgc.a(325): SCH: Satisfied jobs for 9953 are: 12-1
11-14 20:31:01.914  8182  8554 I Finsky  : [690] abya.accept(100): SCH: Job 12-1 starting
11-14 20:31:01.915  8182  8182 I Finsky  : [2] ContentSyncJob.h(11): [ContentSync] job started
11-14 20:31:01.962  8182  8555 W Finsky  : [691] aaiq.d(33): SLM: no metadata property com.android.vending.derived.apk.id found for shared library com.google.android.trichromelibrary_373018518:
11-14 20:31:01.962  8182  8555 W Finsky  : [691] aaiq.d(33): SLM: no metadata property com.android.vending.sdk.version.patch found for shared library com.google.android.trichromelibrary_373018518:
11-14 20:31:01.962  8182  8555 W Finsky  : [691] aaiq.d(33): SLM: no metadata property com.android.vending.derived.apk.id found for shared library com.google.android.trichromelibrary_672308636:
11-14 20:31:01.962  8182  8555 W Finsky  : [691] aaiq.d(33): SLM: no metadata property com.android.vending.sdk.version.patch found for shared library com.google.android.trichromelibrary_672308636:
11-14 20:31:01.963  8182  8555 W Finsky  : [691] aaiq.d(33): SLM: no metadata property com.android.vending.derived.apk.id found for shared library com.google.android.trichromelibrary_672310636:
11-14 20:31:01.963  8182  8555 W Finsky  : [691] aaiq.d(33): SLM: no metadata property com.android.vending.sdk.version.patch found for shared library com.google.android.trichromelibrary_672310636:
11-14 20:31:01.963  2744  2744 D BoundBrokerSvc: onUnbind: Intent { act=com.google.android.gms.safetynet.service.START pkg=com.google.android.gms }
11-14 20:31:02.209  8182  8228 I Finsky  : [613] wfm.r(41): Completed 0 account content syncs with 0 successful.
11-14 20:31:02.209  8182  8182 I Finsky  : [2] ContentSyncJob.a(14): [ContentSync] Installation state replication succeeded.
11-14 20:31:02.209  8182  8182 I Finsky  : [2] afcz.q(61): SCH: jobFinished: 12-1. TimeElapsed: 295ms.
11-14 20:31:02.214  8182  8269 I Finsky  : [628] qsn.accept(59): SCH: Scheduling phonesky job Id: 1-1337, CT: 1731614883300, Constraints: [{ L: 30211796, D: 73411796, C: CHARGING_NONE, I: IDLE_NONE, N: NET_ANY }]
11-14 20:31:02.216  8182  8259 I Finsky  : [623] mgb.apply(152): SCH: Scheduling 1 system job(s)
11-14 20:31:02.216  8182  8259 I Finsky  : [623] afcv.b(261): SCH: Scheduling system job Id: 9974, L: 28832880, D: 72032880, C: false, I: false, N: 1
11-14 20:31:02.217  8182  8554 I Finsky  : [690] afep.a(26): SCH: job service finished with id 9953.
11-14 20:31:02.231  2562  2562 D BoundBrokerSvc: onUnbind: Intent { act=com.google.android.gms.clearcut.bootcount.service.START pkg=com.google.android.gms }
