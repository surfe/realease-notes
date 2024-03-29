# Release Notes

## 2.0 (October 21, 2022)

- Rebrand to Surfe!
- Introduce Deal Pipeline view
- Lots of bug fixes

**2.0.1**

- Fix highlight logic
- Update Intercom links
- Update Chrome URLs

**2.0.2**

- Fixes

**2.0.3**

- Change welcome modal copywriting
- Invite owner when not a Surfe user
- Fix SN list export

**2.0.4**

- Introduce "Link to another record" feature
- Fix bug where contacts are added to the wrong company

**2.0.5**

- Increase size of task's comment section
- Display owner of shared templates
- Mark mandatory fields in tasks

**2.0.6**

- Add delete task button
- Fix onboarding tooltips

## 1.30 (September 29, 2022)

- Edit contact fields on click
- Show the number of Notes on profile
- Fix enrichment loading and fetch

**1.30.1**

- Fix repeated fields requests

**1.30.2**

- Introduce enrichment feature during onboarding
- Fix dates in tasks
- Add support for currency and date fields

**1.30.3**

- Fix Deals on SalesNav

## 1.29 (August 3, 2022)

- Migrate to Manifest V3

**1.29.1, 1.29.2, 1.29.3**

- Fix Manifest V3 permissions

**1.29.4**

- Display all Tasks related to a Contact
- Implement real-time event notification
- Fix Primary association removed when updating Contact (HubSpot)
- Fix Job Update count
- Remove "refresh page" notification

**1.29.5**

- First Deal Pipeline view implementation
- Fix modal height
- Fix Ember redirects

**1.29.6**

- Fixes

**1.29.7**

- Fix sync conversation
- Change note initial state to full view
- Mark voice notes in conversation sync

**1.29.8**

- Send contact pictures to HubSpot
- Display task details in side panel

## 1.28 (June 11, 2022)

- Implement Note Templates + default examples
- Notes can be saved with Ctrl+S shortcut
- Support Saved Searches in SalesNav
- Ignore some LinkedIn URLs to avoid errors
- Fix Notes not saving if only title was edited
- Fix SalesNav API queries
- Fix multiple layer induced error

**1.28.1**

- Integrate with ZeroBounce
- Truncate floating point numbers display

**1.28.2**

- Fix Smart Conversations
- Fix SalesNav integration after layout change

**1.28.3**

- Fix UI not injected in some SalesNav profiles
- Fix smart conversation not injected in bubbles

**1.28.4**

- Export connexion degree level
- Support second phone field
- Fix message templates shortcut

**1.28.5**

- Fix personal emails not being sent to CRM
- Fix {current_position} template placeholder
- Fix "invalid message" error on empty SalesNav bubble conversations
- Fix duplicate company when different name after adding new Contact

**1.28.6**

- Change Task design in Contact section
- Fix bubble conversations

**1.28.7**

- Fix popup alert design

## 1.27 (April 08, 2022)

- Redesign Notes in side panel (mnimized & extended views)
- Export Contacts / Companies from SalesNav Search page
- Link Contacts to existing Deals

**1.27.1**

- Prioritize personal phone numbers from third party enrichment tools
- Fix issue where Deals are not ediable after they first loaded
- Fix issue causing the wrong deal to be linked to a Company
- Fix tooltips

**1.27.2**

- Export funding amount of Company
- Fix content script injection issue causing Leadjet to disappear
- Fix localstorage capacity
- Fix extra fields overflow on SalesNav

**1.27.3**

- Support rich text edition in Notes (bold, italic, lists, ...)
- Redesign drop-downs for labels
- Required fields displayed on top and not breaking regular fields' layout
- Fix browser API issue preventing onboarding
- Reduce errors "User not found" and for pages not supported

**1.27.4**

- Choose what Company to be sent to the CRM if contacts has multiple recent ones
- Add cmd+Enter shortcut to add note
- SalesNav list are highlighted faster
- Improve status dropdown UX
- Improve error handling
- Improve sync conversation feature
- Fix extra fields grid layout
- Fix authentication portal not closing

## 1.26 (January 15, 2022)

- Refactor code-base (domain driven)
- Support checkbox field type
- Fix highlight in SalesNav lists

