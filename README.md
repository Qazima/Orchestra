# Orchestra

Orchestra is a versatile application built with C# .NET Core that allows the execution of code scripts in various programming languages within Docker images.
This application provides the necessary parameters to the scripts and retrieves the results, which can be formatted for end-user presentation or passed on to subsequent scripts.

## Features

- **Multi-language Support**: Execute code scripts written in any programming language.
- **Docker Integration**: Run scripts within Docker containers for isolation and consistency.
- **Result Formatting**: Output results in multiple formats including CSV, XML, JSON, HTML, and graphical representations.
- **Chaining Scripts**: Pass the output of one script as input to another, enabling complex workflows.
- **MongoDB Integration**: Store scripts and their sequencing in a MongoDB database for easy management and scalability.

## Requirements

- .NET Core SDK 3.1 or higher
- Docker
- MongoDB (in a docker image)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Qazima/Orchestra.git
    cd Orchestra/source
    ```

2. Build the application:

    ```bash
    dotnet build
    ```

3. Run the application:

    ```bash
    dotnet run
    ```

## Usage

`pending developments`

## Output Formats

Orchestra supports various output formats. Specify the desired format in the MongoDB document for each script:

- **CSV**: Outputs a CSV file.
- **XML**: Outputs an XML file.
- **JSON**: Outputs a JSON file.
- **HTML**: Outputs an HTML page.
- **Graphical**: Generates graphical representations of the data (e.g., charts).

This list is not exhaustive and will be expanded over time to include more output formats as needed.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE. See the [LICENSE](LICENSE) file for details.

## Contact

Domain name on the way. Stay tuned.

## Thank you ...

... for choosing Orchestra! We hope it enhances your workflow by seamlessly integrating multi-language script execution with versatile output formatting.
