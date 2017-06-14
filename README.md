

# SASS - Partials

- Partials actually are the files which holds the values and donot get converted to css upon transpiling.
- In this example as per the convention we named them as
    ```javascript
        _variables.scss. _(underscore).
     ```
- so upon transpiling they donot get converted to css but still can be utilized inside the application.
- Likewise to utilize them in main.scss we imported them @import 'variables' . No need of _ or full file name.
- In local cli generated apps we can use them as the below form
    ```javascript
        @import "variables";
    ```
  wherever we wanted to use.