# Date picker › Index

> **Category:** date-picker
> **Component Name:** `flux:date-picker.index`

## Overview

Date picker input with calendar interface.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `selectableHeader` | `mixed` | `null` | Configuration for selectableHeader |
| `withConfirmation` | `mixed` | `null` | Configuration for withConfirmation |
| `weekNumbers` | `mixed` | `null` | Show week numbers in calendar |
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `withPresets` | `mixed` | `null` | Configuration for withPresets |
| `unavailable` | `mixed` | `null` | Configuration for unavailable |
| `withInputs` | `mixed` | `null` | Configuration for withInputs |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `withToday` | `mixed` | `null` | Configuration for withToday |
| `type` | `string` | `'button'` | Configuration for type |
| `presets` | `mixed` | `null` | Configuration for presets |
| `trigger` | `mixed` | `null` | Configuration for trigger |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `months` | `mixed` | `null` | Number of months to display |
| `value` | `mixed` | `null` | Current value of the component |
| `size` | `mixed` | `null` | Size variant of the component |
| `name` | `mixed` | `null` | Form field name attribute |
| `mode` | `mixed` | `null` | Operating mode of the component |

## Supported Attributes

- `wire:model`
- `disabled`
- `readonly`

## Usage

### Basic Example

```blade
<flux:date-picker.index
    placeholder="Enter value"
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:date-picker.index
    selectableHeader="value"
    withConfirmation="value"
    weekNumbers="value"
    placeholder="value"
>
    Advanced content
</flux:date-picker.index>
```

### With Livewire

```blade
<flux:date-picker.index
    wire:model="property"
/>
```

## Accessibility

- ARIA labels are properly set for screen readers
- Comprehensive ARIA attributes for accessibility
- Disabled states are properly communicated to assistive technologies
- Visual and functional disabled states

## Styling

### Default Styling

The component uses Tailwind CSS classes for styling. Key styling features:

- **Dark mode support** - Automatically adapts to dark mode
- **Border radius** - Rounded corners for modern appearance
- **Shadows** - Depth and elevation effects
- **Hover states** - Interactive feedback on hover
- **Disabled states** - Visual indication when disabled

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Date picker › Input](./input.md)
- [Date picker › Button](./button.md)
- [Date picker › Selected](./selected.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
