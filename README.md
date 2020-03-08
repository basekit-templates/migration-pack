# migration-pack
Site import to help speed up the process of creating testing sites for migration.


### Steps

1. Clone or download this repo
2. Create a new site by importing the **site.zip** file
3. Login to the site and upgrade directly to V10
4. Fill in all the profile data in the settings panel *(A logo can be found in the images folder)*
5. Import blog posts by using the **blog.xml** file *(Make sure to select the checkbox below the import field to publish the posts)* and change the blog visibility to 'Online'
6. Create a store and import products using the **store.csv** file *(Make sure to publish your store)*


### Pages

Homepage - Includes all draggable widgets on one page in the main zone (home.twig)

About - Includes all draggable widgets inside columns within a main zone (default.twig)

Sections > Widgets in sections - Includes all draggable widgets within a row

Sections Folder - Includes pages which include all current sections available in V10
