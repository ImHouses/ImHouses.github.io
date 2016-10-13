#EVENTS

Events must be defined in a XML with the following structure.

```
<?xml version="1.0" encoding="UTF-8"?>
<event name="EVENT NAME" date="DATE">
  <info>
  <!---- DESCRIPTION --->
  
  </info>
  <guests number="NUMBER OF GUESTS">
    <item id="GUEST ID"
          name="GUEST NAME" 
          <!--- Photo directory --->
          photo="./photos/guests/id.jpg">
  </guests>
  <address>
  <info>
  <!---- HOW TO GET TO THE SPOT ---->
  </info>
  </address>
</event>
```
