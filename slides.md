---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1576595580361-90a855b84b20?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1674&q=80
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

<img src="https://zero-one-group.com/wp-content/uploads/2019/12/ZeroOneGroup_Black_500x500_Padded.png" />

## Lessons Learned from Creating Design System

### Rivaldi Putra
### rivaldi@zero-one-group.com
### ZOG Sharing Session 6 April 2023


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
<style>
 img {
    width: 100px;
    margin : 0 auto;
    height: 100px;
   }
</style>

---
transition: fade-out
---

# What is Design System?

The design system is a collection of components that are used repeatedly to maintain quality standards and design consistency.
UI/UX designers play a key role in designing and developing design systems.

<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*vI3VLuqj0NPUjI6MX25RuQ.jpeg" />

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
 img{
     height: 300px;
     margin : 0 auto;
   }

</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# The main goal of Design System

<ul>
<li> improve efficiency</li>
<li>Improve consistency</li>
<li>Improve quality</li>
<li>Increase collaboration</li>
</ul>



<!--
Here is another comment.
-->

---
transition: slide-up
---

# ZOG UI

<a href="https://github.com/zero-one-group/zog-ui">ZOG</a> UI is a design system we are trying to develop, hoping that collaboration and efficiency in developing new projects will increase.


<img src="/zog.png" />

<style>
img{
     height: 300px;
     margin : 0 auto;
   }
</style>
<!--
Here is another comment.
-->

---
transition: slide-up
---


# The goal of ZOG UI


<table>
  <tr>
    <th>objective</th>
    <th>achieved</th>
  </tr>
  <tr>
    <td>Increase efficiency</td>
    <td>❌</td>
  </tr>
  <tr>
    <td>Customizable</td>
    <td>❌</td>
  </tr>
  <tr>
    <td>Reusable Component</td>
    <td>✅</td>
  </tr>
  <tr>
    <td>Developer Exprience</td>
    <td>❌</td>
  </tr>
</table>

# cause some objectives are not achieved

The system design itself is not suitable for agencies and the development deadline is relatively short


<style>
table, th, td {
  border:1px solid black;
}
</style>
<!--
Here is another comment.
-->

---
transition: slide-up
---


# challenges or problems faced during development

<ul>
 <li>Untidy token design</li>
 <li>mindset during development</li>
 <li>how to think for create a component based on figma but still costomizable</li>
 <li>we have to learn css fundamental</li>
</ul>

# lessons to be learned

<ul>
 <li>As FrontEnd Engineers, we cannot ignore fundamental css</li>
 <li>In the future maybe the PD better communicate with the Engineer before developing a UI</li>
 <li>Design System is not always an option to increase efficiency and collaboration</li>
 <li>For the short deadline better we chose  component library rather than create from scratch</li>
</ul>

