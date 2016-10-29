jaxb2-maven-plugin 1.x版总结：

1、通过maven，将java类生成schema文件：
		mvn jaxb2:schemagen
2、通过mave，将schema文件生成java类
		mvn jaxb2:xjc
3、使用命令“mvn jaxb2:schemagen”时，includes节点为必填项
4、使用命令“mvn jaxb2:xjc”时，schemaDirectory节点为必填项
5、使用命令“mvn jaxb2:schemagen”生成schema文件时，不管javaClass中是否有JAXB标准注解，都会进行生成