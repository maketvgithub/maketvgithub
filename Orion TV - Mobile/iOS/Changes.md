# Changes

## 3.0.0(11)

### Added
- Settings > Playback settings (case 703, 716) - Play locked in landscape mode
- Home Error screen (case 733) - displayed when session expired or other errors
- Confirm use cellular to watch live channel in Details
- Advertising Identifier in About screen for testing and will be used in the next test with production Google Ad units
- Disconnect social account
- Recent searches fallback
- Remove reminders fallback

### Changed
- Local language localization
- EPG - scroll to current time (LIVE) or scroll to top if date is in the past
- Play sound animation or keep playing stream when you back from inactive state - tap a Home button on-screen or home bar on your screen then back to app

### Fixed
- Pick a date to show EPG (case 712)
- Hide sound control after few seconds (case 717) 
- Removed structural navigation at Sign in screen that was already set, it should animate just once to Home screen (case 679)
- Sign in/up with Apple (case 682, 684) - implementation separation - note if you already using Apple ID with this app and you want to sign up, remove your Apple ID that was used in system settings, explained in Manage App Using Apple ID
- Removed lorem ipsum on confirmation dialog when channel is not available in EPG, added channel name as title

### Explain
- Username (case 677) - if you type dejan.rogulja it will add suffix `@orion.rs`, except you already typed `@`
- My reminders (case 697) - not reproduced
- Sign in with Apple - [Manage App Using Apple ID](https://support.apple.com/en-us/HT210426)
- IDFA - Add Ad Identifier - [Set up a test device](https://support.google.com/admob/answer/9691433#example) 

## 3.0.0(10)

### Added
- Google Ads in Home Banner
- Search EPG (case 688) - search shows for subscribed channels
- `LIVE` flag - currently live on program (case 711)
- Localization
- Channel Locked screen - link to buy premium package (case 734)
- Colour placeholder when image (logo) is missing 
- My Channels - title of 2 text lines to display full channel name
- My Devices - messages on failure to unlink device
- Search on return fallback
- Loader - displayed while searching shows (case 732)
- Copy Cloud Messaging Token
- Google Banner Ad when playing radio
- Pause control for currently playing radio channel at Radio channels screen (case 707)
- Play/Pause control in Player when playing radio
- Change radio channels on swipe up/down

### Changed
- Agree with terms and conditions on create social account (case 681)
- Share link available on the App Store (case 723)
- Auto rotate on play, lock player in landscape orientation and resize content layer (case 703)
- Checkmark for current device is not shown for selection at My Devices to unlink
- If channel category is not contained in all channels remove from selection (case 709)
- Sound visualization to animation - removed use of mic

### Fixed
- Onboarding steps (case 673)
- Sign out (case 693) - on sign out show Login screen
- Confirmation message on change password - removed lorem ipsum (case 695)
- Device activation with code or scan QR code (case 700, case 701)
- My devices (case 702)
- Playback - toggle `WiFi required to play video` is off
    - show play buttons at Home screen (case 703)
    - show images at My Channels (case 699, case 713)
- EPG details - live/catchup (case 712, case 737) 
    - show play button if current
    - show remind button if Show starts anytime in the future from now
    - show catchup if Show ended and became past event
- Player - on change orientation (case 715, case 716)
- Time controls in Player (case 719)
- Tap on `Contact us` - don't show mail composer if services are not available and show message where to set up an email account (case 706)
- Now Playing controls
- Google Cast - on stop casting keep playing on device
- Mark with reverse icon catchup enabled video channels

### Explain & Suggest
- Play buttons have bigger touchable area around the icon (case 685)
- Display (case 685) - adjusting in Settings > Display & Brightness > Text Size
- Accessibility (case 685) - [Apple HIG /accessibility](https://developer.apple.com/design/human-interface-guidelines/foundations/accessibility)
    - Larger Accessibility Text Sizes in Settings > Accessibility > Display & Text Size > Larger Text
    - adjusting layout at large font sizes
    - increase the size of meaningful interface icons as font size increases
- Home Banner is now visible regardless of remote configuration for testing purposes (case 686)
- Touch and hold to show up volume control (case 717)
- Link to buy premium package (case 734) - I'm not sure is it legal(Apple have In-App Purchase) and depends on external services but if Apple agree 
    - [reader??? apps with a link](https://developer.apple.com/support/reader-apps/) 
    - [StoreKit External Purchase](https://developer.apple.com/support/storekit-external-entitlement/)
    - [store rules](https://support.stripe.com/questions/changes-to-mobile-app-store-rules#apple-updates)
- VOD tab is hidden, VOD onboard excluded - Service on iOS is not available (case 685, case 673)
- [Now Playing on Apple Watch](https://support.apple.com/en-gb/guide/watch/apd4ea5db227/watchos)




