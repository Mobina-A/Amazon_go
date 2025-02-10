# Amazon_go

## Project Overview
This project defines an ontology for a smart retail environment that includes both cashierless stores and traditional stores with cashiers. The ontology uses OWL (Web Ontology Language) and SWRL (Semantic Web Rule Language) to classify customers, stores, and checkout methods based on predefined rules.

### Classification Rules:
1. **Rich Person**: A customer with more than 3 products in their virtual cart is classified as a `RichPerson`.
2. **Cashierless Store**: A store with a `storeCode` starting with "00" is classified as a `CashierlessStore`.
3. **Store with Cashier**: A store with a `storeCode` starting with "11" is classified as a `StoreWithCashier`.
4. **Automated Checkout**: If a `CustomerPerson` is in a `CashierlessStore`, their checkout is classified as `AutomatedCheckout`.
5. **Manual Checkout**: If a `CustomerPerson` is in a `StoreWithCashier`, their checkout is classified as `ManualCheckout`.

## Ontology Details
### Key Concepts & Rules:
1. **Rich Person**: A customer with more than 3 products in their virtual cart is classified as a `RichPerson`.
2. **Cashierless Store**: A store with a `storeCode` starting with "00" is classified as a `CashierlessStore`.
3. **Store with Cashier**: A store with a `storeCode` starting with "11" is classified as a `StoreWithCashier`.
4. **Automated Checkout**: If a `CustomerPerson` is in a `CashierlessStore`, their checkout is classified as `AutomatedCheckout`.
5. **Manual Checkout**: If a `CustomerPerson` is in a `StoreWithCashier`, their checkout is classified as `ManualCheckout`.

## Usage Instructions
### Prerequisites
To view and edit this ontology, you need an OWL ontology editor such as:
- [Protégé](https://protege.stanford.edu/)
- RDF-compatible semantic reasoning tools

### How to Use
1. Open the `.rdf` file in Protégé or an RDF editor.
2. Analyze the defined OWL classes and SWRL rules.
3. Modify or extend the ontology based on your needs.
4. Use reasoning tools to infer classifications based on the predefined rules.
