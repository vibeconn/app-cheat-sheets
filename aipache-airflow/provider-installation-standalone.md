So, you are looking for creating connection in the Connections options Of Admin module. You want to create a connection but do not see your provider. The dummy connections that already exist show **Email** as their connection type and you want to change it. \
To get the right provider in your connection type selection, you need to install the provider.  \
This document describes the flow for standalone mode(dev/local) environments only. 
1. The install a connector, for example postgres, you need to install the plugin first from pip ```pip install apache-airflow-providers-postgres``` .  
2. After you are done installing the connector, restart your airflow instance, ```airflow standalone``` and you should see your connector in connection type drop down.
