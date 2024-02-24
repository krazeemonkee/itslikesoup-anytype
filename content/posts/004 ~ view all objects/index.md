---
#title: "how to view all objects"
title: "view all objects"
# title: "what the heck are objects?"
# title: "a house full of objects"
date: 2024-02-14T21:11:49-08:00
draft: false
description: ""
categories:
  - 🗺 guide
tags:
  - 👁 view
  - 🦅 overview
# programs:
#  - anytype
scopes:
  - set
guides:
  - beginner
functions:
  - view
serial: "004"
slug: "view-all-objects"
ver: "v1"
changes: ""
featuredImage: "https://kyojuuros.tumblr.com/post/685089475098034176/animations-daily-the-lion-king-1994-dir-rob"
related:
  - 005
  - 013
  - 012
---

<p style="text-align: justify">out of the box, there is no root directory that allows you to view/access all your objects <i>or all objects of a particular type</i>, but you can easily create such an aggregated list referred to in <b><i>anytype</i></b>, as a <code>📊 set</code>
</p>

## what are sets

<p style="text-align: justify">a <code>📊 set</code> starts out as an assortment of every single object that's an offspring of its parental <code>⚛️ object-type</code> ~ so, w/out applying any filters, a freshly created <code>📊 set</code> will  contain every single sibling-object of their parent's <code>⚛️ object-type</code> ~
</p>

## what are relations

<p style="text-align: justify">just as every person has an amalgamated identity that's comprised of many sub-identities such as name, gender [reproductively], nationality, eye-color, etc, every single object created in <b><i>anytype</i></b> also has such sub-identities, bits of information/properties relating to an object which are refered to in <b><i>anytype</i></b> as <code>🖇 relations</code>
</p>

<p style="text-align: justify">three relations that are identifiers of every single object created in <b><i>anytype</i></b> are:
<ul>
    <li> <code>🖇 creation date</code>
    <li> <code>🖇 last opened date</code>
    <li> <code>🖇 last modified date</code>
</ul>
<p style="text-align: justify">since these relations are shared by every single object in your <b><i>anytype</i></b> space, we can create a <code>📊 set</code> whose parent is not an <code>⚛️ object-type</code> but rather a <code>🖇 relation</code> ~ this means all sibling-objects in the set will be every single object that contains information for that relation, in our case w/ the relations above, since every object is born w/ these native-creations, every single object in our space should appear in these sets ~
</p>

### create relation sets

<p style="text-align: justify">follow the following guide to create a set of relations for the three relations we discussed above: </p>
<ul>
    <li> <code>🖇 creation date</code>
    <li> <code>🖇 last opened date</code>
    <li> <code>🖇 last modified date</code>
</ul>

{{< alert icon="sun" iconColor="yellow" cardColor="darkblue" textColor="fff8d6" >}}
💠 <b style="color: red;">🧵 create 🖇 relation 📊 set</b> <br>
<ul>
    <ol>
        <li> navigate to library page
            <ul>
                <li> <details><summary> via side-panel</summary>
                    <ul>
                        <li>⌨️ if configured to open/close on command
                            <ul>
                                <li> <code>⌘ .</code> // <code>⌘ \</code> == <code>open/close side-panel</code>
                            </ul>
                    </ul>
                    <ul>
                        <li>🐁 if configured to open/appear by mouse-summoning
                            <ul>
                                <li> <code>drag cursor to  left-edge of screen</code>
                            </ul>
                    </ul>
                    <img src="img/1-1-side-panel.gif" style="padding: 0; margin: 0;">
                    </details>
              <li> <details><summary>via ⌨️ keyboard</summary>
                <ul>
                    <li><code>⌘ l</code> == <code>open library page</code>
                    <li><code>⌘ ⌥ t</code> == <code>open relations panel</code>
                <img src="img/1-2-keyboard.gif" style="padding: 0; margin: 0;">
                    </details>
                </ul>
                <li> <details><summary>open relations pane</summary>
                <img src="img/2-open-relations-pane.gif">
                </details>
                <li> <details><summary>search for relation</summary>
                <img src="img/3-search-relation.gif">
                </details>
                <li> <details><summary>select relation</summary>
                <img src="img/4-select-relation.gif">
                </details>
                <li> <details><summary>click/select "create set"</summary>
                <img src="img/5-create-set.gif">
                </details>
                <li> <details><summary>configure title/icon [set-identity]</summary>
                <img src="img/6-configure-set-identity.gif">
                </details>
            </ul>
    </ol>
    <b>entire process</b>
            <img src="img/mouse-set-created99.gif" style="margin: 0; padding: 0;">

