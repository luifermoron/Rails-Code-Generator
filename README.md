
From a empty Rails project generated, this rails code generator can generate:
  * Models with Associations
  * Controllers
  * Views wiht material design
  * Gem file with some usefull gems
  * Migrations files

Prerequisites
* Watch "Ruby on Rails Code Generator - [Eclipse - Maven - Acceleo - Cloud9]" video of Camilo Benavides from the follow link:
  https://www.youtube.com/watch?v=x14ZnQhR3r0&t=89s
* Eclipse Neon needs to be installed
* Ask for miniuml project of Camilo Benavides

Usage
1.- Replace the generate.mtl(/src/miniuml/generator/main/) file from this project to miniuml.generator/src/miniuml/generator/main/ project
2.- Generate a rails application with:
      rails new projectname
3.- As the 1:51 from the video, you can create primitive types with the following values:
      belongs_to
      has_many
      integer
      string
      date
      boolean
      float
      datetime
      time
4.- Create classes as seen in the video(2:35).       
    Considerations
    4.1 Parent property is not supported. 
    4.2 belongs_to and has_many primitive types are only for associations
    4.3 When you create a property either belongs_to or has_many the value of the name must be exactly what class you want to be associated
    4.4 If you want to associate models, in your class, first create all belongs_to Attributes and then all has_many Attributes.
 5.- Execute the project as seen in the video.
 Consideration
 To run the migration files, please change the name of them sorted in order to not have problems.
 
 Note.-
 The BootstrapFormBuilder class and javascript and css files are from Ecommerce - Codigo Facilito course.
 
      
