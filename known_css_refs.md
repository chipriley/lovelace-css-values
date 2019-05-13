# Known Lovelace CSS Elements
The following are known CSS values that can be modified via a theme.yaml file or through various custom cards/components to customize Lovelace.  I have attempted to break them out into sections based on what they modify but please submit changes if you think there could be a better way to organize it.

Sources:

[ha-card.ts](https://github.com/home-assistant/home-assistant-polymer/blob/master/src/components/ha-card.ts)  
[ha-style.ts](https://github.com/home-assistant/home-assistant-polymer/blob/master/src/resources/ha-style.ts)  
[style.ts](https://github.com/home-assistant/home-assistant-polymer/blob/master/src/resources/styles.ts)  
[Various Themes from Home Assistant Community Themes](https://github.com/maartenpaauw/home-assistant-community-themes/)  


## Card-Specific Modifications
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`ha-card-border-radius:`|`20px`|0.88.1|Rounded corners on cards. NOTE: may not work with custom cards.
|`ha-card-background:`|`'grey'`|0.88.1|Defines the background for cards.
|`ha-card-box-shadow:`|`1px 3px 4px black`|0.89|Shadows on cards. Same as `shadow-elevation-2dp_-_box-shadow:`

## Fonts
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`primary-font-family:`|`Roboto, sans serif`| |Primary font family to be used.  
|Each of the following all have the following elements that can be appended: `_-_font-family`, `_-_webkit-font-smoothing`, `_-_white-space`, `_-_overflow`, `_-_text-overflow`, `_-_font-size`, `_-_font-weight`, `_-_letter-spacing`, `_-_line-height`, `_-_text-transform`
|`paper-font-common-base...`| | |
|`paper-font-common-code...`| | |
|`paper-font-common-code2...`| | |
|`paper-font-common-nowrap...`| | | 
|`paper-font-body1...`| | | 
|`paper-font-body2...`| | |
|`paper-font-code1...`| | |
|`paper-font-code2...`| | |
|`paper-font-button...`| | |
|`paper-font-menu...`| | |
|`paper-font-subhead...`| | | 
|`paper-font-headline...`| |<0.89| No longer available in 0.89
|`paper-font-caption...`| | |
|`paper-font-title...`| | |
|`paper-font-headline...`| | |
|`paper-font-display1...`| | |
|`paper-font-display2...`| | |
|`paper-font-display3...`| | |
|`paper-font-display4...`| | |
|`app-toolbar-font-size:`|`14px`| |
|`app-drawer-font-size:`|`14px`| |

## Colors
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`primary-text-color:`|`'#FFFFFF'`| | CSS color value for the color to be used.
|`text-primary-color:`| | |
|`secondary-text-color:`| | | 
|`disabled-text-color:`| | |
|`accent-color:`| | | 
|`accent-medium-color:`| | | 
|`background-color:`| | | 
|`background-color-2:`| | | 
|`background-card-color:`| | | 
|`secondary-background-color:`| |CSS color value, ie. `red`|secondary color that can be used by cards, e.g. custom updater card uses it to color every second row
|`border-color:`| | | 
|`divider-color:`| | |
|`primary-color:`| | |
|`dark-primary-color:`| | | 
|`light-primary-color:`|CSS color value, ie. `red`| |color of your Avatars letter background
|`paper-tabs-selection-bar-color:`| | |
|`table-row-background-color:`| | | 
|`table-row-alternative-background-color:`| | | 
|`alarm-color-disarmed:`| | | 
|`alarm-color-pending:`| | | 
|`alarm-color-triggered:`| | | 
|`alarm-color-armed:`| | | 
|`alarm-color-autoarm:`| | |
|`alarm-state-color:`| | |  
|`state-icon-unavailable-color:`| | |
|`dark-primary-opacity:`| | |
|`dark-secondary-opacity:`| | | 
|`dark-disabled-opacity:`| | |
|`paper-listbox-color:`|CSS color value, ie. `red`| |Color of the overall text of the popup menues (such as "3 dot menu" and background of hovered icon (in a lighter shade of the same color)

## Header
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------

## Left Menu
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`paper-listbox-background-color:`|CSS color value, ie. `red`| |Color of the background of the left sidebar menu.
|`paper-listbox_-_font-family:`|Roboto, sans serif | |Font used for the left sidebar menu. 
|`sidebar-icon-color:`|CSS color value, ie. `red`| |Color for the icons in the left sidebar menu.
|`sidebar-selected-icon-color:`|CSS color value, ie. `red`| |Color for the currently selected icon in the left sidebar menu. 
|`sidebar-selected-text-color:`|CSS color value, ie. `red`| |Color for the text of the currently selected menu item in the left sidebar menu.
|`sidebar-text_-_background:`|CSS color value, ie. `red`| |
|`primary-background-color:`| | | color of the sidebar headers background (space behind the text "Home Assistant" and your Avatar)

## Card Elements
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`paper-card-header-color:`| | | 
|`paper-card-background-color:`| white| | background of the cards
|`paper-dialog-background-color:`| | | 
|`paper-item-icon-color:`| | | 
|`paper-item-icon-active-color:`| | | 
|`paper-item-icon_-_color:`| | | 
|`paper-item-selected_-_background-color:`| | |
|`paper-menu-button-dropdown-background:`| | | 
|`paper-slider-height:`| | |Height of the slider.
|`paper-slider-container-color:`| | |Color of the part of the slider which is not active.
|`paper-slider-knob-color:`| | | 
|`paper-slider-knob-start-color:`| | | 
|`paper-slider-pin-color:`| | | 
|`paper-slider-active-color:`| | |Color of the part of the slider which is active.
|`paper-slider-secondary-color:`| | | 
|`paper-slider-disabled-active-color:`| | | 
|`paper-toggle-button-checked-button-color:`|CSS color value, ie. `red`| |Color of the button for an on/off toggle when turned on. 
|`paper-toggle-button-checked-bar-color:`|CSS color value, ie. `red`| |Color of the sliding area for an on/off toggle when turned on.
|`paper-toggle-button-checked-ink-color:`| | | 
|`paper-toggle-button-unchecked-button-color:`|CSS color value, ie. `red`| |Color of the button for an on/off toggle when turned off. 
|`paper-toggle-button-unchecked-bar-color:`|CSS color value, ie. `red`| |Color of the sliding area for an on/off toggle when turned off. 
|`paper-toggle-button-unchecked-ink-color:`| | | 

## Shadows
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`lumo-box-shadow-s:`| | |
|`lumo-box-shadow-m:`| | |
|`lumo-box-shadow-l:`| | |
|`lumo-box-shadow-xl:`| | |
|`paper-input-container-shared-input-style_-_box-shadow:`|`none`| |
|`paper-material_-_display:`| | |
|`paper-material_-_position:`| | |
|`paper-material-elevation-1_-_box-shadow:`| | |
|`paper-material-elevation-2_-_box-shadow:`| | |
|`paper-material-elevation-3_-_box-shadow:`| | |
|`paper-material-elevation-4_-_box-shadow:`| | |
|`paper-material-elevation-5_-_box-shadow:`| | | 
|`shadow-elevation-2dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-3dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-4dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-6dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-8dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-12dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-16dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-elevation-24dp_-_box-shadow:`|`"0px 0px 0px 0px black"`| |
|`shadow-transition_-_transition:`|`box-shadow 0.28s cubic-bezier(0.4, 0, 0.2, 1)`| |

## Uncategorized - Need to Update
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`label-badge-border-color:`| | | 
|`paper-grey-50:`| | | 
|`paper-grey-200:`| | | 
|`paper-progress-height:`| | |
|`paper-tabs-selection-bar-color:`| | |
|`ha-label-badge-color:`| | |  
|`label-badge-red:`| | | 
|`label-badge-text-color:`| | | 
|`label-badge-background-color:`| | | 
|`google-red-500:`| | | 
|`google-green-500:`| | | 
|`mdc-theme-primary:`| |0.88|Related to the new mwc-card/buttons somehow.  
|`base-unit:`| | | 

### Custom Ideas
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`base-hue:`|`"220"`| |
|`base-sat:`|`"5%"`| |
|`huesat:`|`"var(--base-hue), var(--base-sat),"`| |Define your own variables in your theme and then use them for actual elements like `primary-color: "hsl(var(--huesat) 36%)"` like in [kysa](https://community.home-assistant.io/u/ksya)'s [Grey Night theme](https://github.com/maartenpaauw/home-assistant-community-themes/blob/master/night.yaml).
