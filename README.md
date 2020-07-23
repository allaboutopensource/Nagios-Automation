Playbook for setting up the Nagios agent on the Linux clients (CentOS/RHEL/) and add them to the monitoring in Nagios via the API.

There are several ways to automate Nagios XI but I am using the API method which could be faster then the other ways of automating Nagios.

In this case I am using the automation software as ansible but you can feel free to use other as well.

Normally most of the organisation uses software like Bigfix and other to push the agents to the client. 

You need to mention the variable (vars) in the yaml. Nagios-XI IP address and api_key.

Depending on your needs you need to edit the host files as well.

After that you need to run the script name nagiosautomate.yml using the below command:
    
    ansible-playbook nagiosautomate.yml -i hosts
