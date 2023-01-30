---
layout: post
title:  "make my browser easier to use"
date:   2023-01-30 22:17:26 +0800
categories: browser
---
I often have more than ten pages open at once while using my browser to search information. When a new tab is opened at the end, i tend to loes my place. Is there a way to make new tabs open after the current tab?
Yes! absolute!
## safari
```
tell application "Safari"
  tell front window
    set _old_tab to current tab
    set _new_tab to make new tab at after _old_tab
    set current tab to _new_tab
  end tell
end tell
```

## microsoft edge
[extensions](https://microsoftedge.microsoft.com/addons/detail/open-new-tab-after-curren/deebimacbjlpdcfbpacpckoccjnojacb)



