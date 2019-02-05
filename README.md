# CSS and a PNG that can be used by OpenShift to customize its logo in the console

## Installation Instructions for OCP 3.9+
[Post-Install OCP Documentation](https://docs.openshift.com/container-platform/3.4/install_config/web_console_customization.html#customizing-the-logo)


### Pre-Install OCP Documentation

Add this to the hosts file

```
# Configure extension stylesheets for web console customization
# https://docs.openshift.com/enterprise/latest/install_config/web_console_customization.html#loading-custom-scripts-and-stylesheets
#
openshift_web_console_extension_stylesheet_urls=['https://raw.githubusercontent.com/vincepower/ocp-console-logo/master/azure.css']
```

## Azure

```
CSS: https://raw.githubusercontent.com/vincepower/ocp-console-logo/master/azure.css
Image: https://raw.githubusercontent.com/vincepower/ocp-console-logo/master/azure.png
```

## Other clouds will be added as required
