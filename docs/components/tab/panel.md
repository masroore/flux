# Tab › Panel

> **Category:** tab
> **Component Name:** `flux:tab.panel`

## Overview

Tab navigation component for organizing content.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `selected` | `boolean` | `false` | Configuration for selected |
| `name` | `mixed` | `null` | Form field name attribute |

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:tab.panel
    name="field_name"
/>
```

### With Livewire

```blade
<flux:tab.panel
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

- [Tab › Index](./index.md)
- [Tab › Group](./group.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features

---

*Generated on February 17, 2026*
