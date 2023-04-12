# Class Eight Notes (401)

## Access Control (ACL)

### 5 steps to RBAC[^1]

- *Role Based Access Control (RBAC)* is granting user access to a system based on their role within the organization. This can be a very efficient way of managing the organization as it can make assignment of access rights systematic and repeatable.
- One example implementation is an admin user can alter the datebase, and a staff user can access and read the data.
- I would use access control lists(ACL), since it categroze access rights based on user-groups or objects, which simplify a lot of processes for a simple database administration.

### RBAC Wiki[^2]

- Authorization is "based on who you are, what type of access are you authorized to have".
- Three primary rules defined for RBAC are:

1. role-based assignment, where a subject can exercise a permission only if the subject has selected or been assigned a role;
2. role authorization: a subject's active role must be authorized for the subject;
3. permission authorization: a subject can exercise a permission only if the permission is authorized for the subject's active role. In combination of the two roles above, the user can exercise only permissions for which they are aurhorized

### RBAC Tutorial[^3]

- Access rights are associated with the role. So an individual does not have extra excess that's not associated to their role.
- Access rights is activated into one or more roles, and their rights depend on what the role allows the user to have access to.
- RBAC benefits a business in the following way: 

1. Policy does not have to change once a person leaves the organization or when a new employee signs on, they should be able to activate the rights by being in a role. 
2. Each person would revisiting least privilege, since the user in one role has access to a subset of the files rather than everything
3. The user can switch roles to gain access to other resources.
4. SELinux supports RBAC

Explain how RBAC might benefit a business.

## Things I want to know more about


 [Back to main page](https://mirandalu2020.github.io/reading-notes/)

## References

[^1]:https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html
[^2]:https://en.wikipedia.org/wiki/Role-based_access_control
[^3]: