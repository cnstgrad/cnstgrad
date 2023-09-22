- 👋 Hi, I’m @cnstgrad
- Azure Tenant A is the primary tenant for your organization.  Azure Tenant B is a dev environment, a
sovereign cloud environment, or a partner's tenant.  You already have users in Tenant B which configured,
but tenant B doesn't have the security configured (CA, MFA, PIM) that Tenant A has.  With this solution, you will
be able to do a mass conversion of your Tenant B users to external guests to Tenant A.  This will allow you to log
into Tenant B with Tenant A credentials.  This depends on having a mail attribute for the users in Tenant B being equal
to the login email for Tenant A.

This requires a csv file to fill in the hash table for the UPN and mail attributes.

  Example:
   mail,upn
   "testuser@contoso.com","testuser@nwtraders.com"
- 
<!---
cnstgrad/cnstgrad is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
