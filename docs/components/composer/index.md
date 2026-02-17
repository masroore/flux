# Composer › Index

> **Category:** composer
> **Component Name:** `flux:composer.index`

## Overview

Rich text composition interface with toolbar actions.

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `name` | `mixed` | `$attributes->whereStartsWith('wire:model')->first()` | Form field name attribute |
| `actionsTrailing` | `mixed` | `null` | Configuration for actionsTrailing |
| `actionsLeading` | `mixed` | `null` | Configuration for actionsLeading |
| `variant` | `mixed` | `null` | Visual style variant of the component |
| `invalid` | `mixed` | `null` | Whether the component is in an invalid state |
| `footer` | `mixed` | `null` | Configuration for footer |
| `header` | `mixed` | `null` | Configuration for header |
| `input` | `mixed` | `null` | Configuration for input |

## Supported Attributes

- `wire:model`
- `disabled`

## Usage

### Basic Example

```blade
<flux:composer.index
    name="field_name"
/>
```

### Advanced Example

```blade
<flux:composer.index
    actionsTrailing="value"
    actionsLeading="value"
    variant="value"
>
    Advanced content
</flux:composer.index>
```

### With Livewire

```blade
<flux:composer.index
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

### Customization

You can customize the component by:

- Adding custom classes via the `class` attribute
- Using Tailwind's utility classes
- Overriding CSS variables for theme colors


## Technical Notes

- Supports Livewire `wire:model` binding
- Built on Flux UI custom elements for enhanced functionality

---

*Generated on February 17, 2026*
