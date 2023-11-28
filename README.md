### Chinese Zodiac Animals w Spinning Wheel and Slider
​
This **Chinese Zodiac Animals Wheel** project is an educational interface where the 12 animals of the Chinese Zodiac are generated dynamically, using JavaScript. 
- The application uses a dataset, **zodiac-animals-data.js**, which consists of an **array** of 12 **objects**, one per animal.
- The **renderAnimals()** function, which runs on **DOMContentLoaded**, iterates over the array of 12 animal objects.
- Each iteration, makes a div for the current animal. 
- Inside each animal div go several elements, including images and text. These are all generated, dynamically in the JS loop.
- The **sound icon** when clicked plays an **mp3** audio file of the animal being spoken in both English and Chinese. 
- The **sort menu select element** lets the user sort the animals by **English name, Chinese name** or **Year**.
The **Descending checkbox** toggles the sort order between ascending-descending.
- The **spinning wheel** depicts the 12 animals of the Chinese Zodiac. The **animation** is handled by **setInterval(callback, delay)** which runs a function on a 25 ms delay  (40x per sec), which rotates the wheel by the wheel spedd each time the function in invoked. 
- The **slider control** (input element of type **range**) calls a function every time the slider is changed. The function sets the wheel speed.
