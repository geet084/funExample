# FunList!!

This application was built using `create-react-app`
After you clone this down
  - `npm install`
  - `npm start`
  - `npm test`

### Expectations / Rules

Build a React App that displays *fun events*!

You will have a 40 minutes to build this application. Whatever you don't finish in the mock assessment, we recommend you practice prior to the final assessment.

***When you create a component you MUST also create a test file. You must test as you go.***

![mockup](https://github.com/Tman22/funExample/blob/master/mockup.png)

### Iteration 0

Walk through the mockup and outline the components that you will need to buid this application.

* Start by creating a component that has a form inside with two inputs labeled
  - Event and Details
  - Place this form inside the `Event-form` div in the `App` component'
* Add a button that submits the Fun Event.
* After clicking the submit button I should see the event populate inside the `Fun-area` class
  - To make this happen you should add 2 components. An `EventList` & `Event` component
  - The `EventList` component should receive a list of `events` while an `Event` should receive a single event with an `id`, `event`, `details`.
* Finally add a button to each `Event` that can delete that specific event.
