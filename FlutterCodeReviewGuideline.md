The following aspects are considered to ensure good quality and high performance deliverables

### Naming conventions followed
* Classes, enums, typedefs, and extensions name should in UpperCamelCase
* Libraries, packages, directories, and source files name should be in snake_case(lowercase_with_underscores)
* Variables, constants, parameters, and named parameters should be in lowerCamelCase.
* Proper meaningful names should be followed.
* Private variables names preceded with underscores

 ### Proper folder structure followed
* Segregation of code into a proper folder structure namely providers, models, screens/pages, utils.
* Code is properly formatted with trailing commas used appropriately.
* Adequate comments added for documentation.
* Try to make code reusable with help of helper functions in utility files saved in the utils folder.
* Widgets should also be designed to be reusable and can be saved in a widgets folder separately.
* Avoiding static/hard coded strings in the UI screens. Constants should be derived from a single place including color codes, validation messages etc. all saved in the constants file.
 
 ### Widget structure and usage
* When working with infinite lists or very large lists, ListView builder is used in order to improve performance
* Split the widget into different Widgets.
* When setState() is called on a State, all descendent widgets will rebuild. Therefore, Split widget into small widgets so the setState() call rebuilds only the part of the subtree, whose UI actually needs to change.

### Follow Linting rules
* Use Const in Widgets
* You can cache parts of your widget tree to prevent unnecessary rebuilds.
* The easiest way is to use dart const constructors for parts of the child tree whichwill not change. The widget which will not change when setState is called, we should define it as 

### Check for boundary cases and handle layout overflows properly
* The widgets should take care of responsiveness of the application.
* Use of widgets which will handle screen overflows like Expanded to avoid overflow errors.

### Build method structure
* The build method should be pure, without any side effects. This is because, it may be triggered by many external factors, such as:
     -  Route pop/push, 
     -  Screen resize, usually due to keyboard appearance or orientation change
     - Parent widget recreated its child
     - An InheritedWidget the widget depends on (Class.of(context) pattern) change
* The build method should not have any logic to trigger an http call or modify any state.

### Using Third party packages
* Validate any third party package being used in the application as sometimes it might break the build or not be in sync with the current flutter version. This is especially required when you are upgrading flutter, so make sure to check all your plugins and third party packages after upgrade.







