# Web_Dev_Dump
This is a simple webpage made using html and css.
## Media Query Usage
<h2>For devices having width: 400px < w < 990 px </h2>
<ul>
  <li>The <b>display</b> of the elements of <b>row</b> class is set to <b>block</b> type. In order to get the elements of the div in next line. </li>
  <li>The <b>flex<b> attribute is set to 1 in order to set flex-grow: 1 , flex-shrink:1 and flex-basis: 0, so that the elements of the nav bar take equal spacing.</li>
</ul>                                      



<h2>For devices having width: <=400px <br></h2><ul><li> The padding of the wrapper(contains icons of github,yt,...) class is set to <b>0.75vh 0vw.</b></li>
<li>The line-height,font-size of the icons is also altered in the profile card so as to fit to the minimized screen.</li> 
<li><b>Flex</b> attribute is set to 100% in order to get the profile card at the bottom of the description text </li>
<li><b>Overflow</b> attribute is set to hidden.</li>
</ul>


## Flex Box Usage
<h2>
Flex box is used upon the contents of</h2>
<ul>
  <li>Navigation Bar<br><p>Flex attribute of nav's is set to 1<br>The display of the elements of navigation bar are set to inline</p></li>
  <li>Profile Card<br><p>The display of the profile card's icons is also set to <b>inline-flex</b></p></li>
  <li>Wrapper Class<br><p>The individual icons are also contained inside the flex box</p></li>
</ul>
