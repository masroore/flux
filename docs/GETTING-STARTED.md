# Getting Started with Flux Pro Components

Welcome to the Flux Pro component library documentation! This guide will help you get up and running quickly.

## What is Flux Pro?

Flux Pro is a premium UI component library for Laravel and Livewire applications. It provides over 120 professionally designed, accessible, and fully customizable components that seamlessly integrate with your Laravel applications.

## Key Features

- 🚀 **120+ Components** - Comprehensive set of UI components
- ⚡ **Livewire Native** - Built specifically for Livewire 3+
- 🎨 **Tailwind CSS** - Styled with Tailwind CSS utilities
- 🌙 **Dark Mode** - Full dark mode support out of the box
- ♿ **Accessible** - WCAG compliant with proper ARIA attributes
- 📱 **Responsive** - Mobile-first responsive design
- 🎯 **Type-Safe** - TypeScript definitions included
- 🔧 **Customizable** - Easy to customize and extend

## Installation

Flux Pro is already installed in this project. The components are available in the `flux:` namespace.

## Basic Usage

### Simple Components

The simplest way to use Flux Pro components is with the `flux:` prefix:

```blade
{{-- Button --}}
<flux:button>Click me</flux:button>

{{-- Input --}}
<flux:input placeholder="Enter your name" />

{{-- Text Area --}}
<flux:textarea placeholder="Enter description" />
```

### Form Components

Form components work seamlessly with Livewire:

```blade
{{-- Text Input with Livewire --}}
<flux:input 
    wire:model="name" 
    placeholder="Your name"
    label="Name"
/>

{{-- Select Dropdown --}}
<flux:select wire:model="status">
    <option value="active">Active</option>
    <option value="inactive">Inactive</option>
    <option value="pending">Pending</option>
</flux:select>

{{-- Date Picker --}}
<flux:date-picker 
    wire:model="birthdate"
    placeholder="Select date"
/>

{{-- Autocomplete --}}
<flux:autocomplete 
    wire:model="country"
    placeholder="Search countries..."
/>
```

### Complex Components

#### Accordion

Create collapsible sections:

```blade
<flux:accordion>
    <flux:accordion.item heading="Section 1">
        Content for section 1
    </flux:accordion.item>
    
    <flux:accordion.item heading="Section 2">
        Content for section 2
    </flux:accordion.item>
    
    <flux:accordion.item heading="Section 3">
        Content for section 3
    </flux:accordion.item>
</flux:accordion>
```

#### Tabs

Create tabbed interfaces:

```blade
<flux:tab.group>
    <flux:tabs>
        <flux:tab name="profile">Profile</flux:tab>
        <flux:tab name="settings">Settings</flux:tab>
        <flux:tab name="notifications">Notifications</flux:tab>
    </flux:tabs>
    
    <flux:tab.panel name="profile">
        Profile content here
    </flux:tab.panel>
    
    <flux:tab.panel name="settings">
        Settings content here
    </flux:tab.panel>
    
    <flux:tab.panel name="notifications">
        Notifications content here
    </flux:tab.panel>
</flux:tab.group>
```

#### Rich Text Editor

Full-featured text editor:

```blade
<flux:editor 
    wire:model="content"
    toolbar="bold italic underline | heading bullet ordered | link"
/>
```

#### Calendar & Date Picker

Advanced date selection:

```blade
{{-- Date Picker with Button --}}
<flux:date-picker 
    wire:model="date"
    type="button"
    placeholder="Select date"
/>

{{-- Standalone Calendar --}}
<flux:calendar 
    wire:model="selectedDate"
    :with-today="true"
    :navigation="true"
/>

{{-- Date Range Picker --}}
<flux:date-picker 
    wire:model="dateRange"
    mode="range"
    :months="2"
/>
```

#### Charts & Data Visualization

Display data beautifully:

```blade
<flux:chart :value="$chartData">
    <flux:chart.bar />
    <flux:chart.axis.x />
    <flux:chart.axis.y />
    <flux:chart.legend />
    <flux:chart.tooltip />
</flux:chart>
```

#### Kanban Board

Organize tasks visually:

```blade
<flux:kanban>
    <flux:kanban.column>
        <flux:kanban.column.header>To Do</flux:kanban.column.header>
        <flux:kanban.column.cards>
            <flux:kanban.card>Task 1</flux:kanban.card>
            <flux:kanban.card>Task 2</flux:kanban.card>
        </flux:kanban.column.cards>
    </flux:kanban.column>
    
    <flux:kanban.column>
        <flux:kanban.column.header>In Progress</flux:kanban.column.header>
        <flux:kanban.column.cards>
            <flux:kanban.card>Task 3</flux:kanban.card>
        </flux:kanban.column.cards>
    </flux:kanban.column>
</flux:kanban>
```

#### File Upload

Drag-and-drop file uploads:

```blade
<flux:file-upload wire:model="documents">
    <flux:file-upload.dropzone>
        Drop files here or click to browse
    </flux:file-upload.dropzone>
</flux:file-upload>
```

## Component Categories

Flux Pro components are organized into categories:

