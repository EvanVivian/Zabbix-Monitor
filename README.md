# Zabbix-Monitor zabbix ��ط���

˵����
1��zabbix_mysql     ���mysql(�汾��5.5.42)�ĸ�����ֵ
   ��  zbx_export_templates.xml     ģ���ļ�
   ��
   ����conf
   ��      zabbix_agentd.conf       ��Ӽ�ؽű�����
   ��
   ����script
           getmysqlinfo.sh         ��ؽű�������Ĳ���������Ҫ�޸�
           
           
2��zabbix_redis      ���redis(�汾��2.8.24) �Զ����֣��Զ�����items
   ��  zbx_export_templates.xml      ģ���ļ�
   ��
   ����conf
   ��      zabbix_agentd.conf        ��Ӽ�ؽű�����    
   ��
   ����script
          redisdbports.sh           �Զ����ֽű�
          redismonitor.sh           ��ؽű�������Ĳ���������Ҫ�޸�

