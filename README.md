--------------------------------------------------------------------------------
Tweak name = FixWANotications16

ADD THIS REPO TO YOUR PACKAGE MANAGER TO DOWNLOAD THE DEB (EVEN IF IT SAYS INVALID): https://551uk.github.io/fix-wa-notifications-ios-16/

--------------------------------------------------------------------------------

This tweak raises the Jetsam memory limit of WhatsApp's notification ServiceExtension in order to fix missing notifications.

While using my 12 Pro Max on IOS 16.2 (Dopamine 2.0) and my XS Max on 16.3.1 (Dopamine 2.0) i observed the memory usage of WhatsApp servicesExtension using CocoaTop64 tweak. The memory usage would hit 108MB usage highest. This would crash the service when messages got sent as it was hitting the Jetsam memory limit. It would cause the sender to only get one tick on there end until they sent another message then both would be received.

It seems on older model iphones models on IOS 16 the memory usage is higher for what ever reason so i have made this tweak to fix WhatsApp notifications. The 112MB should be enough for everyone.

--------------------------------------------------------------------------------

All credit goes to 0xkuj i just edited his tweak for my usage case - his original tweak is here: https://github.com/0xkuj/FixWANotifs 
