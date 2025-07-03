# Baltimoreans & Their Trash

This project investigates data from the Baltimore's Mr. Trash Wheel, a device that collects trash from the city's waterways. The goal is to understand the types of trash collected and what they reveal about the people of Baltimore.

## Data

The data is sourced from the [Mr. Trash Wheel website](https://www.mrtrashwheel.com/), which provides a comprehensive dataset of the trash collected by the device. The dataset includes various types of trash, their weights, and the dates they were collected. You can access the data directly from the [data](/data/) directory.

## Usage

The entire is analysis is conducted in R, in a Quarto document. You can run the analysis by rendering the document using Quarto:

```bash
git clone https://github.com/SepehrAkbari/trash-wheel.git
cd trash-wheel/src
quarto render trash-wheel.qmd
```

This will generate an HTML report that visualizes the data and provides insights into the types of trash collected and their implications for the community. The rendered results are also available in the [result](/result/) directory.

## Contributing

To contribute to this project, you can fork this repository and create pull requests. You can also open an issue if you find a bug or wish to make a suggestion.

## License

This project is licensed under the [GNU General Public License (GPL)](LICENSE).