# Tab › Index

> **Category:** tab
> **Component Name:** `flux:tab.index`

## Overview

Tab navigation component for organizing content.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `iconTrailing` | `mixed` | `null` | Configuration for iconTrailing |
| `iconVariant` | `mixed` | `null` | Configuration for iconVariant |
| `selected` | `boolean` | `false` | Configuration for selected |
| `variant` | `mixed` | `null` | Visual style variant of the component |
| `accent` | `boolean` | `true` | Configuration for accent |
| `name` | `mixed` | `null` | Form field name attribute |
| `icon` | `mixed` | `null` | Configuration for icon |
| `size` | `mixed` | `null` | Size variant of the component |

## Inherited Props (via @aware)

These props are inherited from parent components:

- `variant`
- `size`

## Default Slot

This component accepts a default slot for its main content.

## Supported Attributes

- `disabled`

## Usage

### Basic Example

```blade
<flux:tab.index
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:tab.index
    iconTrailing="value"
    iconVariant="value"
    selected="value"
    variant="value"
>
    Advanced content
</flux:tab.index>
```

### With Livewire

```blade
<flux:tab.index
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
- **Border radius** - Rounded corners for modern appearance
- **Shadows** - Depth and elevation effects
- **Hover states** - Interactive feedback on hover

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Related Components

- [Tab › Panel](./panel.md)
- [Tab › Group](./group.md)

## Technical Notes

- Standard Blade component implementation

---

*Generated on February 17, 2026*
