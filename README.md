# my-idp 
It is developed based on keycloak-services-social-weixin(https://gitee.com/jyqq163/keycloak-services-social-weixin.git) and github idpin keycloak.

to install the idp :

* Add the jar to the Keycloak server:
  * `$ cp target/*.jar _KEYCLOAK_HOME_/providers/`

* Add  templates to the Keycloak server:
  * `$ cp templates/realm-identity-provider-mygithub-ext.html _KEYCLOAK_HOME_/themes/base/admin/resources/partials`
  * `$ cp templates/realm-identity-provider-mygithub.html _KEYCLOAK_HOME_/themes/base/admin/resources/partials`
  

* 20190318
1 实现与CAS v5.3.7的oauth 2.0对接。
