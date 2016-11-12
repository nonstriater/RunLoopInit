

## <CFRunLoop 0x618000168100 [0x109227c70]>

{	wakeup port = 0x1e03, 
	stopped = false, 
	ignoreWakeUps = false, 
	current mode = kCFRunLoopDefaultMode,
	common modes = <CFBasicHash 0x61800004ca20 [0x109227c70]>{type = mutable set, count = 2,
		entries =>
			0 : <CFString 0x10abca770 [0x109227c70]>{contents = "UITrackingRunLoopMode"}
			2 : <CFString 0x1091ff8e0 [0x109227c70]>{contents = "kCFRunLoopDefaultMode"}
	},


common mode items = <CFBasicHash 0x61800004ca80 [0x109227c70]>{type = mutable set, count = 15,
entries =>

	//source
	0 : <CFRunLoopSource 0x610000168400 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x0, callout = PurpleEventSignalCallback (0x10e4b7733)}}
	
	2 : <CFRunLoopSource 0x610000169000 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 19483, subsystem = 0x10ab929a0, context = 0x0}}
	
	5 : <CFRunLoopSource 0x610000168c40 [0x109227c70]>{signalled = Yes, valid = Yes, order = -2, context = <CFRunLoopSource context>{version = 0, info = 0x60800004c930, callout = __handleHIDEventFetcherDrain (0x10a505be5)}}

	6 : <CFRunLoopSource 0x600000169180 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 25347, subsystem = 0x10ff5ef50, context = 0x6100000b9020}}
	
	7 : <CFRunLoopSource 0x610000168f40 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x608000105a90, callout = __handleEventQueue (0x10a504508)}}
	
	14 : <CFRunLoopSource 0x6000001684c0 [0x109227c70]>{signalled = Yes, valid = Yes, order = 0, context = <CFRunLoopSource context>{version = 0, info = 0x600000069580, callout = FBSSerialQueueRunLoopSourceHandler (0x10fb87dfc)}}
	
	15 : <CFRunLoopSource 0x610000168100 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 23819, subsystem = 0x10aba84d0, context = 0x618000025b00}}
	
	19 : <CFRunLoopSource 0x608000168040 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 1, info = 0x3b03, callout = PurpleEventCallback (0x10e4b9c30)}}
	
	21 : <CFRunLoopSource 0x618000168040 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFMachPort 0x618000157600 [0x109227c70]>{valid = Yes, port = 1d03, source = 0x618000168040, callout = _ZL20notify_port_callbackP12__CFMachPortPvlS1_ (0x109a7ff79), context = <CFMachPort context 0x0>}}



	//observer
	1 : <CFRunLoopObserver 0x6100001348c0 [0x109227c70]>{valid = Yes, activities = 0x1, repeats = Yes, order = -2147483647, callout = _wrapRunLoopWithAutoreleasePoolHandler (0x109cf5a9a), context = <CFArray 0x61000004e250 [0x109227c70]>{type = mutable-small, count = 1, values = (
	0 : <0x7fce31809048>
)}}

	4 : <CFRunLoopObserver 0x610000134640 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2147483647, callout = _wrapRunLoopWithAutoreleasePoolHandler (0x109cf5a9a), context = <CFArray 0x61000004e250 [0x109227c70]>{type = mutable-small, count = 1, values = (
	0 : <0x7fce31809048>

	

	3 : <CFRunLoopObserver 0x610000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2001000, callout = _afterCACommitHandler (0x109d2771e), context = <CFRunLoopObserver context 0x7fce30f00940>}
	
	22 : <CFRunLoopObserver 0x610000134960 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 1999000, callout = _beforeCACommitHandler (0x109d27676), context = <CFRunLoopObserver context 0x7fce30f00940>}


	
)}}	

	12 : <CFRunLoopObserver 0x608000134460 [0x109227c70]>{valid = Yes, activities = 0x20, repeats = Yes, order = 0, callout = _UIGestureRecognizerUpdateObserver (0x10a22c6e1), context = <CFRunLoopObserver context 0x6080000c8340>}
	

	20 : <CFRunLoopObserver 0x618000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2000000, callout = _ZN2CA11Transaction17observer_callbackEP19__CFRunLoopObservermPv (0x109b23012), context = <CFRunLoopObserver context 0x0>}
		
},




