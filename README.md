JEEWX-API  ΢�ſ���SDK
===============

  
���°汾�� 1.5.2���������ڣ�20231215��

[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://github.com/zhangdaiscott/jeecg-boot/blob/master/LICENSE)
[![](https://img.shields.io/badge/Author-�����������-orange.svg)](http://jeecg.com/aboutusIndex)
[![](https://img.shields.io/badge/Blog-�ٷ�����-blue.svg)](https://jeecg.blog.csdn.net)
[![](https://img.shields.io/badge/version-1.9.5-brightgreen.svg)](https://github.com/zhangdaiscott/jeecg-boot)
[![GitHub stars](https://img.shields.io/github/stars/zhangdaiscott/jeecg-boot.svg?style=social&label=Stars)](https://github.com/zhangdaiscott/jeecg-boot)
[![GitHub forks](https://img.shields.io/github/forks/zhangdaiscott/jeecg-boot.svg?style=social&label=Fork)](https://github.com/zhangdaiscott/jeecg-boot)



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