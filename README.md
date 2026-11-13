# Belaka - Block User Account

Easily block WordPress user accounts temporarily or permanently. Restrict login, REST API, and authentication access, revoke active sessions, customize messages, send email notifications, and monitor blocking activities.

**Requires at least:** 6.5  
**Tested up to:** 7.1  
**Stable tag:** 2.0.2  
**Requires PHP:** 7.4  
**License:** GPLv2 or later  
**License URI:** https://www.gnu.org/licenses/gpl-2.0.html

## Description

**Take full control of WordPress user account management with Belaka.**

Belaka is a powerful and easy-to-use WordPress plugin that allows administrators to temporarily or permanently restrict user accounts.

Whether you need to prevent a specific user from accessing your website, temporarily suspend an account, or manage multiple user restrictions, Belaka provides the tools you need directly inside your WordPress dashboard.

Unlike basic login restriction tools, Belaka goes beyond standard login forms by applying account restrictions to WordPress authentication, REST API access, and other authentication methods. It also revokes all active user sessions when an account is blocked.

With automatic unblocking, customizable messages, email notifications, activity logs, and detailed statistics, you can manage user restrictions more efficiently from one place.

### Why Use Belaka?

Managing user access is an important part of maintaining a WordPress website.

Website administrators may need to restrict access to accounts involved in suspicious activities, temporarily suspend users who violate website rules, or permanently block accounts that should no longer have access.

Belaka makes these tasks simple by providing flexible account restriction and monitoring tools.

### Key Features

**Easy User Blocking**

Block or unblock individual users with a single click directly from the WordPress users list or their profile page.

- Quickly block or unblock user accounts.
- View account blocking status in the users list.
- Manage restrictions without complicated configurations.
- Administrator accounts are protected from being blocked.

**Temporary and Permanent User Blocking**

Choose between temporary and permanent account restrictions based on your needs.

- Permanently block a user account.
- Set an expiration date for temporary restrictions.
- Choose a blocking duration in hours, days, or months.
- Automatically unblock users when their restrictions expire.

**Comprehensive Access Restrictions**

Prevent blocked users from accessing your website through supported WordPress authentication methods.

- Restrict standard WordPress login.
- Restrict WordPress REST API authentication.
- Apply restrictions to other authentication methods.
- Revoke all active login sessions when an account is blocked.

**Custom Block Messages**

Customize the message displayed to blocked users when they attempt to log in.

- Set a default blocking message in plugin settings.
- Customize messages individually for each user.
- Display appropriate messages for permanent and temporary restrictions.

**Bulk User Management**

Save time by managing multiple user accounts simultaneously.

- Block multiple users at once.
- Unblock multiple users at once.
- Apply blocking duration options to bulk actions.

**Email Notifications**

Keep users and administrators informed about account restrictions.

- Notify users when their accounts are blocked or unblocked.
- Send notifications to administrators about blocking activities.
- Configure email notification settings from the plugin settings page.

**Detailed Activity Logs**

Keep track of account restriction activities with the built-in logging system.

- Record blocking and unblocking activities.
- View activity timestamps.
- Identify the administrator who performed each action.
- Record the reason for blocking a user.
- Review user blocking history from individual profile pages.
- Export activity logs as CSV files.

**Dashboard Widget**

Get a quick overview of account restrictions directly from your WordPress dashboard.

- View the number of blocked users.
- Monitor recent blocking activities.
- Check temporary restrictions approaching their expiration dates.

**Admin Bar Integration**

See the number of blocked user accounts directly in the WordPress admin bar for quick access to account management.

**Blocking Statistics**

Monitor account restriction activity through a dedicated statistics page with charts and trends.

**Built-in Management Tools**

Manage and maintain plugin data with dedicated tools.

- Check expired temporary blocks.
- Clean up activity logs.
- Export activity records.

**RTL Support and Persian Translation**

Belaka supports right-to-left layouts and includes a Persian translation, making it suitable for websites using Persian and other RTL languages.

### Who Can Benefit from Belaka?

Belaka can be useful for different types of WordPress websites, including:

- Membership websites that need to manage member access.
- Online communities that need to restrict problematic user accounts.
- Business websites that require centralized user account management.
- Websites with multiple administrators who need to monitor account restrictions.
- WordPress websites that need temporary or permanent user access restrictions.

### Simple, Flexible, and Efficient

From blocking a single account to managing multiple users and monitoring restriction activities, Belaka brings essential user management tools together in one convenient WordPress plugin.

