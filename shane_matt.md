
[Watch the Video Here](https://www.youtube.com/watch?v=PX_a55ghVLs)

**Power Platform Best Practices**

1. **Data Sources**: The choice of data source is crucial for the performance and functionality of your Power Platform applications. Dataverse is recommended for most scenarios due to its robust security and sharing capabilities. However, SharePoint is considered better than Dataverse for Teams due to its flexibility and ease of use. Excel is considered the least preferred option due to its limitations.

2. **Document Libraries**: SharePoint document libraries are recommended for storing files due to their versioning and version control capabilities. They are also easily accessible and can provide a complete user experience with files.

3. **Many-to-Many Relationships**: In Dataverse, it's recommended to manually build a many-to-many table instead of using the out-of-the-box many-to-many relationship. This allows you to add extra information about the relationship, such as results or grades.

4. **Responsive Apps**: While responsive apps can be useful, they can also be challenging to implement effectively across all devices and screen sizes. It's often more efficient to build separate apps optimized for specific devices or use cases.

5. **Containers**: Containers are useful for formatting and layout in Power Apps. They can be used to place things on top of each other, float things, and easily show and hide groups of controls.

6. **Co-Pilot Features**: The new co-pilot features in Power Apps can be useful for new users or for quickly creating mock-ups and proof of concepts. They can also help with tasks like generating HTML or documenting apps.

**Building Apps**

1. **Custom Themes**: The ability to define a custom theme for your app can greatly enhance its appearance and user experience. This would allow you to set global styles and colors, and then override them as needed within individual controls.

2. **File Handling**: Uploading a file within Power Apps should be made easier. Currently, it requires a significant amount of effort to implement file upload functionality.

3. **Targeted Apps**: Instead of trying to build one app that works for all users and processes, it's often more effective to build targeted, specific apps that are optimized for specific user groups or tasks.

**Tips & Tricks**

1. **Avoid Storing Files in SQL Server**: Storing files directly in SQL Server can lead to poor performance and is generally not recommended.

2. **Avoid Using Attachments in SharePoint Lists**: Using attachments in SharePoint lists can lead to complications and is generally not recommended. Instead, store files in a document library and create a link to them.

3. **Use Containers for Non-Responsive Scenarios**: Containers can be useful for formatting and layout, even in non-responsive scenarios. They can help make your apps look better and more organized.

4. **Use Co-Pilot Features for Mock-Ups and Proof of Concepts**: The new co-pilot features in Power Apps can be useful for quickly creating mock-ups and proof of concepts, even if you're an experienced maker.

5. **Consider User Experience When Designing for Multiple Devices**: When designing apps for multiple devices, consider how users interact with each device. For example, users may prefer menus at the bottom of the screen on mobile devices, but at the top or side on desktop devices.
