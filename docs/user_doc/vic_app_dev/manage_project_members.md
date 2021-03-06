# Manage Project Members # 

After you have added members to a project, you can change existing project members' roles or remove members from the project.

**Prerequisites**

You have a created project and assigned users to it.

**Procedure**

1. Log in to the vSphere Integrated Containers Registry interface at https://<i>vic_appliance_address</i>:443.

   Use the `admin` account, an account with the system-wide Administrator role, or an account that has the Project Admin role for this project. If the vSphere Integrated Containers appliance uses a different port for vSphere Integrated Containers Registry, replace 443 with the appropriate port.
2. Click **Projects** on the left, click a project name, and click **Members**.
3. In the list of project members, click the 3 vertical dots next to a user name and select an option.

   - To assign the member to a different role in the project, select **Project Admin**, **Developer**, or **Guest**.
   - To remove the member from the project, select **Delete**.