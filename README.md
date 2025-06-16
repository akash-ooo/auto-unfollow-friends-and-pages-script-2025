# Facebook Unfollow Automation Script

This JavaScript script automates the process of unfollowing users on Facebook by clicking the three-dot menu and then the "Unfollow" button with human-like delays. It also handles dynamically loaded content by scrolling to load more users.

---

## How to Use

1. **Open Facebook Unfollow Page**

   Go to the Facebook page where your unfollow list is visible.  
   Example URL:  https://www.facebook.com/username/following

2. **Open Browser Console**

- Press `F12` or right-click on the page and select **Inspect**.
- Navigate to the **Console** tab.

3. **Paste and Run the Script**

Copy the entire JavaScript code from this repository and paste it into the console, then press `Enter` to run.

4. **Watch the Automation**

The script will start clicking the three-dot menu and unfollow buttons automatically with appropriate delays, logging progress in the console.

---

## Configuration / Customization

- At the **top of the script**, you will find these selectors:

```js
const unfollowListContainerSelector = '.x78zum5.x1q0g3np.x1a02dak.x1qughib'; // Container holding the list of peoples and pages
const threeDotSelector = '.x1b0d499.xep6ejk'; // Selector for the 3-dot menu button
const unfollowText = 'unfollow'; // Text of the unfollow button (case-insensitive)
