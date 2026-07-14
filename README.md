# Microsoft-Office-Policies

These policies turn off Connected Experiences without requiring the user to log into their Microsoft account and limit telemetry (which is not configurable at all otherwise).

In general, `OfficeExperiencesDownloadingContentPreference` may not as privacy invasive as the other Connected Experiences options; however, I do not have a need for this feature, so I turned it off. Depending on your environment and use-case, you might want to turn it back on.

## Installation

See the documentation for my [Microsoft Edge Policies](https://github.com/TommyTran732/Microsoft-Edge-Policies#macos). 

This is pretty much the same, the 2 policy files need to go to `/Library/Managed Preferences`. You will have to set up a fake MDM if you are not enrolled in one.