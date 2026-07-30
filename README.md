# bem-css-example
A landing page example develop with CSS BEM.

# BEM

## Block

### What's it?

An autonomous entity/component who is meanfull to itself.

> Ex: header, footer, checkbox.

## Element

### What's it?

An Block child-element that is a piece of a block.

> Ex: menu item, list item, checkbox label.

## Modifier

### What's it?

A Block or Element variant who modifies it appearance, change properities or attribute a state.

> Ex: disabled, checked, full-width, dark, light.

# Conventions

## BLOCK

Traditionally it adopts a common name to identifies a block/component.

**Ex: `.menu`**

## ELEMENT

Traditionally it adopts the block name, two underlines and the element name.

**Ex: `.menu__item`, `.menu__link`**

## MODIFIER

Traditionally it adopts the block name, two hyphrnd and the variant/variation name.

**Ex: `.menu--dark`, `.menu__item--disabled`**