**1.26.1**

- Render conversation timestamps based on user's location
- Improve contact-update notification display

**1.26.2**

- Fixes

**1.26.3**

- Improve Company matching
- Fix fields alignment
- Upgrade dependencies

**1.26.4**

- Fix contact update displayed total
- Fix email finder tool API connexion

**1.26.5**

- Fix enrichment on SalesNav
- Fix wrong deal displayed for contact

**1.26.6**

- View Company deals from Contact profile
- Change Contact owner directly from the Leadjet section
- Fetch Companies specialties
- Show most recent Deal in caroussel first
- Perform list export in the background
- Fix welcome panel display display

**1.26.7**

- Add Company to new Deal
- Add past experiences to CRM from SalesNav
- Fix templates

**1.26.8**

- Move Contact Updates to side panel
- Export Connection Level to CRM

**1.26.9**

- Move Notes to the side panel
- Fix Leadjet unable to work alongside some third-party extensions
- Rebrand Salesloft

**1.26.10**

- Support new SalesNav Contact layout
- Filter Salesloft cadences by name / team

## 1.25 (December 30, 2021)

- V1 Contact Update feature

**1.25.1**

- Export SalesNav list name with exported contacts
- Fix notification shadows

## 1.24 (September 17, 2021)

- Revamp Note taking from LinkedIn profile
- Make Notes editable from Copper
- Optimize API calls made to CRMs
- Basic cache optimizations
- Enable Org search autocomplete for Hubspot

**1.24.1**

- New design for onboarding tooltips
- Add shortcut to Leadjet dashboard in Navbar
- Fix message Templates not displayed in "New message" bubble conv
- Fix list export

**1.24.2**

- Implement Salesloft new branding
- Improve conversation handling
- Fix SVG display

**1.24.3**

- Improve multi-value dropdowns

**1.24.4**

- Support Salesforce RecordTypes and custom Layouts
- Remove "Set LinkedIn URL" step from onboarding
- Automate LinkedIn URL matching based on CRM's config
- Introduce navbar notification system
- Fix LinkedIn URL format
- Fix button display issues
- Throttle API calls

**1.24.5**

- Add "Go Premium" panel for premium features
- Fix display issues

**1.24.6**

- Display HubSpot german ebook link
- Fix navbar URL
- Fix SalesNav list export

**1.24.7**

- Implement new HubSpot invitation workflow

**1.24.8**

- Ask for required fields before add to CRM
- Add "Rate us" notification
- Refacto CSS

**1.24.9**

- Quick fix API version change

**1.24.10**

- Fix injected onboarding

**1.24.11**

- Support Company page on LinkedIn SalesNav
- Add SalesNav URL custom field
- Redesign extension popup
- Notify successful Salesloft action
- Fix contact highlighting

**1.24.12**

- Display panel when not enough credits
- Display info bubble when hovering contacts
- Highlight Companies in SalesNav account lists
- Fix duplicate "More fields" button
- Fix extra fields display

**1.24.13**

- Remove support for Firefox addons
- Simplify Copper's welcome panel
- Serve API endpoints dynamically

## 1.23 (August 12, 2021)

- Display email/phone enrichment provider and dynamic cascading
- Provide help on the CRM selection onboarding panel
- Fix SalesNav smart conversations
- Fix various CSS selectors
- Fix profile picture not being sent to Pipedrive
- Fix responsiveness of embedded Deals

**1.23.1**

- Fix SalesNav URL in conversations

**1.23.2**

- Improve OAuth process

**1.23.3**

- Export list as Lead
- Update Firefox version
- Smooth section appearance
- Prevent same embedded field to be used more than once

**1.23.4**

- Revamp onboarding step-by-step tutorial
- Disable Update button when not needed
- Export Twitter handle & Industry from LinkedIn
- Fix blank panel at startup
- Fix Company section above dropdowns

**1.23.5**

- Improve extra fields display
- Fix SVG width browser support
- Fix Export to CRM button not appearing
- Improve wording

## 1.22 (May 20, 2021)

- Sync LinkedIn conversation using API
- Display Company name in Leadjet section
- Reveal pro email
- Fix scroll required to view "sync" button in SalesNav
- Fix company / jobtitle mismatch

