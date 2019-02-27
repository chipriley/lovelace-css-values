# Known Lovelace CSS Elements
The following are known CSS values that can be modified via a theme.yaml file to customize Lovelace.  I have attempted to break them out into sections based on what they modify but please submit changes if you think there could be a better way to organize it.

Sources:

[ha-card.ts](https://github.com/home-assistant/home-assistant-polymer/blob/master/src/components/ha-card.ts)  
[ha-style.ts](https://github.com/home-assistant/home-assistant-polymer/blob/master/src/resources/ha-style.ts)  
[style.ts](https://github.com/home-assistant/home-assistant-polymer/blob/master/src/resources/styles.ts)  

## Card-Specific Modifications
| Element | Example Value | Description
| ---- | ---- | -----------
|`ha-card-border-radius:`|`20px`|Rounded corners on cards. NOTE: may not work with custom cards.

## Fonts
| Element | Example Value | Description
| ---- | ---- | -----------
|`primary-font-family:`|`Roboto, san serif`|Primary font family to be used.  
|`paper-font-common-base\_-\_font-family:`|`Roboto, san serif`|May use `'var(--primary-font-family)'` to reference another variable already set.
|`paper-font-common-code\_-\_font-family:`|`Roboto, san serif`|
|`paper-font-body1\_-\_font-family:`|`Roboto, san serif`|
|`paper-font-subhead\_-\_font-family:`|`Roboto, san serif`|
|`paper-font-headline\_-\_font-family:`|`Roboto, san serif`|
|`paper-font-caption\_-\_font-family:`|`Roboto, san serif`|
|`paper-font-title\_-\_font-family:`|`Roboto, san serif`|
|`paper-font-headline\_-\_font-weight:`|`Roboto, san serif`|
|`app-toolbar-font-size:`|`Roboto, san serif`|
|`app-drawer-font-size:`|`Roboto, san serif`|
## Colors
| Element | Example Value | Description
| ---- | ---- | -----------
|`primary-text-color:`|`'#FFFFFF'`|CSS color value for the color to be used.
|`secondary-text-color:`| |
|`accent-color:`| |
|`accent-medium-color:`| |
|`background-color:`| |
|`background-color-2:`| |
|`background-card-color:`| |
|`border-color:`| |
|`primary-background-color:`| |
|`secondary-background-color:`| |
## Header
| Element | Example Value | Description
| ---- | ---- | -----------
|`primary-color:`| |
|`text-primary-color:`| |
|`paper-tabs-selection-bar-color:`| |
## Left Menu
| Element | Example Value | Description
| ---- | ---- | -----------
|`paper-listbox-color:`| |
|`paper-listbox-background-color:`| |
|`paper-listbox\_-\_font-family:`| |
|`sidebar-icon-color:`| |
|`sidebar-selected-icon-color:`| |
|`sidebar-selected-text-color:`| |
## Uncategorized - Need to Update
| Element | Example Value | Description
| ---- | ---- | -----------
|`dark-primary-color:`| |
|`light-primary-color:`| |
|`disabled-text-color:`| |
|`label-badge-border-color:`| |
|`divider-color:`| |
|`table-row-background-color:`| |
|`table-row-alternative-background-color:`| |
|`paper-grey-50:`| |
|`paper-grey-200:`| |
|`paper-card-header-color:`| |
|`paper-card-background-color:`| |
|`paper-dialog-background-color:`| |
|`paper-item-icon-color:`| |
|`paper-item-icon-active-color:`| |
|`paper-item-icon\_-\_color:`| |
|`paper-item-selected\_-\_background-color:`| |
|`paper-tabs-selection-bar-color:`| |
|`label-badge-red:`| |
|`label-badge-text-color:`| |
|`label-badge-background-color:`| |
|`paper-toggle-button-checked-button-color:`| |
|`paper-toggle-button-checked-bar-color:`| |
|`paper-toggle-button-checked-ink-color:`| |
|`paper-toggle-button-unchecked-button-color:`| |
|`paper-toggle-button-unchecked-bar-color:`| |
|`paper-toggle-button-unchecked-ink-color:`| |
|`paper-slider-knob-color:`| |
|`paper-slider-knob-start-color:`| |
|`paper-slider-pin-color:`| |
|`paper-slider-active-color:`| |
|`paper-slider-container-color:`| |
|`paper-slider-secondary-color:`| |
|`paper-slider-disabled-active-color:`| |
|`google-red-500:`| |
|`google-green-500:`| |
|`mdc-theme-primary:`| |
|`paper-dialog-buttons\_-\_color:`| |
