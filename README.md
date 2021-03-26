# Feel UI

`feelui` is an event-driven gui tookit that focus on building beautiful user interface and make custom widgets easily.
It also provide a offical baseview for those who want to create audio plugin.

## Example
// todo
## Features

- Cross-platform support
  - Build your application and running on Windows, MacOS, Linux, Android(Experiment) and iOS(Experiment).
- Offical baseview support for creating audio plugin(e.g: VST).(**WIP**)
- Custom widgets support
- CSS Theming
- I18n(add `features=["i18n"]` to enable this features)

## Design

feelui is originally based on these process:

- Events
- Styling
- Layout
- Drawing

First we will build a widget, then bind events on it.