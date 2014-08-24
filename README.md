# Mixing in Backbone.Events with React components

A tiny bit of glue code making it easier to work with objects that have `Backbone.Events` mixed in, like Backbone Models, Collections but also Ampersand.js' State, Collection, Model, etc.


It basically provides available to a component to which it's mixed in:

- `this.on`
- `this.off`
- `this.trigger`
- `this.once`
- `this.listenTo`
- `this.stopListening`
- `this.listenToOnce`

Also the following methods can be implemented in the definition of a component to more easily manage
the listening to objects throughout's the component's lifecycle:

- `this.registerListeners(props, state)`
- `this.degisterListeners(props, state)`

This approach is designed to be **completely unopinionated to how you structure your components**, what events to listen for and other application specific details. If you are looking for more guidance on this, have a look at one of the many other React / Backbone mixins.

## Example

TBD

## API

TBD

