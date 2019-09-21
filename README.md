# zabbix template for Adobe Experience Manager 6.x (AEM)
-----------------------

1. Configure AEM to expose JMX
  JMX_OPTS='-Dcom.sun.management.jmxremote -Dcom.sun.management.jmxremote.authenticate=false -Dcom.sun.management.jmxremote.port=5502 -Dcom.sun.management.jmxremote.ssl=false'
  CQ_JVM_OPTS="${CQ_JVM_OPTS} ${JMX_OPTS}"
2. Import template to zabbix 
3. Add the template to the AEM host
  and set the JMX host/port on the AEM instance




Required:
  zabbix-java-gateway
  
