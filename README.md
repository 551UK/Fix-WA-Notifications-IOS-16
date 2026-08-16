Raises the Jetsam memory limit of whatsApp's notification ServiceExtension in order to fix missing notifications.

While using my 12 Pro Max on IOS 16.2 Dopamine and my XS Max on 16.3.1 i observed the memory usage of whatapp servicesExtension using CocoaTop tweak. The memory usage would sit at around 108MB. This would crash the service when messages got set as it was hitting the limit. It would cause the sender to only get one tick on there end until sending another message than both would be received. 

It seems on older model iphones on IOS 16 the memory usage is higher for what ever reason so i have made this tweak to fix whatapp notifications. The 112MB should be enough for everyone.

All credit goes to 0xkuj i just edited his tweak - his original tweak is here: https://github.com/0xkuj/FixWANotifs
