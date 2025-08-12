# Flight log 1.0.1

### Major Changes

#### Date device added

* "Date added" is now visible on the device page under Settings for all registered devices.

#### "+ Remain true for" for conditions

* “+ Remain true for” button. This feature allows users to create rules that are triggered only if a condition (e.g., motion detection) remains true for a specified duration.
* The "Remain true for" field is connected to specific conditions, and when the condition is deleted, the "Remain true for" field is also removed.
* Notification resolved. To receive new notifications when a rule is triggered, the user must first complete all previously received notifications.



#### Improved Local Services Deployment

* Enhanced the local deployment process for services to streamline development and testing.
* Goal: Each service is now easily deployable locally with a single command, reducing setup complexity and improving development efficiency.



#### &#x20;AI Assistant Integration

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeTRiH4ZKTOvJ1E6Hwl21De_rxcQOrmoRWUIA6C-zg-aAZEnYTnfVD7g-sQvsHdf73_Vi-X1XpqB9PhExI5Fv67NSU36TJO3eOUHx9vJMZHfVHX7TMBEn84DXl8PdJTg3eCys6aXXi1XMSr1RAdCw?key=tNsubmjd5HuEL0rOWRh-uQ)

* Introduced a new AI Assistant to provide intelligent support and data insights across the platforms.
* The assistant can interact with users in chat form, leverage platform-specific contexts for better reasoning, and generate visual insights from device data.

### Minor Changes

#### Remove signing on wallet deleting

* Remove wallet. No signature is required to confirm the deletion of a wallet from a user's account.
* Removed the requirement for signing when deleting a wallet.\

* This update streamlines the process by eliminating the need for user authentication (e.g., signature) when removing a wallet from the system.

#### Add Metrics Tracking to Site and Application

* Integrated metrics tracking into the site and application to monitor user behavior across various scenarios.\

* Set up tracking for key actions: adding a device, adding a widget to the dashboard, and creating a rule.\

* Metrics will help identify where users drop off, where they experience delays, and where they proceed smoothly.



#### Bug Fix: DC Balance Displays as Zero During Impersonation

* Fixed a bug where the DC balance incorrectly displayed as zero during impersonation sessions.

#### Bug Fix: Unable to Top Up DC — All Payment Methods Failing

* Fixed a critical issue preventing users from topping up Data Credits (DC) via the NowPayments integration.

#### Bug Fix: Wrong Error Message When Wallet Has 0 Chirp Tokens

* Fixed an issue where users with a connected wallet and a 0 Chirp token balance received an incorrect error message.

#### UX Improvement: Subscription Page – Replaced Technical Parameters with User-Friendly Feature Names

* Improved the Subscription page by replacing technical or configuration-style terms with clear, user-friendly feature names.

#### Bug Fix: Users Able to View Other Accounts’ Notifications via Search

* Fixed a security issue where users could inadvertently access notifications belonging to other accounts by using the search function.
