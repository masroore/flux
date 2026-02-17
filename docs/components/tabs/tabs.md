# Tabs

> **Category:** tabs
> **Component Name:** `flux:tabs`

## Overview

Container for tab navigation groups.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `size` | `mixed` | `null` | Size variant of the component |
| `variant` | `mixed` | `null` | Visual style variant of the component |
| `scrollable` | `boolean` | `false` | Configuration for scrollable |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `variant`

## Default Slot

This component accepts a default slot for its main content.

## Usage

### Basic Example

```blade
<flux:tabs
/>
```

### Advanced Example

```blade
<flux:tabs
    size="value"
    variant="value"
    scrollable="value"
>
    Advanced content
</flux:tabs>
```

### With Livewire

```blade
<flux:tabs
    wire:model="property"
/>
```

## Accessibility

- Component follows standard HTML accessibility practices
- Keyboard navigation supported where applicable

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Border radius** - Rounded corners for modern appearance

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Technical Notes

- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
