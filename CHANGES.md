# 1.2.1 (pending next release)

 - **[Breaking]** `ColorUtil.blendRGBWithSaturation(...)` changed signature to include result parameter to avoid ambiguity
 - **[Breaking]** ColorUtil methods removed if they duplicated functionality from the Color class.
 - **[Breaking]** ColorUtil methods involving hue changed from 0-1 scale to 0-360 scale.
 - Added tweens. API not yet stable.