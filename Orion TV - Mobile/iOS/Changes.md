# Changes

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
- Accessibility (case 685) - [Apple HIG /accessibility](https://developer.apple.com/design/human-interface-guidelines/foundations/accessibility)
    - for example, turn on Larger Accessibility Text Sizes in Settings > Accessibility > Display & Text Size > Larger Text
    - adjusting layout at large font sizes
    - increase the size of meaningful interface icons as font size increases
- Home Banner is now visible regardless of remote configuration for testing purposes (case 686)
- Touch and hold to show up volume control (case 717)
- Link to buy premium package (case 734) - I'm not sure is it legal(Apple have In-App Purchase) and depends on external services but if Apple 
    - [reader” apps with a link](https://developer.apple.com/support/reader-apps/) 
    - [StoreKit External Purchase](https://developer.apple.com/support/storekit-external-entitlement/)
    - [store rules](https://support.stripe.com/questions/changes-to-mobile-app-store-rules#apple-updates)
- VOD tab is hidden, VOD onboard excluded - Service on iOS is not available (case 685, case 673)
- [Now Playing on Apple Watch](https://support.apple.com/en-gb/guide/watch/apd4ea5db227/watchos)




