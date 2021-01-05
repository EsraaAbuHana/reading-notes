# Controlling the position of elements
## Definition and Usage
> The position property specifies the type of positioning method used for an element (static, relative, absolute, fixed, or sticky).
# *Block-level elements*
- A block-level element always starts on a new line and takes up the full width available
![](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)
# *Inline Elements*
- An inline element does not start on a new line and it only takes up as much width as necessary.
- * - here  some block and inline elements in the html 
# ![](https://www.differencebetween.com/wp-content/uploads/2018/02/Difference-Between-Block-and-Inline-Elements-fig-1.png)
# Containing Elements
## The size and position of an element are often impacted by its containing block
# ![](https://www.unm.edu/~tbeach/IT145/week08/images/boxmodel.gif)
## * When a user agent (such as your browser) lays out a document, it generates a box for every element. Each box is divided into four areas:*
- Content area
- Padding area
- Border area
- Margin area
#
# The position Property
> The position property specifies the type of positioning method used for an element.
> 
## There are five different position values:
* static
* relative
* fixed
* absolute
* sticky
- Example :
###Example###
> div.fixed {
>  position: fixed;
>  bottom: 0;
>  right: 0;
>  width: 300px;
>  border: 3px solid #73AD21;
> }
# Clearing Floats
clear
# What is “Float”?
_ Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called “text wrap”. Here is an example of that.
## Techniques for Clearing Floats
- The Empty Div Method is, quite literally, an empty div. <div style="clear: both;"></div> . ...
- The Overflow Method relies on setting the overflow CSS property on a parent element. ...
- The Easy Clearing Method uses a clever CSS pseudo selector ( :after ) to clear floats.

#

##
Difference Between Fixed And Fluid Layouts
Although most designers and developers would consider defining fixed and fluid website layouts to be elementary, we’ll go over it just to be clear.
# FIXED WEBSITE LAYOUTS
- A fixed website layout has a wrapper that is a fixed width, and the components inside it have either percentage widths or fixed widths
# ![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/c3ccabfb-1f1d-42f8-b3a6-f0dca9679655/fixed.jpg)
# FLUID WEBSITE LAYOUTS
- In a fluid website layout, also referred to as a liquid layout, the majority of the components inside have percentage widths, and thus adjust to the user’s screen resolution.
# ![](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/6bfc16df-3bb6-42b2-9076-7a8f4daef4d2/fluid.jpg)
