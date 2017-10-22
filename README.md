flink ansible
=========


Requirements
------------

Role Variables
--------------
```
flink_version: 1.3.2
scala_version: 2.11
hadoop_version: 27
flink_version_folder_name: "flink-{{flink_version}}"
flink_tar_file_name: "flink-{{flink_version}}-bin-hadoop{{hadoop_version}}-scala_{{scala_version}}.tgz"
flink_download_url: "http://www-eu.apache.org/dist/flink/flink-{{flink_version}}/{{flink_tar_file_name}}"
flink_home: /app/flink
flink_install_dir: "/app"
flink_role: jobmanager ## or taskmanager
JAVA_HOME: "/app/jdk1.8.0_92"
```

Dependencies
------------

JAVA_HOME

Example Playbook
----------------

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