</ul>
{{< /alert >}}




<!-- scrap
~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ •
~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
## create <span style="color: aqua;">📊 set</span>/list for a specific <span style="color: aqua;">⚛️ object</span>-type

### ~ navigate to object's library page

<p style="text-align: justify"> to view all the notes [or <code>⚛️ objects</code>] for the default object-type <code>📝 note</code>
</p>

{{< alert icon="sun" iconColor="yellow" cardColor="darkblue" textColor="#fff8d6" >}}
💠 <b style="color: red;">navigate to object-type's library page</b> <br>
in ⚛️ <b style="color: yellow;">object view</b> 👁

1. via the <code style="color: yellow;"> object-name identifier</code> <i style="color: yellow;">near the top-left</i>
    1. <details><summary>🐁 mouse</summary><img src="img/guide/1a~open~object-type's~library~page.gif"></details>
2. via <code style="color: yellow;">🖇 relations-pane 👁</code>
      1. <details><summary>🐁 mouse</summary><img src="img/guide/1b~navigating~to~object~via~relations-pane.gif"></details>
      2. <details><summary>⌨️ keyboard <code>⌘ ⇧ r</code> == <code>open relations pane</code></summary><img src="img/guide/1d~nav~to~relations~pane~via~keyboard.gif"></details>
3. via <code style="color: yellow;">🏛 library-page 👁</code>
    1. <details><summary>🐁 mouse</summary><img src="img/guide/1c~navigating~to~object~ via~mouse~in~side-panel.gif"></details>
    2. <details><summary>⌨️ keyboard <code>⌘ l</code> == <code>navigate to library page</code></summary><img src="img/guide/1e~open~library~page~via~keyboard.gif"></details>

{{< /alert >}}

### ~ create set/list of all objects

once at the object's library page, you can now create a set [or list] of all the instances of this object [all your notes]

![](img/guide/2~create~"new~set~of~objects".gif)

{{< lead >}}
<details><summary><i style="color: orange;">recommended</i> ~ <i><span style="color: yellow;">rename set list</span> to fit a systematic naming convention, for example, refer to the following article discussing one method to name objects vs sets<a></a></summary><img src="img/guide/3~renaming~set~of~objects.gif"></i></details>
{{< /lead >}}


{{< alert cardColor="darkred" >}}
<p style="text-align: justify;" color="red;"><b>voila, you have now created a set , which in of itself is an object that specifically aggregates all the invididual components within that particular object [📝 Note]</b></p>
{{< /lead >}}

## add new set of object to widget // side-panel

{{< alert icon="sun" iconColor="yellow" cardColor="darkblue" textColor="#fff8d6" >}}
💠 <b style="color: red;">add object to widget/side-panel</b> <br>

1. via the <code style="color: yellow;">menu button [ellipsis]</code> <i style="color: yellow;">near the top-right</i>
    1. <details><summary>🐁 mouse</summary><img src="img/guide/4a~create~widget~via~elipses~button.gif"></details>
2. via the <code style="color: yellow;">widget/side-panel </code>
    1. <details><summary>🐁 mouse</summary><img src="img/guide/4b~add~widget~via~side-pannel.gif"></details>
{{< /alert >}}

{{< act >}}
redo or maybe have image carousel... slow your ponies...
{{< /act >}}


>you created a note but where did it go?

that note [an ⚛️ object] lives within/under

