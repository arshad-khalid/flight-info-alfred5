# Flight Info Workflow for Alfred

This script allows Alfred users to quickly retrieve real-time flight information using the AviationStack API.

## Requirements

- **jq** and **curl** (install via Homebrew):
  ```sh
  brew install jq curl
  ```

## Installation

1. Copy the script `flight_info.sh` to your preferred location.
2. Make it executable:
   ```sh
   chmod +x flight_info.sh
   ```
3. Set up an API key from [AviationStack](https://aviationstack.com/) and insert it in the `API_KEY` variable.

## Usage

- Run the script with a flight number as an argument:
  ```sh
  ./flight_info.sh AA123
  ```

This will return the departure and arrival airports, status, scheduled and actual departure times, and delay information.
