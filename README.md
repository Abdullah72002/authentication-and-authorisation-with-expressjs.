# authentication-and-authorisation-with-expressjs.
## User authentication system with a twist

Implementing the delete user functionality with proper authentication and authorization is a **good idea**. However, allowing everyone to delete each other without proper authorization is a **bad idea**.

Explanation:

- **Authentication**: This is the process of verifying the identity of a user. It ensures that the user is who they claim to be. In this context, this is done using JWT tokens, which are issued upon successful login and verified in subsequent requests.

- **Authorization**: This is the process of determining whether an authenticated user has the necessary permissions to perform a specific action. It ensures that the user has the right to access certain resources or perform certain operations. In this context, this is managed by checking the user's role (e.g., user, admin) and ensuring they have the appropriate permissions.
  
**In short**:

- Authentication: "Who are you?"
- Authorization: "What are you allowed to do?"

## Example

### Authentication

![diagram1](https://github.com/user-attachments/assets/f2b90fc5-bc76-4ad3-b4cc-9b8eefc11e0b)


### Authorization

![diagram2](https://github.com/user-attachments/assets/6fa39740-2e4e-4941-9b9c-8a5515b99839)



**You will be able to**

+ Issue a cookie to the client browser containing the user’s information and the account role
+ Combine the skill of Authentication and Authorisation into a project usage
+ Protect the back-end routes with the authentication and authorisation middleware
+ Create a complete administrative dashboard to manage the users’ data
+ Prevent unauthorised access using Authorisation by determine the various account role
