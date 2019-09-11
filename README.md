SET foreign_key_checks = 0;
UPDATE `apimgtdb`.`idn_oauth_consumer_apps` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa', `CONSUMER_SECRET` = 'k1WCE2oKiXvXW6HXCZHRI5fsCZga' WHERE (`ID` = '1');
UPDATE `apimgtdb`.`idn_oidc_property` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '1');
UPDATE `apimgtdb`.`idn_oidc_property` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '2');
UPDATE `apimgtdb`.`idn_oidc_property` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '3');
UPDATE `apimgtdb`.`idn_oidc_property` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '4');
UPDATE `apimgtdb`.`idn_oidc_property` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '5');
UPDATE `apimgtdb`.`idn_oidc_property` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '6');
UPDATE `apimgtdb`.`am_application_key_mapping` SET `CONSUMER_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`APPLICATION_ID` = '2') and (`KEY_TYPE` = 'PRODUCTION');
UPDATE `apimgtdb`.`sp_inbound_auth` SET `INBOUND_AUTH_KEY` = 'fQlMQzYmXkuG49jnEsP2VpyLBToa' WHERE (`ID` = '19');

SET foreign_key_checks = 1;
