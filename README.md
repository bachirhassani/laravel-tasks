---
languages:
- php
page_type: sample
description: "This is a sample application that you can use to follow along with the Build a PHP and MySQL web app in Azure tutorial."
products:
- azure
- azure-app-service
---

# Laravel sample for Azure App Service

This is a sample application that you can use to follow along with the tutorial at 
[Build a PHP and MySQL web app in Azure](https://docs.microsoft.com/azure/app-service/tutorial-php-mysql-app?pivots=platform-linux).

This sample application is taken from the official [Laravel sample task list application](https://github.com/laravel/quickstart-basic) and modified minimally to make it work with Azure App Service. For instructions on how to use Laravel, see the official repository.

For MySQL version 8.0 and above, Generated Invisible Primary Keys(GIPK) is enabled by default for all the Azure Database for MySQL Flexible Servers.

Disabling GIPK fixes the issue, and to do so follow the following steps:

    Sign in to the Azure portal, then locate your Azure Database for MySQL - Flexible Server.

    Under the SETTINGS section, click Server parameters to open the server parameters page for the Azure Database for MySQL - Flexible Server.

    Search for sql_generate_invisible_primary_key and update it to off.

Source: https://learn.microsoft.com/en-us/azure/mysql/flexible-server/concepts-limitations#generated-invisible-primary-keys


## License

See [LICENSE](LICENSE).

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
  
