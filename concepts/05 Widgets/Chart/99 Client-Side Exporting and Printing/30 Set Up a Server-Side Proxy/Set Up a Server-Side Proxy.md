If you need exporting and printing in browsers that do not provide an API for saving files (that is, in **Safari on Mac OS**), implement a server-side proxy that will stream the resulting file back to an end user in response to a POST request. The proxy implementation is different for each platform.