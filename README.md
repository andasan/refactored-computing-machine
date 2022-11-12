## Getting Started

Add reference libraries to compatible JavaFX SDK - I have included a folder of 3 different SDK versions for M1 chip macbook.

Replace the path: `"vmArgs": "--module-path PATH/TO/JAVAFXSDK/THATS/INSIDE/THIS/REPOSITORY --add-modules javafx.controls,javafx.fxml"`

Example path: `/Users/francoispolo/Development/Prototype/M1-0922/Kota/demo/sdk/javafx-sdk-19.2/lib`

Connection URL: `jdbc:postgresql://[HOST]:[PORT_NUMBER]/[DATABASE_NAME]`
Please omit the square brackets above `[]`, when you replace with actual values.

### Side note: this is working on my side, using javafx-sdk-19.2
