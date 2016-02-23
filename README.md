# MultilingualDemo
Globalization is the process of preparing your site so that it is accessible to as wide an audience as possible.

ASP.NET already provides a localization framework, which is based on Cultures and Resources. Web Pages have a Culture property and a UICulture property. 

you have one resource file which represents the default culture for the site. You need additional resource files for other languages. These need to be named carefully, as the framework expects to find valid culture codes as part of the file name.

I have added two resourse file 1. English 2. Hindi 
Our application should use added resource files instead of hard coded values. For that, I have added a class library with resources files for each language. 

On selection of language, I am setting culture and retreived value as per language from resource files.

When we implement globalization, it is important to follow standard design guidelines . Because each culture may utilize different size of the screen.

### We may take care 
1. No absolute positioning of controls
2. Use fluid layout with forms
3. No absolute size of controls
4. Try to arrange controls in a table.
