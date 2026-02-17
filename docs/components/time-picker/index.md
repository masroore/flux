# Time picker › Index

> **Category:** time-picker
> **Component Name:** `flux:time-picker.index`

## Overview

Time selection input component.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `placeholder` | `mixed` | `null` | Placeholder text when no value is selected |
| `unavailable` | `mixed` | `null` | Configuration for unavailable |
| `clearable` | `mixed` | `null` | Whether the component shows a clear button |
| `dropdown` | `mixed` | `null` | Configuration for dropdown |
| `type` | `string` | `'button'` | Configuration for type |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `value` | `mixed` | `null` | Current value of the component |
| `name` | `mixed` | `null` | Form field name attribute |
| `size` | `mixed` | `null` | Size variant of the component |

## Slots

| Slot | Required | Description |
|------|----------|-------------|
| `dropdown` | No | Custom dropdown content |

## Supported Attributes

- `wire:model`
- `disabled`
- `readonly`

## Usage

### Basic Example

```blade
<flux:time-picker.index
    placeholder="Enter value"
    name="field_name"
>
    Content here
</flux:time-picker.index>
```

### Advanced Example

```blade
<flux:time-picker.index
    placeholder="value"
    unavailable="value"
    clearable="value"
    dropdown="value"
>
    Advanced content
</flux:time-picker.index>
```

### With Livewire

```blade
<flux:time-picker.index
    wire:model="property"
/>
```

## Accessibility

- Keyboard navigation support with proper focus management
- Disabled states are properly communicated to assistive technologies

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

- [Time picker › Input](./input.md)
- [Time picker › Button](./button.md)
- [Time picker › Selected](./selected.md)

## Technical Notes

- Supports Livewire `wire:model` binding
- Contains `wire:ignore` regions for JavaScript library integration
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
