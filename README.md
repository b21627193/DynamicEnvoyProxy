# DynamicEnvoyProxy

This repository presents an envoy proxy that handles dynamic configuration by using a control plane. 

For more information about Envoy: https://www.envoyproxy.io/

Taking the controller that is created by Steve Sloka, I made a basic sample by containerizing it.

xds-server: https://github.com/stevesloka/envoy-xds-server

There is just a basic docker-compose file.

# Start

Build and run containers:

``` docker-compose up ```

For update messages, just change the config file in the xdsserver container:

``` nano config/config.yaml ```
