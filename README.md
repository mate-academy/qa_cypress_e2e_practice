# ![Drash Example App](logo.png)

## Workflow

1. Fork the repo.
1. Clone **your** forked repository.
1. Create a new branch `git checkout -b e2e_testing`.
1. Run the [app](./DEV.md).
1. Resolve tasks.
1. Create a pull request.
1. Do not forget to click on `Re-request review` if you submit the homework after previous review.

## Task

Go to `e2e` folder and cover listed functionality with e2e tests:

- creating an article;
- editings an article;
- deleting an article;
- sign in (positive);
- sign in (invalid credentials);
- sign up (positive);
- sign up (negative);
- following/unfollowing the user;
- updating bio;
- updating username;
- updating email;
- updating password.

### Basics level

1. Clear all data from the database before the test.
1. Add `data-qa` attributes for all elements you are working with in tests.
1. Use faker and custom methods to generate a fake data in tests.

### Advanced level

1. Use PageObject pattern for your tests. Resources:
   - [Deep diving PageObject pattern and using it with Cypress](https://medium.com/reactbrasil/deep-diving-pageobject-pattern-and-using-it-with-cypress-e60b9d7d0d91);
   - [Cypress Page Object Model](https://medium.com/nerd-for-tech/cypress-page-object-model-953791736972);
   - [Using Page Objects in Cypress](https://dev.to/leading-edje/using-page-objects-in-cypress-co9);
   - [What is Cypress Page Object Model?](https://www.browserstack.com/guide/cypress-page-object-model);
   - [CYPRESS Page Object Model EXAMPLE](https://www.youtube.com/watch?v=bC9bGHDgpQk).
