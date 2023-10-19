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

- React Context - Potential Disadvantages.
  There is two disadvantages are:

1. Complex Setup/ Management: In more comples apps, managing React Context can lead to deeply nested JSX code and / or juge " Context Provider " components.
2. Performance: React Context is not optimized for high frequency state changes.

HOW REDUX WORKS ?

- Central Data ( state ) Store.
- Here we use reducer funtion to change the data or update the data in store data.
- Here we use Action which dispacth the data from component and than action forward the dispacth data to reducer function and than reducer it will give data to central data store basically update the data in central data store