Illustrates how to call into a C static library on Windows with `DynamicLibrary.executable()`.

See `ec12d3a4300c19cc79ef825549747d0135ea0a67` for the required diff.

Test with `flutter run -d windows`, click the button, 42 is printed, value comes from a C static library.
