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

## Fonts
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`primary-font-family:`|`Roboto, sans serif`| |Primary font family to be used.  
|`paper-font-common-base\_-\_font-family:`|`Roboto, sans serif`| |May use `'var(--primary-font-family)'` to reference another variable already set.
|`paper-font-common-code\_-\_font-family:`|`Roboto, sans serif`| | 
|`paper-font-body1\_-\_font-family:`|`Roboto, sans serif`| | 
|`paper-font-subhead\_-\_font-family:`|`Roboto, sans serif`| | 
|`paper-font-headline\_-\_font-family:`|`Roboto, sans serif`| | 
|`paper-font-caption\_-\_font-family:`|`Roboto, sans serif`| | 
|`paper-font-title\_-\_font-family:`|`Roboto, sans serif`| |
|`paper-font-headline\_-\_font-weight:`|`Roboto, sans serif`| |
|`app-toolbar-font-size:`|`Roboto, sans serif`| |
|`app-drawer-font-size:`|`Roboto, sans serif`| |

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
|`primary-background-color:`| | | 
|`secondary-background-color:`| | |
|`border-color:`| | | 
|`divider-color:`| | |
|`primary-color:`| | |
|`dark-primary-color:`| | | 
|`light-primary-color:`| | |
|`paper-tabs-selection-bar-color:`| | |
|`table-row-background-color:`| | | 
|`table-row-alternative-background-color:`| | | 

## Header
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------

## Left Menu
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`paper-listbox-color:`|CSS color value, ie. `red`| |Color of the overall text of the left sidebar menu.
|`paper-listbox-background-color:`|CSS color value, ie. `red`| |Color of the background of the left sidebar menu.
|`paper-listbox\_-\_font-family:`|Roboto, sans serif | |Font used for the left sidebar menu. 
|`sidebar-icon-color:`|CSS color value, ie. `red`| |Color for the icons in the left sidebar menu.
|`sidebar-selected-icon-color:`|CSS color value, ie. `red`| |Color for the currently selected icon in the left sidebar menu. 
|`sidebar-selected-text-color:`|CSS color value, ie. `red`| |Color for the text of the currently selected menu item in the left sidebar menu.
|`sidebar-text_-_background:`|CSS color value, ie. `red`| |

## Card Elements
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`paper-card-header-color:`| | | 
|`paper-card-background-color:`| | | 
|`paper-dialog-background-color:`| | | 
|`paper-item-icon-color:`| | | 
|`paper-item-icon-active-color:`| | | 
|`paper-item-icon\_-\_color:`| | | 
|`paper-item-selected\_-\_background-color:`| | |
|`paper-slider-knob-color:`| | | 
|`paper-slider-knob-start-color:`| | | 
|`paper-slider-pin-color:`| | | 
|`paper-slider-active-color:`| | | 
|`paper-slider-container-color:`| | | 
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
|`shadow-elevation-2dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-3dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-4dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-6dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-8dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-12dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-16dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-elevation-24dp_-_box-shadow:`|`"0px 0px 0px 0px black)"`| |
|`shadow-transition_-_transition:`|`box-shadow 0.28s cubic-bezier(0.4, 0, 0.2, 1)`| |

## Uncategorized - Need to Update
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`label-badge-border-color:`| | | 
|`paper-grey-50:`| | | 
|`paper-grey-200:`| | |  
|`paper-tabs-selection-bar-color:`| | | 
|`label-badge-red:`| | | 
|`label-badge-text-color:`| | | 
|`label-badge-background-color:`| | | 
|`google-red-500:`| | | 
|`google-green-500:`| | | 
|`mdc-theme-primary:`| |0.88|Related to the new mwc-card/buttons somehow.  

### Custom Ideas
| Element | Example Value | HA Version | Description
| ---- | ---- | ---- | -----------
|`base-hue:`|`"220"`| |
|`base-sat:`|`"5%"`| |
|`huesat:`|`"var(--base-hue), var(--base-sat),"`| |Define your own variables in your theme and then use them for actual elements like `primary-color: "hsl(var(--huesat) 36%)"` like in [kysa](https://community.home-assistant.io/u/ksya)'s [Grey Night theme](https://github.com/maartenpaauw/home-assistant-community-themes/blob/master/night.yaml).