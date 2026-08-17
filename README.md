--------------------------------------------------------------------------------
Tweak name = FixWANotications16

ADD THIS REPO TO YOUR PACKAGE MANAGER TO DOWNLOAD THE DEB (EVEN IF IT SAYS INVALID): https://551uk.github.io/fix-wa-notifications-ios-16/

--------------------------------------------------------------------------------

This tweak raises the Jetsam memory limit of WhatsApp's notification ServiceExtension in order to fix missing notifications.

While using my 12 Pro Max on IOS 16.2 (Dopamine 2.0) and my XS Max on 16.3.1 (Dopamine 2.0) i observed the memory usage of WhatsApps ServicesExtension using CocoaTop64 tweak. The memory usage would hit 108MB at its highest. This would crash the service when messages got sent as it was hitting the Jetsam memory limit. This would cause the sender to only get one tick on there end until they sent another message then both messages would be received.

It seems on older model iphones on IOS 16 the memory usage is higher for what ever reason, so i have made this tweak to fix WhatsApp notifications. The 112MB should be enough for everyone. Start at the lowest and work up.

--------------------------------------------------------------------------------

All credit goes to 0xkuj i just edited his tweak for my usage case - his original tweak is here: https://github.com/0xkuj/FixWANotifs 
