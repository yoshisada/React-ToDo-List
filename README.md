# To-do list application

## Intro
Implemented as a part of IBM Acellerate 2021 using React and Material-UI.  Deoplyed here: [**yoshisada.github.io/React-ToDo-List/**](https://yoshisada.github.io/React-ToDo-List/)
## Requirements
Feature requirements:
+ **Take in and display** to do list items
+ Allow users to **mark items as complete**
+ Provide the **date and time of item addition**
+ Validate there are **no duplicated items** (i.e. do not accept duplicate inputs)
+ Give users the option to **update list items**
+ Give users the option to **delete list items**


Implementation requirements:
+ Use [**Material UI components**](https://material-ui.com/) at least once throughout the app
+ Use JS's [**list.map**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) function at least once to manipulate list items
+ Implement at least one **functional component**


## Testing
When testing web components, developers often use ids to uniquely define elements on a page. The React Testing Library provides a query which can identify items with the attribute data-testid to do just that (reference [here](https://testing-library.com/docs/queries/bytestid/)). We have implemented simple tests in `App.test.js` that will look for ids in your code. Do not push changes to the tests in this file. To get familiar with the idea of testing ids, implement the attributes below:
+ `data-testid="new-item-input"` on the Input component which takes user input for new items.
+ `data-testid="new-item-button"` on the Button component which submits new items to the to do list.


Note: Material UI components (and other libraries) render as HTML components under the hood, so using Material UI's TextField would still render in the DOM as an Input element and pass the tests for this lab.
