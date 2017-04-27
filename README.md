


************************************************************************************************************************

https://github.com/levimodesto/wso2-squirrel.3.7.1/blob/master/lib/squirrel-sql-3.7.1-standard.jar

execução linux 
java -jar  squirrel-sql-3.7.1-standard.jar

************************************************************************************************************************



Configurar com o arquivo h2-1.4.194.jar 

(https://github.com/levimodesto/wso2-squirrel.3.7.1/blob/master/lib/h2-1.4.194.jar)


************************************************************************************************************************
************************************************************************************************************************
                                       Configuração WSO2 API 2.1.0
************************************************************************************************************************
************************************************************************************************************************


************************************************************************************************************************
                                                      WSO2AM_DB
************************************************************************************************************************

configurar Banco H2 (WSO2AM_DB)

Name: WSO2AM_DB

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2AM_DB  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2AM_DB  (pasta H2 em seu projeto - Linux)
userNAme: wso2carbon

pass: wso2carbon 


************************************************************************************************************************
                                                      WSO2CARBON_DB
************************************************************************************************************************


configurar Banco H2 (WSO2CARBON_DB)

Name:WSO2CARBON_DB

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2CARBON_DB  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2CARBON_DB  (pasta H2 em seu projeto - Linux)


userNAme: wso2carbon

pass: wso2carbon 

************************************************************************************************************************
                                                      WSO2MB_DB
************************************************************************************************************************

configurar Banco H2 (WSO2MB_DB)

Name:WSO2MB_DB

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2MB_DB  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2MB_DB  (pasta H2 em seu projeto - Linux)

userNAme: wso2carbon

pass: wso2carbon 



************************************************************************************************************************
                                                      WSO2METRICS_DB
************************************************************************************************************************


configurar Banco H2 (WSO2METRICS_DB)

Name:WSO2METRICS_DB

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2METRICS_DB  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-2.1.0/repository/database/WSO2METRICS_DB  (pasta H2 em seu projeto - Linux)

userNAme: wso2carbon

pass: wso2carbon 

************************************************************************************************************************


########################################################################################################################



************************************************************************************************************************
************************************************************************************************************************
                                       Configuração WSO2 API Manager 2.1.0
************************************************************************************************************************
************************************************************************************************************************


************************************************************************************************************************
                                                      ANALYTICS_EVENT_STORE
************************************************************************************************************************

configurar Banco H2 (ANALYTICS_EVENT_STORE)

Name: ANALYTICS_EVENT_STORE

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/ANALYTICS_EVENT_STORE  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/ANALYTICS_EVENT_STORE  (pasta H2 em seu projeto - Linux)

userNAme: wso2carbon

pass: wso2carbon 



************************************************************************************************************************
                                                      ANALYTICS_PROCESSED_DATA_STORE
************************************************************************************************************************

configurar Banco H2 (ANALYTICS_PROCESSED_DATA_STORE)

Name: ANALYTICS_PROCESSED_DATA_STORE

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/ANALYTICS_PROCESSED_DATA_STORE  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/ANALYTICS_PROCESSED_DATA_STORE  (pasta H2 em seu projeto - Linux)

userNAme: wso2carbon

pass: wso2carbon 



************************************************************************************************************************
                                                      WSO2CARBON_DB
************************************************************************************************************************

configurar Banco H2 (WSO2CARBON_DB)

Name: WSO2CARBON_DB

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/WSO2CARBON_DB  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/WSO2CARBON_DB  (pasta H2 em seu projeto - Linux)

userNAme: wso2carbon

pass: wso2carbon 


************************************************************************************************************************
                                                      WSO2METRICS_DB
************************************************************************************************************************

configurar Banco H2 (WSO2METRICS_DB)

Name: WSO2METRICS_DB

Driver: H2

URL: jdbc:h2:C:/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/WSO2METRICS_DB  (pasta H2 em seu projeto - Windows)
URL: jdbc:h2:/opt/wso2-6.0/api/wso2am-analytics-2.1.0/repository/database/WSO2METRICS_DB  (pasta H2 em seu projeto - Linux)

userNAme: wso2carbon

pass: wso2carbon 


************************************************************************************************************************
