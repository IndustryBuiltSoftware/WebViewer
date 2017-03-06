# WebViewer
A simple web viewer part that can be added to a page or role center to allow inline viewing of secure web URLs. The general idea is that you add the web viewer part to a role center and from there, a user can access one or more URLs directly from their role center.

One thing that can be done when your extension is installed, is to assign some URLs to specific roles so that you can intriduce users more easily to different concepts (eg. sample Power BI site) that otherwise might be complex for new users to setup.

As this uses the standard Dynamics NAV 2017 web viewer component, only HTTPS urls are supported.

Features
- URLS are created for specific role centers
- User able to show/hide web viewer if not in an evaluation company
- Users able to expand the web viewer part to view as a "fullscreen" view

This example includes the Business Manager role center that as already been modified to include the web viewer part.
