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

![github](http://img.blog.csdn.net/20180309122145466 "jeewx")
![github](http://img.blog.csdn.net/20160323154916164?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center "jeewx")


    