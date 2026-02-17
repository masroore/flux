# Calendar › Index

> **Category:** calendar
> **Component Name:** `flux:calendar.index`

## Overview

Date selection interface with month/year navigation.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `selectableHeader` | `mixed` | `null` | Configuration for selectableHeader |
| `weekNumbers` | `mixed` | `null` | Show week numbers in calendar |
| `unavailable` | `mixed` | `null` | Configuration for unavailable |
| `withInputs` | `mixed` | `null` | Configuration for withInputs |
| `navigation` | `mixed` | `null` | Enable navigation controls |
| `withToday` | `mixed` | `null` | Configuration for withToday |
| `months` | `mixed` | `null` | Number of months to display |
| `value` | `mixed` | `null` | Current value of the component |
| `mode` | `mixed` | `null` | Operating mode of the component |
| `size` | `mixed` | `null` | Size variant of the component |
| `name` | `mixed` | `null` | Form field name attribute |

## Supported Attributes

- `wire:model`
- `disabled`
- `readonly`

## Usage

### Basic Example

```blade
<flux:calendar.index
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:calendar.index
    selectableHeader="value"
    weekNumbers="value"
    unavailable="value"
    withInputs="value"
>
    Advanced content
</flux:calendar.index>
```

### With Livewire

```blade
<flux:calendar.index
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
- **Hover states** - Interactive feedback on hover
- **Disabled states** - Visual indication when disabled

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Technical Notes

- Supports Livewire `wire:model` binding
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
