### Can unauthenticated users order items in the Service Catalog using Service Portal?
No. Service Catalog ordering depends on an AngularProcessor transaction that currently requires documentation. Unauthenticated users will be allowed to see Catalog items, but ordering will not work as expected.

### Are Order Guides supported?
Yes. Order Guides are supported on the sc_cat_item_guide page.

### Are Catalog Client Scripts supported? How can I make them work?
Service Portal only executes client scripts with the UI Type of "Both" or "Mobile". Read more about what's supported and what's not in the Mobile client scripting runtime here: http://wiki.servicenow.com/index.php?title=Mobile_Client_GlideForm_(g_form)_Scripting#gsc.tab=0 

### Is there a “Copy Portal” functionality similar to what we have for CMS?
Unfortunately not. We have a tool for copying widgets, but nothing for pages or portals at the moment. It shouldn't be too difficult to manually copy what you need though, portals are easy to build up and you rarely want a full copy anyway.

### Can I use widgets out of the Service Portal?
No. Widgets depend on the Service Portal Framework to render. 

### I have a question about something, but it isn't documented anywhere. What do I do?
Create an issue on this repository and we'll check it out! We want the best coverage we can manage, so if there is anything we're missing, please let us know.

PLEASE NOTE: Only create issues in this repository for documentation problems. For issues with the Service Portal framework, please create an incident on HI and the Service Portal team will investigate from there.

### I've written a bit of documentation myself, can I contribute to this project?
Of course! We love having help. Create a pull request with your updates and somebody on the documentation team will check it out.