### 1. Form Components
- [Select](./components/select/README.md) - Dropdown selection
- [Autocomplete](./components/autocomplete/README.md) - Auto-complete input
- [Pillbox](./components/pillbox/README.md) - Multi-select with pills
- [Slider](./components/slider/README.md) - Range slider

### 2. Date & Time
- [Calendar](./components/calendar/README.md) - Calendar component
- [Date Picker](./components/date-picker/README.md) - Date selection
- [Time Picker](./components/time-picker/README.md) - Time selection

### 3. Content Organization
- [Accordion](./components/accordion/README.md) - Collapsible sections
- [Tabs](./components/tabs/README.md) - Tab navigation
- [Kanban](./components/kanban/README.md) - Kanban board

### 4. Rich Content
- [Editor](./components/editor/README.md) - Rich text editor
- [Composer](./components/composer/README.md) - Composition interface

### 5. Data Visualization
- [Chart](./components/chart/README.md) - Charts and graphs

### 6. Overlays & Dialogs
- [Toast](./components/toast/README.md) - Notifications
- [Popover](./components/popover/README.md) - Floating content
- [Context](./components/context/README.md) - Context menus
- [Command](./components/command/README.md) - Command palette

### 7. File Management
- [File Upload](./components/file-upload/README.md) - File upload interface
- [File Item](./components/file-item/README.md) - File display

## Common Patterns

### Validation & Error States

All form components support validation states:

```blade
<flux:input 
    wire:model="email"
    name="email"
    placeholder="Email address"
/>

{{-- Errors are automatically detected from Laravel's $errors bag --}}
@error('email')
    <span class="text-red-500">{{ $message }}</span>
@enderror
```

### Disabled State

Disable components when needed:

```blade
<flux:select disabled wire:model="status">
    <option>Select status</option>
</flux:select>
```

### Custom Styling

Add custom classes:

```blade
<flux:button class="w-full bg-blue-600 hover:bg-blue-700">
    Full Width Button
</flux:button>
```

### Size Variants

Most components support size variants:

```blade
<flux:button size="sm">Small</flux:button>
<flux:button size="md">Medium</flux:button>
<flux:button size="lg">Large</flux:button>
<flux:button size="xl">Extra Large</flux:button>
```

### Dark Mode

All components automatically support dark mode based on your Tailwind configuration:

```blade
{{-- This component will automatically adapt to dark mode --}}
<flux:card class="bg-white dark:bg-zinc-800">
    Content here
</flux:card>
```

## Livewire Integration

Flux Pro is built for Livewire. Here are common integration patterns:

### Two-Way Binding

```blade
<flux:input wire:model="username" />
```

### Live Updates

```blade
<flux:input wire:model.live="search" />
```

### Debounced Updates

```blade
<flux:input wire:model.debounce.500ms="query" />
```

### Lazy Loading

```blade
<flux:textarea wire:model.lazy="description" />
```

### Events

```blade
<flux:select wire:model="category" wire:change="updateProducts">
    <option value="all">All Categories</option>
</flux:select>
```

## Accessibility

All Flux Pro components follow accessibility best practices:

- ✅ Proper ARIA attributes
- ✅ Keyboard navigation
- ✅ Focus management
- ✅ Screen reader support
- ✅ Semantic HTML
- ✅ Color contrast compliance

## Performance Tips

1. **Use wire:model.lazy** for less critical updates
2. **Use wire:model.debounce** for search inputs
3. **Leverage wire:ignore** for JavaScript-heavy components
4. **Use wire:key** for dynamic lists

## Customization

### Tailwind Configuration

Flux Pro uses Tailwind CSS. Customize colors in your `tailwind.config.js`:

```javascript
module.exports = {
    theme: {
        extend: {
            colors: {
                'accent': {
                    DEFAULT: '#3b82f6',
                    foreground: '#ffffff',
                }
            }
        }
    }
}
```

### Component Variants

Many components support variants:

```blade
{{-- Tabs variants --}}
<flux:tabs variant="pills">...</flux:tabs>
<flux:tabs variant="segmented">...</flux:tabs>

{{-- Editor variants --}}
<flux:editor variant="borderless">...</flux:editor>
```

## Next Steps

1. **Browse Components** - Explore the [component index](./README.md)
2. **Read Component Docs** - Each component has detailed documentation
3. **Check Examples** - Look at usage examples in component pages
4. **Experiment** - Try components in your own project

## Common Issues & Solutions

### Component Not Found

Make sure Flux Pro is properly installed and registered in your service providers.

### Styles Not Applied

Ensure Tailwind CSS is properly configured and your build process includes Flux Pro's views:

```javascript
// tailwind.config.js
module.exports = {
    content: [
        './vendor/livewire/flux-pro/stubs/**/*.blade.php',
        // ... other paths
    ]
}
```

### Livewire Not Working

Ensure Livewire is properly installed and the `@livewireScripts` directive is in your layout.

## Resources

- [Main Documentation](./README.md)
- [Component Navigation](./NAVIGATION.md)
- [All Component Categories](./README.md#component-categories)

## Support

For issues, questions, or feature requests, please refer to the official Flux Pro documentation or support channels.

---

*Last updated: February 17, 2026*

