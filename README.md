# Flight Info Workflow for Alfred

This script allows Alfred users to quickly retrieve real-time flight information using the AviationStack API.

## Requirements

- **jq** and **curl** (install via Homebrew):
  ```sh
  brew install jq curl
  ```

## Installation

1. Copy the code in the script `flight-info.sh`.
2. Open Alfred Workflow
3. Enter Details
4. Create a Script Filter
5. Set language to /bin/bash
6. Paste Code in the Script Section
7. Set up a free API key from [AviationStack](https://aviationstack.com/) and insert it in the `API_KEY` variable.

## Usage

- Run using your set keyword (mine is "flight") with a flight number as an argument:
  ```sh
  flight QR 3
  ```

This will return the departure and arrival airports, status, scheduled and actual departure times, and delay information.
