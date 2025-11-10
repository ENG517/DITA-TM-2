# DITA Topic Model - Enter Title Here

This repo contains a DITA topic model (TM) ...

## Authors

- Wyatt Blanchette, Madelyn Kenney, Deanna Kolski

## Project Maps

### User Scenario 1: ...

Samuel has spent the last five years working at a large independent design consultancy that works on everything from graphics and images, web design, products and packaging, to exhibitions and installations. Frequently, he will work cross-functionally with the web designers, who do most of their work in Figma. They consistently extoll the collaborative component of Figma and would like Samuel to start crafting some of his images in the software, even if he does ultimately finish everything in Adobe Illustrator. The final product must align with accessibility standards, particularly for colorblind users

Map Outline:
- c_filename.dita (File title)
- c_filename.dita (File title)
- t_filename.dita (File title)
  - t_filename.dita (File title)

### User Scenario 2: ...

Terrence is a college senior at the Academy of the Arts studying illustration. In his time at school, he has done everything from sample illustrations for advertisements, caricatures for the school's satire newspaper, cartoons, and children's books. 

His real passion, however, lies in concept art. Terrence has always been a sci-fi junkie and enjoys hand-sketching elaborate cityscapes, fantasy backgrounds, and futurist characters and technology. His portfolio of these drawings was so extensive, in fact, that he was able to acquire an internship with Harper Voyager, a sci-fi-focused imprint of Harper Collins. Perhaps even more importantly, Harper Voyager would like to use one of Terrence's drawings for one of their represented writers! His first task is to both digitize and colorize the selected illustration for their use. They would like it to be in vector format to scale up for promotional materials they are going to create to advertise the release of the author's new novel.

Map Outline:
- C_Raster_vs_Vector images
- C_Bitmaps
- T_Vectorize_An_Image
- T_Create_Frame
- T_Scale_Image
- T_Fill_Frame
- R_Image_Types
- R_Supported_Plugins


### User Scenario 3: ...

Gary has worked as a freelance illustrator in the publishing industry for the past fifteen years and has built relationships with authors and publishing agencies spanning numerous genres, including fantasy, science fiction, comic books, and academic textbooks. Most of the time, Gary will hand off his hand-drawn drawings to either the authors directly or the agency he’s working with, who then handle the digitization of his work.

Recently, Gary was approached by DC Comics to work on a popular comic book series.   He has done some graphic illustrations for this series prior, but never directly worked with DC, which has quite a robust team working on the project both internally and within their parent company, Warner Bros. Discovery. 

The team he’s working on recently transitioned to Figma for its collaborative power, not only amongst the illustrators but also with DC’s in-house web designers. They would like for Gary to give a short virtual presentation of work he’s created prior to the series, and would like his images to be in Figma so other team members can offer real-time feedback and comments.

Map Outline:
- C_Negative_Space
- C_Raster_vs_Vector images
- T_Create_Frame
- T_Fill_Frame
- T_Scale_image
- T_Rotate_Image
- R_Image_Vectors
- R_Image_Rasters
- R_Image_Types
- R_Hotkeys
- R_Design_Panel


## Folders &amp; Files

- `assets`: Contains all assets used within the TM.
- `concepts`: Contains all concept topics.
- `references`: Contains all reference topics.
- `tasks`: Contains all task topics.
- `shared`: Contains all topic files that are shared across multiple maps.
- `out`: Contains all output folders.
- `themes`: Contains `.yaml` style configuration files.
- **Skeleton files**: All topic folders contain a single "skeleton" topic file for you to copy, whenever you need to quickly create a new file.
- `.keep` **files**: Ignore these files. They ensure that any empty folders are tracked by git. 
- `.gitignore`: This file tells git which files to ignore in the repo. You can leave this one be.

## Filenaming Conventions

- Task Topics: `t_verb_verbobject.dita`
- Concept Topics: `c_nounphrase.dita`
- Reference Topics: It varies, but something akin to `r_types_of_nounphrase.dita`
- Dita Maps: `_modelname.ditamap`

## Building Outputs Manually with the Command Line

See the DITA-OT user guide about how to generate output: [https://www.dita-ot.org/dev/topics/build-using-dita-command](https://www.dita-ot.org/dev/topics/build-using-dita-command)

### Sample DITA Commands

#### Help

To see all of the commands and parameters, use the following command:

```
dita --help
```

#### DITA options and arguments

```
-f == dita output format
-i == dita input map file
-o == dita output directory
-D&lt;property&gt;=&lt;value&gt; == add custom args
    with particular values to dita transformation
-filter &lt;file&gt; == filter and flagging file
```

#### Create an HTML5 site

```
dita -f html5 -i 'url/to/your/wanted.ditamap' \
  -o 'url/to/your/output/folder' \
```

#### Create an HTML5 site with a custom CSS file

```
dita -f html5 -i 'url/to/your/wanted.ditamap' \
  -o 'url/to/your/output/folder' \
  -Dargs.cssroot='url/to/your/assets/folder' \
  -Dargs.css='${cssroot}/your-custom-css-file.css' \
  -Dargs.csspath='css' \
  -Dargs.copycss='yes'
```

#### Create a PDF

```
dita -f pdf -i 'url/to/your/wanted.ditamap' \
  -o 'url/to/your/output/folder' \
```
