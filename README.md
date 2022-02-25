# CZ-SK-hosts-file-to-block-trackers-and-ads
Hosts files to block the most common trackers and ad-related domains found on the internet. The host files were created by analyzing DNS logs of mostly Czech and Slovak users, altho browsing both local and international websites. 

The hostfile should cause no or very little breakage of legitimate websites.

These host files also block tracking domains that are not included in other lists (including EasyList CZ/SK), such as some trackers found on Czech and Slovak websites.

Optionally, you can choose hosts files completely blocking Facebook. Even if you block Facebook in your browser, apps are commonly connecting to Facebook domains (api.facebook.com and graph.facebook.com) for tracking purposes. The host file with Facebook blocking will completely prevent all known Facebook domains from resolving. Credits for Facebook blocking to: https://github.com/jmdugan/blocklists/blob/master/corporations/facebook/all.
