# Time picker › Input

> **Category:** time-picker
> **Component Name:** `flux:time-picker.input`

## Overview

Time selection input component.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `variant` | `string` | `'outline'` | Visual style variant of the component |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `dropdown` | `mixed` | `null` | Configuration for dropdown |
| `invalid` | `boolean` | `false` | Whether the component is in an invalid state |
| `size` | `mixed` | `null` | Size variant of the component |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:time-picker.input
/>
```

### Advanced Example

```blade
<flux:time-picker.input
    variant="value"
    clearable="value"
    dropdown="value"
    invalid="value"
>
    Advanced content
</flux:time-picker.input>
```

### With Livewire

```blade
<flux:time-picker.input
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
- [Time picker › Button](./button.md)
- [Time picker › Selected](./selected.md)

## Technical Notes

- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
