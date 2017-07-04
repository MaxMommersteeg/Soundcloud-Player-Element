[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/maxmommersteeg/soundcloud-player-element)

# \<soundcloud-player\>

Stream tracks from Soundcloud with this element.

![Simple soundcloud-player](http://imgur.com/Q8ZCLFZ.png "Simple soundcloud-player")

## Usage
Reference the element in the `head` section for your HTML-document:

```html
  <head>
    <link rel="import" href="../Soundcloud-Player-Element/soundcloud-player.html">
  </head>
```

Then render the element using following code:

```html

<soundcloud-player client-id="YOUR_SOUNDCLOUD_CLIENT_ID" track-url="https://soundcloud.com/trackurl"></soundcloud-player>

```

## Installation

Use bower to install the `soundcloud-player` element.

```bower
bower install --save MaxMommersteeg/Soundcloud-Player-Element
```

## Notes
A Soundcloud SDK ClientId is required in order to use this element.

Make sure you follow the Soundcloud guidelines as stated on the [Soundcloud developer website](https://developers.soundcloud.com/docs/api/guide#playing).
- Credit the uploader as the creator of the sound
- Credit SoundCloud as the source by including one of the logos found here
- Link to the SoundCloud URL containing the work
- If the sound is private link to the profile of the creator

You can register your app in order to get a Soundcloud ClientId [here](https://soundcloud.com/you/apps).
