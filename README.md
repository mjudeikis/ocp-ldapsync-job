OCP-LDAPSync-Job
=========

Role to create LDAPSync-Job for Openshoft

Requirements
------------

Running openshift cluster

Role Variables
--------------

openshift_ldapsync_serviceaccount: ldapsync
openshift_ldapsync_namespace: openshift-infra
openshift_ldapsync_configmap_name: ldapsync-config
openshift_ldapsync_schedule: "*/60 * * * *"
openshift_config_dir: /etc/origin/master/artifacts


Author Information
------------------

Mangirdas Judeikis m.j@redhat.com
