🌑 Minimalist Firefox Theme
This theme is designed for a clean, distraction-free browsing experience. It achieves a "True Minimalist" look by removing UI clutter, including the background settings buttons.

/data/image.png

🛠️ Installation Guide (Follow in Order!)
Since this theme hides the "Edit" buttons on the New Tab page to keep things clean, you must set your wallpaper first.

Step 1: Set the Wallpaper
Open a New Tab in Firefox.

Click the Settings (Gear icon) in the top-right corner of the page (or the "Personalize" button).

Choose the option to upload a custom background.

Select the wallpaper.png file included in this folder.

Verify: Make sure the wallpaper looks correct before moving to the next step.

Step 2: Enable Custom Styles (about:config)
Firefox needs permission to load our custom code.

Type about:config in your address bar and press Enter.

Click "Accept the Risk and Continue".

Search for: toolkit.legacyUserProfileCustomizations.stylesheets

Double-click it (or click the toggle icon) to set it to true.

Step 3: Install the userContent.css
This file applies the minimalist look and hides the menu buttons you just used.

Type about:support in the address bar and press Enter.

Find "Profile Folder" and click Open Folder (or Show in Finder).

In that folder, check if there is a folder named chrome.

If not: Right-click, create a New Folder, and name it chrome.

Copy the userContent.css file from this download and paste it inside that chrome folder.

Step 4: Install Dependencies (Extensions)
To get the full functionality shown in the showcase image, you need a few specific extensions.

Open the links.txt file included in this folder.

Copy each URL and paste it into Firefox to install the required add-ons.

These extensions handle things like dark mode for websites and custom tab behavior.

Step 5: The Final Restart
For the changes to take effect (and for the UI clutter to disappear), you must restart your browser.

Close all Firefox windows.

Relaunch Firefox.

Enjoy your clean, minimalist setup!

Note: If you ever want to change your wallpaper later, you will need to temporarily remove the userContent.css file from the chrome folder and restart Firefox to bring the settings buttons back.
