> [!yellow-clear]+ What's new in v1.7.4
> 
>## Improvements
>
>- The "Close all tabs in tab group" command is no longer available insidebars.
>
>## No longer broken
>- Editor commands no longer trigger when the tab title is focused.- Fixed URI action always getting delivered to the main window instead of the active pop-out window.
>- Fixed clipboard URI actions not working when a pop-out window is active.
>- Fixed pinned icons not appearing on tabs until the tab is focused.
>- Fixed issue with community themes only showing light or dark themes when the current theme is set to adapt to system.
>- Fixed issue where sidebar tabs would stay focused after collapsing the sidebar.
>- Fixed `Shift-ArrowUp` in the editor causing the inline title to get focused.
>
> ## Developers
>
>- Lucide icons have been updated to 0.446.0.
>- Fixed `requestUrl` failing silently when the URL fails to resolve.

>[!green-clear]+ What's new in v1.7.3
>## Improvements
>
>- If a plugin takes a while to load at startup, a message will appear and give you the option to disable the plugin and restart the app.
>- The startup debug screen now shows how long individual plugins took to load.
>
>## No longer broken
>
>- Fixed sidebar views not always updating to reflect the latest active file.
>- Fixed extra history entries appearing in the view navigation list.
>- Fixed `append` and `prepend` URI actions adding extra newlines when the file content is empty.


