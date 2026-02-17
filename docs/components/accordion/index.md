# Accordion › Index

> **Category:** accordion
> **Component Name:** `flux:accordion.index`

## Overview

Collapsible content sections that can be expanded or collapsed.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `variant` | `mixed` | `null` | Visual style variant of the component |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:accordion.index
>
    Content here
</flux:accordion.index>
```

### With Livewire

```blade
<flux:accordion.index
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:


### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Accordion › Content](./content.md)
- [Accordion › Heading](./heading.md)
- [Accordion › Icon](./icon.md)
- [Accordion › Item](./item.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
