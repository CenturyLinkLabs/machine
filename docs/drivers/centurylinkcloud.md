### CenturyLink Cloud
Create machines on [CenturyLink Cloud](http://www.centurylinkcloud.com). The same username and password you use to access the CenturyLink Cloud console is required during server creation.

Options:

 - `--centurylinkcloud-username`: **required** CLC username
 - `--centurylinkcloud-password`: **required** CLC password
 - `--centurylinkcloud-group-id`: **required** Group ID. The group the server will be created in. This will also determine the datacenter. If you do not have a group, you must create one. The ID can be determined by looking at the last segment of the URL when viewing the group in the control panel, e.g. `f1329903893b437e91613ffc33fd6fbf`.
 - `--centurylinkcloud-source-server-id`: A template ID or the ID of an existing server to use when creating. It will otherwise default to the Ubuntu template.
 - `--centurylinkcloud-network-id`: An optional network ID for the created machine to join. Networks are unique to your account per datacenter. More information on finding your network IDs can be [found here](https://www.ctl.io/api-docs/v2/#data-centers-get-data-center-deployment-capabilities).
 - `--centurylinkcloud-cpu`: The number of CPUs for the created instance.  Defaults to 1.
 - `--centurylinkcloud-memory-gb`: The amount of RAM in GB for the created server. Defaults to 2.
