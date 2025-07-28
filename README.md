# SAP-CPI-Groovy-Script-1

# Extract Customer ID from JSON

## Description
Parses an incoming JSON payload and extracts the nested customer ID field.

## Input (Sample JSON)
{
  "customer": {
    "id": "CUST001"
  }
}

## Output
Sets 'customerId' as a property in the message: "CUST001"

## Usage
Use this in iflows where you need to extract specific JSON fields for routing or mapping.
