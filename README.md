# lovelace-css-values
Simply a repo to house information about CSS values that can be modified by Lovelace theme files. The values that I have included come from either official Home Assistant source files (I've only dug so far) or from other themes out there.  Please help out and submit additional values or corrections via PRs.

Take a look at [known_css_refs.md](https://github.com/chipriley/lovelace-css-values/blob/master/known_css_refs.md) for the current list.

## Options for Values  

In addition to standard values for the various CSS elements (eg. sizes, font names, CSS colors, etc), there are a few other options that you can use in your themes.  

### Referencing Another Element  

You can reference another element which has already been defined either by default in Lovelace or by an entry in your theme file.  You do this by using the value `'var(--some-other-variable)'` where `some-other-variable` is the name of the defined element.  

Example:  
```yaml
yourtheme:  
  background-color: 'black'                                   # Sets the background color to black  
  .  
  .  
  .  
  paper-dialog-background-color: 'var(--background-color)'    # Sets the dialog background color to the same as above  
```
### Additional CSS Functions Within Elements

As with CSS in a style sheet or from a script, you can use CSS functions in the theme values.

Example:  
```yaml
yourtheme:
  paper-slider-container-color: 'linear-gradient(var(--primary-background-color), var(--secondary-background-color)) no-repeat'
```
### Other Places to Use These Values

If you are using custom cards or modules, like [lovelace-card-modder](https://github.com/thomasloven/lovelace-card-modder) from @thomasloven, which allow for style definitions from the card definition, you can use these elements by prepending a `--` just like in the `'var(--some-other-variable)'` within the `style:` block.  

Example:
```yaml
  style:
    --paper-toggle-button-checked-button-color: '#FFCC66'
```
This would style the button of the toggle in your Lovelace element separately from the overall theme.  
