jaxb2-maven-plugin 1.x���ܽ᣺

1��ͨ��maven����java������schema�ļ���
		mvn jaxb2:schemagen
2��ͨ��mave����schema�ļ�����java��
		mvn jaxb2:xjc
3��ʹ�����mvn jaxb2:schemagen��ʱ��includes�ڵ�Ϊ������
4��ʹ�����mvn jaxb2:xjc��ʱ��schemaDirectory�ڵ�Ϊ������
5��ʹ�����mvn jaxb2:schemagen������schema�ļ�ʱ������javaClass���Ƿ���JAXB��׼ע�⣬�����������