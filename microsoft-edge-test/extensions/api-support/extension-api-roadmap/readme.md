---
description: Find information on current progress towards completing the Microsoft Edge extension API.
title: Extension API roadmap
author: abbycar
---

# Microsoft Edge extension API roadmap

In addition to web APIs, the extension API allows extensions to achieve deeper integration with the browser host. This API gives developers access to Microsoft Edge’s browser features such as tab and window manipulation.  Check out the table below for descriptions on how these classes can empower your extensions.

This table also details our current progress towards completing the Microsoft Edge extension API. Status updates will be made here as classes move through development towards completion.

> [!NOTE]
> Native messaging is currently in development.
| Class         | Description | Status — Build Number
|---------------|--------------|---------------------|
bookmarks     | Used to create, organize, and manipulate bookmarks. | In development |
browserAction | Enables extensions to add a persistent button within Microsoft Edge. | Supported — Microsoft Edge (38) / Windows 10 (14393)
contextMenus  | Adds a context menu item on a specific URL, in a specified context of a webpage. | Supported — Microsoft Edge (38) / Windows 10 (14393)
cookies       | Used to query and modify cookies, as well as notify when they change. | Supported — Microsoft Edge (38) / Windows 10 (14393) |
downloads     | Used to programmatically initiate, monitor, manipulate, and search for downloads. | Under consideration |
extension     | Contains utilities that can be used by any extension page. | Supported — Microsoft Edge (38) / Windows 10 (14393)      |
history       | Interacts with the browser's record of visited pages. | Under consideration |
i18n          | Implements internationalization across an extension. | Supported — Microsoft Edge (38) / Windows 10 (14393)      |
idle          | Used to detect when the machine's idle state is changed. | Supported — Microsoft Edge (38) / Windows 10 (14393) |
notifications | Allows creation of notifications using templates to be displayed in the user's system tray. | Under consideration |
pageAction    | Enables extensions to add a button inside the address bar. | Supported — Microsoft Edge (38) / Windows 10 (14393)      |
permissions   | Allows users to select what optional permissions they would like to grant an extension access to. | Under consideration
runtime       | Retrieves the background page, returns details about the manifest, and listens for and responds to events in the extension lifecycle. | Supported — Microsoft Edge (38) / Windows 10 (14393)
storage       | Used by the extension to read/write data and to sync data. | Supported — Microsoft Edge (38) / Windows 10 (14393)
tabs          | Interacts with Microsoft Edge's tab system by creating, modifying, and rearranging tabs in the browser. | Supported — Microsoft Edge (38) / Windows 10 (14393)
webNavigation | Used to receive notifications about the status of navigation requests in-flight. | Supported — Microsoft Edge (38) / Windows 10 (14393)
webRequest    | Enables use of the webRequest API to observe and analyze traffic and to intercept, block, or modify requests in-flight. | Supported — Microsoft Edge (38) / Windows 10 (14393)
windows       | Interacts with the browser by creating, modifying, and rearranging windows. | Supported — Microsoft Edge (38) / Windows 10 (14393)
