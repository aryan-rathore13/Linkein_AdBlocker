# Linkein_AdBlocker Extension
This browser extension removes promoted ads from LinkedIn feeds, providing a cleaner browsing experience on the platform. By identifying and hiding ad components as the page loads and the user scrolls, it ensures that sponsored content does not interrupt the feed.
# Features
Detects and removes promoted LinkedIn posts in real-time
Automatically updates ad removal as the user scrolls through their LinkedIn feed
Efficient ad detection through DOM manipulation
# How It Works
The extension uses the webNavigation API to monitor page navigation events and triggers the ad removal script upon detecting a LinkedIn page load. When the LinkedIn feed is detected, the removeAds function is injected into the page, hiding ad elements by setting their CSS display property to none. This function runs on an interval to capture newly loaded ads while scrolling.
