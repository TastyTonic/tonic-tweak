# CSS UI-Tweak for [Aevann1/rDrama](https://github.com/Aevann1/rDrama)

## How it's used
Add following line to your "Custom CSS"-setting:
```css
@import url('https://cdn.jsdelivr.net/gh/TastyTonic/tonic-tweak@main/tweak.css') screen and (min-width: 720px);
`` `

## What it does

### UI-Changes

#### Properly centers the search
The search is no longer off-center.
![alt text](https://github.com/TastyTonic/tonic-tweak/blob/main/screenshots/search.png?raw=true)

#### Videos are full width
Videos are centered with a black background.
![alt text](https://github.com/TastyTonic/tonic-tweak/blob/main/screenshots/video.png?raw=true)

### Moves message from above search to bottom left corner
Hovering over Marsey will reveal the message.
![alt text](https://github.com/TastyTonic/tonic-tweak/blob/main/screenshots/bottom%20left%20corner.png?raw=true)
![alt text](https://github.com/TastyTonic/tonic-tweak/blob/main/screenshots/bottom%20left%20corner%20hover.png?raw=true)

#### Makes sidebar hide in the bottom right corner and pop up on hover
More like bottombar am i right?
![alt text](https://github.com/TastyTonic/tonic-tweak/blob/main/screenshots/bottom%20right%20corner.png?raw=true)
![alt text](https://github.com/TastyTonic/tonic-tweak/blob/main/screenshots/bottom%20right%20corner%20hover.png?raw=true)

#### Removes Banner
It's gone.

### Tweaks
* Nav and content use flexbox instead of `position: fixed`
* Hides mobile-only elements in nav
* User dropdown has more space to the right