Protect your website and take control of user account access with Belaka by DangoWeb.

## Installation

1. Upload the `block-user-account` folder to the `/wp-content/plugins/` directory, or install the plugin directly through the WordPress Plugins screen.
2. Activate Belaka - Block User Account through the 'Plugins' menu in WordPress.
3. Navigate to the 'Users' page to access user blocking options.
4. Go to 'Settings > Block User Account' to configure the plugin.
5. Start managing user restrictions directly from your WordPress dashboard.

## Frequently Asked Questions

### Can I block WordPress users temporarily?

Yes. You can set an expiration date for each temporary block. Once the restriction expires, the plugin automatically unblocks the user.

You can choose a blocking duration in hours, days, or months.

### Can I permanently block a user account?

Yes. You can permanently block a user account without setting an expiration date.

### What happens when a blocked user tries to log in?

The plugin prevents blocked users from accessing your website through supported authentication methods and displays the configured blocking message when they attempt to log in.

### Are blocked users logged out automatically?

Yes. When a user account is blocked, all active login sessions for that account are revoked. The user must not be able to continue using previously authenticated sessions.

### Does blocking apply to REST API authentication?

Yes. Blocked accounts are restricted from accessing WordPress through REST API authentication and other supported authentication methods, in addition to standard login.

### Can administrators block other administrators?

Administrator accounts are protected from being blocked by the plugin.

### Can I customize the message displayed to blocked users?

Yes. You can configure a default blocking message in the plugin settings or set a custom message for individual users from their profile pages.

### Will blocked users receive email notifications?

Yes. You can enable email notifications to inform users when their accounts are blocked or unblocked.

The plugin can also send email notifications to administrators about blocking activities.

### Can I block multiple users at once?

Yes. Use the bulk actions dropdown on the WordPress users page to block or unblock multiple accounts simultaneously. You can also configure blocking duration options when applying bulk restrictions.

### Can I record the reason for blocking a user?

Yes. Administrators can enter a reason when blocking a user. The reason is recorded in the activity logs.

### Does the plugin keep a record of blocking activities?

Yes. Belaka includes an activity logging system that records blocking and unblocking actions, timestamps, administrator information, and blocking reasons.

You can also review a user's blocking history from their profile page.

### Can I export activity logs?

Yes. You can export activity logs as CSV files for further review and record keeping.

### Can I see how many users are blocked?

Yes. The plugin provides a dashboard widget, an admin bar indicator, and a dedicated statistics page to help you monitor blocked accounts and related activities.

### Will temporary blocks be removed automatically?

Yes. The plugin uses WordPress cron jobs to check expired temporary restrictions and automatically unblock users when their expiration dates are reached.

You can also use the built-in tools to check expired blocks manually.

### Does Belaka support WooCommerce?

The plugin applies its WordPress account restrictions to WooCommerce users as they use WordPress authentication. It does not currently provide dedicated WooCommerce integration or store-specific account management features.

### Does Belaka support RTL languages?

Yes. The plugin supports right-to-left layouts and includes a Persian translation.

### Where can I manage blocked users?

You can manage user restrictions directly from the WordPress users list or individual user profile pages.

Plugin settings and additional management tools are available under 'Settings > Block User Account'.

## Changelog

### 2.0.2
- Improved user interface.

### 2.0.1
- Fixed REST API authentication bypass for blocked users (security fix).

### 2.0.0
- Complete plugin rewrite with an object-oriented architecture.
- Added temporary user blocking with expiration dates.
- Added automatic unblocking through WordPress cron jobs.
- Added activity logging with CSV export.
- Added email notifications for users and administrators.
- Added bulk blocking and unblocking actions with duration options.
- Added a statistics page with charts and trends.
- Added admin bar menu with blocked user count.
- Added dashboard widget with expiring blocks overview.
- Added a new settings page with an improved interface.
- Added user profile blocking history.
- Added built-in tools for checking expired blocks, cleaning logs, and exporting data.
- Improved security with nonce verification.

### 1.4
- Added Persian translation.
- Fixed login authentication issues.
- Improved toggle switch design.

### 1.3
- Added bulk user actions.
- Added user status columns.

### 1.0
- Initial release.

## Upgrade Notice

### 2.0.2
Includes user interface improvements and all the major account management features introduced in version 2.0. Update to the latest version for the best experience.

## Credits

Developed by [DangoWeb](https://dangoweb.ir)