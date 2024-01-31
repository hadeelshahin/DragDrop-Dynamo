"# DragDrop-Dynamo" 



https://github.com/hadeelshahin/DragDrop-Dynamo/assets/106568841/c9191f86-c580-4f19-997c-d1815ea9e169



The project involves the implementation of the draggable HTML attribute, which allows elements to be interactively moved by users through dragging. This attribute takes a Boolean value, either true or false, indicating whether the element is draggable. It is often employed in conjunction with JavaScript to enable drag-and-drop functionality. JavaScript event handlers like ondragstart, ondragover, and ondrop are utilized for controlling and customizing the drag-and-drop behavior.

Additionally, the project incorporates the use of the dataTransfer object in the Drag and Drop API. This object facilitates the transfer of data between the source (dragged element) and the target (drop zone) during drag-and-drop operations. The dataTransfer object has methods like setData(format, data) for setting the data to be transferred, where format specifies the type of data, and data is the actual content.

The effectAllowed property of the dataTransfer object is employed to specify the allowed drag-and-drop operation effects. It is set during the dragstart event and can have values like "copy," "move," "link," or combinations such as "copyMove."

The dragenter and dragover events are part of the Drag and Drop API and are triggered when the dragged element enters and hovers over a potential drop target. These events are utilized for applying visual feedback, performing setup, or controlling the drop based on the element's position.

To prevent the default behavior of dragover and drop events, the event.preventDefault() method is employed. This is crucial for enabling dropping, as browsers, by default, do not allow dropping elements into other elements. Preventing the default behavior allows for more control over the drag-and-drop behavior, enabling the implementation of custom logic for handling the drop.
