1. multiplication function Unit Tests
    - Expect multiplication(2, 3) to be a number
    - Expect multiplication(2, 3) to be equal to 6
    - Expect multiplication('a', 3) to be an error
    - Expect multiplication([] , 3) to be an error
    - Expect multiplication(3, 'b') to be an error
    - Expect multiplication(3) to be equal to 3
    - Expect multiplication(3, 4, 6) to be an error

2. concatOdds function Unit Tests
    - Expect concatOdds([3, 6, 7], [8, 13, 47, 9]) to be an array
    - Expect concatOdds([3, 6, 7], [8, 13, 47, 9]) to result in [3, 7, 9, 13, 47]
    - Expect concatOdds([3, 6, 7, 13, 9], [8, 13, 47, 7, 9, 9]) to result in [3, 7, 9, 13, 47]
    - Expect concatOdds(5, 3) to be an error
    - Expect concatOdds([4, 18, 24, 6], [8, 14, 2]) to result in an empty array
    - Expect concatOdds(['lettuce', 'tomato'], [5, 7, 3]) to be an error
    - Expect concatOdds([3, 16, 9], 'a') to be an error
    - Expect concatOdds() to be an error
    - Expect concatOdds([3, 6, 7, 13, 9]) to be an error

3. Shopping Cart Functional tests
    - When a user adds something to the cart, the proceed to checkout button should be enabled
    - When a logged-in user clicks proceed to checkout, the prompts for billing and shipping should be autofilled with saved information
    - When a not logged in user clicks proceed to checkout, they should be prompted to log in, create an account or continue as a guest
    - When a user selects continue as a guest, they should be prompted to input billing and shipping info
    - When a user selects create an account, they should be prompted for login information
    - When a user tries to submit invalid information at login, they should see an error and a password reset link
    - When a user tries to submit invalid information at account creation, they should see an error that includes what types of inputs are accepted
    - When a user tries to create an account with a username that already exists, they should see an error that says to pick a different one
    - When a user tries to submit invalid billing information, they should receive an error
    - When a user tries to submit invalid shipping information they should receive an error