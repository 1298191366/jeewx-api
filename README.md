JEEWX-API  ΢�ſ���SDK
===============

  
���°汾�� 1.3.2���������ڣ�20220902��
������[www.jeecg.com](http://www.jeecg.com) 



��Ŀ����
-----------------------------------
 JEEWX-API ��һ��JAVA���΢�ſ���SDK��֧��΢�Ź��ںš�С����΢����ҵ�š�֧���������SDK��΢��SDK������Ի����������ٵ�ɵ�ϻ��Ľ���΢�ſ�����֧������΢��������
 ����jeewx-api��������������ӵ�м����õ�API���ÿ��������������磬��ʡ����ʱ�䡣


��������
-----------------------------------
* 	������̳�� www.jeecg.org
* 	�����ĵ��� [http://jeewx-api.mydoc.io](http://jeewx-api.mydoc.io)
* 	API�ĵ��� [http://www.jeewx.com/jeewx-api](http://www.jeewx.com/jeewx-api)



Jeewx-Api ���ɷ���
-----------------------------------
### [1].maven ��ʽ
    ��pom.xml ���jeewx-api 1.3����
    <dependency>
		<groupId>org.jeecgframework</groupId>
		<artifactId>jeewx-api</artifactId>
		<version>1.3.2</version>
	</dependency>
	
### [2].��maven��ʽ
         ֱ�ӿ���jeewx-api-1.3.2.jar����ĿLib��
		 




API����
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