![MD style image](Documentation/images/Documentation_preview_banner_w_text.png)

<div align="center">
<!--  <div style="display:inline-block; text-align:left; max-width:900px; font-size:20px;">  -->
  <div style="display:inline-block; max-width:900px; font-size:20px;">
    ProjectMPB is an interactive simulation of photosynthesis developed at the University of Turku.<br>
    The goal is to provide an accurate, visually rich, and accessible tool for researchers and educators<br> to observe photosynthetic processes in silico.
  </div>
</div>

<br>

<div align="center">
  <div style="display:inline-block;">
    <a href="https://example.com/docs" target="_blank" rel="noopener noreferrer" style="display:inline-block;">
      <img src="Documentation/images/click_run.png" alt="View documentation" style="height:220px;">
    </a>
    <a href="https://example.com/docs" target="_blank" rel="noopener noreferrer" style="display:inline-block;">
      <img src="Documentation/images/click_documentation.png" alt="View documentation" style="height:220px;">
    </a>
  </div>
</div>

<br>
<br>
  
#
<h1 align="center">How to control the simulation?<h1/>

<br>

<table align="center">
  <tr>
    <td align="center"><p>Scroll to zoom</p></td>
    <td align="center"><p>Right click to<br>move camera</p></td>
    <td align="center"><p>Left click to<br>add particles</p></td>
  </tr>
  <tr>
    <td align="center"><img src="Documentation/images/gifs/tuto_1.gif" alt="tuto 1" width="300"></td>
    <td align="center"><img src="Documentation/images/gifs/tuto_2.gif" alt="tuto 2" width="300"></td>
    <td align="center"><img src="Documentation/images/gifs/tuto_3.gif" alt="tuto 3" width="300"></td>
  </tr>
  <tr>
    <td colspan="3" align="center"><p>Adjust speed of particles using the Speed slider</p></td>
  </tr>
  <tr>
    <td colspan="3" align="center">
      <img src="Documentation/images/gifs/tuto_4.gif" alt="tuto 4" width="1025">
    </td>
  </tr>
</table>



<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
## Maybe some table of content?
- [Overview](#overview)
- [Installation](installation.md)
- [Usage](usage.md)
- [Biology](biology/proteins.md)
  - [Protein Complexes](biology/complexes.md)
  - [Photosystems](biology/photosystems/PSI.md)

test

## Proteins and protein complexes.
- <span style="color:#32CD32">🌿 Oxygen-evolving complex.</span>
  - Important short description of OEC.
  - [Read more details](Documentation/OEC.md).
  - Go to chapter directly: [function](Documentation/OEC.md#function).
  - Code sniplet [L301](scenes/Level_7_scenes_and_scripts/Photosystem_II.gd#L301).
  - Code sniplet [L301–L601](scenes/Level_7_scenes_and_scripts/Photosystem_II.gd#L301-L601).
- <span style="color:#32CD32">🌿 Photosystem II.</span>
  - Whatever.

## Some ideas to make MD look nice.
### Example GDScript.

```gdscript
func test():
    print("Protein Complexes!")
```

```py
func test():
    print("Protein Complexes!")
```















<details>
  <summary>
    ✅ GDScript dropdown test.🔎
  </summary>

  <pre><code style="color: orange;">
def water_binding():
    print("OEC binds two water molecules!")
  </code></pre>
</details>






<details>
  <summary>
    ✅ GDScript dropdown test.🔎
  </summary>
  <gdlink>"Project/Scripts/OEC.gd"</gdlink>
```py
def water_binding():
    print("OEC binds two water molecules!")
```
</details>












### Example MD image placement.
![MD style image](Documentation/images/chlorophyll_A_absorption.png)





### 📊 Some diagrams.
- Diagrams with **Mermaid** (supported on GitHub!)  

Example:

```mermaid
graph TD
  A[Cell] --> B[Complexes]
  B --> C[OEC]
  B --> D[PSII]
```

---
### Extra ideas:
- Glossary.md to keep links to each and every one element of cell biology.
---
