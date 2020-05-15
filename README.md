# Ethereum Address Metadata
## Overview
A collection of metadata files for identifying popular Ethereum addresses. Initially constructed for use in [0x Tracker](https://0xtracker.com), the metadata can be consumed in any application which needs to label Ethereum addresses.

## Usage
Consumption of metadata files is simple due to naming conventions. All metadata files are stored in the _data/{lowercase_address}.json_.

You can use this convention to build to build a URL to fetch from. For example:

[https://raw.githubusercontent.com/0xTracker/ethereum-address-metadata/master/data/0x4aa817c6f383c8e8ae77301d18ce48efb16fd2be.json](https://raw.githubusercontent.com/0xTracker/ethereum-address-metadata/master/data/0x4aa817c6f383c8e8ae77301d18ce48efb16fd2be.json)

Addresses which have no metadata file will simply return a 404.

## Contributing

Contributions to the collection are welcome from anyone. Please follow these steps when opening a PR:

* One PR per metadata file
* PR titles should be in the format:
  * Add metadata for {address}
  * Update metadata for {address}
* If submitting a new metadata file, please include a reference to verify the metadata you've given.
  * e.g. Official project url referencing contract, labeled Etherscan address url, a link to verified source for the contract.

## Used in Applications
* [0x Tracker](https://0xtracker.com) - The leading provider of 0x protocol market data, transparent Ethereum token price index and 0x protocol news aggregator.
