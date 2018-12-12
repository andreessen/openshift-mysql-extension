## Example project to extend base mysql image
### Deploy project via oc CLI

#### Basic project creation
-----------
To create app:
```
$ git clone https://github.com/andreessen/openshift-mysql-extension
$ cd wso2apim-openshift-example/
$ oc create -f fmysql.yaml
$ oc new-app mysql-ext -p APP_NAME=mysql-ext
```
This template shows how to extend base image and how to use hooks in Openshift.
