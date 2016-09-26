appcanary.agent
=========

Set up the [Appcanary](https://appcanary.com) agent.

Requirements
------------

You must have an [appcanary](https://appcanary.com) account and the API key provided by it.

Role Variables
--------------

- `api_key`: Your appcanary api key
- `monitored_files`: A list of paths monitored 


Example Playbook
----------------
    
    - hosts: servers
      roles:
         - { role: appcanary.agent, api_key: "MYAPIKEYHERE", monitored_files: ["/path/to/my/Gemfile.lock", "/path/to/another/Gemfile.lock"] }

License
-------

GPLv3

Author Information
------------------

Contact us at [hello@appcanary.com](mailto:hello@appcanary.com)
