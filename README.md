# README - Maedina Gold Scalper

This repository contains the code for the Maedina Gold Scalper Expert Advisor. This EA is designed to trade on the XAU/USD (Gold) currency pair. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in the product. To find the official developer of this product, please use the MQL5 website.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [License](#license)

## Introduction

The Maedina Gold Scalper is an Expert Advisor (EA) designed to trade on the XAU/USD currency pair. It utilizes a scalping strategy to take advantage of short-term price fluctuations in the market. The EA opens buy trades when the market is ranging, and calculates the lot size based on the available capital and risk percentage. The maximum number of trades allowed and the maximum lot size can be configured by the user.

## Installation

To use the Maedina Gold Scalper EA, follow these steps:

1. Download the 'mql5' file from this repository.
2. Open your MetaTrader 5 platform.
3. Go to 'File' -> 'Open Data Folder'.
4. Open the 'MQL5' folder.
5. Open the 'Experts' folder.
6. Copy the 'mql5' file into the 'Experts' folder.
7. Restart your MetaTrader 5 platform.

The Maedina Gold Scalper EA should now appear in the list of expert advisors in your MetaTrader 5 platform.

## Usage

To use the Maedina Gold Scalper EA, follow these steps:

1. Drag and drop the Maedina Gold Scalper EA onto the XAU/USD (Gold) chart.
2. Set the desired parameters in the input settings, such as lot size, risk percentage, maximum trades, etc.
3. Make sure that the Auto Trading button is enabled in your MetaTrader 5 platform.
4. The EA will now automatically monitor the market and open buy trades when the conditions are met.

Please note that the EA will only open trades if the maximum number of trades is not exceeded and if the market is ranging.

## Configuration

The Maedina Gold Scalper EA provides the following input parameters for configuration:

- **LotSize**: The initial lot size for each trade.
- **MaxLotSize**: The maximum lot size allowed for each trade.
- **RiskPercentage**: The risk percentage per trade. This is used to calculate the lot size based on the available capital.
- **MaxTrades**: The maximum number of trades allowed at any given time.

## License

This code is licensed under the [MIT License](LICENSE).
