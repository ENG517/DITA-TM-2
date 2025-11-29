# Group Reflection

## Scenario 1 - Crafting Grayscale Images / Image Design for Accessibility

## Links to Project Management Resources

[Project Google Folder](https://drive.google.com/drive/folders/1SmRxSvmAYp3WKy-sv4jPcinfL2zMWA_g?usp=sharing)

[Project Daycare Google Doc](https://docs.google.com/document/d/1Dxz1tRY0phiJU4e4vkBQdN6E0A069k_qsfTjOAhohTA/edit?usp=sharing)

[Project Tracker Spreadsheet](https://docs.google.com/spreadsheets/d/1Ip0ZPNTkDlS_5SMLw7OkBz-DGdIyvbCJ/edit?usp=sharing&ouid=109057038477145032535&rtpof=true&sd=true)

### Map 1

1. C_Negative_Space
2. T_Grayscale_using_Monomagic
3. T_Testing_Colorblind_Accessibility
4. R_Grayscale
5. R_Hotkeys
6. R_Design_Panel
7. R_Figma_Draw
8. R_Supported_Plugins

### Reflective comments 1

The map for this section outlines how to grayscale an image inside Figma. Reuse cases for concepts include C_Negative_Space because the content of it applies to procedures regarding grayscaling images and importing images based on image types. We decided to include accessibility testing as a task for this one since grayscaling an image also involves ensuring the changes are visible across color vision abilities. One reuse case for references includes R_Plugins for this procedure because the plugins are also included in this topic across procedures. Hotkeys as a reuse case apply across scenarios and procedures because they are useful to know as a skill, regardless of a user’s needs within Figma.

## Scenario 2 - Vectorizing Images / Illustrator for Vectoring
### Map 2

1. C_Raster_vs_Vector images
2. C_Bitmaps
3. T_Vectorize_An_Image
4. T_Create_Frame
5. T_Scale_Image
6. T_Fill_Frame
7. R_Image_Types
8. R_Supported_Plugins

### Reflective Comments 2

The map for section two shows how to vectorize a raster image using a third-party plugin. The distinction between raster vs. vector images is critical for understanding the exigency behind the procedure, and the bitmap concept topic provides further insight into this distinction. All of the task topics are pivotal to the process of conversion. Supported plugins provide supplementary information on navigating plugin pages, and how plug-ins operate, and the image types reference topics elucidate different important image formats.

## Scenario 3 - Importing Images / Illustrator for Image Editing

### Map 3

1. C_Negative_Space
2. C_Raster_vs_Vector images
3. T_Create_Frame
4. T_Fill_Frame
5. T_Scale_image
6. T_Rotate_Image
7. R_Image_Vectors
8. R_Image_Rasters
9. R_Image_Types
10. R_Hotkeys

### Reflective comments 3

This procedure explains how to import an image into Figma for editing. The map outlines types of image files (rasters and vectors) and how to work with and adjust the image scale and orientation in Figma. We decided it was important that users understand the differences between the two types of images to work with and the different file types Figma supports, so we included concept and reference topics about both. We also included a concept topic about how to use negative space in design when creating and changing the imported image. 

## Overall thoughts on the process and collaboration+project management strategies

One strategy we implemented to ensure consistency and clarity about information, tasks, and resources needed to complete the project was the use of a communal project daycare document. Frequent Zoom meetings to work together and get on the same page were extremely helpful, and all merging took place via screen share. We discussed problems quickly and effectively, utilizing the discussion items tab of the spreadsheet and messaging in WhatsApp to strategize solutions upon working together for our scheduled Zoom meetings. 

We look forward to further expanding upon this topic model in the next unit and growing together for this project!

## Lindgren's Feedback

Overall, this is a great first draft. I really appreciate your work to integrate all of this content. I provide some overarching feedback below, but please see some of my feedback within some respective dita files, which should also be considered as representative cases for revisions to carry out throughout the remainder of the model, when appropriate.

- **C -> T -> R**: I see this as your algorithm via your maps. It makes sense to a degree, and I can see how that was a takeaway from some of our example lessons with fewer files. Yet, remember that conceptual and reference information support tasks. Accordingly, I recommend reading through your outputs to help you identify what aspects of the more complete concept and reference topics are truly necessary to include in your task topics. Once you do this part of the DITA writing process, then you'll start to really recognize where you can (1) revise the topics to be more reusable, and (2) consider how to start using conrefs to target specific **units of content** within other topics files to support task topics, rather than include entire topic files all the time. I want to reiterate that this is a *great first draft*. Conceptually, it takes awhile to wrap one's mind around topic-based, single-source writing, and I can even think about how to revise my lessons to offer more upfront guidance on conref cases and methods, which I'll be sure to review. But, consider how this model has yet to use *any* conrefs, so you have some time and opportunity to implement them as you conduct your other editing and revision work. As you do so, consider and take note of how to target specific parts of concepts and reference topics, for instance, to support task topics, rather than thinking you need to always dump entire files in an sequence like *Concepts --> Tasks --> References*.
- **Reuse cases**: I like your inclusion of some potentially helpful reuse cases at the entire topic level so far, such as the hotkeys as references to provide. Perhaps, consider how that could become a shared understanding as a documentation team, wherein y'all would know that you would use hotkey references in your task topics, so it could be common practice to provide that table at some recurrent place in the task topic. That said, you don't need to add the entire reference topic. Instead, you could consider a couple things:
    1. Conref in a table or part of a table into the `prereq` as a provided resource to use throughout the task.
    2. Add `uicontrol` wrappers in your ref topic tables for each hotkey, so you can use them like variables in your tasks. NOTE: I am not asking you to consider this one, because it would take lots of time away from your next unit. But, I thought it'd be worth mentioning as a possibility. Glossaries in DITA can be used to accomplish this variable reuse strategy too.
- **Conrefs**: As noted above, there are no reuse cases with conrefs. Consider a few ways to implement a strategy to help your outputs become a little more readable. Please note that I'm going to provide some support in that area with some more examples to consider.
- **Titles/Headings**: Be sure to adhere to more descriptive and appropriate headings. I noted how some files included headings, such as "Definition", etc. While we are focusing on DITA elements and topic production in this first phase, we did cover the basic tenents of appropriate titles, based on the topic file type. You'll have some good opportunity to revise these during the last unit, which I would have asked y'all to do anyhow. `:-)`
- Element Semantics / Appropriate Element Usage: This is a tricky one, and I think y'all are doing great thus far for a first draft from folks who are new to DITA. So, well done! I have some specific cases to reconsider, based on some patterns I noticed:
    - **Tables**: I offer a few cases in my in situ notes, wherein sometimes your use of a properties table is actually more appropriately a simpletable, and other cases where it's vice versa. Just be sure to read the DITA specification, when you're not sure. And, if that doesn't clarify it for you, discuss with peers and/or someone more experienced. In this case, that's me lol. Feel free to ask me if you're unsure about certain uses, because DITA has so many options where there are honestly moments where it can feel like splitting hairs. The deliberation is a key part of the process, though, regardless of experience level.
    - **`shortdesc`**: Be sure to follow Bellamy et al's guidance on writing short descriptions appropriate for each type of topic. I noted how many of them are either missing important moves, or include more superficial moves that don't quite work well with the semantic purpose of that element. For example,
      > Figma is a vector based design software. As such, there is no eraser tool.
    This short description from a task topic does not include the cornerstone moves, such as a goal statement and stated outcome. In short, review the requirements and be sure to resvise accordingly throughout your model.
- **Alerting Moves**: Be sure to revisit your task topics and consider where and how you can more generously apply `stepresult` and `result` elements, as well as `note` and `info` elements. When reading through the procedural content, thinking of your audience, I felt a little lost about what action I should be taking and what outcome I should expect.
- **Indentation & Formatting**: Be sure to use consistent and *appropriate* indentation of your elements across all of your files. Indentation and formatting achieves a couple main skills beyond what seems like superficial ends:
    1. More readable files, since you and your colleagues will not need to constantly (re)evaluate and interpret element inter-relationships.
    2. Appropriate indentation shows me that you understand that X element is a child, sibling, or descendant of Y element.
- One more note on indentation/formatting: I note how longer lines seemed to be chopped up. I'm not sure if a Document Formatter did that, which is a VS Code feature to definitely use. BUT, I recommend not chopping up longer lines like paragraphs, etc., and instead simply use the Word Wrap feature in your editor, as well as use an example format below, wherein the longer content of elemnts like shortdesc and paragraphs are contained like children elements:
    ```xml
    <shortdesc>
      This defines HEX Values and provides a table for different colors and their associated HEX value and RGB Value.
    </shortdesc>

    or

    <p>
      A HEX Value is a color code that tells computers and devices which color to display using three pairs of digitals, representing the red, green, and blue RGB values.
    </p>
    ```
- Lots of dita files are not being used, despite being rather fully drafted. Did you have plans to integrate them? Seems like you could conduct an audit of material and delete anything not being used.