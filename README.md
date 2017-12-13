# SC-Order-Guide-Fixed

Modification to the SC Order Guide widget in ServiceNow

1. fixes the items+submit part of the widget so that it scrolls with the window
2. replaces the scrollTo functionality with anchorScroll since scrollTo doesn't handle anchors well if not at the top of page
3. adds a "top of form" link to the items

To implement, clone the SC Order Guide widget and then update the code with the code here.
