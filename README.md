"# Locker-Bank-Layout" 

Added Model classes Root, Column & Locker  for reading from the layout.json file.

On the HomeController Index() action after reading the entire layout.json file, deserialized json string to model objects.

Then returned the jsonModel to the View(Index.cshtml).

There listed the locker objects using Bootstrap styling.

Made the selection of individual lockers using event handler and jQuery.