modes = <CFBasicHash 0x61800004ca50 [0x109227c70]>{type = mutable set, count = 5,

entries =>
	
	2 : <CFRunLoopMode 0x610000180d00 [0x109227c70]>{name = UITrackingRunLoopMode, port set = 0x2e0b, queue = 0x610000168280, source = 0x6100001de5a0 (not fired), timer port = 0x3003, 
	
	sources0 = <CFBasicHash 0x61000004cba0 [0x109227c70]>{type = mutable set, count = 4,
entries =>
	0 : <CFRunLoopSource 0x610000168400 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x0, callout = PurpleEventSignalCallback (0x10e4b7733)}}
	1 : <CFRunLoopSource 0x610000168f40 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x608000105a90, callout = __handleEventQueue (0x10a504508)}}
	3 : <CFRunLoopSource 0x610000168c40 [0x109227c70]>{signalled = Yes, valid = Yes, order = -2, context = <CFRunLoopSource context>{version = 0, info = 0x60800004c930, callout = __handleHIDEventFetcherDrain (0x10a505be5)}}
	4 : <CFRunLoopSource 0x6000001684c0 [0x109227c70]>{signalled = Yes, valid = Yes, order = 0, context = <CFRunLoopSource context>{version = 0, info = 0x600000069580, callout = FBSSerialQueueRunLoopSourceHandler (0x10fb87dfc)}}
}
,
		sources1 = <CFBasicHash 0x61000004cc00 [0x109227c70]>{type = mutable set, count = 5,

entries =>
	0 : <CFRunLoopSource 0x618000168040 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFMachPort 0x618000157600 [0x109227c70]>{valid = Yes, port = 1d03, source = 0x618000168040, callout = _ZL20notify_port_callbackP12__CFMachPortPvlS1_ (0x109a7ff79), context = <CFMachPort context 0x0>}}
	1 : <CFRunLoopSource 0x608000168040 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 1, info = 0x3b03, callout = PurpleEventCallback (0x10e4b9c30)}}
	2 : <CFRunLoopSource 0x610000169000 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 19483, subsystem = 0x10ab929a0, context = 0x0}}
	3 : <CFRunLoopSource 0x600000169180 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 25347, subsystem = 0x10ff5ef50, context = 0x6100000b9020}}
	5 : <CFRunLoopSource 0x610000168100 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 23819, subsystem = 0x10aba84d0, context = 0x618000025b00}}
}
,
	observers = (
    "<CFRunLoopObserver 0x6100001348c0 [0x109227c70]>{valid = Yes, activities = 0x1, repeats = Yes, order = -2147483647, callout = _wrapRunLoopWithAutoreleasePoolHandler (0x109cf5a9a), context = <CFArray 0x61000004e250 [0x109227c70]>{type = mutable-small, count = 1, values = (\n\t0 : <0x7fce31809048>\n)}}",
    "<CFRunLoopObserver 0x608000134460 [0x109227c70]>{valid = Yes, activities = 0x20, repeats = Yes, order = 0, callout = _UIGestureRecognizerUpdateObserver (0x10a22c6e1), context = <CFRunLoopObserver context 0x6080000c8340>}",
    "<CFRunLoopObserver 0x610000134960 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 1999000, callout = _beforeCACommitHandler (0x109d27676), context = <CFRunLoopObserver context 0x7fce30f00940>}",
    "<CFRunLoopObserver 0x618000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2000000, callout = _ZN2CA11Transaction17observer_callbackEP19__CFRunLoopObservermPv (0x109b23012), context = <CFRunLoopObserver context 0x0>}",
    "<CFRunLoopObserver 0x610000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2001000, callout = _afterCACommitHandler (0x109d2771e), context = <CFRunLoopObserver context 0x7fce30f00940>}",
    "<CFRunLoopObserver 0x610000134640 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2147483647, callout = _wrapRunLoopWithAutoreleasePoolHandler (0x109cf5a9a), context = <CFArray 0x61000004e250 [0x109227c70]>{type = mutable-small, count = 1, values = (\n\t0 : <0x7fce31809048>\n)}}"
),
	timers = (null),
	currently 500609829 (470501324496232) / soft deadline in: 1.84462736e+10 sec (@ -1) / hard deadline in: 1.84462736e+10 sec (@ -1)
},





	3 : <CFRunLoopMode 0x610000180c30 [0x109227c70]>{name = GSEventReceiveRunLoopMode, port set = 0x3703, queue = 0x6100001684c0, source = 0x6100001de690 (not fired), timer port = 0x3a03, 
	
	sources0 = <CFBasicHash 0x61000004ccf0 [0x109227c70]>{type = mutable set, count = 1,
entries =>
	0 : <CFRunLoopSource 0x610000168400 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x0, callout = PurpleEventSignalCallback (0x10e4b7733)}}
}
,
	sources1 = <CFBasicHash 0x61000004cb70 [0x109227c70]>{type = mutable set, count = 1,
entries =>
	2 : <CFRunLoopSource 0x608000168280 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 1, info = 0x3b03, callout = PurpleEventCallback (0x10e4b9c30)}}
}
,
	observers = (null),
	timers = (null),
	currently 500609829 (470501325727213) / soft deadline in: 1.84462736e+10 sec (@ -1) / hard deadline in: 1.84462736e+10 sec (@ -1)
},




	4 : <CFRunLoopMode 0x618000180c30 [0x109227c70]>{name = kCFRunLoopDefaultMode, port set = 0x1f03, queue = 0x6180001681c0, source = 0x6180001de780 (not fired), timer port = 0x2103, 
	
	sources0 = <CFBasicHash 0x61800004cab0 [0x109227c70]>{type = mutable set, count = 4,
entries =>
	0 : <CFRunLoopSource 0x610000168400 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x0, callout = PurpleEventSignalCallback (0x10e4b7733)}}
	1 : <CFRunLoopSource 0x610000168f40 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 0, info = 0x608000105a90, callout = __handleEventQueue (0x10a504508)}}
	3 : <CFRunLoopSource 0x610000168c40 [0x109227c70]>{signalled = Yes, valid = Yes, order = -2, context = <CFRunLoopSource context>{version = 0, info = 0x60800004c930, callout = __handleHIDEventFetcherDrain (0x10a505be5)}}
	4 : <CFRunLoopSource 0x6000001684c0 [0x109227c70]>{signalled = Yes, valid = Yes, order = 0, context = <CFRunLoopSource context>{version = 0, info = 0x600000069580, callout = FBSSerialQueueRunLoopSourceHandler (0x10fb87dfc)}}
}
,
	sources1 = <CFBasicHash 0x61800004cae0 [0x109227c70]>{type = mutable set, count = 5,
entries =>
	0 : <CFRunLoopSource 0x618000168040 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFMachPort 0x618000157600 [0x109227c70]>{valid = Yes, port = 1d03, source = 0x618000168040, callout = _ZL20notify_port_callbackP12__CFMachPortPvlS1_ (0x109a7ff79), context = <CFMachPort context 0x0>}}
	1 : <CFRunLoopSource 0x608000168040 [0x109227c70]>{signalled = No, valid = Yes, order = -1, context = <CFRunLoopSource context>{version = 1, info = 0x3b03, callout = PurpleEventCallback (0x10e4b9c30)}}
	2 : <CFRunLoopSource 0x610000169000 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 19483, subsystem = 0x10ab929a0, context = 0x0}}
	3 : <CFRunLoopSource 0x600000169180 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 25347, subsystem = 0x10ff5ef50, context = 0x6100000b9020}}
	5 : <CFRunLoopSource 0x610000168100 [0x109227c70]>{signalled = No, valid = Yes, order = 0, context = <CFRunLoopSource MIG Server> {port = 23819, subsystem = 0x10aba84d0, context = 0x618000025b00}}
}
,
	observers = (
    "<CFRunLoopObserver 0x6100001348c0 [0x109227c70]>{valid = Yes, activities = 0x1, repeats = Yes, order = -2147483647, callout = _wrapRunLoopWithAutoreleasePoolHandler (0x109cf5a9a), context = <CFArray 0x61000004e250 [0x109227c70]>{type = mutable-small, count = 1, values = (\n\t0 : <0x7fce31809048>\n)}}",
    "<CFRunLoopObserver 0x608000134460 [0x109227c70]>{valid = Yes, activities = 0x20, repeats = Yes, order = 0, callout = _UIGestureRecognizerUpdateObserver (0x10a22c6e1), context = <CFRunLoopObserver context 0x6080000c8340>}",
    "<CFRunLoopObserver 0x610000134960 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 1999000, callout = _beforeCACommitHandler (0x109d27676), context = <CFRunLoopObserver context 0x7fce30f00940>}",
    "<CFRunLoopObserver 0x618000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2000000, callout = _ZN2CA11Transaction17observer_callbackEP19__CFRunLoopObservermPv (0x109b23012), context = <CFRunLoopObserver context 0x0>}",
    "<CFRunLoopObserver 0x610000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2001000, callout = _afterCACommitHandler (0x109d2771e), context = <CFRunLoopObserver context 0x7fce30f00940>}",
    "<CFRunLoopObserver 0x610000134640 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2147483647, callout = _wrapRunLoopWithAutoreleasePoolHandler (0x109cf5a9a), context = <CFArray 0x61000004e250 [0x109227c70]>{type = mutable-small, count = 1, values = (\n\t0 : <0x7fce31809048>\n)}}"
),
	timers = <CFArray 0x6180000b9260 [0x109227c70]>{type = mutable-small, count = 1, values = (
	0 : <CFRunLoopTimer 0x618000168640 [0x109227c70]>{valid = Yes, firing = No, interval = 0, tolerance = 0, next fire date = 500609830 (1.13532901 @ 470502463124761), callout = (Delayed Perform) UIApplication _accessibilitySetUpQuickSpeak (0x108510da7 / 0x10a15f9ef) (/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/System/Library/Frameworks/UIKit.framework/UIKit), context = <CFRunLoopTimer context 0x61800006b3c0>}
)},
	currently 500609829 (470501325763227) / soft deadline in: 1.13736152 sec (@ 470502463124761) / hard deadline in: 1.13736149 sec (@ 470502463124761)
},




	5 : <CFRunLoopMode 0x600000180c30 [0x109227c70]>{name = UIInitializationRunLoopMode, port set = 0x4507, queue = 0x600000168580, source = 0x6000001de870 (not fired), timer port = 0x4607, 
	sources0 = <CFBasicHash 0x60000004db00 [0x109227c70]>{type = mutable set, count = 1,
entries =>
	1 : <CFRunLoopSource 0x6000001684c0 [0x109227c70]>{signalled = Yes, valid = Yes, order = 0, context = <CFRunLoopSource context>{version = 0, info = 0x600000069580, callout = FBSSerialQueueRunLoopSourceHandler (0x10fb87dfc)}}
}
,
	sources1 = <CFBasicHash 0x60000004db30 [0x109227c70]>{type = mutable set, count = 0,
entries =>
}
,
	observers = (
    "<CFRunLoopObserver 0x618000134780 [0x109227c70]>{valid = Yes, activities = 0xa0, repeats = Yes, order = 2000000, callout = _ZN2CA11Transaction17observer_callbackEP19__CFRunLoopObservermPv (0x109b23012), context = <CFRunLoopObserver context 0x0>}"
),
	timers = (null),
	currently 500609829 (470501327830507) / soft deadline in: 1.84462736e+10 sec (@ -1) / hard deadline in: 1.84462736e+10 sec (@ -1)
},




	6 : <CFRunLoopMode 0x600000180f70 [0x109227c70]>{name = kCFRunLoopCommonModes, port set = 0x5307, queue = 0x600000168940, source = 0x6000001deb40 (not fired), timer port = 0x5403, 
	sources0 = (null),
	sources1 = (null),
	observers = (null),
	timers = (null),
	currently 500609829 (470501327898172) / soft deadline in: 1.84462736e+10 sec (@ -1) / hard deadline in: 1.84462736e+10 sec (@ -1)
},

}
}