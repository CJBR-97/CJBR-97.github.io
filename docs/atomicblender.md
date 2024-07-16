# Atomic Figures in Blender (Tutorial)[^1]
**by Christoff Reimer**

Creating figures and diagrams for your work can be quite a rewarding activity, and it helps to know some tricks for making visualizations vibrant (yet simple).

A short time ago, I had the opportunity to assist one of my colleagues [Conrard Tetsassi, PhD](https://www.linkedin.com/in/conrardtetsassi/) with representing an atomic system using Blender, the free 3D everything-software. The process was recorded so I could send it remotely, and with permission I am able to share it right here in this post.
Let's begin by making sure you have Blender installed and have activated the [atomic Blender add-on](https://docs.blender.org/manual/en/4.0/addons/import_export/mesh_atomic.html). 

> [!TIP]
> If you haven't installed Blender before, make sure to get the program from the official site.

Open Blender with the add-on enabled and you will see a grey landscape with a single cube in the middle of it. For newcomers, I recommend taking a minute to familiarize yourselves with the interface controls via mouse and keyboard. When you are comfortable with the Blender UI, you can click on the cube and press **'H'** to hide it, or use the **'Delete'** key to remove it entirely. 

Next, at the top left, open the menu **'File' --> 'Import' --> 'XYZ (.xyz)'** and find the desired atomic file on your computer. 
With the XYZ file open, your atoms should be visible and you can access the overlay controls at the upper right of the layout screen to turn off visual aids that you don't require for a clean figure (grids, axes, etc).

<figure>
  <img src="{{site.url}}/assets/images/1st.png" alt="The Blender home screen with the overlay menu opened at the top right."/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">Figure 1. The Blender home screen with the overlay menu opened at the top right
  </figcaption>
</figure>

With the scene mostly ready, let's take a minute to familiarize ourselves with the camera controls. This video covers the basics, which are explained step-by-step below. Lighting and rendering is covered in another video at the end of this tutorial.

<iframe width="1551" height="725" src="https://www.youtube.com/embed/BfNCyXAn_dg?si=Ab_7fmpwM6X4pIR1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

1. The camera can be selected by clicking on the wire-frame aperture hovering near your atoms or from the menu on the right-hand side of the screen.  The camera can be adjusted using the move (**'G'**) and rotate (**'R'**) options, with **'X'**, **'Y'**, and **'Z'** keys locking transformations to a particular axis.

<figure>
  <img src="{{site.url}}/assets/images/2nd.png" alt="The Blender camera object."/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">Figure 2. The Blender camera object.
  </figcaption>
</figure>

2. Right-click while the camera is selected and a menu will appear with two options for adjusting the camera, **'Adjust Focal Length'** and **'Adjust Focus Distance'**.  Change these to your satisfaction, and then select **'Set Active Camera'** to make this the camera that pictures will be taken from.

<figure>
  <img src="{{site.url}}/assets/images/3rd.png" alt="The Blender camera options menu."/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">Figure 3. The Blender camera options menu.
  </figcaption>
</figure>

3. With the camera setup done, open the **'View'** drop-down menu at the top of the screen and select **'Viewport Render Image'**, which will open a new window that shows the rendered view through the camera.

<figure>
  <img src="{{site.url}}/assets/images/4th.png" alt="The 'View' menu options."/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">Figure 4. The 'View' menu options.
  </figcaption>
</figure>

4. In the render window at the top left of the screen is an option **'Image' --> 'Save as'**, which will allow you to save the render in your preferred file type and location.  If your camera is too close to the target you can close the viewport render window and adjust the camera before trying again.

<figure>
  <img src="{{site.url}}/assets/images/5th.png" alt="A very close-up view of some atoms through the render window."/>
  <figcaption style="text-align: center; font-style: italic; color: grey;">Figure 5. A very close-up view of some atoms through the render window.
  </figcaption>
</figure>

Now that you are able to take a photo in Blender, you may want to replace the background or change the lighting. Blender has a staggering array of lighting types and interactions. However, detailed lighting is only applied at certain rendering viewports, so switch over to those as in the video below.

<iframe width="1551" height="725" src="https://www.youtube.com/embed/OyoRgz9HqsY?si=ftPAukp1Z3gJtWgU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I also added a **'Plane'** mesh object placed underneath as a background (like a sheet of paper) and assigned it a new white **'Material'** in the 'Material Properties' panel for contrast.  Lastly, the material was given the **'Surface' --> 'Background'** property to get rid of any shadows that might land on it from the atoms themselves.

Remember, a picture is worth a thousand words.

**TODO: Port over the rest of the tutorial from my LinkedIn**

[^1]: Originally posted on my LinkedIn on December 4th, 2023
