# Electrical Distribution Network Topological Path Identification (TPI)

This repository contains the code and data used for the identification of customer topological paths in electrical distribution networks. The methodology employs geographic information system (GIS) data and integer linear programming (ILP) optimization to estimate paths from the MV/LV transformer to customers.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Usage](#usage)
- [Data](#data)
- [Requirements](#requirements)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Topological path identification (TPI) is crucial for the digitalization, analysis, and planning of electrical distribution networks. This repository presents an innovative approach to tackle the challenge of TPI using only the data available to distribution system operators (DSOs).

## Methodology

The methodology involves the following steps:
1. **Data Preparation:** Transform raw data into well-defined information.
2. **Hypothetical Path Identification:** Generate a set of possible paths using GIS data.
3. **Optimization:** Apply an ILP optimization algorithm to find the paths that closely match the real paths.

For more detailed information, refer to the paper [here](link-to-paper).

## Usage

To run the TPI process, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/repo-name.git
   cd repo-name
