# Mother Nature Cli

This is a simple weather application written in Go. It retrieves weather data from the [WeatherAPI](https://www.weatherapi.com/) service.

## Setup

### Prerequisites

Before running the application, ensure you have the following installed:

- Go programming language (version 1.16 or higher)
- Git

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/dev-jolo/mother-nature-cli.git
    ```

2. Navigate to the project directory:

    ```bash
    cd mother-nature-cli
    ```

3. Install dependencies:

    ```bash
    go mod tidy
    ```

### Configuration

1. Sign up for a free account at [WeatherAPI](https://www.weatherapi.com/) to obtain an API key.

2. Create a `.env` file in the root directory of the project:

    ```bash
    touch .env
    ```

3. Add your WeatherAPI API key to the `.env` file:

    ```plaintext
    WEATHER_API_KEY=your_api_key_here
    ```

### Building the Application

Run the following command to build the application:

```bash
go build -o mother-nature-cli cmd/weather/main.go
```

### Running the Application

After building the application, you can execute it with:

```bash
mother-nature-cli
```

### Adding to PATH (Optional)
To run the application from any directory without specifiying the path, you can add the directory containing the `mother-nature-cli` (or `mother-nature-cli.exe` on Windows) executable to your system's APTH environment Variable.

### Usage
After running the application, you will be prompted to enter the location for which you want to retrieve weather data. If no location is provided, the default location is used.




