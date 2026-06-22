Project name: Redesigning Bank Search on SWIFT Transfer Journey

💡 While designing the SWIFT international transfer flow for business banking | EasyBiz platform, I identified a usability issue in how users were expected to find their recipient's bank. Recognising the potential impact on task completion, I proposed new direction with more user centered solution. This became an opportunity to balance business requirements with real user needs, ultimately improving the efficiency of the SWIFT transfer experience.

Public or NDA: NDA

Client EastWest Bank Business Banking | EasyBiz

My role UX Designer (sole designer)

Platform Web (cade study is focusing on web platform) and mobile (iOS & Android)

Timeline 2026 - in development 

🌟 Outcome

• Redesigned the original client requirement and proposed a better structured search sequence. Result: cleaner and more accurate bank selection experience for the SWIFT transfer.

01 background/problem.

Searching first by the bank name creates ambiguity

The client's original requirement asked users to search for their recipient's bank using either a bank name or a SWIFT code as the first primary input.

This breaks down for large international banks. For an example Standard Chartered operates in over 50 countries and each with its own SWIFT code. Searching by bank name returns a long, undifferentiated list. A user sending money to Singapore and a user sending to South Korea would see the same bank name appear multiple times.

Standard Chartered Singapore: SCBLSG22
Standard Chartered South Korea: SCBLKRSE
Standard Chartered South Africa: SCBLZAJJ
Standard Chartered Philippines: SCBLPHMM

The only differentiator is the country code buried inside the SWIFT string, an information most users won't recognise. In an international transfer, selecting the wrong branch means funds sent to the wrong destination.

02 understanding problems.

How SWIFT codes are structured

Before proposing the solution, I mapped out how SWIFT codes actually work. A SWIFT code has four parts:

Image source: https://www.worldfirst.com/uk/help-support/iban-versus-swift-code/

Country is the second element in the code and the most meaningful filter for users initiating an international transfer. (With the assumption) users mostly will know which country they're sending to. They may not know the complete exact bank name, and they almost certainly don't know the SWIFT code upfront.

03 user research : competitive analysis.

How other banking platforms handle this

I reviewed how DBS, UOB, and Revolut handle the same flow. No formal usability study was available — the project timeline didn't allow for it. But the pattern across platforms was consistent enough to make a case.

Platform	Search sequence

DBS	Country → Bank name → Branch
UOB	Country → Bank name → Account details	
Revolut	Country → Bank details

04 solutions.

Country first, then bank name

I proposed to change the search sequence to mirror how users naturally think about an international transfer: country first then bank name to follow.

Country → Bank name (filtered) → Branch + account details

Once a country is selected, the bank name field filters to institutions registered in that country only, reducing the list and eliminating cross-country duplicates. The core team (BA and SA) discussed this ideation of the SWIFT code structure and the competitive examples. The change was accepted by the team.

original design / flow of SWIFT for fields ↓


05 design.

The redesign form

The "Transfer to" section opens with a country selector as the first input. Bank name and branch fields follow, progressively revealed as the user narrows down.

06 key takeaways.

The redesigned flow is currently in development (2026 Q2). The client initially pushed back on the proposal. Their original approach was based on the assumption that users could search using any part of the SWIFT code structure, including country, bank, and branch information.

I presented the proposed solution alongside the Business Analyst, supported by competitive benchmarking and a breakdown of the search behaviour. 

Impact

🌟 Improved search accuracy by limiting results to banks within the selected country
🌟 Reduced the risk of selecting the wrong bank or branch, particularly for global institutions with similar names
🌟 Lowered users’ cognitive load by replacing a broad global search with a more narrow lookup process