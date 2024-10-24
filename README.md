TKExplorer - A Simple Python-Based Browser
Created by Paul Stultz

---------------------------------

Disclaimer: TKExplorer has minimal security features. It's designed to demonstrate the capabilities of Python 3.12.1 and existing libraries in creating a basic browser. It cannot run JavaScript and is intended for safe, well-established websites.

Prerequisites
- Python 3.12.1 installed as a Windows app. You can download it from the Microsoft Store (https://www.microsoft.com/store/productId/9PJPW5LDXLZ5).
- Required modules: TkHTMLview and BeautifulSoup4.
These can be installed with pip through the command prompt, here are the commands: 'pip install tkhtmlview' and 'pip install beautifulsoup4'.

How to Run:
- On Windows, unzip the package and double-click 'launch.bat'. Compatible with versions of Windows that support Python 3.10.

New features in 2.0.0:

-Home Button: Redirects user to https://www.visitpaul.com.

-Reload Button: The user can now reload the current page with a Reload button, refreshing the displayed content without entering the URL again.

-Bookmarks: Users can add bookmarks to a menu by clicking the Add Bookmark option, which is accessible from the menu bar. Each bookmark is dynamically listed for easy navigation.

-Keyboard Shortcuts:

    Enter: Load the URL in the entry box.
    Alt + Left Arrow: Navigate back in history.
    Alt + Right Arrow: Navigate forward in history.
    Ctrl + R: Reload the current page.

-Loading Indicators:

   A loading message (Loading...) appears when a URL is being fetched.
   A status bar updates with the current URL or relevant messages like "Error" or "Bookmarked".

-URL Input Auto-correction: The URL entered by the user is automatically prepended with http:// if neither http:// nor https:// is included.

Feedback and Contact:
- https://VisitPaul.com

This project is a showcase of rapid development using Python and is not intended for practical web browsing.

I hope you enjoy exploring TKExplorer!
