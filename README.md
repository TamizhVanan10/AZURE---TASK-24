# AZURE---TASK-24

## Create and configure a Recovery Services vault

In this task, you will create a Recovery Services vault. A Recovery Services vault provides storage for the virtual machine data.

In the Azure portal, search for and select Recovery Services vaults and, on the Recovery Services vaults blade, click + Create.

On the Create Recovery Services vault blade, specify the following settings:

Screenshot of the recovery services vault.

Click Review + Create, ensure that the validation passes and then click Create.

Note: Wait for the deployment to complete. The deployment should take a couple of minutes.

When the deployment is completed, click Go to Resource.

In the Settings section, click Properties.

Select the Update link under Backup Configuration label.

On the Backup Configuration blade, review the choices for Storage replication type. Leave the default setting of Geo-redundant in place and close the blade.

Note: This setting can be configured only if there are no existing backup items.

Did you know? The Cross Region Restore option allows you to restore data in a secondary, Azure paired region.

Select the Update link under Security Settings > Soft Delete and security settings label.

On the Security Settings blade, note that Soft Delete (For workload running in Azure) is Enabled. Notice the soft delete retention period is 14 days.
