# console

Tries to configure the console plugin with grails 4

Based on this plugin: https://github.com/sheehan/grails-console

## Steps

Run the app

    gradlew bootRun -Dgrails=dev

Go here:

    http://localhost:8080/console
    
## Enabling the plugin on other environments

Add the following configuration in application.yml: grails.plugin.console.enabled: true
Don't forget to ensure that your console is protected from any suspicious access.