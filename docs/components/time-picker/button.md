# Time picker › Button

> **Category:** time-picker
> **Component Name:** `flux:time-picker.button`

## Overview

Time selection input component.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `invalid` | `boolean` | `false` | Whether the component is in an invalid state |
| `size` | `mixed` | `null` | Size variant of the component |

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:time-picker.button
    placeholder="Enter value"
/>
```

### Advanced Example

```blade
<flux:time-picker.button
    placeholder="value"
    clearable="value"
    invalid="value"
    size="value"
>
    Advanced content
</flux:time-picker.button>
```

### With Livewire

```blade
<flux:time-picker.button
    wire:model="property"
/>
```

## Accessibility

- ARIA labels are properly set for screen readers
- Comprehensive ARIA attributes for accessibility
- Keyboard navigation support with proper focus management
- Disabled states are properly communicated to assistive technologies
- Visual and functional disabled states

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Border radius** - Rounded corners for modern appearance
- **Shadows** - Depth and elevation effects
- **Disabled states** - Visual indication when disabled

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Time picker › Index](./index.md)
- [Time picker › Input](./input.md)
- [Time picker › Selected](./selected.md)

## Technical Notes

- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
