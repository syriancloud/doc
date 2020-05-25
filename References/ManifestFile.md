
# Web App Manifest
W3C Working Draft 30 March 2020

### Abstract
This specification defines a JSON-based manifest file that provides developers with a centralized place to put metadata associated with a web application. This metadata includes, but is not limited to, the web application's name, links to icons, as well as the preferred URL to open when a user launches the web application. The manifest also allows developers to declare a default orientation for their web application, as well as providing the ability to set the display mode for the application (e.g., in fullscreen). Additionally, the manifest allows a developer to "scope" a web application to a URL. This restricts the URLs to which the manifest is applied and provides a means to "deep link" into a web application from other applications.

Using this metadata, user agents can provide developers with means to create user experiences that are more comparable to that of a native application.

This specification also defines the manifest link type as a declarative means to associate a document with a manifest.

**NOTE:** manifest.webmanifest or manifest.json?
 >   The official file extension for the manifest is .webmanifest. Some web servers recognize this extension and transfer the file using the standardized MIME type for a manifest (application/manifest+json). Developers can also choose a different extension (e.g. .json) or none at all (e.g. /api/GetManifest), but are strongly encouraged to transfer the manifest using the application/manifest+json MIME type.

https://www.w3.org/TR/appmanifest
https://developer.mozilla.org/en-US/docs/Web/Manifest
https://dev.opera.com/extensions/manifest
https://app-manifest.firebaseapp.com
https://web.dev/progressive-web-apps