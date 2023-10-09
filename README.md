# Font Library
The Font Library is a C# DLL that provides easy access to various font families in different styles and weights. This library simplifies font handling within your C# applications, allowing you to easily set fonts for different UI elements.
## Supported Font Families
1.  **Open Sans**
    -   **License:** [Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)
2.  **Poppins**
    -   **License:** [Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)
3.  **Roboto**
    -   **License:** [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
4.  **Roboto Mono**
    -   **License:** [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
5.  **Ubuntu**
    -   **License:** [Ubuntu Font License](http://font.ubuntu.com/ufl/)
## Usage
To get started with the Font Library, follow these steps:
1. **Add the Font Library to Your Project**

   You can add the Font Library DLL to your project as a reference. Make sure to include it in your project's dependencies.
3. **Example usage the Roboto Font Family**

   The Font Library exposes various font families in different styles and weights, making it easy to set fonts for text elements in your application.

   Here's an example of how to use it for the "Roboto" font family:

   ```csharp
   // Simple usage
   using FontLibrary.libRoboto;
   textBox1.Font = Roboto.Black(12F);
   ```
   ou can replace `"Black"` with other styles like `"Bold"`, `"Italic"`, `"Medium"`, `"Regular"`, and so on, according to your design needs.
3. **Enjoy High-Quality Fonts**
   By using the Font Library, you can ensure that your application uses high-quality fonts in a consistent and convenient manner.
## Contribution and Issues
Feel free to contribute to this project or report any issues you encounter. We welcome your feedback and contributions to make this library even better.
## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/korayustundag/fontlibrary/blob/main/LICENSE) file for details.
