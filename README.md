# contacts

A new Flutter project.

This project demonstrate how state changes with help of ValueNotifier that notify change of value that can hold only one value if it's value changes then by using ValueListenableBuilder we can rebuild some desendent.

Here ContactBook class provide methods to modify the state on calling method notifyListeners in add and remove.

On adding new contact with add method call notifyListeners and changes listen by valueListenable so it rebuild HomePage's view.

For dismissing contact call remove method to notify and rebuilding view.