# Gtk
[[العربية]](README.ar.md)

GTK+ bindings for the Alusus Programming Language, providing access to the GTK 3 toolkit for building graphical user interfaces.

## Description

This library provides Alusus language bindings for GTK+ 3, enabling developers to create modern desktop applications with graphical user interfaces using the Alusus programming language. The bindings wrap the GTK+ C library and expose its functionality through an Alusus-friendly interface.

## Components

- **Gtk**: Core GTK+ 3 bindings including:
  - `common.alusus` - Common GTK types and functions
  - `constants.alusus` - GTK constants and enumerations
  - `widgets.alusus` - Widget bindings (buttons, labels, entries, etc.)
  - `windows.alusus` - Window and container management

- **Glib**: GLib library bindings providing:
  - `common.alusus` - Common GLib types and utilities
  - `List.alusus` - GLib list data structures

- **Examples**: Sample applications demonstrating library usage:
  - `hello_world.alusus` - Basic GTK window example
  - `simple_timer.alusus` - Timer application
  - `widgets_guide.alusus` - Widget usage examples
  - `factorial.alusus` - Factorial calculator demo

## Usage

Import the library in your Alusus program:

```alusus
import "Apm";
Apm.importPackage("Alusus/Gtk@0.2");
```

## License

This project is licensed under the GNU Lesser General Public License v3.0 (LGPL-3.0). See the `COPYING` and `COPYING.LESSER` files for details.
