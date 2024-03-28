# List UI Node

This node helps to create a list of elements.&#x20;

This node is used for providing the data to the list dynamically and for adding logic to various events. The main purpose of the node is to populate the list of items that you want to show repeatedly.

### How to get List UI Node.

![](../../../.gitbook/assets/listview-.gif)

For creating a new List first you have to create a single element \[repetitive element] of the list, this can be a single rectangle, text or a group with multiple items in it. The process remains the same for all types of list except when list element consists of a single rectangle or text then only one item widget is going to be generated while list node is created, but if the single list element consists of multiple items like a group then the number of item widget that going to be associated with list node is equal to the number of items present in the single group.

After the list element is created convert it to the list by clicking on the convert to list button in the properties panel, then select the list created and right-click on the list and choose  "edit in blup lightning" in the arsenal .

As soon as you do that a listview node is generated in the blup lightning which consists of an automatically generated item widget based on the number of items in a single element of the list.

### Components of List UI node

<table><thead>
    <tr>
      <th>Component</th>
      <th>Description</th>
    </tr>
  </thead><tbody><tr><td><strong>Is Update</strong></td><td>This input node point is used to define whether the children are to be updated dynamically or not, this node point accepts a Boolean type value.</td></tr><tr><td><strong>Item count</strong></td><td>Item count input node point defines the total number of items to be had on the list.</td></tr><tr><td><strong>Is hide</strong> </td><td>This input node point helps to hide the list. </td></tr><tr><td><strong>Item Widget</strong></td><td>These input node points are dynamically generated based on the number of items present in the single element in the list.</td></tr><tr><td><strong>Extra Data</strong></td><td>This input node points help to store data. which can be used in further cases.</td></tr><tr><td><strong>Width</strong></td><td>This input node point helps to define the width of the list.</td></tr><tr><td><strong>Height</strong></td><td>This input node point helps to define the height of the list.</td></tr><tr><td><strong>Padding Left</strong></td><td>This node point helps to give the left padding.</td></tr><tr><td><strong>Padding Right</strong></td><td> This node point helps to give the Right padding.</td></tr><tr><td><strong>Padding Top</strong></td><td>This node point helps to give the Top padding.</td></tr><tr><td><strong>Padding Bottom</strong></td><td>This node point helps to give the Bottom padding.</td></tr><tr><td><strong>Grid Row Count</strong></td><td>This input node point can be used to convert the list into a grid list. If the value of this property is one then it is a simple list but if we increase the value of let's say to 2 it becomes the grid list with two-column.</td></tr><tr><td><strong>Item Spacing</strong> </td><td>This property helps to define the spacing [vertical height] between the list items. Higher the value of item spacing greater the vertical height between the item in the list and vice versa.</td></tr><tr><td><strong>Grid Spacing</strong></td><td>This property helps is used to define the horizontal spacing between the grid items. Note - The property only going to works when we have a grid, not a list.</td></tr><tr><td><strong>Item Aspect Ratio</strong></td><td>Aspects ratio is the ratio between the width and height of the item, the greater the value of this property smaller the vertical spacing between them and the smaller the item gets.</td></tr><tr><td><strong>Iterator</strong></td><td> This output node point provides the current index of the list.</td></tr><tr><td><strong>Scroll Listener</strong> </td><td>This output node point provides you the scroll pixels.</td></tr><tr><td><strong>On Bottom Reached</strong></td><td>This output node point helps to perform any logic when the list reaches the bottom [last element in list].</td></tr><tr><td><strong>On Top Reached</strong> </td><td>This output node point helps to perform any logic when the list reaches the top [first element in list].</td></tr><tr><td><strong>On Scroll Up</strong> </td><td>This output node point is used to perform any logic when the user scrolls up.</td></tr><tr><td><strong>On Scroll Down</strong> </td><td> This output node point helps you to perform any logic when the user scrolls down.</td></tr><tr><td><strong>On default prop update</strong></td><td><p> This output node point as the name suggests helps you to run any logic when any primary input node points [primary properties ] changes.</p><p>Also if you stretch the node point it will give you the properties values that are present on the left-hand side of the rectangle node.</p></td></tr><tr><td><strong>On Extra prop Update</strong></td><td>This output node point helps to define logic when these secondary properties are changed. Change also similar to above node point stretch this node point further will help you to get more output node points.</td></tr></tbody></table>

<div class="container">
  {% tab title="Music" %}
  {% embed url="https://open.spotify.com/playlist/0vvXsWCC9xrXsKd4FyS8kM?si=2c7f55bd3f944878" %}
  Lofi music
  {% endembed %}
  {% endtab %}
  {% endtabs %}
</div>
