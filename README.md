JEEWX-API  ΢�ż���SDK
===============
  ��JAVA����ͬʱ֧��΢�Ź��ں�\��ҵ΢��\֧����\С����\΢���ȣ�
===============
���°汾�� 1.3���������ڣ�20190604��
������[www.jeewx.com](http://www.jeewx.com) 



һ����Ŀ���ܣ�
-----------------------------------
 JEEWX-API �ǵ�һ��JAVA��΢�ż���SDK��������ҵ΢��SDK��֧����SDK��΢��SDK�����Կ��ٵĻ���������΢�Ź��ںš���ҵ΢�š�֧������΢��Ӧ�ÿ�����
 ���� jeewx-api ������������ӵ�м����õ�API���ÿ��������������磬��ʡ����ʱ�䡣


������������
-----------------------------------
* 	QQ����Ⱥ�� 287090836
* 	������̳�� www.jeecg.org
* 	�����ĵ��� [http://jeewx-api.mydoc.io](http://jeewx-api.mydoc.io)



����Jeewx-api ���ɷ���
-----------------------------------
### [1].maven ��ʽ
    ��pom.xml ���jeewx-api 1.3����
    <dependency>
		<groupId>org.jeecgframework</groupId>
		<artifactId>jeewx-api</artifactId>
		<version>1.3</version>
	</dependency>
	
### [2].��maven��ʽ
         ֱ�ӿ���jeewx-api-1.3.jar����ĿLib��
		 




�ġ�API����
-----------------------------------

    public static void main(String[] args) {
		try {
			String accesstoken = "?";
			String user_openid = "o8QKAuAyDxxfyuBZ9ugSMR4SR5XQ";
			JwUserAPI.getWxuser(accesstoken, user_openid);
		} catch (WexinReqException e) {
			// TODO Auto-generated catch block
			e.printStackTrace();
		}
		
	}