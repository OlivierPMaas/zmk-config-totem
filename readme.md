
# My ZMK config for the totem split keyboard

[Here](https://github.com/GEIGEIGEIST/totem) you can find the hardware files and build guide.

TOTEM is a 38-key column-staggered split keyboard.
My version is the Bluetooth version, assembled and provided by http://keep.supply.

Additionally, I am using a third SEEED XIAO BLE as a dongle.

![TOTEM layout](/docs/images/TOTEM_layout.svg)
![my layout](/docs/images/my_keymap.svg)

## General considerations

I took a lot of inspiration from existing configurations like [Miryoku](https://github.com/manna-harbour/miryoku_zmk), [sunaku glove80](https://sunaku.github.io/moergo-glove80-keyboard.html) and many others.

I tried to stick to Miryoku's opposite site layer feature to reduce complications.

But I was intrigued by auto-shift, rather than pressing shift for caps.
Generally, this might lead to a lower type speed, but I think it adds a little bit more comfort.

So far, I have not found a nice configuration to use auto-shift in a nice way with home row mods, which is still on my to-do list.

## Sym layers

I decided to have two separate symbol layers.
One for typing and one for coding. In my opinion, the two vary heavily in the most used keys, and therefore I thought it makes sense to utilize the home row differently.

### Programming specific

Furthermore, I wanted to make developing and reaching symbols for development easier and more intuitive.
I wanted to create a more rolling motion from outward to inward, also like sunaku explains, but due to the limited space, I can not match all his constraints.

> **Note** I am still exploring the coding part, and this might be subject to be changed.

## To-do's

- home row mods, or at least easier accessible modifiers, maybe combos
- improvement to shortcut layer, and rethinking how to access it
