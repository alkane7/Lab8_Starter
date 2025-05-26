# Lab8-Starter

Wanting Li

### How are graceful degradation and service workers related?
Graceful degradation is a design strategy where an application continues to function with reduced capabilities when advanced features are not supported by the browser. Service workers enhance graceful degradation by enabling features like offline access and caching. If a browser does not support service workers, the website still loads and works—just without those enhancements. This ensures the core functionality remains accessible, even in less capable environments.