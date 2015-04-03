This is an example application for crud operations using Java EE 6, with a particular focus on JSF, Bean Validation, EJB and JPA.

It presents the user with a page with a simple table, from where new users can be added. The edit/add screen is reached via a GET request and the user to be edited is transformed back via a view parameter on the destination page.

After editing/adding a user, an EJB DAO is used to save it via JPA and there is a redirect back to the homepage (POST-Redirect-GET pattern), where The Flash is used to display the confirmation message.

Validation constraints are defined in the User model, and are automatically taken care of by JSF.

The application was developed by Mark van der Tol, for his [master thesis Software Engineering](http://jdevelopment.nl/wp-content/uploads/sites/2/2012/07/markvandertol_thesis3.pdf) at the UVA.

It can be tried out via this [live demo](http://javaee6crud-beginning.rhcloud.com).