# Microsoft-Office-Policies

These policies are written with personal use in mind, so that I can configure Microsoft Office for security and privacy on my personal systems. Certain features are disabled because I see them as unnecessary, annoying, or potentially privacy invasive.

In general, `OfficeExperiencesDownloadingContentPreference` and Cloud Fonts may not be as privacy invasive as the other Connected Experiences options; however, I do need these feature, so I turned them off. Depending on your environment and use-case, you might want to turn them back on.

The documentation for Office Policies is scattered on several different pages:
- https://learn.microsoft.com/en-us/microsoft-365-apps/privacy/mac-privacy-preferences
- https://learn.microsoft.com/en-us/microsoft-365-apps/mac/mau-preferences
- https://learn.microsoft.com/en-us/microsoft-365-apps/mac/preferences-add-ins
- https://learn.microsoft.com/en-us/microsoft-365-apps/mac/set-preference-macro-security-office-for-mac
- https://learn.microsoft.com/en-us/microsoft-365-apps/mac/preferences-office

The LLM writing the docs may have hallucinated on `DisableVisualBasicMacScript`. I think it should be set to true for better security.

## Installation

See the documentation for my [Microsoft Edge Policies](https://github.com/TommyTran732/Microsoft-Edge-Policies#macos). 

This is pretty much the same, the 2 policy files need to go to `/Library/Managed Preferences`. You will have to set up a fake MDM if you are not enrolled in one.