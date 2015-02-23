# Sentora SSO Module

This module has been developed and is maintained by [Supared](http://supared.com); The module enables you to implement token based single sign-on to your [Sentora Control Panel](http://sentora.org). This is a great module if you wish to build a centralised client panel and want to implement single sign-on functionality.

You can also check out our [SSO PHP client](https://github.com/supared/sentora-sso-client) in order to generate SSO tokens and login buttons/links in your PHP projects etc.

## License

This tool is released under the [GPL v2 license](LICENSE).

## Requirements

This module will work on Sentora version 1.0.1+ and upwards.

## Installation

You can install the SSO module by logging into your server and running the following commands:

Firstly, you need to add the Supared module repository (unless you already have it added):

```
zppy repo add zppy.supared.com
zppy update
```

Then install the package like so:

```
zppy install sso
```

Now that you have it install, go and activate the module in the Sentora Module Admin and then go to ```Admin > SSO Config`` and set your own encryption key and IV (initiation vector).

## Support

Premium support is provided by [Supared Limited](http://supared.com). If you would like consultancy/development services to implement this into your existing solution please contact us at: hello@supared.com
