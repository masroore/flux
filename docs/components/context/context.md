# Context

> **Category:** context
> **Component Name:** `flux:context`

## Overview

Context menu that appears on right-click or trigger.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `position` | `string` | `'bottom end'` | Position of the floating element |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `wire:model`

## Usage

### Basic Example

```blade
<flux:context
/>
```

### With Livewire

```blade
<flux:context
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


## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
