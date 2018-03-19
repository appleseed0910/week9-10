# Week9-10

For this checkpoint, I focus on discussing and comparing three different Interactive Fiction Creating tools: Twine, InkdML, InkleWriter.

The discussion would contain some common functions that are needed and often being used during the creation of Interactive Fiction (CYOA), and introduce different approaches through three tools.

- <a href="https://appleseed0910.github.io/week9-10/Willowfield%20Manor.html">Demo</a> This is a game demo I currently created using Twine. I've used most features of Twine in this demo.
- The last time I used InkdML framework is almost a year ago. I've checked some documentations and review my team project created during the Storytelling class.
- I didn't use InkleWriter to complete any project yet. But I've played both 80 Days and Sorcery! series and read some tutorials.

## Functions

1. Story and Options writing

Story and Options are the essence of the CYOA game, three tools have different ways to create the story structure. In Twine, **passage** and **link** are used for this target. Passage represents different scene, links are transistions that bring players to the other passage. Twine's interface is quite easy to read, click the big greent button could allow user create a new passage. Double-click a passage could open it and edit the content. There are multiple ways to write a link in Twine, either "[[Link text|Passge name]]" or "[[Link Text->Passage name]]" could realize a link. There're also (link:) marcross could wrtie links.

In InkdML conversation editor, the interface is similar to Twine and easy to understand as well. In the original InkdML, users edit the special <inkd> html tag to create new **node** which works as same as **passage** in Twine. So does the options are created in the same way.
  
In InkleWriter, it's a little bit different. Both Twine and InkdML use a graphic map which has two axis. The passage map could be like a tree or a bell or a spindle. But in the InkleWriter, even though you could still create different options. The stucture is vertical in most times, which means manage he story structure would be a little difficult if the story is not quite linear.

The other obvious difference is, in Twine and inkdML, user could write plain html code inside the passage/node. The outcome of these two tools are both websites. However, InkleWriter is a packaged platform. The default interface is fancy and classic whereas the limitation of source code access decline the ability.

2. Customize external media

InkdML is most flexiable tool in engaging other media form rather than other two tools. The ways that insert a picture or sound or video to the game in InkdML and in Twine are similar since they are both html file. But in Twine, import a absolute link of the raw file is very hard except user holds a server on her own. InkleWriter also doesn't support submit but only allows user to use external link.

InkdML allows user to pack the images and audio file together, which is the best choice when the use doesn't really have her personal server.

3. Effects and Fonts

InkdML and Twine are pretty good at this aspect, if the user knows html and css well. The font part, since the story's stylesheet is editable, some open source website such as Google fonts provide very useful help. And font file could also be placed inkdML folders.

Text effects could be realized through (text-style:) marcross in the Twine and through the CSS in the inkdML.

4. Logic and Data

Twine allows user to write their own script using JS. However it's a little bit rigid if the user cannot get full access to all the html elements. I haven't realized any code in Twine in JavaScript yet. InkdML is more flexiable since the source code is open to browse. In Twine, the logic and data part rely on multiple marcross to realize such as (if:) and (datamap:). Both two tools involve some basic logic and data algorithm such as "if..else" "array" some concepts.

InkleWriter has a very powerful feature that other two tools don't have. It allows user to publish their story stucture out and using it in Unity (requires some C# knowledge), also could publish it out as a JSON file.

## Reference

https://inkdlab.gitbooks.io/inkdml/content/

https://twinery.org/wiki/twine2:guide

https://www.inklestudios.com/inklewriter/


