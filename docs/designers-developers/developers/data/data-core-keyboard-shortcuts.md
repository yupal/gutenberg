# The Keyboard Shortcuts Data

Namespace: `core/keyboard-shortcuts`.

## Selectors

<!-- START TOKEN(Autogenerated selectors|../../../../packages/keyboard-shortcuts/src/store/selectors.js) -->

<a name="getAllShortcutRawKeyCombinations" href="#getAllShortcutRawKeyCombinations">#</a> **getAllShortcutRawKeyCombinations**

Returns the raw representation of all the keyboard combinations of a given shortcut name.

_Parameters_

-   _name_ `string`: Shortcut name.

_Returns_

-   `Array<string>`: Shortcuts.

<a name="getCategoryShortcuts" href="#getCategoryShortcuts">#</a> **getCategoryShortcuts**

Returns the shortcut names list for a given category name.

_Parameters_

-   _categoryName_ `string`: Category name.

_Returns_

-   `Array<string>`: Shortcut names.

<a name="getShortcutAliases" href="#getShortcutAliases">#</a> **getShortcutAliases**

Returns the aliases for a given shortcut name.

_Parameters_

-   _name_ `string`: Shortcut name.

_Returns_

-   `Array<WPShortcutKeyCombination>`: Key combinations.

<a name="getShortcutDescription" href="#getShortcutDescription">#</a> **getShortcutDescription**

Returns the shortcut description given its name.

_Parameters_

-   _name_ `string`: Shortcut name.

_Returns_

-   `?string`: Shortcut description.

<a name="getShortcutKeyCombination" href="#getShortcutKeyCombination">#</a> **getShortcutKeyCombination**

Returns the main key combination for a given shortcut name.

_Parameters_

-   _name_ `string`: Shortcut name.

_Returns_

-   `?WPShortcutKeyCombination`: Key combination.

<a name="getShortcutRepresentation" href="#getShortcutRepresentation">#</a> **getShortcutRepresentation**

Returns a string representing the main key combination for a given shortcut name.

_Parameters_

-   _name_ `string`: Shortcut name.
-   _representation_ (unknown type): Type of representation (display, raw, ariaLabel).

_Returns_

-   `?string`: Shortcut representation.

<!-- END TOKEN(Autogenerated selectors|../../../../packages/keyboard-shortcuts/src/store/selectors.js) -->

## Actions

<!-- START TOKEN(Autogenerated actions|../../../../packages/keyboard-shortcuts/src/store/actions.js) -->

<a name="registerShortcut" href="#registerShortcut">#</a> **registerShortcut**

Returns an action object used to register a new keyboard shortcut.

_Parameters_

-   _get_ `Function`: Atom resover.
-   _set_ `Function`: Atom updater.
-   _config_ `WPShortcutConfig`: Shortcut config.

<a name="unregisterShortcut" href="#unregisterShortcut">#</a> **unregisterShortcut**

Returns an action object used to unregister a keyboard shortcut.

_Parameters_

-   _get_ `Function`: get atom value.
-   _set_ `Function`: set atom value.
-   _name_ `string`: Shortcut name.


<!-- END TOKEN(Autogenerated actions|../../../../packages/keyboard-shortcuts/src/store/actions.js) -->