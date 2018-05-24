FROM atlassian/confluence-server
MAINTAINER whb
ADD  atlassian-extras-decoder-v2-3.3.0.jar ${CONFLUENCE_INSTALL_DIR}/confluence/WEB-INF/lib/
ADD  mysql-connector-java-5.1.46.jar ${CONFLUENCE_INSTALL_DIR}/confluence/WEB-INF/lib/
RUN chown -R ${RUN_USER}:${RUN_GROUP} ${CONFLUENCE_INSTALL_DIR}/confluence/WEB-INF/lib/atlassian-extras-decoder-v2-3.3.0.jar
#docker push registry.cn-shenzhen.aliyuncs.com/kye/confluence-server:6.8.2
