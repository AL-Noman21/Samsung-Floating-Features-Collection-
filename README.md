# Samsung-Floating-Features-Collection-
Samsung Floating Features Collection

Samsung Floating Features Collection For Custom Rom .

You need to add those code into your floating_feature.xml

Floating feature locating >

# If you have just system partition then 

    system/etc/floating_feature.xml

# If you have separate vendor partition then 

    vendor/etc/floating_feature.xml   


# 1 : Screen recorder feature enabler code

    <SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_SCREEN_RECORDER_ITEM>-pip</SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_SCREEN_RECORDER_ITEM>
    <SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_RECORDER>TRUE</SEC_FLOATING_FEATURE_FRAMEWORK_SUPPORT_SCREEN_RECORDER>
   
# 2 : Dolby Atmos all feature enabler code 
 
   <SEC_FLOATING_FEATURE_MMFW_SUPPORT_DOLBY_AUDIO>TRUE</SEC_FLOATING_FEATURE_MMFW_SUPPORT_DOLBY_AUDIO>
   <SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_NUMBER_OF_SPEAKER>1</SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_NUMBER_OF_SPEAKER>
   <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DUAL_SPEAKER>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DUAL_SPEAKER>
   <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DOLBY_GAME_PROFILE>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DOLBY_GAME_PROFILE>
   <SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DEFAULT_ON_DOLBY_IN_GAME>TRUE</SEC_FLOATING_FEATURE_AUDIO_SUPPORT_DEFAULT_ON_DOLBY_IN_GAME>
   
<SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_VERSION>eq_knob,eq_custom,uhq_switch,uhq_level,adapt,spk_stereo,dvfs_860000,tube,concert</SEC_FLOATING_FEATURE_AUDIO_CONFIG_SOUNDALIVE_VERSION>

# 3 : Function menu key enabler code 

    <SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_FUNCTION_KEY_MENU>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_FUNCTION_KEY_MENU>
   
# 4 : High performance enabler code

    <SEC_FLOATING_FEATURE_COMMON_CONFIG_DYN_RESOLUTION_CONTROL>WQHD,FHD,HD</SEC_FLOATING_FEATURE_COMMON_CONFIG_DYN_RESOLUTION_CONTROL>
    <SEC_FLOATING_FEATURE_COMMON_SUPPORT_HIGH_PERFORMANCE_MODE>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_HIGH_PERFORMANCE_MODE>

# 5 : High contrast keyboard enabler code

    <SEC_FLOATING_FEATURE_SIP_SUPPORT_HIGHCONTRAST_KEYBOARD>TRUE</SEC_FLOATING_FEATURE_SIP_SUPPORT_HIGHCONTRAST_KEYBOARD>
   
# 6 : Charging info showing enabler code 

    <SEC_FLOATING_FEATURE_LCD_SUPPORT_AMOLED_DISPLAY>TRUE</SEC_FLOATING_FEATURE_LCD_SUPPORT_AMOLED_DISPLAY>
