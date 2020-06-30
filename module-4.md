# Module 4 Rubric

## Props & State

1. No code or very little code has been written or the code doesn't run. If it runs, no deliverables have been met. Not managed to set state or pass props successfully.

2. State is not being set or updated. Props are not being passed down, or you are passing down the right prop but trying to access it incorrectly (wrong name, unnecessary `this`, `state` instead of `props`) or key props are missing. API call does not successfully populate state or does not rely on state at all (e.g. uses `querySelector()` to grab the value instead of passing the state).

3. State is working. However, it may be in the wrong component, it might be nested oddly or might have some unnecessary state. Props are being passed unnecessarily to components. Functions that change or calculate state are not defined in the component that they are most closely tied to.

4. State works and is held by the lowest common component. No unnecessary state is created. Only the necessary props are being passed down. Functions used to edit state are passed down.

5. Advanced deliverables are met.

## Code Structure/Efficiency

1. No code or very little code has been written or the code doesn't run, i.e. syntax errors, imports missing, etc. If it runs, no deliverables have been met.

2. Starter components have been unnecessarily modified and broken. There is no reference to componentDidMount. Incorrect or unnecessary lifecycle methods are used. Vanilla JavaScript methods (e.g. `querySelector()`) are being used instead of appropriate React techniques.

3. Fetch is triggered in the right place. Code is not abstracted into clear methods. Additional components have been added which serve no purpose. Props and variables could be named consistently and descriptively.

4. Components are structured in a logical way. Class components only used when needed, functional components used for everything else. Code is abstracted into clear methods. Used object destructuring and spread operator successfully.

5. Advanced deliverables met. Uses some of the following: destructuring, functional components, spreading, hooks, pure functions, performance is taken into account.

## Rendering

1. No code or very little code has been written or the code doesn't run. If it runs, no deliverables have been met.

2. Did not manage to render everything that was asked for in the deliverables.

3. Renders everything that is asked for in the deliverables. Components could be more abstract/reusable. May have created own components instead of using the components provided.

4. Renders everything that is asked for in the deliverables. Components are abstract/reusable. No unnecessary components were created.

5. Everything from 4 plus extra features were added that are not listed in the deliverables.
