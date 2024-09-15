# Stream Deck Plugins

## Plugin master list

Here you will find a list of various plugins that I have produced. You will be able to use the sidebar to select the plugin you want more information about. I hope this helps.

## Compatibility Overview

I strive to make my plugins functional on multiple operating systems, along with multiple device types. However, I am unable to check every single device. Thus, I allow users to submit claims to state whether or not plugins are working.

??? question "Support ranking"
    Support will be ranked in the following way:

    1. :fontawesome-solid-circle-check: - Fully working, tested by developer
    1. :fontawesome-regular-circle-check: - Claim: Fully working, tested by community
    1. :fontawesome-solid-circle-question: - Partially working, tested by developer
    1. :fontawesome-regular-circle-question: - Claim: Partially working, tested by community
    1. :fontawesome-solid-circle-xmark: - Not working at all, tested by developer
    1. :fontawesome-regular-circle-xmark: - Claim: Not working at all, tested by community
    1. :fontawesome-solid-circle-exclamation: - Will not work on specific device model (due to limitations on the device)
    1. :fontawesome-solid-circle-radiation: - Untested

    This will be placed in information for individual plugin functionality, allowing you to see how this functionality is compatible on a per-action basis. Notes may also be provided dependent on the ranking.

??? note "Support checks"
    We check plugins under functionality types rather than against specific devices. Here are the functionality types available:

    - Dial
    - Key
    - Touch
    - Panel (think the InfoBar on the Stream Deck Neo)

??? info "Information regarding profiles"
    When specific profiles are brought into play for plugins, these will then have compatibility checks against specific Stream Deck hardware. These will be tested as follows.

    - 15 (both Mk1 and Mk2)
    - XL
    - Mini
    - Plus
    - Pedal
    - Neo
    - Studio

    ??? warning "A warning regarding Stream Deck Mobile"
        Due to the new Stream Deck mobile setup, it is difficult to test this, as there are now large fluctuations in the sizing available. The reason for this is the new app allows you to configure your board to have anywhere from one to eight rows, and the same applies to columns (and these settings are completely independent of each other).

        As a compromise, we will list the minimum amount of rows and columns required for the profile to be considered usable, or we will state if it just outright will not work 

## Unsupported hardware

I am also aware of devices that utilise Stream Deck plugins but do not directly interface with the Elgato Stream Deck software. I will not be testing these devices, and users who submit compatibility check information about these devices will have their submissions refused.

!!! danger
    These devices that don't interface directly with the Stream Deck software are using reverse-engineering and other hacks to gain functionality. As a result, they often have quirks that cause issues within plugins, and these quirks often have no rhyme or reason to them. Consequently, support will not be provided if there are issues (it is impossible for us to provide support for these unofficial devices). You would have to liaise with other users outside of the server.

!!! failure "Notice regarding adding support"
    Submissions to support these devices that interface with Stream Deck plugins while not using the Elgato software will not be considered. I will only support official devices.
    
    If a plugin is open source, it will be AGPL licenced. This means you will be allowed to modify the code to make it work for your own devices, however you must also licence it under that same AGPL licence (and as such comply with the terms), and you must use a different plugin name (as this is a trademark issue, and it must be something that an average individual will not reasonably confuse with the original product name).
    
    Anyone using your version of this plugin may not access support from my support portals, so please ensure you have your own support available. You will not receive support from my support portals in terms of being able to modify the code to function with these unofficial devices.