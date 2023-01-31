# Cypress: Book Store

App for testing: `https://demoqa.com/login`

[Create](https://demoqa.com/register) an account **manually** 
before completing the task.  

"username":"TestCypress"
"password": "TestCypress123!"

**task** is to check next flow:

1. Login:
   - assert the username after login username;
   - asser new url;
1. Navigate to `Book store`.
1. Type into search field 'Speaking JavaScript'.
1. Click on 'Speaking JavaScript' book.
   - assert description of the book.
1. Click on [Add To Your Collection].
1. Confirm popup. 
1. Go to your profile page.
1. Assert 'Speaking JavaScript' in your shopping list.
1. Delete Speaking JavaScript book from your list.



1. Split a test flow on 3 tests: 
 - login 
 - add book 
 - delete book
1. Create `cy.login()` command to login with API. Use `cy.request()` with `.setCookie()` to implement this command.
1. Use `cy.login()` in second and third tests.