<ol>
  <li> within the <code style="color: yellow;">👁object-view👁</code>, navigate to the object-type's library page 🏛 ⚛️
    <ol>
      <li><details>
      <summary>click on the object-type's <i>name/identifier</i> near the top-left</summary>
      <img src="img/guide/1a~open~object-type's~library~page.gif">image
      </details>
      <li> open relations pane
        <ol>
          <li> <details>
          <summary>mouse: click on the [relations-logo] top-right</summary>
          <img src="img/guide/1b~navigating~to~object~via~relations-pane.gif">image
          </details>
          <li> keyboard: <code>⌘ r</code>
        </ol>
    </ol>
</ol>

{{< alert icon="sun" iconColor="yellow" cardColor="darkblue" textColor="#fff8d6" >}}
💠 <b style="color: red;">navigate to object-type's library page</b> <br>
⚛️ <b style="color: yellow;">object view</b> 👁

1. 🐁 mouse
    1. <details><summary>click on the object-type's <i>name/identifier</i> near the top-left</summary><img src="img/guide/1a~open~object-type's~library~page.gif"></details>
2. ⌨️ keyboard
    1. <code style="color: red;">⌘ +</code> == <code style="color: red;">zoom in</code>
    2. <code style="color: red;">⌘ -</code> == <code style="color: red;">zoom out</code>

{{< /alert >}}

<img src="img/guide/2~create~"new~set~of~objects".gif">

that comprise object

## view all i nstances of an object // view all objects of an object-type

## <code>📊 set</code>/list of <code>⚛️ object</code>-type

, that display either all of your objects or all objects of a particular object-type ~

this article will guide you into creating 2 ways to view every object inside your space

instance of that object-type's

, along w/ all of it's sibling objects/notes

contents are organized by similarity ~ for instance,

the more notes you create, the more objects that fill this never-ending room, the harder it will continually get to find specific objects in the future ~ so, to prevent the eventuality of this chaotic, unorderly scenario, you must simply separate the objects + group them in bins/containers according to a trait that's shared by all the objects inside

 according to a trait that's shared by all the objects inside

<p style="text-align: justify">try imagining every new <code>⚛️ object</code>/<code>✏️ note</code>

<p style="text-align: justify">try imagining every new <code>⚛️ object</code> you create in <b><i>anytype</i></b> as an actual, physical object that now exists inside an empty room [<code>⚛️ object-type</code>], inside a house [<code>🌌 space</code>] ~ this room can only hold objects of a particular type, in this case, <code>✏️ notes</code> </p>

<p style="text-align: justify"> just as you may put a label on each object to more easily identify them, this identity is called relations each object has properties/details/info ~</p>

<p style="text-align: justify">the following article will show you how to view all the objects inside a particular room, or object-type, of the house but i will now discuss if you wish to find all the objects in the house</p>

<p style="text-align: justify">these objects are the building blocks for your entire <b><i>anytype</i></b> database, where relations connect objects together
</p>

groupable/sortable containers them in bins/containers according to a trait that's shared by all the objects inside
<p style="text-align: justify">to prevent the eventuality of this chaotic, unorderly future, you must simply separate/arrange the objects into groups, placing them in containers containing other objects that share similar traits ~
</p>

<p style="text-align: justify">in the start of your <b><i>anytype</i></b> journey, you may often find yourself feeling get the sense of things being lost or unable to be found ~</p>

## where are my notes?

<p style="text-align: justify">in the start of your <b><i>anytype</i></b> journey, you may often get the sense of things being lost or unable to be found ~</p>

{{< lead >}}
🤷🏻‍♂️ <i>i created a note but where did it go + how can i retrieve/recall it?</i>
{{< /lead >}}

<p style="text-align: justify">before knowing where your notes are, it might help to first understand <i>what</i> your notes are ~
</p>

## *what* are my notes?


<p style="text-align: justify">like all other components, or building blocks of  <b><i>anytype</i></b>, that note you wrote is actually an <code> ⚛️ object</code>, an offspring instantiated from a parental family/type ~ so, that note lives together w/ all other sibling-objects  of the same type [<code>✏️ notes</code>, for example] within your <code>🌌 space</code> [place where <i>all objects</i>, <i>of all types</i>, are stored] ~
</p>