**1.22.1**

- Solve stability issue in SalesNav
- Fix Share Template feature
- Change "Update CRM" icon in SalesNav
- Possibility to skip tutorial after onboarding
- Fix Pipeline selection modal icon

**1.22.2**

- Multiple Deals carousel
- Display & Edit Copper tags
- Display warning when Contact's LinkedIn URL not present in the CRM
- Remove "homonyms" feature
- Salesloft support on SalesNav
- Faster loading time

**1.22.3**

- Auto-sync of conversations
- Display drop-down labels for Companies
- Lusha support
- Support more CRM fields type
- Give possibility to restrict fields mapping to admin only
- Fix SalesNav list export feature
- Complete refactoring of conversations
- Fix giant SVG icons
- Fix conversations sent to wrong Contacts

**1.22.4**

- Move company selector
- Invite the user to see an onboarding guide if error
- Fix tutorial popup which could not be closed
- Change default state in Leadjet popup

**1.22.5**

- Display number of Notes on "Add Notes" button
- Show if a certain field is "read-only"
- VoilaNorbert integration
- Change notification engine & style
- Fix double scroll on long popups
- Fix reject errors
- Expand layout storage size

**1.22.6**

- SalesNav Company list highlight
- Fix panel display
- Fix multiple-value fields edit
- Fix labels overflow
- Fix Copper tags removed when update
- Hubspot Companies now have owners
- Fix time offset in conversations

**1.22.7**

- Add Deals for Salesforce
- Improve SalesNav list export
- Fix Company search query
- Fix extrafield overflow

**1.22.8**

- Fix class & ID names
- Fix SalesNav Lead status update

**1.22.9**

- Support Deals labels (Pipedrive)
- Send Stripe built-in invoice via email
- Improve matching algorithm for Hubspot
- Enable Pro features during trial
- Remove template recommendations
- Fix message Templates injection on New Message
- Fix scroll on label overflow

## 1.21 (February 23, 2021)

- Deployed interactive tutorial at startup
- Prepare Deals API
- Improve highlight contact speed
- Improve "Add Note" UX

**1.21.1**

- Basic Deals support in profile pages
- Implemented dynamic selectors to prevent long-lasting impact when LinkedIn changes its display
- Display different onboarding panel when invited
- Fix enrichment issue in SalesNav

**1.21.2**

- Add notes on SalesNav
- Add "Go premium" button
- Fix SalesNav style issue
- Improve security

**1.21.3**

- Implement basic Salesloft integration (add Person and assign to Cadence)
- Edit/Delete CRM notes
- Support Template in SalesNav
- Add "Participate to roadmap" popup
- Add basic Leadjet section for company pages

**1.21.4**

- Choose pipeline before Deal creation
- Filter read-only fields
- Extract contact profile location
- Fix SalesNav smart conversations

**1.21.5**

- Add Deals in SalesNav
- Edit embedded fields directly from LinkedIn
- Fix selector in LinkedIn's new design
- Fix custom fields panel
- Fix SalesNav update button
- Fix empty conversation error

**1.21.6**

- Support embedded fields on Companies and Deals
- Improve enrichment queries with Company domain
- Display a "What's New?" button every month
- Fix need to refresh after "Add to CRM" in SalesNav
- Fix embedded fields style
- Fix "Sync" button not appearing in conversations

**1.21.7**

- Edit Lead embedded fields
- Fix <br> in Templates

**1.21.8**

- Export LinkedIn SalesNav lists (beta)
- Fix storage issue
- Remove onboarding checkbox

## 1.20 (December 8, 2020)

- Edit and delete template
- Recommended template tag
- Template colors

**1.20.1**

- Template shortcuts
- Template support in "New Message"
- Highlight leads on network connections
- Country code of the user
- Styling
- Fix reveal email display
- Fix Lead status display for Hubspot

**1.20.2**

- Add privacy policy to onboarding sequence

**1.20.3**

- Hide status dropdown for Salesforce
- Fix whitespace in templates
- Add styling to edit buttons

**1.20.4**

- Revamp user dashboard authentication

**1.20.5**

- Support for Dropdown extra field type
- Show number of trial days remaining in popup

