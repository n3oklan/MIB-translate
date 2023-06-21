# MIB-translate
Převod souborů MIB do šablon Zabbix -> .MIB na .XML:

snmptranslate -Tz -m ./soubor.mib | ./mib2zabbix -o .1.3.6.1.4.1 -f sablona-soubor.xml -N jmeno_sablony
