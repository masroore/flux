# Slider › Index

> **Category:** slider
> **Component Name:** `flux:slider.index`

## Overview

Range slider for selecting numeric values.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `range` | `boolean` | `false` | Enable range selection mode |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:slider.index
/>
```

### With Livewire

```blade
<flux:slider.index
    wire:model="property"
/>
```

## Accessibility

- Comprehensive ARIA attributes for accessibility
- Keyboard navigation support with proper focus management
- Disabled states are properly communicated to assistive technologies
- Visual and functional disabled states
- Focus visible indicators for keyboard navigation

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Border radius** - Rounded corners for modern appearance
- **Shadows** - Depth and elevation effects

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Slider › Tick](./tick.md)

## Technical Notes

- Uses the `@blaze` directive for enhanced component features
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