**1.20.6**

- Add contact from conversation
- Change contact status from conversation
- Go to contact's CRM profile from conversation
- Snov.io enrichment tool support
- Send feedback at the end of trial
- Fix phone update
- Fix conversation observers
- Fixes

**1.20.7**

- Share and Copy templates
- Extra fields support in SalesNav
- Get profile image from SalesNav to Pipedrive
- Show the name of the images and attachements in convs

**1.20.8**

- Fix LinkedIn profile display causing Leadjet features to fail

**1.20.9**

- Add Salesforce lead status
- Add uninstall survey
- Display profile picture of contact owner next to his/her name
- Improve display grid
- Fix profile upper section not updated on page change

## 1.19 (October 13, 2020)

- Reveal email in SalesNav
- Add title to Salesforce notes
- Time zone offset

**1.19.1**

- Various code structure improvements

**1.19.2**

- Company select drop-down
- Toggle company select
- Handle leads

**1.19.3**

- LinkedIn new visual identity support
- New user dashboard authentication mechanism
- Improve onboarding steps
- Basic EN and FR translations

**1.19.4**

**1.19.5**

- Fix modal height

**1.19.6**

- Basic conversation smart template system

## 1.18 (September 23, 2020)

- New onboarding welcome panels
- Put settings button in extension popup
- Oauth step in LinkedIn

**1.18.1**

- Fix onboarding state machine
- Improve styling

**1.18.2**

- Fix onboarding

**1.18.3**

- Enrich company in SalesNav
- "Add to CRM" button in SalesNav
- Highlight leads in SalesNav
- Fix conversation emoji reaction

**1.18.4**

- Fix open modal company page

## 1.17 (September 10, 2020)

- Basic SalesNav support
- Highlight list contacts

**1.17.1**

- Code improvements

**1.17.2**

- Fix find profile company

**1.17.3**

- Fix fail to enrich company without LinkedIn page
- Copper dedicated wording

**1.17.4**

- Basic SalesNav contact info layout
- SalesNav labels & activity
- Fix error message in conversation

**1.17.5**

- Synchronize bubble conversations in SalesNav

## 1.16 (August 18, 2020)

- Highlight CRM contacts in "People also viewed" sidebar

**1.16.1**

- Get email from public LinkedIn coordinates
- Customize appearance for Copper users
- Edit phone and email on enter

**1.16.2**

- Fix conversation sync issue

**1.16.3**

- Fix profile picture upload
- Fix email from public LinkedIn coordinates feature

**1.16.4**

**1.16.5**

- Fix "undefined" in conversations
- Colored labels with drop-down choice

**1.16.6**

- Improved label colors + drop-down icon
- Sync CRM button style change
- Fix of strange behavior of the Sync conv button

## 1.15 (August 18, 2020)

- Use of the LinkedIn API
- Revamping of the code base (Webpack)
- Add company now based on URL, not name
- Matching based on LinkedIn profile URL, not name + company
- Fetch more contact fields and the company info from the prospect's page

**1.15.1**

- Fix wrong company being enriched
- Fix phone number causing pending "Add to CRM"
- Fix contact name being sent to the server

**1.15.2**

- Extension version is sent along API request
- Fix "Sync" not displayed in bubble conversations
- Fix freemium upgrade message display

**1.15.3**

- Remove "Enrich & Add" button
- Fix bubble conversations
- Fix fetch data for incomplete profiles

**1.15.4**

- Improve _Add to CRM_ error handling
- Fix bubble conversation "Sync"

# 1.14

- Edit email & phone from the LinkedIn profile

**1.14.2**

- Kendo support
- Limit use when no subscription exist
- _Upgrade_ popup page
- Send URL to API (to improve homonyms management)
- Fix drop-down behind Leadjet embedded section
- Fix _Reveal_ button

## 1.13

- New brand identity (purple update)

## 1.12

- Support for the new OAuth login
- Number of credits shown for all enrichment tools in the popup
- _Add to CRM_ button gives option to _Enrich and Add_
- Update CRM button
- Fix _Enrich and Add_

## 1.11

- New homonyms management system
- New mail enrichment feature

## 1.10

- Improve job title parsing on LinkedIn profiles
