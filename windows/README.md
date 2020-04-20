1] If you are using ConfigureWindows.yml to configure newly created windows system, Make sure that your host/group vars should be as follows :

ansible_user: Administrator
ansible_password: <password>
ansible_connection: winrm
ansible_winrm_transport: ntlm
ansible_port: 5985
ansible_winrm_server_cert_validation: ignore

2] Run the ConfigureWindows.yml and now your windows system is able to managed by control node.
