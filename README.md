JEEWX-API  ΢�ż���SDK
===============
  ��JAVA����ͬʱ֧��΢�Ź��ں�\��ҵ΢��\֧����\С����\΢���ȣ�
===============
���°汾�� 1.2.2���������ڣ�20181106��
������[www.jeewx.com](http://www.jeewx.com) 



һ����Ŀ���ܣ�
-----------------------------------
 JEEWX-API �ǵ�һ��JAVA��΢�ż���SDK��������ҵ΢��SDK��֧����SDK��΢��SDK�����Կ��ٵĻ���������΢�Ź��ںš���ҵ΢�š�֧������΢��Ӧ�ÿ�����
 ���� jeewx-api ������������ӵ�м����õ�API���ÿ��������������磬��ʡ����ʱ�䡣


������������
-----------------------------------
* 	QQ����Ⱥ�� ��289709451
* 	������̳�� www.jeecg.org
* 	�����ĵ��� [http://jeewx-api.mydoc.io](http://jeewx-api.mydoc.io)



����Jeewx-api ���ɷ���
-----------------------------------
### [1].maven ��ʽ

	��һ���� ��ӹٷ��ֿ�
	 <repositories>
		<repository>
            <id>aliyun</id>
            <name>aliyun Repository</name>
            <url>http://maven.aliyun.com/nexus/content/groups/public</url>
            <snapshots>
				<enabled>false</enabled>
			</snapshots>
        </repository>
		<repository>
            <id>jeecg</id>
            <name>jeecg Repository</name>
            <url>http://maven.jeecg.org/nexus/content/repositories/jeecg</url>
            <snapshots>
				<enabled>false</enabled>
			</snapshots>
        </repository>
		<repository>
            <id>jeecg-snapshots</id>
            <name>jeecg-snapshots Repository</name>
            <url>http://maven.jeecg.org/nexus/content/repositories/snapshots</url>
            <snapshots>
				<enabled>true</enabled>
			</snapshots>
        </repository>
	</repositories>
	
    �ڶ����� ��pom.xml ���jeewx-api 1.2.2����
    <dependency>  
		<groupId>org.jeewx</groupId>  
		<artifactId>jeewx-api</artifactId>  
		<version>1.2.2</version>  
	</dependency>
	
### [2].��maven��ʽ
         ֱ�ӿ���jeewx-api-1.2.2.jar����ĿLib��
		 




�ġ����Դ���
-----------------------------------

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

	
### ���ں��塢С�����̳�

![github](http://www.jeecg.org/data/attachment/forum/201601/25/180314mjvputsot6hhtvoa.jpg "jeewx521")
![github](https://static.oschina.net/uploads/img/201810/15180859_25Ok.jpg "jeewx521")
    