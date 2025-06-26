# IT Companies Catalogue
[![XML](https://img.shields.io/badge/XML-1.0-blueviolet.svg)](https://www.w3.org/XML/) [![DTD](https://img.shields.io/badge/DTD-Document%20Type%20Definition-darkpurple.svg)](https://www.w3.org/TR/REC-xml/#dt-doctype) [![XSLT](https://img.shields.io/badge/XSLT-Extensible%20Stylesheet%20Language%20Transformations-red.svg)](https://www.w3.org/TR/xslt/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Theme 09 from `docs/task-condition.pdf` file. This project is a catalogue of IT companies in Bulgaria, organized by region and described using XML, DTD, XSLT, and XSL-FO technologies.

## Structure
- `data/` - XML files describing companies
- `dtd/`  - DTD schema(s) for validation
- `xslt/` - XSLT stylesheets and XSL-FO templates
- `output/` - Generated PDFs and other output
  
## Features
- **XML-based catalogue:**  
  Structured storage of Bulgarian IT companies by region, including both textual and graphical information about each company.
- **Graphical content and links:**  
  Graphical content is represented via XML entities, while relationships and references use ID/IDREF attributes.
- **DTD validation:**  
  The catalogue structure and data are validated using a custom-built DTD.
- **XSLT & XSL-FO transformation:**  
  Automated generation of styled (PDF) documents from XML using XSLT and XSL-FO.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss your ideas.

## License
This project is licensed under the MIT License.

## Contact
For questions or suggestions, please open an issue or contact [monnicam88](https://github.com/monnicam88).
