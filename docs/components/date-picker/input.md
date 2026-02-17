# Date picker › Input

> **Category:** date-picker
> **Component Name:** `flux:date-picker.input`

## Overview

Date picker input with calendar interface.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `clearable` | `boolean` | `false` | Whether the component shows a clear button |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `size` | `mixed` | `null` | Size variant of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `placeholder`

## Slots

| Slot | Required | Description |
|------|----------|-------------|
| `iconTrailing` | No | Custom iconTrailing content |

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:date-picker.input
    placeholder="Enter value"
>
    Content here
</flux:date-picker.input>
```

### Advanced Example

```blade
<flux:date-picker.input
    placeholder="value"
    clearable="value"
    invalid="value"
    size="value"
>
    Advanced content
</flux:date-picker.input>
```

### With Livewire

```blade
<flux:date-picker.input
    wire:model="property"
/>
```

## Accessibility

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

- [Date picker › Index](./index.md)
- [Date picker › Button](./button.md)
- [Date picker › Selected](./selected.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
