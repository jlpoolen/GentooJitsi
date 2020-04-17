# GentooJitsi
Installing Jitsi on a Gentoo System

Video conferencing is now a must given recent stay-at-home policies due to a the COVID-19 virus.  Zoom has been a forefront runner until problem arose.  Jitsi is a competing product which is open source AND you can run your own server making the entire video conference experience completely within your control and protection.

There currently is not a Gentoo ebuild and probably will not be because of the various components required for the Jitsi service.  Notably, Node Package Manager ("npm") is required and Gentoo disavows npm due to its vulnerability.  But if your willing to take the risk installing and using npm, then Jitsi is a possible alternative to Zoom.

Jitsi is designed for Debian so the task at hand is to dissect the Jitsi build paradigm and create a Gentoo install punch list... just like the Gentoo Handbook for installing Gentoo.  This project will serve as a springboard to see if there is collaboration among Gentoo enthusiasts for Jitsi and will continue to serve until something more official is embedded into the Gentoo Wiki.

Dated: April 18, 2020
