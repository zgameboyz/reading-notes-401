# reading-notes-401


## Reading 32 View Components

View components render chunks rather than a whole response. These have the same separation of concerns as the controller and views.

View components have two parts. The first is a class that is derived from the View Component and the result it returns which is typically a view. 

To create a view component class you can derive it from ViewComponent  or decorate a class with the [ViewComponent] Attribute. Clastly you can createa class where the name ends with the suffix ViewComponent.

A view component defines its logic in an InvokeAsync method that returns a Task ```<IViewComponentResult>``` or in a synchronous Invoke method that returns an IViewComponentResult. Parameters come directly from invocation of the view component, not from model binding. A view component never directly handles a request.


[Table Of Contents](README.md)