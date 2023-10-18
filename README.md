# REDUX

WHAT IS REDUX ?

- A state management system for cross-component or app-wide state.

CROSS-COMPONENT AND APP-WIDE STATE ?

- Local State: State that belong to single component. Example - toggling button.
  Should be managed component-internal with useState()/useReducer.

- Cross-Componrnt: State that effect multiple components. Example - Open/Close state of a modal overlay. Require " props chains" / " prop drilling ".

- App-wide state: State that affect the entire app ( most/ all components). Example -
  user authentication status. Require " props chains" / " prop drilling ".

WHY WE USE REDUX WHEREAS WE HAVE USECONTEXT() ?
