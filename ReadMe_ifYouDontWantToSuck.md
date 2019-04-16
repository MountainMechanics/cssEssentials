<h1>Docmumentation</h1>
<h5>Purpose of this Project</h5>
<article>
These CSS classes are made for anyone that is too lazy to write their own Styles
</article>

<h3>
CSS classes
</h3>
<h4>
Basic-CSS
</h4>

This File holds "basic" CSS-classes that are used for arranging content within the Page responsively and naturally

<h5>
Fonts
</h5>

>.font-basic <br>
>applies a basic font-layout which is shown in the demo<br>
>Font: Open-sans sans-serif <br>
>weight: auto

>.font-header <br>
>applies a header-specific font-layout which is shown in the demo <br>
>Font: Work-sans sans-serif <br>
>weight: bold

<h5>
Cards
</h5>
Cards are basically anything you want them to be, but they are intended as an easy container to display content like text, pictures or sold goods.

>.card<br>
>displays content semi-responsively
>it does adjust width and height according to the content and the amount of cards in a row, but it doesnt wrap automatically if the screen is too small (maybe a future feature idk) <br>
>other than that:
>* border: lightgray 1px solid;<br>
> to give a basic border nothing special really
>* transition: 0.25s transform, box-shadow ease-out;<br>
> provides good animation if you use .animate on the same object
>* box-shadow: none;

>.animate<br>
>intended for use with .card, to add some visual flair during a hover<br>
>it uses:<br>
>*transform: translateZ(5px) translateX(3px) translateY(-3px);<br>
>*box-shadow: -3px 3px 7px -3px rgba(0, 0, 0, 0.25);<br>

