# fukui-hotel-data-combined

Combined hotel booking data for Fukui Prefecture tourism nodes, merging two sources:

1. **Rakuten Travel API data** — future hotel availability, pricing, and reviews for our 4 official DHDE tourism nodes (Tojinbo, Fukui Station East, Katsuyama/Dinosaur Museum, Rainbow Line) plus Obama as an additional area.
2. **code4fukui open data** — real historical hotel occupancy and reservation data for the Obama area, sourced from the Fukui Prefectural Tourism Federation's "FTAS" system.

## Features

- Rakuten dataset: hotel name, address, minimum charge, review score, availability by date, per node.
- FTAS dataset: daily reservation counts, number of guests, rooms booked, total revenue, occupancy rate (OCC), average daily rate (ADR), and RevPAR for the Obama area.

## Data Sources

- Rakuten Travel API: https://webservice.rakuten.co.jp/
- code4fukui / obama-kanko-reservation (FTAS open data): https://github.com/code4fukui/obama-kanko-reservation

Credit and thanks to [Code for Fukui](https://code4fukui.github.io/) and the Fukui Prefectural Tourism Federation for making the FTAS data openly available under the MIT License.

## License

This project is licensed under the [MIT License](LICENSE).
