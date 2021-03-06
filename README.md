[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Abe90/paper-avatar)

# \<paper-avatar\>

This component is made for generate a different random avatar for every member.

## Example

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-avatar.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<style is="custom-style">
	paper-avatar.red {
		--paper-avatar-color: red;
	}
	paper-avatar.large {
		--paper-avatar-width: 60px;
	}
</style>
<paper-avatar label="Abe90"></paper-avatar>
<paper-avatar label="Abe90" src="https://avatars.githubusercontent.com/u/4205629"></paper-avatar>
<paper-avatar label="Abe90" two-chars></paper-avatar>
<paper-avatar label="Abe90" class="red"></paper-avatar>
<paper-avatar label="Abe90" class="large"></paper-avatar>
<paper-avatar label="Abe90" jdenticon></paper-avatar>
```


## Background color
The background color is automatically generated by hashing the label and selecting from an array of colors.

You can setting up this array passing the values in `colors` parameter.

### Default colors

![Default colors](/demo/colors-min.png?raw=true)

## Two chars
The `two-chars` parameter is used to show two chars in the generated avatar.

If the `label` is composed of a single word, you'll see the first two letters of that word; the first letter will always appear capitalized.

If instead the `label` is composed of two words, will be displayed the first letter of every word.

### Example
- first: Fi
- First: Fi
- first second: Fs
- First Second: FS



## Customization
There is the opportunity to change some parameters to customize the generated avatar.

The css parameters `--paper-avatar-color` and `--paper-avatar-width` correspond to the background color and the size (width and height) of the avatar.



## Jdenticon (jdenticon.com)
Jdenticon is a free Javascript library for generating highly recognizable identicons.

You can use this library adding `jdenticon` parameter.
In this case the text will be replaced with white jdenticon image.

More information at [jdenticon.com](https://www.jdenticon.com/)



## Install

```
bower install --save Abe90/paper-avatar
```
