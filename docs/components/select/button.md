# Select › Button

> **Category:** select
> **Component Name:** `flux:select.button`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `invalid` | `boolean` | `false` | Whether the component is in an invalid state |
| `suffix` | `mixed` | `null` | Configuration for suffix |
| `size` | `mixed` | `null` | Size variant of the component |
| `max` | `number` | `1` | Configuration for max |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `placeholder`

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:select.button
    placeholder="Enter value"
/>
```

### Advanced Example

```blade
<flux:select.button
    placeholder="value"
    clearable="value"
    invalid="value"
    suffix="value"
>
    Advanced content
</flux:select.button>
```

### With Livewire

```blade
<flux:select.button
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

- [Select › Options](./options.md)
- [Select › Variants › Custom](./variants-custom.md)
- [Select › Variants › Combobox](./variants-combobox.md)
- [Select › Variants › Listbox](./variants-listbox.md)
- [Select › Indicator › Index](./indicator-index.md)

## Technical Notes

- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
