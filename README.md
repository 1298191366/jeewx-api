JEEWX-API  ΢�ſ���SDK
===============

  
���°汾�� 1.4.9���������ڣ�20220902��

 > �������⣺����bug����github [��issue](https://github.com/jeecgboot/jeewx-api/issues/new)


��Ŀ����
-----------------------------------
 JEEWX-API ��һ��JAVA���΢�ſ���SDK��֧��΢�Ź��ںš�С����΢����ҵ�š�֧���������SDK��΢��SDK������Ի����������ٵ�ɵ�ϻ��Ľ���΢�ſ�����֧������΢��������
 ����jeewx-api��������������ӵ�м����õ�API���ÿ��������������磬��ʡ����ʱ�䡣


��������
-----------------------------------
* 	���������� www.jeecg.com
* 	�����ĵ��� [http://jeewx-api.mydoc.io](http://jeewx-api.mydoc.io)
* 	API�ĵ��� [http://www.jeewx.com/jeewx-api](http://www.jeewx.com/jeewx-api)



Jeewx-Api ���ɷ���
-----------------------------------
### [1].maven ��ʽ
    ��pom.xml ���jeewx-api 1.3����
    <dependency>
		<groupId>org.jeecgframework</groupId>
		<artifactId>jeewx-api</artifactId>
		<version>1.4.9</version>
	</dependency>
	
### [2].��maven��ʽ
         ֱ�ӿ���jeewx-api-*.jar����ĿLib��
		 




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