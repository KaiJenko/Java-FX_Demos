Java FX Demos

Dr Gary Allen, The University of Huddersfield

A number of Java FX Demo projects for use by students.

Projects named FXML_xxx were created using scene builder to generate fxml files.

Projects named JavaFX_xxx are written 'long hand' coding with the Java FX classes.

NOTE that since Java 1.9 it is now necessary to both:

    import the JavaFX libraries.  At the university this means importing /usr/local/javafx/lib
    edit the run configuration of each program to pass the following VM arguments:  
        --module-path /usr/local/javafx-sdk-11.0.2/lib --add-modules=javafx.controls,javafx.fxml
        (edit the above path as required)

Currently there is:

	a classic HelloWorld (java fx),
	a calculator (java fx),
	a set of pop-up window demos of varying complexity (java fx),
	a TableView demo to show how to display, edit, and add to data in a table (java fx),
	a Table and Pie Chart demo (java fx) 
	    (heavily based upon one found online at:
	    https://stackoverflow.com/questions/23964885/binding-chart-to-tableview-javafx),
    a MenuDemo that shows off menus and a range of components (java fx),
    a CSS Theme switching demo, which changes the theme dynamically at run time,
	a HelloWorld created with scene builder and xfml,
	a CountingButton created with scene builder and xfml,
	a Calculator created with scene builder and xfml,
	a Collections demo using the ListView and ObservableList classes, created with scene builder and xfml,
	an 'Active Interface' demo to show off how to show/hide and enable/disable components at run time.

These may all be updated over time, and other demos may be added.


