JEEWX-API  ΢�ż���SDK
===============
  ��һ��JAVA�汾΢��SDK��������ҵ΢��SDK��֧����SDK��
===============
���°汾�� 1.2.0���������ڣ�20180403��
������[www.jeewx.com](http://www.jeewx.com) 


һ����Ŀ���ܣ�
-----------------------------------
 JEEWX-API �ǵ�һ��JAVA��΢�ż���SDK��������ҵ΢��SDK��֧����SDK�����Կ��ٵĻ���������΢�Ź��ںš���ҵ΢�š�֧����Ӧ�ÿ�����
 ���� jeewx-api ������������ӵ�м����õ�API���ÿ��������������磬��ʡ����ʱ�䡣


�����ӿڹ����嵥
-----------------------------------
*   �����ĵ��� [�ӿ�WIKI](http://wiki.jeecg.org/pages/viewpage.action?pageId=7110659)


����Jeewx-api ���ɷ���
-----------------------------------
### [1].maven ��ʽ
    ��pom.xml ���jeewx-api 1.2.0����
	(���������˽������ο����ӵ�5.2�ų�jeecg��˽������Ȼ���������ʧ�ܵ������ https://blog.csdn.net/zhangdaiscott/article/details/50915206 )

    <dependency>  
		<groupId>org.jeewx</groupId>  
		<artifactId>jeewx-api</artifactId>  
		<version>1.2.0</version>  
	</dependency>
	
### [2].��maven��ʽ
         ֱ�ӿ���jeewx-api-1.2.0.jar����ĿLib��
		 
### [3].����ʾ��

    public static void main(String[] args) {
		try {
			String accesstoken = "yALYWcUbB1hdURQvJ-Qn1jbyq5E0qNraZixnxhC1wtN5sKrAfHifyFHHpRWiUnZ1xnhjN_dcnYqFAgpJqeJJybx2NOVoEDZd7SFLjwFIvM8AJv3a8EGarbY0jo--4vuqUNNhADAQJJ";
			String user_openid = "o8QKAuAyDxxfyuBZ9ugSMR4SR5XQ";
			JwUserAPI.getWxuser(accesstoken, user_openid);
		} catch (WexinReqException e) {
			// TODO Auto-generated catch block
			e.printStackTrace();
		}
		
	}
    

	
�ġ���������
-----------------------------------
* 	QQ����Ⱥ�� ��289709451
* 	������̳�� www.jeecg.org



�塢���ο�������
-----------------------------------

![github](https://camo.githubusercontent.com/e196c5829ef14d25d30ee24ce81bfb6e0dfb49a4/687474703a2f2f7777772e6a656563672e6f72672f646174612f6174746163686d656e742f666f72756d2f3230313630362f32372f3132333530347936397276397a7178776576767636362e706e67 "jeewx")
![github](https://camo.githubusercontent.com/7caeaa7c2d8e3f13bf40f3adb22a3c19213b8289/687474703a2f2f7374617469632e6f736368696e612e6e65742f75706c6f6164732f73706163652f323031362f303432342f3133313130355f42536c4e5f3933303839382e706e67 "jeewx")


    