![](img/house.gif)


<p style="text-align: justify">try imagining every new <code>⚛️ object</code> you create in <b><i>anytype</i></b> as an actual, physical object that now exists inside an empty room, inside a house ~ this room can <i>only</i> hold objects of a particular type, in this case, <code>✏️ notes</code> ~
</p>

![](img/empty-room.png)

<p style="text-align: justify">the more notes you create, the more objects that fill this <i>never-ending</i>/<i>ever-expanding</i> room, the harder it will continually get to find specific objects in the future ~
</p>

![](assets/empty-room/output/empty-room.png)

<p style="text-align: justify">to prevent the eventuality of such a chaotic inevitability, you must simply bring order to the system by separating the objects into into groups relating the bunch by some common, or similar traits/attributes shared by all other objects in the group
</p>

<p style="text-align: justify">much like a birth certificate, a trait/attribute that every object is given the moment it is created is a <code>creation date</code> ~ anytype calls these bits of information that identify the nature of an object as <code>🖇 relations</code></p>

<p style="text-align: justify">since every object has a <code>🖇 relations</code>/<code>📅 creation date</code>, this relation therefore units every single object inside every room [<code>⚛️ object-type</code>] in your entire house [<code>🌌 space</code>] ~
</p>

<p style="text-align: justify">so, of all the objects in a given room, <code>✏️ notes</code>, for example, we can choose to put them into a magical container that

separate socks from tops



>the next article will show how you can do the same thing but with all objects in your space, not just for a specific object-type</p>

that's an instance of it's

just as every person has an overall identity that's comprised

identifiers that reveal sub-data,

## create a set to view all objects

### sorted by creation date

### sorted by opened date

### sorted by modified date

### make <code>📊 set</code> for <code>🖇 creation date</code>

<li> <i class="info"> <code>⌘ l</code> == <code>open library page</code>

<li> <code>⌘ .</code> == <code>reveal/disappear side-panel</code>

<li>if configured to open/close on command in options, then summon it






{{< alert icon="sun" iconColor="yellow" cardColor="darkblue" textColor="fff8d6" >}}
💠 <b style="color: red;">🧵 create 🖇 relation 📊 set</b> <br>
<ul>
    <ol>
        <li> navigate to library page
            <li> via side-panel
        <ul>
            <li> <i style="color: yellow;">open side-panel</i>
                <ul>
                    <li>if configured to open/close on command
                        <ul>
                            <li> <code>⌘ .</code> // <code>⌘ \</code> == <code>open/close side-panel</code>
                        </ul>
                    <li>if configured to open/appear by mouse-summoning
                        <ul>
                            <code>drag cursor to  left-edge of screen</code>
                        </ul>
                    <img src="img/mouse-set-created99.gif" style="padding: 0; margin: 0;">
                </ul>
        </ul>
    <li> ⌨️ keyboard
        <ul>
            <li><code>⌘ l</code> == <code>open library page</code>
            <li><code>⌘ ⌥ t</code> == <code>open relations panel</code>
            <li><i style="color: #868686;">click on vid/gif to enlarge it</i> <img src="img/set-created99.gif" style="padding: 0; margin: 0;">
        </ul>
</ul>
{{< /alert >}}








<i style="color: #868686;">click vid/gif to enlarge</i>




<b>entire process</b> <i style="color: #868686;">by path/route</i>
        <ul>
            <li> <details><summary>side-panel</summary>
            <i style="color: #868686;">click vid/gif to enlarge</i>
            <img src="img/mouse-set-created99.gif" style="margin: 0; padding: 0;">
            </details>
            <li> <details><summary>keyboard-shortcut</summary>
            <img src="img/keyboard-process.gif" style="margin: 0; padding: 0;">
            </details>
        </ul>


 <i style="color: #868686;">by path/route</i>

### create relation-set for creation date

### create set for creation date, opened date, modified date [relation]


-->
