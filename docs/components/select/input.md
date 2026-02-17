# Select › Input

> **Category:** select
> **Component Name:** `flux:select.input`

## Overview

Dropdown select component with search and filtering.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `size` | `mixed` | `null` | Size variant of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `placeholder`

## Slots

| Slot | Required | Description |
|------|----------|-------------|
| `iconTrailing` | No | Custom iconTrailing content |

## Supported Attributes

- `wire:model`
- `disabled`

## Usage

### Basic Example

```blade
<flux:select.input
    placeholder="Enter value"
>
    Content here
</flux:select.input>
```

### Advanced Example

```blade
<flux:select.input
    placeholder="value"
    clearable="value"
    size="value"
>
    Advanced content
</flux:select.input>
```

### With Livewire

```blade
<flux:select.input
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

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
