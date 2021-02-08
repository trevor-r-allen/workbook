# Day 34
__02/04/2020__

## Thoughts on Testing in Vue

### What are the three main types of testing we can accomplish in Vue?
Unit testing, component testing, and end-to-end testing. Unit testing lets you test isolated code, component testing lets you test a full components functionality via the DOM, and E2E testing lets you test all the layers at once witha user flow.

### What testing method do you think is the most useful? Why?
Personally I think E2E testing is the most important because seeing how all the components function together can't be done successfully on the lower levels. It also has the potential to reveal flaws in the user flows and provides an important final filter before considering a project finished.

### What testing method do you think is the least useful? Why?
Personally I would say that unit testing is the least important becuase, while not true in all cases, most of the time component tests will provide a significant validation of unit functionality for units contained within that component.
