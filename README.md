# node-red-contrib-axios

An advanced HTTP request node for Node-RED, built on top of the [Axios](https://www.npmjs.com/package/axios) HTTP client.

[![npm version](https://img.shields.io/npm/v/node-red-contrib-axios.svg?style=flat-square)](https://www.npmjs.org/package/node-red-contrib-axios)  
[![install size](https://img.shields.io/badge/dynamic/json?url=https://packagephobia.com/v2/api.json?p=node-red-contrib-axios&query=$.install.pretty&label=install%20size&style=flat-square)](https://packagephobia.now.sh/result?p=node-red-contrib-axios)  
[![npm downloads](https://img.shields.io/npm/dm/node-red-contrib-axios.svg?style=flat-square)](https://npm-stat.com/charts.html?package=node-red-contrib-axios)  
[![Known Vulnerabilities](https://snyk.io/test/npm/node-red-contrib-axios/badge.svg)](https://snyk.io/test/npm/node-red-contrib-axios)

## Nodes included in this package

This package includes two nodes:

### HTTP Endpoint Configuration Node

Use this node to define base configurations for your HTTP endpoints—such as base URL, authentication, certificates, or proxy settings.  
This approach is especially powerful, as the configuration can be reused across multiple HTTP request nodes.

Supported authentication mechanisms:

- Basic Authentication  
- Bearer Token Authentication  
- API Key (via HTTP header or query parameter)

![axios-endpoint](https://raw.githubusercontent.com/csteinba/node-red-contrib-axios/master/examples/axios-endpoint.png)

### HTTP Request Node

Use this node within your flows to perform HTTP requests.

![axios-request](https://raw.githubusercontent.com/csteinba/node-red-contrib-axios/master/examples/axios-request.png)

## Example Flows

Check out this [basic example flow](https://github.com/csteinba/node-red-contrib-axios/blob/master/examples/basics.json) to get started.

Or learn how to use `multipart/form-data` with this [example flow](https://github.com/csteinba/node-red-contrib-axios/blob/master/examples/form-data.json).

![axios-flow](https://raw.githubusercontent.com/csteinba/node-red-contrib-axios/master/examples/axios-flow.png)

## Documentation

All node functionalities are thoroughly documented within the Node-RED editor.
