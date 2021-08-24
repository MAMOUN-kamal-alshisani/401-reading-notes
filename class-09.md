# Reading: Authorization/Authentication


## What header(s) are used in authentication and authorization :

***Using the HTTP Authorization header is the most common method of providing authentication information. Except for POST requests and requests that are signed by using query parameters, all Amazon S3 operations use the Authorization request header to provide authentication information.***

## What is safe to put into a JWT

***A JWT is a mechanism to verify the owner of some JSON data. It’s an encoded, URL-safe string that can contain an unlimited amount of data (unlike a cookie) and is cryptographically signed.***
***When a server receives a JWT, it can guarantee the data it contains can be trusted because it’s signed by the source. No middleman can modify a JWT once it’s sent.***

## How are JWTs validated 

* Check that the JWT is well formed.

* Check the signature.

* Check the standard claims.

## RBAC

***In computer systems security, role-based access control (RBAC)[1][2] or role-based security[3] is an approach to restricting system access to authorized users. It is an approach to implement mandatory access control (MAC) or discretionary access control (DAC).***
***Role-based access control (RBAC) is a policy-neutral access-control mechanism defined around roles and privileges. The components of RBAC such as role-permissions, user-role and role-role relationships make it simple to perform user assignments. A study by NIST has demonstrated that RBAC addresses many needs of commercial and government organizations.[4] RBAC can be used to facilitate administration of security in large organizations with hundreds of users and thousands of permissions. Although RBAC is different from MAC and DAC access control frameworks, it can enforce these policies without any complication.***

## User Roles

***A combined user role that grants to users the ability to perform all User, Device, and Policy Manager tasks. Allow users to read, create, update, and delete all types of devices.***

## JWT Token

***is a proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key.***
