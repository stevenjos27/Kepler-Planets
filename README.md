# Kepler Planets

This project processes data from the Kepler space telescope to identify potentially habitable exoplanets. It reads data from a CSV file (`kepler_data.csv`) and filters out planets based on specific criteria.

## Criteria for Habitable Planets
- The planet must be confirmed (`koi_disposition` is 'CONFIRMED').
- The insolation flux (`koi_insol`) must be between 0.36 and 1.11.
- The planet's radius (`koi_prad`) must be less than 1.6 times that of Earth.

## Usage
To run the project, use the following command:

```sh
node index.js
```

The script will output the number of habitable planets found based on the criteria above.
