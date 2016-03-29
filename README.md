<h1>fuse-dropdown</h1>
an attempt at making a little dropdown ui component for fuse to use in my app

So I've just quickly adapted the dropdown example from the repo that I forked this from. Played around with it so it's functional as much as it needs to be now.

<h2>How To Use It</h2>
<p>Put the ux file in your project and to use it just put</p> 
```<DropdownMenu ListItems="{your items observable}" />```
<p>To select the options that you want you need to create an Observable with the name that you referenced to the List property earlier:</p>
```var dropdownOptions = Observable({name: "item1"},{name: "item2"});```
<p>To get the value of the selected item you can use</p>
```
selected.value
```
<p>That's the basics, if you need anything please email me or inbox me</p>
      
  
