Project name: Kill Switch & the Improvement of Login Experience

💡 EastWest Bank EasyBiz needed a critical fraud-prevention tool accessible pre and post login, but the existing login screen had no infrastructure for it. This project redesigned the pre-login experience from scratch to accommodate Kill Switch feature and establish a scalable quick-link pattern for future security utilities.

This use case will only focusing on pre-login Kill Switch feature in mobile.

Public or NDA: NDA

Client EastWest Bank Business Banking | EasyBiz

My role UX Designer (sole designer)

Platform Mobile (iOS, Android) & web | case study is focussing on pre login mobile journey

Timeline 2026

🌟 Outcome

• Kill Switch is now easily accessible from the login page, as well as post login
• Login screen redesigned with a quick links feature, a scalable pattern for future pre-login utilities
• Reworked the login information architecture to support expanding pre-authentication features

01 background.
A security feature improving user login experience
Kill Switch is a security feature requested by client ot be implemented in EastWest's EasyBiz business banking app and web.

Feature functionality: When a user account is compromised, authorised bank operators can trigger it to immediately block the affected User ID and apply necessary restrictions to all linked accounts and stopping outgoing transactions in real time.

The client's request was straightforward: make Kill Switch accessible from the login screen for rapid response. The problem was that the existing login screen had no mechanism for pre-login actions.

By adding the Kill Switch feature on the pre-login screen, it means we are redesigning information architecture of the app's entry point entirely.

02 users.
Who uses this and what they need
The type of users that using this EasyBiz. These users handle real payments under time pressure, often with different access levels.
Maker
Creates and submits transactions. Needs clear progress and confirmation that submissions are successful. Only able to initiate Kill Switch. Needs to act fast without navigating through the full app. Authentication is required before execution 
Checker Reviews and approves transactions. Needs quick visibility of pending tasks. Formally authorises an already-executed Kill Switch. Some Makers are also Checkers

03 identified problems.
The OOTB login journey wasn’t created to enable pre login journey

problem 01
No pre-login utility layer
The original / OOTB login screen only facilitates 2 actions, both related to login. Biometric and Passcode. There are no infrastructure to allow bank to have secondary utilities

problem 02
Kill Switch only accessible post login Without adjustment in the login journey, accessing Kill Switch required full authentication first, then navigating into the Security section. In a fraud scenario, that delay matters.

problem 03
Any change to login will affect the app IA The login screen is the app's entry point. Adding anything to it isn't cosmetic — it restructures how users orient themselves from the first screen they see, and sets a precedent for every future addition.

🎙️ voice of customer
"Having Kill Switch accessible from login is important.”

04 solutions.
Step by step login journey restructuring

solution 01 - first iteration
Kill Switch entry point added to the login journey
The first iteration introduces Kill Switch access directly into the pre-login screen. An "Activate Kill Switch" link sits below the primary login actions, clearly separated from the authentication flow but immediately visible.

What important changes made in this intermediate stage
• Placement of the biometric button and passcode button
• Adding pre login Kill Switch button at the bottom
• Adding branding on the login screen

Why this intermediate stage matters
🌟 This stage makes Kill Switch reachable immediately, faster implementation without giving a heavy restructuring of the login journey

solution 02 - next step iteration
Maximizing Login Journey ROI While Safeguarding Risk Controls

In this next step iteration, quick links access was introduced to house key pre-login functions, including Kill Switch and other feature than can bring ROI to the bank, for example, Loan or Credit Card application links. This provides users with a permanent, easily discoverable location for essential utilities without interrupting the login flow.

The login screen was also redesigned to establish a clearer visual hierarchy, featuring Face ID as the primary actions, with passcode login option positioned as a secondary layer below. This creates a more focused and streamlined sign-in experience while maintaining access to critical pre-login services.

Why it matters
🌟 Transforms the login screen into a conversion touchpoint by providing direct access to account opening and credit card applications, increasing product visibility, reducing friction, and driving higher customer acquisition opportunities

Information Architecture
How the IA evolved

Introducing the Kill Switch to the pre-login screen was more than a UI enhancement, it redefined the app’s entry-point structure and expanded what the login screen can do.

Before  – Splash screen  – Login screen (Face ID / passcode only)  – No pre-login utilities  – Kill Switch buried under Security settings (post-login)

After  → Splash screen (unchanged)  → Login screen with quick-link dock  → Pre-auth Kill Switch access via login dock  → Kill Switch flow: confirm → authenticate → result  → Scalable dock pattern for future utilities

05 key takeaways.

my role
Led UX design from discovery to delivery, redesigning the login experience to support secure pre-login actions while establishing a scalable framework for future features.

key learning
The solution wasn't adding a Kill Switch button—it was creating a more flexible pre-login architecture that could scale beyond a single use case.

Impact
🌟 Intermediate step Kill Switch feature has been implemented on Q1 2026
🌟 Established a reusable quick-link pattern that improves accessibility for critical actions and supports future business and security requirements.