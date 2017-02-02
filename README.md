[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Abe90/paper-avatar)

# \<paper-avatar\>

User avatar in material style

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

## Install

```
bower i Abe90/paper-avatar --save
```
