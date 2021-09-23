**UMIP #**  - tbd

-   **UMIP title:** Add **AthleteX DAO** as collateral currency 
-   **Author**  AthleteX DAO (athletexmarkets@gmail.com)
-   **Status: Draft**
-   **Created:**  9/23/2021
-   **Discourse Link:**  https://discourse.umaproject.org/t/whitelist-ax-as-collateral/1250

## Summary

This UMIP proposes adding **AX** for use as collateral in UMA contracts.

## Motivation

The addition of this collateral currency offers additional functionality to the UMA protocol and increases the range of contracts that can be built.

## Technical Specification

To accomplish this upgrade, the following changes need to be made:

-   The **AX** address **0x5617604BA0a30E0ff1d2163aB94E50d8b6D0B0Df (https://polygonscan.com/address/0x5617604BA0a30E0ff1d2163aB94E50d8b6D0B0Df)** needs to be added to the collateral currency whitelist introduced in UMIP-8.
-   A final fee of **5,000** needs to be added for **AX** in the Store contract.
    

## Rationale

This store fee was chosen as it is approximately equivalent to $400 in line with other collateral currencies as determined by **taking the # of coins multiplied by .08 (community sale price) = 400**

## Implementation


This change has no implementations other than the aforementioned governor transactions

## Security considerations

Adding a collateral currency introduces a level of risk into the UMA Ecosystem.  This collateral type should be monitored to ensure that the proposed collateral continues to have value.

Contract deployers considering using this collateral in an UMA contract should refer to the [guidelines on collateral type usage](https://docs.umaproject.org/uma-tokenholders/guidence-on-collateral-currency-addition) to ensure appropriate use.


