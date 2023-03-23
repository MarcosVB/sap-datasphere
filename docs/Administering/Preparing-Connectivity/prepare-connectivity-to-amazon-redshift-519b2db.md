<!-- loio519b2dbc588940fb9698745e430c9859 -->

# Prepare Connectivity to Amazon Redshift

To be able to successfully validate and use a connection to an Amazon Redshift database for remote tables or data flows certain preparations have to be made.



<a name="loio519b2dbc588940fb9698745e430c9859__prereq_rt_Amazon_Redshift"/>

## Remote Tables

Before you can use the connection for creating views and accessing data via remote tables, the following is required:

-   An administrator has connected an SAP HANA smart data integration Data Provisioning Agent to SAP Datasphere and registered the CamelJdbcAdapter.

    For more information, see [Preparing Data Provisioning Agent Connectivity](preparing-data-provisioning-agent-connectivity-f1a39d1.md).

-   An administrator has downloadad and installed the required JDBC library in the <code><i class="varname">&lt;DPAgent_root&gt;</i>/camel/lib</code> folder and restarted the Data Provisioning Agent before registering the adapter with SAP Datasphere.




<a name="loio519b2dbc588940fb9698745e430c9859__prereq_df_Amazon_Redshift"/>

## Data Flows

Before you can use the connection for data flows, the following is required:

-   The outbound IP has been added to the source allowlist.

    For information on where a DW administrator can find the IP address, see [Finding SAP Datasphere IP addresses](finding-sap-datasphere-ip-addresses-0934f7e.md).

-   A DW administrator has uploaded the required ODBC driver file to SAP Datasphere.

    For more information, see [Upload Third-Party ODBC Drivers \(Required for Data Flows\)](upload-third-party-odbc-drivers-required-for-data-flows-b9b5579.md).


